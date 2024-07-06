

### Repository Name
**Netflix-Recommendation-System**

### Description
A Netflix recommendation system project focused on data cleaning, preparation, and analysis to improve movie recommendations using TMDB data.

---

 **README File Content**

```markdown
# Netflix Recommendation System

Overview
This project aims to build a Netflix recommendation system using data cleaning, preparation, and analysis techniques. The dataset is sourced from TMDB (The Movie Database) and includes various attributes like movie titles, genres, runtime, and user votes.

###Project Steps

### 1. Data Cleaning
- Checked for null values and rows with zero runtime.
- Filled missing data for runtime and overview using the TMDB API.
- Extracted specific data, converted text to lowercase, removed spaces, and combined relevant data into new columns.
- Joined lists in "tag", "tag_genres", and "tag_ppl" into single string values.

### 2. Data Preparation
- Created a new dataframe, `df_ready_to_vector`, by selecting relevant columns and renaming them.
- Ensured the dataframe is ready for further analysis and modeling.

### 3. Analysis
- Analyzed the cleaned and prepared dataset to derive insights and recommendations.
- Used various data visualization tools to display the data and findings.

## Key Features
- Data cleaning and preprocessing to ensure data quality.
- API integration to fill missing data.
- Dataframe preparation for analysis and modeling.
- Exploratory data analysis and visualization.

## Tools and Technologies
- Python
- Pandas
- NumPy
- TMDB API
- Data visualization libraries (e.g., Matplotlib, Seaborn)
```

Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/maheshwarianmol/Netflix-Recommendation-System.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Netflix-Recommendation-System
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

**Usage**
1. Run the data cleaning script:
   ```bash
   python data_cleaning.py
   ```
2. Prepare the dataframe for analysis:
   ```bash
   python data_preparation.py
   ```
3. Perform exploratory data analysis:
   ```bash
   python data_analysis.py
   ```
