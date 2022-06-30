# Music-Genre-Classification


Our goal in this project is to implement an algorithm that reduces the number of data points we 
need to work with and build a classifier (KNN and ANN) using a set of 1000 music samples 
(blues(100), classical(100), country(100), disco(100), hiphop(100), jazz(100), metal(100), 
pop(100), reggae(100), rock(100)). In this we developed an automated music genre 
categorization model system. The initial stage was to identify good traits that clearly defined the 
genre's borders. The GTZAN music dataset was preprocessed and multiple time-frequency 
domain parameters such as MFCC vector, chroma waves, spectral rolloff, spectral centroid, and 
egg crossing rate were obtain to find the feautre vector for each music sample. Further, The 
music sample features were given to train the supervised learning algorithms such as KNN and 
ANN with two separate dataset such as GTZAN and MFCC. GTZAN contain labeled audio files 
of different music types and genres whereas, MFCC dataset contain labeled numeric feature 
vectors for different music types. Finally, the trained models were tested using the train data sets 
from both the categories and performance of each was evaluated. KNN provided the maximum 
accuracy of 55% using GTZAN and 87% using MFCC dataset. However, the classification 
accuracy of ANN using GTZAN dataset remained lower (56%)
