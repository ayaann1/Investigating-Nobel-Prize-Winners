🏅 Nobel Prize Data Analysis
📌 Project Overview

This project looks at more than a century of Nobel Prize winners to discover interesting patterns in gender, country of birth, and prize categories.
The goal is to answer simple but powerful questions, such as:

Which gender and country have received the most Nobel Prizes?

Which decade had the most U.S. winners?

In which decade and prize category were women most represented?

Who was the first woman to win a Nobel Prize?

Who are the rare people or organizations that have won more than once?

Even if you are not a programmer, the results give an easy-to-read picture of Nobel history.

🗂️ Data Source

File: nobel.csv

Contains details of every Nobel Prize awarded:

Year of award

Category (Physics, Peace, Literature, etc.)

Full name of the winner

Gender

Country of birth

Other details like organizations and motivations

🔑 Key Findings
Question	Result (stored in code)
Most common gender	top_gender
Most common birth country	top_country
Decade with highest ratio of U.S. winners	max_decade_usa
Decade & category with highest share of female winners	max_female_dict
First woman Nobel laureate	Name → first_woman_name / Category → first_woman_category
People/organizations with more than one prize	repeat_list
🧮 What Was Done

Basic Counts – Found the most frequent gender and birth country.

U.S. Winners by Decade – Calculated the percentage of U.S.-born winners in every decade.

Female Representation – Measured the proportion of female laureates for each decade and prize category.

First Female Winner – Identified the earliest woman to win and her category.

Repeat Winners – Listed all individuals/organizations that have received 2 or more prizes.

📊 Visual Insights

Two simple line charts were created:

U.S. Winners Over Time – Shows how America’s share of prizes changed across decades.

Female Winners Over Time – Highlights growth (or lack) of female representation in each category.

⚙️ Tools Used

Python – Main programming language

pandas – Data cleaning and analysis

NumPy – Numerical calculations

Seaborn – Charts and visualizations
