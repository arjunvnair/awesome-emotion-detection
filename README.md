# Awesome Emotion Detection

An annotated bibliography of tutorials, papers, and demos for text-based automated emotion detection systems.

## Published Works 

### Computer Science / Artificial Intelligence

Here is a list of works that shed light on the field of emotion detection from a technical perspective.

- [Text-based emotion detection: Advances, challenges, and opportunities](https://onlinelibrary.wiley.com/doi/full/10.1002/eng2.12189)
Survey paper that discusses models of emotion and key datasets in the field.

#### Machine Learning Architectures

- [Multimodal and Multi-view Models for Emotion Recognition](https://aclanthology.org/P19-1095/)
This paper presents an emotion detection model that can align audio and text input together in a more natural manner than previous works.

- [Using millions of emoji occurrences to learn any-domain representations for detecting sentiment, emotion and sarcasm](https://arxiv.org/abs/1708.00524)
This paper from MIT presents DeepMoji, a model that can predict the most appropriate emojis for a piece of text and then use those emojis as a proxy for detecting sentiment, emotion, and sarcasm in text.

- [WASSA 2021 Shared Task: Predicting Empathy and Emotion in Reaction
to News Stories](https://aclanthology.org/2021.wassa-1.10.pdf)
Shared task in which a number of research teams compete to design the best model for predicting empathy and distress ratings

#### Datasets

- [Modeling Empathy and Distress in Reaction to News Stories](https://arxiv.org/abs/1808.10399)
A corpus of empathy and distress ratings for reactions to news stories.



- [IEMOCAP: interactive emotional dyadic motion capture database](https://link.springer.com/article/10.1007/s10579-008-9076-6)
A multimodal dataset of emotions with visual, audio, and text information.

- [EmotionLines: An Emotion Corpus of Multi-Party Conversations](https://arxiv.org/abs/1802.08379)
A corpus of emotion ratings for conversations, pulled from the T.V. show *Friends*.

- [MELD: A Multimodal Multi-Party Dataset for Emotion Recognition in Conversations](https://arxiv.org/abs/1810.02508) 
An extended version of EmotionLines that adds two new modes: visual and audio.

### Psychology

This is a list of relevant works from the field of psychology that are often cited in the above papers. It is highly recommended for one to be familiar with these works before attempting to conduct research in this field.

#### Models of Emotion

- [Universal Facial Expressions of Emotion](https://www.paulekman.com/wp-content/uploads/2013/07/Universal-Facial-Expressions-of-Emotions1.pdf)
Based off of his research on universal facial expressions across cultures, Paul Ekman proposed six basic emotions: joy, sadness, fear, anger, surprise, and disgust.

    - [Basic Emotions](https://onlinelibrary.wiley.com/doi/pdf/10.1002/0470013494.ch3)
In the third chapter of *Handbook on Cognition and Emotion*, Paul Ekman delves into the six basic emotions, what distinguishes them from other affective phenomena, and briefly discusses the evolution of his beliefs regarding them.

    - [Unmasking the Face: A Guide to Recognizing Emotions from Facial Clues”](https://psycnet.apa.org/record/1975-31746-000)
The first work where Ekman stated that the synergy of two or more basic emotions could lead to the emergence of more complex emotions. He later stated that he is no longer fully sure whether this is true.

    - [The Universality of a Contempt Expression: A Replication](https://www.paulekman.com/wp-content/uploads/2013/07/The-Universality-Of-A-Contempt-Expression-A-Replication.pdf)
In this paper, Ekman presents a seventh basic emotion - contempt - and presents his argument for why he believes this to be the case. While there is strong evidence to suggest that this is true, this seventh basic emotion has not been widely adopted by the affective computing community.

- [A circumplex model of affect](https://psycnet.apa.org/record/1981-25062-001)
Two-dimensional model of emotion that posits that emotions are defined by valence (how positive or negative an emotion is) and arousal (how activated a person is when experiencing it).

- [Evidence for a three-factor theory of emotions](https://www.sciencedirect.com/science/article/pii/009265667790037X)
An extended version of the circumplex of affect which adds a third dimension: dominance, which represents a person's sense of control over their surroundings when they are experiencing the emotion.

- [A general psychoevolutionary theory of emotion](https://www.sciencedirect.com/science/article/pii/B9780125587013500077)
Plutchik's wheel of emotions, which posits that there are eight emotions that exist in direct opposition to one another.

- [The Cognitive Structure of Emotion](https://www.researchgate.net/publication/202304316_The_Cognitive_Structure_of_Emotion)
The OCC model, which postulates that there are 22 emotions, including the six originally proposed by Ekman.

- [Distress and empathy: two qualitatively distinct vicarious emotions with different motivational consequences](https://pubmed.ncbi.nlm.nih.gov/3572705/)
This paper presents Batson's definitions of empathy and distress, what distinguishes the two from one another, and a scale used to measure the presence of the two in an individual at any given time.

## Demos

- [DeepMoji](https://deepmoji.mit.edu/)
- [IBM Watson Natural Language Understanding (NLU)](https://www.ibm.com/demos/live/natural-language-understanding/self-service/home)
- [IBM Watson Tone Analyzer](https://tone-analyzer-demo.ng.bluemix.net/?_ga=2.20122552.102902457.1633958604-1511044110.1630457514&_gac=1.19216714.1633958604.Cj0KCQjwwY-LBhD6ARIsACvT72PtNNUR4YWK71BZOiYKSV-A3lNeBfY-v95QOfZRwNksDLRb7BfMlQYaAnddEALw_wcB)
    - [IBM Watson Tone Analyzer for Customer Engagement](https://customer-engagement-demo.ng.bluemix.net/)

## Libraries

- [IBM Watson NLU Emotion Detection API](https://cloud.ibm.com/apidocs/natural-language-understanding?code=python#emotion)
- [NLTK VADER for Sentiment Analysis](https://www.nltk.org/_modules/nltk/sentiment/vader.html)

## Repositories

- [DeepMoji](https://github.com/bfelbo/DeepMoji)
- [IMS-EmoInt](https://github.com/koepermn/IMS-EmoInt)

