# Temporal Features in Sentiment Analysis (W266)

Abstract

With the growing usage of Internet spaces for discussion, shopping, and all sorts of interaction, lots of sentiment is now being expressed online. Strong sentiment can sway the opinions of others and lead to echo chambers during online interaction. In order to prevent this phenomenon, a reliable method of sentiment classification can be used to monitor sudden changes in sentiment. Previous work has suggested that the year some text is written is important to the accuracy of a sentiment classifier. The experiments conducted in this paper attempt to verify that hypothesis. The research will use several configurations of CNNs and BERT models to find if passing in the year a piece of text was written can improve the accuracy of a classifier. Ultimately, the temporal features did not prove much value, as the loss in accuracy for the classifiers was due to other characteristics of the text. 

Dataset - Amazon Reviews (http://deepyeti.ucsd.edu/jianmo/amazon/categoryFiles/All_Amazon_Review_5.json.gz)

Model - CNN, BERT & roBERTa

Descriptions of each of the files and folders are below:
1) CNN_Improved (1).ipynb -- Design, Training & implementation of CNN models
2) Bert_Implementation_NLP_V1.8_Final.ipynb(& HTML) -- Design, Training & implementation of BERT & roBERTa models.
3) Exploration EDA - EDA & splitting  the data set into training & test datasets.
4) Report (1).pdf - Final writeup of the research

Contributors 
Mrinal Chawla & Adi Khurana 
W266 (Natural Language Processing with Deep Learning) MIDS UC Berkeley
