# Final-Year-Project

As part of my Final Year Project, I was responsible for the control system of the gantry ststem and the other things in our prototype. I selected and integrated suitable microcontrollers( Arduino MEGA 2560), stepper motor drivers (TMC 2209) , and the robotic motion control system (Gantry system), along with appropriate firmware (Marlin) and G-code processing software (pronterface) to ensure smooth operation and synchronization.

To automate welding torch activation, I implemented a method using a KY-040 rotary encoder to detect extruder movement clock signals. Based on these signals, the welding torch was precisely triggered only during material deposition. Additionally, for enhancing surface quality and consistency, I read the real-time welding current signal through a current display module and used this feedback to control a dedicated Z-axis stepper motor, dynamically adjusting the torch height during printing.
