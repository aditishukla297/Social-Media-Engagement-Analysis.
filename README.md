# Social Media Content Engagement Analysis

## Project Overview

Social media platforms generate large amounts of data through user interactions with online content. Analyzing these interactions helps understand content performance, audience engagement, and patterns across different platforms.

This project focuses on analyzing social media content engagement using Python. It explores engagement metrics across different platforms, post types, and publishing times to identify patterns and understand content performance.

The analysis is performed using Python libraries in Google Colab, with data visualization techniques to present meaningful insights.

## Project Objectives

- Analyze social media engagement metrics such as likes, comments, shares, impressions, and reach.
- Compare engagement across different content types and social media platforms.
- Examine the relationship between posting time and audience engagement.
- Calculate engagement rate using impressions as the denominator.
- Identify patterns and trends through data visualization.
- Derive meaningful insights from the available dataset.

## Dataset

This project uses the **Social Media Engagement Dashboard Dataset**.

**Original Dataset Source:** [Social Media Engagement Dashboard – GitHub](https://github.com/abhishek07ma/Social_Media_Engagement_Dashboard)

**Dataset File:** `Social_Media_Engagement.csv`

The dataset contains approximately 19,885 social media post records and includes the following attributes:

- Platform
- Post ID
- Post Type
- Post Timestamp
- Likes
- Comments
- Shares
- Impressions
- Reach
- Engagement Rate
- Audience Demographics
- Sentiment

**Note:** The dataset is obtained from an external repository and is not included in this project repository. Please refer to the original source for access and usage terms.

## Technologies Used

- **Python** – Programming language for data analysis.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical computations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical data visualization.
- **Plotly** – Interactive and animated visualizations.
- **Google Colab** – Cloud-based development environment.

## Data Preprocessing

The following preprocessing operations are performed:

1. Loading the dataset using Pandas.
2. Standardizing column names.
3. Converting timestamps into datetime format.
4. Converting engagement metrics into numeric data types.
5. Removing duplicate records.
6. Creating additional features such as posting hour, post date, and month.
7. Calculating total engagement and engagement rate.

## Engagement Metrics

### Total Engagement

Total engagement is calculated using the sum of likes, comments, and shares.

**Formula:**

`Total Engagement = Likes + Comments + Shares`

### Engagement Rate

The project calculates an impressions-based engagement rate to measure interactions relative to the number of impressions.

**Formula:**

`Engagement Rate (%) = (Total Engagement / Impressions) × 100`

Rows with missing or zero impressions are excluded from this calculated rate.

## Data Visualization

The project includes four main visualizations:

1. **Engagement Rate by Post Type:** Compares average engagement rates across different content formats.
2. **Engagement by Time of Day:** Examines how average engagement varies across different posting hours.
3. **Impressions and Reach by Platform:** Compares the average impressions and reach across social media platforms.
4. **Monthly Engagement Trend:** Examines changes in average total engagement over time.

### Additional Interactive Visualizations

- Donut chart showing the distribution of post types.
- Animated bar chart showing monthly engagement by post type.
- Animated scatter plot comparing impressions and total engagement over time.

## How to Run the Project

### Option 1: Google Colab (Recommended)

The project was developed and executed using Google Colab.

[**Open the Google Colab Notebook**](https://colab.research.google.com/drive/1mGRRKCYJJn9Xob1aFA1ST8OHuXxnSVLY?usp=sharing)

Steps:

1. Open the notebook using the Google Colab link.
2. Download `Social_Media_Engagement.csv` from the original dataset repository.
3. Run the notebook cells sequentially.
4. Upload the CSV file when prompted.

### Option 2: Run Locally

1. Clone this repository:

   `git clone https://github.com/aditishukla297/Social-Media-Engagement-Analysis.git`

2. Navigate to the project directory.

3. Install the required libraries:

   `pip install -r requirements.txt`

4. Download the dataset from the original source repository.

5. Place the CSV file in the project directory or inside a folder named `dataset`.

6. Open and run `Social_Media_Engagement_Analysis.ipynb` using Jupyter Notebook.

## Repository Structure

```text
Social-Media-Engagement-Analysis/
│
├── Social_Media_Engagement_Analysis.ipynb
├── README.md
└── requirements.txt
```

## Key Outcomes

The project provides a descriptive analysis of social media engagement patterns by examining:

- Differences in engagement across post types.
- Variations in engagement across posting hours.
- Platform-wise comparisons of impressions and reach.
- Monthly engagement trends.
- Relationships between post visibility and user interactions.

The visualizations help interpret content performance and identify patterns within the available dataset.

## Limitations

The analysis is descriptive and limited to the supplied dataset. Posting-time patterns do not establish causation, and findings should not be generalized beyond the dataset. The dataset's original source and usage terms should be consulted before redistribution.

## Conclusion

This project demonstrates how Python-based data analytics can be used to explore social media engagement patterns. Through data preprocessing, feature engineering, exploratory data analysis, and visualization, the project provides insights into how engagement varies across platforms, content formats, and publishing times.

## Acknowledgements

**Dataset:** Social Media Engagement Dashboard Dataset.

**Dataset Source:** [Abhishek07ma – Social Media Engagement Dashboard](https://github.com/abhishek07ma/Social_Media_Engagement_Dashboard)

**Project Analysis and Notebook:** Aditi Shukla.

**Development Environment:** Google Colab.
