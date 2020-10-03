# Emotion-Prediction-Using-Twitter-data
This project is the extraction of the human emotions from the text. The extracted emotions are 'Happiness', 'Anger' and 'Disappointment'.
- "Just Scrap file" is the program that extract the text related with the three focused emotions from twitter. This program will create a csv file and save the raw data from the twiiter with their related emotions. You can find the the resulted dataset from this program [here](https://www.kaggle.com/kosweet/raw-emotion-extraction-dataset-from-twitter).
- "Just Clean File" is the program that clean raw data from the twitter. 6 steps of data pre-processing methods are applied. The results of cleaned dataset can be seen [here](https://kaggle.com/kosweet/cleaned-emotion-extraction-dataset-from-twitter?utm_medium=social&utm_campaign=kaggle-dataset-share&utm_source=linkedin).
- "My One" is the program that classifies the cleaned data to the emotions. RNN-LSTM with attention mechanism is applied in this program. Although this program is a classifier program. It can produce the results one time and difficult to reuse after closing the program. So, "Reload" program is created.
- "Reload" is the program that reloads the results of "My One" and able to use anytime. (*This program is created to resuse the classifier easily*)
<table>
||Precision|	Recall|	F1-score|
|--|----------|:-------------:|------:|
|Disappointed |	99%|	96%	|98%|
Angry	93%	93%	93%
Happy	93%	93%	92%
</table>
