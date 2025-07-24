# **Toward Smarter Valuation: A Machine Learning Approach to Residential Property Mass Appraisal in Philadelphia**

by BETA GROUP - DTI DS
- Christina Eastti Saktiani
- Jonathan Mark Hamonangan
- Faaza Naima
  
**Context**
Philadelphia is currently facing a significant housing crisis driven by a severe shortage of affordable housing. Strong demand and limited housing supply have caused rents to rise beyond the reach of many, while first-time homebuyers are finding the market difficult due to overvalued properties. 

The Office of Property Assessment (OPA) in Philadelphia determines the value of each property within the city for the purpose of real estate tax assessment. OPA uses mass appraisal methods, relying on sales data, property characteristics, and statistical techniques. For the 2020 assessment, OPA analyzed sales transactions from July 1, 2017, to June 30, 2018, to determine property values. This method, while widely accepted, has limitations due to its reliance on outdated data and traditional statistical methods such as Multiple Regression Analysis. The reliance on outdated data and traditional statistical methods (Multiple Regression Analysis) limits the ability to predict property values accurately
mispricing in the real estate market flawed policy decisions related to housing and urban development. Traditional statistical methods (Multiple Regression Analysis) often fail to incorporate large scale complex non-linear relationships between variables, and cannot adapt to emerging patterns or trends. 

In the era of big data, ML has received a lot of attention as a means of large-scale data analysis. Experts in the field of economics have been using ML algorithms to estimate property values extensively over the past decade . The advantages of these algorithms are their ability to output predictions from large datasets with more precision than traditional regression models. Decision Trees, Random Forest, and Gradient Boosting Models are the most frequently applied ML models in property valuation and could provide accurate prediction results.

As data scientists of the Housing Association of Philadelphia (HAP), we aim to improve this process by leveraging machine learning techniques and extending the dataset to include more recent data (up to 2020). This approach will provide more accurate and fair property valuations, reflecting current market trends.

Target: Market Value

**Files:**
- Dataset : PHL_OPA_PROPERTIES.csv
- Notebook : beta_group_final_project.ipynb
  - df_model.csv used for modeling
  - df_prediction.csv used to analyze the prediction result (implementation part)
- Tableau : https://public.tableau.com/app/profile/jonathan.mark.hamonangan/viz/BetaGroup-TowardSmarterValuationAMachineLearningApproachtoResidentialPropertyMassAppraisalinPhiladelphia/DashboardMV?publish=yes
- App Deployment (Local) : https://philadelphia-housing-price-betagroup.streamlit.app/ (public)
* This streamlit app is unstable on public access, so we suggest to launch the app on local access.
  
---
**How to Use the Streamlit Application (Local):**
1. Clone or download all the following files into **one project folder**:
   * `about.py`
   * `app.py`
   * `conn.py`
   * `custom_components.py`
   * `pipelines.joblib`
   * `prediction.py`
   * `prediction_batch.py`
   * `prediction_single.py`
   * `style.css`
2. Open terminal or command prompt.
3. Navigate to the project folder : `cd path/to/your/folder`
5. Launch the Streamlit app by typing this on terminal : `streamlit run app.py`
---

**Tableau Dashboard:**
![tableau1_beta_group](https://github.com/user-attachments/assets/4f7ebe03-5bd1-4bf3-91dc-2390d52eeb88)

![tableau2_beta_group](https://github.com/user-attachments/assets/fbac837a-e8e7-4959-ae9a-5a338e4725fd)

![tableau3_beta_group](https://github.com/user-attachments/assets/0d559eb4-5383-4ad1-92fd-0d3066d53916)
---
