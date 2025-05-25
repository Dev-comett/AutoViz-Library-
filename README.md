# AutoViz-Library 📊

This project demonstrates how to use the [AutoViz](https://github.com/AutoViML/AutoViz) library for automated exploratory data analysis (EDA) and beautiful plots with minimal code.

## 🚀 What is AutoViz?

[AutoViz](https://github.com/AutoViML/AutoViz) automatically visualizes any dataset (CSV, Excel, etc.) with just a single line of code. It helps in quick data profiling, trend detection, and insight generation — ideal for data science and machine learning workflows.

## 📁 Project Structure

AutoViz-Library-/
├── AutoViz_Example.ipynb # Jupyter Notebook showing AutoViz in action
├── sample_data.csv # Sample dataset (optional)


csharp
Copy code

## ⚙️ Installation

Install AutoViz using pip:


pip install autoviz
Make sure setuptools is installed:


pip install setuptools
Or in a Jupyter Notebook cell:


!pip install autoviz
📊 How to Use
In your Jupyter Notebook:


from autoviz.AutoViz_Class import AutoViz_Class

AV = AutoViz_Class()

df = AV.AutoViz("your_dataset.csv")
That's it — AutoViz will generate a series of plots and summary stats for you!

🔍 Example Output
You’ll get visualizations like:

Histograms

Scatter plots

Correlation heatmaps

Word clouds (for NLP datasets)

Time series plots

Feature distributions by target class



🪪 License
This project is for educational/demo purposes.












