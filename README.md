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

\begin{table}[h]
   	\centering
	\caption{Sentences generated with DA-SC.}
	\resizebox{\linewidth}{!}{
	
\begin{tabular}{ll}     \toprule

\multicolumn{1}{c}{\textbf{Original}}                 & \multicolumn{1}{c}{\textbf{Corrected}}            \\ \midrule
최고의 2d영화가 아닌가싶으다....!                             & 최고의 2d 영화가 아닌가 싶다....!                            \\
그래픽똥이네용그래픽이참ㅋㅋㅋㅋㅋ영화발로만드나                          & 그래픽 똥이네요 그래픽이 참ㅋㅋㅋㅋㅋ 영화 발로 만드나                    \\
국산영화봅시다 다세포봐요 국산물산장려운동                            & 국산 영화 봅시다 다세포 봐요 국산 물산장려운동                        \\
정말 이렇게밖에 못만드나? 편집이라도 좀 잘하지.                       & 정말 이렇게밖에 못 만드나? 편집이라도 좀 잘하지.                      \\
잼있네여 ㅎㅎ 꽃놓고 가요$\sim$$\sim$                        & 재밌네요 ㅎㅎ 꽃 놓고 가요$\sim$$\sim$                       \\
돈내고봣는데 보다보다 못봐줘서 꺼버렷다 진짜 ........................ & 돈 내고 봤는데 보다보다 못 봐줘서 꺼버렸다 진짜 ..................... \\ \bottomrule
\end{tabular}}
\label{table:31}
\end{table}

--
## 2. EDA-POS: Easy Data Augmentation based on Part-Of-Speech tagging (형태소 분석 기반의 쉬운 데이터 증강)

--
## 3. DA-cMLM: Data Augmentation with conditional Masked Language Modeling (조건부 MLM 기반의 데이터 증강)


--
## Reference (TBD)
--
* [EDA: Easy Data Augmentation Techniques for Boosting Performance on Text Classification Tasks](https://arxiv.org/pdf/1901.11196.pdf)
* [Low Resource Text Classification with ULMFit and Backtranslation](https://arxiv.org/pdf/1903.09244.pdf)


