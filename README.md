# Customer Support Ticket Analyzer Using Python

## 📌 Project Overview

The **Customer Support Ticket Analyzer** is a Python-based project that stores, cleans, analyzes, and extracts insights from customer support tickets.

The project uses customer names, issue descriptions, ticket numbers, and priority levels to perform basic text and ticket analysis.

## 🎯 Objectives

* Store customer support ticket data using Python dictionaries and lists.
* Add new tickets dynamically through user input.
* Automatically generate ticket numbers.
* Validate ticket priorities.
* Clean issue descriptions using string operations.
* Analyze frequently used keywords.
* Analyze ticket priority distribution.
* Find the ticket with the longest issue description.
* Extract unique words from all issue descriptions.

## 🛠️ Technologies Used

* **Google Colab**

## 📚 Python Concepts Used

* Lists
* Dictionaries
* Sets
* `for` loops
* `while` loops
* `if`, `elif`, `else`
* Functions
* `append()`
* `split()`
* `join()`
* `replace()`
* `strip()`
* `lower()`
* `capitalize()`
* Sorting

## 📂 Project Tasks

### Task 1: Preloaded Tickets

The project starts with **10 predefined customer support tickets** containing:

* Ticket Number
* Customer Name
* Issue Description
* Priority

### Task 2: Add More Tickets

Users can add new support tickets by entering:

* Customer Name
* Issue Description
* Priority

Ticket numbers are automatically assigned starting from **11**.

The priority is validated to accept only:

* High
* Medium
* Low

### Task 3: Text Cleaning

Issue descriptions are cleaned using the following operations:

* Convert text to lowercase.
* Remove punctuation such as `. , ! ? -`
* Convert multiple spaces into a single space.
* Remove leading and trailing spaces.
* Replace shorthand such as `ok` with `okay`.

### Task 4: Keyword-Based Issue Analysis

A function named `count_tickets_with_word(word)` is used to count the number of tickets containing a specific word.

The project analyzes these keywords:

* **poor**
* **good**
* **slow**
* **excellent**

### Task 5: Final Summary & Insights

The final analysis includes:

#### 1. Final Cleaned Ticket Data

Displays the cleaned ticket information in a readable format.

#### 2. Priority Analysis

Calculates the number of:

* High-priority tickets
* Medium-priority tickets
* Low-priority tickets

#### 3. Longest Issue Description

Identifies the ticket with the longest issue description based on word count.

The output includes:

* Ticket number
* Customer name
* Cleaned issue description
* Word count

#### 4. Unique Word Analysis

Extracts all unique words from the issue descriptions and displays:

* Total number of unique words
* Sorted list of unique words

## 🔄 Project Workflow

```text
Load Initial Ticket Data
        ↓
Add New Tickets
        ↓
Validate Priority
        ↓
Clean Issue Descriptions
        ↓
Keyword Analysis
        ↓
Priority Analysis
        ↓
Find Longest Description
        ↓
Extract Unique Words
        ↓
Final Insights
```

## 📊 Key Analysis Areas

The project focuses on:

| Analysis            | Purpose                                    |
| ------------------- | ------------------------------------------ |
| Ticket Management   | Store and add customer tickets             |
| Text Cleaning       | Standardize issue descriptions             |
| Keyword Analysis    | Identify tickets containing specific words |
| Priority Analysis   | Understand ticket priority distribution    |
| Longest Description | Find the most detailed issue               |
| Unique Words        | Identify vocabulary used across tickets    |

## 💡 Learning Outcomes

Through this project, I practiced:

* Working with Python lists and dictionaries.
* Adding and modifying data.
* Using loops and conditional statements.
* Creating and using functions.
* Performing string manipulation.
* Working with sets.
* Performing basic text analysis.
* Extracting meaningful information from structured data.

## ▶️ How to Run

1. Open the Google Colab or Jupyter Notebook.
2. Run the cells in the order of the assignment tasks.
3. Enter the requested information when prompted.
4. Review the generated analysis and insights.

## 📁 Project Files

```text
Customer-Support-Ticket-Analyzer/
│
├── Customer_Support_Ticket_Analyzer.ipynb
├── README.md
└── Project_Documentation.docx
```

## 🔗 Google Colab

**Colab Notebook:**
https://colab.research.google.com/drive/1Wjcj0bTbiLpuDeTc2MKcqp0dqxdDbdTo?usp=sharing

## 👩‍💻 Author

**Sabana Asmi R**

Aspiring Data Analyst | Python | SQL | Power BI | Excel

## 🏷️ Tags

#Python #PythonProgramming #DataAnalysis #CustomerSupport #TextAnalysis #DataAnalytics #GoogleColab #GitHub
