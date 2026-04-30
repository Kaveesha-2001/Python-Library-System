# Library Management System 📚

A simple and efficient Python-based Library Management System developed during my learning journey. This project focuses on CRUD (Create, Read, Update, Delete) operations using CSV files for persistent data storage.



## 🌟 Features
*   **Add New Books:** Easily record book titles, authors, genres, and publication years.
*   **Data Persistence:** Uses a CSV file (`library.csv`) to ensure your data is saved even after closing the program.
*   **Search Functionality:** Quickly find any book by searching for titles or other keywords.
*   **Data Visualization/Stats:** Automatically calculates the number of books available per genre.
*   **Author Information:** Includes a separate lookup for author contact details (e.g., retrieving the phone number for the author of "LOTR").

## 🛠️ Technologies Used
*   **Python:** Core programming language.
*   **CSV Module:** For handling data storage.
*   **OS Module:** For file path and existence checks.

## 📊 Project Structure & Logic

### 1. File Initialization
The system initializes a `library.csv` file with predefined headers: `ID`, `Title`, `Author`, `Genre`, `Year`, and `Location`.

### 2. Core Functions
*   `addRecord()`: Captures user input and assigns a unique ID to each book.
*   `displayData()`: Formats and displays all records in a clean, tabular view.
*   `searchData()`: Filters the database based on a user-provided search term.

### 3. Statistics & Analytics
The system includes logic to iterate through the dataset and provide a breakdown of library content, such as:
*   **Authors per Genre:** A summary showing how many books/authors belong to categories like Fantasy or Novels.



## 🚀 How to Run
1. Clone this repository to your local machine or open it in Google Colab.
2. Run the code cells in sequence.
3. Use the interactive menu to manage your library:
    *   `1` - Add a book
    *   `2` - Display books
    *   `3` - Search
    *   `x` - Exit and Save

## 📈 Sample Output
```text
--- Statistics: Authors per Genre ---
fantasy: 1
Fantasy: 2
Novel: 1

--- Fetching Phone for LOTR Author ---
The phone number for Tolkiens is: 09878987
```

---
*Created by Kaveesha Athapaththu as a learning project*
