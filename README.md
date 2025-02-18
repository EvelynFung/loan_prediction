
<!-- Project Overview -->
## Project Overview

This project implements a Loan Prediction Model using Generative AI, instead of traditional machine learning models like Random Forest, Decision Tree, and Linear Regression. The model formulates prompts based on applicant data and uses a large language model to predict loan default probability.


### Prerequisites

Ensure you have the following Python packages installed:
  ```sh
  pip install numpy pandas torch transformers langchain chromadb
  ```
### Setup Steps
_Below is an example of how you can set up the model._

1. Load Dataset (clean_loan_data.csv)
2. Install python packages
   ```sh
   install numpy pandas torch transformers langchain chromadb
   ```
3. Run the Jupyter notebook (loan_prediction_genai.ipynb) in Google Colab

### Modifications to Existing Models
The previous version used Machine Learning algorithms (Random Forest, Decision Tree, and Linear Regression). This version replaces those with Generative AI to predict loan defaults based on textual prompts.
