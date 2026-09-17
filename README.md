# Scripbox AI Robo-Advisory Case Study

## AI in Digital Wealth Management

A case study exploring how Artificial Intelligence and Machine Learning can be applied to digital wealth management and robo-advisory, using **Scripbox** as the business context.

## 📌 Project Overview

This project studies the problem of manually profiling investors and comparing a large number of mutual funds. It proposes an AI/ML-based approach that can automate risk profiling and help generate a personalised shortlist of investment options.

The project combines:

* **Random Forest Classification** for investor risk profiling
* **Multi-Factor Weighted Scoring** for mutual fund ranking
* Responsible AI and human oversight considerations
* Generative AI-based research and prompt evaluation

## 🎯 Business Problem

As digital investment platforms scale, manually understanding every investor's risk appetite and comparing a large number of mutual funds becomes difficult.

The key problems addressed in this case study are:

* Slow investor onboarding
* Inconsistent risk profiling
* Large number of mutual funds to compare
* Generic or mismatched recommendations
* Difficulty scaling personalised advisory services

## 🤖 AI/ML Solution

### 1. Random Forest Classification

The Random Forest model is used to classify investors into three risk categories:

* Conservative
* Moderate
* Aggressive

The model uses client/onboarding information such as age, income, investable surplus, existing investments, investment horizon and behavioural signals.

### 2. Multi-Factor Weighted Scoring

A separate scoring engine ranks mutual funds using factors such as:

* Returns
* Risk
* Expense ratio
* Sharpe ratio
* Fund quality/rating

This creates a transparent ranking system where the contribution of different factors can be explained.

## 🔄 System Workflow

```text
Client & Fund Data
        ↓
Random Forest Risk Profiling
        ↓
Investor Risk Category
        ↓
Mutual Fund Weighted Scoring
        ↓
Ranked Fund Shortlist
        ↓
Personalised Investment Recommendation
```

## 📊 Data

The demonstration model uses **synthetic data** structured around the types of client and mutual-fund information required for the proposed system.

### Client Data

* Age
* Income
* Number of dependents
* Monthly investable surplus
* Existing investments
* Investment horizon
* Behavioural response to market movements

### Mutual Fund Data

* Fund category
* 1-, 3- and 5-year returns
* Expense ratio
* Standard deviation
* Sharpe ratio
* Fund rating

## 💻 Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Random Forest
* Data analysis and scoring techniques

## 📁 Repository Contents

```text
Presentation/       → Final case-study presentation
AI_Model/           → Robo-advisory AI/ML demonstration notebook
Prompt_Portfolio/   → AI prompts used during the project
References/         → Research references
Learning_Reflection/→ Individual learning reflection
```

## 📈 Expected Business Impact

The proposed AI solution can help enable:

* Faster investor onboarding
* More consistent risk profiling
* More personalised fund shortlists
* Scalable advisory processes
* Greater transparency in recommendations
* Better use of advisor time

## ⚖️ Responsible AI

Since financial recommendations can affect real investment decisions, the project considers:

* **Bias:** Regularly audit risk classifications across different customer groups.
* **Transparency:** Make model feature importance and scoring weights explainable.
* **Human Oversight:** AI should support rather than completely replace human advisors.
* **Data Privacy:** Protect sensitive financial and behavioural information.
* **Model Risk:** Treat projected returns as estimates rather than guaranteed outcomes.

## 🧪 Project Demonstration

A sample client in the demonstration is classified as **Moderate risk**, with the system producing a shortlist focused on suitable fund categories.

The notebook demonstrates the proposed AI/ML workflow using synthetic data.

## 🧠 Generative AI Usage

Generative AI tools were used during the research and project-development process for:

* Understanding robo-advisory concepts
* Structuring the case study
* Comparing AI/ML approaches
* Researching Scripbox and the Indian wealth-tech industry
* Improving research prompts
* Developing the project workflow

## 💡 Key Learning

The project demonstrates that a successful AI solution should begin with a clear business problem.

Key learnings include:

1. AI and business strategy need to work together.
2. Explainability is particularly important in financial applications.
3. Good prompting improves the quality and usefulness of AI-assisted research.
4. Human oversight remains important when AI supports financial decisions.

## 👥 Academic Project

**Course:** Introduction to AI & Machine Learning
**Institution:** Chitkara Business School
**Topic:** AI in Digital Wealth Management — A Robo-Advisory Case Study: Scripbox

## 📌 Disclaimer

This is an academic case study and demonstration project. The AI model uses synthetic data and is not intended to provide actual investment advice or recommendations.
