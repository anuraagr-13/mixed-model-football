# mixed-model-football
Predicting International team Quality in Football using Mixed-Effect models

The advent of Sports Analytics in recent times has led to an increase in data-based evaluation for deciding strategies across various sports and tournaments. This project is to focus on International tournaments in Football (soccer), and how various factors like offensive and defensive metrics, quality of opposition, and home or away team advantage affect the quality of various teams across their history.

There are two major R markdown files:

1. Project Modelling (Stats501_ProjectModelling.Rmd)
2. Project Plots (Project_Plots.Rmd)

The steps to run the project:

1. Run all the lines in the Project Modelling(Stats501_ProjectModelling.Rmd).
    - The mixed effects model takes 14 hours to run. 
    - The coefficients for the mixed model are provided in quality_team.csv (Quality), quality_teamyear.csv (Yearly Quality).
    - The bayesian mixed model takes 22 hours to run. The bayesian_model.RDS can be imported to run the analysis further. This will generate the final points table
      for World Cup 2022. 
    - The coefficients for the bayesian mixed model are provided in quality_team_b.csv (Quality), quality_teamyear_b.csv (Yearly Quality).
2. These coefficient files can be generated. Then, the code in Project Plots(Project_Plots.Rmd) can be run to generate the EDA and the interferential plots.

Data is provided as results.csv, goalscorer.csv and shootouts.csv

Finally, we get World Cup 2022 group table prediction, based on the results from the bayesian mixed effect models.