# TextMoodClassification
This is a text sentiment classification project.   
It is a short text classification problem and there are two classes: positive sentiment and negative sentiment.  
In the .tsv files, 'id' is unique for each text,  'sentiment' is sentiment classes.(positive is 1, negative is 0)   
'review'  is the text.   
**labeledTrainData.tsv**：Training data, which has 24500 texts and each text has its label.   
**unlabeledTrainData.tsv**：Training data, which has 49000 texts, but each text has no label. This dataset could be used to unsupervised learning.   
**testData.tsv**：Test data, which has 22000 texts.(Output the probability of each test text using trained model, and submit result as submission.txt)
