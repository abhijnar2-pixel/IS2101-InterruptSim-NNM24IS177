# IS2101-InterruptSim-NNM24IS177

# Description
This Java program simulates the working of an Interrupt Controller, which manages interrupts from multiple devices such as Keyboard, Mouse, and Printer.
It demonstrates how priorities, masking, and Interrupt Service Routines (ISRs) work in a computer system.
The simulation uses multithreading to model concurrent device interrupts, where one thread handles the ISR execution while others trigger interrupts at random intervals.

# Features
Device Prioritization — Each device (Keyboard, Mouse, Printer) has a defined priority level.
Masking Mechanism — Interrupts can be ignored when a device is masked.
Concurrent ISR Handling — Uses threads to simulate real-time interrupt responses.
Logging System — Records timestamped ISR execution logs.
Random Interrupt Simulation — Generates interrupts randomly to simulate real-world conditions.

# File Structure
InterruptControllerSimulation/
│
├── Main.java               
├── InterruptController.java
├── Device.java             
└── README.md               

 # Running the Program
Prerequisites
Java 8 or higher installed
Any IDE (VS Code, IntelliJ, Eclipse) or Command Line
Save the program as Main.java
Compile the code:
javac Main.java
Run the program:
java Main

# Sample Output
KEYBOARD → ISR Completed at 10:25:30
MOUSE → ISR Completed at 10:25:31
PRINTER → ISR Completed at 10:25:32
KEYBOARD → ISR Completed at 10:25:33
MOUSE → ISR Completed at 10:25:34

--- ISR Log ---
10:25:30 - KEYBOARD executed
10:25:31 - MOUSE executed
10:25:32 - PRINTER executed
10:25:33 - KEYBOARD executed
10:25:34 - MOUSE executed

# Output


<img width="902" height="673" alt="Screenshot 1" src="https://github.com/user-attachments/assets/ffd28fa8-21d3-4b49-98dc-ff13ad46a1db" />


# Conclusion
This simulation effectively demonstrates:
The priority-based interrupt handling mechanism
The role of masking in controlling interrupt responses
The importance of synchronization and multithreading in managing concurrent events
Through this, you gain hands-on understanding of how interrupt controllers coordinate multiple device requests efficiently in computer systems.



