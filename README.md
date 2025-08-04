Task 1: Data Cleaning & Preprocessing**  
**Dataset Source:** [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)



🔍 Objective

To clean and preprocess the Netflix dataset by:
- Identifying and handling missing values
- Removing duplicates
- Standardizing formats
- Renaming columns
- Ensuring consistent and correct data types

🧰 Tools Used

- Python
- Pandas
- Jupyter Notebook / VS Code


🧼 Cleaning Steps Performed

1. **Handled Missing Values**
   - Filled `director` and `cast` columns with `'Unknown'`
   - Filled `rating` with `'Not Rated'`
   - Dropped rows with missing `country`, `date_added`, or `duration`

2. **Removed Duplicate Records**
   - Used `.drop_duplicates()` to remove exact duplicates

3. **Standardized Text Values**
   - Cleaned white spaces using `.str.strip()`
   - Converted values in `type`, `country`, and `rating` to proper case (title or upper)

4. **Converted Date Formats**
   - Converted `date_added` to a consistent format `dd-mm-yyyy`

5. **Renamed Column Headers**
   - Made all column names lowercase and replaced spaces with underscores

6. **Checked and Fixed Data Types**
   - Converted `date_added` to `datetime` type
   - Ensured `release_year` is an integer


✅ Final Output

- Total records after cleaning: *(Add the number after running the script)*
- Missing values successfully handled
- Dataset ready for analysis or modeling
