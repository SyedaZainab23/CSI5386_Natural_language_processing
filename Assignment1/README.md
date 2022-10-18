                            *********************************   PART 1   *****************************************


- The folder "PART1" contains all the essential files for the PART 1 of the assignment.

- NLP_Assignment_Part1.ipynb contains the code

- We used google collab because jupyter notebook crashed because of the huge dataset

- For viewing the output, any browser can be used


- Input Files:

    'merged.txt'  Contains all 510 files merged together

    'stopwords.txt' Contains the stopwords provided for the assignment 


- NOTE: Without these files, you will get an error while running "NLP_Assignment_Part1.ipynb"

(Because the data to be analyzed and the stop words to be eliminated are in these files)


- Output Files:

    'output.txt' contains all the tokens

    'tokens.txt' contains a list of all tokens and their frequencies



----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

                            ***********************************     PART 2   ***************************************


-Dataset : sts2016-english-with-gs-v1.0

This package contains test sets with gold standard labels for the 2016 Semantic Textual Similarity (STS) shared task.



Input Files

    STS2016.input.answer-answer.txt

    STS2016.input.headlines.txt

    STS2016.input.plagiarism.txt

    STS2016.input.postediting.txt

    STS2016.input.question-question.txt


Gold Standard Files:

    STS2016.gs.answer-answer.txt

    STS2016.gs.headlines.txt

    STS2016.gs.plagiarism.txt

    STS2016.gs.postediting.txt

    STS2016.gs.question-question.txt




Evaluation Script:

    Correlation-noconfidence.pl





Code: The Code folder contains all sentence embedding models we used.

    Doc2vec.ipnyb 

    simcse.ipnyb

    InferSent.ipnyb

    roberta.ipnyb

    sbert_mpnet.ipnyb

    universal_sentense_encoder.ipnyb




Open google collab upload the dataset files and the .ipnyb notebook. Change the readline file and execute to see the output list of cosine similarities.

** To run InferSent.ipnyb models.py should also be uploaded to collab



Dataset Output Folder:

    The cosine similarity list files and the gold standard files are stored under this folder.

    To execute the perl script and get the persson coeff run the below command:

    /correlation-noconfidence.pl STS2016.gs.<dataset>.txt  <model>.txt


