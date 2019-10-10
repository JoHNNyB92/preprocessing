# Preprocessing

The following page in wikipedia is the source we are going to use
• Artificial neural network:
https://en.wikipedia.org/wiki/Artificial_neural_network.
We pre-process the Web page, extract its text and answer the following questions:
1. What is the word count and vocabulary of this Web page?
2. How many sentences are contained in the page?
3. What is the lexical diversity of the page?
4. What are the 5 most common lexical categories (parts of speech)?
5. What are the 10 most common unigrams, the 10 most common bigrams? (please exclude
stopwords, using the nltk.corpus.stopwords('english') list)
6. How many nouns are in the page?


Bonus:
Provide a Comma Separated File (CSV) with the following requirements:
• It contains a single row, with 3 cells.
o The first cell must contain the given name of the student in Greek.
o The second cell must contain the surname of the student in Greek.
o The third cell must contain the string “Μεταπτυχιακό στην Επιστήμη Δεδομένων”, including
quotes.
• The provided file must open in Microsoft Excel, only with a single click from the Windows File explorer,
without any further action required by the user. The target operating system is Windows 10, with
Greek localisation (Appearance and Local settings).
• The provided file must be encoded in UTF-8.
