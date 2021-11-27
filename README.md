# Reducing repetition in convolutional abstractive summarization
https://doi.org/10.1017/S1351324921000309

Journal of Natural Language Engineering

## Abstract
Convolutional sequence to sequence (CNN seq2seq) models have met success in abstractive summarization. However, their outputs often contain repetitive word sequences and logical inconsistencies, limiting the practicality of their application. In this paper, we find the reasons behind the repetition problem in CNN-based abstractive summarization through observing the attention map between the summaries with repetition and their corresponding source documents and mitigate the repetition problem. We propose to reduce the repetition in summaries by attention filter mechanism (ATTF) and sentence-level backtracking decoder (SBD), which dynamically redistributes attention over the input sequence as the output sentences are generated. The ATTF can record previously attended locations in the source document directly and prevent the decoder from attending to these locations. The SBD prevents the decoder from generating similar sentences more than once via backtracking at test. The proposed model outperforms the baselines in terms of ROUGE score, repeatedness, and readability. The results show that this approach generates high-quality summaries with minimal repetition and makes the reading experience better.

## Data and Code
Coming soon
