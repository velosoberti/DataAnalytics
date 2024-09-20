<h1 align="center"> Projects Focused on Data Analysis </h1>


<h3 align="center"> This repository will include all my work and projects focused on objective and practical data analyses. Enjoy! </h3>

##

# **Projects:**

<ol>
  <li>
    <a href="#churn-analysis-for-a-telecom-company">
      Churn Analysis for a Telecom Company
    </a>
  </li>
  <li>
    <a href="#study-of-ibovespa-stocks-in-brazil">
      Study of Ibovespa Stocks in Brazil
    </a>
  </li>
  <li>
    <a href="#superstore-sales-analysis">
      Superstore Sales Analysis
    </a>
  </li>
  <li>
    <a href="#brazilian-agricultural-studies">
      Brazilian Agricultural Studies
    </a>
  </li>
  <li>
    <a href="#study-on-real-estate-prices-in-são-paulo">
      Study on Real Estate Prices in São Paulo. Where is it cheaper and why?
    </a>
  </li>
</ol>

#

- <h3 id="churn-analysis-for-a-telecom-company">Churn Analysis for a Telecom Company</h3>
<p>This project focuses on analyzing customer churn for a telecom company. It is divided into six main parts.</p> <p><strong>First:</strong> We assess the scope of the problem. Is churn actually a significant issue for the company, or is it within acceptable limits?</p> <p><strong>Next,</strong> we explore whether demographic factors are influencing churn. Are certain customer segments more prone to canceling their services?</p> <p><strong>Third,</strong> we investigate whether the type of contract significantly affects churn. Does contract length or type play a role in customer retention?</p> <p><strong>Fourth,</strong> we examine the impact of payment methods. Could the choice of payment method increase the likelihood of a customer churning?</p> <p><strong>Fifth,</strong> we calculate the probability of churn for customers with a tenure of just one month. What are the early indicators of churn risk?</p> <p><strong>Finally,</strong> we build a machine learning model to predict churn. Unlike many projects that build multiple classifiers and choose the best through cross-validation, this project prioritizes speed and precision. We opted for a <strong>Random Forest</strong> model, fine-tuning parameters like `max_features`, `n_estimators`, and `ccp_alpha` for pruning. This resulted in a model with 90% accuracy and approximately 60% recall, without severe overfitting. The model not only performs well but also highlights the most influential factors driving churn.</p> <p>This approach helps the company continuously feed new data into the model and track the most critical variables contributing to customer churn.</p> <p align="center"> <a href="https://github.com/velosoberti/DataAnalytics/blob/main/PROJETO%20-%20ANÁLISE%20DE%20CHURN/PROJECT%20-%20CHURN%20ANALYSIS.ipynb" style=" display: inline-block; padding: 10px 20px; font-size: 16px; font-weight: bold; color: #fff; background-color: #007bff; border: 2px solid #800080; border-radius: 5px; text-decoration: none; "> Click Here </a> </p>


#

- <h3 id="study-of-ibovespa-stocks-in-brazil">Study of Ibovespa Stocks in Brazil</h3>
        <p>The project aims to evaluate stocks in the IBOVESPA index. This project has four parts.</p>
        <p><strong>First:</strong> We start with data selection. The raw data from the IBOVESPA includes over 810 columns divided into categories such as "CLOSE_", "VOL_", "HURST_", "POWER_", "PROB_".</p>
        <p><strong>Next,</strong> we process this data. Since close values only appear after 10 AM, we need to remove values before this time.</p>
        <p><strong>Then,</strong> we calculate the daily percentage change using <code>pct.change()</code> over 1, 5, and 15 time periods, and merge these columns with the dataset. We then clean some values and categorize the "Prob_SUBIR" column into:</p>
        <ul>
            <li><strong>Very Low (MB)</strong>: from 0.002038 to 0.1954</li>
            <li><strong>Low (B)</strong>: from 0.1954 to 0.3878</li>
            <li><strong>Medium (M)</strong>: from 0.3878 to 0.5802</li>
            <li><strong>High (A)</strong>: from 0.5802 to 0.7726</li>
            <li><strong>Very High (MA)</strong>: from 0.7726 to 0.965</li>
        </ul>
        <p>This categorization helps us use machine learning algorithms more effectively and enables probability calculations.</p>
        <p><strong>Finally,</strong> we perform data mining to determine the best day of the week for buying stocks. We then look for the strongest correlations and find that the probability of a stock price increase is most strongly associated with the values of Ind_C and Ind_V. We also explore clusters, associations, and develop KNN and Decision Tree models to predict whether to buy or not, and a simple regression to forecast the probability of a stock price increase based on the most recent price.</p>

<p align="center">
  <a href="https://github.com/velosoberti/Data-Analytics-/tree/main/PROJETO%20-%20ANALISE%20AÇÕES%20DO%20IBOVESPA" style="
    display: inline-block;
    padding: 10px 20px;
    font-size: 16px;
    font-weight: bold;
    color: #fff;
    background-color: #007bff;
    border: 2px solid #800080;
    border-radius: 5px;
    text-decoration: none;
  ">
    Click Here
  </a>
</p>

#

- <h3 id="superstore-sales-analysis">Superstore Sales Analysis</h3>
In this project, I am conducting a market study to evaluate a sales boom. The data is located in the folder in the file "Superstore.csv," collected from Kaggle. The aim of this project is a diagnostic analysis of this boom, and at the end, I apply a regression analysis to infer and determine the percentage change of the responsible variable.


<p align="center">
  <a href="https://github.com/velosoberti/Data-Analytics-/tree/main/PROJETO%20-%20SUPERSTORE" style="
    display: inline-block;
    padding: 10px 20px;
    font-size: 16px;
    font-weight: bold;
    color: #fff;
    background-color: #007bff;
    border: 2px solid #800080;
    border-radius: 5px;
    text-decoration: none;
  ">
    Click Here
  </a>
</p>

#


- <h3 id="brazilian-agricultural-studies">Brazilian Agricultural Studies</h3>
The aim of this project is to analyze relationships and patterns in agricultural sector prices. The raw data is available and was sourced from Kaggle. In this study, it was important to address several questions such as:


<p align="center">
  <a href="https://github.com/velosoberti/Data-Analytics-/tree/main/PROJETO%20-%20PREÇOS%20DA%20AGRICULTURA" style="
    display: inline-block;
    padding: 10px 20px;
    font-size: 16px;
    font-weight: bold;
    color: #fff;
    background-color: #007bff;
    border: 2px solid #800080;
    border-radius: 5px;
    text-decoration: none;
  ">
    Click Here
  </a>
</p>


#

<h3 id="study-on-real-estate-prices-in-são-paulo">Study on Real Estate Prices in São Paulo. Where is it cheaper and why?</h3>
<p id="churn-analysis-for-a-telecom-company" /p>
This project aims to explore a bit about real estate prices in the state of São Paulo. As my first project, it is somewhat simpler but still yields significant results. The data is also available in the folder and was sourced from Kaggle.


<p align="center">
  <a href="https://github.com/velosoberti/Data-Analytics-/tree/main/PROJETO%20-%20ANALISE%20DE%20DADOS%20DOS%20ALUGUÉIS%20DE%20IMÓVEIS%20-%20SP" style="
    display: inline-block;
    padding: 10px 20px;
    font-size: 16px;
    font-weight: bold;
    color: #fff;
    background-color: #007bff;
    border: 2px solid #800080;
    border-radius: 5px;
    text-decoration: none;
  ">
    Click Here
  </a>
</p>




##

- 🔭 I am currently working on Machine Learning and Data Analytics projects.

- I bring my experience with Statistics and Machine Learning through mini-projects that aim to explore the complexity and variety of data in the world.

- 🤓 Among my key skills, I highlight Excel, Python, R, Power BI (storytelling and related), and SQL.

- ✅ I always strive to provide new and powerful insights, operating through the lens of business and root cause analysis.

- Having worked in the data field for 3 years with various projects, I am starting my repository here. The idea of this repository is to showcase my skills.

- 📘 Probability, Estimation, Hypothesis Testing, Regression, and Forecasting with Machine Learning will be some of the topics you'll find here today!







<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/www.linkedin.com/in/velosoberti" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="www.linkedin.com/in/velosoberti" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer"> <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> </p>
