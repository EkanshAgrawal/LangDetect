# LangDetect: Language Detection using Natural Language Processing
LangDetect uses a language detection dataset, which has different types of languages in it, and uses a hybrid approach, which combines the best rule-based and ML approaches with natural language processing, machine learning, and human input and recognizes the language of the given data. We used LinearSVC, RandomForestClassifier and Logistic Regression to train the model.

# Requirements #
Make sure you have the following software installed:
<ul>
  <li>Python (version >= 3.6)</li>
  <li>Jupyter Notebook</li>
  <li>Python libraries (NumPy, Pandas, Scikit-learn, RE, String, Math, NLTK)</li>
</ul>

# Dataset #
The dataset has around 10 million+ rows and contains data about 150 languages. We have only selected 12 languages that are actively spoken in India. The 12 languages selected are:
<ul>
  <li>Bengali: ben</li>
  <li>English: eng</li>
  <li>Gujarati: guj</li>
  <li>Hindi: hin</li>
  <li>Kannada: kan</li>
  <li>Malayalam: mal</li>
  <li>Marathi: mar</li>
  <li>Nepali: nep</li>
  <li>Oria: ori</li>
  <li>Punjabi: pan</li>
  <li>Sanskrit: san</li>
  <li>Tamil: tam</li>
  <li>Urdu: urd</li>
</ul>



# Results #
The dataset is pre-processed and plotted based on the language it belongs. After that, data is trained and unigram, bigram, up to 10chargram are applied. Then various ML algorithms like Random Forest Classifier, Linear SVC, and Logistic Regression model are applied on the training dataset. Finally, the language of input data is detected. A comparison of the accuracy of different models is also shown. 

By using the hybrid approach, the model performance is enhanced and is expected to achieve language detection accuracy of around 93%.
