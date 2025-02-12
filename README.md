# LLM-Driven Expense Categorisation & Financial Insights

## Project Overview
### This project uses LLM (Large Language Model) to categorise expenses, assess financial health, and provide personalised financial recommendations. It integrates data analysis, visualisation, and AI-powered decision-making to help users understand their spending habits and make informed financial decisions.

## Project Workflow
### 1. Load & Preprocess Data
- Standardise descriptions by removing extra spaces and converting them to uppercase.
- Ensure data integrity by handling duplicates.

### 2. AI-Powered Expense Categorisation
- Use **OpenAI's GPT** to categorise expenses into **Groceries, Dining, Subscriptions, Rent, Shopping, Transport, and Miscellaneous**.
- Implement a fail-safe mechanism to classify unrecognised entries as Miscellaneous.

### 3. Data Cleaning & Manual Corrections
- Apply a **correction dictionary** to adjust misclassified transactions.

### 4. Visualise Expense Distribution and Trends Over Time
- Generate a **pie chart** to analyse expense distribution across categories and generate a **line chart** to display expense trends over time.

### 5. Financial Assessment Using LLM
- Compute key financial metrics(Total expenses, Average monthly expenses, Expense distribution ) Analyse **expense-to-salary ratio** and detect **potential cost-cutting opportunities**.

### 6. Savings & Retirement Planning
compute monthly savings and estimate:
  - **Time required to save £49,000**.
  - **Projected retirement age based on current savings trends**.
  - **Alternative investment strategies for early retirement**.

### 7. Personalised Financial Advice & Product Recommendations
- **Ask key financial questions** to classify the user's financial personality:(Long-Term Planner, Short-Term Spender, Risk-Taker,Conservative Investor,Mixed-Type)
- Explain the **classification logic**.
- Generate **customised financial product recommendations** tailored to spending patterns, goals, and risk tolerance.


## Visualisations
![image](https://github.com/user-attachments/assets/9dfc2a2d-c0f4-47db-ab06-85eb36ce3997)


![image](https://github.com/user-attachments/assets/9b99360d-0c5a-4e85-a7a7-5aa34aaf8bbd)

