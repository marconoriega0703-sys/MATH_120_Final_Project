# Python Final Project: Pokemon Data Analysis

## Project Overview
This project demonstrates data processing and analysis techniques using Python tools learned throughout the semester. The notebook focuses on examining Pokémon across Generations 1-6 and comparing their total base stats. The project incorporates data cleaning, merging, classes, and visualization.  

## Project Structure
```
python_final_project/
├── data_raw/                 # Original data files
│   └── Pokemon.csv           # Raw pokemon dataset
├── data_cleaned/                    # Cleaned data files
│   └── cleaned_pokemon.csv  # (Can be downloaded by running the download cell)
├── notebooks/                    # Cleaned data files
│   └── MATH_120_Final_Project_Final_Draft.ipynb
├── MATH 120 Final Written Draft.pdf    
└── README.md               # This file

## Requirements
- Python 3.7+
- pandas
- plotly.express
- files
- jupyter (for local execution)

## Installation and Setup

### Local Execution
1. Clone this repository:
   ```bash
   git clone https://github.com/marconoriega0703-sys/MATH_120_Final_Project.git
   cd python_final_project
   ```

2. Install required packages (if needed):
   ```bash
   pip install pandas plotly.express files jupyter
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook MATH_120_Final_Project_Final_Draft.ipynb
   ```
4. Dataset
   ```bash
   https://www.kaggle.com/datasets/abcsds/pokemon
   ```

### Google Colab Execution
1. Open [Google Colab](https://colab.research.google.com/drive/1Bl55AAWnxjGPW5tzQx1MbRHMXNGy6Rsy#scrollTo=KyUNJTHNevQX)
2. Upload the `MATH_120_Final_Project_Final_Draft.ipynb` file or connect to your GitHub repository
3. Run the first cell to automatically set up the environment

## Data Description
The raw Pokémon dataset consists of 721 unique Pokémon. This dataset includes different forms of the same Pokémon species, resulting in multiple rows having the same Pokédex ID number. The cleaning process removes these form differences.

## Analysis Features
- Data loading and cleaning
- Data merging operations
- Data visualization with plotly.express

## Key Learning Objectives Demonstrated
- File I/O operations with pandas
- Data cleaning and preprocessing
- Data merging and joining
- Statistical analysis
- Data visualization
- Classes and Function creation
- Environment compatibility (local vs. cloud)
## Usage
Run all cells in `MATH_120_Final_Project_Final_Draft.ipynb` sequentially. The notebook will:
1. Set up the environment automatically
2. Load and clean the raw data
3. Perform statistical analysis
4. Generate visualizations
5. Saves cleaned data to the user's downloads

## Author
[Marco Noriega]  
[MATH 120] - [Fall/2025]
