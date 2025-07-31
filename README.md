# Persistence of Vision (POV) Display

This project demonstrates the concept of Persistence of Vision (POV) by displaying characters and patterns using an array of LEDs mounted on a rotating arm. When spun at a high speed, the LEDs flash at precise intervals to form readable text or graphics in mid-air.

## ✨ What is POV?

Persistence of Vision is an optical illusion where multiple images blend into a single image in the human eye due to the retention of vision for a fraction of a second. This project takes advantage of that principle to display characters using a single column of LEDs.

---

## 🧰 Hardware Used

- ✅ Arduino nano
- ✅ 7 x 5mm LEDs
- ✅ 7 x 220Ω resistors
- ✅ 1kΩ resistor
- ✅ 2kΩ resistor
- ✅ HC-05 Bluetooth module
- ✅ 1000 RPM DC Motor
- ✅ 2 x 9V Battery 
- ✅ IR sensor
- ✅ 12v Power Supply
- ✅ Jumper wires, General Purpose Board
- ✅ Hylem Sheet for Structure

---

## 💻 Software

- Arduino IDE  
- File: `code.ino` (contains the main sketch for LED timing and character display)
- Serial Bluetooth Termial

---

## ⚙️ How It Works

1. The Arduino controls the LEDs to turn on/off at specific time intervals.
2. The LED column spins rapidly (either using a motor).
3. The eye perceives the sequential blinking as a stable image or word floating in space.
4. A sensor is used to sync each rotation cycle.

---

## 📝 Setup Instructions

1. Wire the 7 LEDs to digital pins 2–8 of the Arduino using 220Ω resistors.
2. Mount the Arduino - LED Setup , batteries, IR Sensor, Bluetooth on a rotating circular hylem Sheet and make it balanced.
3. Upload the code from  `code.ino` file to your Arduino using the Arduino IDE.
4. Power the Ariduno and the Sensor and HC-05
5. Using the Serial Bluetooth Terminal App Send the Word to be Displayed.
6. Power the motor to start rotation.
7. Adjust delay timing in the code to improve clarity and stability of the display.

---

## 📸 Circuit Diagram 

Refer : cicuit.jpeg 

https://github.com/harinisubbiah/Persistence-of-Vision-/blob/c31e902a48ca4845ba16e25535b9d797497a811a/circuit.jpeg 

---

## 🙋‍♀ Author

Created by 
Harini S  

# Contributors

- Harshini S[ https://github.com/harshini-subbiah]
- Kiran S []
- Krithikesh[https://github.com/krithikeshI]

# Mentors
- Mr.Suresh Sir 
- Mr.VijayaKumar Sir
