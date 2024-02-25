Movie Recommendation System
===
This project analyzes a movie dataset to provide recommendations based on user ratings and movie correlations.

Data Description
====
The dataset used for analysis consists of movie ratings provided by users, along with corresponding movie titles and IDs.

Tools and Libraries Used
====
+ Pandas
+ Matplotlib
+ Seaborn

Setup Instructions
====
**1. Clone the repository:**
``` bash
git clone https://github.com/parulkumari2707/Movie-Recommendation.git
cd movie-recommendation-system
```


**2. Install the required dependencies:**
``` bash
pip install pandas matplotlib seaborn
```


**3. Download the dataset files:**

+ file.tsv: Contains user ratings data.
+ Movie_Id_Titles.csv: Contains movie titles and IDs.
+ Update the file paths in the code to point to the downloaded dataset files.

**4. Run the Python script:**
``` bash
python movie_recommendation.py
```

Project Overview
====
**1. Data Exploration:**
+ Load the dataset and examine its structure.
+ Check movie titles and IDs.


**2. Data Preprocessing:**
Merge user ratings data with movie titles.


**3. Data Analysis:**
+ Calculate mean and count ratings for all movies.
+ Visualize rating distributions.


**4. Recommendation System:**
+ Create a movie-user rating matrix.
+ Analyze correlations between movies.


**5. Recommendation Results:**
Display top recommended movies based on correlation.


Conclusion
====
This project demonstrates the implementation of a basic movie recommendation system using collaborative filtering and correlation analysis.

License
===
This project is licensed under the [MIT License](License).
