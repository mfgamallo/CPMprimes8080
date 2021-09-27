# CPMprimes8080
CP/M program in 8080 assembly to find prime numbers.

I wanted to try how it was to program the old 8080 using just the utilities found in CP/M 3 (ED, MAC, HEXCOM and SID).

This code will print all of the prime numbers starting from 2. It's written in assembly for the CP/M 3 macro assembler included in Locomotive CP/M Plus for the ZX Spectrum +3.

Uses BDOS just for printing ASCII. The rest is coded bottom-up: routines to 16 bit SUB and DIV/REM, as well as decimal number printing.

The code was produced with none other than CP/M's ED in an actual ZX Spectrum +3. There's a submit script to put together the final ASM file, assemle it and generate the final COM binary in one go.

There's plenty of comments in the code. The code itself is far from optimized. Optimization comes next if I don't lose interest first.
