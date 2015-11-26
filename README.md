# LED-Cube (4x4x4)
64 LEDs makes up this 4 by 4 by 4 cube, controlled by an Arduino Uno microcontroller, to display amazing 3D animations.

The LED_cube.ino file contains this:

We will be using a Arduino Uno board(microcontroller board based on the ATmega328P) and POV multiplexing to swtith the 64 LEDs to display various 3D animations and patterns.

1. We shall connect the pins from the cube to the Arduino as mentioned in the connection manual.
2. Use Arduino Software (IDE) 1.0 to write the main code for the microcontroller.
3. Initialize and declare the layers and the respective LEDs.
4. Using setup() function set layers and LEDs for output.
5. Define randomSeed() fuction for random animations.
6. Now inside loop() function declare all the other methods to used to make patterns.
7. Define each of those functions using custom logic and timing.

Then comes the job to setup the Arduino with the cube and run the code.
