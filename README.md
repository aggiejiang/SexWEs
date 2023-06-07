# SexWEs

Aiqi Jiang, Arkaitz Zubiaga. SexWEs: Domain-Aware Word Embeddings via Cross-lingual Semantic Specialisation for Chinese Sexism Detection in Social Media. In Proceedings of the 17th International AAAI Conference on Web and Social Media (ICWSM 2023).

Please check our paper for more details [here](https://ojs.aaai.org/index.php/ICWSM/article/view/22159).

## Abstract

The goal of sexism detection is to mitigate negative online content targeting certain gender groups of people. However, the limited availability of labeled sexism-related datasets makes it problematic to identify online sexism for low-resource languages. In this paper, we address the task of automatic sexism detection in social media for one low-resource language -- Chinese. Rather than collecting new sexism data or building cross-lingual transfer learning models, we develop a cross-lingual domain-aware semantic specialisation system in order to make the most of existing data. Semantic specialisation is a technique for retrofitting pre-trained distributional word vectors by integrating external linguistic knowledge (such as lexico-semantic relations) into the specialised feature space. To do this, we leverage semantic resources for sexism from a high-resource language (English) to specialise pre-trained word vectors in the target language (Chinese) to inject domain knowledge. We demonstrate the benefit of our sexist word embeddings (SexWEs) specialised by our framework via intrinsic evaluation of word similarity and extrinsic evaluation of sexism detection.  Compared with other specialisation approaches and Chinese baseline word vectors, our SexWEs shows an average score improvement of 0.033 and 0.064 in both intrinsic and extrinsic evaluations, respectively. The ablative results and visualisation of SexWEs also prove the effectiveness of our framework on retrofitting word vectors in low-resource languages.

## SexWEs resources

All specialised Chinese sexist word embeddings are available [here](https://drive.google.com/drive/folders/1flKSTZBQCop-kRFBoYayg2-3y6gF5JJr?usp=sharing).

- `sexwes.zh.vec.txt` - SexWEs specialised by both general and domain constraints, fusing external domain-specific target pairs

- `sexwes.zh.vec.no.external.txt` - SexWEs specialised by both general and domain constraints without external domain-specific target pairs

- `sexwes.zh.vec.general.txt` - SexWEs specialised by general constraints

- `sexwes.zh.vec.domain.txt` - SexWEs specialised by domain constraints     


## Reference

Our work has been published in the 17th International AAAI Conference on Web and Social Media (ICWSM 2023). If you are interested in this paper or resource, please cite: 

```
@article{jiang2023sexwes, 
    title={SexWEs: Domain-Aware Word Embeddings via Cross-Lingual Semantic Specialisation for Chinese Sexism Detection in Social Media}, 
    volume={17}, 
    url={https://ojs.aaai.org/index.php/ICWSM/article/view/22159}, 
    number={1}, 
    journal={Proceedings of the International AAAI Conference on Web and Social Media}, 
    author={Jiang, Aiqi and Zubiaga, Arkaitz}, 
    year={2023}, 
    month={Jun.}, 
    pages={447-458} }
```

If you have any queries or suggestions about our work, please contact us via aiqi.jiang@yahoo.com. We also welcome any ideas or cooperation related to online abuse especially gender-based abuse and cross-lingual scenarios.
