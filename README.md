#  Hotel Booking and Cancellation Analysis

## 📌 Project Overview
The main aim of this project is to understand hotel booking patterns and identify factors associated with booking cancellations.

This project uses Exploratory Data Analysis (EDA) techniques to analyze hotel booking data and discover useful insights about customer behavior, booking trends, and cancellation patterns.

##  Objectives
- Understand hotel booking patterns.
- Analyze canceled and non-canceled bookings.
- Identify factors associated with booking cancellations.
- Compare booking rates between different hotel types.
- Understand customer booking behavior.
- Visualize booking trends and relationships.

##  Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

##  Dataset Description
The project uses the Hotel Booking Dataset (`hotel_bookings.csv`).

The dataset contains information about:
- Hotel type
- Booking status
- Lead time
- Arrival date
- Number of guests
- Customer type
- Market segment
- Average Daily Rate (ADR)
- Previous cancellations
- Special requests

##  Data Preprocessing
The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Checked dataset shape, columns, and data types.
3. Identified missing values.
4. Removed duplicate records.
5. Dropped the unnecessary company column.
6. Handled missing values in children, agent, and country columns.
7. Replaced undefined values in categorical columns.
8. Created a new arrival_date column.
9. Created a total_guests column.
10. Created a cancellation_status column.

##  Exploratory Data Analysis

The following visualizations and analyses were performed:

- Booking Distribution by Hotel Type
- Canceled vs Non-Canceled Bookings
- Cancellation Percentage (Pie Chart)
- Lead Time Distribution (Histogram)
- Lead Time vs ADR (Scatter Plot)
- ADR Outlier Detection (Box Plot)
-
