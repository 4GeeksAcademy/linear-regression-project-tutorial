<!-- hide -->
# Linear regression - Step by step guide
<!-- endhide -->

- Understand a new dataset.
- Process it by applying exploratory data analysis (EDA).
- Model the data using linear regression.
- Analyze the results and optimize the model if possible.

<onlyfor saas="false" withBanner="false">
  
## 🌱 How to start this project

Follow the instructions below:

1. Create a new repository based on [machine learning project](https://github.com/4GeeksAcademy/machine-learning-python-template) by [clicking here](https://github.com/4GeeksAcademy/machine-learning-python-template/generate).
2. Open the newly created repository in Codespace using the [Codespace button extension](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).
3. Once the Codespace VSCode has finished opening, start your project by following the instructions below.

</onlyfor>

## 🚛 How to deliver this project

Once you have finished solving the exercises, be sure to commit your changes, push them to your repository, and go to 4Geeks.com to upload the repository link.

## 📝 Instructions

### Predicting the cost of health insurance for a person

The important insurance company 4Geeks Insurance S.L. wants to calculate, based on the physiological data of its customers what will be the premium (cost) to be borne by each of them. To do this, it has assembled a whole team of doctors, and based on data from other companies and a particular study, it has managed to gather a set of data to train a predictive model.

#### Step 1: Loading the dataset

The dataset can be found in this project folder under the name `medical_insurance_cost.csv`. You can load it into the code directly from the link:

```text
https://raw.githubusercontent.com/4GeeksAcademy/linear-regression-project-tutorial/main/medical_insurance_cost.csv
```

Or download it and add it by hand in your repository. In this dataset, you will find the following variables:

1. `age`. Age of primary beneficiary (numeric)
2. `sex`. Gender of the primary beneficiary (categorical)
3. `bmi`. Body mass index (numeric)
4. `children`. Number of children/dependents covered by health insurance (numeric)
5. `smoker`. Is the person a smoker? (categorical)
6. `region`. Beneficiary's residential area in the U.S.: northeast, southeast, southwest, northwest (categorical)
7. `charges`. Health insurance premium (numerical)

#### Step 2: Perform a full EDA

This second step is vital to ensure that we keep the variables that are strictly necessary and eliminate those that are not relevant or do not provide information. Use the example Notebook we worked on and adapt it to this use case.

Be sure to conveniently divide the data set into `train` and `test` as we have seen in previous lessons.

#### Step 3: Build a linear regression model

You do not need to optimize the hyperparameters. Start by using a default definition, and improve it in the next step.

#### Step 4: Optimize the previous model

After training the model, if the results are not satisfactory, optimize it if possible.

> Note: We also incorporated the solution samples on `./solution.ipynb` that we strongly suggest you only use if you are stuck for more than 30 min or if you have already finished and want to compare it with your approach.
