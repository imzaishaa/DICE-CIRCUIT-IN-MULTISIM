# DICE-CIRCUIT-IN-MULTISIM
This project simulates an electronic dice circuit using NI Multisim. The circuit mimics the function of a standard 6-sided dice, generating a random number (1 to 6) when a push button is pressed. The number is displayed using a 7-segment display or a combination of LEDs to represent dice faces.
Here's a `README.md` file for your **Dice Circuit in Multisim** based on the provided circuit image (using 4017 decade counter and LEDs):

---

# 🎲 Dice Circuit Simulation (Multisim)

## 🔍 Overview

This project simulates a **digital dice** circuit using **NI Multisim**. The circuit uses a 4017 Decade Counter (U1) to sequentially light up one of six LEDs representing the numbers 1 to 6, mimicking the behavior of rolling a standard dice. The clock signal is controlled using a switch, allowing a "roll" when the user presses it.

---

## ⚙️ How It Works

* **Clock Generator (V1):** A 1kHz pulse source generates the clock pulses needed to advance the counter.
* **Control Switch (S1):** Pressing the switch allows clock pulses to reach the 4017 IC, causing it to count.
* **4017 Decade Counter (U1):** This IC outputs a HIGH signal sequentially from Q0 to Q5 (representing dice numbers 1 to 6).
* **LEDs (1–6):** Connected to Q0 through Q5 of the 4017, only one LED lights up at a time to represent the current dice value.

---

## 🧠 Components Used

* Pulse Generator (V1) – 1kHz, 5V
* Push Button Switch (S1)
* IC 4017 Decade Counter (U1)
* 6 LEDs for dice outputs
* Resistors (as current limiters if included)
* Ground


## 🛠️ Operation Steps

1. Run the simulation in NI Multisim.
2. Press the switch (`Key = A`) to activate the clock.
3. LEDs will change rapidly. Releasing the switch will "lock" the output on one LED – simulating a dice roll.

## 📦 Features

* Simple and cost-effective dice simulation using digital electronics.
* Easily extendable for educational or game-based applications.
* Demonstrates the use of counters and clocked logic in digital circuits.


