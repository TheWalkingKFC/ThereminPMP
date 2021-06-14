# ThereminPMP
Theremin using raspberry pi and a monk makes phototransistor circuit.
The goal of this project is to act as a pseudo theremin, using a photoresistor circuit supplied by MonkMakes and a raspberry Pi. 
Essentially, it takes the amount of light from the phototransistor and inputs this into PureData. PureData then processes these numbers (capped out at 100) and outputs a sound.
The closer your hands to the sensor, the less light it detects, the lower the number it outputs to PureData, and the quietter the sound that is outputed. 

Ps: This project requires an auditory output device to attach to the raspberry pi, such as headphones, speakers or earphones. 
Ps: Make sure you have an environment to run python, as well as PureData
To start the program:
1: Create circuit #8 from http://monkmakes.com/downloads/pi_box_1a.pdf 

2: Connect circuit to Raspberry Pi 

3: Import the files into your raspberry pi (If they are already there, they will open up on startup, but the rest of the steps will be for your first time runing this)

4: Open the Murchison_Pelletier_Python_Script.py file 

5: Open the PureData file called Murchison_Pelletier_theremine.pd

6: Start the Python script 

7: Lift hand away from sensor to increase sound, bring closer to sensor to decrease sound
	
	
Ps: Could also use a flashlight, and fluxuate its distance from the sensor, that way the sound is always clear and loud. This will also have the opposite effect, as your flashlight gets closer the sound gets louder and as it gets farther away, the sound gets quietter. 
