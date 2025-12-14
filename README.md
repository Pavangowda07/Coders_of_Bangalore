# 🚀 Coders of Bangalore  
### OpenAI Instagram Followers – Raw Data Analytics Challenge

---

## 📖 Project Overview

Coders of Bangalore is a real-world Python data analytics project built around a high-pressure **24-hour challenge** inspired by a fictional interaction with Sam Altman in Bangalore. Instead of being given clean data or APIs, the challenge required collecting and analyzing **raw Instagram profile data of OpenAI followers**, mimicking the kind of unstructured, messy data problems commonly faced in industry.

The goal of this project was not just to extract numbers, but to demonstrate **data engineering thinking**, analytical reasoning, and the ability to convert raw text into meaningful insights under strict constraints.

---

## 🎯 Problem Statement

Analyze raw Instagram profile data of OpenAI followers and answer the following questions:

- Who has the **maximum number of posts**?
- Who has the **maximum number of followers**?
- Who follows the **maximum number of people**?
- How many **types of Instagram account categories** exist (Digital Creator, Business, Non-profit, etc)?
- How many users fall under each category?

**Constraints:**
- No official Instagram APIs  
- No pre-cleaned or structured datasets  
- Only raw, real-world profile text  

---

## 📍 Data Collection Story

To execute the data collection process, two contributors were involved:
- **Vijyalaxmi Iyer** from **Hebbal**
- **Sam Chandra** from **HSR Layout**

Since Hebbal and HSR Layout are geographically distant, the planning and coordination meeting was conducted at **Rameshwaram Cafe, Indiranagar**, a central location in Bangalore. This setting reflects a realistic team collaboration scenario where logistics and coordination are part of the problem-solving process.

Raw Instagram profile data was collected in plain text format exactly as observed, without any preprocessing or cleaning at the time of collection.

---

## 📂 Raw Data Characteristics

Each Instagram profile was stored as an unstructured text chunk containing:
- Username
- Number of posts
- Number of followers (including K/M notation)
- Number of accounts followed
- Display name
- Account category (if available)
- Biography text (multi-line)

This raw format intentionally introduced inconsistencies and variability, requiring custom parsing logic.

---

## ⚙️ Data Processing & Parsing

Custom Python functions were written to:
- Split raw text into meaningful fields
- Normalize numerical values (handling K and M suffixes)
- Handle missing or optional fields gracefully
- Convert unstructured text into structured dictionaries
- Store all parsed profiles in a JSON-like structure for analysis

This step represents a critical **data engineering phase**, where raw data is transformed into analysis-ready form.

---

## 📊 Analysis Performed

After structuring the data, analytical operations were performed to:
- Identify the profile with the **highest number of posts**
- Identify the profile with the **highest follower count**
- Identify the profile that follows the **most accounts**
- Extract all unique **account categories**
- Count the number of users in each category

These operations relied on Python loops, comparisons, sets, and dictionary-based analysis.

---

## 🧠 Key Learnings

Through this project, the following practical skills and insights were gained:

- Working with **unstructured real-world data**
- Writing robust string parsing and cleaning logic
- Handling inconsistent numeric representations
- Structuring data using Python dictionaries and JSON
- Applying analytical thinking to derive insights
- Understanding how real data problems differ from textbook datasets
- Appreciating the importance of data preprocessing in analytics pipelines

---

## 🌟 Why This Project Matters

This project reflects the kind of challenges faced by **data analysts, data engineers, and machine learning practitioners** in real organizations, where clean data is rare and problem-solving ability matters more than tools alone. It demonstrates the ability to work under constraints, think analytically, and deliver insights from imperfect data.

---

## 🏁 Final Note

When data was not provided, it was built.  
When APIs were unavailable, logic was written.  
When the problem was messy, s

