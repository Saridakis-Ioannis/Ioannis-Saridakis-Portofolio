<h1>Binary Classification of MNIST Dataset - Distinguishing Digit 4</h1>

<h1>Dataset</h1>
<p>The project uses the MNIST dataset, which consists of handwritten digits from 0 to 9. The dataset is divided into a training set of 60,000 images and a test set of 10,000 images.</p>

<h1>Project Workflow</h1>
<ul>
  <li>Data Loading: The MNIST dataset is fetched using sklearn's fetch_openml method.</li>
  <li>Data Preprocessing: Splitting the dataset into training and test sets.</li>
  <li>Model Training: Training a binary classifier to identify whether a given image is the digit '4' or not.</li>
  <li>Evaluation: Using accuracy, confusion matrix, and ROC curve to assess model performance.</li>
</ul>

<h1>Technologies Used</h1>
<ul>
  <li>Python</li>
  <li>NumPy</li>
  <li>Matplotlib for visualization</li>
  <li>Scikit-learn for model training and evaluation</li>
</ul>

<h1>Results</h1>
<p>The classifier performs well with an accuracy significantly higher than the baseline model, which predicts 'not-4' for all inputs. The detailed performance is illustrated by a confusion matrix and an ROC curve indicating good true positive rates.</p>

<h1>Conclusion</h1>
<p>The project demonstrates the effectiveness of binary classifiers on image recognition tasks within highly imbalanced datasets. It highlights the importance of using appropriate metrics for model evaluation to reflect true performance.</p>

<h1>How to Run</h1>
<ol>
  <li>Ensure Python and necessary libraries (NumPy, Matplotlib, Scikit-learn) are installed.</li>
  <li>Clone the repository and navigate to the project directory.</li>
  <li>Run the Jupyter notebook to observe the workflow and results.</li>
</ol>
