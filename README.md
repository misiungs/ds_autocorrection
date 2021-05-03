# Natural language processing: spell checker
NLP project about news classification

<img src="https://github.com/misiungs/readme_images/blob/master/spellchecker.jpg?raw=true" alt="drawing" width="500"/>

# Problem
The goal of this repository is to provide an algorithm that will check whether each word in a sentence is correctly written.
For misspelled words it will propose a correct alternative.
Highest priority will be assigned for words that could be a misclicks on a QWERTY keyboard.

# Approach
All necessary components of spell checker are developed from scratch: a function to identify misspelled words based on a vocabulary, a candidate model which proposes word alternatives, a language model which chooses the most probable words from the candidate model and a spelling error model, that decide which mistake was most likely to happen.
In the spelling error model an improved Levenshtein distance is proposed which assigns lower weights to misclicks.

# Conclusions
Proposed spell checker works well and correctly identifies the keyboard misclicks.

