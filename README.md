
## Project Overview

This project focuses on analyzing quiz performance data to extract meaningful insights, identify weak areas, and provide actionable recommendations. It leverages Python libraries like Pandas, Seaborn, and Matplotlib for data analysis and visualization.

## Key Features

1. Data Loading

- Data was from API endpoints loaded and cleaned.

- Columns were converted to appropriate data types (e.g., datetime conversion for timestamps, numeric conversion for scores).

2. Data Cleaning

- Handled missing values.

- Ensured numeric columns (e.g., accuracy, score, negative_score) were correctly formatted.

- Removed unnecessary columns and standardized data schemas.

3. Data Analysis

- Performance by Topics

    I. Grouped quizzes by topic to analyze:

        . Average duration.

        . Correct answer marks.

        . Number of questions per topic.

    II. Visualized topic distribution using pie charts.

 - User Performance Metrics

    I. Grouped historical performance data by quiz_id to calculate:

       . Average scores.

       . Average accuracy.

       . Average speed and negative scores.

    II. Visualized these metrics with bar and line charts.

- Weak Areas and Trends

    I. Identified quizzes with:

      . Low accuracy.

      . High negative marks.

      . Topics requiring attention.

    II. Highlighted patterns in user performance over time.

4. Recommendations

- Proposed areas for improvement based on insights:

    I. Focus on topics with low accuracy.

    II. Practice quizzes with high negative scores.

    III. Spend more time on challenging topics.

5. Student Persona

- Defined personas by categorizing students based on performance metrics (e.g., accuracy, speed).

- Highlighted specific strengths and weaknesses with creative labels.
## Key Insights

- Certain topics (e.g., Body Fluids and Circulation) had longer durations but lower accuracy rates, indicating a need for focused practice.

- Quizzes with higher negative scores corresponded to difficult topics.

- Users performed better when accuracy was prioritized over speed.
## Visualizations

- Bar charts for average scores by quiz.

- Line charts for accuracy trends.

- Pie charts showing topic distribution.
## Future Work

- Enhance analysis by integrating additional user demographic data.

- Apply machine learning models to predict user performance trends.

- Develop personalized quiz recommendations based on past performance.
## Requirements

- Python, Pandas, Numpy, Matplotlib, Seaborn, Requests, Warnings
## How to Use

- Ensure the required libraries are installed.

- Run the analysis script to generate insights and visualizations.

- Review the visualizations and recommendations to guide quiz improvements.