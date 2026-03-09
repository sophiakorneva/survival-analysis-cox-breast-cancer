Dataset: Breast cancer clinical dataset (public dataset used for demonstration)

Goal:
Evaluate the effect of estrogen receptor (ER) status and therapy on patient survival.


##Methods

- Kaplan–Meier survival curves
- Log-rank test
- Cox proportional hazards model
- Interaction effects
- Proportional hazards assumption test

##Variables

- age
- tumor size
- number of positive nodes
- estrogen receptor expression
- hormone therapy

  ##Example result

Hormone therapy significantly reduces hazard of death (HR ≈ 0.66).

## Example survival curves

![Survival curves](survival_er.png)

Tools

Python  
pandas  
lifelines  
matplotlib
