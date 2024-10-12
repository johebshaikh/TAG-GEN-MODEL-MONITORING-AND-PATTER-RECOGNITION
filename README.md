# APPLIED RESEARCH PROJECT

### OKKULAR TAG-GEN-MODEL-MONITORING-AND-PATTER-RECOGNITION

## Project Supervisor
- Vishal Ahuja (Co-Founder & Data-Scientist)
- Mahendra Harish (Founder Advisor)

## Executive Summary
This project explores key patterns in eCommerce data and performs semantic segmentation to enhance the consumer experience, impacting business outcomes. Image segmentation, used to identify objects and boundaries, simplifies image representation for easier analysis by labeling pixels with common features.

The project starts with Exploratory Data Analysis (EDA) on a dataset from Google Analytics for an Okkular client's website, which includes events like items clicked, added to cart, and purchased. The data covers automated product tagging and visual search for clothing, footwear, and accessories across various digital platforms.

The final part of the project applies semantic segmentation to clothing images using MODNET and MobileNetV2, comparing their performance.

# Introduction

## Problem Definition


Product tagging is a critical method for identifying and categorizing a product's features, such as size, color, material, and brand. These tags help customers find items that match their preferences, thereby influencing purchasing decisions. For fashion retailers, identifying meaningful product attributes has become essential for boosting customer engagement and sales. By leveraging data analysis, companies can streamline the process of understanding customer needs, improving search efficiency, and increasing overall profitability. While this project primarily focuses on Exploratory Data Analysis (EDA), data visualization also plays a role in pre-processing tasks like outlier detection and model validation. Advances in image segmentation further enhance product tagging by automating feature identification, reducing the need for manual intervention, and allowing employees to focus on more creative tasks.

Okkular aims to drive innovation by automating low-impact tasks, increasing efficiency, and boosting revenue across the retail chain. The organization is particularly focused on understanding the factors that influence consumer behavior, such as website visits that don’t lead to purchases. Additionally, Okkular is exploring semantic segmentation techniques to automate background removal from product images, saving time for retail staff. The analysis involves several phases, including data cleaning, user grouping, and exploring semantic segmentation methods. These efforts are designed to expand Okkular's intelligent retail tools, improving both the consumer experience and operational productivity for retailers.

## Goals and Expected Outcomes

This project explores key patterns and implements image segmentation to enhance customer experience, a critical factor for the company. Image segmentation simplifies image representation by labeling pixels with common features, helping identify objects and boundaries.

The study focuses on three operational areas: sales, product tags, and fashion choices. By leveraging image segmentation, the company aims to track trends and improve sales monitoring through semantic and asemantic analysis. Product tagging also streamlines the shopping experience by aligning products with customer preferences, addressing the growing demand for personalized fashion choices.

## Conclusion

To enhance the recommender system, we recommend focusing on users interested in dresses and those who browse without specific category preferences. Targeting users based on time of day rather than day of the week would be more effective, as peak activity hours are consistent across time zones, making them ideal for promotions. While "frequently bought together" insights were limited, recommending items from the same clothing set should be prioritized.

Unexplored tasks that could provide further insights include:

Analyzing sessions that ended in a goal, such as the number of pageviews and triggered events.
Applying dimensionality reduction before clustering to uncover more meaningful patterns.
Conducting time series analysis to group users based on seasonal site visits.
For semantic segmentation, we suggest creating or finding a labeled dataset with photos that match the intended use. A possible starting point is this dataset, though it contains humans, which may cause overfitting to human shapes during training.
