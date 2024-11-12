# Youtube-8M

Youtube Category Classification is Machine Learning based project which focused on classification algorithms and their usage for finding category (genere) of the videos. For better Outcome not only one but several algorithms are being used, among them better Outcome will be considerable. For training part, we have used 8 million data entries.

This project has been developed while I was doing my bachelor(2021).

![youtube](https://github.com/user-attachments/assets/436efff7-78c8-457e-a49c-86d38ebaa2da)


## Steps and Models used

- Scrap the data from youtube.
- Preproess the data
- I have applied two different kinds of model such as LSTM, BiLSTM, Logistic Regression, Random Forest
- We have done some feature engineering as well by combining the title of the video with the description part of the video
- We are getting optimal results when using LSTM.
- You can check the results, in different notebook files.

## File Description

- youtubedata.csv is containing the raw dataset obtained from youtube, cleaned_data.csv is containing the cleaned dataset after performing the data preprocessing. For data preprocessing you can see Data Cleaning.ipynb
- Modeling with Title.ipynb is containing the classical machine learning models using Title only.
- Modeling with Title + Description.ipynb is containing the classical machine learning models by featurizing the title+description.
- Modeling with Title + Description using LSTM.ipynb is containing the LSTM model for classification.
