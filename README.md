## TypeSQL

TypeSQL: Knowledge-based Type-Aware Neural Text-to-SQL Generation

#### Environment Setup

Python 3 and Torch 1.0

#### Download Data and Embeddings

1. Download the train data at [Google Drive](https://drive.google.com/file/d/1CGIRCjwf2bgmWl3UyjY1yJpP4nU---Q0/view?usp=sharing).
The data already contains the type info.

2. Download the pretrained [Glove](https://nlp.stanford.edu/data/wordvecs/glove.42B.300d.zip) and the [paraphrase embedding](https://drive.google.com/file/d/1iWTowxEG1-KZyq-fHP6cb6dNqMh4eHiN/view?usp=sharing) `para-nmt-50m/data/paragram_sl999_czeng.txt`.

#### Eval Result


| parameter | dev query-match acc | test query-match acc| dev execution acc | test execution acc|
| ------ | ------ | ------ | ------ | ------|
| db_content=1 | 0.785 | 0.738 | 0.844 | 0.817 |
| db_content=0 | 0.659 | 0.651 | 0.722 | 0.718 | 

#### For Understanding

table info:
![table](https://github.com/guotong1988/TypeSQL-python3/blob/master/doc/table.png)
question info:
![question](https://github.com/guotong1988/TypeSQL-python3/blob/master/doc/question.png)

#### Acknowledgement

https://github.com/taoyds/typesql
