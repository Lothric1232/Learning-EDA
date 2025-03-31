# Learning-EDA
# Banking Dataset EDA

## Overview

This repository contains the Exploratory Data Analysis (EDA) for the Banking Dataset, which comprises client information and financial behavior for bank customers. The dataset includes various features that can be utilized for understanding customer demographics, financial products, and risk assessments.

## Dataset Description

The Banking Dataset includes the following columns:

- **Client ID**: Unique identifier for each client.
- **Name**: Client's name.
- **Age**: Client's age.
- **Location ID**: Identifier for the client's geographical location.
- **Joined Bank**: Date when the client joined the bank.
- **Banking Contact**: Preferred contact method for the client.
- **Nationality**: Client's nationality.
- **Occupation**: Client's job title or occupation.
- **Fee Structure**: Information on fees associated with client accounts.
- **Loyalty Classification**: Classification of the client based on loyalty metrics.
- **Estimated Income**: Client's estimated annual income.
- **Superannuation Savings**: Amount saved in superannuation accounts.
- **Amount of Credit Cards**: Total number of credit cards held by the client.
- **Credit Card Balance**: Outstanding balance on credit cards.
- **Bank Loans**: Total amount of personal loans taken by the client.
- **Bank Deposits**: Total deposits made by the client.
- **Checking Accounts**: Balance in checking accounts.
- **Saving Accounts**: Balance in saving accounts.
- **Foreign Currency Account**: Balance in foreign currency accounts, if applicable.
- **Business Lending**: Amount of loans taken for business purposes.
- **Properties Owned**: Number of properties owned by the client.
- **Risk Weighting**: Risk assessment score for the client.
- **BRId**: Bank relation identifier for linked accounts.
- **GenderId**: Identifier for the client's gender.
- **IAId**: Identifier for internal assessments.
- **Income_band**: Classification of income based on bands.

## Goals of the EDA

The primary objectives of the EDA on the Banking Dataset are:

1. **Understand Client Demographics**:
   - Analyze age, nationality, and occupation distributions to identify customer segments.

2. **Assess Financial Behavior**:
   - Examine the relationships between income, savings, loans, and credit behaviors.
   - Calculate total client deposits and total loans.

3. **Identify Trends and Patterns**:
   - Explore correlations between different financial products and client demographics.
   - Visualize how loyalty classification impacts banking products usage.

4. **Risk Assessment**:
   - Evaluate risk weightings in relation to client behaviors and product usage.

## Tools and Libraries

The EDA will be performed using the following tools and libraries:
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Getting Started

To reproduce the analyses, clone the repository and ensure all required libraries are installed:

```bash
git clone [repository-url]
cd banking-dataset-eda
pip install -r requirements.txt
