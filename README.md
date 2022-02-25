# Controlling system Audio using your Fingers in Python and Computer vision

Gesture recognition helps computers to understand human body language. This helps to build a more potent link between humans and machines, rather than just the basic text user interfaces or graphical user interfaces (GUIs). 

Libraries used - Numpy, Pycaw : Python Audio Control Library, Mediapipe is an open-source machine learning library of Google, which has some solutions for face recognition and gesture recognition, and provides encapsulation of python, js and other languages. 

The camera in our device will detect our hand with points in it so as it can see the distance between our thumb finger tip and index finger tip. The distance between the points 4 and 8 is directly proportional to the volume of device.

Methodology:

1. Detect hand landmarks
2. Calculate the distance between thumb tip and index finger tip.
3. Map the distance of thumb tip and index finger tip with volume range. Here, distance between thumb tip and index finger tip was within the range of 30 – 350 and the volume range was from -63.5 – 0.0.
4. In order to exit press ‘Spacebar'
