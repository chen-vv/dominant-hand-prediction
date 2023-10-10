
# Dominant Hand Prediction Model based on Personality

This repo contains an investigation into the possibility of building a machine learning model for determining whether an individual is right- or left-handed based on their interests, fears, and personality traits. 

### Dataset
The primary dataset used in this study contains 1010 data points collected from participants, all of which were of Slovakian nationality and aged between 15 to 30. The participants were asked about their preferences, interests, fears, opinions, and personality traits. For the purposes of this study, only features listed under the following headers were used:
- Hobbies & interests
- Phobias
- Personality traits, views on life, & opinions

Source: https://www.kaggle.com/datasets/miroslavsabo/young-people-survey


### Models Used
Due to the classification nature of this problem, the following models from `sklearn` were trained on the data:
- `RandomForestClassifier`
- `LogisticRegression`
- `KNeighborsClassifier`
- `SVC`
- `DecisionTreeClassifier`
