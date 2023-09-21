# Project for CS 5500

## JSONAPI

This package is an extended json encoder and decoder. 

## Installation

command: pip install .

## Sample Code

*Dumps*

from jsonapi import dumps

complex_number = 3 + 4j
json_string = dumps(complex_numer)
print(json_string) // Output: '[3.0, 4.0]'