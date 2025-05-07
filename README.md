# Agentic Financial Query Resolver

The **Agentic Financial Query Resolver** is a conversational query system designed to interact with financial data. It leverages modern tools like CrewAI, Pandas, and Matplotlib to analyze and visualize financial information seamlessly. System empowers users to upload their financial data and explore it through natural language queries.

---

## Table of Contents
1. [Overview](#overview)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Setup and Run the App](#setup-and-run-the-app)
5. [How to Use](#how-to-use)
6. [Example Queries](#example-queries)
7. [Visualizations](#visualizations)

---

## Overview
The **Agentic Financial Query Resolver** enables users to:
- Upload financial data (CSV format).
- Ask conversational queries like "What is the total income?" or "Show expenses for Q1."
- Generate insightful visualizations such as pie charts, bar graphs, and line charts.

By integrating CrewAI for conversational querying, Pandas for data manipulation, and Matplotlib for visualization, this project simplifies financial analysis.

---

## Requirements
Before setting up the app, ensure you have:
- Python 3.x
- Google Drive (optional for uploading CSV files)
- OPENAI API KEY OR ANY LLM KEY (Can be host free llm on device as well)

---

## Installation
Install the required dependencies using the following command:
!pip install crewAI pandas matplotlib pyngrok


### Required Libraries:
- **CrewAI**: Conversational AI for processing financial queries.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib**: Graph and chart generation.
- **Pyngrok**: Optional tool to expose the app online.

---
## Setup and Run the App

### Step 1: Upload Financial Data
- Upload a CSV file containing your financial data (e.g., income, expenses, transactions).

### Step 2: Install Dependencies
- Run the following command in your terminal or Jupyter Notebook:
- !pip install crewAI pandas matplotlib pyngrok

Alternatively, run all cells sequentially in a Jupyter Notebook.


---

## How to Use

### Interact with Your Financial Data:
1. **Upload Your CSV File:** Add a file containing your financial data.
2. **Ask Queries:** Examples include:
   - "What is the trend in electricity cost per unit produced over the last three years?"
   - "Generate a chart comparing total gross profit percentage change from 2022 to 2025."
3. **Visualize Data:** View insights through graphs and charts.

---

## Example Queries

Here are some sample queries you can try:
- “How does the COGS-to-Revenue ratio change as revenue increases?”
- “What is the inventory turnover ratio trend across the last three years?”

You can customize these queries to suit your specific needs.

---
## Visualizations

The app supports generating various visualizations:
- **Pie Charts:** Income vs expenses breakdown.
- **Bar Graphs:** Monthly expenses or income comparison.
- **Line Charts:** Track trends over time.

These visualizations provide actionable insights into your financial data.

---

