# Missing Value Imputation Program (Version 3.2)

This Python program is designed to impute missing values in a dataset using both Deep Learning (DL) and Machine Learning (ML) methods. It utilizes various libraries and techniques for data preprocessing and imputation.

## Instructions

1. **Dataset**: Make sure you have the dataset file "AMR-and-NSH-Buoy-Data1394-Clean-Data.xls" placed in the "clean-xls-files" directory. The program will load this dataset for further processing.

2. **Libraries**: Ensure you have the required Python libraries installed. You can install them using pip if not already installed.

3. **Running the Program**: Execute the program by running it. There's no need to specify the program name in the command.

4. **Results**: The program will perform the following tasks:

   - Load the dataset.
   - Slice out specific columns for analysis.
   - Normalize the dataset.
   - Generate new date and time values for the dataset.
   - Impute missing values using the LassoCV estimator with Iterative Imputation.
   - Perform data analysis on non-time columns.
   - Save the imputed dataset to a CSV file.

5. **Output**: The imputed dataset will be saved to a CSV file, which you can use for further analysis or modeling.

## Version History

- Version 3.2:
  - Utilizes LassoCV estimator for Iterative Imputation.
  - Normalizes the dataset.
  - Generates date and time values.
  - Performs data analysis on non-time columns.

For earlier versions or additional details, refer to the previous README files or documentation.
