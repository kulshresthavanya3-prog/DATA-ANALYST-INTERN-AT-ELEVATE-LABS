# DATA-ANALYST-INTERN-AT-ELEVATE-LABS
THIS IS THE TASK-1 OF THIS INTERNSHIP AT ELEVATE LABS(IT COMPANY ,BANGALORE) 


🧹 Data Cleaning & Preprocessing — Sales Data
📌 Objective
Prepare and clean a raw dataset containing nulls, duplicates, and inconsistent formats to ensure it is ready for analysis and dashboard creation.

🛠️ Tools Used
Python (Pandas)
Google Colab
Kaggle
Excel

⚙️ Steps Performed
Missing Values Handling

Used .isnull() in Pandas and Excel filters to identify nulls.

Imputed or removed missing entries depending on attribute relevance.

Duplicate Removal

Applied .drop_duplicates() to eliminate redundant rows.
Remove irrelvant product categories  from Category Column

Date Formatting

Converted all date columns to dd-mm-yyyy format using pd.to_datetime().

Data Type Fixes

Converted object datatype attributes (Payment Method,Sales channel) to String format.

Ensured date attributes were stored as datetime.

Irrelevant Values Removal

Dropped unnecessary attributes that did not contribute to analysis.

✅ Deliverables
Cleaned Dataset: Ready for downstream analysis and dashboard integration.

Summary of Changes:

Nulls handled

Duplicates removed

Dates reformatted

Data types corrected

Irrelevant attributes removed

📊 Outcome
The dataset is now structured, consistent, and optimized for analysis. This preprocessing step ensures reliable insights when building dashboards or applying machine learning models.
