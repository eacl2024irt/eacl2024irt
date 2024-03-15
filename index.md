---
theme: default

---


## Welcome

Welcome to our tutorial on Item Response Theory for Natural Language Processing!


This tutorial will introduce the NLP community to Item Response Theory (IRT).
IRT is a method from the field of psychometrics for model and dataset assessment. 
IRT has been used for decades to build test sets for human subjects and estimate latent characteristics of dataset examples.
Recently, there has been an uptick in work applying IRT to tasks in NLP.
It is our goal to introduce the wider NLP community to IRT and show its benefits for a number of NLP tasks. 
From this tutorial, we hope to encourage wider adoption of IRT among NLP researchers.

As NLP models improve in performance and increase in complexity, new methods for evaluation are needed to appropriately evaluate performance improvements.
In addition, data quality continues to be important.
Models exploitation of annotation artifacts, annotation errors, and a misalignment between models and dataset difficulty can hinder an appropriate assessment of model performance. 
As models reach and exceed human performance on certain tasks, it gets more difficult to distinguish between improvements and innovations and changes in scores due to chance.
In this **three-hour, introductory** tutorial, we will review the current state of evaluation in NLP, then introduce IRT as a tool for NLP researchers to use when evaluating their data and models.
We will also introduce and demonstrate the py-irt Python package for IRT model-fitting to help encourage adoption and facilitate IRT use.

While this methodology has been applied successfully to NLP applications, further community exposure specifically for graduate students may provide a new methodological perspective. 
We aim to make the tutorial interactive with hands-on Jupyter notebooks which will give concrete simple examples. 



## Date and Place

The tutorial will take place at [EACL 2024](https://2024.eacl.org/) on March 21st, 2024. 

## Speakers

* [John Lalor](https://jplalor.github.io), University of Notre Dame
* [Pedro Rodriguez](https://www.pedro.ai/), Meta AI-FAIR
* [Joao Sedoc](https://www.stern.nyu.edu/faculty/bio/joao-sedoc), New York University
* [Jose Hernandez-Orallo](https://josephorallo.webs.upv.es/), Universitat Politècnica de València and the Leverhulme Centre for the Future of Intelligence, University of Cambridge, UK

# Schedule

* Evaluation in NLP
* Introduction to IRT
    * Defining IRT Models
    * IRT Model Fitting
    * Introduction to py-irt
* IRT in NLP 
    * Building Test Sets
        * Model Evaluation
        * Chatbot Evaluation
    * Training Dynamics
        * Example Mining
        * Curriculum Learning
    * Model and Data Evaluation 
        * Rethinking Leaderboards
        * Features Related to Difficulty
* Advanced Topics and Opportunities for Future Work


## Material


These materials are still **under construction**. Please stay tuned for the final versions, which will be uploaded prior to the tutorial.

- Evaluation in NLP: [slides](pdf/1_EvalInNLP.pdf)
- Introduction to IRT: [slides](pdf/2_IntroToIRT.pdf), [ipynb notebook](notebooks/2_IntroToIRT.ipynb)
- IRT in NLP: [slides](pdf/3_IRTinNLP.pdf), [ipynb notebook](notebooks/3_IRTinNLP.ipynb)
- Advanced Topics: [slides](pdf/4_1_AdvancedTopics.pdf) 
- Conclusion and Opportunities for Future Work: [slides](pdf/5_Conclusion.pdf)

We have also put together a [structured reading list (pdf)](pdf/structured_references.pdf) for references.


## Reference

If you build on top of this tutorial and want to cite it, please use the following bib entry:

```
@inproceedings{irt4nlp2024,
  title =        "Item Response Theory for Natural Language Processing",
  author =       "Lalor, John P. and Rodriguez, Pedro and Sedoc, Joao and Hernandez-Orallo, Jose",
  booktitle =    "Proceedings of the 18th Conference of the European
                  Chapter of the Association for Computational
                  Linguistics: Tutorial Abstracts",
  month =        march,
  year =         "2024",
  address =      "Malta",
  publisher =    "Association for Computational Linguistics",
  abstract =     "This tutorial will introduce the NLP community to
                  Item Response Theory (IRT). IRT is a method from
                  the field of psychometrics for model and dataset
                  assessment. IRT has been used for decades to build
                  test sets for human subjects and estimate latent
                  characteristics of dataset examples. Recently, there
                  has been an uptick in work applying IRT to tasks in
                  NLP. It is our goal to introduce the wider NLP
                  community to IRT and show its benefits for a number
                  of NLP tasks. From this tutorial, we hope to encourage
                  wider adoption of IRT among NLP researchers."
}
```
