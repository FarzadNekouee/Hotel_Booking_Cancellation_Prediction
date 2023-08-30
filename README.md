# 🏨 Hotel Booking Cancellation Prediction and Analysis
![Hotel Booking Cancellation Prediction](image.jpg)

## 🌐 Overview
This repository contains a project focused on predicting hotel booking cancellations. The dataset includes a variety of features related to hotel bookings, such as lead time, deposit type, and special requests. The primary objective is to develop a predictive model that accurately determines whether a hotel booking would be canceled. This prediction is essential for hotels as cancellations can significantly impact revenue and operational planning.

## 🌟 Problem
In this project, we aim to build a predictive model to determine whether a hotel booking would be canceled, which is crucial for hotels as cancellations affect revenue and operational planning. The dataset contains a high number of features related to booking, such as lead time, deposit type, and special requests, which adds to the complexity of the model. The challenge lies in the data preprocessing steps, which include feature selection and engineering, handling missing values, and noise in the data. Additionally, we are going to train different models, evaluate their performance using the right metrics, and interpret the model by analyzing the most important features in the context of hotel booking cancellations.

## 🎯 Objectives
The objectives of the project are as follows:

* **Explore the Dataset**: Investigate the dataset's basic information, including summary statistics for numerical and categorical variables.
* **Preprocessing Steps**:
  - Select and engineer features to enhance predictive performance.
  - Handle missing values effectively.
  - Address noise in the data to improve model robustness.
  - Encode categorical variables for use in machine learning models.
* **Model Building**:
  - Implement and fine-tune classification models, including Decision Trees, Random Forest, and XGBoost.
  - Emphasize achieving high F1-score for class 1 predictions to comprehensively identify booking cancellations.
* **Evaluate and Compare Model Performance**: Utilize accuracy, precision, recall, F1-score, and AUC to gauge models' effectiveness.
* **Analyze Feature Importance**: Understand which features have the most significant impact on model predictions and interpret their relevance in the context of hotel booking cancellations.

## 📚 Dataset Description
The dataset comprises various metrics related to hotel bookings. The features of the dataset are described in the table below:

| Index | Variable            | Description |
| :---  | :---                | :---        |
| 1     | hotel               | Type of hotel (Resort Hotel, City Hotel) |
| 2     | is_canceled         | Reservation cancellation status (0 = not canceled, 1 = canceled) |
| 3     | lead_time           | Number of days between booking and arrival |
| 4     | arrival_date_year   | Year of arrival |
| 5     | arrival_date_month  | Month of arrival |
| 6     | arrival_date_week_number | Week number of the year for arrival |
| 7     | arrival_date_day_of_month | Day of the month of arrival |
| 8     | stays_in_weekend_nights | Number of weekend nights (Saturday and Sunday) the guest stayed or booked |
| 9     | stays_in_week_nights | Number of week nights the guest stayed or booked |
| 10    | adults              | Number of adults |
| 11    | children            | Number of children |
| 12    | babies              | Number of babies |
| 13    | meal                | Type of meal booked (BB, FB, HB, SC, Undefined) |
| 14    | country             | Country of origin of the guest |
| 15    | market_segment      | Market segment designation |
| 16    | distribution_channel | Booking distribution channel |
| 17    | is_repeated_guest   | If the guest is a repeat customer (0 = not repeated, 1 = repeated) |
| 18    | previous_cancellations | Number of previous bookings that were canceled by the customer |
| 19    | previous_bookings_not_canceled | Number of previous bookings that were not canceled by the customer |
| 20    | reserved_room_type  | Type of reserved room |
| 21    | assigned_room_type  | Type of assigned room |
| 22    | booking_changes     | Number of changes made to the booking |
| 23    | deposit_type        | Type of deposit made (No Deposit, Refundable, Non Refund) |
| 24    | agent               | ID of the travel agent responsible for the booking |
| 25    | company             | ID of the company responsible for the booking |
| 26    | days_in_waiting_list | Number of days the booking was in the waiting list |
| 27    | customer_type       | Type of customer (Transient, Contract, Transient-Party, Group) |
| 28    | adr                 | Average Daily Rate |
| 29    | required_car_parking_spaces | Number of car parking spaces required |
| 30    | total_of_special_requests | Number of special requests made |
| 31    | reservation_status  | Last reservation status (Check-Out, Canceled, No-Show) |
| 32    | reservation_status_date | Date of the last reservation status |
| 33    | name                | Guest's name |
| 34    | email               | Guest's email address |
| 35    | phone-number        | Guest's phone number |
| 36    | credit_card         | Last four digits of the guest's credit card |


## 📁 File Descriptions
- 📓 **`Hotel_Booking_Cancellation_Prediction.ipynb`**: Jupyter notebook containing data exploration, visualization, modeling, and evaluation code.
- 📁 **`Hotel_Booking.csv`**: CSV file containing the hotel booking dataset.
- 📘 **`README.md`**: This file, providing an overview of the project.


## 🚀 Instructions for Local Execution
1. **Clone this Repository**: Begin by cloning this repository to your local setup.
2. **Open the Notebook**: Access the `Hotel_Booking_Cancellation_Prediction.ipynb` in Jupyter.
3. **Install Dependencies**: Ensure all necessary Python libraries are installed for seamless execution.
4. **Execution**: Run all cells in the notebook to witness the results and insights.

## 🔗 Additional Resources
- 🌐 **Kaggle Notebook**: If you're keen on a Kaggle environment, delve into the notebook [here](https://www.kaggle.com/farzadnekouei/code).
- 🤝 **Connect on LinkedIn**: Have queries or looking for collaborations? Feel free to connect on [LinkedIn](https://www.linkedin.com/in/yourusername/).
