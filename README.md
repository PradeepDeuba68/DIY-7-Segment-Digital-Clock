# DIY-7-Segment-Digital-Clock
A simple and fully functional digital clock project using 7-segment displays and an ATmega328p/8A microcontroller. Ideal for electronics hobbyists and beginners. Includes circuit instructions, component list, and Arduino code.





📚 What is a 7 Segment Display?
A 7-segment display is a type of digital display device used to show decimal numbers and a few characters. It consists of seven individual LEDs, labeled A through G, arranged in a rectangular fashion. Each segment can be lit up individually to display numbers 0–9 and a limited set of letters.

🔹 Key Features:
Simplicity: Easy to design and build.

Versatility: Can show numerals and some characters (like A, b, C, d, E, F).

Cost-effective: Inexpensive compared to other display types.

Energy-efficient: Uses low-power LEDs.


🧰 Component List
Component	Quantity
ATmega328p / ATmega8A	1
16 MHz Crystal	1
22pF Capacitors	2
28 Pin IC Base	1
LEDs	~21 (for 4 digits)
Zero PCB	1
Slide On/Off Switch	1
Push On/Off Switch	1
Push Buttons	2
100Ω Resistors	8
Male Pin Headers	As needed
Li-Ion Battery (3.7V)	1
Battery Charger	1

🛠️ Assembly Instructions
✅ Step 1: Build a Single 7 Segment
Use 3 LEDs in parallel for each segment.

Connect all cathodes together in each group.

Connect anodes of the same segment together.

✅ Step 2: Make 4 Sets
Create four identical 7-segment modules.

Keep each cathode separate.

Connect the cathodes to a male header.

✅ Step 3: Segment Grouping
Connect all 'A' segments of each digit together, and do the same for B to G.

Each common segment (A-G) goes to its own pin on the microcontroller via a header.

✅ Step 4: Wire to IC
Connect all the segment pins and digit selects to the appropriate pins on the ATmega as per your schematic.

✅ Step 5: Upload the Code
Use an Arduino UNO as ISP programmer.

Flash the code (provided below or in the GitHub repo) to your ATmega328p/8A chip.

cpp
Copy
Edit
// Sample code snippet
void setup() {
  // Your setup code here
}

void loop() {
  // Display time using segments
}
(👉 Full code will be available in this repo under code/digital_clock.ino)

✅ Step 6: Power It Up
Plug in your 3.7V Li-ion battery.

Enjoy your fully functional digital 7-segment clock!

📥 Download
🗂️ Schematic Diagram

🧾 Source Code (digital_clock.ino)

📄 PCB Design (optional)

💬 Feedback & Support
If you have any feedback or questions about this project, feel free to open an issue or leave a comment. I'd love to hear from you and help you build your own digital clock!

🙏 Thank You!
Happy making! 🌟

🔗 License
This project is open-source under the MIT License.
