# Student Performance Analytics Engine

A Python and NumPy project that analyzes a synthetic dataset of 500 students across six subjects.

## Features

- Generates a reproducible 500 × 6 marks matrix
- Calculates subject-wise mean, median, standard deviation, and variance
- Calculates student-wise statistics and percentages
- Ranks students by total marks
- Detects unusual marks using Z-scores and NumPy broadcasting
- Exports student results, subject summaries, and outlier reports to CSV

## Technologies Used

- Python
- NumPy
- Pandas
- Google Colab
- GitHub

## Project Structure

- `student-performance-analytics.ipynb` — complete analysis notebook
- `student_results.csv` — student marks, totals, percentages, and rankings
- `subject_summary.csv` — subject-wise statistics
- `outliers.csv` — unusual marks identified by Z-scores

The CSV files are generated when the notebook is executed. Downloaded files are not automatically uploaded to GitHub.

## How to Run

1. Open the notebook in Google Colab.
2. Run each code cell from top to bottom.
3. Review the tables and outlier results.
4. Download the generated CSV reports.

## Dataset

The project uses randomly generated synthetic marks. It does not use real student records.

## Learning Outcomes

This project demonstrates NumPy arrays, axis-based calculations, broadcasting, statistical analysis, sorting and ranking, Pandas DataFrames, and CSV export.

## Future Improvements

- Visualize marks with Matplotlib
- Add pass/fail analysis
- Compare student performance across subjects
- Build a simple interactive dashboard

## Author

Lokesh Chaudhary
