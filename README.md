<div align="center">
  <a href="https://github.com/business-science/ai-data-science-team">
    <picture>
      <img src="/img/ai_data_science_team_logo.jpg" alt="AI Data Science Team" width="400">
  </picture>
  </a>
</div>
<div align="center">
  <em>An AI-powered data science team of agents to help you build head-turning AI data science apps</em>
</div>
<div align="center">
  <a href="https://pypi.python.org/pypi/ai-data-science-team"><img src="https://img.shields.io/pypi/v/ai-data-science-team.svg" alt="PyPI"></a>
  <a href="https://github.com/business-science/ai-data-science-team"><img src="https://img.shields.io/pypi/pyversions/ai-data-science-team.svg" alt="versions"></a>
  <a href="https://github.com/business-science/ai-data-science-team/blob/main/LICENSE"><img src="https://img.shields.io/github/license/business-science/ai-data-science-team.svg?v" alt="license"></a>
</div>


# Your AI Data Science Team (An Army Of Agents)

**An AI-powered data science team of agents to help you build head-turning AI data science apps**.

**Star ⭐ This GitHub (Takes 2 seconds and means a lot).**

*Beta - This Python library is under active development. There may be breaking changes that occur until release of 0.1.0.* 

---

The AI Data Science Team of Copilots includes Agents that specialize data cleaning, preparation, feature engineering, modeling (machine learning), and interpretation of various business problems like:

- Churn Modeling
- Employee Attrition
- Lead Scoring
- Insurance Risk
- Credit Card Risk
- And more

## Table of Contents

- [Your AI Data Science Team (An Army Of Agents)](#your-ai-data-science-team-an-army-of-agents)
  - [Table of Contents](#table-of-contents)
  - [Companies That Want A Custom AI Data Science Team (And AI Apps)](#companies-that-want-a-custom-ai-data-science-team-and-ai-apps)
  - [Free How To Build AI Agents for Data Scientists Workshop](#free-how-to-build-ai-agents-for-data-scientists-workshop)
  - [Data Science Agents](#data-science-agents)
    - [Coming Soon: Multi-Agents](#coming-soon-multi-agents)
    - [...And after that, the Multi-Agent Data Science Apps](#and-after-that-the-multi-agent-data-science-apps)
    - [Agents Available Now](#agents-available-now)
    - [Agents Coming Soon](#agents-coming-soon)
  - [Disclaimer](#disclaimer)
  - [Installation](#installation)
  - [Usage](#usage)
    - [Example 1: Feature Engineering with the Feature Engineering Agent](#example-1-feature-engineering-with-the-feature-engineering-agent)
    - [Example 2: Cleaning Data with the Data Cleaning Agent](#example-2-cleaning-data-with-the-data-cleaning-agent)
  - [Contributing](#contributing)
  - [License](#license)
- [Want To Become A Full-Stack Generative AI Data Scientist?](#want-to-become-a-full-stack-generative-ai-data-scientist)

## Companies That Want A Custom AI Data Science Team (And AI Apps)

Want to have your own _customized_ enterprise-grade AI Data Science Team and domain-specifici AI-powered Apps? 

**Send inquiries here:** [https://www.business-science.io/contact.html](https://www.business-science.io/contact.html)

## Free How To Build AI Agents for Data Scientists Workshop

If you're an aspiring data scientist who wants to learn how to build AI Agents and AI Apps for your company that performs Data Science, Business Intelligence, Churn Modeling, Time Series Forecasting, and more, then I'd love to help you. 

[**Register for my next Generative AI for Data Scientists workshop here.**](https://learn.business-science.io/ai-register)

## Data Science Agents

This project is a work in progress. New data science agents will be released soon.

![Data Science Team](/img/ai_data_science_team.jpg)

### Coming Soon: Multi-Agents

This is the internals of the Business Intelligence SQL Agent I'm working on:

![Business Intelligence SQL Agent](/img/multi_agent_sql_data_visualization.jpg)

### ...And after that, the Multi-Agent Data Science Apps

This is a top secret project I'm working on. It's a multi-agent data science app that performs time series forecasting.

![Multi-Agent Data Science App](/img/ai_powered_apps.jpg)

### Agents Available Now

1. **Data Wrangling Agent:** Merges, Joins, Preps and Wrangles data into a format that is ready for data analysis.
2. **Data Visualization Agent:** Creates visualizations to help you understand your data. Returns JSON serializable plotly visualizations.
3. **Data Cleaning Agent:** Performs Data Preparation steps including handling missing values, outliers, and data type conversions.
4. **Feature Engineering Agent:** Converts the prepared data into ML-ready data. Adds features to increase predictive accuracy of ML models.
5. **SQL Database Agent:** Connects to SQL databases to pull data into the data science environment. Creates pipelines to automate data extraction. Performs Joins, Aggregations, and other SQL Query operations.

### Agents Coming Soon

1. **Data Analyst:** Analyzes data structure, creates exploratory visualizations, and performs correlation analysis to identify relationships.
2. **Machine Learning Agent:** Builds and logs the machine learning models.
3. **Interpretability Agent:** Performs Interpretable ML to explain why the model returned predictions including which features were the most important to the model.
4. **Supervisor:** Forms task list. Moderates sub-agents. Returns completed assignment. 

## Disclaimer

**This project is for educational purposes only.**

- It is not intended to replace your company's data science team
- No warranties or guarantees provided
- Creator assumes no liability for financial loss
- Consult an experienced Generative AI Data Scientist for building your own custom AI Data Science Team
- If you want a custom enterprise-grade AI Data Science Team, [send inquiries here](https://www.business-science.io/contact.html). 

By using this software, you agree to use it solely for learning purposes.

## Installation

``` bash
pip install git+https://github.com/business-science/ai-data-science-team.git --upgrade
```

## Usage

[See all examples here.](/examples)

### Example 1: Feature Engineering with the Feature Engineering Agent

[See the full example here.](/examples/feature_engineering_agent.ipynb)

``` python
feature_engineering_agent = FeatureEngineeringAgent(model = llm)

feature_engineering_agent.invoke_agent(
    data_raw = df,
    user_instructions = "Make sure to scale and center numeric features",
    target_variable = "Churn",
    max_retries = 3,
)
```

``` bash
---FEATURE ENGINEERING AGENT----
    * CREATE FEATURE ENGINEER CODE
    * EXECUTING AGENT CODE
    * EXPLAIN AGENT CODE
```

``` python
feature_engineering_agent.get_data_engineered()
```

### Example 2: Cleaning Data with the Data Cleaning Agent

[See the full example here.](/examples/data_cleaning_agent.ipynb) 

``` python
data_cleaning_agent = DataCleaningAgent(model = llm)

response = data_cleaning_agent.invoke_agent(
    data_raw = df,
    user_instructions = "Don't remove outliers when cleaning the data.",
    max_retries = 3,
)
```

``` bash
---DATA CLEANING AGENT----
    * CREATE DATA CLEANER CODE
    * EXECUTING AGENT CODE
    * EXPLAIN AGENT CODE
```

``` python
data_cleaning_agent.get_data_cleaned()
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License. See LICENSE file for details. 

# Want To Become A Full-Stack Generative AI Data Scientist?

![Generative AI Data Scientist](/img/become_a_generative_ai_data_scientist.jpg)

I teach Generative AI Data Science to help you build AI-powered data science apps. [**Register for my next Generative AI for Data Scientists workshop here.**](https://learn.business-science.io/ai-register)


