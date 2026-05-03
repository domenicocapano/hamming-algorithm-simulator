[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20011269.svg)](https://doi.org/10.5281/zenodo.20011269)
# Hamming Algorithm Simulator (Single-Bit Error Detection and Correction)

## Online Simulator

👉 https://domenicocapano.github.io/hamming-algorithm-simulator/

This simulator can be used directly in the browser without installation.
## Description

This project is an educational simulator designed to illustrate the functioning 
of the **Hamming algorithm** for detecting and correcting single-bit errors 
in binary data transmission.

The simulator allows students to:

* Insert binary data
* Automatically compute control bits (parity bits)
* Visualize the generated codeword
* Simulate transmission errors
* Detect and correct the error using syndrome calculation
* Understand the logic behind parity subsets and error localization

The implementation is based on the classical formulation of the Hamming code:

(d + c + 1) ≤ 2^c

where:

* d = number of data bits
* c = number of control bits

## Educational Objectives

This simulator is intended for:

* Secondary technical schools (ITIS)
* Introductory courses in computer networks and digital systems
* Learning Object–based instructional design

Students can visually understand:

* Why control bits are placed at positions 2^k
* How parity subsets are generated using binary indexing
* How the syndrome identifies the exact error position

## Features

* Interactive binary input
* Automatic computation of control bits
* Visual codeword representation
* Error simulation via click
* Step-by-step decoding process
* Explanation modal (mathematical reasoning)
* Subset visualization panel
* Fully responsive (desktop and mobile)

## How to Use

1. Download the HTML file
2. Open it with any modern browser (no installation required)
3. Enter a binary string (e.g., 10011)
4. Observe the encoding process
5. Click a bit in the receiver to simulate an error
6. Analyze and correct the error

## Technical Notes

* The simulator is implemented as a single HTML file (HTML + CSS + JavaScript)
* No external dependencies are required
* Designed for offline use in educational environments

## Theoretical Reference

The simulator is based on the formal definition of Hamming code and parity subsets, 
as described in the author's teaching material 

## Author

Domenico Capano
IISS "Carlo Emilio Gadda" – Fornovo (PR), Italy
Project: LearningObjects.org

## Citation

If you use this simulator in academic or educational contexts, please cite the author.

## License

See LICENSE file for details.
