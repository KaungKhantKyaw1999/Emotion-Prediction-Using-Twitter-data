# Emotion-Prediction-Using-Twitter-data
This project is the extraction of the human emotions from the text. The extracted emotions are 'Happiness', 'Anger' and 'Disappointment'.
- "Just Scrap file" is the program that extract the text related with the three focused emotions from twitter. This program will create a csv file and save the raw data from the twiiter with their related emotions.
- "Just Clean File" is the program that clean raw data from the twitter. 6 steps of data pre-processing methods are applied.
- "My One" is the program that classifies the cleaned data to the emotions. RNN-LSTM with attention mechanism is applied in this program. Although this program is a classifier program. It can produce the results one time and difficult to reuse after closing the program. So, "Reload" program is created.
- "Reload" is the program that reloads the results of "My One" and able to use anytime. (*This program is created to resuse the classifier easily*)
