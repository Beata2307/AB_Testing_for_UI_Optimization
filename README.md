# A/B Testing for User Interface Optimization

### Overview

This project evaluates the impact of a redesigned User Interface (UI) on the online process for clients at Vanguard, a US-based investment management company. The objective is to determine whether a more user-friendly and modern UI can enhance the overall user experience and encourage more clients to complete the process.

### A/B Test Details
**Duration:** from 15/03/2017 to 20/06/2017 (4 months)

- **Control Group:** Clients interacted with Vanguard’s traditional online process.

- **Test Group:** Clients experienced the new, spruced-up digital interface.

Both groups navigated through an identical process sequence: an initial page, three subsequent steps, and finally, a confirmation page signaling process completion.

### Initial Data Sets
To perform analysis, [three datasets](https://github.com/data-bootcamp-v4/lessons/tree/main/5_6_eda_inf_stats_tableau/project/files_for_project) are provided:
1. **Client Profiles (df_final_demo)**: Demographics like age, gender, and account details of our clients.
2. **Digital Footprints (df_final_web_data)**: A detailed trace of client interactions online, divided into two parts: pt_1 and pt_2. 
3. **Experiment Roster (df_final_experiment_clients)**: A list revealing which clients were part of test and contro groups.

## Tasks Performed
1. **Exploratory Data Analysis (EDA) & Data Cleaning**:  Explored and cleaned the dataset to prepare it for analysis.
2. **Client behavior analysis**: Examined customer information to understand who the primary clients are using this online process.
3. **Key performance indicators (KPIs)**:  Defined relevant KPIs to determine the success of the new design.
4. **Hypothesis Testing**: Conducted hypothesis testing to validate assumptions and draw conclusions.

## Files
- Main Notebook 'PROJECT_EDA' for preparation of data and generation of a CSV for Statistical Analysis and Tableau Visualisation
- Python File "Functions" that store the different functions used in the main Notebook
- Other Notebooks Python for customer analysis & Statistical Analysis
- Tableau workbook [link](https://public.tableau.com/views/Week4_5_EDA_Project/Dashboard1?:language=fr-FR&publish=yes&:display_count=n&:origin=viz_share_link)
  
### Authors:
Beata & Pierre
