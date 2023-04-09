# Diabetes Data Analysis - CS5530 Assignment 2

This repository contains Python code to analyze the `diabetes.csv` dataset. The dataset contains data of 768 patients, including 8 attributes (Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age) and 1 response variable (Outcome). The response variable, Outcome, has binary value (1 indicating the outcome is diabetes and 0 means no diabetes). For this analysis purposes we will consider this data as a population.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this code, you'll need Python 3.x and the following packages:

- pandas
- numpy
- matplotlib

You can install these packages using pip and the requirements.txt file provided in this repository:

```bash
pip install -r requirements.txt
```

## Usage

To reproduce the analysis, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the cloned repository directory.
3. Create a virtual environment using Python's venv module: `python -m venv env`
4. Activate the virtual environment: `source env/bin/activate`
5. Install the required packages: `pip install -r requirements.txt`
6. Launch Jupyter Notebook: `jupyter notebook`
7. Open the `diabetes_data_analysis.ipynb` notebook and run the cells.

## File Structure

- `diabetes.csv`: the Diabetes dataset in CSV format.
- `diabetes_data_analysis.ipynb`: Jupyter Notebook containing the code for data analysis.
- `README.md`: this file.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the GNU Public License v3.0. See the [LICENSE](LICENSE) file for details.
