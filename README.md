## Hi - Servus

My name is Samuel and I love to tinker around in different areas of tech but especially in robotics!  
I have created an overview of my projects below, it's all open source and free to use, maybe you find something useful or slightly interesting :D

## Project overview

- **Robots**
  - [Bugsy](https://github.com/SamuelNoesslboeck/Bugsy.git): A simple robot designed for some control and SLAM tests
    - [bug_os](https://github.com/SamuelNoesslboeck/bug_os.git): Low-level control software for the Bugsy robot
  - [Crabsy](https://github.com/SamuelNoesslboeck/Crabsy.git): A hexapod robot designed to be taught by AI
    - [CrabOS](https://github.com/SamuelNoesslboeck/CrabOS.git): Low-level control software for the Crabsy robot
  - [DrAI](https://github.com/SamuelNoesslboeck/DrAI.git): Diploma Project of [Rene Schwarz](https://github.com/SchwarzRene) and mine
  - [SyArm](https://github.com/SamuelNoesslboeck/SyArm.git): The first ever robotic arm I created 
- **Gadgets**
  - [RDX](https://github.com/SamuelNoesslboeck/RDX.git): Universal robot driver for stepper and servo motors. Features fast connectors and easy setup
    - [rdx_os](https://github.com/SamuelNoesslboeck/rdx_os.git): Basic operating system for the RDX, includes the general HAL for the robot driver
  - [DrRoll](https://github.com/SamuelNoesslboeck/DrRoll.git): Modified cardboard roll to store/transport A2 & A3 drawings/posters
  - [DrRo-III](https://github.com/SamuelNoesslboeck/DrRo-III.git): Upgraded version of the "DrRoll" with a better sealing mechanism and ability to carry A1 paper
  - [MagicBox](https://github.com/SamuelNoesslboeck/MagicBox.git): A flexible & programmable LoRa controller for different applications
    - [magicontent](https://github.com/SamuelNoesslboeck/magicontent.git): HAL for the "MagicBox", including demo programs that enable basic functionalities
    - [magic_wizard](https://github.com/SamuelNoesslboeck/magic_wizard.git): Simple UDP state machine coded in rust that enables systems that use the STD to receive simple inputs over WiFi from the MagicBox
- **Libraries**
  - [syact](https://github.com/SamuelNoesslboeck/syact.git): Generalizes actuators in a no-std environment that other libraries can build upon
  - [sybot](https://github.com/SamuelNoesslboeck/sybot.git): A rust library for controlling assemblies of components, including coordinate systems and complex mechanical calculations
  - [sylo](https://github.com/SamuelNoesslboeck/sylo.git): A small C++ helper library with components and structures frequently used in low level programming, especially with the Arduino framework
  - [systep](https://github.com/SamuelNoesslboeck/systep.git): Expansion crate for the syact library that enables high percision and parallel control of stepper motors on std environments
  - [lcd_menu](https://github.com/SamuelNoesslboeck/lcd_menu): A no-std, zero-alloc rust library for creating LCD menus on embedded devices using embedded-hal traits
- **Misc**
  - [noob_slam](https://github.com/SamuelNoesslboeck/noob_slam.git): Basic SLAM algorithm created by noobs
