SPEECH-RECOGNITION-SYSTEM
COMPANY :CODTECH IT SOLUTIONS PVT.LTD

NAME:VIDHYARTTH S A

INTERN ID:CT04DH1668

DOMAIN NAME: embedded system

DURATION:4 WEEKS

MENTOR:NEELA SANTOSH

DESCRIATION

The Speech Recognition System is a conceptual smart automation project that uses voice commands to control devices such as LEDs through Python-based speech recognition and visualized hardware interaction. The idea behind this project is to simulate how human speech can be translated into electronic actions, such as turning an LED ON or OFF, using simple voice commands like “turn on the light” or “switch off the fan.” For this project, we used Python 3.12+ as the programming language and Visual Studio Code (VS Code) as the development environment. The speech recognition feature was implemented using Python libraries such as speech_recognition, pyaudio, and pipwin. These libraries allow the system to capture audio input from the user using a built-in laptop microphone and convert the spoken words into text. This text is then compared with predefined commands, and if a match is found, a corresponding action is performed, such as printing “LED ON” or “LED OFF” to the console or changing a GUI label. Since speech recognition requires real-time microphone input and audio processing, this part was done entirely in Visual Studio Code on a laptop, outside of any online simulator. Tinkercad and other circuit simulators do not support real-time audio or voice recognition features, which makes it impossible to fully simulate the behavior in a hardware environment online. However, to represent the hardware side of the project, I used EasyEDA to create the conceptual circuit design. This included an Arduino Nano, a microphone module (symbolically representing the input), and multiple LEDs connected via resistors. Although the microphone symbol was only for visual representation and not actually functional in simulation, it helped conceptualize how a real system would look. The Arduino was not programmed in this project because the voice recognition and logic control were handled entirely through Python on a computer, with the Arduino circuit serving as a reference or future implementation step. In other words, the hardware circuit was designed but not physically built or simulated with real audio commands. The simulated LED behavior was shown through console messages in the VS Code terminal or a basic GUI interface using Tkinter or similar tools. When the user spoke a recognized phrase, the Python program printed “LED ON” or “LED OFF” to simulate how a physical LED would respond. This approach allowed us to focus on developing a working speech recognition prototype without relying on external hardware. The project demonstrates how voice technology can be applied in home automation, assistive systems, or touchless control environments. It is also a valuable learning experience in combining software with conceptual hardware, allowing for easy upgrades to physical components in the future using Arduino and relay modules. In conclusion, the Speech Recognition System effectively integrates Python programming, audio processing, and circuit design. Though the speech recognition part could not be simulated online or directly connected to an Arduino, using Visual Studio Code for logic and EasyEDA for design allowed the entire system to be conceptually complete and practically useful for real-world applications and future hardware integration.

circuit:


output:

