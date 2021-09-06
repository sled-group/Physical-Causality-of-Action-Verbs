# Physical-Causality-of-Action-Verbs

Official dataset for [Physical Causality of Action Verbs in Grounded Language Understanding](https://sled.eecs.umich.edu/publication/dblp-confacl-gao-dyc-16/). *Qiaozi Gao, Malcolm Doering, Shaohua Yang, Joyce Chai*. ACL, 2016.

![What Action Causes This? Towards Naive Physical Action-Effect Prediction](https://sled.eecs.umich.edu/media/datasets/physical-causality.png)

## Overview

Linguistics studies have shown that action verbs often denote some Change of State (CoS) as the result of an action. However, the causality of action verbs and its potential connection with the physical world has not been systematically explored. To address this limitation, this paper presents a study on physical causality of action verbs and their implied changes in the physical world. We first conducted a crowdsourcing experiment and identified eighteen categories of physical causality for action verbs. For a subset of these categories, we then defined a set of detectors that detect the corresponding change from visual perception of the physical environment. We further incorporated physical causality modeling and state detection in grounded language understanding. Our empirical studies have demonstrated the effectiveness of causality modeling in grounding language to perception.

### Datasets

#### Download

* [Annotations](https://www.dropbox.com/s/6pcbz0d6pddnw63/causality_annotation.zip?dl=0)

#### Descriptions

* This dataset contains verb causality information of 4391 sentences. Each sentence was annotated by three different annotators through crowdsourcing. 

* In the data file, each line contains the verb-object pair in one of the 4391 sentences and followed by a 18-dimension causality vector. In the vector, an element is 1 if at least two annotators labeled the corresponding causality attribute as true, 0 otherwise. The 18 causality attributes are: 

    ```
    1) AttachmentOfPart 
    2) Color 
    3) Containment 
    4) FlavorSmell 
    5) Location 
    6) OcclusionBySecondObject 
    7) Orientation 
    8) PresenceOfObject 
    9) Quantity 
    10) Shape 
    11) Size 
    12) Solidity 
    13) SurfaceIntegrity 
    14) Temperature 
    15) Texture 
    16) Visibility 
    17) Weight 
    18) Wetness
    ```

### Cite

[Physical Causality of Action Verbs in Grounded Language Understanding](https://sled.eecs.umich.edu/publication/dblp-confacl-gao-dyc-16/). *Qiaozi Gao, Malcolm Doering, Shaohua Yang, Joyce Chai*. ACL, 2016. [[Paper]](https://aclanthology.org/P16-1171/).

```tex
@inproceedings{gao-etal-2016-physical,
    title = "Physical Causality of Action Verbs in Grounded Language Understanding",
    author = "Gao, Qiaozi  and
      Doering, Malcolm  and
      Yang, Shaohua  and
      Chai, Joyce",
    booktitle = "Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = aug,
    year = "2016",
    address = "Berlin, Germany",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/P16-1171",
    doi = "10.18653/v1/P16-1171",
    pages = "1814--1824",
}
```