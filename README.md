## ASCII ART
* ASCII-art is a program written in Go that takes a string as input and outputs a graphic representation of the string using ASCII characters. This program supports numbers, letters, space, special characters, and newline characters. 

## Features ##
* Input Handling :-  Accepts strings containing numbers, letters, spaces, special characters, and newline characters.
* ASCII Representation:- Converts the input string into a graphical representation using ASCII characters.
* Customizable Templates:- Provides different graphical templates such as "shadow," "standard," and "thinkertoy" for ASCII representation.
* Command-Line Interface-: Accessible via the command line for easy input and output.
* Error Handling:- Implements robust error handling to ensure reliable performance.

## Instructions

To clone this repository: use the command below on your terminal:
```
git clone https://learn.zone01kisumu.ke/git/vandisi/ascii-art-fs.git
```

## Banner Format
* Each character in the ASCII representation has a height of 8 lines. 
* Characters are separated by a newline character \n. 

The program includes several banner formats for graphical representation using ASCII characters:

* shadow
* standard
* thinkertoy
* asteric
* lean

>  The program automatically takes the banner format of `standard`, but if the user wants to using other graphical representation, the banner format desired should be the third arguement. 

## Usage
```bash
go run . [STRING] [BANNER]
```
### Running Tests
To run unit tests, navigate to the project directory and run:
```bash
go test -v
```
