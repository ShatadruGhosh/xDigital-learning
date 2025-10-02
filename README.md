0Phase 1

📘 **Day 1 — Learning Outcomes**

🔹 C++ Basics

* **Variables**: `int ledPin = 13;` → store numbers.
* **Functions**: `setup()` runs once, `loop()` runs repeatedly.
* **Commands**: `pinMode()`, `digitalWrite()`, `delay()` control hardware.
* **Structure**: setup + loop = Arduino program skeleton.

---

🔹 Electronics Basics

* **Digital Output**: Pins set HIGH (ON) or LOW (OFF).
* **LED**: Needs protection to avoid burning out.
* **Resistor**: Limits current. Example: 5V/220Ω ≈ 22mA (safe).

---

 🔹 Takeaway

* Wrote first embedded C++ program (Blink).
* Learned setup–loop cycle for firmware.
* Understood why resistors protect hardware.
* First step toward thinking like a firmware engineer.

---

📘 **Day 2 — Learning Outcomes**

 🔹 C++ Basics

* Learned `digitalRead()` for reading input pins.
* Practiced `if/else` conditionals to react to input.
* Understood difference between `INPUT` and `INPUT_PULLUP`.

🔹 Electronics Basics

* Explored push button structure (4 pins, internal bridging).
* Understood **floating inputs** and the role of pull-up/pull-down resistors.
* Learned that **GND** is the common reference for all voltages.
* Built circuit: Button press → Pin D2 HIGH → LED ON (pin 13). Release → LOW → LED OFF.

🔹 Takeaway

* Button is a switch; it connects pin either to 5V or GND.
* Resistor ensures pin is never floating, defines default logic state.
* Completed full loop: Input (button) → MCU logic → Output (LED).

---

✨ Next (Day 3): Implement toggle logic — one button press turns LED on and keeps it on, another press turns it off. This introduces **state variables** and **edge detection** in firmware.

