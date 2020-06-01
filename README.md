# Natural Language Processing- Word Sense Disambiguation with NLTK
## Goal
The goal is to use the Lesk algorithm provided by Python NLTK Word Sense Disambiguation (WSD)
module to find the correct definition (i.e. WordNet’s synset definition) of the word
“rock” in the following sentences:

➢ “A rock is classified according to characteristics such as mineral and chemical composition”

➢ “Queen are a British rock band formed in London in 1970”.
## Results

Using Lesk algorithm we got a 50% accuracy. For the first example sentence it could not identify the most appropriate definition but for the second example sentence it could find the correct definition of "rock".

I also tried to use Lesk algorithm after removing the stopwords from the sentences but it is not the ideal thing to do as Lesk algorithm is designed to consider stopwords.

## Acknowledgements
This assignment was provided by Otto von Guericke University, Magdeburg.
