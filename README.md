# CS-6263-HW5

The following libraries were used, pandas, pytorch, scikit-learn
The dataset used was the financial phrasebank dataset
The Pre-trained model used was the distilbert-base-uncased
To run this code, install the libraries and run it google colab
 link to the dataset  https://drive.google.com/drive/folders/1Ei6brVx8fYs39O1XfhHZusoYxhNM-NMX?usp=drive_link
 Considering that I used distilbert-base-uncased for financial sentiment analysis,  BLEU Rouge-L BERTScore CodeBLEU couldn’t be directly evaluated
 So I did the evaluation using  precision    recall  f1-score   support best suited for a BERT analysis. 
 The evaluation showed the same results for both models, even though they were trained differently. 
