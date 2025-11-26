# Portfolio-3
## Project Background
#### The company is a consumer-lending institution offering personal loans, credit-building products, and other unsecured lending solutions to customers across several regions. As part of its credit-risk operations, the organization collects detailed information on applicants’ demographic profiles, financial stability, credit history, and loan characteristics. It also records whether customers eventually default on their loans.
#### This project analyzes that loan-level dataset to uncover the underlying factors that drive loan defaults and to build a predictive model that supports evidence-based risk assessment. The goal is to understand which customers pose the highest probability of default and why, while identifying the financial, behavioral, and credit-related signals that separate risky borrowers from reliable ones.

### The insights and recommendations center on three key domains:
#### - Credit Behavior — identifying structural signs of repayment difficulty based on credit history and previous delinquency.
#### - Loan Structure & Pricing — understanding how loan amount, interest rate, grade, and term duration influence default risk.
#### - Customer Profile & Financial Stability — examining income, employment duration, and demographic attributes that correlate with higher likelihood of default.

## Overview of Findings
#### Analysis of the loan dataset reveals several strong patterns that distinguish high-risk borrowers from low-risk ones. These patterns highlight the importance of financial stability, responsible credit use, and appropriate loan structuring in predicting whether a borrower will repay.
### 1. Previous credit issues are the strongest default indicator
#### Borrowers with a history of past default or short credit history show default rates far higher than other groups.
#### The combination of limited credit experience and prior negative events forms the most influential risk cluster.
### 2. Interest rate and loan grade sharply separate risky applicants
#### High-interest and lower-grade loans (suggesting internal risk-based pricing) consistently show elevated default levels.
#### This confirms that pricing is not only reactive but predictive — lenders charge higher rates to risky borrowers, and those borrowers do, in fact, default more often.
### 3. Loan amount interacts with income and employment stability
#### Borrowers with high loan requests relative to income, or with short employment duration, show above-average defaults.
#### This reinforces the importance of assessing repayment capacity, not just loan size alone.
### 4. Demographic factors play a secondary role
#### Age shows a predictable but weaker pattern:
#### - Younger borrowers default more frequently
#### - Middle-aged borrowers show the lowest risk
#### - Very old borrowers show slightly elevated risk, potentially due to income limitations
#### These effects exist but are far less influential than financial and credit variables.

## Executive summary
#### The analysis highlights that loan default is driven primarily by credit history strength, loan pricing and structure, and financial stability, rather than demographic characteristics alone. Borrowers with prior credit issues, short credit histories, high-interest loans, and strained income-to-loan ratios constitute the highest risk group.
#### The predictive modeling confirms these insights: variables such as previous default flag, loan grade, interest rate, credit history length, and income level consistently emerge as top predictors of default.
#### These findings equip the institution with a clear understanding of where default risk is concentrated and which applicant characteristics require enhanced scrutiny during underwriting. By targeting these high-risk segments with more robust verification, responsible loan sizing, and tailored pricing, the company can meaningfully reduce future losses.

## Recommendations
### 1. Strengthen screening for applicants with prior defaults or short credit histories
#### These factors exhibit the strongest predictive power.
#### Implement stricter verification or offer smaller, lower-risk loan products for these customers.
### 2. Reevaluate pricing policies for high-interest, lower-grade loans
#### The highest-priced loans experience the most defaults.
#### The institution should consider whether pricing reflects actual risk or unintentionally increases repayment burden.
### 3. Apply income-to-loan ratio and employment duration checks more rigorously
#### Ensure that approved borrowers have stable capacity to repay, especially when requesting higher-value loans.
### 4. Use predictive modeling outputs to support underwriting decisions
#### Integrate the model’s risk scores into operational workflows to prioritize manual review and adjust lending thresholds.
