# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a subtle yet common bug in HTML/JavaScript: a typo in the `getElementById` method.

## The Bug

The `bug.html` file contains a simple HTML page with a div element and a JavaScript script. The script attempts to modify the innerHTML of the div, but it contains a typo in the `getElementById` method, using `getElementByIdx` instead.

This results in a runtime error because `getElementByIdx` is not a defined method.

## The Solution

The `bugSolution.html` file demonstrates the correct way to access the `innerHTML` property using the correct method name `getElementById`.