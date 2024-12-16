Overview
--------

This Python script is designed to simplify large numbers, percentages, and monetary values in text while preserving contextual meanings and improving readability ( In German Lanague ). It uses regular expressions to process input text and provides helpful contextual explanations for numbers, percentages, and monetary values. The main purpose of this tool is to make complex numerical data more understandable to a wider audience, such as when presenting technical reports or educational content.

Features
--------

Number Simplification: Rounds large numbers according to predefined rules (e.g., rounding millions to thousands) while avoiding changes to numbers related to years.
Percentage Simplification: Simplifies common percentages (e.g., 25%, 50%, 75%) and provides human-readable explanations.
Monetary Value Context: Adds explanations for monetary values based on the amount (e.g., comparing amounts to house prices, car prices, or vacations).
Contextual Explanations: Adds contextual descriptions to numbers (e.g., "1 Million" → "So much money you could buy 100 cars").
Date Preservation: Preserves date-related values and avoids modifying numbers that are part of date references.

Installation:
-------------

To use this script, simply clone the repository or download the Python file. The script does not have external dependencies, so you can run it in any Python environment.
---------------------------------------------------------------------------------------------------------------------
git clone https://github.com/HananAlHujaily/number-simplifier.git

cd number-simplifier

----------------------------------------------------------------------------------------------------------------------------

Alternatively, if you just want to use the script in your project, copy the content of simplify_numbers.py into your project directory.

Usage
-----

You can use the simplify_numbers function in your Python code by importing it and passing a string of text that you want to simplify. The function will return a new string with numbers, percentages, and monetary values simplified with contextual explanations.

