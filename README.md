# 🏨 Hotel Data Analysis Project

## 🎯 Project Overview

This project analyzes hotel booking data to uncover insights into guest behavior, booking patterns, and revenue trends for city and resort hotels. The analysis includes identifying frequent guests, popular countries of origin, booking trends by day and week, average stay lengths, and customer spending patterns. The goal is to help hotel management understand their customers better and make data-driven decisions.

---

## 🗂 Dataset Description

The dataset contains booking information for a city hotel and a resort hotel, including details such as booking date, length of stay, number of adults, children, and babies, and the number of parking spaces. All personally identifying information has been removed.

* **Number of Rows & Columns:** Varies per dataset
* **Key Variables:**

  * `ADR` – Average Daily Rate
  * `Adults`, `Children`, `Babies` – Number of guests
  * `ArrivalDateDayOfMonth`, `ArrivalDateMonth`, `ArrivalDateWeekNumber`, `ArrivalDateYear` – Arrival details
  * `IsCanceled` – Booking cancellation status
  * `CustomerType` – Type of booking (Contract, Group, Transient, Transient-party)
  * `TotalOfSpecialRequests` – Number of special requests
  * `LeadTime` – Days between booking and arrival
  * And other variables describing the booking and guest characteristics

**Source:** Data originally from *Hotel Booking Demand Datasets* by Nuno Antonio, Ana Almeida, and Luis Nunes (Data in Brief, Volume 22, February 2019). Names, emails, phone numbers, and credit card numbers are synthetic.

---

## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* Datetime libraries (for handling dates)

---

## 🔍 Exploratory Data Analysis (EDA) & Insights

### 1️⃣ General Overview

* Checked dataset dimensions and missing values
* Removed columns with excessive null values (`company`)

### 2️⃣ Guest Demographics & Behavior

* **Top 5 Countries with Highest Bookings**
* **Most Frequent Guest Last Names (Top 5)**
* **Percentage of Repeat Guests**
* **Guests with Most Children & Babies**

### 3️⃣ Booking & Stay Patterns

* **Average Nights per Stay**
* **Average Total Cost per Stay**
* **Guests with Exactly 5 Special Requests**
* **Most Frequent Phone Number Area Codes (Top 3)**
* **Number of Hotel Arrivals in First Half of the Month**
* **Number of Hotel Arrivals by Day of the Week**

### 4️⃣ Revenue Insights

* **Guest Paying Highest ADR**
* **Mean ADR Across All Hotel Stays**

## 🔎 Advanced Analysis

After completing the initial EDA, advanced analysis was performed to uncover deeper insights into booking behavior, cancellations, and revenue trends:

* **Overall Cancellation Rate:** Measured the percentage of bookings canceled across all hotels  
* **Cancellation Rate by Hotel Type:** Compared cancellations between *City Hotel* and *Resort Hotel*  
* **ADR (Average Daily Rate) Effects on Cancellations:** Explored how room pricing impacts cancellation likelihood  
* **Seasonality & Monthly Booking Trends:** Analyzed booking patterns across months to identify peak and off-season periods  
* **Count of Bookings by Market Segment:** Determined which customer segments contribute most to total bookings  
* **Revenue Generated per Segment:** Calculated total revenue by market segment to identify the most valuable customers

---

## 📁 Project Structure

```
Hotel-Data-Analysis/
│
├── hotel_analysis.ipynb      # Jupyter Notebook with all analysis
├── hotel_data.csv            # Hotel booking dataset
├── README.md                 # Project overview and insights
└── requirements.txt          # Optional: list of Python libraries used
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone <your-repo-link>
```

2. Open the folder in Jupyter Notebook
3. Run `hotel_analysis.ipynb` step by step
4. Ensure you have the required Python libraries installed (`pandas`, `numpy`, `datetime`)

---

## 🙏 Acknowledgements

* Dataset: *Hotel Booking Demand Datasets* by Nuno Antonio, Ana Almeida, and Luis Nunes (Data in Brief, 2019)
* Analysis implemented and interpreted independently
