libDetectGender
===============

A simple library stack that provides a data based function to detect user gender based on first name. Future versions will implement results from machine learning + larger datasets.

Currently there is one function that handles all the work:

================================
theDetectedGender (function)
pfirstname (parameter)

The function returns one of 3 values: "Male", "Female", "Unknown".
"Unknown" is return when the name is rare and not found  in the  dataset, or when the name is found in both the male and female dataset.

Example:
answer theDetectedGender("Jason") // SHOWS A ANSWER DIALOG WITH "Male"
