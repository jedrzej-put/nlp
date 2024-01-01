# Natural language processing
- sentiment analysis - BERT and logistics regression 
    - [pretrained BERT](01_HUGGINGFACE_TRANSFORMERS/BERT/pretrained_BERT.ipynb)
    - [fine tuning BERT](01_HUGGINGFACE_TRANSFORMERS/BERT/fine_tuning_BERT.ipynb)
- [Named Entity Recognition - flair](02_NER/flair.ipynb)
- [byte-pair encoding](03_LINGUISTIC_ENGINEERING/tokenization.ipynb)
- [Bag of words, Bag of clusters, n-gram](03_LINGUISTIC_ENGINEERING/tokenization.ipynb)
- Neural models of sequence prediction
    - [CNN](04_EMBEDDING_CNN/classification.ipynb)
    - [RNN LSTM CRF](05_RNN_CRF/phrase_analysis.ipynb)



## Technologies
- torch 
    - embedding, rnn, linear, lstm, convolutional
    - dataset, dataloader
    - pad_sequence, pack_padded_sequence, pad_packed_sequence

- transformers - HUGGING FACE
    - AutoTokenizer
    - AutoModelForSequenceClassification
    - TrainingArguments
    - Trainer

- flair 
    - SequenceTagger
    - ModelTrainer
- torchtext
    - vocab
    - CoNLL2000Chunking
- sklearn
    - FeatureHasher
    - TfidfVectorizer
    - SVM
    - Logistics Regression
- nltk
    - word_tokenize