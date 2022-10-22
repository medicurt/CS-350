# CS-350
A repository for storing my work in SNHU's CS-350 class

This repository contains two seperate projects from my embedded systems and microcontrollers at SNHU.
The first project, milestone three, demonstrates use of a timer, GPIO, and States defined by enumeration
to either cause an LED to blink 'SOS' or 'OK' (if an interrupt is triggered) in morse code. One thing
that I did well was the implementation of the states and the state machine logic. One thing that I could
have done better is making sure that no other state is entered until one state's logic is completed.
This project helped me to cultivate skills in the use of timers, GPIO, and State Machines, all of which
are applicable for other embedded systems projects. Additionally, learning to think about all programs as
being state machines has helped me to reframe how I approach writing all of my code.
This project was made durable for future reading and adaptation through the use of commenting, decoupled
code, and enumeration to set up the various state machines, making the code easy to change. Additionally,
variables, functions, and enumerations are all named so that their role in the code is clear and easy to
follow.

The second project, the Final Project, demonstrates the use of I2C, GPIO, and UART to create a thermostat 
which reads room temperature, adjusts state accordingly, and could be programmed to return data to a cloud.
One thing I did well with this project is making sure that the logic was abstracted out appropriately,
making it easy to adjust the logic and change the code at any given point.
One thing I think I could have done better is documenting the code more thoroughly.
This project helped me to cultivate an understanding of how different components in a microcontroller can
work together to synthesize behavior that is useful for both a business and a consumer, and I also gained
experience in dealing with very fast sampling rates to which a program is expected to respond.
This project was made durable for the future by using logic abstractions to make the code highly 
decoupled and easy to change; variable, function, enumeration names are all chosen to clearly 
convey their role in the program. 
