# Embedded_recess

This is our group project as Group13 on the class rota
        1. Zirimabagabo Anslem
        2. Mukisa Don
        3. Arinda Johnson
        
This is an embedded system that uses a camera and OCR to detect number plates in real time and sends an email notification ,this system can be used to track cars on the run,such systems can be installed on roads to reduce traffic crimes such as grand theft and many of sort.
We were able to use the following components;
A harvad tiny ML kit that consists of a shield,a  Nano 33 BLE Sense board and a OV7675 camera.
We used arduino to write our code in C and used django framework to capture and send emails after detecting number plates 
There was an issue with inaccuracy in OCR using pytesseract therefore we were able to use vertex ai from google by integrating their vision api into our project.


