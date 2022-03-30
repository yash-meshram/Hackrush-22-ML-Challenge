<img width="1000" src="./data/top.gif">

# [HackRush'22](https://www.kaggle.com/competitions/hackrush22-ml-challenge) | Team **PRAY** Submission

## Problem Statement

In an alternate universe, due to the unbalanced workload among the faculty of Stanford University, the university is suffering from high faculty attrition and has become an object of mockery among the public. There has also been a petition to rename it to Standard University due to this mismanagement.

To combat the inevitable backlash, the university aims to build a system that can tell the number of students that will enrol in a course in a given academic year. Such a system will not only allow the university's stakeholders to smartly recruit faculty to balance faculty workload but also gauge the student's interest in a given course to decide if the given course should be offered or not.

Now the question is how to build these systems? That's where you come in!

In this challenge, you will develop a model that tries to forecast the future total student enrolment for courses offered at the university based on the historic enrolment trend of the last 200 years.

## Our approach

Yash bhai! yahan pe hamara approach likh de

## Models we used?

- Linear Regression(scikit)
- Random forest regression(scikit)
- CatBoostRegressor(catboost)
- Sequential model(tensorflow)

## Tuning Hyperparameters

- `n_estimators`: number of trees in the forest
- `depth`: depth of the tree
- `learning_rate`: determines the step size at each iteration while moving toward a minimum of a loss function

## Challenges we faced!

- Faculty and Courses are given as labels but machine learning required numerical data for processing
- Normalizing of inputs/outputs
- Splitting data for training and testing
- Finding perfect parameters for our model
- High training times
- Overfitting
- Presence of outliers and missing entries

## References

- [sklearn.ensemble.RandomForestRegressor](http://sklearn.ensemble.RandomForestRegressor)
- [CatBoostRegressor](https://catboost.ai/en/docs/concepts/python-reference_catboostregressor)
- [tf.keras.Sequential](https://www.tensorflow.org/api_docs/python/tf/keras/Sequential)
- [Stackoverflow](https://stackoverflow.com/)
- [Towards Data Science](https://towardsdatascience.com/)

## Contributors

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/yash-meshram">
          <img src="https://avatars2.githubusercontent.com/u/64315038" width="100;" alt="anupam"/>
          <br />
          <sub><b>Yash Meshram</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/akcgjc007">
          <img src="https://avatars2.githubusercontent.com/u/56300182" width="100;" alt="anupam"/>
          <br />
          <sub><b>Anupam Kumar</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Pradeep14saini">
          <img src="https://avatars2.githubusercontent.com/u/70324259" width="100;" alt="pradeep"/>
          <br />
          <sub><b>Pradeep Saini</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Robins87">
          <img src="https://avatars2.githubusercontent.com/u/98398708" width="100;" alt="robin"/>
          <br />
          <sub><b>Robin Kumar</b></sub>
      </a>
    </td>  
  </tr>
</table>
