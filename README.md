Note: This repository is now set to "read-only" and development of the application is halted.
"CalcTest1" was a very simple console-based application written in C++. Its purpose was for me to attempt to apply some of what I was learning from the page [LearnCpp](https://www.learncpp.com/) in the form of a simple calculator.
After initial tests, I noticed that I didn't like the way the application code was written. A successor to this application can be found at [vonint/CalcTest2](https://github.com/vonint/CalcTest2).

If you want to use this application and/or its code yourself: I have now attached the UNLICENSE "license" to this repository, subsequently releasing it to the public domain (as-is).

Date: July 16th, 2023

<details>
  <summary>CalcTest1: Application README</summary>

  # CalcTest1

This console-only application contains basic arithmetic functions as a proof-of-learning milestone for myself and is absolutely not intended for production. Release included for testing.

Features:
* Simple 4 choices prompt with user input (through "cin")
* Basic addition (first and second summand)
* Basic subtraction (minuend and subtrahend)
* Basic multiplication (first and second factor)
* Basic division (dividend and divisor)
** To be improved: Currently no consideration for invalid entries
* Error on invalid 4 choice prompt entry through "else" statement
* "cls" echo to system on choice prompt entry confirm ("std:system("cls")" on every "else if" statement for arithmetic functions)
** To be improved: No utilization of functions outside of main

Date of finish: 25.10.2022

UPDATE: Version 1.1

* Added "std:system("pause >NUL")" after the program has finished running. This keeps the Windows console open so that the user can confirm their result. 
* Added string to explain that user input is required for the program to terminate.
* Improved other strings to circumvent user error on feature limitations (such as manual input confirms). 
** This will be improved on a different code base. 
* Added additional comments.
* Source code is now in DEBUG configuration. Release will be available in the RELEASE configuration, as expected.
* In the future, the local time of finish will be included with the date of finish. This version took less than 10 minutes to create.

There will be no further improvements to CalcTest1 after this patch. Any further adjustments made to the program will be released separately on a rewritten code base.
Thank you for understanding.

Date of update finish: 25.10.2022, 19:45 CEST

</details>
