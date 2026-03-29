**Programmable 4x4 Macro Keypad**

A custom-built Stream Deck based on an ESP32-S3, implemented using a 4x4 matrix keypad with diodes to eliminate ghosting.

The system enables the execution of customizable macros through the electrical detection of each key press. Its architecture is based on continuous scanning of the GPIO pins associated with the matrix keypad, allowing efficient and reliable user input detection. The system enables the execution of customizable macros through the electrical detection of each key press. Its architecture is based on continuous scanning of the GPIO pins associated with the matrix keypad, allowing efficient and reliable user input detection.The generated events are transmitted via serial communication to a Java-based application, where logical mapping is performed between each key identifier and its corresponding action, such as opening URLs, displaying images, or executing dynamically configured behaviors.
