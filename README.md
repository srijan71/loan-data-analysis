# loan-data-analysis
In this project we have successfully managed to 
1) Clean the dataset
2) Preprocess the dataset
3) Prepare the dataset for further analysis


Following steps are performed:-

1. Importing the packages - The necessary packages were imported to enable data analysis and manipulation, numpy.
2. importing the data - The data was imported into the analysis environment from the specified source, ensuring accessibility for further processing and exploration.    The file was in .csv format.
3. Checking for incomplete data - The dataset was examined to identify and address any missing or incomplete data points, ensuring the integrity and quality of the      analysis.
4. Splitting the Dataset - The dataset was divided into two separate sets: one containing numeric data for quantitative analysis, and another containing string data for  categorical analysis, facilitating a comprehensive examination of the dataset.
5. Reimporting the data - The data was reimported and transformed into two separate datasets: one with numeric values for quantitative analysis, and another with string  values for categorical analysis, allowing for specific analysis techniques tailored to each data type.
6. Created Checkpoints - A checkpoint function was created to save the progress and preserve the current state of the work, ensuring the ability to resume from this      point if needed without losing any modifications or analyses performed and further work can be stored by just calling the function.
7. Manipulating String Columns - String columns were manipulated by applying various transformations such as removing leading/trailing spaces, filling missing values, removing undesired columns, converting strings to integers(to make it short and easy for analysis), enabling better data organization.
8. Manipulating Numeric Columns - Numeric columns were manipulated by filling missing values using appropriate techniques such as mean, max and min. Exchange rates from USD to EUR were incorporated to convert monetary values into their EUR equivalents, enabling consistent currency analysis and comparisons. 
9. Created the Complete Dataset - The preprocessed versions of the string and numeric data were combined to create a comprehensive "Complete" dataset, merging the transformed columns and ensuring all necessary information is available for further analysis and modeling.
10. Sorting and Storing the new dataset - The dataset was sorted based on the ID column, arranging the records in ascending or descending order. The sorted dataset was then stored, preserving the new order for future reference and analysis.
