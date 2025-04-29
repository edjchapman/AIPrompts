# Dataset Exploration Analysis

## Context
When starting a data analysis project, exploring and understanding the dataset is a crucial first step. This prompt helps generate a comprehensive exploratory data analysis approach.

## Prompt
```
I have a dataset about [topic/domain] with the following attributes:
- [List key variables/columns]
- [Mention sample size if known]
- [Note data format: CSV, JSON, etc.]

Please help me create a comprehensive exploratory data analysis plan that includes:

1. Initial data inspection steps (checking for missing values, outliers, data types)
2. Descriptive statistics to calculate for each variable
3. Key visualizations to create (suggest specific charts for different variables)
4. Potential relationships between variables to explore
5. Data quality issues to watch for
6. Preprocessing steps recommended before further analysis
7. Specific questions this dataset might help answer

For any statistical methods suggested, please explain why they're appropriate for this data.
```

## Notes
- Adjust the level of technical detail based on your expertise
- For time-series data, specifically request temporal analysis techniques
- You may want to add a request for code snippets in your preferred language (Python, R, etc.)
