# paquora
The aim of this project is to devise a machine learning method to identify the personality traits of a user based on his/her answers on Q&amp;A website Quora.
Database Specs:
database name: nlp
username: nlp
password: nlppassword
Feature added
affin_data.py -> parses essays data 
AFINN is a list of English words rated for valence with an integer between minus five (negative) and plus five (positive). So I parsed essays data set and generated average valence of essays depending on the presence of words. Many essays didn't had any words so we will have to see.

