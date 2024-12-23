# Demand for Shared Bikes 🏇
> Build a multiple linear regression model for the prediction of demand for shared bikes


## Table of Contents
- [Demand for Shared Bikes 🏇](#demand-for-shared-bikes-)
  - [Table of Contents](#table-of-contents)
  - [Repo structure](#repo-structure)
  - [Problem Statement](#problem-statement)
  - [Business Goal:](#business-goal)
  - [Technologies Used](#technologies-used)
      - [Linux/macOS](#linuxmacos)
      - [Windows](#windows)
  - [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## Repo structure
```plaintext
.
├── data
│   ├── Readme.md               # Data dictionary explaining variable definitions
│   └── raw
│       └── day.csv                # Primary dataset containing bike details (2018-2019)
├── docs
│   ├── Regression+Subjective+Questions.pdf  # Presentation explaining analysis and results
│   └── Regression+Subjective+Questions.pptx # PowerPoint version of the presentation
├── notebook
│   └── bike.ipynb                  # Jupyter Notebook containing all EDA code and visualizations
├── .gitignore                     # Files and folders to exclude from Git version control
├── .pre-commit-config.yaml        # Configuration file for pre-commit hooks
├── pyproject.toml                 # Configuration for project dependencies and tools
├── requirements.txt               # Python dependencies required for the project
└── README.md                      # Project description and repository details
```

<!-- ## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

You don't have to answer all the questions - just the ones relevant to your project. -->

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


## Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

<!-- ## Conclusions
- Conclusion 1 from the analysis
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis -->

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
**Data Analysis + Model building and evaluation:**

* **pandas (2.2.3):** Essential library for data manipulation, analysis, and cleaning.
* **matplotlib (3.9.2):** Versatile library for creating various visualizations.
* **seaborn (0.13.2):** High-level data visualization library built on matplotlib, offering attractive and informative plots.
* **scikit-learn (1.5.2):** Comprehensive library for machine learning tasks like classification, regression, and clustering.
* **statsmodels (0.14.4):** Statistical modeling library for time series analysis, regression, and statistical tests.
* **spacy (3.8.2):** SpaCy modeling library is for natural language processing tasks.

**Development Tools:**

* **black (24.10.0):** Enforces a consistent code formatting style.
* **flake8 (7.1.1):** Static code analysis tool for style violations and potential bugs.
* **isort (5.13.2):** Automatically sorts imports for better readability.
* **pre-commit (4.0.1):** Framework for managing pre-commit hooks to ensure code quality checks before commits.

**Installation:**

* **Recommended:** Create a virtual environment to isolate project dependencies 🐍:

  #### Linux/macOS
    ```bash
    python3 -m venv env
    source env/bin/activate
    pip3 install -r requirements.txt
    ```
  #### Windows
    ```bash
    python -m venv env
    env\Scripts\activate.bat
    pip install -r requirements.txt
    ```

<!-- ## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com). -->


## Contact
Created by [@amaan2398](https://github.com/amaan2398) 💻 - Let's connect!

You can also find me on LinkedIn: [amaan2398](https://www.linkedin.com/in/amaan2398/) 💼
