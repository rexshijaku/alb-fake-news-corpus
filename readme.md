# Albanian Fake News Corpus

Hello! Thank you for using our corpus!

In this repository you may find following informations :

 - ``full_texts`` folder, which contains the full texts, as collected from their websites. Inside this folder, there are 2 more folders:

   - ``fake`` folder: it contains the collected fake news;
   - ``true`` folder: it contains the collected true news;
   - ``fake-meta-information`` folder: it contains the metadata information of each fake news;
   - ``true-meta-information`` folder: it contains the metadata information of each true news;
   - ``fake-pos`` folder: it contains the POS tagged fake news;
   - ``true-pos`` folder: it contains the POS tagged true news;

   The files in the fake and true metadata information folders follow the following model (line by line):

          date and time of publication
		  facebook link
          web page link
          number of tokens
          number of words without punctuation
          number of words in upper case
          average word length
          number of characters
          number of letters in upper case
          number of verbs
          number of subjuntive 
          number of imperative verbs
          number of nouns
          number of adjectives
          number of adverbs
          number of pronouns
          number of modal verbs (mainly auxiliary verbs)
		

   To find the aligned true and fake news pairs is very simple, as they are equally numbered/named inside their folders.

Finally, this corpus is used in our work ``Albanian Fake News Detection`` which was published on ``The ACM Transactions on Asian and Low-Resource Language Information Processing (TALLIP)`` and you may find it [here](https://dl.acm.org/doi/10.1145/3487288).
