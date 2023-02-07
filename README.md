# Real-time face mask position recognition system based on MobileNet model

## Abstract
COVID-19 is a highly contagious disease that was first identified in 2019, and has since taken more than six million lives world wide till date, while also causing considerable economic, social, cultural and political turmoil. As a way to limit its spread, the World Health Organization and medical experts have advised properly wearing face masks, social distancing and hand sanitization, besides vaccination. However, people wear masks sometimes uncovering their mouths and/or noses consciously or unconsciously, thereby lessening the effectiveness of the protection they provide. A system capable of automatic recognition of face mask position could alert and ensure that an individual is wearing a mask properly before entering a crowded public area and putting themselves and others at risk. We first develop and publicly release a dataset of face mask images, which are collected from 391 individuals of different age groups and gender. Then, we study six different architectures of pre-trained deep learning models, and finally propose a model developed by fine tuning the pre-trained state of the art MobileNet model. We evaluate the performance (accuracy, F1-score, and Cohen’s Kappa) of this model on the proposed dataset and MaskedFace-Net, a publicly available synthetic dataset created by image editing. Its performance is also compared to other existing methods. The proposed MobileNet is found as the best model providing an accuracy, F1-score, and Cohen’s Kappa of 99.23%, 99.22%, and 99.19%, respectively for face mask position recognition. It outperforms the accuracy of the best existing model by about 2%. Finally, an automatic face mask position recognition system has been developed, which can recognize if an individual is wearing a mask correctly or incorrectly. The proposed model performs very well with no drop in recognition accuracy from real images captured by a camera.


### Overall architecture of our proposed system: 
<p align="center">
  <img src="https://user-images.githubusercontent.com/87877319/217154126-69ca7c8f-a45d-46c9-b93e-a12af999cd0b.png" width="500" height="500">
</p>

### Citation
You can find our paper [here](https://www.sciencedirect.com/science/article/pii/S2352648323000107#b23)

```
@article{rahman2023real,
  title={Real-time face mask position recognition system based on MobileNet model},
  author={Rahman, Md Hafizur and Jannat, Mir Kanon Ara and Islam, Md Shafiqul and Grossi, Giuliano and Bursic, Sathya and Aktaruzzaman, Md},
  journal={Smart Health},
  pages={100382},
  year={2023},
  publisher={Elsevier}
}
```
