# User Journey Analysis in Python Project

This project focuses on analyzing user journey data to better understand user behavior on a website. The dataset contains information about user sessions, subscription types, and a sequence of user actions. By cleaning and processing the data, we aim to gain valuable insights into user navigation and identify popular patterns and conversion paths.

## Project Overview

The main goals of this project are:
1. **Preprocess the user journey data**: Clean the raw user journeys by removing consecutive duplicate actions and filtering out specific pages like "Log in" and "Sign up".
2. **Analyze user navigation**: Group user sessions, split actions, calculate journey length, and identify popular navigation patterns.
3. **Extract insights**: Perform detailed analyses to answer quiz questions about common user behaviors and conversion actions.

## Files in This Repository

- **`user_journey_raw.csv`**: The raw data used for the analysis, containing user session information.
- **`cleaned_user_journeys.csv`**: The cleaned version of the data, exported after processing.
- **`user_journey_analysis.ipynb`**: The Jupyter Notebook containing all the steps involved in cleaning, analyzing, and extracting insights from the dataset.
- **`README.md`**: This file, providing an overview of the project.

## Project Steps

1. **Data Loading and Exploration**
   - Loaded the dataset from CSV and performed an initial inspection of its structure, data types, and missing values.

2. **Data Cleaning**
   - Removed consecutive duplicate actions to make the user journey clearer.
   - Filtered out specific pages (e.g., "Log in", "Sign up") that weren't needed for deeper analysis.

3. **User Journey Processing**
   - Split user journeys into individual actions for better analysis.
   - Grouped multiple sessions for each user into a single, consolidated journey.
   - Calculated journey length for each user to understand the depth of engagement.

4. **Pattern and Funnel Analysis**
   - Analyzed the most common navigation paths.
   - Identified key content pages and how users navigated towards conversion points.
   - Answered specific quiz questions related to popular sequences, page visits, and conversion rates.

## Key Insights

- **Most Popular Navigation Patterns**: Extracted insights about the most common sequences of actions taken by users, including identifying popular entry and exit points.
- **Content Engagement**: Determined which pages are the most engaging for users and how often they navigate through key content.
- **Conversion Analysis**: Analyzed how often users reached conversion pages like "Checkout" and identified key user behaviors leading to conversions.

## Tools Used

- **Python**: Main programming language used for data manipulation and analysis.
- **Pandas**: Library for data manipulation and analysis.
- **Jupyter Notebook**: Environment for interactive development and documenting the process.

## Future Work

- **Advanced Segmentation**: Analyze user journeys based on different segmentation criteria (e.g., by subscription type or user activity level).
- **Visualization**: Create visualizations of the user journeys for easier understanding of the user flow and common paths.
- **Predictive Modeling**: Use machine learning models to predict future user actions based on historical journey data.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

## Contributing

Feel free to open an issue or submit a pull request for any improvements or additional features you would like to see.

## Contact

For questions or further information, please contact [your email].
