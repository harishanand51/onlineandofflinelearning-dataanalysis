### Online and Offline Learning Impacts on Student's Grades

## Overview

This project analyzes the impact of digital tool usage on students' academic performance, psychological well-being, and social interaction before and after the COVID-19 pandemic. The study leverages two datasets, one focusing on academic scores (reading, writing, math) and the other exploring digital tool usage, time spent on tools, and survey responses. The analysis incorporates statistical methods, data visualizations, and Large Language Model (LLM)-based insights to uncover trends and draw meaningful conclusions.

## Features

- **Data Analysis**:
  - Comparison of academic performance metrics (reading, writing, math scores) across gender and time periods.
  - Exploration of digital tool usage trends before and after COVID-19.
  - Analysis of survey responses on psychological and social impacts.

- **Data Visualization**:
  - Box plots to depict score distributions across gender and time periods.
  - Bar plots to visualize digital tool usage, time spent, and survey responses.

- **LLM Integration**:
  - Question-based analysis using OpenAI's GPT model to extract insights from the datasets.
  - Evaluation of LLM performance and accuracy across different types of queries.

## Methodology

1. **Data Preparation**:
   - Loading datasets and structuring them for analysis.
   - Grouping data by gender, time period, and other key attributes for comparative analysis.

2. **Data Analysis**:
   - Calculation of summary statistics (mean, median, standard deviation) for academic scores.
   - Grouped analysis of digital tool usage and survey responses.

3. **Data Visualization**:
   - Box plots for academic scores.
   - Bar plots for digital tool usage, time spent, and survey results.

4. **LLM-Based Insights**:
   - Structured prompts to query datasets using OpenAI's GPT models.
   - Analysis of LLM performance for different types of queries (averages, counts, opinions, trends).

## Results

- **Key Findings**:
  - Female students showed more consistent academic performance across all time periods.
  - Increased reliance on mobile phones and laptops after COVID-19, especially among female students.
  - Psychological and social impacts, such as isolation and screen fatigue, were more pronounced among female students.

- **LLM Evaluation**:
  - LLMs provided meaningful and accurate results for questions involving averages, summaries, and trends.
  - Accuracy decreased for queries requiring exact counts, though consistency improved with repeated queries.
  - Overall accuracy was rated at 70%.

## Tools and Libraries

- **Python Libraries**:
  - `pandas`: Data manipulation and analysis.
  - `matplotlib` & `seaborn`: Data visualization.
  - `sentence-transformers`: Text embedding for LLM queries.
  - `openai`: Integration with GPT models.

- **Dataset Sources**:
  - Academic performance metrics and digital tool usage surveys.