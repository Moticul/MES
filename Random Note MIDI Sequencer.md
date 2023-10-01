# Overview 

Every modern synthesizer is able to support the Musical Instrument Digital Interface (MIDI) standard. But not every synthesizer has a built in sequencer. Some don't even have keys to for users to manually play notes, and purely rely on external MIDI notes to function. This standalone MIDI sequencer will allow for random note patterns to be generated within the user-selected musical scale, key, and tempo. Serving as a source of inspiration to build off of.   

# Application 

A user will be able to define the following: 
- root note
- low and high octave boundaries
- tempo (in beats per minute) 
- musical key and scale 
- MIDI channel  

Once defined, the sequencer will generate random notes and apply them across 32-steps (2 bars) in random order, at random note lengths, and with random rests inserted. 
# Parts

- 5-pin DIN connector to interface with other instruments via a MIDI cable 
- buttons for user input 
	- up
	- down
	- enter
	- back
	- play/stop
- display for UI  
# Block Diagram

![[Block Diagram.png]]

