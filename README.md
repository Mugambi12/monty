# Monty

Monty is a stack-based interpreter for Monty Bytecode files. It executes Monty bytecodes (.m files) and implements various operations on a stack.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description

This repository contains the source code for the Monty interpreter. The Monty interpreter is written in C and supports a set of operations on a stack, such as push, pop, add, sub, and more.

## Installation

To compile and run the Monty interpreter, follow these steps:

1. Clone the repository:
   ```shell
   git clone https://github.com/mugambi12/Monty.git
   ```

2. Change to the repository directory:
   ```shell
   cd Monty
   ```

3. Compile the source code using the provided Makefile:
   ```shell
   make
   ```

4. Run the Monty interpreter with a Monty bytecode file:
   ```shell
   ./monty path/to/bytecode.m
   ```

## Usage

The Monty interpreter accepts Monty bytecode files (.m) as input. Each line in the bytecode file contains an operation to be performed on the stack.

Example Monty bytecode file (example.m):
   ```shell
  push 1
  push 2
  push 3
  pall
   ```

To execute the bytecode file, run the Monty interpreter with the file as an argument:
   ```shell
   ./monty example.m
   ```

## Contributing
Contributions to Monty are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License
Monty is released under the MIT License.
   ```shell
   Please make sure to replace `your-username` in the installation instructions with your actual GitHub username. You can customize the README.md file further to meet your specific needs and preferences.
   ```
