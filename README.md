# Life Insurance Repository

## 1. General info

This repository contains the analysis of factors influencing Life Insurance.

It encompasses the following steps:
1.Data collection
2.Data cleaning and preparation
3.Exploratory Data Analysis

## 2. Dataset

This dataset contains insurance-related information of individuals, including demographic details, health metrics, and insurance charges. It can be used for predictive modeling, data analysis, and machine learning applications related to healthcare costs.

**Columns Description:**
- age: Age of the individual
- sex: Gender (male/female)
- bmi: Body Mass Index, a measure of body fat based on height and weight
- children: Number of dependent children
- smoker: Whether the individual is a smoker (yes/no)
- region: Residential region (southwest, southeast, northwest, northeast)
- charges: Medical insurance cost billed to the individual

## 3. Environment
It's highly recommended to use a virtual environment for your projects. 

- first clone the repo
```
  # clone repo
git clone https://github.com/lamelkekana/Obesity_Prediction.git
```
You can use Python’s built-in venv module to create a virtual environment

**Create the new evironment**

```
# create enironment
python -m venv <env_name>
# activate environment
obesity_env\Scripts\activate

```
**If pip is not installed in your environment, you can install it by running:**

```
python -m ensurepip --upgrade
```
**Install the Project Dependencies**
```
pip install -r requirements.txt

```
Aternatively ,you can use use conda to create environment,this is applicable if you have anaconda installed in your machine

**Create the new evironment** -

```
 # create the conda environment
conda create --name <env>
```

**This is how you activate the virtual environment in a terminal and install the project dependencies**

```
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project, requirements.txt is provided in the the repo
pip install -r requirements.txt ```
```
## 4.Launching the notebook

Navigate to the cloned repository
```
cd path/to/your/repo
```

Activate environment
```
# if environment not activated,activate it using venv if it was created with venv((Python virtual environment))
your_env_name\Scripts\activate

# alternatively activate environment using conda if you successfully created the environment using conda
conda activate your_env_name
```
Run
```
jupyter notebook
```

## 5. Analyst

| Lamel Kekana         | lamel466@gmail.com             |
