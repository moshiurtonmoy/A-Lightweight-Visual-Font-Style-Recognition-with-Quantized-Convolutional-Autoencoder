# <center> A Lightweight Visual Font Style Recognition with Quantized Convolutional Autoencoder </center>
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) <a target="_blank" href="https://colab.research.google.com/github/moshiurtonmoy/Bangla-Visual-Font-Style-Recognition-with-Lightweight-Convolutional-Autoencoder/blob/master/%5BQuantized%5D_Bangla_Visual_Font_Recognizer.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> [![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/) [![DOI:10.1109/OJCS.2024.3378709](https://zenodo.org/badge/DOI/10.1109/OJCS.2024.3378709.svg)](https://doi.org/10.1109/OJCS.2024.3378709) 
<hr/>
Font style recognition plays a vital role in the field of computer vision, particularly in document and pattern analysis, and image processing. In the industry context, this recognition of font styles holds immense importance for professionals such as graphic designers, front-end developers, and UI-UX developers. In recent times, font style recognition using Computer Vision has made significant progress, especially in English. Very few works have been done for other languages as well. However, the existing models are
computationally costly, time-consuming, and not diversified. In this work, we propose a state-of-the-art
model to recognize Bangla fonts from images using a quantized Convolutional Autoencoder (Q-CAE)
approach. The compressed model takes around 58 KB of memory only which makes it suitable for not only
high-end but also low-end computational edge devices. We have also created a synthetic data set consisting
of 10 distinct Bangla font styles and a total of 60,000 images for conducting this study as no dedicated
dataset is available publicly. Experimental outcomes demonstrate that the proposed method can perform
better than existing methods, gaining an overall accuracy of 99.95% without quantization and 99.85% after
quantization.

<br/>
<br/>

The work has been published in _**IEEE Open Journla of the Computer Society**_ and the full article can be accessed publicly from <a target='_blank' href="https://ieeexplore.ieee.org/abstract/document/10475431"> IEEE Xplore </a>.

# Dataset
Experimental data is publicly available in <a target="_blank" href="https://data.mendeley.com/datasets/cnd2wh65my/1"> Mendeley Data </a>.

Sample data instances- 

<img src="https://github.com/moshiurtonmoy/Bangla-Visual-Font-Style-Recognition-with-Lightweight-Convolutional-Autoencoder/blob/master/sample_data/sample01.jpg" alt="sample_data" width="150"/> <img src="https://github.com/moshiurtonmoy/Bangla-Visual-Font-Style-Recognition-with-Lightweight-Convolutional-Autoencoder/blob/master/sample_data/sample02.jpg" alt="sample_data" width="150"/> <img src="https://github.com/moshiurtonmoy/Bangla-Visual-Font-Style-Recognition-with-Lightweight-Convolutional-Autoencoder/blob/master/sample_data/sample03.jpg" alt="sample_data" width="150"/>

# Citation
```
@ARTICLE {10475431,
author={Tonmoy, Moshiur Rahman and Rakib, Abdul Fattah and Rahman, Rashik and Adnan, Md Akhtaruzzaman and Mridha, MF and Huang, Jie and Shin, Jungpil},
journal = {IEEE Open Journal of the Computer Society},
title = {A Lightweight Visual Font Style Recognition With Quantized Convolutional Autoencoder},
year = {2024},
volume = {5},
number = {01},
issn = {2644-1268},
pages = {120-130},
doi = {10.1109/OJCS.2024.3378709},
publisher = {IEEE Computer Society},
address = {Los Alamitos, CA, USA},
month = {Jan}
}
```
<hr/>

