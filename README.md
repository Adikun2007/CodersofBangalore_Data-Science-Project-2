# 🚀 Coders of Bangalore — From Chaos to Intelligence

![Stars](https://img.shields.io/github/stars/Adikun2007/CodersofBangalore_Data-Science-Project-2?style=for-the-badge&label=Stars)
![Forks](https://img.shields.io/github/forks/Adikun2007/CodersofBangalore_Data-Science-Project-2?style=for-the-badge&label=Forks)
![Issues](https://img.shields.io/github/issues/Adikun2007/CodersofBangalore_Data-Science-Project-2?style=for-the-badge&label=Issues)
![License](https://img.shields.io/github/license/Adikun2007/CodersofBangalore_Data-Science-Project-2?style=for-the-badge&label=License)

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
    {'user_name': 'startuphub_blr', 'no_of_posts': 2300, 'no_of_followers': 45000, 
     'no_of_following': 120, 'real_name': 'Startup Hub Bangalore', 
     'type_of_page': 'Media', 
     'user_bio': '🦄 News from the Silicon Valley of India\n
     📢 Funding alerts, Hiring trends, and Drama\n
     📩 DM for features\nstartuphub.blr/newsletter'
    }
```

### 👑 User with Maximum Follow
```python
    {
     'user_name': '_anujsinghal',
     'no_of_posts': 1785,
     'no_of_followers': 681000,
     'no_of_following': 248,
     'real_name': 'Anuj Singhal',
     'type_of_page': 'Digital creator',
     'user_bio': 'Managing Editor, CNBC-Awaaz. Most trusted and followed biz anchor in India\nLet’s talk about finance and life\nContact: Singhalanuj1010@gmail.com\nhindi.cnbctv18.com/market-gurukul'
    }
```

### 🔗 User Following the Most Accounts
```python
    {
     'user_name': 'bangalore_tech_bro',
     'no_of_posts': 402,
     'no_of_followers': 12500,
     'no_of_following': 890,
     'real_name': 'Rahul | HSR Hustler',
     'type_of_page': 'Entrepreneur',
     'user_bio': '🚀 Building the next Unicorn in Fintech\n☕ 3rd Wave Coffee addict\n💻 Python | React | AI\n📍 HSR Layout, BLR\nlinktr.ee/rahulbuilds'
    }
```
### 🔥How many categories (Digital creators, etc do we have?)
```python
    {
    'No of people we have: 34'
    }
```

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

## 💡 Closing Note
- This project Works on real-world messy data, not pre-cleaned datasets
- Emphasizes data preprocessing, a critical data science skill
- Designed for clarity, scalability, and usability
- Demonstrates full pipeline: raw data → insights

## 🎯 Outcome
- A complete system that
--- Converts unstructured social media data into structured, meaningful insights efficiently and reliably.

## ⚠️ Setup Instructions
- Clone the repository
- Replace dataset with your raw input
- Run the parsing and cleaning scripts
- Execute analysis modules