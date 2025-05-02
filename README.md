# Dsc-Phase-2-project-2025
# Final Project: Movie Performance Analysis

## Overview

This repository contains the exploratory data analysis (EDA) project on the movie industry to generate actionable insights for a company launching a new movie studio. The goal is to uncover patterns and factors that contribute to box office success by examining various datasets related to film performance, including genres, budgets, runtimes, and release timing.

---

## Business Understanding

The company plans to launch a new movie production studio but currently lacks experience in the film industry. To make data-driven decisions, leadership wants to understand:

- Which genres are the most profitable?  
- What months or seasons yield the best box office performance?
- Do directors significantly influence success?
- How does the production studio affect financial and critical outcomes?
- What trends in audience preferences or industry performance should be considered?

These insights will guide investment strategies and help ensure a profitable market entry.


## Data Understanding and Analysis

### Source of Data

The project draws from multiple sources:
- IMDb  
- Box Office Mojo  
- Rotten Tomatoes  
- TheMovieDB  
- The Numbers  

The datasets include structured (CSV, TSV) and relational (SQLite) formats, covering movie details, reviews, box office performance, and studio data.

### Description of Data

Key datasets:
- Rotten Tomatoes: Movie ratings and reviews.
- Box Office Mojo: Revenue and earnings.
- TheMovieDB: Metadata such as cast, crew, and production details.
- The Numbers: Financial performance, budgets, and profits.

These datasets were cleaned, merged, and prepared for exploratory analysis.

### Visualizations

Three visualizations presented in this project:

1. **relationship between studios and Box Office performance**  
   !['Top 10 Studios by Average Box Office Earnings'](Images/img1.png)

2. **Find top 5 studios by number of movies**  
   !['Box Office Earnings by Top 5 Studios'](Images/img2.png)

3. **Top Directors vs Box Office Performance**  
   !['Box Office Revenue: Top Directors vs Others'](Images/img3.png)

4. **Top Directors by Average Movie Rating**  
   !['Top Directors by Average Movie Rating'](Images/img4.png)

5. **Genre vs Box Office Performance**  
   !['Box Office Revenue by Genre'](Images/img5.png)



## Conclusion

### Summary of findings

Based on the EDA, we identified three key findings:

- **Director Impact (T-Test Results):**  
  Statistical tests comparing films by top directors versus others showed a highly significant difference in average box office earnings (T-statistic ≈ 26.10, p-value ≈ 0.0000), indicating that well-known or acclaimed directors reliably boost audience draw and revenue.

- **Studio-Level Revenue Analysis:**  
  Among the top five studios, Universal Pictures and Sony Pictures consistently produced the highest-revenue films, outperforming competitors on average. This suggests that their production choices, marketing strategies, and resource allocations serve as strong models for success.

- **Genre Profitability Patterns:**  
  Median and upper-quartile box office earnings were highest in the Animation and Action/Adventure categories, with Animation films showing consistently strong returns and fewer underperformers. These genres demonstrate robust audience demand and profitability.

These findings provide actionable recommendations for the company’s launch strategy: Invest in Top Directors to Boost Revenue Potential,  Model After High-Performing Studios and Prioritize   Animation and Action/Adventure Films 
