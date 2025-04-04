# 🦙 LlamaPartialSpoof

[📄 Preprint](https://arxiv.org/abs/2409.14743) | [📢 Speech Samples](https://hieuthi.github.io/sample-LlamaPartialSpoof/) | [⬇️ Download](https://zenodo.org/records/14214149)

This is the official repository of the LlamaPartialSpoof Project. The dataset is ready for download from zenodo.
Stay updated on the latest resources and information about the LlamaPartialSpoof project and partially fake speech by following this repository.

## Updates
- 2025-01-07 The paper "LlamaPartialSpoof: An LLM-Driven Fake Speech Dataset Simulating Disinformation Generation" is accepted, we will give a presentation on this topic at ICASSP 2025 in Hyderabad, India around April 6 to 11, 2025

## Related Repositories
- [MultiResoModel (Simple)](https://github.com/hieuthi/MultiResoModel-Simple)
- [partialspoof-metrics](https://github.com/hieuthi/partialspoof-metrics)

## FAQ

### 01. How should the data be used?
- LlamaPartialSpoof was designed for evaluation hence we didn't provided training data. We want researchers to develop a system that either trained on a third-party dataset (e.g. PartialSpoof) or using a non-training method so it can generalize to real life scenarios.
- However if you want to train on the dataset, we suggest using k-fold to split the speakers and the method for training, validating, and testing.


## Have a question?
If you have any question or feedback, feel free to create [a new issue](https://github.com/hieuthi/LlamaPartialSpoof/issues) in this repository.
It may take sometimes for us to get back but we love to connect with the research community on this topic.


## Citations
```
@inproceedings{luong2025llamapartialspoof,
  title={LlamaPartialSpoof: An LLM-Driven Fake Speech Dataset Simulating Disinformation Generation},
  author={Luong, Hieu-Thi and Li, Haoyang and Zhang, Lin and Lee, Kong Aik and Chng, Eng Siong},
  booktitle={IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={1--5},
  year={2025},
  organization={IEEE}
}
```
