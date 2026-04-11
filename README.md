                                                                     Data Science + Generative AI Roadmap



# Day 1 — Python Variables & Data Types
Learned:
- Variables are boxes to store information
- Data types: int, float, str, bool
- Used type() to check data types


# Day 2 — Python Lists & Tuples
Learned:
- List = flexible container [can add, remove, change]
- Tuple = fixed container (cannot change)


# Day 3 — Python Dictionaries & Sets
Learned:
- Dictionary = key-value pairs (like a phonebook)
- Set = collection of unique values


# Day 4 — Python Conditional Statements
Learned:
- if = check condition
- elif = check another condition
- else = default action


# Day 5 — Python Loops
Learned:
- for loop = repeat for each item
- while loop = repeat until condition fails


# Day 6 — Python Functions
Learned:
- Functions = reusable blocks of code
- Parameters = inputs
- return = output
- Default parameters = pre-set values


# Day 7 — Python Error Handling
Learned:
- try = code that might fail
- except = handle the error
- else = runs if no error
- finally = always runs


# Day 8 — Python File Handling
Learned:
- "r" = read
- "w" = write
- "a" = append
- "with open()" = best practice


# Day 9 — NumPy Arrays Basics
Learned:
- NumPy arrays = optimized lists for numbers
- 1D and 2D arrays
- Array properties: shape, dtype
- Special arrays: zeros, ones, range


# Day 10 — NumPy Operations (Reshape, Slicing)
Learned:
- reshape = change array shape without changing data
- slicing = extract parts of array


# Day 11 — Pandas Series & DataFrames
Learned:
- Series = one column (1D)
- DataFrame = full table (2D)
- Access rows/columns using index


# Day 12 — Data Cleaning with Pandas
Learned:
- drop_duplicates() = remove duplicate rows
- fillna() / dropna() = handle missing values
- rename() = change column names
- astype() = change data types


# Day 13 — Handling Missing Values
Learned:
- isnull() / notnull() = detect missing values
- fillna() = replace missing values
- dropna() = remove missing values


# Day 14 — Matplotlib Basic
Learned:
- Line plot = show trends
- Bar plot = compare categories
- Customization with colors, markers, titles


# Day 15 — Seaborn Plots
Learned:
- Histogram = distribution of values
- Scatter plot = relationship between two variables
- Seaborn makes plots more attractive and easier


# Day 16 — Probability Basics
Learned:
- Probability = favorable outcomes / total outcomes
- Range: 0 (impossible) to 1 (certain)


# Day 17 — Statistics Basics
Learned:
- Mean = average
- Median = middle value
- Mode = most frequent value


# Day 18 — Standard Deviation & Variance
Learned:
- Variance = average squared distance from mean
- Standard Deviation = square root of variance
- Both measure spread of data


# Day 19 — Normal Distribution
Learned:
- Normal distribution = bell curve
- Mean = Median = Mode
- Spread controlled by standard deviation


# Day 20 — Hypothesis Testing Basics
Learned:
- Null hypothesis (H0) vs Alternative hypothesis (H1)
- p-value and significance level (α)
- One-sample t-test using scipy


# Day 21 — SQL SELECT Queries
Learned:
- SELECT * → fetch all columns
- SELECT column → fetch specific columns
- AS → rename columns
- DISTINCT → remove duplicates
- LIMIT → restrict rows


# Day 22 — SQL WHERE & ORDER BY
Learned:
- WHERE → filter rows by condition
- ORDER BY ASC → sort ascending
- ORDER BY DESC → sort descending


# Day 23 — SQL JOINs
Learned:
- INNER JOIN → matching rows from both tables
- LEFT JOIN → all rows from left table
- RIGHT JOIN → all rows from right table (simulated in SQLite)
- FULL OUTER JOIN → union of left + right joins


# Day 24 — SQL GROUP BY & HAVING
Learned:
- GROUP BY → group rows by column
- Aggregate functions (AVG, SUM, COUNT)
- HAVING → filter groups after aggregation


# Day 25 — SQL Practice Project
Learned:
- Combined SELECT, WHERE, ORDER BY, JOIN, GROUP BY, HAVING
- Built queries on employees + departments tables
- Practiced filtering, sorting, grouping, and aggregation


# Day 26 — GitHub Basics
Learned:
- Installed and configured Git
- Created first GitHub repository
- Cloned repo locally


# Day 27 — Commit & Push Workflow
Learned:
- git add → stage changes
- git commit → save changes locally
- git push → upload changes to GitHub


# Day 28 — README.md Writing
Learned:
- README is the front page of a project
- Basic structure: Title, Overview, Features, Usage, Results
- Recruiter tips: keep it short, clear, and visual


# Day 29 — Organize Folders for Projects
Learned:
- Each project/day should have its own folder
- Standard format: DayXXX_Topic
- Inside each folder: notebook, dataset, README
- Group folders by phase for recruiter clarity


# Day 30 — Upload First Mini Project
Learned:
- Organized project files into folders
- Staged, committed, and pushed project to GitHub


# Day 31 — Linear Regression Theory
Learned:
- Linear regression finds the best straight line through data
- Equation: Y = β0 + β1X + ε
- Assumptions: linearity, independence, equal variance, normality
- Advantages: simple, interpretable
- Limitations: fails for non-linear data, sensitive to outliers


# Day 32 — Linear Regression Coding
Learned:
- Used sklearn to implement linear regression
- Visualized data with scatter plot
- Model learned slope + intercept
- Made predictions and plotted regression line
- Layman analogy: "Salary increases steadily with experience"


# Day 33 — Logistic Regression Theory
Learned:
- Logistic regression predicts categorical outcomes (Yes/No)
- Uses sigmoid function to output probabilities
- Assumptions: categorical dependent variable, independence, no multicollinearity
- Advantages: interpretable, probability-based
- Limitations: linear boundaries, sensitive to outliers


# Day 34 — Logistic Regression Coding
Learned:
- Implemented logistic regression using scikit-learn
- Visualized data with scatter plot
- Model outputs probabilities (0–1) using sigmoid curve
- Made predictions for pass/fail classification
- Layman analogy: "More study hours → higher chance of passing"


# Day 35 — Titanic Survival Prediction Project
Learned:
- Applied logistic regression on Titanic dataset
- Converted categorical features to numeric
- Trained model and evaluated accuracy
- Predicted survival outcomes based on passenger details
- Layman analogy: "Model guesses who had better survival chances"


# Day 36 — Decision Tree Theory
Learned:
- Decision tree = flowchart of decisions
- Structure: root, branches, leaves
- Splitting criteria: Gini, Entropy, Variance
- Advantages: simple, interpretable
- Limitations: overfitting, sensitive to data changes


# Day 37 — Decision Tree Coding
Learned:
- Implemented decision tree classifier using sklearn
- Visualized tree with branching rules
- Evaluated accuracy
- Made predictions for pass/fail outcomes
- Layman analogy: "Tree asks questions step by step until it decides"


# Day 38 — Random Forest Theory
Learned:
- Random Forest = many decision trees combined
- Uses bootstrap sampling + random feature selection
- Advantages: reduces overfitting, robust, accurate
- Limitations: slower, less interpretable
- Layman analogy: "Trust the majority opinion instead of one person"


# Day 39 — Random Forest Coding
Learned:
- Implemented Random Forest classifier using sklearn
- Trained multiple trees and combined predictions
- Evaluated accuracy
- Checked feature importance
- Layman analogy: "Ask 100 friends and trust the majority opinion"


# Day 40 — Classification Mini Project
Learned:
- Applied Logistic Regression, Decision Tree, and Random Forest on Iris dataset
- Compared model accuracies
- Visualized predictions and performance
- Layman analogy: "Three experts classify flowers, we check who is most accurate"


# Day 41 — K-Means Clustering Theory
Learned:
- K-Means groups data into clusters without labels
- Steps: choose K, assign points, update centroids
- Uses Euclidean distance for closeness
- Advantages: simple, fast, scalable
- Limitations: must choose K, sensitive to outliers
- Applications: customer segmentation, image compression


# Day 42 — K-Means Clustering Coding

Learned:
- Implemented K-Means clustering using sklearn
- Grouped customers by income and spending score
- Visualized clusters with centroids
- Layman analogy: "Customers grouped like friends with similar habits"


# Day 43 — Customer Segmentation Project
Learned:
- Applied K-Means clustering for customer segmentation
- Grouped customers by income and spending score
- Visualized clusters with centroids
- Business insight: identify budget, average, and premium shoppers


# Day 44 — DBSCAN Theory
Learned:
- DBSCAN groups dense points and marks outliers
- Parameters: eps (distance), min_samples (neighbors)
- Types of points: core, border, noise
- Advantages: arbitrary shapes, outlier detection, no need for K
- Limitations: sensitive to parameters, struggles with varying densities
- Applications: fraud detection, anomaly detection, image segmentation


# Day 45 — DBSCAN Coding
Learned:
- Implemented DBSCAN clustering using sklearn
- Grouped customers by density of points
- Visualized clusters and detected outliers
- Layman analogy: "Groups at a party, loners marked as outliers"


# Day 46 — DBSCAN Project
Learned:
- Applied DBSCAN clustering on transaction dataset
- Detected dense clusters and flagged anomalies
- Visualized spending patterns and outliers
- Business insight: identify suspicious transactions for fraud detection


# Day 47 — Ensemble Methods Theory
Learned:
- Ensemble methods combine multiple models for stronger predictions
- Types: Bagging, Boosting, Stacking
- Advantages: accuracy, less overfitting
- Limitations: expensive, harder to interpret
- Applications: fraud detection, credit scoring, medical diagnosis


# Day 48 — Bagging Coding
Learned:
- Implemented Bagging using sklearn
- Compared single Decision Tree vs Bagging ensemble
- Bagging improves accuracy by combining multiple models
- Layman analogy: "Ask many trees, take a vote"


# Day 49 — Boosting Coding
Learned:
- Implemented AdaBoost and Gradient Boosting using sklearn
- Compared boosting methods on Iris dataset
- Boosting improves accuracy by correcting errors step by step
- Layman analogy: "Each new teacher fixes mistakes of the previous one"


# Day 50 — Ensemble Project
Learned:
- Applied Bagging, AdaBoost, and Gradient Boosting on Iris dataset
- Compared ensemble methods vs single models
- Bagging = parallel voting, Boosting = sequential correction
- Ensemble methods improve accuracy and robustness


# Day 51 — Accuracy, Precision, Recall
Learned:
- Accuracy = overall correctness
- Precision = correctness of positive predictions
- Recall = ability to find all positives
- Layman analogies: exam scores, disease detection


# Day 52 — F1 Score & Confusion Matrix
Learned:
- F1 Score balances precision and recall
- Confusion Matrix shows TP, FP, TN, FN
- Layman analogies: balanced report card, scoreboard of predictions


# Day 53 — ROC Curve & AUC

Learned:
- ROC Curve shows trade-off between sensitivity and false alarms
- AUC measures overall classification ability
- Layman analogy: smoke detector sensitivity vs accuracy


# Day 54 — Cross Validation
Learned:
- Cross validation = multiple train/test splits for reliable evaluation
- Prevents overfitting and ensures fair comparison
- Layman analogy: multiple exams for fairness


# Day 55 — Model Evaluation Project
Learned:
- Combined metrics: Accuracy, Precision, Recall, F1, ROC, AUC
- Compared Decision Tree vs Logistic Regression
- Used cross validation for fair evaluation
- Layman analogies: exams, scorecards, false alarms vs detections


# Day 56 — Feature Scaling
Learned:
- Feature scaling ensures fair comparison between features
- Methods: Min-Max Scaling, Standardization
- Layman analogy: runners measuring distance in meters vs kilometers


# Day 57 — Feature Engineering
Learned:
- Feature engineering improves model performance by creating new features
- Techniques: polynomial, log transform, binning, interaction, date/time
- Layman analogy: cooking ingredients into a better dish


# Day 58 — Handling Categorical Variables

Learned:
- Categorical variables = non-numeric data like city, gender
- Encoding methods: Label Encoding, One-Hot Encoding
- Layman analogies: roll numbers for students, separate attendance sheets


# Day 59 — Feature Selection
Learned:
- Feature selection = choosing most important features
- Methods: Filter, Wrapper, Embedded
- Layman analogy: studying only important exam topics


# Day 60 — Feature Engineering Mini Project
Learned:
- Applied feature selection (Chi-Square), scaling, and Logistic Regression
- Accuracy improved with clean, meaningful features
- Layman analogies: exam topics, runners on same track


# Day 61 — Telecom Churn Dataset Intro
Learned:
- Churn = customers leaving service
- Dataset includes demographics, usage, contracts, churn label
- Explored dataset basics: head, info, missing values, churn rate
- Layman analogy: gym members cancelling membership


# Day 62 — Telecom Churn Data Cleaning
Learned:
- Handled missing values (especially TotalCharges)
- Converted Yes/No columns into numeric
- Applied one-hot encoding for categorical variables
- Verified cleaned dataset
- Layman analogy: fixing exam papers before grading


# Day 63 — Telecom Churn EDA
Learned:
- Visualized churn distribution
- Explored tenure, monthly charges, contract type vs churn
- Found patterns: short tenure and high monthly charges linked to churn
- Layman analogy: charts = report cards showing hidden patterns


# Day 64 — Telecom Churn Classification Models
Learned:
- Trained Logistic Regression, Decision Tree, Random Forest
- Converted categorical data into numeric
- Split dataset into train/test
- Compared model accuracies
- Layman analogy: three teachers grading the same exam


# Day 65 — Telecom Churn Model Evaluation
Learned:
- Evaluated Logistic Regression, Decision Tree, Random Forest
- Used precision, recall, F1 score, confusion matrix, ROC curve
- Found Random Forest usually performs best
- Layman analogy: evaluation = detailed report card, not just total marks


# Day 66 — Power BI Basics
Learned:
- Opened Power BI Desktop
- Loaded churn dataset
- Checked columns in Data View
- Made charts:
  - Churn distribution
  - MonthlyCharges
  - Tenure
  - Contract type
- Layman analogy: Power BI = notice board for charts


# Day 67 — Telecom Churn Dashboard
Learned:
- Opened Day 66 file with churn visuals
- Arranged all charts on one dashboard page:
  - Churn distribution
  - MonthlyCharges
  - Tenure
  - Contract type
- Added standard slicers:
  - Contract
  - InternetService
  - Gender
  - SeniorCitizen
- Used Format (paint roller) pane:
  - Column color for single-series charts
  - Data colors / Series for multi-series charts (after adding Legend)
- Set consistent colors:
  - Churn Yes = Red
  - Churn No = Green
- Added a simple dashboard title
-Layman analogy: Dashboard = a decorated notice board where charts are pinned neatly,  and slicers act like checkboxes to filter information instantly.


# Day 68 — Add KPIs to Dashboard
Learned:
- Opened Day 67 dashboard
- Decided KPIs:
  • Total Customers
  • Churned Customers
  • Churn Rate (%)
  • Avg Monthly Charges
- Created KPI cards using Card visual
- Wrote DAX measure for Churn Rate with correct table reference
- Formatted KPI cards with clear titles and colors
- Placed KPIs at the top of the dashboard
- Layman analogy: KPIs are like sticky notes with big numbers pinned at the top of the notice board, so anyone can see the most important stats instantly.


# Day 69 — Finalize Churn Project
Learned:
- Opened Day 68 KPI dashboard
- Cleaned visuals:
  • Aligned charts and cards
  • Standardized fonts and colors
  • Removed duplicate legends and repetitive field names
  • Renamed chart titles
- Polished slicers:
  • Consistent formatting
  • Clear titles for filters
- Added final touches:
  • Footer text box
  • Logo image
  • Neat layout: KPIs on top, charts in middle, slicers on side, footer at bottom
- Saved final project file for GitHub upload
- Layman analogy: Finalizing the dashboard is like tidying your room before guests arrive — everything looks neat, balanced, and professional.


