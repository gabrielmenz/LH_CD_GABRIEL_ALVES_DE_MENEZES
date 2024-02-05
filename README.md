# LH_CD_GABRIEL_ALVES_DE_MENEZES
This is a repository specifically built to share my report challenge for Indicium's Data Science challenge.

THis README file contains instructions on how the user should install and run this project. Below you can find the step-by-step guide.

Project Title

Lighthouse DS 2024 challenge - building an EDA and price forecasting for rent units in NYC.

Description
Provide a more detailed introduction to the project including the problem it solves, its objectives, and any unique methodology it employs. Mention the main technologies used.

Prerequisites
Before you begin, ensure you have met the following requirements:

Python (last version preferably) installed;
pip for installing Python packages.

Installation
To install the required Python packages, follow these steps:

bash
Copy code
git clone https://github.com/yourusername/yourprojectname.git
cd  XXX
pip install -r requirements.txt
Replace yourusername and XXX with your gitHub username and the name of your project repository respectively.

Usage
To run this project, you can follow these steps:

Jupyter Notebooks:

Navigate to the project directory and start Jupyter Notebook or JupyterLab:

bash
Copy code
jupyter notebook
or

bash
Copy code
jupyter lab
Open the notebook files (.ipynb) provided in the repository and run the cells sequentially.

Running ML Models:

bash
Copy code
python run_model.py

Loading and Using Pickled Models:

Ensure you have the .pkl files in the specified directory.

Use the following Python code to load and use a model:

python
Copy code
import pickle

Load a model:
with open('path/to/your/model.pkl', 'rb') as file:
    model = pickle.load(file)

Use the model:
results = model.predict(data)


Contributing
For those who wish to contribute to this project:

Fork the repository
Create a new branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a pull request
License
MIT License

Contact
Gabriel Alves de Menezes - gabrielmenz@icloud.com
Project Link: https://github.com/gabrielmenz/LH_CD_GABRIEL_ALVES_DE_MENEZES

