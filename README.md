# 📚 Gravity Books Database Analysis (CIS525 Project)

This project was developed as part of my MBA in Business Analytics (CIS525 – Applied Data Structure and Databases). It focuses on analyzing the **Gravity Books** database using **MySQL**, a widely-used open-source relational database management system. But addicional work will be done on it, for a complementary development skill.

The analysis began with the construction of an **Entity Relationship Diagram (ERD)** to map out the structure of the database—highlighting primary keys, foreign keys, relationships between tables, and essential data types.

## 🎯 Business Goals

This project answers **four key business questions** posed by Gravity Books’ upper management:

1. **Which publisher** should be selected for a special promotion?
2. **Which country** has the highest number of active customers?
3. What are the **five least popular books** among customers?
4. Which **shipping method** is the least efficient and may be discontinued?

Additional insights were also explored, based on trends and hidden patterns in customer behavior, product sales, and fulfillment operations.

## 🔧 Tools & Skills Used
- **MySQL** – SQL queries, joins, aggregations, filtering
- **Database Modeling** – ERD creation and interpretation
- **Business Intelligence** – Data storytelling and decision-making
- **Data Cleaning & Analysis** – Structured problem-solving

## 📊 Project Structure

```bash
gravity-books-analysis/
│
├── README.md                  # Project summary and documentation
├── ERD.png                    # Entity Relationship Diagram
├── SQL_queries/               # All .sql files for the analysis
│   ├── top_publisher.sql
│   ├── country_customers.sql
│   ├── least_popular_books.sql
│   └── inefficient_shipping.sql
├── Visualizations/            # Images of the results from the queries
├── summary_report.pdf         # Final report submitted 
└── insights.md                # Extra business observations and commentary
