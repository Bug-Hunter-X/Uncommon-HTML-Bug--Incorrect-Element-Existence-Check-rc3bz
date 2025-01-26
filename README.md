# Uncommon HTML Bug: Incorrect Element Existence Check

This repository demonstrates a subtle bug in JavaScript code within an HTML file. The bug involves incorrectly checking for the existence of an element before attempting to manipulate its properties.

## Bug Description

The provided HTML uses JavaScript to check if a div element exists before setting its display style to 'none'. However, the conditional statement is flawed and will always hide the div, regardless of its existence.  The issue lies in the incorrect order of operations in the conditional statement: `!document.getElementById('myDiv') == null`.

## Solution

The solution involves correctly restructuring the conditional statement to ensure it accurately checks if the element exists before attempting to modify it.