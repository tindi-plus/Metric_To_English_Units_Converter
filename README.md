# Metric To English Units Converter

![pexels-pixabay-162500](https://user-images.githubusercontent.com/78483332/147291804-0476217e-295f-4d7c-9f0d-3ef5a1b55778.jpg)

## Introduction
This is a program that converts Metric units to their English counterparts. It can also convert from English to Metric Units.

# Installation
The program uses Pandas and Python's regular expression library re. If you do not already have pandas installed, you can install it from [Pypi](https://pypi.org/project/pandas/) by running ***pip install pandas*** on your command line. The ***re*** library is aleady installed with python installation. 

# Description
To use the program, the input must be in the following format: ***How many inches are in 10 meters?*** Also, all units in the input must be in plural, for example, it is inches and not inch, even when you are referring to 1 inch. Currently, the program supports the following units conversions:
  * Length: The following table shows the table and the conversion constants. The conversion constant is located at the intersection of the row and a column. For example, the conversion constant for yards to centimeters is 91.44.
  
                                                      |        | millimeters | centimeters | meters | kilometers |
                                                      | ------ |-------------|-------------|--------|------------|
                                                      | inches | 25.4        | 2.54        | 0.0254 | 0.0000254  |
                                                      | yards  | 914.4       | 91.44       | 0.9144 | 0.0009144  |
                                                      | feet   | 304.8       | 30.48       | 0.3048 | 0.0003048  |               
                                                      
  * 

Authors And 
