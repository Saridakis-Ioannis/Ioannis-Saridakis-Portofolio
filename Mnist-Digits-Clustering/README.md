<h1>MNIST Digits Clustering Analysis</h1>

<h2>Dataset</h2>
<p>This project utilizes the MNIST dataset, specifically focusing on the digits 7, 8, and 9. The MNIST dataset is widely used for training and testing in the field of machine learning for handwritten digit recognition.</p>

<h2>Project Workflow</h2>
<p>The workflow of this project includes several steps:
<ul>
  <li>Data Filtering: Keeping only the digits 7, 8, and 9 from the MNIST dataset.</li>
  <li>Data Transformation: Applying Principal Component Analysis (PCA) to reduce the dimensionality of the dataset to the first two principal components.</li>
  <li>Data Visualization: Plotting the two principal components for each class to visualize the separation between the digits.</li>
  <li>K-Means Clustering: Training K-Means clusterers with cluster counts ranging from 2 to 10 and calculating the silhouette score for each to determine the optimal number of clusters.</li>
  <li>Analysis of Results: Identifying the best number of clusters and comparing it with the actual number of classes (digits).</li>
  <li>Cluster Centers Visualization: Plotting a representative image for each cluster using the centers derived from the best K-Means model.</li>
</ul>
</p>

<h2>Technologies Used</h2>
<p>The project is implemented using Python and several scientific computing libraries:
<ul>
  <li>Python</li>
  <li>NumPy for numerical operations</li>
  <li>Pandas for data manipulation</li>
  <li>Matplotlib for plotting graphs</li>
  <li>Scikit-Learn for PCA and K-Means clustering</li>
</ul>
</p>

<h2>Results</h2>
<p>The project successfully identifies the optimal number of clusters based on silhouette scores. The results suggest that the best cluster count closely matches the number of targeted digits in the dataset.</p>

<h2>Conclusion</h2>
<p>The PCA and K-Means clustering techniques were effective in identifying and visualizing the underlying patterns in the data. The number of optimal clusters identified matches the number of distinct digits analyzed, demonstrating the effectiveness of the clustering approach in this context.</p>

<h1>How to Run</h1>
<p>To run this project:
<ul>
    <li>Clone the repository to your local machine.</li>
    <li>Ensure that you have Python installed, along with the required libraries (NumPy, pandas, Scikit-learn, Matplotlib).</li>
    <li>Open the Jupyter notebook in this repository and execute the cells sequentially to see the analysis and results.</li>
</ul>
</p>
