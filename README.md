# News-Summarizer-with-Pegasus

Text summarization is one of the most useful applications of Natural Language Processing, since it can be used by the masses on a daily basis. Abstractive Text summarization can produce shortened and simplified summaries of large text documents. News Summarization is one task where this technology can be applied quite conviniently, and with the advent of Large Language Models (LLMs), this task can be done quite easily and reliably. 


## Pegasus

Pegasus is a Transformer with a self-supervised pre-training method called Gap-Sentence Generation. In this method, a paragraph is taken and alternate sentences in the paragraph are removed and concatenated. The remaining sentences of the original para, now concatenated as well, are used as inputs, while the removed (concatenated) sentences are used as output in the training process. Basically model is being made to figure out missing sentences.


![image1](https://github.com/RohanBh23/News-Summarizer-with-Pegasus/assets/78695257/3c64f82c-8d38-4a36-99eb-760ce0c33c74)

