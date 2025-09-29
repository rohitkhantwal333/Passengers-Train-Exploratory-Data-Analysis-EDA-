1. Data Understanding and Inspection

Load the dataset and inspect its structure using .info() to check column types and missing values.

Use .describe() to get statistical summaries like mean, median, standard deviation for numerical columns.

For categorical columns, use .value_counts() to understand distribution and frequency of categories.

2. Data Cleaning (if required)

Handle missing values by either imputation or removal.

Convert columns to appropriate data types (e.g., date columns to datetime).

Remove duplicates if any to ensure data integrity.

3. Univariate Analysis

Plot histograms for numerical features to observe their distribution.

Use boxplots to detect outliers in passenger counts, ticket prices, or distances.

Analyze categorical variables with bar charts to see class distributions (e.g., train classes, stations, or routes).

4. Bivariate Analysis and Relationships

Plot scatterplots between numerical features like Distance vs Fare to identify correlations or patterns.

Use pair plots (sns.pairplot()) to visualize relationships between multiple numerical variables.

Compute correlation matrix and plot heatmap (sns.heatmap()) to identify strong positive/negative relationships.

Highlight anomalies, outliers, or unusual patterns that may need further investigation.

6. Summary of Findings
