# NumPy Data Filtering

## Description
This project demonstrates numerical data filtering using NumPy Boolean conditions and Boolean indexing. It identifies values above, below, and equal to specified thresholds.

## Objective
To practice Boolean indexing and numerical filtering using NumPy.

## Tools Used
- Python
- NumPy
- Google Colab

## Dataset
- Student marks
- Sales values

## Operations Performed
- Created NumPy arrays containing numerical values.
- Filtered values greater than a threshold.
- Filtered values less than a threshold.
- Identified values equal to a threshold.
- Applied different threshold conditions.
- Filtered sales data using Boolean indexing.

## Code Example
python
import numpy as np

marks = np.array([35, 45, 50, 60, 75, 80, 90, 25, 55, 65])

print("Marks above 50:", marks[marks > 50])
print("Marks below 50:", marks[marks < 50])
print("Marks equal to 50:", marks[marks == 50])


## Expected Output
text
Marks above 50: [60 75 80 90 55 65]
Marks below 50: [35 45 25]
Marks equal to 50: [50]


## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run the cells sequentially.
3. Observe the filtered results.

## Outcome
Successfully implemented NumPy data filtering using Boolean indexing and different numerical thresholds.

## Author
Archita
