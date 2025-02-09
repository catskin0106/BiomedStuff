Lecture Notes

**Lecture Coverage:**
- Overview of Visual System
- Neural Circuits in the Retina
- Circuitry of the Antagonistic Receptive Field Structure
- Photoreceptor Spectral Sensitivity

---
#### **Overview of Visual System**

| Stage               | Compartment           | Function                                                                                                                                                                                                                                                                    |
| ------------------- | --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <br>Light Gathering | <br>Cornea & Lens<br> | Provide Optical Power (≈ 59D) & Focus 2D Images onto Retina:<br>  - Cornea: Majority of Optical Power<br>  - Lens: <abbr Title="Due to being suspended in aqueous humour">Minor</abbr> but <abbr Title="Due to Ciliary Muscles">Adjustable</abbr> Optical Power (up to 14D) |
| Light Detection     | Photoreceptor         | Transduction of Incident Photons into Electrochemical Signals                                                                                                                                                                                                               |
| Neural Processing   | Neural Circuits       | <abbr Title="Higher visual complexity are detected further up the hierarchy">Hierarchical Feedforward Processing</abbr> of Visual Signals                                                                                                                                   |


#### **Neural Circuits in the Retina**
**Neuroanatomy of the Retina [(Diagram)](3204_RetinaNeuroanatomy.png)**

|                     Layer                      | Description                                                                                                                                     |
| :--------------------------------------------: | ----------------------------------------------------------------------------------------------------------------------------------------------- |
|   <abbr Title="Pigment Epithelium">PE</abbr>   | Retina-Choroid Barrier for Light Absorption & Homeostasis                                                                                       |
|     <abbr Title="Photoreceptors">PR</abbr>     | Cone & Rod Cells: Mediates Phototransduction                                                                                                    |
| <abbr Title="Outer Plexiform Layer">OPL</abbr> | <abbr Title="Horizontal Cells">HC</abbr>: Relays OPL signal horizontally                                                                        |
| <abbr Title="Inner Plexiform Layer">IPL</abbr> | <abbr Title="Amacrine Cells">AC</abbr>: Relays IPL signal horizontally                                                                          |
|  <abbr Title="Ganglion Cell Layer">GCL</abbr>  | <abbr Title="Retinal Ganglion Cell">RGCs</abbr>: Receives signal from PR through <abbr Title="Bipolar Cells">BC</abbr> & Fires Action Potential |

**PR: Phototransduction**
- Photochemistry Processes

| Step  | Description                                                                                                            |
| :---: | ---------------------------------------------------------------------------------------------------------------------- |
| <br>1 | Light activation<br>  - Rod: Rhodopsin → Metarhodopsin-II<br>  - Cone: Cone Opsin → Metarhodopsin-II-like Intermediate |
|   2   | Meta-II splits Transducin αβγ → Transducin α & βγ                                                                      |
|   3   | Transducin α activates <abbr Title="Phosphodiesterase">PDE</abbr>                                                      |
|   4   | PDE Hydrolyzes cGMP → 5'-GMP                                                                                           |
|   5   | cGMP ↓ → <abbr Title="Cyclic Nucleotide-gated">CNG</abbr> cation channels close<br>  ∴ Cation Influx ↓                 |
- Electrophysiological Processes

| Step  | Description                                                                                                                                                                                                                                                                                                                                                                |
| :---: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1   | Cation Influx ↓ → Hyperpolarization                                                                                                                                                                                                                                                                                                                                        |
|   2   | Voltage-gated Ca²⁺ Channels close<br>∴ Cell Ca²⁺ ↓                                                                                                                                                                                                                                                                                                                         |
| <br>3 | Synapse Glutamate Release ↓<br>  - ↓ <abbr Title="Metabotropic">m</abbr>GluR6 Activation on ON BC → ↑ <abbr Title="Allows Cation Influx">TRPM1 Opening</abbr> → ON BC Depolarization<br>  - ↓ <abbr Title="Ionotropic">i</abbr>GluR Activation on OFF BC → OFF BC Hyperpolarization<br>  - ↓ <abbr Title="Ionotropic">i</abbr>GluR Activation on HC → HC Hyperpolarization |
-  Photoreceptors: Only type of Primary Sensory Neuron to Hyperpolarize in response to Stimulus

**BC: Parallel Pathways**
- Bipolar Cell Transmission Processes [(Diagram)](3204_BCPathways.png)

| Signal Type | Pathway                                |
| ----------- | -------------------------------------- |
| Rod ON      | Rod BC → AII AC → Cone ON BC → ON RGC  |
| Rod OFF     | Rod BC → AII AC → Cone OFF BC & ON RGC |
| Cone ON     | Cone ON BC → ON RGC                    |
| Cone OFF    | Cone OFF BC → OFF RGC                  |


#### **Circuitry of the Antagonistic Receptive Field Structure ([Video](https://www.youtube.com/watch?v=9ptnmfpDThk))**
- By Horizontal Cells connecting to Centre & Surrounding Cones

| Step | Event                                          |
| :--: | ---------------------------------------------- |
|  1   | HC Stimulated by Glutamate → Release more GABA |
|  2   | ↑ PR GABAR Conductance & Cl<sup>-</sup> Influx |
|  3   | PR Depolarization & ↓ Glutamate Release        |
 - i.e. Strength of HC Inhibition of Glutamate Release ∝ Area of Darkness in the Light Pattern


**Light Pattern and RGC Output**

|                                     Light Pattern                                     |                                ON RGC Output                                 |            Off RGC Output            |
| :-----------------------------------------------------------------------------------: | :--------------------------------------------------------------------------: | :----------------------------------: |
| Centre <span style="color:red">Off</span>-Surround <span style="color:red">Off</span> |           ![[Pasted image 20250131054327.png]]<br>(Baseline Rate)            |                  <                   |
| Centre <span style="color:lime">On</span>-Surround <span style="color:lime">On</span> | ![[Pasted image 20250131055454.png]]<br>(Slightly Higher than Baseline Rate) |                  <                   |
| Centre <span style="color:lime">On</span>-Surround <span style="color:red">Off</span> |                     ![[Pasted image 20250131055601.png]]                     | ![[Pasted image 20250131055633.png]] |
| Centre <span style="color:red">Off</span>-Surround <span style="color:lime">On</span> |                     ![[Pasted image 20250131055635.png]]                     | ![[Pasted image 20250131055601.png]] |


#### **Photoreceptor Spectral Sensitivity**
**Types of Photoreceptors**

| Photoreceptor        | Rod Cell                                                                                                                              | Cone Cell (<abbr Title="S,M,L">3 Types</abbr>)                         |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| Vision Type          | <abbr Title="Dim Light Vision">Scotopic Vision</abbr>                                                                                 | <abbr Title="Colored Vision under Bright Light">Photopic Vision</abbr> |
| Distribution         | Central fovea                                                                                                                         | Everywhere else (Except Optic Disc)                                    |
| Convergence into RGC | Higher (Many AII AC : 1 RGC)<br>  ∴ <abbr Title="Have Signal as long as 1 Rod detects light">High Sensitivity</abbr> & Low Resolution | Lower (1 Cone : 1 RGC)<br>  ∴ Low Sensitivity & High Resolution        |

**Structural Optimization of Fovea**
- More Detector Units with Low convergence → Higher Resolution
- Reduction of Light Scattering → Higher Sensitivity
	- Thinnest Part of Retina (Other components laterally displaced)
	- Lack of Blood Vessels


**Parallel Pathways for Luminance & Color Opponency**
- All have antagonistic receptive field structure
	- ON / OFF parallel pathways
	- Centre-Surround organization

|    Pathway    |    RGC Involved    |                    Function                    |
| :-----------: | :----------------: | :--------------------------------------------: |
| Magnocellular |   Parasol Cells    |                   Luminance                    |
| Parvocellular |    Midget Cells    |            Red-Green Discrimination            |
| Koniocellular | Bistratified Cells | Blue-Yellow Discrimination<br>Light & Contrast |
