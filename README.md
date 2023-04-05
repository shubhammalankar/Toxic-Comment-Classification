# Toxic-Comment-Classification

We are using the **LSTM, LSTM-CNN** models in this project to classify toxic and non-toxic comments and the performance of the both the models.

## Toxic Classes:
    Severe toxic
    Obscene
    Threat
    Insult
    Identity hate


## Pre-Processing<br>

•	Text-Cleaning:<br>
&nbsp;&nbsp;&nbsp;&nbsp;a.	We apply two processing methods to texts<br>
&nbsp;&nbsp;&nbsp;&nbsp;b.	Make all alphabet lower case <br>
&nbsp;&nbsp;&nbsp;&nbsp;c.	Remove special token and deal with postfix<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    Ex: “Hi How’re You – hi how are you”<br>
•	Tokenization:<br>
&nbsp;&nbsp;&nbsp;&nbsp;a.	Separates sentences into words<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ex: hi how are you – “hi” “how” “are” “you”<br>
•	Encoding:<br>
&nbsp;&nbsp;&nbsp;&nbsp;a.	Mapping the word to an ID<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ex: “hi how are you” – [1,2,3,4]<br>


## LSTM Architecture
![image](https://user-images.githubusercontent.com/32535576/230226994-db805ee7-f821-48a5-8c88-def940ea163c.png)

## LSTM MODEL SUMMARY
![image](https://user-images.githubusercontent.com/32535576/230227164-98ae2774-209e-4c60-9e09-f5200020e6a8.png)

## LSTM-CNN Architecture
![image](https://user-images.githubusercontent.com/32535576/230227416-6743c1ec-9024-45bc-86bb-b829848edd08.png)

## LSTM-CNN MODEL SUMMARY
![image](https://user-images.githubusercontent.com/32535576/230227464-73e9c48c-635d-4a42-8715-79881e4d62e2.png)

## MODEL PERFORMANCES

<img src="https://user-images.githubusercontent.com/32535576/230227530-d5b80e43-0cf5-4de2-844e-3a87a93b4d78.png" width="400" height="150"/>


