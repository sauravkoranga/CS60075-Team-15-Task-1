...........................................Group: 15............................................

.................................Team: iitkgp_cs60075_team15....................................

.........................course: Natural Language Processing CS60075............................

Group Members-

20CS60R10..............Jagdish Singh Samant
20CS60R46..............Deepanshi Pandey
20CS60R48..............Ashish kumar singh
20CS60R65..............Saurav koranga
20CS60R70..............Ram kishor Yadav

************************************************************************************************

Problem Statement:

LCP 2021 provides participants with an augmented version of CompLex, a multi-domain English dataset with sentences annotated using a 5-point Likert scale (1-5) (from very easy to very difficult). The task is to predict the complexity value of words in context.

LCP 2021 is divided into two sub-tasks:

    Sub-task 1: predicting the complexity score of single words;
    Sub-task 2: predicting the complexity score of multi-word expressions 

***********************************************************************************************

File Structure:
	-Dataset
		--Sub-task 1
			---lcp_single_test.tsv
			---lcp_single_trial.tsv
			---lcp_single_train.tsv
			---lcp_single_test_labels.tsv
		--Sub-task 2
			---lcp_multi_test.tsv
			---lcp_multi_trial.tsv
			---lcp_multi_train.tsv
			---lcp_multi_test_labels.tsv
	-code.ipynb
	-single_test_predictions.csv
	-multi_test_predictions.csv

*************************************************************************************************

Imported libraries:

numpy
pandas
sklearn
tensorflow
re
csv
nltk
spacy
warnings

*************************************************************************************************

TO run command on ubuntu terminal:
		
		ipython code.ipynb
		
		
	
