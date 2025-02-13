<h1>Exploring Auto-encoders with MNIST Dataset</h1>

<h2>Dataset</h2>
<p>This project utilizes the MNIST dataset, which consists of 70,000 images of handwritten digits (0-9). The dataset is split into a training set (5/7), a validation set (1/7), and a test set (1/7).</p>

<h2>Project Workflow</h2>
<ul>
    <li>Data preprocessing to split the dataset into training, validation, and test sets.</li>
    <li>Building a vanilla auto-encoder with three fully-connected layers: an input layer, a latent layer, and an output layer.</li>
    <li>Training the model on the MNIST training data for up to 100 epochs with early stopping based on the validation set (patience of 5 epochs).</li>
    <li>Evaluating the reconstruction error on the test set using different sizes of the latent space: 10, 100, and 250 nodes.</li>
    <li>Analyzing the impact of the latent space size on model performance.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
    <li>Python for programming</li>
    <li>TensorFlow and Keras for building and training the neural network</li>
    <li>NumPy for data handling</li>
</ul>

<h2>Results</h2>
<p>The results indicate that as the number of nodes in the latent space increases, the reconstruction error decreases. However, the improvements diminish as the size of the latent space becomes too large, suggesting a trade-off between complexity and performance.</p>

<h2>Conclusion</h2>
<p>The experiment demonstrates the effectiveness of auto-encoders in learning compressed representations of data, with the potential for diminishing returns at higher complexities. It also highlights the importance of tuning hyperparameters like the size of the latent space to balance performance and computational efficiency.</p>

<h2>How to Run</h2>
<ol>
    <li>Clone the repository to your local machine.</li>
    <li>Ensure Python and the necessary libraries (TensorFlow, Keras, NumPy) are installed.</li>
    <li>Execute the notebook or Python script to train the model and visualize the results.</li>
</ol>
