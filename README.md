# ECG-Expert-QA
This is a repository for reproducing the paper [ECG-Expert-QA: A Benchmark for Evaluating Medical Large Language Models in Heart Disease Diagnosis](https://export.arxiv.org/abs/2502.17475)

## Usage
### Prepare Datasets
We use a public datasets in our model, they can be downloaded from:
* [MIMIC-IV-ECG](https://physionet.org/content/mimic-iv-ecg/1.0/)

The preprocessing code for these datasets, including extracting waveform data, converting to WFDB format, etc., can be found in our previous work [ECG Chat](https://github.com/YubaoZhao/ECG-Chat).

### Use this benchmark to evaluate
You can refer to the code in our code.py file

## Citation
If you think that our work is useful to your research, please cite using this BibTeX:
```bibtex
@misc{wang2025ecgexpertqa,
    title={ECG-Expert-QA: A Benchmark for Evaluating Medical Large Language Models in Heart Disease Diagnosis},
    author={Xu Wang and Jiaju Kang and Puyu Han},
    year={2025},
    eprint={2502.17475},
    archivePrefix={arXiv},
    primaryClass={eess.SP}
}
```
If you have questions about this repo, please submit an issue or contact [kangjiaju@fuxi-lab.com](mailto:kangjiaju@fuxi-lab.com).
