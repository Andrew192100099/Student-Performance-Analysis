					# Student Performance Prediction Project #
					==========================================

![Education Analytics](https://img.shields.io/badge/domain-education%20analytics-blue) 
![Python](https://img.shields.io/badge/python-3.8%2B-blue)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📌 Overview
Predictive analysis of student academic performance using machine learning. This project analyzes factors influencing grades in Mathematics and Portuguese language courses.

## 📂 Dataset
**Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/320/student+performance)

##🎗️ Dataset Characteristics
- Students: 395 (Math), 649 (Portuguese)
- Features: 33 attributes
- Target: Final grade (G3)

##🎭 Key Attributes
| Feature        | Description                          | Type/Values                       |
|----------------|--------------------------------------|-----------------------------------|
| `school`       | Student's school                     | GP, MS                            |
| `G1-G3`        | Period grades (0-20)                 | Numeric                           |
| `studytime`    | Weekly study hours                   | 1(<2h), 2(2-5h), 3(5-10h), 4(>10h)|
| `failures`     | Past class failures                  | Numeric (0-4)                     |
| `internet`     | Home internet access                 | Binary (yes/no)                   |
| `Dalc/Walc`    | Alcohol consumption                  | 1-5 scale                         |

**Full attribute details**: [See complete list](#-attribute-details)

## 🛠️ Installation
```bash
# Clone repository
git clone https://github.com/yourusername/student-performance-prediction.git

# Install requirements
pip install -r requirements.txt