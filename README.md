# Single-Layer-Perceptron
<h1>GUI</h1>
<h5>User Input:</h5>
<p>Select two features</p>
<p>Select two classes (C1 & C2 or C1 & C3 or C2 & C3)</p>
<p>Enter learning rate (eta)</p>
<p>Enter number of epochs (m)</p>
<p>Add bias or not (Checkbox)</p>
<br>
<h1>Initialization</h1>
<p>Number of features = 2</p>
<p>Number of classes = 2.</p>
<p>Weights + Bias = small random numbers</p>
<br>
<h1>Classification</h1>
<p>Sample (single sample to be classified)</p>
<br>
<h1>Description</h1>
<h5>Visualize Penguins dataset</h5>
<p>Penguins' dataset contains 150 samples (50 samples/class). Each sample consists of 5 features.</p>
<p>The first part is analyzing the data and making a simple report to know the linear/non-linear separable features.</p>
<p>HINT: Drawing all possible combinations of features like (X1, X2), (X1, X3), (X1, X4), (X2, X3), (X2, X4), etc as shown in the following figure and determine which features are discriminative between which classes</p>
<br>
<h5>Implement the Perceptron learning algorithm</h5>
<p>Single layer neural networks which can be able to classify a stream of input data to one of a set of predefined classes.</p>
<p>Use the penguins data in both your training and testing processes. (Each class has 50 samples: train NN with 30 non-repeated samples randomly selected, and test it with the remaining 20 samples)</p>
<br>
<h5>After training</h5>
<p>Draw a line that can discriminate between the two learned classes. You should also scatter the points of both classes to visualize the behavior of the line.</p>
<p>Test the classifier with the remaining 20 samples of each selected classes and find confusion matrix and compute overall accuracy.</p>
<br>
<h1>Notes</h1>
<p>In the report you should have screenshots/plots of the visualizations and a written analysis of what you understood from each of these visualizations and how the features discriminate or not between classes. You should have a plot and analysis for each combination (10 combinations) </p>
<p>You should not drop any row from the dataset.</p>
<p>Using scikit-learn metrics library or any similar built-in function for the confusion matrix is not allowed.</p>
