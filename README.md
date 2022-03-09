# TweCla
Tweet Classifier

![TweCla banner](https://i.imgur.com/jCH5JgT.png)

**Authors**: José Silva, Yuri Melissa, Jhan Rojas

## Objective

Classify tweets by basic emotions:
* joy
* sadness
* anger
* love
* surprise
* fear

## Dataset
The dataset used for the project can be found [here](https://www.kaggle.com/parulpandey/emotion-dataset?select=training.csv). In a nutshell, the dataset has two columns:
* text: Tweet content
* label: number representing an emotion

## Models
The models used in the project are:

* Deep Neural Network: Gives a map of probabilities for each emotion. The model used has five layers
  * Flatten
  * Dense layer with 32 nodes
  * Dense layer with 156 nodes
  * Dropout layer with 40% drop probability
  * Dense layer with 6 nodes

* Support Vector Machine
* Random Forest
* Logistic Regression (multibinomial for multiclasses)

## Links
The original **notebook** can be found [here](https://colab.research.google.com/drive/1tPJ3_ma_4Yjk9omr9lp4ur1tLeBTQytx?usp=sharing).

The **video** can be found [here](https://youtu.be/1TsA4zPwmjg).

The **repository** can be found [here](https://github.com/VashLT/TweCla).
