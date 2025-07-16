# Final-Year-Project

This project presents the development of a low-cost, open-source metal additive manufacturing system based on Wire Arc Additive Manufacturing (WAAM) using MIG welding integrated with a three-axis gantry robotic platform. Designed to meet the growing demand for affordable, customizable, and rapid metal fabrication, the system enables layer-by-layer deposition of metal with improved mechanical reliability and precision.

As part of my Final Year Project, I was responsible for the control system of the gantry ststem and the other things in our prototype. I selected and integrated suitable microcontrollers( Arduino MEGA 2560), stepper motor drivers (TMC 2209) , and the robotic motion control system (Gantry system), along with appropriate firmware (Marlin) and G-code processing software (pronterface) to ensure smooth operation and synchronization.

To automate welding torch activation, I implemented a method using a KY-040 rotary encoder to detect extruder movement clock signals. Based on these signals, the welding torch was precisely triggered only during material deposition. Additionally, for enhancing surface quality and consistency, I read the real-time welding current signal through a current display module and used this feedback to control a dedicated Z-axis stepper motor, dynamically adjusting the torch height during printing.

Prototype

![image alt](https://github.com/Chalangana/Final-Year-Project/blob/b5d66177dde9a55e370dfb8e40b6c9af7044274b/Screenshot%202025-07-17%20020245.png)

![image alt](https://github.com/Chalangana/Final-Year-Project/blob/b5d66177dde9a55e370dfb8e40b6c9af7044274b/WhatsApp%20Image%202025-07-17%20at%2001.32.44_dff8ced5.jpg)

Control system

![image alt](https://github.com/Chalangana/Final-Year-Project/blob/43173fb445646ab35c1e38f2c57c2098491dec75/Screenshot%202025-07-17%20020144.png)

Results

![image alt](https://github.com/Chalangana/Final-Year-Project/blob/55218579ff17243d80a1d027b585e5f9876cd464/WhatsApp%20Image%202025-07-09%20at%2006.52.18_0cda25b1.jpg)

![image alt](https://github.com/Chalangana/Final-Year-Project/blob/55218579ff17243d80a1d027b585e5f9876cd464/WhatsApp%20Image%202025-07-09%20at%2006.52.21_0187d1d9.jpg)

![image alt](https://github.com/Chalangana/Final-Year-Project/blob/55218579ff17243d80a1d027b585e5f9876cd464/WhatsApp%20Image%202025-07-09%20at%2006.52.22_1438b3e1.jpg)

![image alt](https://github.com/Chalangana/Final-Year-Project/blob/55218579ff17243d80a1d027b585e5f9876cd464/WhatsApp%20Image%202025-07-09%20at%2007.17.48_a2f3a25a.jpg)

![image alt](https://github.com/Chalangana/Final-Year-Project/blob/55218579ff17243d80a1d027b585e5f9876cd464/WhatsApp%20Image%202025-07-17%20at%2001.35.04_7a176e8d.jpg)
