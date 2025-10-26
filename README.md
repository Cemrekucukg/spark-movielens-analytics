Spark MovieLens Analytics
--------------------------
This project applies Apache Spark (PySpark) to analyze the MovieLens 100K dataset.
It aims to explore user ratings, identify the most popular movies, and demonstrate practical usage
of Spark DataFrame and SQL APIs for large-scale data processing.
1. Project Overview
------------------The MovieLens dataset contains user ratings for various
movies.
Using PySpark, this project
performs:
- Calculation of average movie
ratings
- Identification of the most rated
movies
- Basic user behavior
analysis
2. Technologies Used
-------------------- Python
3.10+
- Apache Spark
(PySpark)
-
Pandas
-
Matplotlib
3. Dataset
---------Source:
https://grouplens.org/datasets/movielens/100k/
Main files included:
- u.data — User–movie–rating–timestamp records
- u.item — Movie titles and genres
- u.user — User demographic data
4. Analysis Workflow
-------------------1. Initialize a
SparkSession.
2. Load the u.data file into a Spark
DataFrame.
3. Select key columns (user_id, movie_id, rating,
timestamp).
4. Compute the average rating for each
movie.
5. Sort and visualize results using
Matplotlib.
5. How to Run
------------Run
Locally:
pip install pyspark pandas
matplotlib
python
spark-movielens.ipynb
Run on Google Colab:
1. Upload the notebook to Colab.
2. Install dependencies:
!pip install pyspark pandas matplotlib
3. Execute the cells step by step.

---
Developed by Cemre Küçükgöde
Portfolio: https://cemrekucukgode.com
GitHub: https://github.com/Cemrekucukg
LinkedIn: https://www.linkedin.com/in/cemre-kucukgode-/
Email: cemrekucukg@gmail.com
