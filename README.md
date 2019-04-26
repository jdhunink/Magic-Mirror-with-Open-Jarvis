# Magic-Mirror-with-OpenJarvis-AI

Status: Partially Complete

A Raspberry Pi powered monitor set behind one way glass creating a reflective mirror with
a backlit display. The interface uses the Magic Mirror repo and a couple of extra modules built for the magic mirror itself.
The Mirror is also attached with a microphone that is used to record input for voice recognition. After passing this input through Jarvis the command can be run by either jarvis as a stand alone, or through jarvis to the mirror itself.

The wake word for Jarvis is "Jarvis"
The hotword to interact with the mirror is "Please" thanks to the MMM-Jarvis-Voice-Vontrol module

A sample command of: "Jarvis, please show the forecast" when magic mirror is running will navigate to the forecast page.
