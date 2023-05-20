# Hinglish CodeMix Generation

The project focuses on code mix generation, which involves the practice of mixing two or more languages in a single sentence. This phenomenon is particularly prevalent in user-generated content on social media and website comments. The challenge lies in adapting natural language processing (NLP) models, originally designed for monolingual data, to effectively handle code-mixed text. 

The project aims to address this challenge by developing a code mix generation model using statistical and neural algorithms. The objective is to generate fluent and natural mixed-language text, enabling applications in machine translation, sentiment analysis, and text classification.


#### Dataset
We have used the English - Hinglish (ENG - HINGLISH) dataset provided by [LINCE](https://ritual.uh.edu/lince/datasets) . The dataset is useful for training and evaluating models for cross-lingual text classification, cross-lingual sentiment analysis, and other multilingual NLP tasks. 


#### Models
- hinglish-generation-ngram notebook contains generic ngram language model trained on the dataset. It uses LSTM network with masked inputs to train the language model for codemix generation
- hinglish-generation-transformer notebook uses pre-trained hinglish sentence transformer to predict further words
- bert_finetune_transformer notebook trains a masked language model using BERT base transformer for codemix language generation.

#### Instructions to run the code
- Create a new virtual environment
`python3 -m venv venv`
- Activate the virtual environment
- Install requirements.txt using following command
`pip install -r requirements.txt`
- Run each notebook Individually