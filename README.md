# Enhanced APACHE Score Prediction Model
## Project Overview
The Enhanced APACHE Score Prediction Model aims to improve the accuracy of ICU patient outcome predictions by refining the existing Acute Physiology and Chronic Health Evaluation (APACHE) II scoring system. Utilizing advanced data analytics and machine learning techniques, this project seeks to offer healthcare providers a more reliable tool for assessing patient survival probabilities, thereby facilitating better clinical decision-making and resource allocation in critical care environments.

## Getting Started
### Prerequisites
Python 3.6 or higher<br>
Jupyter Notebook<br>
Required Python libraries: numpy, pandas, scikit-learn, matplotlib<be>

### Installation
Clone the repository:
```
git clone https://github.com/AllenJWZhu/IML_final_project
```
Install the required Python packages:
```
pip install -r requirements.txt
```

### Usage
Open the Jupyter Notebook (cs4262_project.ipynb) to view the project's code and analysis.
Run each cell in the notebook to replicate the study's findings or apply the model to new data.

### Model Development
The project employs logistic regression to develop a binary classification model, utilizing a curated dataset from the GOSSIS initiative. The model is trained to predict ICU patient survival outcomes based on a selection of 30 critical features identified through rigorous data analysis.

### Data Preprocessing
Data cleaning and preprocessing steps are detailed within the Jupyter Notebook, focusing on handling missing values and feature selection.

### Model Training and Evaluation
The methodology section outlines the model training process, including data splitting, model fitting, and evaluation metrics (accuracy, precision, recall).

### Results
The enhanced APACHE score prediction model demonstrated a significant improvement in predicting patient outcomes, with a notable increase in accuracy compared to the traditional APACHE II scores.

## Contributing
We welcome contributions to this project. Please read CONTRIBUTING.md for details on our code of conduct and the process for submitting pull requests.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
Aaron Guo and Jiawei Zhu for their significant contributions to the project.
MIT's GOSSIS initiative for providing the dataset.

## Contact
Project Link: [GitHub Repository URL](https://github.com/AllenJWZhu/IML_final_project)
