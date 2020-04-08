# SpamVsHam-classifier-using-Logistic-Regresion
Spam vs Ham Classifier that classifies whether a message is spam or ham using Logistic Regression, Which is implemented from scratch.

### SETTING UP THE ENVIRONMENT
For running the classifier, I shall recommend installing anaconda for python 3.7. This ensures all the basic dependencies. Moreover, you may create a virtual environment using the environment.yml file uploaded in the repository. The command to create the virtual environment with the environment.yml file is:
<pre><code>conda env create -f environment.yml</code></pre>
The first line of .yml file sets the name of the environment 
<pre><code>conda activate <environment_name> </code></pre>

### STEPS TO CREATE THE FILTER
#### 1. DATA PREPROCESSING:
In this step, we imported the important python libraries for linear algebra, data preprocessing and Natural Language Processing.
##### The Libraries imported are:
1. numpy
2. pandas
3. string
4. scikitlearn
5. Natural Language toolkit (NLTK)
6. pyplot
7. scipy

The dataset was imported and was processed as per following sequence:
1. Cleaning the data by removing punctuations and stopwords
2. Stemming : reducing the words to roots
3. TfIdf vectorization : creating a proper matrix of words appearing, with proper weightage given to each word

#### 2. LOGISTIC REGRESSION CLASSIFIER
The steps to code the logistic regression classifier from scratch are:
1. Define the logistic funtion, more popularly known as sigmoid function
2. Define the logistic cost function 
3. Define the gradient descent algorithm to get optimum parameters
4. Initialise the matrix of parameters, the learning rate, the number of iterations
5. split the data into training set and test set, and make predictions on the test set.

In this classifier, I have used learning rate = 0.01 and 10,000 iterations. This resulted in an accuracy of 86.54%. Feel free to play around with these two hyper parameters to get better results. 
