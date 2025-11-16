# Shark-Tank-India-Season-1-Analysis-The-8th-Shark
The 8th Shark 🦈 | Data analysis of 117 Shark Tank India S1 pitches using Python, pandas, &amp; NumPy. Uncovered the real insights: Aman (28 deals) is the top investor, avg. deal is ₹44L, and 5-shark deals are a fantasy (only 4!).
Project Overview
This project puts data in the investor's seat. I acted as the "8th Shark," analyzing all 117 pitches from Season 1 of Shark Tank India to uncover the real business metrics behind the on-screen drama.

Instead of a checkbook, I used Python, pandas, and NumPy to clean, transform, and analyze the complete dataset. This repository contains the full analysis, from raw CSV to actionable insights, revealing which sharks are all bite and which are all bark.

Key Insights & Features
The analysis went beyond simple averages and aimed to answer the core questions of the show: What does it take to get a deal?

The Apex Predator: The most active investor was Aman Gupta, who made 28 deals, with Peyush Bansal as a close second at 27.

The Price of a Dream: For the 65 companies that secured funding, the average deal (investment + debt) was ₹44 Lakhs.

The 10% Club: To break into the top 10% of successful valuations, a company needed to be valued at over ₹13.9 Crores (1390 Lakhs).

Debt is a Rarity: Despite negotiations, debt-based deals are incredibly rare. Only 8 out of 117 pitches included a debt component.

The "All-Shark" Fantasy: The coveted 5-shark deal is practically a myth, happening only 4 times in the entire season (3.4% of all pitches).

Technical Stack
Python 3.x: The core language for the analysis.

Pandas: Used for data manipulation, cleaning, and transformation.

NumPy: Used for numerical operations and calculations.

Jupyter Notebook: For interactive analysis, visualization, and code execution.

Analysis Workflow
Data Cleaning:

Loaded the raw ShartankIndiaAllPitches.csv file.

Stripped and standardized column names.

Converted the Equity column from string percentages (e.g., "18%") to numeric floats (0.18) for calculation.

Mapped "Y/N" investor columns to binary (1/0) for numerical analysis.

Feature Engineering:

Created a Deal_Status column to easily filter for successful pitches.

Calculated Valuation(lakhs) for each company based on the investment amount and equity given.

Created a Sharks Count column by summing the binary investor columns to see how many sharks invested in each deal.

Engineered a Total Funding(lakhs) column by adding investment and debt.

Exploratory Data Analysis (EDA):

Identified the most active sharks by summing their total investments.

Filtered the data to find deals with the maximum number of sharks.

Analyzed the frequency and details of debt-based deals.

Calculated average and percentile statistics for valuations and funding amounts.
