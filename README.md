# Static Code Analyzer

## Overview
The Static Code Analyzer is a tool designed to analyze code snippets and provide various metrics and visualizations to aid in understanding and improving code quality. This tool performs analysis on Python code and provides insights into metrics such as raw code metrics, reserved keywords frequency, identifiers frequency, and Abstract Syntax Tree (AST) representation.

## Features
- **Code Analysis**: Provides basic analysis of the entered code, including raw SCA metrics such as Maintainability Index and Cyclomatic Complexity.
- **Reserved Keywords Frequency**: Displays the frequency of reserved keywords used in the code through bar charts, word clouds, and pie charts.
- **Identifiers Frequency**: Shows the frequency of identifiers used in the code along with visualizations.
- **AST Representation**: Presents the Abstract Syntax Tree (AST) representation of the code for deeper understanding of its structure.

## Installation
1. Clone this repository.
2. Install the required dependencies using `pip3 install -r requirements.txt`.

## Usage
1. Run the application using Streamlit: `python3 -m streamlit run app.py`.
2. Enter the code snippet you want to analyze in the provided text area.
3. Click on the "Analyze" button to initiate the analysis.
4. Explore the various tabs to view different aspects of the code analysis and visualizations.

## Dependencies
- Streamlit
- Radon
- WordCloud
- Matplotlib
- Altair
- Plotly Express
