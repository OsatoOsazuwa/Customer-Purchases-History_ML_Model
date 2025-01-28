# Customer Purchases History - Association Rule ML Model

This project analyzes customer purchase data to uncover hidden patterns and associations using the Apriori algorithm. The primary objective is to identify frequent itemsets and generate actionable association rules to improve business strategies such as cross-selling and marketing.

## Table of Contents
- [Project Overview](#project-overview)
  - [Key Features](#key-features)
  - [Technologies Used](#technologies-used)
- [Files in the Repository](#files-in-the-repository)
- [Dataset Description](#dataset-description)
  - [Example Structure](#example-structure)
- [How to Run the Project](#how-to-run-the-project)
  - [Prerequisites](#prerequisites)
  - [Steps](#steps)
- [Insights and Recommendations](#insights-and-recommendations)
- [Contribution](#contribution)
- [Contact](#contact)

## Project Overview

### Key Features
- Implements the Apriori algorithm to discover frequent itemsets.
- Evaluates association rules based on metrics like **support**, **confidence**, and **lift**.
- Provides actionable insights to improve product placements, promotions, and targeted marketing strategies.

### Technologies Used
- **Python**: Core programming language.
- **Pandas**: For data preprocessing and manipulation.
- **MLxtend**: For Apriori and association rule generation.
- **Jupyter Notebook**: For an interactive analysis environment.

## Files in the Repository

- **`Customer_Purchases_History_ML_Model.ipynb`**: Jupyter Notebook containing the implementation of the Apriori algorithm, data preprocessing steps, and visualization of results.
- **`README.md`**: Project documentation.
- **`Market_Basket_Optimisation.csv`**: Dataset containing customer purchase transactions.

## Dataset Description

The dataset contains transactional data representing customer purchases. Each transaction consists of items bought together.

### Example Structure:
| Item1      | Item2      | Item3   | ... |
|------------|------------|---------|-----|
| Milk       | Water      | Grapes  |     |
| Bread      | Diapers    | Beer    |     |

## How to Run the Project

### Prerequisites
Make sure you have the following installed:
- Python 3.8+
- Required libraries: `pandas`, `mlxtend`, `numpy`, `matplotlib`, `seaborn`

### Steps
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project-directory>
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Customer_Purchases_History_ML_Model.ipynb
   ```
5. Execute the notebook cells to run the analysis.

## Insights and Recommendations
- **Lift and Confidence Analysis**: Extracted rules highlight meaningful associations, such as `ground beef` being frequently bought with `mineral water`.
- **Actionable Strategies**:
  - Cross-sell items based on association rules.
  - Place frequently associated items together in stores or online.
  - Offer bundle discounts to increase sales.

## Contribution
Contributions are welcome! If you'd like to contribute:
- Fork the repository.
- Create a new branch for your feature/bug fix.
- Submit a pull request describing your changes.


## Contact
For questions or feedback, reach out via email or GitHub issues.

---

