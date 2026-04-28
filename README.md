# **Python Assignment (BCB5460)**
This repository contains all the files required to complete the Python assignment provided by Dr. X. 
The goal of this assignment is to analyze and visualize biological sequence data, integrating with phenotypic data using Python.

## Repository Contents

- **BCB5460 Python.ipynb**  
 Jupyter notebook documenting the full workflow, including code, explanations, and outputs. 
- **penguins_cytb.fasta**  
 FASTA file containing cytochrome-b DNA sequences for 12 penguin species.
- **penguins_mass.csv**  
 CSV file containing average adult body mass for each penguin species.
- **penguins_mass_cytb.csv**  
 Final output DataFrame including species, body mass, GC content, and molecular weight.
- **sequence_translate.py**  
Original assignment instructions and partially completed script provided by Dr. X.

## Data Processing Workflow

The notebook executes the subsequent functions:
1. Reads cytochrome-b sequences using BioPython (`SeqIO`)
2. Translates DNA sequences into amino acid sequences  
3. Calculates GC content  and Molecular weight of amino acid sequences  
4. Integrates all computed values into a **pandas DataFrame** containing penguin body mass  
5. Exports the final processed dataset as a `.csv` file  

## Visualizations

### 1. Bar Plot – Body Mass by Species
- Displays body mass across penguin species  
- Sorted to identify smallest and largest species  
### 2. Scatter Plot – Molecular Weight vs GC Content
- Color gradient represents molecular weight variation  
- Helps evaluate relationships between nucleotide composition and protein size  

## Bonus Analysis

Additional visualizations were added to explore the dataset further:

### Enhanced Scatter Plot
- Point size represents **body mass**  
- Color represents **species**  
- Includes regression line to show trends  

### Correlation Heatmap
- Displays relationships among body mass, GC content, and molecular weight  
- Helps identify patterns and correlations  
