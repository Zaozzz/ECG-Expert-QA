# ECG-Expert-QA
This is a repository for reproducing the paper [ECG-Expert-QA: A Benchmark for Evaluating Medical Large Language Models in ECG](https://ieeexplore.ieee.org/document/11356744)

## Usage
### Prepare Datasets
We use a public datasets in our model, they can be downloaded from:
* [MIMIC-IV-ECG](https://physionet.org/content/mimic-iv-ecg/1.0/)

The preprocessing code for these datasets, including extracting waveform data, converting to WFDB format, etc., can be found in our previous work [ECG Chat](https://github.com/YubaoZhao/ECG-Chat).

### Use this benchmark to evaluate
You can refer to the code in our code.py file

The complete test code will be released soon

## Citation
If you think that our work is useful to your research, please cite using this BibTeX:
```bibtex
@INPROCEEDINGS{11356744,
  author={Wang, Xu and Kang, Jiaju and Han, Puyu and Liu, Ruida and Gong, Luqi and Fan, Fanda},
  booktitle={2025 IEEE International Conference on Bioinformatics and Biomedicine (BIBM)}, 
  title={ECG-Expert-QA: A Benchmark for Evaluating Medical Large Language Models in ECG}, 
  year={2025},
  pages={5718-5723},
  keywords={Ethics;Large language models;Semantics;Electrocardiography;Benchmark testing;Cognition;Robustness;Safety;Medical diagnostic imaging;Software development management;ECG Interpretation;Medical Large Language Models;Multi-turn QA;Cross-modal Clinical Reasoning;Ethical and Risk-aware Evaluation},
  doi={10.1109/BIBM66473.2025.11356744}}

```
If you have questions about this repo, please submit an issue or contact [kangjiaju@fuxi-lab.com](mailto:kangjiaju@fuxi-lab.com).
