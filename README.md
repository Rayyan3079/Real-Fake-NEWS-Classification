# PROJECT BRIEF

The project seeks to identify false news. We picked the dataset
from Kaggle. The dataset has five fields I.e., Id, Author name,
News Title, News, and the label (which tells whether the news if
true or false in 0 1 form). Based on the title and author, the
model determines if it is fake or real news. The project uses a

model of Logisitic Regression.

Firstly, data is cleaned by checking for empty fields and
replacing their null values with an empty space. News title and
author are combined to form a new column. On the content&#39;s
column, stemming is applied which returns the root word of
every word. String Is converted into list to remove stop words

from the text

Since our content column is in the form of text, we need to
convert it into numerical form so that we can feed the data in
our ml model to train it. To achieve that we applied Tfidf
Vectorizer on our content which converts the textual data into
numerical form then our data is split into training and test data
the testing size is 20 percent. Finally, we feed the training data
into our ML model which then is trained to predict whether the

news is true or false
