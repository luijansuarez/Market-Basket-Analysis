# Market-Basket-Analysis— Turning Shopping Baskets into Better Retail Decisions
## Overview

Retailers generate millions of transactions every year, but most shopping baskets are treated as isolated events.
This project applies Market Basket Analysis (MBA) to discover purchasing patterns hidden across thousands of customer transactions and transform them into actionable retail decisions.
Using Python, the workflow identifies which products customers consistently purchase together and evaluates the strength of these relationships through Support, Confidence, Lift, and the Apriori algorithm. The resulting analysis helps retailers optimize promotions, cross-selling opportunities, and in-store product placement.

## Business Problem

Improving sales is not always about attracting more customers.
Sometimes the greatest opportunity is helping existing customers buy one additional product.
However, when retailers manage thousands of SKUs and millions of possible product combinations, identifying these opportunities manually becomes impossible.
Market Basket Analysis provides a structured way to answer questions such as:

-Which products should be promoted together?
-Which aisles should be located close to each other?
-Which cross-selling opportunities have the highest probability of success?
-Which associations are statistically meaningful rather than random?

## What the Solution Does
Transaction Engineering
-Loads raw retail transaction data
-Converts purchases into basket format
-Creates a binary transaction matrix

## Association Rule Mining

Computes:
-Support
-Confidence
-Lift
using both:
-Brute-force pair enumeration
-Apriori algorithm

allowing comparison between exhaustive and scalable approaches.

## Executive Reporting

Automatically generates an Excel report containing:

-Most frequently purchased aisles
-Heatmap of aisle popularity
-Strongest product associations
-Support, Confidence and Lift metrics

Designed for recurring retail decision making rather than one-time analysis.

## Key Insights

This project demonstrates that:
Not every frequent combination represents a meaningful relationship.
High confidence does not necessarily imply a valuable association.
Lift is essential to distinguish genuine customer behavior from popularity effects.
Small improvements in cross-selling can generate meaningful revenue without increasing customer acquisition costs.

## Why This Matters

Retail competitiveness increasingly depends on understanding customer behavior at the basket level.
Market Basket Analysis allows organizations to improve:
-Cross-selling
-Store layout
-Promotional campaigns
-Category management
-Inventory allocation
using purchasing behavior rather than intuition.

##Skills Demonstrated
Retail Analytics
Market Basket Analysis
Apriori Algorithm
Association Rule Mining
Data Engineering
Python
Data Storytelling
Retail Decision Support
