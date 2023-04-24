# AI4ALL_ApplyAI_Team18

Names of participants: 
Ian Centeno Romero, John Wong, and Kyeongseo Choi

Topic of interest: 
Predicting the probability of developing depression with specific symptoms

Research Topic/Question:
Our project's goal is to use a supervised learning model that accurately predicts the probability of a person developing depression based on symptoms and showcase our data with a decision tree classifier.

Summary: 
Major Depression is one of the most common mental illnesses in the United States and also in the world. It interferes with people’s ability to carry out everyday tasks, participate in their hobbies and interests, and have a sense of joy in their lives (REXULTI® (Brexpiprazole)). All this can happen in the span of two weeks, which is considered as a major depressive episode. Data from 2020 tells that about 8.4% of all U.S. adults (18 years or older) had at least one major depressive episode in their lives (National Institute of Mental Health). There are also studies that have shown that depression can “accumulate” and worsen as a person grows older (ourworldindata).
It is important to understand that this mental disorder has varying causes and varying symptoms. Each person is different and therefore their signs of depression may be different, but there is a general guideline for people to assess themselves to see if they have this terrible illness. This is called the Montgomery-Asberg Depression Rating Scale (MDCalc). 
The MADRS asks a series of questions to the user and gives the score when finished assessing. The higher the score, the higher the severity of depression in the person. Our dataset found in Kaggle uses this rating scale and contains sample scores from people that took this assessment (Kaggle, Mobius). With this, predictions based on scores and other symptoms will be made possible.

Impact on world:
Depression is a sickening disease that humanity would be better off without. Being able to predict and determine who is likely to have depression could allow us to give them the help they need before it develops into something way worse. 
This is a mental disorder as terrible as they come. Artificial intelligence, specifically supervised machine learning, could help a major breakthrough in the mental health field. By analyzing millions of cases of past people that have suffered from this disease, it could learn to identify very possible signs of it and catch it as early as possible. AI has already shown to be able to identify the linguistic patterns of depressed individuals (Stevens Institute of Technology). Identifications like these can help people get the maximum amount of help and attention they need in order to get past this disorder as smoothly as possible.

Potential Bias:
Problems with error or uncertainty in the data, predictions may not be 100% accurate 
Can be expending more datasets as time goes which will allow the AI to analyze better.
People are unable to or can’t afford to get treatment
Can show the selection of free treatment from NIMH as an option under the chart.
The MADRS scale may incorrectly label the scale of a person’s depression because they may not answer 100% truthfully (reduce severity)
Other scales are also not 100% truthful, and as it is used in mental hospitals, it is trustful.

Technical Component:
Supervised Learning - an approach to creating artificial intelligence, where a computer algorithm is trained on input data that has been labeled for a particular output. It's good at classification and regression problems.​
Decision Tree - a tree-structured classifier, where internal nodes represent the features of a dataset, branches represent the decision rules and each leaf node represents the outcome. It uses the CART algorithm, which stands for Classification and Regression Tree algorithm. A decision tree simply asks a question, and based on the answer (Yes/No), it further split the tree into subtrees.

Next Steps:
We can see how each environments affect the possibility of getting depression. But, it would be better to get more cases to analyze and try to get rid of bias caused by small dataset. This can be done with modifying a new decision tree with a larger dataset that includes depression patients from all over the world. ​
Once the algorithm knows the major factor that causes depression, we can now make other thing that tells information about this to patients. In order to do that, we can easily make an website that tells the patient which bad factors they have and how it can be fixed based on our research by just entering the MADRS score. Something that shows the output.​

Citations (MLA):
About Depression & Partial Response | REXULTI® (Brexpiprazole). https://www.rexulti.com/depression-partial-response. ​
Carlos E. Galván-Tejada, Laura A. Zanella-Calzada, Hamurabi Gamboa-Rosales, Jorge I. Galván-Tejada, Nubia M. Chávez-Lamas, Ma. del Carmen Gracia-Cortés, Rafael Magallanes-Quintanar, José M. Celaya-Padilla, "Depression Episodes Detection in Unipolar and Bipolar Patients: A Methodology with Feature Extraction and Feature Selection with Genetic Algorithms Using Activity Motion Signal as Information Source", Mobile Information Systems, vol. 2019, Article ID 8269695, 12 pages, 2019. https://doi.org/10.1155/2019/8269695​
Dattani, Saloni. “What Is the Lifetime Risk of Depression?” Our World in Data, 18 May 2022, ourworldindata.org/depression-lifetime-risk#:~:text=The%20chances%20of%20ever%20having,the%20time%20they%20are%2065.​
“Decision Tree Algorithm in Machine Learning - Javatpoint.” Www.javatpoint.com, https://www.javatpoint.com/machine-learning-decision-tree-classification-algorithm. ​
“Depression.” National Institute of Mental Health, U.S. Department of Health and Human Services, https://www.nimh.nih.gov/health/topics/depression. ​
“Detecting Depression, Using AI.” Stevens Institute of Technology, 26 Feb. 2021, www.stevens.edu/news/detecting-depression-using-ai. ​
“Major Depression.” National Institute of Mental Health, U.S. Department of Health and Human Services, https://www.nimh.nih.gov/health/statistics/major-depression. ​
Möbius. “The Depression Dataset.” Kaggle, 6 Feb. 2021, https://www.kaggle.com/datasets/arashnic/the-depression-dataset. ​
“Montgomery-Asberg Depression Rating Scale (MADRS).” MDCalc, https://www.mdcalc.com/calc/4058/montgomery-asberg-depression-rating-scale-madrs. ​
