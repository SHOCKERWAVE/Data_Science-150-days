                                                                    150 Day Data Science + Generative AI Roadmap



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


