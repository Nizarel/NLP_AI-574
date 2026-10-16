# Spell-checker
In this assignment we would like to build a Spell-checker. Given a text, the spell-checker detects spelling errors and fix them. The straightforward solution is to use as a machine translation system based on Transformers. The system translates noisy inputs with spelling and grammatical errors into errorless outputs.

To this end, we will use Dataset of Misspellings and Grammatical Errors to train a spell-checker. The dataset consists of hundreds of thousands of “typo” edits automatically harvested from GitHub. It is one of the largest datasets of spelling mistakes and their corrections.

The dataset is already tokenized based on common characters ("0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ .,!?’-"). In particular, whitespaces are replaced by “_” and any characters outside the common characters are replaced with “#”. The dataset includes the following files:

all.tsv (the original dataset before character tokenization)
train.tok.fr 
train.tok.en
dev.tok.fr
dev.tok.en
The suffix "fr" means that "noisy text before spelling correction" whereas the suffix "en" means "clean text after spelling correction."


Guidelines
Download the Dataset of Misspellings and Grammatical Errors  (gtc.zipDownload gtc.zip).
Build the spell-checker using transformers.
Write your code and save your Jupyter notebook as [FirstName - LastName]- Assignment1.ipynb
Export/Print your Jupyter Notebook as pdf.
Upload both your Jupyter notebook (.ipynb) and its printout (.pdf).
*Should you have questions, please contact me.