# Mildew Dectection Algorithm

## Planning Phase

### Business Requirements

The cherry plantation crop from Farmy & Foods is facing a challenge where their cherry plantations have been presenting powdery mildew. Currently, the process is to manually verify if a given cherry tree contains powdery mildew. An employee spends around 30 minutes in each tree, taking a few samples of tree leaves and verifying visually if the leaf tree is healthy or has powdery mildew. If it has powdery mildew, the employee applies a specific compound to kill the fungus. The time spent applying this compound is 1 minute. The company has thousands of cherry trees located in multiple farms across the country. As a result, this manual process is not scalable due to time spent in the manual process inspection.

To save time in this process, the IT team suggested an ML system that is capable of detecting instantly, using a leaf tree image, if it is healthy or has powdery mildew. A similar manual process is in place for other crops for detecting pests, and if this initiative is successful, there is a realistic chance to replicate this project to all other crops. The dataset is a collection of cherry leaf images provided by Farmy & Foods, taken from their crops.

### **Project Goal:**

- 1 - The client is interested in conducting a study to visually differentiate a cherry leaf that is healthy and that contains powdery mildew.
- 2 - The client is interested to predict if a cherry leaf is healthy or contains powdery mildew.

## Dataset Content

- The dataset is sourced from [Kaggle](https://www.kaggle.com/codeinstitute/cherry-leaves). We created then a fictitious user story where predictive analytics can be applied in a real project in the workplace.
- The dataset contains +4 thousand images taken from client's crop fields. The images show cherry leaves that are healthy and cherry leaves that contain powdery mildew, which is a fungal disease that affects a wide range of plants. The cherry plantation crop is one of their finest products in the portfolio and the company is concerned about supplying the market with a product of compromised quality.

## Hypothesis and how to validate?

- The tree leaves that have pwdery mildew contains white streaks on them.
  - conventional data analysis will be used to conduct a study to visually differentiate a cherry leaf that is healthy from one that contains powdery mildew.

## Rationale to map the business requirements to the Data Visualizations and ML tasks

- **Business Requirement 1**: Data Visualization
  In order to visually differentiate healthy and mildew-infested cherry leaves:

  - As a client I want to display the "mean" and "standard deviation" images for cherry leaves that are healthy and cherry leaves that contain powdery mildew.
  - As a client I want to display the differences between an average healthy cherry leaf and a cherry leaf that has powdery mildew.
  - As a client I want to display an image montage for healthy cherry leaf and mildew-infested leaf.

- **Business Requirement 2**: Classification
  - As a client I want to predict if a given cherry leaf is healthy or contains powdery mildew so that I do not supply the market with a product of compromised quality.
  - As a client I want to build a binary classifier and generate reports.

## ML Business Case

- As a client I want a ML model to predict if the cherry leaf tree is healthy or has powdery mildew.
- The ideal outcome is provide Farmy & Foods with a faster and reliable mildew detection mechanism that is readily scalable across the multiple farms in the country
- The model success metric are:
  - A study showing how to visually differentiate a cherry leaf that is healthy from one that contains powdery mildew.
  - The capability to predict if a cherry leaf is healthy or contains powdery mildew.
  - The model accuracy on test data is 97%
