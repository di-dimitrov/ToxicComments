# Toxic Comment Classification



## Цел на проекта


Да се подобри комуникацията в интернет пространството. Трябва да се построи модел, който да е класифицира даден коментар според зададени категории - toxic, insult… Данните за модела са събрани от дискусионните страници на Wikipedia. Реших да работя с keras(Tensorflow backend), защото вече имам повече опит с него от Tensorflow и бях притиснат от време.


## Процес на работа

### Първо проучих няколко от решенията предоставени от участници в състезанието в kaggle. Това, което ми подбуди интереса беше GloVe embeddings, защото не бях запознат с тях. След това влязох в keras документациите и намерих: (https://blog.keras.io/using-pre-trained-word-embeddings-in-a-keras-model.html).

### Запознах се с GloVe и реших да го използвам като baseline. Използвах кода за зареждане на данните от предоставения линк. Използвах glove.840B.300d.zip - 2.2M vocabulary, 300 dimensional embedding vectors, 840B tokens.


### Имплементирах 


https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge



