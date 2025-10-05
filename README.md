# An Analysis of Variables Contributing to a Country's GDP

[cite_start]This repository contains the code and reports for a data mining project completed for the COSC-4426EL course at Laurentian University[cite: 1, 6]. [cite_start]The project investigates the complex relationships between a country's Gross Domestic Product (GDP) and other metrics like the Human Development Index (HDI), Gender Development Index (GDI), population size, and Mean Years of Schooling (MYS)[cite: 241].

[cite_start]The analysis uses exploratory data analysis, correlation matrices, logistic regression, and XGBoost models to explore these connections[cite: 281, 283].

### Key Findings

* [cite_start]**GDP is difficult to predict:** Consistent with existing literature, the analysis found that no single variable or simple combination of variables has a strong correlation with GDP[cite: 504]. [cite_start]The XGBoost regressor model built to predict GDP yielded a very high Mean Squared Error, indicating a poor fit[cite: 486].
* [cite_start]**Population and GDP:** Population size had the strongest positive correlation with GDP among the variables studied, with a Pearson coefficient of **0.46**[cite: 290].
* **HDI is highly predictable:** In contrast to GDP, HDI was much more predictable. [cite_start]An XGBoost classification model predicted whether a country has a high HDI with **97% accuracy**[cite: 411].
* **Strongest Correlations:** The strongest observed correlations were between composite human development metrics. [cite_start]HDI and Mean Years of Schooling (MYS) had a correlation of **0.90**, and HDI and GDI had a correlation of **0.68**[cite: 290].

---
### Technologies & Libraries

* Python
* Pandas & Numpy (for data manipulation)
* Seaborn & Matplotlib (for data visualization)
* Scikit-learn & Statsmodels (for regression models)
* XGBoost
* Jupyter Notebook

---
### Repository Structure

* **/code**: Contains the Jupyter Notebook with the full data analysis.
* **/data**: Contains the raw `.csv` datasets used in the analysis.
* **/reports**: Contains the final academic submissions for the project.
* `README.md`: An overview of the project.
* `requirements.txt`: A list of Python libraries required to run the code.

---
### How to Run the Analysis

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/GDP-Data-Mining-Analysis.git](https://github.com/your-username/GDP-Data-Mining-Analysis.git)
    cd GDP-Data-Mining-Analysis
    ```

2.  **Install dependencies** (virtual environment recommended):
    ```bash
    pip install -r requirements.txt
    ```

3.  **Launch Jupyter Notebook** and open the notebook file located in the `/code` directory to view the analysis.

---
### Academic Reports

For a detailed discussion of the background, methodology, and results, please see the full academic reports:

* **[Data Mining Survey](./reports/Data_Mining_Survey.pdf)**: A literature review on the tools and concepts of computational economics.
* **[Data Mining Report](./reports/Data_Mining_Report.pdf)**: A detailed report on the project's methodology, data analysis, and final results.

---
### License

The source code contained in this repository is licensed under the **MIT License**.

The written reports (`Data_Mining_Survey.pdf` and `Data_Mining_Report.pdf`) are licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License**.
