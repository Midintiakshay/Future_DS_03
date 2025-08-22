# College Event Feedback Analysis Project

## Project Overview
This project analyzes student feedback data collected via Google Forms to gain meaningful insights that can help improve campus events and educational experiences.

## Objectives
- Clean and prepare feedback data.
- Analyze rating patterns across different categories.
- Perform sentiment analysis on text feedback.
- Create visualizations to illustrate findings.
- Generate actionable recommendations (based on the analysis).

## Tools Used
- **pandas**: Data manipulation and analysis
- **matplotlib & seaborn**: Data visualization
- **textblob**: Sentiment analysis
- **wordcloud**: Creating word clouds
- **numpy**: Numerical operations

## Dataset
- **Source**: Simulated Student feedback collected via Google Forms (sample data used in this notebook).
- **Total Responses**: 1,000 students.
- **Rating Scale**: 1-10 (1 = Poor, 10 = Excellent).
- **Categories**: 8 different aspects of courses/events.

## Analysis Highlights (Based on Sample Data)

### Overall Satisfaction
The overall average rating across all categories in the sample data is approximately **6.13/10**.

### Top Performing Areas
Based on the sample data, the areas with the highest average ratings are:
1.  **Well versed with the subject**: Approximately 7.46/10
2.  **Use of presentations**: Approximately 7.01/10
3.  **Explains concepts in an understandable way**: Approximately 6.46/10

### Areas for Improvement
Based on the sample data, the areas with the lowest average ratings (needing attention) are:
1.  **Course recommendation based on relevance**: Approximately 5.55/10
2.  **Provides support for students going above and beyond**: Approximately 5.53/10
3.  **Degree of difficulty of assignments**: Approximately 5.42/10

### Sentiment Analysis (Sample Data)
-   **Positive Sentiment**: Approximately 60.0%
-   **Neutral Sentiment**: Approximately 20.0%
-   **Negative Sentiment**: Approximately 20.0%

### Student Segmentation (Sample Data)
-   **Satisfied**: ~58.0%
-   **Neutral**: ~39.6%
-   **Highly Satisfied**: ~1.7%
-   **Dissatisfied**: ~0.7%

## How to Use the Notebook
1.  Ensure you have the required libraries installed (`pandas`, `numpy`, `matplotlib`, `seaborn`, `textblob`, `wordcloud`, `plotly`). The notebook includes a cell to install these.
2.  Replace the sample data loading section with code to load your actual `student_feedback.csv` file.
3.  Run the cells sequentially to perform data loading, exploration, analysis, and visualization.
4.  Interpret the outputs and visualizations to derive actionable insights for improving college events.

---

*This README was generated based on the analysis performed in the accompanying Colab notebook.*
