# PAXQA Datasets and Code
Code and Data for the [paper](https://arxiv.org/abs/2304.12206) "PAXQA: Generating Cross-lingual Question Answering Examples at Training Scale" at EMNLP 2023 (Findings).

## PAXQA Data
We release the PAXQA datasets on the HuggingFace Hub. The fields are consistent with the MLQA (and therefore SQuAD) fields.

The PAXQA test and validation sets are available at [this link](https://huggingface.co/datasets/manestay/paxqa_val_test), and consists of 1788 QA examples total.

The PAXQA train sets are available at [this link](https://huggingface.co/datasets/manestay/paxqa_train), and consists of 660K QA examples total. PAXQA_HWA are the 2 `*gale*` datasets, while PAXQA_AWA are the other 5 datasets.

### Dataset sizes 
Table 1 of the paper gives the number of QA examples for each split and each language:
![Table 1](https://github.com/manestay/paxqa/assets/9099139/77300d29-22e7-409f-aba9-78007ce8db95)

You can verify the numbers with the files you downloaded above (contact the authors if there are inconsistencies).

## Code
This section is forthcoming.

## Citation
```
@article{li2023paxqa,
      title={\textsc{PaxQA}: Generating Cross-lingual Question Answering Examples at Training Scale}, 
      author={Bryan Li and Chris Callison-Burch},
      year={2023},
      journal={Findings of the Association for Computational Linguistics: EMNLP}
}
```
