# EDA on Netflix Movies and TV Shows

This project presents a detailed Exploratory Data Analysis (EDA) of Netflix's catalog of movies and TV shows. The goal is to uncover patterns in content types, release years, countries, genres, and ratings, helping stakeholders understand Netflix’s library composition and identify opportunities for content strategy and business decisions.

## Project Objectives

* Analyze the distribution of movies and TV shows by various attributes (type, genre, country, release year).
* Explore relationships between key variables (e.g., content type vs rating, release year trends).
* Provide actionable insights for Netflix content strategy, regional targeting, and catalog management.
* Deliver clean, well-commented, production-ready code that runs end-to-end without errors.

## Key Features of This Project

* **Data Cleaning & Wrangling:**

  * Removed duplicate records.
  * Handled missing values in columns such as director, cast, country, and rating.
  * Standardized categorical data (e.g., content type, country names).

* **Visualization & Insights:**

  * 15 meaningful charts covering univariate, bivariate, and multivariate analyses.
  * Included rationale, key insights, and business impact for each visualization.
  * Explored catalog growth over time, regional content distribution, and rating patterns.

* **Deployment Ready:**

  * Exception handling in code blocks.
  * Sequentially executable notebook.
  * Clear, well-organized markdown explanations.

* **Business Impact Focus:**

  * Insights to support decisions on regional content expansion, genre diversification, and release year trends.
  * Identified catalog gaps and opportunities for future content acquisition.

## Project Structure

```
├── EDA-on-Netflix-Movies-TV-Shows/
│   ├── EDA_Notebook.ipynb      # Complete EDA notebook with charts and insights
│   ├── netflix_titles.csv      # Dataset used
│   ├── README.md               # This file
└── ...
```

## Key Insights

* Netflix’s catalog has seen significant growth since 2010, with peaks in content addition.
* Movies dominate the catalog over TV shows, though TV content is steadily increasing.
* The USA, India, and the UK contribute the largest portions of content.
* Rating patterns reveal a focus on TV-MA and TV-14 content, catering to mature audiences.

## Future Scope

* Extend EDA with up-to-date datasets to analyze recent trends.
* Use NLP techniques on descriptions and titles to identify emerging themes.
* Build recommendation models based on content metadata.
* Create interactive dashboards for dynamic exploration of the catalog.

## How to Run

1. Clone this repository:

   ```
   git clone https://github.com/BrijKumbhani/EDA-on-Netflix-Movies-TV-Shows.git
   ```
2. Open the notebook `EDA_Notebook.ipynb` in Jupyter or Google Colab.
3. Ensure the dataset (`netflix_titles.csv`) is available in the correct path or update the file path accordingly.
4. Run all cells in sequence to reproduce the analysis.

## Author

**Brij Kumbhani**
[GitHub Profile](https://github.com/BrijKumbhani)

## License

This project is open source and available under the MIT License (if applicable — add LICENSE file if you want to include this).

## Acknowledgments

* Dataset: [Kaggle Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
* Visualization libraries: Seaborn, Matplotlib, Plotly
* Tools: Python, Jupyter, Google Colab
* Thanks to the open source community for the tools and libraries used in this project.
