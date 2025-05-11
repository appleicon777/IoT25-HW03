# IoT25-HW03

## Purpose
Set ESP32 Board at Arduino IDE 2.0, Check if the board operates well with Example Blink

---

## Arduino IDE Setting
- Board: DOIT ESP32 DEVKIT V1
- Port: /dev/cu.SLAB_USBtoUART

![IDE 설정 스크린샷](./images/ide.png)

---

## Blink Example Video
(https://youtube.com/shorts/5IxnP190IlY?si=GDXLIBXNyI5YGVs0)

---

## Code

// the setup function runs once when you press reset or power the board
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);  // turn the LED on (HIGH is the voltage level)
  delay(1000);                      // wait for a second
  digitalWrite(LED_BUILTIN, LOW);   // turn the LED off by making the voltage LOW
  delay(1000);                      // wait for a second
}
