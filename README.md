# Next-Word-Predictor

Methodology
1. Preprocessing involves removing non-alphanumeric letters and converting words to lowercase in datasets like the Brown corpus.
2. Bigrams are created from the processed data to capture sequences of words.
3. Frequency Calculation: The frequency of each bigram is computed to generate a frequency distribution.
4. The prediction strategy involves considering all bigrams that begin with the input word when predicting the next word.
5. The computer computes the likelihood of each possible succeeding word by analyzing its frequency in the dataset.
6. The word with the highest probability is chosen as the projected next word. If no bigrams are detected for the input word, the computer resorts to guessing one of the most frequently occurring terms in the dataset.
7. This method guarantees that forecasts rely on the statistical probability of word sequences, enabling precise predictions of the following word.word.

The project showcases a basic method of language modeling by utilizing bigrams and probabilistic methods. The code accurately forecasts the following word by utilizing the NLTK library and a dataset Brown corpus, through statistical analysis of word sequences. The project, although is straightforward in its execution, acts as a foundation for comprehending more complex natural language processing tasks and applications.
