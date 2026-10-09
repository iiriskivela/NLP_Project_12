# pride and prejudice dialogue analysis

this project looks at talking lines from 10 main people in the book pride and prejudice. everything is in one jupyter notebook file.

you do not need to run the code to see the results. you can see all tables and plots just by clicking and opening project_12.ipynb here on github.

## how to run

### run in google colab
1. open google colab
2. upload the file project_12.ipynb
3. click runtime and then run all. the first block will install all tools and download the book.

### run on your computer
1. download this repository
2. install the tools in your terminal:
pip install nltk pandas numpy scipy matplotlib seaborn scikit-learn empath transformers sentence-transformers
3. open the notebook:
jupyter notebook project_12.ipynb

## tools and versions

this code uses python 3.10 or newer and these tools:

nltk==3.8.1
pandas==2.2.2
numpy==1.26.4
scipy==1.13.1
matplotlib==3.9.0
seaborn==0.13.2
scikit-learn==1.5.0
empath==0.89
sentence-transformers==3.0.1
transformers==4.42.0

## task list and report tables

all tasks are inside project_12.ipynb. each block has a comment like # task x: to show what it does.

- task 1 (cell 1 and 2): counts character names in the book and in talking parts. makes the table for character mentions and citations.
- task 2 (cell 3): gets dialogue lines and counts words, nouns, verbs, and adjectives. makes the table for word counts and parts of speech.
- task 3 (cell 4): counts new words over time using heaps law. makes the heaps law table and the word growth plot.
- task 4 (cell 5): counts helping verbs like can, must, would. makes the modal verbs table and the curve plot.
- task 5 (cell 6): finds the 5 most common words and checks similarity between people. makes the 5d table and similarity heatmap.
- task 6 (cell 7): finds 5 topics using lda. makes the top 10 words table and the lda heatmaps.
- task 7 (cell 8): checks 5 themes using sentence-bert. makes the bert topic table and heatmaps.
- task 8 (cell 9): compares all talking lines with bert vectors and compares bert with lda. makes the bert similarity table and difference heatmap.
- task 9 (cell 10): checks word topics using empath. makes the top 15 topics table and empath similarity heatmap.
- task 10 (cell 11): checks good, bad, and neutral feelings with sentiwordnet. makes the sentiment score table and triangle plots.
