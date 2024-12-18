Cyberbullying Detection using Sentiment Analysis and Machine Learning
This project uses machine learning and sentiment analysis techniques to detect cyberbullying in social media tweets. The goal is to classify tweets as either "cyberbullying" or "non-cyberbullying" based on their sentiment scores and features extracted from the text.

***************
Features
***************
Data Preprocessing: Removes duplicates and irrelevant data.
Sentiment Analysis: Utilizes VaderSentiment for extracting sentiment scores.
Text Vectorization: Applies CountVectorizer and TfidfTransformer for feature extraction.
Classification: Implements a Naive Bayes classifier to detect cyberbullying.
Visualization: Includes visualizations such as pie charts and histograms for data analysis.

****************************
Technologies Used
****************************
Python: Core language for the project.
Libraries:
Pandas for data handling.
NumPy for numerical operations.
Matplotlib & Seaborn for visualizations.
scikit-learn for machine learning models and vectorization.
VaderSentiment for sentiment analysis.

********************
Prerequisites
********************
Make sure you have the following installed:

Python 3.x
Visual Studio Code (VS Code)
Python extensions for VS Code:
Python extension (search for Python in the extensions marketplace in VS Code)
Jupyter extension (for running notebooks if required)

********************************************
Setup Instructions
********************************************
Clone the repository:
git clone https://github.com/Harini410/Cyberbullying.git

************************************
Navigate to the project directory:
************************************
cd cyberbullying-detection

*********************************************************************
Set up a Python virtual environment (optional but recommended):
*********************************************************************
python -m venv venv


**************************************
Activate the virtual environment:
**************************************
On Windows:
venv\Scripts\activate  

On macOS/Linux:
source venv/bin/activate

***************************************
Install the required dependencies:
***************************************
pip install -r requirements.txt

*******************************
Open the project in VS Code:
*******************************

code .
Run the Code: You can run the script directly in the VS Code terminal by executing the following:

python script_name.py
Or, if you are working in Jupyter notebooks, open the .ipynb file and run the cells.

********************
Project Structure
*******************

cyberbullying-detection/
│
├── Cyberbullying.csv          # Dataset containing tweets
├── script_name.py             # Main Python script for classification and analysis
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation
Visualizing Results
After running the script, you will see:

Pie Chart: Distribution of cyberbullying vs. non-cyberbullying tweets.
Histogram: Distribution of sentiment scores for each tweet (positive, negative, neutral, compound).
Classifier Model
This project uses Naive Bayes classification, implemented using the MultinomialNB model from sklearn. The dataset is split into training and testing sets, and the classifier is trained on the training data and evaluated on the test data.

********************
Contributing
********************
If you would like to contribute to this project, feel free to fork the repository, create a branch, and submit a pull request. Make sure to follow the code style and conventions used in the project.

****************************
requirements.txt 
****************************
Make sure to create a requirements.txt to list the dependencies for your project:

makefile
Copy code
pandas==1.3.3
numpy==1.21.2
matplotlib==3.4.3
seaborn==0.11.2
scikit-learn==0.24.2
vaderSentiment==3.3.2
With this setup, you can run and modify the project in Visual Studio Code and share the code with others who can also set it up with ease.