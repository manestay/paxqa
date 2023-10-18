# PAXQA Datasets and Code
Code and Data for the [paper](https://arxiv.org/abs/2304.12206) "PAXQA: Generating Cross-lingual Question Answering Examples at Training Scale" at EMNLP 2023 (Findings).

## PAXQA Data
The PAXQA test and validation sets are available at [this link](https://huggingface.co/datasets/manestay/paxqa_val_test) in the HuggingFace hub. This consists of 1788 QA examples total.
The fields are consistent with the MLQA (and therefore SQuAD) fields.

As the train data is much larger (662k examples), we release them in ZIP files (which also include the test and validation sets): \
[PAXQA human-aligned](https://drive.google.com/file/d/1GpUAuX93NgZZKtCOagAabF0kk72ANWcW/view?usp=share_link) \
Contents:
* `gale_ar-en_tnmt` and `gale_zh-en_tnmt` directories: saved with the [`datasets`](https://huggingface.co/docs/datasets/index) library, load with `datasets.load_from_disk(DIRECTORY_NAME)`.
* `gale_{lang}_{split}.jsonl` files: same data as the directories in an alternate format.

[PAXQA automatically-aligned](https://drive.google.com/file/d/1jj1xGNUn53352rS8M-Va2mx9SSljLi-f/view?usp=share_link)
Contents are organized similarly to the prior ZIP.

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
