# intelunnati_TeamMV
Design and Implementation of Automated Teller Machine (FSM) Controller(Team MV)(Veekshitha, Madhu shree M)
Sure, here is a modified README for GitHub Design and Implementation of Automated Teller Machine (FSM) Controller with additional checks:

## Description

This repository contains the design and implementation of an ATM machine controller using the Finite State Machine (FSM) modelling technique. The controller is implemented in VHDL and can be synthesized into a hardware description, which can be realized on an FPGA (Field-Programmable Gate Array).

The controller implements the following ATM functions, with additional checks:

* **User authentication:** The controller will authenticate the user by checking their PIN. If the PIN is entered incorrectly 3 times, the account will be locked for 24 hours.
* **Transaction processing:** The controller will process ATM transactions, such as withdrawals, deposits, and balance inquiries.
* **Cash dispensing:** The controller will dispense cash to the user, if the withdrawal amount is less than or equal to 10000 INR. For withdrawals greater than 10000 INR, the face recognition test will be triggered.
* **Receipt generation:** The controller will generate a receipt for the user, which will show the details of the transaction.
* **Mini statement:** The controller will show the 10 most recent transactions on the user's account.

The controller is designed to be modular and reusable, and it can be easily extended to support additional ATM functions.

## Requirements

* VHDL compiler
* FPGA development board
* Simulation software
  Intel Quartus Prime Design Software (Lite edition)
  Simulation using Modelsim / Questa Sim
* Download Center for Intel FPGAs:
https://www.intel.com/content/www/us/en/software-kit/665990/intel-quartus-prime-lite-edition-designsoftware-
version-18-1-for-windows.html

## Usage

To use the controller, you will need to first compile the VHDL code. Once the code has been compiled, you can synthesize it into a hardware description. The hardware description can then be loaded onto an FPGA development board.

The controller can be simulated using a simulation software. This will allow you to test the controller's functionality and correctness.

## Documentation

The documentation for the controller is available in the `docs` directory. The documentation includes the following:

* A description of the FSM model
* The VHDL code for the controller
* A simulation model of the controller

## License

The controller is licensed under the MIT License.

## Author

The controller was created by Veekshitha, Madhu shree M .

## Contact

If you have any questions about the controller, please contact veekshithanaik01@gmail.com.

## Changelog

* 2023-07-14: Initial release.
* 2023-07-15: Added checks for invalid PIN entry, face recognition, and mini statement.

## TODO

* Add support for additional ATM functions.
* Improve the documentation.
* Test the controller on different FPGA development boards.

## Additional Notes

* The controller will lock the account for 24 hours if the PIN is entered incorrectly 3 times.
* The face recognition test will be triggered if the withdrawal amount is greater than 10000 INR.
* The mini statement will show the 10 most recent transactions.

I hope this is helpful!

Here are the changes I made:

* I added a section called "Additional Notes" that provides more information about the additional checks that the controller performs.
* I updated the "TODO" section to include some additional tasks that need to be completed.
* I corrected some grammar and spelling errors.

Please let me know if you have any other questions.
