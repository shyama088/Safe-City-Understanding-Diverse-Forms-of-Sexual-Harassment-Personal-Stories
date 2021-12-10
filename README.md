# Safe-City-Understanding-Diverse-Forms-of-Sexual-Harassment-Personal-Stories
To automate the categorizing and evaluating several forms of sexual harassment: commenting, ogling, and groping , which aims to advance the battle against such harassment and abuse using Machine Learning models


This project is based on the Research paper titled "SafeCity: Understanding Diverse Forms of Sexual Harassment Personal Stories" by Sweta Karlekar, Mohit Bansal
Results from the paper:
![image](https://user-images.githubusercontent.com/59326106/145611196-09faee14-77ba-4b6f-8287-8a022dc8a947.png)


1. Objective:
To classify if a personal story falls into either of the following categories or not - Commenting, Groping or Ogling.

2. Data Type:
Text data

3. ML Problem:
Three binary classification models - Commenting or Not Commenting, Groping or not Groping and Ogling or not Ogling

4. Performance Metric:
Accuracy and F1 score

5. Results:
Commenting or Not Commenting Accuracy - 79%
Groping or Not Groping Accuracy - 82%
Ogling or Not Ogling Accuracy - 83%

![image](https://user-images.githubusercontent.com/59326106/145610335-71ae5a06-4c72-428e-a8ad-c1cb65a730b0.png)

6. Models Experimented: Logistic Regression, Support Vector Machine, Decision Tree and GBDT. Decision Tree gave the best results for Commenting,
Groping and Ogling. Below image is for Commenting dataset. A similar result is seen for Groping and Ogling
![image](https://user-images.githubusercontent.com/59326106/145610744-fcf64e9b-5ade-42a3-97fb-a2b2e30eeb6e.png)



7. These results are obtained using classical ML models. They are very close to the results obtained in the research paper Deep Learning models.

8. Model deployed on AWS
