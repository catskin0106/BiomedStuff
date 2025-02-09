Lecture Notes

**Lecture Coverage:**
- Nature of Sound
- Ear as Frequency Analyzer
- The Auditory Pathway

---
#### **Nature of Sound**
- Longitudinal pressure wave propagated through mediums (e.g. Air)
	- Represented by Vibrations of Mass-Spring Systems:
		- Vibration rate ∝ √Stiffness
		- Vibration rate ∝ 1 / Weight
- Can be bounced back in Resonant Cavities → Echo
	-  Resonance Frequency ∝ √Cavity Volume

**Fourier Transform in Periodic Sounds**
-  Real world Sounds are "Addition" of Sine Waves in a Amplitude to Time Graph
	- Can be interpreted as a "riddle image" that requires combining different sine functions (answers) together to produce that image
- Harmonics
	- Frequency components that are integer multiples of the fundamental frequency
		- E.g. Middle A=440Hz while All As has a fundamental frequency of 27.5Hz (1/16)
	- Overtones: Not necessarily frequency components
- Formants
	- Concentration of <abbr Title="Speaking, NOT SINGING where pitch is changed">Acoustic Energy</abbr> where a Specific Frequency is Amplified ("Mountain Ranges" in a Spectrogram)


#### **The Ear as a Frequency Analyzer**
- Ear performs Time-Frequency Analysis of Incoming Sounds
	- Place Code: Frequency (Tonotopy)
	- Rate Code: Intensity
	- Time Code: Temporal Structure (Fine Structure)

**Structure of the Cochlea**
- Coiled Canal from Stapes / Oval Window to Round Window
- Basilar Membrane: The Middle "Wall" of the Cochlea
	- Provides 2 Routes for sound detection through Basilar Membrane Deflection
	- Stiff base (Inner Coils): High frequency sounds
	- Floppy apex (Outer Coils): Low frequency sounds
- Organ of Corti: Site of Sound Transduction at Hair Cells
	- Outer Hair Cells: Mechanical Feedback Amplify Vibrations in a Tuneable State
	- Inner Hair Cells: Transmits Frequency Signal into Nerve Fibres
		- Tip Links: Stretch between Stereocilia to Stretch K<sup>+</sup> Channels for depolarization upon sound deflection

**Place Coding in Frequency Analysis: Tonotopy**
- Different neurons on the Basilar Membrane has their own sensitivity towards different frequencies of sound
	- Crudely produces a "spectrogram" of perceived sounds where different neurons occupy different frequency bands (y values)
	- → Excitation of particular places give rise to respective pitch

**Time Coding in Frequency Analysis: [Phase Locking](https://www.cns.nyu.edu/~david/courses/perception/lecturenotes/pitch/pitch.html)**
- Phase Locking: Pitch are partially coded by firing rate of neurons with soundwave mimicry (i.e. Frequency ∝ Firing Rate)
	- Volley Principle: Although the firing pattern of a single neuron won't have a diversity to code for 20-20k Hz, <abbr Title="maybe 20">many</abbr> neurons jointly will have the diversity to do so


#### **The Auditory Pathway**
**Tonotopy of the Cochlear Nucleus**
- Base Basilar Membrane → Medial Cranial Nerve
- Apex Basilar Membrane → Lateral Cranial Nerve

**Ascending Auditory Pathway**

| Structure                         | Step  |   Location    |                                              Remarks                                              |
| --------------------------------- | ----- | :-----------: | :-----------------------------------------------------------------------------------------------: |
| Cochlear Nuclei (CN)              | 1     | <br>Brainstem | <br><br>CN, SOC, & NLL can send signals downstream to IC by either a step-wise or skipping manner |
| Superior Olivary Complex (SOC)    | 2     |       ^       |                                                 ^                                                 |
| Nuclei of Lateral Lemniscus (NLL) | 2/3   | <br>Midbrain  |                                                 ^                                                 |
| Inferior Colliculus (IC)          | 2/3/4 |       ^       |                                                 ^                                                 |
| Medial Geniculate Body (MGB)      | 5     | <br>Thalamus  |                                                 /                                                 |
| Cortex                            | 6     |               |          Mammals often have >2 Primary & Multiple Higher Order Auditory Cortical Fields           |


#### **Hearing Loss and Treatment**
**Hearing Loss**
- Conductive
	- Tympanic Membrane
	- Ear Canal Occlusion
	- Otitis Media (Fluid in Middle Ear)
	- Otosclerosis (Ossicle Classification)
- Sensory-Neural
	- Hair Cell Damage due to:
		- Innate Vulnerability / Old Age
		- Noise
		- Ototoxic Drug
	- Damage to Auditory Nerve
		- Acoustic Neuroma

**Cochlear Implants (CI) as Hearing Aids**
- Treats severe sensorineural hearing loss through <abbr Title="Continuous Interleaved Sampling">CIS</abbr>
	- Absence of sound: ~1000Hz pulses through each electrode at fixed rates with offsets
		- ∴ No simultaneous activation of electrodes & Prevents Current Spread (Stimulation spreads beyond target neural tissue area)
	- Presence of sound: The frequency and firing rates of the pulses will be changed
		- ∴ Encode Formant peaks across the electrode array
- Limitations of CIS:
	- Poor Pitch Perception (Melody / Distinguish Voices from Background Noises)
		- Sub-<abbr Title="milisecond">ms</abbr> Temporal Coding not possible → Fail to convey temporal fine structure of sound periodicity
		- Not enough effective channels for different Frequencies → Weak harmonic structure of sounds
	- Poor Spatial Hearing (Binaural Cues)
		- Many patients have only 1 CI Implant
		- Poor even if fitted <abbr Title="Implant on both sides of the ear; Available to HK Children">bilaterally</abbr>
			- Poor synchronization between two implants
			- Limited dynamic range of electrodes