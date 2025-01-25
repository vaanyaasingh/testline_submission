# testline_submission

# Quiz Performance Analysis and Personalized Recommendations

## Project Overview

This project analyzes historical and current quiz performance data to identify individual user strengths and weaknesses, and generates personalized recommendations for improvement. 

## Setup Instructions

### Dependencies

*   Python 3.x
*   pandas==1.5.3
*   matplotlib==3.7.1
*   seaborn==0.12.2
*   requests==2.28.1
*   IPython


### Data

The project uses data from three sources:

*   **Historical Quiz Data:** Contains past quiz attempts by different users. This data is fetched from: `https://api.jsonserve.com/XgAgFJ`
*   **Current Quiz Data:** Contains data about a recent quiz attempt. This data is fetched from: `https://www.jsonkeeper.com/b/LLQT`
*   **Submission Data:** This data is related to a specific user's recent quiz submission. This data is fetched from: `https://api.jsonserve.com/rJvd7g`

## Approach Description

1.  **Data Loading and Preprocessing:** The project begins by fetching data from the URLs provided above using the `requests` library. The data is then loaded into pandas DataFrames for analysis.
2.  **Performance Metric Calculations:** Several performance metrics are calculated, including accuracy, speed, initial mistake count, mistakes corrected, and better than.
3.  **Identification of Weak Areas and Trends:** The project identifies weak areas for individual users based on low accuracy, high initial mistakes, consistent weak topics across quizzes, struggles with specific difficulty levels, and negative performance trends.
4.  **Recommendation Generation:** Personalized recommendations are generated based on the identified weak areas and trends. These recommendations offer actionable advice for improvement, focusing on areas where the user can benefit most.
5.  **Visualizations:** The project uses `matplotlib` and `seaborn` libraries to create insightful visualizations, including accuracy trends over time, accuracy by topic and difficulty level, and correlation between difficulty and accuracy.


## Key Visualizations

**Visualization:** Accuracy Trend for User

**Description:** Plots user's accuracy trend over time. 
[Insert screenshot of the visualization here]



**Visualization:** Average Accuracy by Topic

**Description:** This visualization shows the average accuracy for different topics covered in the quiz. 
[Insert screenshot of the visualization here]



**Visualization:** Average Accuracy by Difficulty Level

**Description:** This bar plot depicts the average accuracy across different difficulty levels, giving insight into areas where users find the most challenges. 
[Insert screenshot of the visualization here]


**Visualization:** Correlation between Difficulty and Accuracy

**Description:** This shows how difficulty and accuracy are related, revealing if there's a noticeable impact of difficulty on user performance.
[Insert screenshot of the visualization here]



**Visualization:** Average Accuracy Over Time

**Description:** Illustrates the average accuracy achieved by users on a weekly basis, demonstrating whether overall performance is improving or declining over time. 
[Insert screenshot of the visualization here]



## Insights Summary

*   Accuracy and speed are crucial performance metrics.
*   Consistent weaknesses are observed in specific topics for certain users.
*   Users tend to struggle more with quizzes of higher difficulty levels.
*   Negative performance trends can reveal areas for targeted improvement.
*   Personalized recommendations offer tailored guidance to improve individual performance.


## Video Demonstration

[Add the link to your video here if applicable]

