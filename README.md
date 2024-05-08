# 🎉**Awesome-SLM**🎉

## 🌱 How to Contribute
We are welcome contributions from researchers. For detailed guidelines on how to contribute, please see our [CONTRIBUTING.md](CONTRIBUTING.md) file.

## 📜 Contents
- [🎉**Awesome SLM**🎉](#Awesome-SLM)
  - [🌱 How to Contribute](#-how-to-contribute)
  - [📜 Contents](#-contents)
  - [👋 Introduction](#-introduction)
  - [🔥 Base Model](#-base-model)
  - [💪 Pretrain datasets](#-Pretrain-dataset)
  - [💡 SFT datasets](#-SFT-dataset)
  - [🔧 synthetic datasets](#-synthetic-dataset)
  - [📦 preference dataset](#-preference-dataset)
  - [🌈 benchmark](#-benchmark)
 
## 👋 Introduction


## 🔥 Base Model

- OPT-series [[paper](https://arxiv.org/abs/2205.01068)] [[code](https://github.com/facebookresearch/metaseq)] [[model](https://huggingface.co/facebook/opt-1.3b)]
  - release time: 2022/06
  - organzation: meta
  - model size: 125M, 350M, 1.3B, 2.7B, 6.7B, 13B, 30B, 66B, 175B

- Pythia [[paper](https://arxiv.org/pdf/2304.01373)] [[code](https://github.com/EleutherAI/pythia)] [[model](https://huggingface.co/EleutherAI/pythia-1b)]
  - release time: 2023/06
  - organzation: meta
  - model size: 70M, 160M, 410M, 1.0B, 1.4B, 2.8B, 6.9B, 12B

- phi-1 [[paper](https://arxiv.org/pdf/2306.11644.pdf)] [[code](https://huggingface.co/TommyZQ/phi-1)] [[model](https://huggingface.co/TommyZQ/phi-1)]
  - release time: 2023/06
  - organzation: mircosoft
  - model size: 1.42B

- phi-1_5 [[paper](https://arxiv.org/pdf/2309.05463.pdf)] [[model](https://huggingface.co/TommyZQ/phi-1_5)]
  - release time: 2023/09
  - organzation: mircosoft
  - model size: 1.42B

- phi-2 [[paper](https://arxiv.org/pdf/2309.05463.pdf)] [[model](https://huggingface.co/TommyZQ/phi-2)]
  - release time: 2023/12
  - organzation: mircosoft
  - model size: 2.78B

- phi-3-series [[paper](https://arxiv.org/pdf/2404.14219)] [[model](https://huggingface.co/microsoft/Phi-3-mini-4k-instruct)]
  - release time: 2024/04
  - organzation: mircosoft
  - model series: Phi-3-mini-4k-instruct, Phi-3-mini-128k-instruct
  - model size: 3.82B

- Tinyllama [[paper](https://arxiv.org/abs/2401.02385)] [[model](https://huggingface.co/TinyLlama)]
  - release time: 2024/01
  - organzation: /
  - model size: 1.1B

 - MiniCPM-series [[paper](https://shengdinghu.notion.site/MiniCPM-c805a17c5c8046398914e47f0542095a)]
  [[code](https://github.com/OpenBMB/MiniCPM)] 
  [[model](https://huggingface.co/openbmb/MiniCPM-2B-sft-bf16)]
    - release time: 2024/02
    - organzation: openbmb
    - model series: MiniCPM-1B-sft-bf16, MiniCPM-2B-sft-bf16, MiniCPM-2B-sft-fp32, MiniCPM-2B-128k, MiniCPM-MoE-8x2B
    - model size: 1.2B, 2.4B, 8X2.4B (excluding embeddings)

- H2O-Danube-1.8B [[paper](https://arxiv.org/abs/2401.16818)] [[code](https://github.com/OpenBMB/MiniCPM)] 
[[model](https://huggingface.co/h2oai/h2o-danube2-1.8b-base)]
    - release time: 2024/04
    - organzation: h2oai
    - model series: h2o-danube2-1.8b-base, h2o-danube2-1.8b-sft, h2o-danube2-1.8b-chat
    - model size: 1.8B

- csg-wukong-series[[model](https://huggingface.co/opencsg/csg-wukong-1B)]
    - release time: 2024/04
    - organzation: opencsg
    - model series: csg-wukong-1B, csg-wukong-1B-VL, csg-wukong-1B-chat
    - model size: 1B

- CT-LLM-Base[[paper](https://arxiv.org/pdf/2404.04167)] [[code](https://github.com/OpenBMB/MiniCPM)] 
[[model](https://huggingface.co/m-a-p/CT-LLM-Base)]
    - release time: 2024/04
    - organzation: opencsg
    - model series: csg-wukong-1B, csg-wukong-1B-VL, csg-wukong-1B-chat
    - model size: 1B




## 💪 Pretrain Datasets
- SlimPajama-627B [[paper](https://www.cerebras.net/blog/slimpajama-a-627b-token-cleaned-and-deduplicated-version-of-redpajama)] [[code](https://github.com/Cerebras/modelzoo/tree/main/src/cerebras/modelzoo/data_preparation/nlp/slimpajama)] [[dataset](https://huggingface.co/datasets/cerebras/SlimPajama-627B)]
  - release time: 2023/06
  - dataset size: 895 GB
  - token size: 627B
  - language: Primarily English, with some non-English files in Wikipedia
  

- dolma [[paper](https://arxiv.org/abs/2402.00159)] [[code](https://github.com/allenai/dolma)] [[dataset](https://huggingface.co/datasets/allenai/dolma)]
  - release time: 2024/04
  - dataset size: 4.5TB
  - token size: 1.7T
  - language: Primarily English, with some non-English files in Wikipedia

- RedPajama-Data-1T [[paper](https://arxiv.org/pdf/1906.02285.pdf)] [[code](https://github.com/togethercomputer/RedPajama-Data)] [[dataset](https://huggingface.co/datasets/togethercomputer/RedPajama-Data-1T)]
  - release time: 2023/04
  - token size: 627B

- C4 [[paper](https://www.tensorflow.org/datasets/catalog/c4)] [[code](https://github.com/allenai/c4-documentation)] [[dataset](https://huggingface.co/datasets/c4)]
  - release time: 2022/01
  - dataset size: en: 305GB, en.noclean: 2.3TB, en.noblocklist: 380GB, realnewslike: 15GB, multilingual (mC4): 9.7TB (108 subsets, one per language)


## 💡 SFT Datasets
- ultrachat [[code](https://github.com/thunlp/UltraChat)] [[dataset](https://huggingface.co/datasets/stingning/ultrachat)]
  - release time: 2023/04
  - dataset size: 2.5GB
  - language: en

- ultrachat_200k [[code](https://github.com/thunlp/UltraChat)] [[dataset](https://huggingface.co/datasets/HuggingFaceH4/ultrachat_200k)]
  - release time: 2023/10
  - dataset size: 1.6GB
  - language: en


## 🔧 synthetic datasets
- cosmopedia [[code](https://github.com/thunlp/UltraChat)] [[dataset](https://huggingface.co/datasets/HuggingFaceTB/cosmopedia)]
  - release time: 2024/02
  - dataset size: 92.2GB
  - language: en


## 📦 preference dataset
- UltraFeedback [[code](https://github.com/thunlp/UltraChat)] [[dataset](https://huggingface.co/datasets/openbmb/UltraFeedback)]
  - release time: 2023/09
  - dataset size: 0.94GB
  - language: en


## 🌈 benchmark