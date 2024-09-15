Book Data Cleaning and Analysis Project
Project Overview
This project involves cleaning, analyzing, and visualizing a dataset of books using R. The goal of this project is to explore various attributes of books, 
including ratings, authors, publishers, and content length, and to discover insights about the most prolific and highest-rated authors and publishers. 
Additionally, the project includes advanced techniques such as text tokenization, cosine similarity calculations, and machine learning models for predictive analysis.

Technologies and Packages Used
R Programming Language
Libraries Used:
stringdist - for string distance calculations
plotly - for interactive visualizations
ggplot2 - for data visualization
quanteda - for text analysis and manipulation
tidyverse - for data cleaning and transformation
neuralnet, e1071, caret - for machine learning models
Project Components
Data Cleaning:

Loaded and cleaned a dataset of over 11,000 books.
Removed incomplete records and converted columns into appropriate data types for analysis (e.g., publication date, average rating, number of pages).
Publisher Analysis:

Tokenized and cleaned publisher names using the quanteda package, removing stopwords and unnecessary tokens like "Inc."
Created a document feature matrix (DFM) for publishers and performed frequency analysis on common publisher names.
Developed cosine similarity calculations to identify similar publishers based on their names.
Factorizing Publisher Names:

Used the cosine similarity results to factorize publisher names and create a new column for analysis.
Analysis of Authors and Publishers:

Identified the most prolific authors and publishers.
Conducted analyses on the authors who publish the longest books and the publishers with the largest catalogs.
Created visualizations such as scatter plots and heatmaps to explore relationships between ratings, number of books, and length of content.
Machine Learning Models:

Implemented a Support Vector Machine (SVM) model to predict book ratings based on attributes like the number of pages and the number of text reviews.
Evaluated model accuracy and performed a confusion matrix analysis.

Visualizations
Created interactive word clouds for publishers and scatter plots with plotly.
Generated heatmaps and scatter plots to visualize relationships between book attributes.

How to Run This Project
Clone the repository:
git clone https://github.com/murphyi00/books.git
Install the required R packages:
install.packages(c("stringdist", "plotly", "ggplot2", "quanteda", "tidyverse", "neuralnet", "e1071", "caret"))
Open and run the R script in your preferred R environment (e.g., RStudio)
