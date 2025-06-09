# Detecting Manipulation in Ukrainian Telegram: A Transformer-Based Approach to Technique Classification and Span Identification
## Abstract
The Russia-Ukraine war has transformed social media into a critical battleground for information warfare, making the detection of manipulation techniques in online content an urgent security concern. This work presents our system developed for the UNLP 2025 Shared Tasks, which addresses both manipulation technique classification and span identification in Ukrainian Telegram posts. In this paper, we have explored several machine learning approaches (LR, SVC, GB, NB) , deep learning architectures (CNN, LSTM, BiLSTM, GRU hybrid) and state-of-the-art multilingual transformers (mDeBERTa, InfoXLM, mBERT, XLM-RoBERTa). Our experiments showed that fine-tuning transformer models for the specific tasks significantly improved their performance, with XLM-RoBERTa large delivering the best results by securing 3rd place in technique classification task with a Macro F1 score of 0.4551 and 2nd place in span identification task with a span F1 score of 0.6045. These results demonstrate that large pre-trained multilingual models effectively detect subtle manipulation tactics in Slavic languages, advancing the development of tools to combat online manipulation in political contexts.

## Schematic process for Manipulation Technique Classification
![](https://www.googleapis.com/download/storage/v1/b/kaggle-forum-message-attachments/o/inbox%2F19186184%2F2f9bb850e055efa6b533d937d4d26377%2FCLassification%20Camera%20Ready.png?generation=1749467697044997&alt=media)

## Schematic process for Manipulative Span Identification
![](https://www.googleapis.com/download/storage/v1/b/kaggle-forum-message-attachments/o/inbox%2F19186184%2Fea5d8df339bbf7692e35dc405f462047%2FSPAN.drawio.png?generation=1749467779518815&alt=media)

### Dataset used in Technique Classification Subtask: [link](https://github.com/borhanitrash/Detecting-Manipulation-in-Ukrainian-Telegram/tree/main/Dataset/Technique%20Classification)

### Dataset used in Span Identification Subtask: [link](https://github.com/borhanitrash/Detecting-Manipulation-in-Ukrainian-Telegram/tree/main/Dataset/Span%20Identification)

### Source code of our best approch for Technique Classification Subtask: [XLM RoBERTa-large](https://github.com/borhanitrash/Detecting-Manipulation-in-Ukrainian-Telegram/tree/main/Technique%20Classification)

### Source code of our best approch for Span Identification Subtask: [XLM RoBERTa-large](https://github.com/borhanitrash/Detecting-Manipulation-in-Ukrainian-Telegram/tree/main/Span%20Identification)

## Pretrained Model used and their Hugging Face model card link:

### [mDeBERTa V3 Base](https://huggingface.co/microsoft/mdeberta-v3-base)

### [InfoXLM Large](https://huggingface.co/microsoft/infoxlm-large)

### [XLM-RoBERTa large](https://huggingface.co/FacebookAI/xlm-roberta-large)

### [BERT multilingual base](https://huggingface.co/google-bert/bert-base-multilingual-cased)

### [Ukr-Roberta Base](https://huggingface.co/youscan/ukr-roberta-base)

### [mt5-base](huggingface.co/google/mt5-base)




