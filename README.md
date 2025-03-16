# 📊 Exploratory Data Analysis (EDA) and Feature Engineering of Google Play Store Dataset

## 📌 Project Overview
With over **2.56 million apps** available on the Google Play Store, understanding app trends is crucial for businesses and developers. This project performs **Exploratory Data Analysis (EDA) and Feature Engineering** to uncover insights such as:
- The **most popular app categories**
- The **apps with the highest installs**
- The **distribution of app sizes and ratings**

## 📂 Dataset Information
The dataset consists of various attributes of apps on the Play Store, including:
- **App**: Name of the app
- **Category**: The app’s category (e.g., Games, Productivity, Social, etc.)
- **Rating**: User rating of the app
- **Reviews**: Number of reviews received
- **Size**: App size (in MB)
- **Installs**: Number of installations
- **Type**: Free or Paid
- **Price**: Price of the app (0 if Free)
- **Content Rating**: Suitable audience (e.g., Everyone, Teen, Adults)
- **Genres**: App genres
- **Last Updated**: Last update date
- **Current Version**: The app’s current version
- **Android Version**: Minimum Android version required

## 🛠️ Steps Followed
### 1️⃣ Data Cleaning
- Identified and handled **missing values** and **duplicate records**.
- Converted data types for better analysis.
- Processed numerical and categorical features separately.

### 2️⃣ Exploratory Data Analysis (EDA)
- **Univariate Analysis**: Examined the distribution of numerical and categorical features using KDE plots, and count plots.
- **Bivariate Analysis**: Explored relationships between key variables such as category-wise installs and rating distribution.
- **Visualization Techniques**: Used **Matplotlib & Seaborn** for bar charts, pie charts, and KDE plots.

### 3️⃣ Feature Engineering
- Extracted **year, month, and day** from the ‘Last Updated’ column.
- Grouped apps by category and calculated **total installs per category**.
- Identified the **top 5 most installed apps in popular categories**.

## 📊 Key Insights & Observations
🔹 **Category Distribution:**
- The **Family category** has the highest number of apps (**19%**), followed by Games (**11%**).
- **Beauty and Comics categories** have the least number of apps (<1%).

🔹 **Most Popular Categories (by Installations)**
- **Games** lead with **35 billion+ installs**, followed by Communication and Productivity apps.

🔹 **Top Apps in Popular Categories**
- **Most popular game**: Subway Surfers
- **Most popular communication app**: Hangouts
- **Most popular productivity app**: Google Drive
- **Most popular social app**: Instagram

🔹 **5-Star Rated Apps**
- There are **271 apps** with a perfect 5-star rating.
- **Top-rated app:** ‘CS & IT Interview Questions’ (from the Family category).

## 💻 Tech Stack
- **Python**
- **Pandas, NumPy** (for data cleaning & manipulation)
- **Matplotlib, Seaborn** (for visualizations)
- **Jupyter Notebook** (for analysis & development)

## 📌 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/piyush35482/google-playstore-eda
   ```
2. Navigate to the project directory:
   ```bash
   cd google-playstore-eda
   ```

## 📜 Conclusion
This project provides valuable insights into the Google Play Store landscape. It highlights trends that can help developers and businesses make **data-driven decisions** regarding app development, marketing, and user engagement.

🚀 **Future Improvements:**
- Perform **sentiment analysis** on app reviews.
- Implement **machine learning models** to predict app ratings.
- Create an **interactive dashboard** for better data exploration.

📢 **Contributions & Feedback**
Feel free to fork the repository, suggest improvements, or reach out for discussions! 😊

