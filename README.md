# K-mer Composition and String Reconstruction

## Project Overview
This project explores the concept of k-mer composition in strings, particularly focusing on nucleotide sequences. It involves generating k-mers of a given string and reconstructing the original string from these k-mers. This approach is fundamental in bioinformatics, especially in genome assembly and analysis. Assignment for Bioinformatics Course (CMPE549) at Bogazici University.

## Features and Tasks

### K-mer Generation
- **Example String**: Creation of a 100-length nucleotide string.
- **K-mer Calculation**: The k-mers are calculated for k values of 3, 4, 5, 20, 30, and 50.
- **Comprehensive Analysis**: Analysis of how the k-mer composition changes with different k values.

### String Reconstruction
- **Function Implementation**: A custom function `reconstruct_string_from_kmers` is implemented to reconstruct the original string using the generated k-mers.
- **Algorithm Explanation**: A detailed explanation of the chosen approach and algorithms is provided, highlighting why the approach is effective (De Bruijn Graph with Eulerian Path).

### Evaluation and Discussion
- **Reconstruction Accuracy**: Analysis of whether the reconstructed string always matches the original string.
- **Challenges and Insights**: Discussion on the challenges faced during string reconstruction and insights into when and why discrepancies might occur.

## Running the Code
- Clone this repository to your local machine.
- Run the Python script or Jupyter Notebook to execute the k-mer generation and string reconstruction.
- Review the output and the discussion section for insights into the process and results.

## Contribution
Contributions to improve the code, enhance the accuracy of string reconstruction, or extend the functionality are welcome. Please feel free to fork this repository and submit your improvements or suggestions through pull requests.

## Contact
For any questions or discussions related to this project, please email me at [dogayalova@gmail.com](mailto:dogayalova@gmail.com).
