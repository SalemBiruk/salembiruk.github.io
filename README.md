# salembiruk.github.io

Salem Biruk's Data Analysis Portfolio
Welcome to my data analysis portfolio! This repository showcases a collection of projects that demonstrate my ability to analyze and interpret data using various tools and techniques. Each project is designed to handle data, perform analysis, and present results in a meaningful way.

Table of Contents
Library Inventory Sorter (C++)
Calorie and Protein Intake Tracker (C++)
Simple Python Calculator
Feels Like Temperature Calculator (x86 Assembly)
Data Analysis Techniques and Visualizations
Installation Instructions
Usage Guidelines
Contribution Guidelines
Acknowledgments
Contact Information


1. Library Inventory Sorter
1.1 Overview
The Library Inventory Sorter project is a C++ program that manages and organizes a library's book inventory. This tool sorts and analyzes book data to optimize the organization of a library's resources.

1.2 Data Analysis Focus
Data Cleaning: The project reads book data from a file and ensures that it is in a standardized format before processing.
Sorting and Analysis: Implements Bubble Sort to organize books alphabetically by title, which helps in understanding patterns and distribution of books.
Visualization: Outputs sorted book data in a structured table format, which can be used for further analysis or reporting.
1.3 Example Usage
To compile and run the Library Inventory Sorter, use the following commands:

Compile the Program:

bash
Copy code
g++ -o library_inventory_sorter library_inventory_sorter.cpp
Run the Program:

bash
Copy code
./library_inventory_sorter books.txt
Where books.txt is a file containing book data.

1.4 Source Code
View and run the code on Replit: Library Inventory Sorter.

cpp
Copy code
#include <iostream>
#include <string>
#include <fstream>
#include <iomanip>
using namespace std;

// Definitions and implementations
// The implementation details focus on data sorting and clean output for analysis
2. Calorie and Protein Intake Tracker
2.1 Overview
The Calorie and Protein Intake Tracker is a C++ application designed to help users monitor their nutritional intake. It collects data on calorie and protein consumption, providing a detailed summary and analysis of dietary habits.

2.2 Data Analysis Focus
Data Collection: Allows users to input data about different food items and their nutritional content.
Aggregation and Summarization: Calculates total calorie and protein intake, offering insights into dietary patterns.
Recommendations: Analyzes the intake data to provide personalized dietary recommendations based on user inputs.
2.3 Example Usage
Compile the Program:

bash
Copy code
g++ -o calorie_protein_tracker main.cpp calorie.cpp protein.cpp
Run the Program:

bash
Copy code
./calorie_protein_tracker
Follow the prompts to input your nutritional data.

2.4 Source Code
View and run the code on Replit: Calorie and Protein Intake Tracker.

cpp
Copy code
#include <iostream>
#include <vector>
using namespace std;

// Definitions and implementations
// The implementation details focus on data collection and summarization for nutritional analysis
3. Simple Python Calculator
3.1 Overview
The Simple Python Calculator is a versatile tool for performing arithmetic operations. Although primarily a calculator, it demonstrates basic data handling and processing in Python.

3.2 Data Analysis Focus
Arithmetic Operations: Performs various calculations, providing insights into numerical data processing.
Input Validation: Ensures accurate and meaningful results by validating user inputs.
Data Interpretation: Allows users to interactively analyze numerical data through calculations.
3.3 Example Usage
Run the Program:

bash
Copy code
python simple_calculator.py
Choose an operation and provide input numbers.

3.4 Source Code
View and run the code on Replit: Simple Python Calculator.

python
Copy code
def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "Error! Division by zero."
    else:
        return x / y

def calculator():
    while True:
        # Prompts and operations for basic data analysis
4. Feels Like Temperature Calculator (x86 Assembly)
4.1 Overview
The Feels Like Temperature Calculator is an x86 assembly language program that computes the "feels like" temperature based on temperature, wind speed, and humidity. This project demonstrates low-level data manipulation and computation.

4.2 Data Analysis Focus
Data Collection: Receives temperature, wind speed, and humidity as input parameters.
Computational Analysis: Applies specific formulas to compute the "feels like" temperature, demonstrating how raw data can be transformed into meaningful results.
Output Formatting: Provides clear and precise results for further analysis or use in applications.
4.3 Example Usage
Assemble and run the program to compute temperature data:

Assemble the Program:

bash
Copy code
nasm -f elf32 feels_like_temperature_calculator.asm -o feels_like_temperature_calculator.o
ld -m elf_i386 -o feels_like_temperature_calculator feels_like_temperature_calculator.o
Run the Program:

bash
Copy code
./feels_like_temperature_calculator
4.4 Source Code
View and run the code on Replit: Feels Like Temperature Calculator.

assembly
Copy code
; Assembly code for calculating "feels like" temperature
; The code demonstrates low-level data manipulation for temperature analysis
5. Data Analysis Techniques and Visualizations
5.1 Overview
In addition to the individual projects, this section focuses on advanced data analysis techniques and visualizations. These techniques are used to interpret data and present it in a meaningful way.

5.2 Techniques
Statistical Analysis: Perform statistical analysis on datasets to identify trends, patterns, and anomalies.
Data Visualization: Create visual representations of data using charts, graphs, and tables to enhance understanding.
Predictive Modeling: Apply machine learning algorithms to predict future trends based on historical data.
5.3 Example Visualizations
Library Inventory Analysis: Create visualizations of book distribution and library usage patterns.
Nutritional Analysis: Visualize calorie and protein intake trends over time.
Temperature Data Analysis: Use visualizations to compare actual and "feels like" temperatures.
5.4 Tools and Libraries
Python Libraries: Utilize libraries such as Matplotlib, Seaborn, and Pandas for data analysis and visualization.
Excel: Use Excel for basic data analysis and charting.
Tableau: Employ Tableau for advanced data visualization and dashboard creation.
5.5 Example Code
Here’s a sample Python script for visualizing nutritional intake data:

python
Copy code
import matplotlib.pyplot as plt
import pandas as pd

# Sample data
data = {'Food': ['Apple', 'Chicken', 'Rice'],
        'Calories': [52, 239, 130],
        'Protein': [0.3, 27.3, 2.7]}

df = pd.DataFrame(data)

# Plotting
plt.figure(figsize=(10, 5))
plt.bar(df['Food'], df['Calories'], color='blue', alpha=0.7, label='Calories')
plt.bar(df['Food'], df['Protein']*10, color='red', alpha=0.7, label='Protein (x10)')
plt.xlabel('Food')
plt.ylabel('Nutritional Value')
plt.title('Nutritional Intake Visualization')
plt.legend()
plt.show()
6. Installation Instructions
6.1 Prerequisites
C++ Compiler: For C++ projects, use g++.
Python: For Python projects, ensure Python is installed.
Assembler: Use nasm for assembly language projects.
Data Analysis Tools: Install libraries such as Matplotlib, Pandas, and Seaborn using pip.
6.2 Installation Steps
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/salem-biruk-portfolio.git
cd salem-biruk-portfolio
Compile C++ Projects:

bash
Copy code
cd library-inventory-sorter
g++ -o library_inventory_sorter library_inventory_sorter.cpp
bash
Copy code
cd ../calorie-protein-tracker
g++ -o calorie_protein_tracker main.cpp calorie.cpp protein.cpp
Run Python Projects:

bash
Copy code
cd ../simple-calculator
python simple_calculator.py
Assemble Assembly Projects:

bash
Copy code
cd ../feels-like-temperature-calculator
nasm -f elf32 feels_like_temperature_calculator.asm -o feels_like_temperature_calculator.o
ld -m elf_i386 -o feels_like_temperature_calculator feels_like_temperature_calculator.o
Install Python Libraries:

bash
Copy code
pip install matplotlib pandas seaborn
7. Usage Guidelines
Library Inventory Sorter: Input data file with book details for sorting and analysis.
Calorie and Protein Tracker: Follow on-screen prompts to enter and analyze nutritional data.
Simple Python Calculator: Use for basic numerical analysis and calculations.
Feels Like Temperature Calculator: Enter temperature, wind speed, and humidity for "feels like" temperature analysis.
8. Contribution Guidelines
Fork the Repository: Click “Fork” on GitHub to create a personal copy.
Clone the Fork: Clone your forked repository.
bash
Copy code
git clone https://github.com/yourusername/salem-biruk-portfolio.git
Create a Branch: Create a branch for your contributions.
bash
Copy code
git checkout -b feature-branch
Make Changes: Implement changes in your branch.
Commit Changes: Commit your updates with a descriptive message.
bash
Copy code
git commit -m "Added new data analysis feature"
Push Changes: Push changes to your forked repository.
bash
Copy code
git push origin feature-branch
Create Pull Request: Submit a pull request from your forked repository to the main repository.
9. Acknowledgments
Special Thanks: To Replit and other platforms for enabling project execution and testing.
Inspirations: Inspired by data analysis challenges and real-world data handling applications.
10. Contact Information
Email: salembiruk3@gmail.com
Phone: 702-957-0368
GitHub Profile: Salem Biruk
Feel free to reach out with any questions or opportunities for collaboration!


