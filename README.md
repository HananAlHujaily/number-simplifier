Overview
--------

This Python script simplifie numbers,and percentages values in German-language text, preserving contextual meanings and improving readability. It utilizes regular expressions to process input, rounding numbers according to German conventions and handling dates in standard German formats. Non-German words are ignored, with only numbers being rounded and contextualized. The script also provides helpful explanations for numerical data. However, further improvements using NLP could significantly enhance its functionality and adaptability by enabling smarter content understanding and context-aware processing.

Features
--------

Number Simplification: Rounds large numbers according to predefined rules (e.g., rounding millions to thousands) while avoiding changes to numbers related to dates.
Percentage Simplification: Simplifies common percentages (e.g., 25%, 50%, 75%) and provides human-readable explanations.
Monetary Value Context: Adds explanations for monetary values based on the amount (e.g., comparing amounts to car prices).
Contextual Explanations: Adds contextual descriptions to numbers (e.g., "1 Million" → "So much money you could buy 100 cars").


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

