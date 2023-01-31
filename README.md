# Strategize Bridge Maintenance Effectively
This analysis was originally a project I (Monika Sembiring) did with my friend Tina Feng in our 95885 - Data Science and Big Data class at Carnegie Mellon University. 

## Background and Motivation
In January 2022, Fern Hollow Bridge collapsed on the day President Biden visited Pittsburgh, the City of Bridges. Although no one died, we wonder: What are the factors associated with the risk level/condition of a bridge? The answer can help prevent potential bridge collapses in the future, thus preparing for better maintenance for the bridge and providing people with a safer living environment.

## Project Goals
* [Classification] Help government prioritize bridge inspection and maintenance for bridges with poor conditions before hand; encourage better preservation to maintain the sustainability of bridges in excellent condition.
* [Case Studies] Recommend some bridges regarding maintenance efforts and costs on top of bridge conditions and other attributes to help government strategically allocate the bridge maintenance budget.

## Dataset
* PennDOT bridge dataset
* Allegheny county crash dataset
* Pennsylvania bridges dataset

### Machine Learning Technique Used
* K Nearest Neighbor
* Gaussian Naive Bayes
* Support Vector Machine
* Random Forest
* Gradient Boosting

## Project Description
(Provide more detailed overview of the project.  Talk a bit about your data sources and what questions and hypothesis you are exploring. What specific data analysis/visualization and modelling work are you using to solve the problem? What blockers and challenges are you facing?  Feel free to number or bullet point things here)

## Featured Notebooks/Analysis/Deliverables
* Best model for bridge condition classification is Random Forest, with an accuracy of 77.8% and a recall rate of 64.1%.
* The most essential features in determining bridges' condition are Substructure Condition, Superstructure Condition, Reconstruction Age, Age, Deck Condition, and Rehab/Replace Eligibility.
* On top of the predicted condition result, maintenance prioritization will be evaluated with the availability of alternative routes, bridge size, traffic amount, and estimated maintenance cost.
