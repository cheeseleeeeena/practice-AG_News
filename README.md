# Task 0: AG News Classification

Using pretrained BERT with Tensorflow

## Table of Contents

- 環境需求
- [安裝](#安裝)
- [教材列表](#教材列表)

## Environment Setup

1. Operating System
    - Name: `macOS Ventura`
    - Version: `13.5.1`
2. Python Environment
    - Version: `3.9+`
    - `conda` Version: `23+`
    - `pip` Version: `23+`

## Installation

1. Clone repository

```sh
git clone https://github.com/IKMLab/course_material.git
```

2. Install **required packages**

```sh
conda install --yes --file requirements. txt
```

3. Install [**PyTorch**](https://pytorch.org/get-started/locally/#start-locally)

|選項|描述|選擇|
|-|-|-|
|PyTorch Build|請選**穩定版**避免未知錯誤|`Stable(2.0.1)`|
|Your OS|依照**作業系統**來選擇|`Mac`|
|Package|安裝 **PyTorch** 使用的方法|`Conda`|
|Language|當前執行 **Python** 版本|`Python 3.9`|
|CUDA|電腦上是否有 **GPU** 且支援 **CUDA 架構**|`Default`|

```sh
conda install pytorch::pytorch torchvision torchaudio -c pytorch
```

## References

1. The Illustrated BERT, ELMo, and co. (How NLP Cracked Transfer Learning) ( https://jalammar.github.io/illustrated-bert/ )
2. Classify text with BERT ( https://www.tensorflow.org/text/tutorials/classify_text_with_bert )
3. Kaggle: Multiclass-Bert ( https://www.kaggle.com/code/rushinaik/multiclass-bert )
4. MULTI-CLASS TEXT CLASSIFICATION USING 🤗 BERT AND TENSORFLOW
( https://www.youtube.com/watch?v=wp9BudYGZyA&list=LL&index=1&ab_channel=TheArtificialGuy )
