# A Human Annotated Dataset for the Quality Assessment of Emotion Translation (HADQAET) for Chinese-English Machine Translation


This repository contains the HADQAET Dataset in our paper submitted to EAMT 2023. For details of the dataset, please see our paper [*Evaluation of Chinese-English Machine Translation of Emotion-Loaded Microblog Texts: A Human Annotated Dataset for the Quality Assessment of Emotion Translation*](https://aclanthology.org/2023.eamt-1.13/) or at [arXiv](https://arxiv.org/abs/2306.11900). To use the dataset, please see our [License](#license). 


## Citation

- Shenbin Qian, Constantin Orăsan, Félix do Carmo, Qiuliang Li and Diptesh Kanojia. 2023. Evaluation of Chinese-English Machine Translation of Emotion-Loaded Microblog Texts: A Human Annotated Dataset for the Quality Assessment of Emotion Translation. In *Proceedings of the 24th Annual Conference of the European Association of Machine Translation*, Finland, Tempere. European Association for Machine Translation.

```
@inproceedings{qian-etal-2023-evaluation,
    title = "Evaluation of {C}hinese-{E}nglish Machine Translation of Emotion-Loaded Microblog Texts: A Human Annotated Dataset for the Quality Assessment of Emotion Translation",
    author = "Qian, Shenbin  and
      Orasan, Constantin  and
      Carmo, Felix Do  and
      Li, Qiuliang  and
      Kanojia, Diptesh",
    booktitle = "Proceedings of the 24th Annual Conference of the European Association for Machine Translation",
    month = jun,
    year = "2023",
    address = "Tampere, Finland",
    publisher = "European Association for Machine Translation",
    url = "https://aclanthology.org/2023.eamt-1.13",
    pages = "125--135",
    abstract = "In this paper, we focus on how current Machine Translation (MT) engines perform on the translation of emotion-loaded texts by evaluating outputs from Google Translate according to a framework proposed in this paper. We propose this evaluation framework based on the Multidimensional Quality Metrics (MQM) and perform detailed error analyses of the MT outputs. From our analysis, we observe that about 50{\%} of MT outputs are erroneous in preserving emotions. After further analysis of the erroneous examples, we find that emotion carrying words and linguistic phenomena such as polysemous words, negation, abbreviation etc., are common causes for these translation errors.",
}
```


## Data

### Translation Quality Evaluation Data
The annotated dataset for the quality assessment of emotion translation can be found in the "data" folder. The inter and intra-annotator agreement data can be seen under the "IAA" folder. Detailed annotation guidelines can be seen in the "annotation_guidelines.txt" file.

### Post-editing Data

The post-edited reference translations are now available under the "data" folder. We hired a translation company to post-edit the MT outputs that have errors in terms of emotion preservation in the annotation process. The post-editing activity is funded by the [European Association for Machine Translation (EAMT)](https://eamt.org/). Note only about 70% of the whole data is released now (The rest will be released in a shared task). This subset includes a total of 4038 instances and about 3000 of them have post-edited reference translations. Details will be released soon in our project paper at EAMT 2024. 

## License

This resource is built on top of the dataset in the [SMP2020-EWECT shared task](https://smp2020ewect.github.io/), provided by the [Social Computing and Information Retrieval Research Center of Harbin Institute of Technology](http://ir.hit.edu.cn/) and sourced from [Sina Weibo](https://weibo.com/). The MT output was generated from [Google Translate](https://translate.google.co.uk/) on the 30th of May, 2022, and distributed under the [Terms of Service](https://policies.google.com/terms?hl=en-US) of Google.

Though the SMP2020-EWECT dataset does not have license information, the distribution of the public content of Sina Weibo needs to follow its [Terms of Service (Clause 1.3)](https://m.weibo.cn/c/regagreement?from=h5), which allows itself and developers to use and distribute any published posts including texts, pictures or videos etc. The source text of this dataset, hence, remains under Sina Weibo's [developer license](https://open.weibo.com/wiki/%E5%BC%80%E5%8F%91%E8%80%85%E5%8D%8F%E8%AE%AE). The quality evaluation data and post-edited reference translations are licensed under a [Creative
Commons 4.0 licence](https://creativecommons.org/licenses/by/4.0/deed.en).
