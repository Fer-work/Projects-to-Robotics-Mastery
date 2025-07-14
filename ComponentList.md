# Component List: Project #1 - Lab Bench Power Supply

# Make prize comparison

| Item | Mercado Libre | Amazon MX | Electronica Amistad | Otro |
| LM7805 | ------------- | --------- | ------------------- | ---- |
| LM317 | ------------- | --------- | ------------------- | ---- |
| Arduino Nano | ------------- | --------- | ------------------- | ---- |
| INA219 | ------------- | --------- | ------------------- | ---- |
| ESP8266 | ------------- | --------- | ------------------- | ---- |

## Power & Regulation

- Main Transformer: 1 x 24V AC, 8A (or ~200VA) Center-Tapped Transformer
- Bridge Rectifier: 1 x 15A Bridge Rectifier Module (or 4 x 1N5408 Diodes for a DIY bridge)
- Main Filter Capacitor: 1 x 4700uF (or higher), 50V Electrolytic Capacitor

### Voltage Regulators (Fixed):

- 1 x LM7824 (+24V)
- 1 x LM7812 (+12V)
- 1 x LM7805 (+5V)

### Voltage Regulator (Variable):

- 1 x LM317 (for up to 1.5A)
  or
- LT1084 (for up to 5A, better choice)

### Smoothing Capacitors:

Assortment of 0.1uF Ceramic and 10uF Electrolytic Capacitors for the regulator outputs.

### Heat Sinks:

Large heat sinks appropriate for TO-220 package regulators (one for each regulator).

## Monitoring & Display

### Microcontroller:

1 x Arduino Nano

## Display:

1 x 16x2 or 20x4 I2C LCD Display Module

### Current/Voltage Sensors:

4 x INA219 GY-219 Modules

## User Interface & Output

### Potentiometer (for Variable Output):

1 x 10kΩ Linear Potentiometer

Binding Posts: 8 x Panel-Mount Binding Posts (4 pairs, red and black)

Switches: 1 x Main Power Switch (rated for mains voltage)

## Miscellaneous

- Project Enclosure (Metal is best for heat dissipation)
- AC Power Cord and Fused Inlet
- LEDs (for power-on indicators) and appropriate resistors (e.g., 220Ω)
- Perfboard or PCB for soldering the circuit
- Assorted wires (different gauges for AC and DC sections)

# Component List: Future Projects (For Bulk Purchase)

## Project #4: The Environment Hub

- Microcontroller: 1 x ESP32 or ESP8266 (Wemos D1 Mini is a great, cheap option)
- Temperature & Humidity Sensor: 1 x DHT22 (or BME280 for higher accuracy and pressure)
- Air Quality Sensor: 1 x MQ-135

## Project #6: The IoT Security Door

- Microcontroller: 1 x ESP32 (recommended for more pins and power)
- Keypad: 1 x 4x4 Matrix Membrane Keypad
- Servo Motor: 1 x MG996R High-Torque Metal Gear Servo
- Ultrasonic Sensor: 1 x HC-SR04
- Buzzer: 1 x 5V Passive Buzzer Module
- Buttons: 2 x Panel-Mount Tactile Push Buttons
- LEDs: Assorted 5mm LEDs (e.g., Red, Green)
- Resistors: Assortment of 220Ω and 10kΩ resistors
