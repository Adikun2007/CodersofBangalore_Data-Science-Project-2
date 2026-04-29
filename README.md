# 🚀 Coders of Bangalore — From Chaos to Intelligence

![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPO?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/YOUR_USERNAME/YOUR_REPO?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/YOUR_USERNAME/YOUR_REPO?style=for-the-badge)
![GitHub license](https://img.shields.io/github/license/YOUR_USERNAME/YOUR_REPO?style=for-the-badge)

![Python](https://img.shields.io/badge/Built%20With-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Data Science](https://img.shields.io/badge/Domain-Data%20Science-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## ⚡ The Challenge

You are given **raw, messy, unstructured Instagram data** —  
missing values, inconsistent formats, noisy text, and zero organization.

No clean dataset. No predefined structure. No shortcuts.

> The task: Extract meaningful insights from chaos within constraints.

---

## 🧠 What This Project Does

This project is a **data transformation and analysis pipeline** that:

- Converts unstructured raw text into structured JSON
- Extracts meaningful user-level attributes
- Cleans inconsistent and incomplete data
- Transforms noise into decision-ready insights

---

## 🔍 Key Questions Answered

- 📈 Who has the **maximum posts**
- 👑 Who has the **highest followers**
- 🔗 Who follows the **most accounts**
- 🧩 What **types of profiles** exist (Digital Creator, Media, Non-Profit, etc.)
- 📊 Total number of users and categories

---

## ⚙️ Pipeline Overview

### 1. Data Parsing
- Split raw text into logical user chunks
- Extracted structured attributes using patterns

### 2. Data Cleaning
- Handled missing and null values
- Removed inconsistencies and duplicates
- Standardized formats across all records

### 3. Data Structuring
- Converted cleaned data into JSON format
- Ensured readability and scalability

### 4. Data Analysis
- Iterated through dataset to compute metrics
- Identified extreme values and patterns

---

## 🧪 Sample Outputs

### 🔥 User with Maximum Posts
```python
    {
     'user_name': 'startuphub_blr',
     'no_of_posts': 2300,
     'no_of_followers': 45000,
     'no_of_following': 120,
     'type_of_page': 'Media'
    }
    
### 👑 User with Maximum Follow
    {
     'user_name': '_anujsinghal',
     'no_of_followers': 681000,
     'type_of_page': 'Digital creator'
    }

### 🔗 User Following the Most Accounts
    {
     'user_name': 'katiasales2220',
     'no_of_following': 1401
    }
    
## 📊 Insights Derived
- High follower count does not always correlate with high posting activity
- Media pages dominate in terms of content volume
- Some low-follower accounts exhibit extremely high following counts
- Dataset includes globally diverse categories beyond local creators

## 🛠️ Tech Stack
- Python — Core processing
- JSON — Data structuring
- Data Cleaning Techniques — Handling real-world noise
- Custom Parsing Logic — Transforming unstructured text

##💡 Closing Note
- This project Works on real-world messy data, not pre-cleaned datasets
- Emphasizes data preprocessing, a critical data science skill
- Designed for clarity, scalability, and usability
- Demonstrates full pipeline: raw data → insights

##🎯 Outcome
- A complete system that:
#### Converts unstructured social media data into structured, meaningful insights efficiently and reliably.