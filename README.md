# Readme: HW00

## Author Info

Author     : Yueze Tan

Email      : yut75@psu.edu

Last update: 2018/08/26

License    : GNU (See `license.txt` for details. A copy of GPL is provided as in `gpl.txt`.)

## How to Compile on ACI

Switch to the root folder of the homework. Use the commands below:

    module load gcc/5.3.1
    make

Or you could use `make program` instead of `make`.

You should see "Make completed." if everything goes on well.

To execute the program then, type the command

    ./bin/HelloWorld

## Expected Output

The program should generate a line of text on the terminal:

	yut75 says: Hello world!

## Write-up Compilation

To compile write-ups, switch to folder `writeup`, and type the command

    cd writeup
    ./pdfmake.sh

## Acknowledgements

Please see the LaTeX write-up and its PDF output for details.

