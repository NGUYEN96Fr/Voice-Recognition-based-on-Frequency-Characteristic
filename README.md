# Voice-Recognition-based-on-Frequency-Characteristic
This project aimed to deal with the voice regcognition problem based on Frequency Characteristic. Hardware design are composed of Voice Recognition Module VR3 and Arduinos.

The main code is divided into two smaller parts.
- The first part has a role like a client in the client - host model. This part is in charge of receiving the established commands from the buttons which control the tasks of the system such as voice sampling task, voice registered task,voice recognition task
- The second part has a role like a host. This part has the mission of receiving the command from the client and implenting the tasks defined above. And, this part processes the voice signals received from VR3 module and showes the results on LCD screen. 
