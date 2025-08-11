You've hit on a crucial concept in machine learning and data science: how to structure your analysis and data preparation. While there isn't one single, universally accepted "famous framework" that dictates exactly how to divide your features (e.g., "personal info," "academic info"), there are several established and widely used methodologies for thinking about and organizing your data.

The most common frameworks for dividing data in ML are:

### 1. By Feature Type (for analysis and preprocessing)

This is the most fundamental and technical way to categorize features, as it directly impacts what kind of analysis and preprocessing you'll perform on them.

* **Numerical Features:** These are measurable quantities. You can perform mathematical operations on them.
    * **Continuous:** Can take any value within a range (e.g., `age`, `marks`, `screen_time`).
    * **Discrete:** Can only take specific, fixed values (e.g., `number_of_siblings`, `number_of_classes_attended`).
* **Categorical Features:** These represent groups or categories. They are often not numerical.
    * **Nominal:** Categories have no inherent order (e.g., `city`, `gender`, `person_id`).
    * **Ordinal:** Categories have a clear, meaningful order (e.g., `school_grade` like 'A', 'B', 'C'; `satisfaction_level` like 'low', 'medium', 'high').
* **Identifiers:** As you noted, these are a special type of categorical feature. They are unique labels for each record and are not used for analysis or modeling. (e.g., `name`, `ID`). You would typically drop these before building a model.
* **Time-Series Features:** Data with a time component. The order of the data is important for analysis (e.g., `date`, `time_of_day`).
* **Text Features:** Unstructured text data (e.g., `comments`, `essays`). These require specific preprocessing techniques like tokenization and vectorization.

This framework is essential for the EDA phase because the type of variable determines the type of visualization and statistical test you should use. For example, you'd use a histogram for a numerical feature like `marks` but a bar chart for a categorical feature like `school_grade`.

### 2. By Role in the Machine Learning Model

This framework is more about the purpose each feature serves in your model-building process.

* **Target Variable (or Dependent Variable):** This is the variable you're trying to predict. In your example, this could be `marks` or `school_performance`.
* **Feature Variables (or Independent Variables):** These are all the other variables in your dataset that you believe might be useful for predicting the target. This would include `screen_time`, `study_hours`, `age`, and so on.
* **Non-Feature Variables:** These are the variables that are not used in the model, such as the `name` and `ID` you identified.

### 3. By Domain or Business Logic

This is the framework you mentioned in your question ("personal info," "academic info"). While not a formal ML framework, it's a very practical and common approach, especially at the beginning of a project.

* **Personal Information:** (e.g., `name`, `age`, `address`, `parent_occupation`)
* **Academic Information:** (e.g., `marks`, `grades`, `subjects`, `attendance`)
* **Behavioral Information:** (e.g., `screen_time`, `study_hours`, `extracurricular_activities`)

This kind of grouping is helpful for:
* **Communicating with stakeholders:** It makes it easier to discuss the data with people who are not machine learning experts.
* **Generating hypotheses:** It helps you systematically think about different factors that could be related to your target variable.
* **Data privacy and governance:** It's easier to identify which columns contain sensitive personal information that needs to be handled carefully or anonymized.

### Summary

The most famous and fundamental framework in machine learning for dividing data is by **feature type** (numerical, categorical, identifiers). This directly informs your EDA and preprocessing steps.

However, in practice, a good data scientist will use a combination of these frameworks. You'll start with the high-level, business-oriented grouping to form your initial hypotheses, then switch to a more technical feature-type framework to perform the actual EDA and data preprocessing, and finally, use the target/feature variable framework to build and evaluate your model.