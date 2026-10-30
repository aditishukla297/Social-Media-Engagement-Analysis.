# Social Media Engagement Analysis

A Python-based data analytics project exploring social media post engagement across platforms, content formats, and publishing times.

## Project objectives

- Inspect and clean social media post data.
- Calculate total engagement from likes, comments, and shares.
- Calculate an impressions-based engagement rate.
- Compare engagement by post type and platform.
- Explore posting-hour and monthly engagement patterns.
- Present findings through static and interactive visualizations.

## Dataset

The notebook expects a CSV file named `Social_Media_Engagement.csv`.

Place it here:

```text
dataset/Social_Media_Engagement.csv
```

**Dataset source:** Add the original dataset URL and publisher here before publishing.

**Licence:** Check the dataset's original licence and redistribution terms. Do not upload the CSV publicly unless its licence permits redistribution. If redistribution is not permitted or the licence is unclear, omit the CSV and explain how users can obtain it from the original source.

**Data provenance:** Verify whether the records are real, anonymized, or synthetic. Do not describe them as verified real-world social media activity unless the source supports that claim.

## Analysis and methodology

### Total engagement

`Total Engagement = Likes + Comments + Shares`

### Engagement rate

`Engagement Rate (%) = (Total Engagement / Impressions) * 100`

The engagement rate calculated in this project is impressions-based. It is not interchangeable with reach-based or follower-based engagement rates. Rows with zero or missing impressions receive no calculated rate.

## Visualizations

The notebook includes four core static charts:

1. Average engagement rate by post type.
2. Average engagement by posting hour.
3. Average impressions and reach by platform.
4. Average monthly engagement.

It also includes interactive Plotly visualizations for post-type distribution, monthly engagement by post type, and impressions versus engagement over time.

## Technologies used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Google Colab / Jupyter Notebook

## Installation

Install the required packages:

```bash
pip install -r requirements.txt
```

## Run the project

1. Clone or download this repository.
2. Place the dataset CSV in the `dataset/` folder.
3. Open `Social_Media_Engagement_Analysis.ipynb` in Jupyter Notebook or Google Colab.
4. Run all cells from top to bottom.

In Google Colab, the notebook can also prompt you to upload the CSV if it is not found in the expected location.

## Repository structure

```text
Social-Media-Engagement-Analysis/
├── Social_Media_Engagement_Analysis.ipynb
├── dataset/
│   └── Social_Media_Engagement.csv   # include only if redistribution is permitted
├── images/                           # optional screenshots of notebook charts
├── README.md
├── requirements.txt
└── LICENSE                           # add only after choosing an appropriate licence
```

## Limitations

The analysis is descriptive and limited to the supplied dataset. Posting-time patterns do not establish causation, and findings should not be generalized beyond the dataset. Dataset provenance and licence should be verified and documented.

## Acknowledgements

Dataset: [Add original dataset title, publisher, and source URL].

Project analysis and notebook: [Add author/team details if required by your course].
