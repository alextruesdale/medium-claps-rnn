<a href='http://quantlet.de/'>
  <img src='https://github.com/alextruesdale/medium-claps-rnn/blob/master/repository_media/HU.png' alt='HU logo' title='HU' align='right' height='80' />
</a>

# HU Kaggle Comp. – Medium Claps Prediction

For the Advanced Data Analtics for Mgmt. Support course at the chair of Information Systems, Humboldt-Universität zu Berlin, students participated in an [in-class data science competition on Kaggle](https://www.kaggle.com/c/adams-nlp-ss19/). The target was to predict, using ~279.5k rows of labelled data, the count of claps an article has received on the publishing platform Medium.com. Features in the data were limited to basic details about a given article: publish date; author; publisher; number of words; and, foremost, the article and teaser text, respectively. The regression task of predicting claps was performed using a recurrent neural network (specifically GRU), in order to capture the sequential nature of text data and thereby account for contextual meaning in an article.

In preparation of the text as input for the RNN, natural language processing methods were employed to unify the heterogeneous article structures / idiosyncrasies. In testing and Kaggle submissions, accuracy was assessed via mean squared error (MSE).

Final code can be seen in the file 'medium_net.ipynb'. All code was written in Python within the Jupyter Notebook environment via Google's Colab env., offering free, base-level cloud computing resources (incl. GPU access).

My efforts earned me position 3 of 20 in the class.

<img src='https://github.com/alextruesdale/medium-claps-rnn/blob/master/repository_media/kaggle.png' alt='Kaggle Competition' title='Kaggle Competition' align='center' width='830' />
