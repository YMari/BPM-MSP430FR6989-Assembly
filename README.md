# BPM Application in Assembly for the Texas Instruments MSP430-FR6989 LaunchPad. (IAR IDE)

### Team Members: [Kevin Lugo](https://github.com/Kevin-Lugo), [José Maldonado](https://github.com/jose-maldonado)

### [Click here for a demo video](https://youtu.be/egEYVSqea88)

### Worked while taking CIIC4082 (Computer Architecture 2) course at UPRM, Spring 2021.

The goal of this project was to make a BPM application in Assembly for the Texas Instruments MSP430-FR6989 LaunchPad. The application will begin with an "OPTION" state, which then leads to either "READ" or "LOG" states. When "READ" is chosen, the user will be prompted to log their heartbeats per minute for the next 30 seconds by clicking the left button. After the "READ" operation is finished, the user will be asked if to "SAVE" the current reading or to skip back to "OPTION". Once a reading has been saved, the 3 most recent readings will be saved into the "LOG" state. Methods for the application are all commented (in Spanish) in the source code. Code worked using the IAR MSP430 IDE.
