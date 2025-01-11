# **Transaction Manager: Household Expense Manager**

💰 **Project Objective:**

In an era where personal and household expense management is pivotal for sustainable financial planning, a simple yet effective application can provide immense value to users. This project, **Transaction Manager**, is designed to offer a clear and functional user interface for monitoring daily economic transactions while empowering users with insightful financial analytics.

---

## **Project Description**

The **Transaction Manager** is a Python-based application developed to address the needs of individuals and families striving to maintain financial sustainability. With an intuitive interface and robust functionality, this application enables users to:

- **Track daily expenses:** Users can record their transactions by specifying the date, description, and amount. These details are stored persistently in a CSV file.
- **Generate insightful monthly reports:** The application aggregates transactions by year and month, offering a transparent overview of financial activities during specific periods.
- **Identify major expenses:** By highlighting the top 10 transactions with the highest amounts, users can quickly identify key areas of spending, paving the way for more informed budgeting decisions.

This solution is lightweight, flexible, and tailored to provide real-time tracking, comprehensive reporting, and the ability to spot high-impact financial transactions effortlessly.

---

## **Key Features**

### 📝 **Add a Transaction**
Users can easily register new transactions, specifying:
- **Date**: Transactions are validated and stored in the format `DD/MM/YYYY`.
- **Description**: A concise note describing the transaction.
- **Amount**: The monetary value of the transaction.

All data is appended to a CSV file, ensuring seamless and persistent storage.

---

### 📊 **Monthly Report**
Generates a summary of all transactions grouped by year and month. The format provides:
- **Aggregated totals** for each month, helping users track cash flow trends.
- A **clear overview** of expenses over time, aiding long-term financial planning.

---

### 💵 **Top 10 Transactions**
Displays the 10 highest transactions sorted by amount, including:
- **Date**: When the transaction occurred.
- **Description**: Details about the transaction.
- **Amount**: The monetary value.

This feature helps users pinpoint high-value expenses, enabling smarter decision-making.

---

## **Value Proposition**

The **Transaction Manager** offers multiple advantages to users:

1. **Immediate Expense Monitoring**:
   - Real-time tracking of daily expenses stored in an easily accessible CSV file.
   
2. **Informed Financial Planning**:
   - Monthly reports provide a transparent and detailed view of where and how money is spent.

3. **Identifying Significant Expenses**:
   - The "Top 10 Transactions" feature helps users focus on major spending categories, supporting better budgeting and financial control.

---

## **Technical Implementation**

- **Core Technology**: The application is built entirely in Python, leveraging its robust libraries for efficient data management and processing.
- **Data Management**: Transactions are stored in CSV format, ensuring simplicity, compatibility, and ease of use.
- **Interactive Menu**: A dynamic command-line interface guides users through various operations, making it highly user-friendly.

---

## **Best Practices**

This project adheres to the following best practices in software development:
1. **Modular Design**:
   - The application is designed with clearly separated components (`TransactionManager` and `TransactionManagerUI`) to ensure maintainability and scalability.
   
2. **Input Validation**:
   - All user inputs are validated to prevent errors and ensure data integrity.

3. **Logging**:
   - Comprehensive logging tracks user actions and errors, aiding debugging and operational monitoring.

4. **Type Hints**:
   - Type annotations improve code clarity and facilitate static analysis.

5. **CSV Handling**:
   - The use of `csv.DictReader` ensures structured and robust data handling.

6. **Dynamic Menu**:
   - A flexible menu system allows users to navigate the application effortlessly, while cycling until valid input is provided.

---

## **Future Enhancements**

This project sets the stage for further improvements and scalability. Planned enhancements include:

1. **Database Integration**:
   - Transition from CSV storage to a relational database for more robust data handling.
   
2. **Graphical User Interface (GUI)**:
   - Develop a GUI to enhance user experience beyond the command line.

3. **Advanced Reporting**:
   - Introduce categorization of transactions and budget forecasting.

4. **API Integration**:
   - Enable third-party applications to interact with the system via RESTful APIs.

---

## **Explore More**

📂 Dive into the project codebase on GitHub to explore how Python's advanced features, modular design, and robust logging practices have been used to build a practical and effective household expense manager.<br>
View my code on ipynb files! Happy coding! ✨

---

**Author:**
- Name: [Eugenio Pasqua]
- Email: [eugenix86@gmail.com]
