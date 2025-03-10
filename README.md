# Endoscopic_images_multi_class_classfication_using_EfficientNetB3
This repository contains the source code used in the paper titled "Interpretable Deep Learning for Enhanced Multi-Class Classification of Gastrointestinal Endoscopic Images."  which is currently submitted at Springer's The Visual Computer Journal. 

## Installation
Clone this repository and install dependencies:
```bash
git clone https://github.com/askastitva/Endoscopic_images_multi_class_classfication_using_EfficientNetB3.git
cd Endoscopic_images_multi_class_classfication_using_EfficientNetB3
pip install -r requirements.txt

```
## 📂 Dataset
This study uses the **Kvasir V2** dataset, which is publicly available on Kaggle:  
🔗 [Kvasir V2 - A Gastrointestinal Tract Dataset](https://www.kaggle.com/datasets/plhalvorsen/kvasir-v2-a-gastrointestinal-tract-dataset)

### 📌 Dataset Description
Kvasir V2 is a publicly available dataset containing labeled gastrointestinal endoscopic images. It consists of **8 classes** of images captured from real endoscopic procedures, including:

- 📌 **Esophagitis**
- 📌 **Normal Z-line**
- 📌 **Polyps**
- 📌 **Ulcerative Colitis**
- 📌 **Pylorus**
- 📌 **Erythematous gastropathy**
- 📌 **Barrett’s Esophagus**
- 📌 **Dyed-lifted polyps**  

### ⚠️ Usage Note
- The **Kvasir V2 dataset is publicly available**, but users must comply with its original terms and conditions as specified on Kaggle.
- We do **not** redistribute the dataset in this repository, but users can download it from the provided link.

## 📑 Citation
If you use this code or dataset in your research, please cite our work as follows:
```bash
@article{Kamble2025,
author = {Astitva Kamble and Vani Bandodkar and Saakshi Dharmadhikary and Veena Anand and Pradyut Kumar Sanki and Mei X. Wu and Biswabandhu Jana},
title = {Interpretable Deep Learning for Enhanced Multi-Class Classification of Gastrointestinal Endoscopic Images},
journal = {The Visual Computer},
year = {2025}}
```

Additionally, please cite the **Kvasir V2 dataset** as follows:
```bash
@article{pogorelov2017kvasir,
author = {Pogorelov, K. and others},
title = {Kvasir: A Multi-Class Image Dataset for Computer Aided Gastrointestinal Disease Detection}, journal = {Proceedings of the 8th ACM Multimedia Systems Conference},
year = {2017},
pages = {164--169},
publisher = {ACM},
doi = {10.1145/3083187.3083212} }
```

## 🛡️ License
This project is licensed under the **MIT License**. See the [`LICENSE`](LICENSE) file for details.

MIT License

Copyright (c) 2025 [Astitva Kamble]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
