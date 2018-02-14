# Dataset
## 英文
1. CNN/Daily Mail  
    - 2015-Hermann et al. - Teaching machines to read and comprehend
    - 2016-Nallapati et al.-Abstractive text summarization using sequence-to-sequence rnns and beyond
    - Nallapati等人有定義評估的步驟，後續如要使用可以follow他們的研究
    - dataset contains 287,113 training examples, 13,368 validation examples and 11,490 testing examples. After limiting the input length to 800 tokens and output length to 100 tokens, the average input and output lengths are respectively 632 and 53 tokens.

1. the New York Times dataset (NYT)   
    - 2008 - Evan Sandhaus - The new york times annotated corpus. 
    - 目前僅有Paulus等人在2017年將此資料集用於 abstractive summarization
    
1. DUC-2004  
    - 2003 - Dorr et al. - Hedge trimmer: A parse-and-trim approach to headline generation.
    - DUC-2004 task can only generate very short summaries up to 75 characters, and are usually used with one or two input sentences.

## 中文
1. CIRB010-Chinese Information Retrieval Benchmark   
1. 



# evaluation


## 自動評價方法

1. ROUGE   
    - 被廣泛使用，為目前最主流的評價方法
    - ROUGE-n
    - ROUGE-L
    - ROUGE-SU    

    - Chin-Yew Lin. Rouge: A package for automatic evaluation of summaries. Workshop on Text Summarization Branches Out, Post-Conference Workshop of ACL 2004.
    - sumeval    
        - implemented in Python is a well tested & multi-language evaluation framework for text summarization. 
        - https://github.com/chakki-works/sumeval
    - pyrouge
        - https://pypi.python.org/pypi/pyrouge/0.1.3
        
1. Edmundson
1. METEOR metric
1. pyramid
1. BE方法
1. N-gram   
    Chin-Yew Lin and Eduard Hovy. Automatic Evaluation of Summaries Using N-gram Co-Occurrence Statistics. In Proceedings of the Human Technology Conference 2003 (HLT-NAACL-2003).
1. Automatic Evaluation of Machine Translation    
Kishore Papineni, Salim Roukos, Todd Ward, and Wei-Jing Zhu. BLEU: a Method for Automatic Evaluation of Machine Translation.

## 人工評價方法


## 參考文章：   
1. http://blog.csdn.net/lcj369387335/article/details/69845385
1. https://github.com/mathsyouth/awesome-text-summarization
