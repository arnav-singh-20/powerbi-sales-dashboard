# Learnings from Sales & Profit Dashboard Project

## 1. Data Modeling Matters More Than Visuals
Learned that incorrect relationships or grain mismatches can silently break metrics, even if visuals look correct. Built proper star schema with fact and dimension tables to ensure reliable measures.

## 2. DAX Requires Context Awareness
Understood the importance of filter context vs row context while creating measures such as Total Sales, Profit, and Quantity. Small mistakes in context can lead to inflated or duplicated values.

## 3. Business Questions Drive Dashboard Design
Realized that dashboards are not about showing all data, but about answering specific questions like:
- Which products drive profit?
- Which promotions are ineffective?
- Are sales growing consistently over time?

## 4. Data Cleaning Is Non-Negotiable
Learned to handle inconsistent date formats, missing values, and invalid records before analysis. Clean data significantly improved accuracy and performance of visuals.

## 5. Visual Design Impacts Decision Making
Experienced how color choice, sorting, and top/bottom comparisons directly affect insight clarity. Simplified visuals to focus attention on actionable patterns.

## 6. Documentation Is Part of the Project
Understood the importance of explaining metrics, assumptions, and logic through README and measure documentation so stakeholders can trust and reuse the dashboard.
