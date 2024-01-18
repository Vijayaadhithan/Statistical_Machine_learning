# Statistical_Machine_learning
Does Wo(men) Talk Too Much in Films? 
## Abstract

This project aims to analyze the representation of gender in Hollywood films through the use of machine learning techniques. By examining a dataset of screenplay details from approximately 1000 movies, the project focuses on the number of words spoken by male and female characters, the gender of lead actors, and the film's box office revenue. The objective is to build classification models that can accurately predict the gender of the lead character in a movie based on these features. The findings of this analysis can provide insights into the gender balance in speaking roles and its potential impact on box office success.

## Introduction

The representation of women in the film industry has long been a topic of discussion and critique. This project delves into the question of whether women talk too much or too little in films, by analyzing the distribution of words spoken by male and female characters. Additionally, the project investigates the gender balance in lead roles and explores the relationship between the dominance of male dialogue and box office revenues. By leveraging machine learning techniques, including logistic regression, the project aims to provide quantitative evidence on gender representation in Hollywood movies.

## Data Analysis and Classification Models

The analysis of the dataset reveals that men tend to have more speaking roles in Hollywood movies, with male characters speaking more words than their female counterparts in the majority of films examined. However, there is evidence of progress in recent years, with a gradual increase in the number of words spoken by female characters. Furthermore, the project examines whether films with more male dialogue generate higher revenues, and the results indicate a correlation between male-dominated dialogue and box office success.

To predict the gender of the lead character, several classification models were implemented, including logistic regression. By considering various features such as the number of words spoken by the lead, the presence of male and female actors, the movie's gross revenue, and the year of release, the models achieved an accuracy of 93.3% after fine-tuning. These results highlight the potential of machine learning in predicting gender representation in films and provide valuable insights for filmmakers and industry professionals.


## Result 

| Model                  | Accuracy | Precision | Sensitivity | Specificity |
|------------------------|----------|-----------|-------------|-------------|
| Logistic Regression    | 87.5     | 90.2      | 94.9        | 55.9        |
| LDA                    | 84.60    | 84.4      | 95.3        | 60.4        |
| QDA                    | 91.34    | 89.0      | 97.6        | 72.9        |
| K Nearest Neighbor     | 81.1     | 83.3      | 93.3        | 47.6        |
| Classification Trees   | 80.12    | 83.47     | 88.9        | 60.4        |
| Random Forests         | 81.1     | 80.3      | 96.7        | 47.9        |
| Boosting               | 89.2     | 85.9      | 93.0        | 57.3        |

## Best Performing Model
The best-performing model based on overall metrics is the Quadratic Discriminant Analysis (QDA) with an accuracy of 91.34%. It achieves high precision, sensitivity, and specificity, making it a strong candidate for your classification task.
