# ChatBot-Nebrija
ChatBot of Nebrija University (Final Graduate Proyect)


## Ubuntu Install and Run

### Download the code 

```
git clone https://github.com/sergiogar99/ChatBot-Nebrija.git
```

### Requirements 

** Python 3 and pip 3** 
```
sudo apt update
sudo apt install python3-dev python3-pip
```

** Rasa Open Source**
```
pip3 install -U pip
pip3 install rasa
```

** Dependencies for spaCy**
```
pip3 install rasa[spacy]
python3 -m spacy download es_dep_news_trf
python3 -m spacy link es_dep_news_trf
```






