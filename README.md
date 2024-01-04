# Modeling the Relationship between Atmospheric Carbon Dioxide Concentrations and the Human Population

<!--## Abstract
This project investigates the effects of carbon dioxide emissions and human population growth on global warming. Provided is a background on the issue of global warming and how it is caused by the burning of fossil fuels. The motivation behind the study is to develop a model to understand the growth of CO2 emissions over time and how it relates to human population growth. The study uses data from the Carbon Dioxide Information Analysis Center and population data from Kaggle. Regression analysis is utilized to determine the optimal parameters for the model. The results show that the model accurately predicts the behavior of the system and can be used to test hypotheses about the system's behavior under different conditions. Limitations of the model exist but it is still a useful tool for understanding and predicting the impact of CO2 emissions on the environment.
-->

## Introduction
This project delves into the intricate relationship between atmospheric CO2 concentration and human activities. It highlights the detrimental effects of rising CO2 levels, including severe weather events, environmental degradation, and adverse health impacts. The motivation behind this work is rooted in the critical need to understand and mitigate the impact of human activities on CO2 concentration and, consequently, global warming. The exploration aims to develop a mathematical model that not only accounts for human-induced factors but also integrates natural CO2 variations, providing a more comprehensive understanding of the factors driving atmospheric CO2 levels and their complex interaction with the human population.


## Mathematical Model
The model explores the relationship between atmospheric CO2 `C(t)` and human population `N(t)`, considering both natural and anthropogenic CO2 sources. It assumes a steady natural CO2 growth rate and a variable human-induced rate, with natural absorption proportional to CO2 levels. The model suggests a predator-prey dynamic between CO2 and population, assuming logistic population growth in the absence of CO2. These assumptions introduce parameters for more accurate predictions by considering natural CO2 variability. Represented through differential equations and compartmental diagrams, the model aims to elucidate the complex interplay between CO2 levels and human population.

![Figure 1](https://github.com/napronald/Modeling-the-Relationship-Between-CO2-Emissions-and-Human-Population/raw/main/Figures/pic1.png)



## Behavior Analysis

### Model Predictions vs. Long-Term Expectations
The long-term behavior predicted by our model, as illustrated in the attached figure, aligns with general expectations of CO2 emissions and human population trends over time. The model suggests a continuous increase in CO2 emissions, which, despite the projected decline in human population post-2100, points towards the persistent rise of other contributing factors to CO2 emissions, such as industrialization and energy consumption patterns.

![Figure 3](https://github.com/napronald/Modeling-the-Relationship-Between-CO2-Emissions-and-Human-Population/raw/main/Figures/pic3.png)

The human population curve indicates a peak followed by a decline, reflecting constraints like limited resources and potential impacts of environmental policies and technological advancements. While the real data closely follows the model's prediction up to the current date, the divergence in later years highlights the model's reliance on current trends and its exclusion of unforeseen future variables.

### Analysis of Predictive Validity
The congruence between our model's predictions and known data suggests that the underlying assumptions are sound within the observed time frame. However, the model's predictions extending into the distant future must be interpreted with caution due to potential changes in variables that are not accounted for in the current model.

Our model's assumptions are rooted in the continuation of present-day trends without significant alteration by new technologies or drastic changes in human behavior. This is a sensible baseline for prediction but is inevitably limited by the availability and scope of the data. The real challenge lies in the model's capacity to adapt to new data as it becomes available, which would require the model to be flexible and updatable.

### Conclusion on Model
Overall, our model provides a plausible projection based on current data and trends. However, there's a noticeable split between model predictions and actual data, hinting at the models' insufficiency in capturing trends due to variables like technology, policy, and economic factors not being considered. These models, while insightful for historical analysis, require enhancements for future predictions, underlining the necessity for incorporating complex dynamics and regular updates to stay relevant to changing global patterns.

![Figure 2](https://github.com/napronald/Modeling-the-Relationship-Between-CO2-Emissions-and-Human-Population/raw/main/Figures/pic2.png)
## Additional Resources and Report

For a comprehensive understanding of our study and to explore the intricacies of our methodology and findings in greater detail, the full written report is available. Additionally, the code used for analysis and modeling is accessible for review and replication of the study's results.

- [Full Written Report](https://github.com/napronald/Modeling-the-Relationship-Between-CO2-Emissions-and-Human-Population/blob/main/Report.pdf)
- [Colab Code for Analysis](https://colab.research.google.com/drive/18ziAUaxkwcjIAIkuyw5jClQf8QpZL5UW?usp=sharing)

## Data Sources
- Carbon Dioxide Information Analysis Center (CDIAC)
- Kaggle Population Dataset
- [Dataset Spreadsheet](https://docs.google.com/spreadsheets/d/e/2PACX-1vT7_E5EcTEZuocjX9goaR1eXwgF8N8iYJd4nZov2W4HXf-CPiIBpgX2fxRaLZkt3-Fd-E9FB61eicgB/pubhtml)


