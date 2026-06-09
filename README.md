# CIS-11 Project B: Test Score Calculator

## Team Information

**Team Name:** Avengers Assemble

**Team Members:**

* David Zaragoza
* Javier Martinez
* Francisco Colorado

**Instructor:** Kasey Nguyen, PhD

---

## Project Description

The Test Score Calculator is an LC-3 Assembly Language program that accepts five student test scores as input. The program calculates and displays:

* Minimum score
* Maximum score
* Average score
* Letter grade equivalent for the minimum, maximum, and average scores

The program also includes input validation to ensure that scores entered are within the valid range of 0–100.

---

## Features

* User input of five test scores
* ASCII-to-integer conversion
* Minimum score calculation
* Maximum score calculation
* Average score calculation
* Letter grade conversion (A, B, C, D, F)
* Input validation for scores greater than 100
* Stack-based register save/restore operations
* Array-based storage using `.BLKW`

---

## Repository Structure

### Program

Contains all LC-3 source code files.

### Documentation

Contains project documentation, pseudocode, testing documentation, and other supporting materials.

---

## How to Run

1. Open the LC-3 Simulator.
2. Load the assembled program.
3. Run the program.
4. Enter five test scores when prompted.
5. View the calculated minimum, maximum, average, and corresponding letter grades.

---

## Test Cases

The project was tested using:

* Assignment sample test case
* Maximum-value test case (100s)
* Input validation test case (scores greater than 100)

See the Documentation folder for detailed test results and screenshots.
