# A Human Annotated Dataset for the Quality Assessment of Emotion Translation (HADQAET) for Chinese-English Machine Translation


This repository contains the HADQAET Dataset submitted to EAMT 2023. For details of the dataset, please see our upcoming paper *Evaluation of Chinese-English Machine Translation of Emotion-Loaded Microblog Texts: A Human Annotated Dataset for the Quality Assessment of Emotion Translation*. To use the dataset, please see our [License](#license). 

<!---[*Evaluation of Chinese-English Machine Translation of Emotion-Loaded Microblog Texts: A Human Annotated Dataset for the Quality Assessment of Emotion Translation*](https://aclanthology.org/2022.wassa-1.29/).---> 

<!---
## Citation

- Shenbin Qian, Constantin Orăsan, Félix do Carmo, Diptesh Kanojia, and Qiuliang Li. 2023. Evaluation of Chinese-English Machine Translation of Emotion-Loaded Microblog Texts: A Human Annotated Dataset for the Quality Assessment of Emotion Translation. In *Proceedings of the 24th Annual Conference of the European Association of Machine Translation*, Finland, Tempere. European Association for Machine Translation.

```
@inproceedings{qian-etal-2022-surrey,
    title = "{SURREY}-{CTS}-{NLP} at {WASSA}2022: An Experiment of Discourse and Sentiment Analysis for the Prediction of Empathy, Distress and Emotion",
    author = "Qian, Shenbin  and
      Orasan, Constantin  and
      Kanojia, Diptesh  and
      Saadany, Hadeel  and
      Do Carmo, F{\'e}lix",
    booktitle = "Proceedings of the 12th Workshop on Computational Approaches to Subjectivity, Sentiment {\&} Social Media Analysis",
    month = may,
    year = "2022",
    address = "Dublin, Ireland",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.wassa-1.29",
    pages = "271--275",
    abstract = "This paper summarises the submissions our team, SURREY-CTS-NLP has made for the WASSA 2022 Shared Task for the prediction of empathy, distress and emotion. In this work, we tested different learning strategies, like ensemble learning and multi-task learning, as well as several large language models, but our primary focus was on analysing and extracting emotion-intensive features from both the essays in the training data and the news articles, to better predict empathy and distress scores from the perspective of discourse and sentiment analysis. We propose several text feature extraction schemes to compensate the small size of training examples for fine-tuning pretrained language models, including methods based on Rhetorical Structure Theory (RST) parsing, cosine similarity and sentiment score. Our best submissions achieve an average Pearson correlation score of 0.518 for the empathy prediction task and an F1 score of 0.571 for the emotion prediction task, indicating that using these schemes to extract emotion-intensive information can help improve model performance.",
}
```
---> 

## Data

The annotated dataset for the quality assessment of emotion translation can be found in the "data" folder. The inter and intra-annotator agreement data can be seen under the "IAA" folder. Detailed annotation guidelines can be seen in the "annotation_guidelines.txt" file.


## License

This resource is built on top of the dataset in the [SMP2020-EWECT shared task](https://smp2020ewect.github.io/), provided by the [Social Computing and Information Retrieval Research Center of Harbin Institute of Technology](http://ir.hit.edu.cn/) and sourced from [Sina Weibo](https://weibo.com/). The MT output was generated from [Google Translate](https://translate.google.co.uk/) on the 30th of May, 2022, and distributed under the [Terms of Service](https://policies.google.com/terms?hl=en-US) of Google.

Though the SMP2020-EWECT dataset does not have license information, the distribution of the public content of Sina Weibo needs to follow its [Terms of Service (Clause 1.3)](https://m.weibo.cn/c/regagreement?from=h5), which allows itself and developers to use and distribute any published posts including texts, pictures or videos etc. The source text of this dataset, hence, remains under Sina Weibo's [developer license](https://open.weibo.com/wiki/%E5%BC%80%E5%8F%91%E8%80%85%E5%8D%8F%E8%AE%AE).

To use this dataset also needs to cite our upcoming paper. 
