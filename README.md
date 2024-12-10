# Exploria Machine Learning Repository

Exploria is a project designed to enhance travel experiences while promoting sustainable tourism in Indonesia. By leveraging advanced technologies like AI and machine learning, this system provides smart recommendations tailored to individual preferences, helping travelers explore Indonesia responsibly and meaningfully.

## Why Exploria?

Indonesia is striving to become one of the world’s top 10 global tourism destinations by 2045. This ambition is supported by remarkable growth in the tourism sector. According to the latest data from BPS-Statistics Indonesia, the country welcomed over 10 million foreign visitors by September 2024, a 20.28% increase from the same period in 2023. This steady rise reflects Indonesia's rich cultural and natural attractions, along with continuous improvements in tourism infrastructure.

In 2023 alone, Indonesia recorded 14.5 million international arrivals, up from 10.4 million in 2022. Tourism contributed significantly to the national economy, accounting for 5.5% of GDP. However, such rapid growth presents challenges, particularly in ensuring that development does not compromise the environment or cultural heritage. The increasing popularity of destinations demands solutions that balance economic gains with sustainability and preservation.

Exploria is our answer to this challenge. By promoting eco-friendly, culturally respectful tourism, it aligns with Indonesia's vision for responsible and sustainable travel, ensuring future generations can enjoy the country's natural and cultural wonders.

## Our Goals

Exploria is designed to:
- Provide personalized travel recommendations to match individual preferences.
- Promote sustainable tourism practices to protect Indonesia's environment and cultural assets.
- Encourage responsible travel choices that create meaningful experiences for visitors while preserving the country’s unique heritage.

## Table of Contents
- [Datasets](#datasets)
- [Library](#library)
- [Model](#model)
- [Evaluation](#evaluation)
- [Model Conversion](#model-conversion)
- About the team

## Datasets

The datasets used in this project are essential for training the machine learning models and generating personalized travel recommendations. Below is a list of datasets included in the project:

1. **Tour_Guide_Biografi_Unique.xlsx**  
   This dataset contains biographical information about various tour guides, ensuring that only unique records are included. It is used to match travelers with the most relevant local guides.

2. **Tour_Guide_Biografi_with_Links_New.csv**  
   A CSV file containing detailed biographical data about tour guides, along with links to additional resources or online profiles. This dataset is crucial for providing in-depth information to travelers.

3. **new_tourism_rating_comments.csv**  
   This file includes ratings and comments for tourism spots. It helps in evaluating the popularity of destinations based on user reviews, which is important for making recommendations.

4. **new_tourism_with_id_links_3.csv**  
   This dataset contains information about tourism spots, including unique IDs and links for further reference. It is useful for linking different aspects of the tourism experience (e.g., attractions, activities) with IDs.

5. **old_users_data_with_links.csv**  
   A dataset containing older user data, including their interaction history with tourism recommendations and links to resources. This is useful for analyzing past behavior and preferences to make more personalized suggestions.

6. **old_users_data_with_links.xlsx**  
   Similar to the CSV version above but in Excel format, containing historical data of users’ interactions with the platform and relevant links.

7. **package_tourism.csv**  
   A dataset listing available tourism packages, including descriptions, pricing, and additional details. This helps in recommending tourism packages to users based on their preferences.

8. **tourist_spots_distance.csv**  
   This file includes the distances between various tourist spots. It is used in optimizing itineraries for users, ensuring that the suggested travel routes are efficient and practical.

All datasets are located in the `Dataset` folder. Make sure to check the data formats and adjust any preprocessing steps as needed before using them to train the models.

---

## Library

In this project, we rely on several libraries to handle data processing, model building, and evaluation. Below are some of the core libraries used:

- **pandas**: For data manipulation and preprocessing.
- **NumPy**: For numerical computing and handling arrays.
- **Scikit-Learn**: For machine learning model building and evaluation.
- **TensorFlow**: For building and training deep learning models.
- **Matplotlib**: For visualizations and result plotting.

The list of libraries and their versions can be found in the `requirements.txt` file. Install them using the following command:

```bash
pip install -r requirements.txt
```
---
## About the Team

Exploria’s Machine Learning team consists of passionate individuals from Bangkit 2024 Batch 2:
| **Name**                | **Bangkit ID**       | **Path**           |
|--------------------------|----------------------|--------------------|
| Komang Ryandhi Suandita | M004B4KY2222    | Machine Learning   |
| Bayu Siddhi Mukti        | M004B4KY0830      | Machine Learning   |
| Yasmin Nur Helisa       | M004B4KX4522     | Machine Learning   |

## Vision for the Future

By fostering sustainable and meaningful tourism, Exploria contributes to Indonesia’s goal of becoming a global tourism powerhouse. Our platform combines cutting-edge technology with a commitment to preservation, ensuring a brighter, balanced future for Indonesia’s tourism industry.

---

Explore responsibly. Travel meaningfully. With Exploria.
