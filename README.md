# ELC325 Digital Communication

Digital Communications Matlab Simulink Project.

***Name:*** Ahmed Ibrahim
***Section:*** 01
***BN:*** 02

*The following simulation is done using MATLAB R2016a Simulink, some results may differ if rerun in another version*

---


## BPSK
> Binary Phase Shift Keying (BPSK) is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: for binary 1 θ=0° and θ=180° for binary 0.

* The following diagram is main blocks to reproduce the results

![Model](/BPSK/BPSK.JPG)

* Then update **random integer generator** to the following settings

![Rand](/BPSK/BPSK-Rand.JPG)

* After starting simulation, the following figures **(which shows signal before and after noise)** will appear.

![Before](/BPSK/BPSK-Before.JPG)   ![After](/BPSK/BPSK-After.JPG)

* Start **bit error analysis** by calling **bertool** from ***Matlab***

* Modify settings to the following

![BER](/BPSK/BPSK-bertool.JPG)

* Press plot

* Modify following settings to pick the model file

![BER2](/BPSK/BPSK-bertool2.JPG)

* After plotting the graph by pressing run, the following results will appear

![BEROut](/BPSK/BPSK-BER.JPG)

---


## QPSK
> Quadrature Phase Shift Keying (QPSK) is a form of Phase Shift Keying in which two bits are modulated at once, selecting one of four possible carrier phase shifts (0, 90, 180, or 270 degrees). QPSK allows the signal to carry twice as much information as ordinary PSK using the same bandwidth. QPSK is used for satellite transmission of MPEG2 video, cable modems, videoconferencing, cellular phone systems, and other forms of digital communication over an RF carrier.

* The following diagram is main blocks to reproduce the results

![Model](/QPSK/QPSK.JPG)

* Then update **random integer generator** to the following settings

![Rand](/QPSK/QPSK-Rand.JPG)

* After starting simulation, the following figures **(which shows signal before and after noise)** will appear.

![Before](/QPSK/QPSK-Before.JPG)   ![After](/QPSK/QPSK-After.JPG)

* Start **bit error analysis** by calling **bertool** from ***Matlab***

* Modify settings to the following

![BER](/QPSK/QPSK-bertool.JPG)

* Press plot

* Modify settings to pick the model file (as done in BPSK modulation)

* After plotting the graph by pressing run, the following results will appear

![BEROut](/QPSK/QPSK-BER.JPG)

---


## FSK
> Frequency Shift Keying (FSK) is the digital modulation technique in which the frequency of the carrier signal varies according to the digital signal changes. FSK is a scheme of frequency modulation.

* The following diagram is main blocks to reproduce the results

![Model](/FSK/FSK-2.JPG)

* Update modulator and demodulator to the following settings

![Modulator](/FSK/FSK.JPG)

* Then update **random integer generator** to the following settings

![Rand](/FSK/FSK-Rand.JPG)

* After starting simulation, the following figures **(which shows signal before and after noise)** will appear.

![Before](/FSK/FSK-Before.JPG)   ![After](/FSK/FSK-After.JPG)

* Start **bit error analysis** by calling **bertool** from ***Matlab***

* Modify settings to the following

![BER](/FSK/FSK-bertool.JPG)

* Press plot

* Modify settings to pick the model file (as done in BPSK modulation)

* After plotting the graph by pressing run, the following results will appear

![BEROut](/FSK/FSK-BER.JPG)

---


## QAM
> QAM (quadrature amplitude modulation) is a method of combining two amplitude-modulated (AM) signals into a single channel, thereby doubling the effective bandwidth.

### QAM 16

* The following diagram is main blocks to reproduce the results

![Model](/QAM-16/QAM-16.JPG)

* Update modulator and demodulator to the following settings

![Modulator](/QAM-16/QAM16.JPG)

* Then update **random integer generator** to the following settings

![Rand](/QAM-16/QAM16-Rand.JPG)

* After starting simulation, the following figures **(which shows signal before and after noise)** will appear.

![Before](/QAM-16/QAM16-Before.JPG)   ![After](/QAM-16/QAM16-After.JPG)

* Start **bit error analysis** by calling **bertool** from ***Matlab***

* Modify settings to the following

![BER](/QAM-16/QAM16-bertool.JPG)

* Press plot

* Modify settings to pick the model file (as done in BPSK modulation)

* After plotting the graph by pressing run, the following results will appear

![BEROut](/QAM-16/QAM16-BER.JPG)



### QAM 64

* The following diagram is main blocks to reproduce the results

![Model](/QAM-64/QAM-64.JPG)

* Update modulator and demodulator to the following settings

![Modulator](/QAM-64/QAM64.JPG)

* Then update **random integer generator** to the following settings

![Rand](/QAM-64/QAM64-Rand.JPG)

* After starting simulation, the following figures **(which shows signal before and after noise)** will appear.

![Before](/QAM-64/QAM64-Before.JPG)   ![After](/QAM-64/QAM64-After.JPG)

* Start **bit error analysis** by calling **bertool** from ***Matlab***

* Modify settings to the following

![BER](/QAM-64/QAM64-bertool.JPG)

* Press plot

* Modify settings to pick the model file (as done in BPSK modulation)

* After plotting the graph by pressing run, the following results will appear

![BEROut](/QAM-64/QAM64-BER.JPG)


