# Kaffee Analyzer

<p align="center">
  <img src="https://github.com/DecPotein/Kaffee-Analyzer/assets/81295133/9ffd4404-5067-44c1-a762-6d7783f735f3" alt="Kaffee Analyzer logo"/>
</p>

Kaffee Analyzer is a lexical, syntax, and semantic analyzer developed for the purpose of parsing programs written in our custom programming language, Kaffee. The name 'Kaffee' is derived from the German word for 'coffee,' which serves as the inspiration for our project. This choice was influenced by our use of Java, with its logo famously depicting a coffee mug.

## Overview

Kaffee Analyzer represents a crucial component in the development and validation process of writing programs. This project attempts to offer analysis and verification of code written in the Kaffee language.

## Features

- **Lexical Analysis**: Identifies and categorizes the lexical elements of the Kaffee language, including keywords, identifiers, literals, and symbols.
  
- **Syntax Analysis**: Implements a parsing mechanism to validate the syntactic structure of Kaffee programs, ensuring adherence to the defined grammar rules.
  
- **Semantic Analysis**: Performs semantic checks to verify the correctness of program constructs, including type compatibility, variable scope, and adherence to language-specific semantics.
  
- **Error Reporting**: Provides error messages to identify and rectify issues within the written Kaffee programs.

## Usage

To use the analyzer, simply create a text file and input your Kaffee source code then move said text file to the `tests` folder. Run `MainKaffee.java` in `src/main`, select the file you wish to analyze by entering its filename in the terminal, and choose the type of analysis you would like the program to perform: lexical, syntax, or semantic. The program will then display any errors in your Kaffee code, based on your selection.

The syntax of Kaffee is inspired by C++ but has been simplified for ease of use. Check `tests` folder to see examples.

<br />

> Note: Kaffee Analyzer is by no means a complete program, and while it offers functionality, it may contain bugs and exhibit limitations under certain conditions. The developers acknowledges these issues and was constrained by the project's deadline, which prevented comprehensive bug fixing and refinement.

## Group Members

- Jerome Saulo
- Geronimo Dayos III
- Francesca Linda Ramos
- Radge Esor Bernardino



---

*Kaffee Analyzer was built to fulfill the requirements of Automata and Formal Languages (CS0023) at FEU Alabang. The project was submitted during the 1st semester of A.Y. 2022-2023.*
