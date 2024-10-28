# NAND-TETRIS

This repository contains my Hardware Description Language (HDL) implementations for the popular "From NAND to Tetris" course. Starting with basic NAND gates, I've built up a complete computer system from first principles, documenting my journey through the fundamentals of computer architecture.

## Overview

The NAND2Tetris course (also known as "The Elements of Computing Systems") takes you through building a modern computer system from the ground up. This repository contains my implementations of each component, from elementary logic gates to a fully functional CPU.

## Project Structure

Each directory corresponds to a course project, containing the following:
- `/01-basic-gates`: Boolean logic and gate implementations
- `/02-arithmetic`: ALU and arithmetic chips
- `/03-sequential`: Registers and memory units
- `/04-machine-language`: Assembly programs
- `/05-computer-architecture`: CPU and computer architecture
- `/06-assembler`: Assembler implementation

## Implementation Details

All chips are implemented using the custom Hardware Description Language (HDL) specified by the course. Each implementation:
- Starts from NAND gates as the basic building block
- Follows the course's hardware simulator specifications
- Includes test files to verify functionality
- Contains comments explaining the logic and design decisions

## Running the Code

You have two options to run and test these implementations:

### Online Simulator
The fastest way to get started:
1. Visit [https://www.nand2tetris.org/software](https://www.nand2tetris.org/software)
2. Click on the "Hardware Simulator (Web)" link
3. Upload the HDL files directly to the browser-based simulator
4. Run the test scripts to verify functionality

### Local Installation
For a complete development environment:
1. Download the NAND2Tetris Software Suite from the official website
2. Extract the downloaded files to your preferred location
3. Run the Hardware Simulator application
4. Load the HDL files and corresponding test scripts

Both options provide the same functionality, but the online simulator offers the advantage of no installation required and easy accessibility across different devices.

## Learning Journey

This repository represents my personal journey through computer architecture fundamentals. Feel free to explore the implementations, but I encourage you to attempt the problems yourself first – the learning experience is invaluable!

## Acknowledgments

Special thanks to Noam Nisan and Shimon Schocken for creating this amazing course, and to the NAND2Tetris community for their continued support and engagement.

## Note

These implementations are part of my learning process. While they pass all test cases, there might be room for optimization. Feedback and suggestions are always welcome!

## License

This project is released under the MIT License. Feel free to use it as a reference, but remember that learning happens through doing!
