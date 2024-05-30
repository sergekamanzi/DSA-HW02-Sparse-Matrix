# DSA-HW02-Sparse-Matrix


DESCRIPTION
This project allows you to perform operations (addition, subtraction, multiplication) on sparse matrices. Sparse matrices are matrices in which most elements are zero. The project reads two sparse matrices from input files, performs the specified operation, and writes the result to an output file.

Prerequisites
Python 3.x
Usage
Clone the repository:
git clone "https://github.com/sergekamanzi/DSA-HW02-Sparse-Matrix.git"
Navigate to the project directory:
cd DSA-HW02-Sparse-Matrix
Ensure your input files are in the sample_inputs directory.

Run the script:

python code/src/sparse_matrix.py
Follow the prompts to select the operation and input files. The result will be saved to code/outputs/result.txt.
Input File Format
The input files should have the following format:

The first line specifies the number of rows.
The second line specifies the number of columns.
Each subsequent line specifies a non-zero element in the format (row, column, value).
Example:

rows=3
cols=3
0 0 1
1 2 2
2 1 3
Output
The result of the operation will be saved in code/outputs/result.txt.

NOTES
Ensure the matrices conform to the mathematical rules for the selected operation.
Handle file paths and ensure input files exist in the specified directory.
