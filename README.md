<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Scene Recognition using Convolutional Neural Networks</title>
</head>
<body>

<h1>Scene Recognition using Convolutional Neural Networks</h1>

<p>This project uses Convolutional Neural Networks (CNNs) for scene recognition, an essential task in computer vision. The project’s goal is to classify images into specific scene categories, with applications in areas like autonomous systems, surveillance, and image indexing.</p>

<h2>Project Overview</h2>

<ul>
  <li><strong>Objective:</strong> To develop a CNN-based model for accurate scene classification.</li>
  <li><strong>Dataset:</strong> Utilizes a subset of the Places365 dataset, resized for efficient processing.</li>
  <li><strong>Model Architecture:</strong> A three-layer CNN featuring convolutional and max-pooling layers, ReLU activations, and a SoftMax output layer for multi-class classification.</li>
</ul>

<h2>Dataset</h2>
<p>The dataset for this project is a subset of the <a href="https://www.kaggle.com/datasets/benjaminkz/places365/data">Places365 dataset</a>, containing images classified into 'amusement park,' 'mountain,' 'bridge,' and 'greenhouse' categories. Each image was resized to 3x48x48 to optimize processing efficiency.</p>

<h2>Model Architecture</h2>
<ul>
  <li><strong>Convolution Layers:</strong> Three convolutional layers for feature extraction.</li>
  <li><strong>Activation Functions:</strong> ReLU for feature extraction and SoftMax for classification output.</li>
  <li><strong>Pooling:</strong> Max-pooling layers after each convolutional layer to reduce spatial dimensions.</li>
  <li><strong>Fully Connected Layer:</strong> Connects features to output layer for classification.</li>
</ul>

<h2>Training</h2>
<ul>
  <li><strong>Optimization:</strong> Stochastic Gradient Descent (SGD) with a learning rate of 0.1.</li>
  <li><strong>Loss Function:</strong> Cross-Entropy Loss for multi-class classification.</li>
  <li><strong>Data Split:</strong> 80% for training, 20% for testing.</li>
  <li><strong>Batch Size:</strong> Set to 32 for efficient training.</li>
</ul>

<h2>Evaluation</h2>
<p>The model is evaluated using:</p>
<ul>
  <li><strong>Accuracy:</strong> The percentage of correct classifications.</li>
  <li><strong>Confusion Matrix:</strong> Shows true positives, true negatives, false positives, and false negatives.</li>
  <li><strong>Precision, Recall, F1-score:</strong> Performance metrics for each class.</li>
</ul>

<h2>Results</h2>
<p>The CNN model demonstrates effective scene classification, with detailed performance visualizations across training epochs.</p>

<h2>Acknowledgments</h2>
<p>Special thanks to Professor Rehan Ahmed for his guidance and support in this project.</p>

<h2>License</h2>
<p>This project is licensed under the MIT License - see the LICENSE file for details.</p>

</body>
</html>
