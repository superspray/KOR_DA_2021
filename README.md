# Data Augmentation for Korean text classification analysis

Data augmentation is a technique to increases the size and diversity of
training data. It works as a regularizer to reduce the overfitting in the model.
Unlike the field of computer vision, research on data augmentation in the
field of natural language processing has been limited. In particular, there are
very few studies related to Korean text data. This paper proposes augmentation techniques to improve classification performance of small-scale Korean
text data: 1) Data Augmentation with Spelling Correction (DA-SC), 2) Easy
Data Augmentation based on Part-Of-Speech tagging (EDA-POS), 3) Data
Augmentation with conditional Masked Language Modeling (DA-cMLM). The
experimental results showed that classification performance can be improved
with the application of the augmentation methods proposed in this paper.


## 1. DA-SC: Data Augmentation with Spelling Correction (맞춤법 교정을 통한 데이터 증강)
![DA_SC1](https://github.com/superspray/KOR_DA_2021/assets/48327038/ae96c2fe-bde3-493f-b676-b56ad5e0f87b)


--
## 2. EDA-POS: Easy Data Augmentation based on Part-Of-Speech tagging (형태소 분석 기반의 쉬운 데이터 증강)
![EDA1](https://github.com/superspray/KOR_DA_2021/assets/48327038/a6939762-f916-4f7b-b558-e8bb7a252458)

--
## 3. DA-cMLM: Data Augmentation with conditional Masked Language Modeling (조건부 MLM 기반의 데이터 증강)
![DA-CMLM1](https://github.com/superspray/KOR_DA_2021/assets/48327038/b5253002-03f0-4742-9d44-c90a4c165d89)
![DA-CMLM2](https://github.com/superspray/KOR_DA_2021/assets/48327038/6cd939af-e7ad-4d24-b879-0fdc4a55b71c)
![DA-CMLM3](https://github.com/superspray/KOR_DA_2021/assets/48327038/96a84ccb-35c0-417a-9ec9-43baab8d1e68)

--
## Reference (TBD)
--
* [EDA: Easy Data Augmentation Techniques for Boosting Performance on Text Classification Tasks](https://arxiv.org/pdf/1901.11196.pdf)
* [Low Resource Text Classification with ULMFit and Backtranslation](https://arxiv.org/pdf/1903.09244.pdf)


