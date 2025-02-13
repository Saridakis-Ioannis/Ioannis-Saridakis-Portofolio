<h1>Analysis of LSTM Window Sizes for Time Series Prediction</h1>

<h1>Dataset</h1>
<p>The dataset used for this project consists of a synthetic time series generated to model certain behavior over time. The dataset is split into training, validation, and testing sets to evaluate the performance of LSTM models with different window sizes.</p>

<h1>Project Workflow</h1>
<p>The project explores the impact of window sizes on the performance of LSTM models for time series prediction. Key steps include:
    <ol>
        <li>Generating the time series data and splitting it into training, validation, and test sets.</li>
        <li>Converting the time series into a supervised learning format suitable for LSTM training.</li>
        <li>Building and training LSTM models with different window sizes.</li>
        <li>Evaluating model performance across various prediction horizons.</li>
    </ol>
</p>

<h1>Technologies Used</h1>
<p>The project utilizes the following technologies and libraries:
    <ul>
        <li>Python</li>
        <li>Jupyter Notebook</li>
        <li>TensorFlow and Keras for building LSTM models</li>
        <li>Matplotlib for visualizations</li>
    </ul>
</p>

<h1>Results</h1>
<p>The results indicate that the LSTM model with a window size of 10 performs better in the short-term prediction horizon, while the model with a window size of 20 shows improved stability and accuracy over longer prediction periods. Visual comparisons of model predictions against the ground truth are provided in the notebook.</p>

<h1>Conclusion</h1>
<p>The study concludes that the choice of window size in LSTM models significantly affects their prediction accuracy and stability. A smaller window size may benefit short-term predictions, whereas larger windows provide better long-term accuracy. Future work could explore hybrid approaches or more complex architectures to optimize performance across varying horizons.</p>

<h1>How to Run</h1>
<p>To run this project:
<ul>
    <li>Clone the repository to your local machine.</li>
    <li>Ensure that you have Python installed, along with the required libraries.</li>
    <li>Open the Jupyter notebook in this repository and execute the cells sequentially to see the analysis and results.</li>
</ul>
</p>
