# English-to-Hinglish-Translation

HINGLISH-translations
# HINGLISH-translations

English text into Hinglish, a mixture of Hindi and English, while also converting difficult words and phrases into Hinglish. Used Helsinki-NLP/opus-mt-en-hi pre-trained translation model for translations.

## Installations
* pip install transformers
* pip install nltk
* Python 3.n

## Steps to run
1. Clone this repository or the HINGLISH Translation.ipynb file.
2. Complete the installations
3. Run all the cells one by one or Run All.
4. Enter the English sentence that you want to translated when input prompt appears.
5. Lastly, translation will be displayed.

## Overview
* The script starts by tokenizing the English text and identifying nouns using the nltk library.
* It then translates these nouns and the input text is translated using the Helsinki-NLP translation model.
* Next, the Hindi text is further converted to a more readable Hinglish version using a combination of consonant and vowel mappings.
* The script performs a noun-switching step to replace the translated nouns with their original English counterparts.
