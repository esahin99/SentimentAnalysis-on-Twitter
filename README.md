# Sentiment Analysis on Twitter
In this project, I designed a graphical user interface for a twitter account that analyzes the desired number of tweets in a specified time period according to 5 different moods. We store information such as ID, user name and tweet text of the tweet data, both in a database and in an excel file. In addition, the data of any twitter account can be automatically retrieved as a daily.

## Install
```
pip install -r requirements.txt
```
## Run
```
python code/main.py
```
## First Page
Since I analyzed my university's twitter account, I put a photo of my university on the login page. In the upper right part of the same screen, there are buttons that direct me to my own linkedin and github account.

![1](https://user-images.githubusercontent.com/61835738/175532808-f443ffe1-87b0-4ed8-a719-7202378de6f1.PNG)

## Second Page
On page 2, the data belonging to the twitter account that we want to analyze is retrieved and this data is trained using machine learning. For this, we first write the username of the account to be analyzed, the date from which we want to analyze and the number of tweets we want to analyze, and save the requested information in a database with the submit button. then machine learning is started with the start training button and the data is trained. After the training is completed, the accuracy rate and 2 related graphics are displayed on the screen.

![2](https://user-images.githubusercontent.com/61835738/175536295-1f6a49d0-d4f0-447d-abb1-e70f4c480e34.PNG)

![3](https://user-images.githubusercontent.com/61835738/175536398-40717cd1-1179-4163-b4a1-b80f3f563e58.PNG)

## Third Page

On the 3rd page, we show the data we have taken and trained with machine learning with an excel table

![4](https://user-images.githubusercontent.com/61835738/175536868-75037919-6e95-4ba6-baae-b563bb8e7b8b.PNG)

![5](https://user-images.githubusercontent.com/61835738/175536877-71889c82-92b0-469b-bfe0-9344e73a044d.PNG)

## Fourth Page

On the 4th page, the sentences entered randomly are classified as positive or negative.

![6](https://user-images.githubusercontent.com/61835738/175537247-9dfe7d5a-0c64-4370-8e4b-38ac6fbad19b.PNG)

![7](https://user-images.githubusercontent.com/61835738/175537263-f12db8c8-1731-49ff-83c7-9b6f107e099c.PNG)



