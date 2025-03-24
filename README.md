# 📊 Dashboard-for-Insurance-Policy-Data-Using-PowerBI

## Overview
This project presents an interactive **Power BI Dashboard** that visualizes insurance claim data. It allows users to analyze claim amounts, premium distributions, claim statuses, and active/inactive policies dynamically.

## 🔥 Features
- **Dynamic Filtering**: Users can filter data by Policy Number, Claim Number, and Customer ID.
- **Drill-Through Capabilities**: Navigate between detailed and summary views.
- **Responsive Design**: Works well on different screen sizes.
- **Interactive Visuals**: Charts for claims distribution, premium amounts, and claim statuses.
- **Multiple Data Sources**: The data is stored in SQL and CSV formats.

## 📁 Project Structure
```sh
  /Insurance-Dashboard
  ├── data/
  │   ├── insurance_data.csv  # Raw data in CSV format
  │   ├── sql_schema.sql      # SQL script for creating tables
  ├── dashboard/
  │   ├── insurance_dashboard.pbix  # Power BI file
  │   ├── screenshots/   # Store dashboard images here
  ├── README.md  # Main project documentation
  ├── LICENSE  # Open-source license file
```
```
bash
Copy
Edit
```
## 🛠 Installation
1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/Insurance-Dashboard.git
   cd Insurance-Dashboard
Load the Data into SQL

Open sql_schema.sql in any SQL database (e.g., MySQL, PostgreSQL) and execute the script.

Alternatively, use insurance_data.csv to manually import the data.

Open in Power BI

Open the insurance_dashboard.pbix file in Microsoft Power BI.

Connect to your SQL database or use the CSV file as a data source.

Refresh the dashboard to see updated insights.

🎥 Screenshots
📌 Dashboard Overview

📌 Filter by Policy Number

🚀 Usage
Open Power BI and load the .pbix file.

Use slicers (Policy Number, Customer ID) to filter results.

Hover over visualizations for additional insights.

🤝 Contributing
We welcome contributions! Please follow these steps:

    Fork the repo

    Create a new branch (feature-new-chart)

    Commit changes (git commit -m "Added new feature")

    Push to GitHub (git push origin feature-new-chart)

    Submit a Pull Request (PR)

📜 License
This project is licensed under the MIT License.
