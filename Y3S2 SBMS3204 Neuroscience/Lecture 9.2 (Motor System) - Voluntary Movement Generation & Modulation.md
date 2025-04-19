Lecture Notes

**Lecture Coverage:**
- Generation of Voluntary Movement
- Motor Execution
- Modulation of Voluntary Movement

---
#### **Generation of Voluntary Movement**
**Pathway of Signal Transduction**

|     CNS Region      | Function                                                      |
| :-----------------: | ------------------------------------------------------------- |
|    Motor Cortex     | Planning & Executing Voluntary Actions                        |
| Corticospinal Tract | Primary Descending Pathway<br>90% Cross to Contralateral Side |
|    Basal Ganglia    | <br>Modulate Motor Output                                     |
|     Cerebellum      | ^                                                             |
| Spinal Motoneurons  |                                                               |

**Stages of Signal Generation**

|       Stage        | Description                                                               |
| :----------------: | ------------------------------------------------------------------------- |
|  Formulating Goal  | Decide what needs to be achieved                                          |
| Movement Planning  | Planning the end-effector trajectory                                      |
| Inverse Kinematics | Compute Joint Angle Patterns to achieve Trajectory                        |
|  Inverse Dynamics  | Compute Joint Torques & Muscle Activation to achieve Joint Angle Patterns |
|  Motor Execution   | Send Commands to Muscles for Motion Generation                            |


#### **Motor Execution**
- 2 Modes: Feedforward / Feedback Motor Control

**Feedforward Motor Control (Open-Looped)**
- Uses the Corticospinal Descending System
- Pre-planned Commands Sent to Muscles without Regard to Sensory Feedback during Movement
	- → Fast & Efficient for well-trained tasks
	- → Can't correct for unexpected errors during execution
- Population Vector Hypothesis: Movement direction is encoded by combined activity of a large motor cortex neuron population
	- → Rapid & Direct generation of feedforward commands

**Feedback Motor Control (Close-Looped)
- Uses the Cortico-cerebellar Loop
- Detect Deviations from Desired State of Movement through Sensory Information
	- Accurate & Adaptable but Slower
	- → Adjustments in Motor Command to Correct the Movement


#### **Modulation of Voluntary Movement**
- Carried out by Cerebellum & Basal Ganglia
- Essential for Movement Correction in Feedback Motor Control

**Cerebellum**
- Refiner of movement in coordination, timing, accuracy & motor learning
- Functional Zones:

|   Functional Zone   |                         Input Source                          |                  Output Destination                  |
| :-----------------: | :-----------------------------------------------------------: | :--------------------------------------------------: |
|   Spinocerebellum   | Motor & Somatosensory Cortex<br>Prioperceptive Spinal Neurons | Brainstem Nuclei & Motor Cortex → Spinal Neurons<br> |
| Vestibulocerebellum |                       Vestibular Nuclei                       |                          <                           |
|  Cerebrocerebellum  |                (Pre)motor & Association Cortex                |                          <                           |

**Basal Ganglia**
- Selects Appropriate Motor Strategies
	- Facilitates Initiation of desired movements & Inhibition of undesired movements
	- Habitual Motor Sequences
- 2 Main Pathways in Cortico-Basal-Ganglia Loops to Communicate with the Cortex:
	- Dopamine excites the Direct pathway & inhibits the Indirect pathway → Movement Promotion

|         Pathway          | Thalamus / Cortex State  |
| :----------------------: | :----------------------: |
|   Direct Pathway (Go)    |  Excitation → Movement   |
| Indirect Pathway (No-go) | Inhibition → No Movement |
