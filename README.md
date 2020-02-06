# Matplotlib-Challenge

In this study, 250 mice were treated through a variety of drug regimes over the course of 45 days. Their physiological responses were then monitored over the course of that time. The objective is to analyze the data to show how four treatments (Capomulin, Infubinol, Ketapril, and Placebo) compare. This repository contains an analysis of the effectiveness of 3 drugs (Capomulin, Infubinol and Ketapril) for cancer and a Placebo control group.

The following was done using Matplotlib, Pandas and Python:
  - A scatter plot that shows how the tumor volume changes over time for each treatment.
  - A scatter plot that shows how the number of metastatic (cancer spreading) sites changes over time for each treatment.
  - A scatter plot that shows the number of mice still alive through the course of treatment (Survival Rate)
  - A bar graph that compares the total % tumor volume change for each drug across the full 45 days.

Three observations about the results of the study:

  1. Capomulin is the best drug overall.
    - This was the most effective drug to decrease the tumor volume over time and to control the metastatic spread over time. 
    - The mice also had the highest chance of survival on this drug.
  
  2. Ketapril helps rather than hinders tumor growth more than the Placebo control group, and should not be used for the treatment of cancer. 
    - The summary bar graph shows that all drugs except Capomulin had a positive average change.
      - positive change implies that the tumor has grown over time.
    - The tumors treated with Infubinol and Ketapril grew 46% and 57% respectively.
    - The tumors treated with Ketapril grew more than the tumors on the Placebo control group (51%).
    
  3. Infubinol is the most risky drug when it comes to survival rates.
    - The Survival During Treatment shows that only 36% of mice survived on Infubinol over 45 days. 
      - This is much lower than Capomulin (84% survival rate), and moderately lower than Ketapril and Placebo (both with a 44% survival rate).
 
