# Extracting Attractive App Aspects from Reviews

This project utilizes Natural Language Processing (NLP) and Clustering Machine Learning techniques to extract and categorize attractive aspects of mobile applications from user reviews. The model is based on the Kano Model, which classifies features based on the impact of the presence or absence of a feature on users' satisfaction. 

For more information, check out our [Project Wiki](https://github.com/JohnsL-U/App-Feature-Extraction/wiki).

## Table of Contents

1. [Introduction](#introduction)
2. [Acknowledgments](#acknowledgments)
3. [Methodology](#methodology)
4. [Results and Discussion](#results)
5. [Improvements and Future Work](#improvements)
6. [Usage](#usage)
7. [Team](#team)
8. [License](#license)

## <a name="introduction"></a>Introduction

The main goal of this project is to use the Kano model and machine learning clustering techniques to analyze user reviews and extract aspects that increase user satisfaction. This is accomplished through a series of data preprocessing, aspect extraction, aspect satisfaction evaluation, and clustering stages.

## <a name="acknowledgments"></a>Acknowledgments

This project is based on the research titled "Extracting Attractive App Aspects from App Reviews using Clustering Techniques based on Kano Model" by Nadeen AlAmoudi, Malak Baslyman, and Motaz Ahmed from the Department of Information & Computer Science, King Fahd University of Petroleum & Minerals, Dhahran, Saudi Arabia. Their original code and data served as the foundation for this project and can be found at this [GitHub repository](https://github.com/NadeenAmoudi/extracting-attractive-app-aspects). We express our deepest gratitude to the authors for making their valuable work available to the community.

## <a name="methodology"></a>Methodology

Our approach consists of four main phases:

1. **Data preprocessing:** This involves cleaning and formatting the review data for further analysis.
2. **App aspects extraction:** This process identifies and extracts the various aspects of the app mentioned in the reviews.
3. **App aspects satisfaction evaluation:** Sentiment analysis is used to calculate the satisfaction and dissatisfaction scores for each aspect.
4. **Extracting attractive app aspects:** The satisfaction and dissatisfaction values of each aspect are then used in clustering algorithms to categorize aspects based on their attractiveness to users.

## <a name="results"></a>Results and Discussion

After implementing our methodology, we compared the resulting categorizations with the ground truth from a user survey. The results were promising, with our system successfully identifying all the attractive aspects. However, certain aspects were missed or misplaced, indicating the need for further improvement.

## <a name="improvements"></a>Improvements and Future Work

Some of the improvements made to the original research methodology include refining the data preprocessing step, using alternative NLP tools, rewriting missing code sections, and generating synthetic survey data. However, future work will include conducting an actual user survey and integrating these responses for better accuracy.

## <a name="usage"></a>Usage

This project was implemented in Python. Please ensure you have the required libraries installed. Instructions for running the various scripts are included in the individual script files.

## <a name="team"></a>Team

This project is a collaborative effort from:

- [JohnsL-u](https://github.com/JohnsL-U)
- [sananeminli](https://github.com/sananeminli)
- [Ali-Hakan](https://github.com/Ali-Hakan)


## <a name="license"></a>License

This project is licensed under the terms of the [MIT license](LICENSE).

## Contact

For any queries or discussion related to this project, feel free to reach out to us. We'd love to hear any feedback, suggestions, or new ideas.
