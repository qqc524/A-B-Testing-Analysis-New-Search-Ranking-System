# A/B Testing Analysis: New Search Ranking System

This project focuses on analyzing an A/B test for a new search ranking system at an online travel agency. The main goal was to see if the new system could **increase bookings** (conversion) without making the **booking process slower**.



## Project Overview

The analysis workflow included:

- **Merging session and user data** to get a complete view of user behavior  
- **Creating a conversion metric** to track whether a session resulted in a booking  
- **Checking group balance** using a **Sample Ratio Mismatch (SRM) test**  
- **Calculating effect sizes** to measure the impact of the new ranking system  
- **Running statistical tests**:
  - Z-test for conversion  
  - T-test for time-to-booking  



## Key Results

- The **variant group increased conversion** by about **14%**  
- **Time to book did not increase**, indicating no negative impact on user experience  
- SRM test showed that the experiment groups were **balanced**, ensuring reliable results  



## Conclusion & Recommendation

Based on the analysis:

- The **conversion improvement is statistically significant**  
- The **booking time did not increase**  
- **Effect sizes** show the improvement is meaningful  

**Recommendation:** The new search ranking system can be **apply to all users**, because it increases bookings without slowing down the booking process.




## Tools & Libraries

- Python (pandas, scipy, statsmodels)  
- Statistical tests: Z-test, T-test  
- Effect size calculation and SRM test for experiment validation  
