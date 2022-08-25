# repo-info-bot

Steps to run the Bot :
------------------------------------
```
pip install rasa
```
To train the model: 
```
rasa train
```
View it in live server

```
rasa run --credentials ./credentials.yml  --enable-api --auth-token XYZ123 --model ./models --endpoints ./endpoints.yml --cors "*"
````
---------------------------------------
Data-Dumping Caution : 

- careful indentation
- No quotes in domain.yml
- no multiple lines for a single example in nlu.yml
- comments(#) does not work