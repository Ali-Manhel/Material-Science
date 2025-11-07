Tensile Test Data Processor
A Python script that automates the analysis of tensile test data exported as XML files. It extracts load and strain data, computes stress–strain curves, detects fracture points, and calculates key mechanical properties such as elastic modulus, yield strength, ultimate tensile strength, fracture stress, resilience, and toughness.

The program generates:

Raw and trimmed stress–strain plots with labeled key points

A summary table of mechanical properties

A CSV file (mechanical_properties_summary.csv) for easy data export

How to use:
Edit the file list and specimen diameters in the “User Editable” section, then run the script in Jupyter Notebook or directly via terminal (python tensile_analysis.py).

Requirements:
Python 3.8+, NumPy, Matplotlib, and Pandas

Ideal for materials testing labs and engineering students who need fast, standardized tensile data analysis.

This project is for educational purposes only. 
Please do not reuse or submit this code as your own.
