Development of a Language Model for the German Medical Domain
===
[![Download
PDF](https://img.shields.io/badge/Download-PDF-green)](https://github.com/heliumind/msc-thesis/releases/download/final/MA_He.pdf)
[![CC BY 4.0][cc-by-shield]][cc-by]

## TUM CIT Master's thesis
Supervised by [Raphael Scheible](https://raphiniert.com/) and [Manuel Milling](https://scholar.google.de/citations?user=884vYsMAAAAJ)
at [Chair for Health Informatics](https://www.kiinformatik.mri.tum.de/de/lehrstuhle/chair-health-informatics) (Prof. Björn Schuller)

## Directories
### thesis
Includes the actual thesis work
### proposal
Includes the thesis proposal 
### presentation
Includes the final presentation

## Citation
```
@mastersthesis{MA_He,
  author = {Henry He},
  title = {Development of a Language Model for the German Medical Domain},
	year = {2025},
  school = {Technische Universität München},
  pages = {102},
  language = {en},
  abstract = {Digital healthcare nowadays generates vast amounts of clinical texts that hold potential for many emerging AI applications in patient care. Recent advances in natural language processing (NLP) through Transformer-based language models like BERT and RoBERTa provide capabilities to extract and analyze information from these clinical texts. Performing domain adaptation on these models has proven essential for specialized fields like medicine where terminology and linguistic patterns differ from general language. However, the availability of large text corpora needed for domain adaptation is limited for the German language due to strict data protection regulations. Moreover, current German medical language models either use the original BERT architecture or were trained on insufficient data, potentially limiting their performance. This thesis aims to reduce these gaps by developing novel German biomedical domain-specific language models based on the RoBERTa base architecture, while employing translation-based data augmentation on large English-language clinical corpora to address data scarcity. For this purpose, we curated a 13.5 GB corpus which encompasses scientific literature, clinical notes and crawled online content from the German health web. To assess the efficacy of the developed models, we evaluated their performance on three medical named entity recognition and two text classification tasks against four existing German general-purpose and medical language models. Furthermore, the effect of different domain adaptation strategies on task performance was investigated: continued pre-training, pre-training from scratch, and pre-training with domain-specific vocabulary. In our experimental setup, the developed models outperform the baseline models across four out of five tasks, establishing a new state-of-the-art for the German clinical language. Our findings indicate that the optimal domain adaptation strategy is task-dependent and remains crucial, as adapted models consistently outperformed general-purpose language models in our experiments. Based on the empirical results, pre-training from scratch is effective for highly specialized clinical texts, whereas continued pre-training is suited for more commonly written medical texts. To support the German medical NLP community, the developed models are made publicly available.},
}
```

## License
This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
