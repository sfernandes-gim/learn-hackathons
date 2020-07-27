
This solution was for a Hackathon for identification of Text from the image and then identifiying the sentiment . 
Was able to reach a rank of 139 with the solution. 

Accuracy: 35.63% (Top 3 %)

Problem_Statement: https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-predict-the-lowest-price/instructions/

Leaderboard : https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-predict-the-lowest-price/leaderboard/predict-the-lowest-price-8-9ffabe00/

Overall Solution process:

  Basically used Deep Learning Fast AI module with different transfer learning modules such as ResNet and DeepNet which allowed me to achieve the said accuracy

Stage 1:

    • Use of pytesseract to detect the text within images (not very user api hence had to try various alterations of this api)

Stage 2:

    • Use of pre trained sentiment models such as 
        1. vaderSentiment
        2. Flair
        3. TextBlob

Fine tuning of stage 1 could significantly improve the overall accuracy and further use of transfer learning to  train a sentiment model (say on Sentiment140 data) could improve the overall solution 




