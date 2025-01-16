# Uncommon HTML Bug: Unclosed Script Tag and incorrect getElementById

This repository demonstrates a subtle bug in HTML involving an unclosed script tag and incorrect usage of getElementById.  The bug can be hard to spot in larger codebases.

## Bug Description

The `bug.html` file contains an HTML document with a script tag that is not properly closed. This leads to the browser misinterpreting the subsequent HTML, potentially causing unexpected behavior or rendering errors.  Additionally, the script uses an incorrect way to select an element by ID in javascript.  The '#' symbol is missing. 

## Bug Solution

The `bugSolution.html` file demonstrates the corrected HTML with a properly closed script tag and the correct use of getElementById in javascript. 

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser. Observe the errors in the browser's developer console and the incorrect rendering of the page.
3. Open `bugSolution.html` in a web browser. Observe the correct rendering and the absence of errors.