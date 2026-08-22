<div align="center"> 
  
# 📊 Demographic Data Analyzer

### Analyzing US Census demographic data using Pandas.

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![freeCodeCamp](https://img.shields.io/badge/freeCodeCamp-Data%20Analysis-0a0a23?style=for-the-badge&logo=freecodecamp&logoColor=white)](https://www.freecodecamp.org/learn/data-analysis-with-python/)
[![License MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

[![GitHub stars](https://img.shields.io/github/stars/HereIsMuhammad/demographic-data-analyzer?style=for-the-badge&color=yellow)](https://github.com/HereIsMuhammad/demographic-data-analyzer/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/HereIsMuhammad/demographic-data-analyzer?style=for-the-badge&color=blue)](https://github.com/HereIsMuhammad/demographic-data-analyzer/network/members)
[![GitHub watchers](https://img.shields.io/github/watchers/HereIsMuhammad/demographic-data-analyzer?style=for-the-badge&color=teal)](https://github.com/HereIsMuhammad/demographic-data-analyzer/watchers)
[![Last Commit](https://img.shields.io/github/last-commit/HereIsMuhammad/demographic-data-analyzer?style=for-the-badge&color=orange)](https://github.com/HereIsMuhammad/demographic-data-analyzer/commits)

</div>

## 📖 Introduction

This project analyzes demographic data extracted from the **1994 US Census database**, using **Pandas** to answer several questions about the population. It's part of freeCodeCamp's Data Analysis with Python curriculum.

The dataset (`adult.data.csv`) includes details like age, education, occupation, race, sex, hours worked per week, native country, and salary for each individual.

## 🗂️ Project Structure

| File | Description |
|---|---|
| `adult.data.csv` | Raw 1994 US Census demographic dataset |
| `demographic_data_analyzer.py` | Contains the `calculate_demographic_data()` function with all the analysis logic |
| `main.py` | Entry point used to run and test `calculate_demographic_data()` |

## 🔍 What It Answers

Using the dataset, the `calculate_demographic_data()` function calculates:

1. How many people of each race are represented
2. The average age of men
3. The percentage of people with a Bachelor's degree
4. The percentage of people with and without advanced education (Bachelors, Masters, or Doctorate) who earn more than 50K
5. The percentage of people without advanced education who earn more than 50K
6. The minimum number of hours a person works per week
7. The percentage of people who work the minimum number of hours per week and earn more than 50K
8. The country with the highest percentage of people earning more than 50K, and that percentage
9. The most popular occupation for those who earn more than 50K in India

## 🧰 Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

</div>

## 🚀 How to Run

Clone the repo, install the dependencies, and run the script:

```bash
git clone https://github.com/HereIsMuhammad/demographic-data-analyzer.git
cd demographic-data-analyzer
pip install pandas
python main.py
```

This will run `calculate_demographic_data()` on `adult.data.csv` and print all the calculated statistics to the console.

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request, whether it's adding new insights, improving performance, or cleaning up the code.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

<div align="center">

### ⭐ If this repo helped you, consider giving it a star!

</div>
