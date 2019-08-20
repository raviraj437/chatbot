# i have done on project on e governemtn scheme chatbot which gives better ubderstanding of e governemr=ent scheme pm jan dhan yojana ,
p m rogar yojana ,india startup loan for backward.
i have extract  dataset for different scheme from different governenent website.
for scheme there is two colum like first one question for scheme like rate of interest ,nature etc, and in another colmn there is approparaue answer
for particular question.
we have created different dataset for different scheme.
we have converted the schemes name into vecotr form .after that we tokenize allscmeme name vector from nltk lib tokenizer through function.
after the we call uniaque function which deleted all same lettre of scmhemes name tokenzier.
then we matrix of size of no of schems * length of tokensizer after the call unqiue functio.
then itretae through the matrix for each string in a row .i place 1 in 1.
then we converted the question in vecotr for and tozier by tokenzier(list).
after we use fucntion which is have synomes replace by orignial name.
after cosine similarity with question and with the matrix .
cosine with hight value row index give the csv file for scheme is asked.
then we extract the csv file.
after remove stop words from question and then remove the words which simlar previous tokensizer created with schemen name.
again we make tokenize the column of csv file and remove stop word.
call unique which deleted the coommon word.
we amke matrix of row = row colmn 1 and vector which comes after the tokenzie it.
then we again same procedurer for give 1 for matching words.
then we make cosine similarity with question and highest value gives the index of answer approapraite.
