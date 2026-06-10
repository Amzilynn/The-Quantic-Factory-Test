# Vélib' Métropole – Spatial Distribution Analysis

This repository contains an analysis of Vélib' bike-share stations in Paris, examining their spatial distribution between the city center and the periphery.

## Prerequisites

To run this notebook, you will need **Python** installed on your machine. We recommend Python 3.8 or higher.

## Setup and Installation

1. **Clone the repository** (or download the files):
   ```bash
   git clone https://github.com/Amzilynn/The-Quantic-Factory-Test.git
   cd The-Quantic-Factory-Test
   ```

2. **Install the required dependencies**:
   The notebook relies on a few Python libraries (like `pandas`, `requests`, `matplotlib`, `seaborn`, and `jupyter`). You can install them using the provided `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

## How to Open and Run

There are a few ways to view and run the analysis:

### Option 1: Using Jupyter Notebook (Browser)
1. Open your terminal or command prompt in the project directory.
2. Run the following command:
   ```bash
   jupyter notebook
   ```
3. Your web browser will open automatically. Click on `velib_analysis.ipynb` to open it.
4. To run the analysis, click on **Cell > Run All** in the top menu, or run each cell individually using `Shift + Enter`.

### Option 2: Using Visual Studio Code (or similar IDEs)
1. Open the project folder in VS Code.
2. Open the `velib_analysis.ipynb` file.
3. Make sure you have the Jupyter extension installed in VS Code.
4. Select your Python environment in the top right corner.
5. Click **Run All** at the top of the notebook.

### Option 3: Running from the Command Line (Headless Execution)
If you just want to execute the notebook from start to finish without opening an interactive window, you can run:
```bash
jupyter nbconvert --to notebook --execute velib_analysis.ipynb
```
*Note: This will create a new file named `velib_analysis.nbconvert.ipynb` containing the executed outputs.*
