<h1>Random Forest Regressor for Housing Prices Prediction</h1>

<h2>Dataset</h2>
<p>The project utilizes the California Housing Prices dataset from the StatLib repository. This dataset includes metrics such as population, median income, median housing price, and more for each block group in California. Block groups are the smallest geographical unit for which the U.S. Census Bureau publishes sample data.</p>

<h2>Project Workflow</h2>
<ul>
    <li>Data Loading and Cleaning: Handling missing values, encoding categorical variables, and feature scaling.</li>
    <li>Feature Engineering: Adding new features like income categories.</li>
    <li>Data Splitting: Using stratified shuffle split to ensure the training and test sets are representative of the overall dataset.</li>
    <li>Model Building: Constructing a pipeline for preprocessing and regression using Random Forest.</li>
    <li>Model Selection: Utilizing Grid Search to find the best hyperparameters.</li>
    <li>Analysis of Feature Importance to determine the most impactful predictors.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
    <li>Python</li>
    <li>NumPy and pandas for data manipulation</li>
    <li>Scikit-learn for machine learning</li>
</ul>

<h2>Results</h2>
<p>The optimized Random Forest model demonstrated significant predictive performance, with key features identified as median income, INLAND (a category of ocean proximity), and longitude being the most predictive of housing prices.</p>

<h2>Conclusion</h2>
<p>The project successfully develops a predictive model for California housing prices using a Random Forest regressor, with comprehensive data preparation, feature engineering, and model optimization steps to enhance model accuracy.</p>

<h1>How to Run</h1>
<p>To run this project:
<ul>
    <li>Clone the repository to your local machine.</li>
    <li>Ensure that you have Python installed, along with the required libraries (NumPy, pandas, Scikit-learn).</li>
    <li>Open the Jupyter notebook in this repository and execute the cells sequentially to see the analysis and results.</li>
</ul>
</p>
