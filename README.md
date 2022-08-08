# SummerProgect
My NLP research, trying to identify emotions in social media posts.


## The GoEmotions dataset is used

GoEmotions is a corpus of 58 thousand marked-up comments from Reddit, with an annotation of 27 categories of emotions or neutral.
* Number of examples: 58,009.
* Number of categories: 27 + neutral.
* The maximum length of the text is 30 characters.
* Language: English.

Categories of emotions include: anticipation, fun, anger, irritation, approval, concern, confusion, curiosity, desire, disappointment, disapproval, disgust, embarrassment, excitement, fear, gratitude, grief, joy, love, nervousness, optimism, pride, awareness, relief, remorse, sadness, surprise.


## Text preprocessing
1. Lowercase translation
2. Normalization of links, mail, numbers
3. Annotation of caps, long words, repetitions, underscores, censorship
4. Word correction
5. Annotation of emoticons
6. Tokenization


## Bert
The "light" model “bert_en_uncased_L-12_H-768_A-12" is used.

- L-12 : 12 hidden layers
- H-768 : 768 neurons (dimension of the hidden layer)
- A-12 : 12 attention modules

The best result for 6 emotions according to Ackerman and neutral accuracy 59.3%, Macro F1 = 0.493
