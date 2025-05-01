# Slide 24: Programming & Data Analysis Demo

This demo walks participants through using AI (e.g., ChatGPT-4 or Claude) to assist in code generation, exploratory data analysis (EDA), and interpretation using a real dataset.

---

## Dataset Used

1-year sample of Chicago Police Department incident reports ([public open-data portal](./https://catalog.data.gov/dataset/crimes-one-year-prior-to-present)). 

**Overview:** Crime data with variables like location, date, offence type, and count

**Use Case:** Exploratory analysis + basic modelling (e.g., trendline, regression)

---

## Demo Flow (Live in ChatGPT or Claude with code interpreter enabled)

### Step 1 – Upload Data

"I have uploaded a CSV file containing 1 year of crime reports. Can you help me understand the structure and suggest variables to explore?"

### Step 2 – Generate EDA

"Please load the dataset and give a summary of key statistics. Plot top 10 offences by frequency and a time series of monthly trends."

### Step 3 – Create a Simple Model

"Run a regression to predict total incidents based on day of week, suburb, or offence type. Interpret the output."

### Step 4 – Explain Statistical Results

"Explain the meaning of R², coefficients, and p-values from this model in plain English."

---

## Bonus Prompts

### Error handling:

"Here’s the error I got while running this code – what’s wrong and how do I fix it?"

### Optimization:

"Rewrite this code block to make it more efficient or readable."
