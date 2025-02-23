# 🧹 Data Sweeper

## 📌 Overview

**Data Sweeper** is a Streamlit-based web application that allows users to upload **CSV** and **Excel** files, perform basic data cleaning, visualize the data, and convert files between **CSV** and **Excel** formats.

## 🚀 Features

- 📂 Upload multiple **CSV** or **Excel** files.
- 👀 Preview the uploaded data.
- 🛠️ Perform data cleaning:
  - ✂️ Remove duplicate entries.
  - 🔄 Fill missing values with column mean.
- 🎯 Select specific columns for processing.
- 📊 Visualize numerical data using bar charts.
- 🔀 Convert and download processed files as **CSV** or **Excel**.

## 🛠️ Installation

Ensure you have **Python** installed. Then, install the required dependencies using:

```bash
pip install pandas streamlit
```

## ▶️ How to Run

Run the Streamlit app using the following command:

```bash
streamlit run app.py
```

## 📂 File Upload Support

The application supports:

- `.csv` (Comma-Separated Values)
- `.xlsx` (Excel Workbook)

## 🔍 Data Cleaning Options

- **Remove Duplicates**: Deletes duplicate rows from the dataset.
- **Fill Missing Values**: Replaces missing values in numeric columns with the column mean.

## 📊 Data Visualization

- 📈 A **bar chart** is generated for the first two numerical columns of the selected dataset.

## 🔀 File Conversion

Convert uploaded files into:

- **CSV** (`.csv`)
- **Excel** (`.xlsx`)

Users can **download** the cleaned and converted files.

## 🛠️ Technologies Used

- **Python** 🐍: For data processing.
- **Pandas** 🏗️: For handling CSV and Excel files.
- **Streamlit** 🎨: For building the interactive web interface.

