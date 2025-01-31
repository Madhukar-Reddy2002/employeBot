# Company Database Assistant

## 📌 Overview

The **Company Database Assistant** is a Streamlit-based web application that allows users to query an SQLite database containing employee and department details. Users can retrieve employee details, salary insights, and department-specific information using natural language queries.

---

## 🚀 Features

- **Database Management:**
  - Creates an `Employees` and `Departments` table if not already present.
  - Inserts sample data for demonstration.
- **Query Engine:**
  - Allows users to fetch employee and department data using natural queries.
  - Provides salary-related insights, like total payroll for a department.
- **Interactive UI:**
  - Search bar for custom queries.
  - Predefined quick queries for common insights.
  - Metrics display for key insights.
  - Table viewer for raw database data.

---

## 🛠 Steps to Run the Project Locally

### 1️⃣ Prerequisites

Ensure you have the following installed on your system:

- **Python 3.8+**
- **pip** (Python package manager)

### 2️⃣ Install Dependencies

Clone the repository and navigate into the project folder:

```bash
# Clone this repository
git clone https://github.com/Madhukar-Reddy2002/employeBot
# Install required Python libraries
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit Application

Execute the following command to start the Streamlit server:

```bash
streamlit run app.py
```

### 4️⃣ Interact with the Application

- Open the provided **localhost URL** in your web browser.
- Use the search bar or quick action buttons to query employee and department data.

---

## ⚠️ Known Limitations & Future Improvements

### ❌ Known Limitations

- **Limited Query Understanding**: The assistant currently supports only predefined queries.
- **No Authentication**: Any user can access and modify the database.
- **Static Dataset**: Employee data is predefined and does not support real-time updates.
- **Limited Error Handling**: Incorrect queries might not provide meaningful feedback.

### 💡 Suggested Improvements

✅ **Enhanced NLP Processing**: Improve query interpretation with AI-powered text analysis.
✅ **User Authentication**: Restrict modifications to authorized users.
✅ **Data Visualization**: Add graphs for salary distributions and department analytics.
✅ **Database Enhancements**: Support external databases like PostgreSQL/MySQL.
✅ **Bulk Data Upload**: Enable CSV/Excel imports for managing employees at scale.
✅ **Improved Error Handling**: Provide better messages for invalid queries.

---

## 📞 Support

For any issues, feel free to raise an issue in the GitHub repository or contact the project maintainer.

💡 **Happy Coding!** 🚀