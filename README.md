# Lead Scoring — ML Case Study

## Problem Statement
An education company (X Education) sells online courses to industry professionals. 
The goal is to build a lead scoring model that assigns a score (0–100) to each lead, 
helping the sales team prioritize high-conversion prospects and improve the lead 
conversion rate from ~30% to ~80%.

## Approach
- Performed EDA and data cleaning on lead attributes (source, activity, demographics)
- Applied feature engineering and handled missing values
- Built a **Logistic Regression** model to predict lead conversion probability
- Assigned lead scores based on predicted probabilities
- Identified top features driving conversion

## Tech Stack
- **Language:** Python
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, Statsmodels
- **Notebook:** Jupyter

## Files
| File | Description |
|---|---|
| `ML_CaseStudy_Sol.ipynb` | Main solution notebook |
| `Presentation.pdf` | Business presentation of findings |
| `Summary_report.pdf` | Summary of methodology and results |
| `Sub_QuestionsAnswers.pdf` | Answers to subjective questions |

## Key Results
- Logistic Regression model with optimized cutoff for business use case
- Top predictors identified: lead source, time spent on website, last activity
- Lead score assigned to each prospect to guide sales prioritization
