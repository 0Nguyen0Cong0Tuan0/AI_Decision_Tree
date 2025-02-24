# AI_Decision_Tree

## Overview
AI_Decision_Tree is a machine learning project that implements a **Decision Tree Classifier** using **Scikit-learn**. The project includes data preprocessing, model training, evaluation, and visualization of decision trees. It is designed to demonstrate classification techniques on structured datasets.

## Features
- Load and preprocess datasets using **pandas**
- Train a **Decision Tree Classifier** with **Scikit-learn**
- Evaluate the model using **confusion matrix, accuracy score, and classification reports**
- Visualize the decision tree using **graphviz**
- Use **seaborn and matplotlib** for data analysis and visualization

## Installation
To run this project, you need to have Python installed along with the required dependencies. You can install them using:

```bash
pip install pandas scikit-learn matplotlib graphviz seaborn
```

## Usage
1. Load the dataset (default: `nursery.data.csv`)
2. Preprocess the data by shuffling and splitting it into training and testing sets
3. Train the **Decision Tree Classifier**
4. Evaluate the model performance
5. Visualize the decision tree

To run the Jupyter Notebook:
```bash
jupyter notebook ai.ipynb
```

## Dependencies
- Python 3.x
- pandas
- scikit-learn
- matplotlib
- seaborn
- graphviz
- os (built-in)

## Visualizing the Decision Tree
This project uses **graphviz** to generate a graphical representation of the decision tree. Make sure you have Graphviz installed:

```bash
sudo apt install graphviz  # Linux
brew install graphviz      # macOS
winget install Graphviz    # Windows
```

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request with improvements.

## License
This project is licensed under the MIT License.

