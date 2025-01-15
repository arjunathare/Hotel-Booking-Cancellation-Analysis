# Hotel-Booking-Cancellation-Analysis

*Overview :
This project analyzes hotel booking data to identify patterns and key factors influencing booking cancellations. The goal is to provide actionable insights to help hotels reduce cancellations and optimize revenue strategies.

*Key Features :
-Data Cleaning and Preprocessing: Handled missing values, removed irrelevant columns, and addressed outliers for reliable analysis.

-Exploratory Data Analysis (EDA):
Analyzed trends in cancellations based on lead time, deposit policies, and average daily rate (ADR).
Identified patterns in customer demographics, booking behaviors, and seasonality.

-Visualizations:
Created bar charts, line plots, and heatmaps using Matplotlib and Seaborn to visualize cancellation trends.
Highlighted relationships between factors like ADR and cancellation rates.

-Insights and Recommendations:
Flexible deposit policies and pricing adjustments can significantly reduce cancellations.
Seasonality impacts booking behaviors, suggesting potential for targeted marketing campaigns.

*Dataset
-Source: [Kaggle]

-Description: The dataset contains information about hotel bookings, including:
Booking details (arrival date, lead time, stay duration).
Guest details (country, market segment, number of children).
Financial details (ADR, deposit type).
Cancellation status (is_canceled: 1 = canceled, 0 = not canceled).

*Technologies Used
-Programming Language: Python

-Libraries:
pandas: Data cleaning and preprocessing.
numpy: Statistical computations.
matplotlib, seaborn: Data visualization.

*Key Findings
-Cancellation Rate: Approximately 37% of bookings were canceled.

-Key Influencing Factors:
Long lead times increase cancellation rates.
High ADRs during peak seasons contribute to cancellations.
Non-refundable deposit policies discourage cancellations.
Seasonality: Cancellation rates are higher during specific months due to fluctuating demand.

*Recommendations
Implement flexible deposit and cancellation policies to reduce cancellations.
Adjust pricing strategies during high-demand seasons.
Target specific customer segments with promotions to encourage bookings.

*Project Structure
hotel_bookings.csv: Dataset file.
Hotel_Booking_Analysis.ipynb: Jupyter Notebook with data analysis and visualizations.
README.md: Project documentation.
