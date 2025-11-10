# Week 3 Tutorial

### Download and install Arduino IDE.

**For Windows**
- Go to the official Arduino website:
👉 https://www.arduino.cc/en/software
- Scroll down to the `“Download the Arduino IDE”` section.
- Under Windows, choose one of the following:
  - Windows Installer (.exe) → recommended (auto-installs drivers)
- Windows ZIP file → portable version (no installation)
- Click “Just Download” (or donate if you wish).
- Once downloaded, open the .exe file and follow the setup wizard:
- Accept the license agreement
- Choose installation folder
` Allow driver installation when prompted. After installation, open Arduino IDE from the Start Menu.`

**For macOS**
- Visit https://www.arduino.cc/en/software
- Under macOS, click “Mac OS X Version” to download the .dmg file.
- Once downloaded, open the .dmg and drag the Arduino icon into your Applications folder.

`Open Arduino from Applications (you may need to allow it in System Preferences → Security & Privacy if it’s blocked).`

**Analyse the program life cycle: setup() and loop() function**
```


```
**Print `Hello World` in serial monitor.**
- Open Arduino IDE
- Launch the Arduino IDE on your computer.
- Connect your Arduino board
- Plug in your Arduino (e.g., Uno, Nano) using a USB cable.
- Select the correct board and port
- Go to Tools → Board → Arduino Uno (or your board type)
- Go to Tools → Port → COMx (select the one with your Arduino)
- Write the code
```
void setup() {
  Serial.begin(9600);      // Start serial communication at 9600 baud
  Serial.println("Hello, World!");  // Print once when Arduino starts
}

void loop() {
  // nothing here
}
```
- Upload the code
- Click the ✅ Verify button (checkmark) to compile.
- Then click the ➡️ Upload button to send the code to your Arduino.
- Open the Serial Monitor
- Go to Tools → Serial Monitor (or press Ctrl + Shift + M)

> Set baud rate = 9600 (bottom-right corner)
### 1. Observe the Arduino Board and find out the GPIO pins. Also, write its functions.
```
Arduino Uno has 14 digital GPIO pins (D0–D13) and 6 analog GPIO pins (A0–A5).GPIO (General Purpose Input/Output) pins allow the Arduino to read sensors (input) and control devices like LEDs or motors (output).

```
### 2. Find out ceramic resonator and microcontroller and write it's function.
```
About ceramic resonator and its function
A timing device that provides the clock signal to keep the Arduino’s operations running at the correct speed (usually 16 MHz).

```
```
About microcontroller and its function


```
### 3. Find out how much memory is on Arduino UNO R3 board? Note out the different types of memory and capacity of each type.
```


```
### 4. What is NodeMCU-ESP32 ? What are the difference between NodeMCU-ESP32 and Arduino UNO?
```


```
