## Portfolio
---
### Machine Learning/Statistics

[1. Custom ChatBot (via Google Colab + Python)](https://b3626385688ead7dd5.gradio.live)

*--LLM based on facebook/opt-1.3B model, fine-tuned using public fianancial data, and hosted online using Python (torch), Hugging Face (transformers) & Gradio.*
<img src="images/FinChat.png?raw=true"/>

---

[2. XGBoostRegressor (Azure AI | Machine Learning Studio)

Predicting number of bike rentals based on work day, temperature, year etc.
Model error metrics: 0.08 Normalized RMSE and 0.82 R Score
<img src="images/AzureML2.png?raw=true"/>](https://ml.azure.com/experiments/id/7b645f8f-7256-4c1c-856a-9d0fcfde4056/runs/bike-rentals-3_0?wsid=/subscriptions/502460ab-9b04-4a78-bcdc-f66453f64081/resourcegroups/group_Alpha/providers/Microsoft.MachineLearningServices/workspaces/Azure_workspace&tid=4a4e828a-52ae-46d2-b126-3e75b1fb605a#metrics)

---

[3. Multiple regression models - actuals vs. predicted (Python sklearn + Dash)
_Predicting number of bike rides per season, temperature, day type, etc. 
GradientBoostingRegressor is the most promissing with 0.8 R^2_
<img src="images/Screen Shot 2024-07-04 at 3.55.01 PM.png?raw=true"/>](https://mlbikerides.onrender.com)

---

[4. Logistic regression ML (Python sklearn)
_Predicting if a person is Diabetic #1 vs. not #2 based on Age, Glucose level and BMI index
Becasue of small sample of diabetics, I'm using *class_weight = 'balanced'*_
<img src="images/Screen Shot 2024-06-04 at 7.16.00 PM.png?raw=true"/>](https://mlapp-diabetic.onrender.com)

---

[5. Credit Default Logistic Regression 
(w/ Python (pandas, sklearn) + Jupyter NoteBook)](https://github.com/ANiraula/data_projects/blob/main/credit/CreditDefault.py)

*-- Jupyter Notebook with Python code analyzing credit default data, how load duration, installment rates, living arrangements & other parameters impact probability of a default.*
<img src="images/DefaultLogit.png?raw=true"/>

---

6. A/B Testing 
(w/ Python (scipy.stats, pandas) in Jupyter NoteBook

*-- created Python code analyzing advertising experiment on Treatment group, using Control group as a baseline showing how T-tests can be used to see statistical difference in outcomes (conversion rate) before and after the advertising.*
<img src="images/Screen Shot 2023-12-25 at 4.23.34 PM.png?raw=true"/>

--

[7. Isolation Forest 
(w/ Python sklearn.ensemble + seaborn)](https://github.com/ANiraula/data_projects/edit/main/PythonPractice.py)

*-- Detecting Inliners and Outliers based on salary and FTE, assuming 10% of population are outliers (Unsupervised learning)*
<img src="images/Screen Shot 2023-05-28 at 4.01.09 PM.png?raw=true"/>

---
                                                                    
[8. Pension Trends Linear Regression (w/ R Shiny)](https://reason.shinyapps.io/DistCoveredEE2/)

*-- Interactive app that allows to build boxplots and linear regression by picking 2 variables and Type of public employee.*
<img src="images/PensionTrendsRegression.png?raw=true"/>

---

[9. Candy Data Logistic Regression (w/ R + Jupyter NoteBook)](https://github.com/ANiraula/data_projects/blob/main/candy/R-candy.ipynb)

*-- Jupyter Notebook with R code analyzing candy data, price-to-sugar relationship & why some win more often when matched than others.*
<img src="images/LogitModel_Candy.png?raw=true"/>

---

[10. Seoul Bike Share Analysis (w/ R + R Markdown)](https://github.com/ANiraula/data_projects/tree/main/SeoulBikeShare)

*-- Analyzing 2018 data on bikes rented in Seoul and parameters (like season, temperature, and hour) that impact the number of bikes rented.*
<img src="images/SeoulBike3.png?raw=true"/>

---


### Managing & Analyzing Data

[2.1 Data workflow (*Palantir Foundry*)]

*-- Interactive data pipeline using Palantir Foundry that cleans, sorts, and joints two tables.*
<img src="images/Screenshot.jpeg?raw=true"/>

---

[2.2 Pension Database (*App w/ PostgreSQL + R Shiny*)](https://anil-niraula.shinyapps.io/ReasonDataViewer4)

*-- Interactive app showing 2001-2021 data for 110+ U.S. pension plans from internal database & linked public sources. User can filter data by state, by plan, by starting year, select columns, view interactive charts, and download filtered data in csv format.*
<img src="images/Reason Database Viewer (V4.0).png?raw=true"/>

---

[2.3 Invesment Returns (*App w/ R Reactable + Shiny*)](https://reason.shinyapps.io/StatePublicPensionReturnResults2021/)

*-- Interactive table & histogram/line chart showing distribution of 2020-2021 pension plan investment returns, and 2001-2021 pension debt.
User can filter data by state, plan, and add percentiles to distribution histogram*
<img src="images/2021FY Returns.png?raw=true"/>

---

[2.4 Invesment Returns 2022 (*App w/ R + datawrapper*)](https://reason.shinyapps.io/StatePublicPensionReturnResults2021/)

*-- Interactive table & line chart showing distribution of 2022 pension plan investment returns built using R for data manipulation & datawrapper for front-end*
<img src="images/InvReturns2022.png?raw=true"/>

---

[3. US Electricity Supply/Demand (*Viz w/ Python pandas*)](https://github.com/ANiraula/data_projects/blob/main/ElectricSupplyDemand_2020.py/)

*-- Line Charts showing share of US electricity supply at Peak and Low-load hours during each day in 2020*
<img src="images/Max_Min_ElectricSupply.png?raw=true"/>

---

[4. Compound Change in Debt (*App w/ Shiny + HTML + Netlify*)](https://reason.shinyapps.io/GainLoss_LASERS/)

*-- Interactive Waterfall chart showing how pension plan's debt compounded (by category) over 2000-2021 period. Slider resets starting year.*
<img src="images/LASERS_GainLoss.png?raw=true"/>

---

[5. R Package (*w/ R + Roxygen2 + GitHub*)](https://github.com/ReasonFoundation/pensionviewr)

*-- "pensionviewr" R package contains functions to pull, filter, manipulate, and visualize pension data from internal database & public sources.*
<img src="images/Pensionviewr.png?raw=true"/>

---

### Automating Reports/Presentations
[1. PowerPoint Slides (w/ RMarkdown + "pensionviewr" R pkg)](http://example.com/)

*-- RMarkdown files allow to automate pulling, analyzing and visualizing data, then knit charts/text/tables into set of powerpoint slides.*
<img src="images/OPERS_PPT2.png?raw=true"/>

---

### Modeling
  
[1. Pension Benefit Projection (*App w/ R + Shiny*)](https://anil-niraula.shinyapps.io/PensionBenefitModel_SCRS/)

*-- Benefit model (w/ interactive interface and custom R funcitons) that allows to recalculate total present value of public employees' pension benefits.
Functionality includes Defined Contribution plans benefits, different employee tiers, custom discount rates and other*
<img src="images/PensionWealthAccrual2.jpg?raw=true"/>

---
  
[2. Pension Benefit Model (*Interactive Doc w/ RMarkdown + Shiny*)](https://anil-niraula.shinyapps.io/PensionWealthModeling/)

*-- RMarkdown document w/ interactive Benefit model elements that allows to write text, bullet points, automate numbers, and interact w/ benefit model.*
<img src="images/PensionWealth_RMarkdown.png?raw=true"/>

---

3. Pension Actuarial Model (*Interactive R Shiny*)

*-- R code (with for-loops and custom functions) that projects pension plan's funding and contributions. Functionality includes stress-testing, changing parameters and amortization method.*
<img src="images/ERC_Proj.png?raw=true"/>

---

### NLP
  
[1. ChatGPT API (*Jupyter Notebook w/ openai pkg*)](https://anil-niraula.shinyapps.io/PensionBenefitModel_SCRS/)

*-- Code for ChatGPT prompts, allowing to set install, set up, and execute API-based connection w/ openai Python package*
<img src="images/ChatGPT_Prompt_Feb2023.png?raw=true"/>

---

### Academic Analysis (ML & Probability & Research)

[1. New Normal in Investment Returns (w/ Excel & R)](https://reason.org/wp-content/uploads/new-normal-public-pension-investment-returns.pdf)

[2. Alaska TRS Employee Separation Effects (w/ R & Stata)](https://reason.org/wp-content/uploads/effects-transition-to-defined-contribution-retirement-plan-on-teacher-separations-in-alaska.pdf)

*-- Peer-reviewed academic research and analysis involving data collection and ID joints, descriptive and regression (ML) analysis, probability analysis (Monte Carlo simulations), etc. *
<img src="images/Academic.png?raw=true"/>

---

---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
