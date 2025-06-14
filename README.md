# 🧠 Decision Tree Classification – Social Network Ads

This project demonstrates a **decision tree classifier** built in R to predict whether a user will purchase a product based on their age and estimated salary.

## 📂 Dataset
- **Source:** [`Social_Network_Ads.csv`](https://github.com/SemaGasimzade/-Decision-Tree-Classification-/blob/main/Social_Network_Ads.csv)
- **Features used:** `Age`, `EstimatedSalary`
- **Target variable:** `Purchased` (0 or 1)

## ⚙️ Steps Performed

1. **Data Preprocessing:**
   - Selected relevant columns.
   - Encoded target variable as factor.

2. **Train-Test Split:**
   - 75% training, 25% test using `caTools`.

3. **Model Training:**
   - Built a **Decision Tree Classifier** using the `rpart` package.

4. **Visualization:**
   - Visualized the decision tree using `fancyRpartPlot` from the `rattle` library.

## 📊 Visualization
[![Decision Tree](Rplot_tree.png)](https://github.com/SemaGasimzade/-Decision-Tree-Classification-/blob/main/Rplott.png)

## 📌 Key Insights

- The decision tree splits the feature space based on Age and Estimated Salary to determine purchasing behavior.
- The resulting tree structure helps understand the decision rules behind the classification.

To run the code, open the [`classification_model.R`](https://github.com/SemaGasimzade/-Decision-Tree-Classification-/blob/main/decision_tree_classification.R) script in RStudio and run each section step by step.
