# Pascal Junior Compiler: x86-64 Assembly Code Generator

This project extends a compiler to generate x86-64 assembly for a subset of the PJ programming language. Built symbol tables to handle global vs. local variables, 
managed function calls, return values, and register usage.

### Key Features

- **Input**: Pascal source code files (`.pas`).
- **Output**: Corresponding x86-64 assembly files (`.s`).
- **Executable Generation**: Compiled assembly files can be linked to create executables using `gcc`.

### Installation

Clone this repository and navigate to the project directory:

```
git clone https://github.com/sanjeev29/pascal-junior.git
cd pascal-junior
```

### Build Instructions

To build the project:

```
make
```

### Running the Compiler

To compile a Pascal Junior source file (`<file>.pas`) into an assembly file (`<file>.s`), use the following command:

```
pjc <file>.pas
```

### Creating Executables

To create an executable from the generated assembly file, use:

```
gcc -o <file> <file>.s
```
