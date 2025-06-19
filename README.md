# MM-DETR
A new paradigm for initializing DETR using multimodality.

### Semantic Alignment Module
<p align="center">
  <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/Semantic_Alignment_Module.png" 
       alt="Semantic Alignment Module" width="80%"/>
</p>

<figure>
  <figcaption style="text-align:center; font-weight:bold;">
    fig1:VisDrone dataset (MM-DETR on the left and DINO on the right)
  </figcaption>

  <p align="center">
    <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdetr/vis/0000001_02999_d_0000005.jpg" width="45%" alt="MM-DETR example 1"/>
    <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdino/vis/0000001_02999_d_0000005.jpg" width="45%" alt="DINO example 1"/>
  </p>
  <p align="center">
    <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdetr/vis/0000021_00000_d_0000001.jpg" width="45%" alt="MM-DETR example 2"/>
    <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdino/vis/0000021_00000_d_0000001.jpg" width="45%" alt="DINO example 2"/>
  </p>
  <p align="center">
    <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdetr/vis/0000026_01000_d_0000026.jpg" width="45%" alt="MM-DETR example 3"/>
    <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdino/vis/0000026_01000_d_0000026.jpg" width="45%" alt="DINO example 3"/>
  </p>
  <p align="center">
    <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdetr/vis/0000026_02000_d_0000028.jpg" width="45%" alt="MM-DETR example 4"/>
    <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdino/vis/0000026_02000_d_0000028.jpg" width="45%" alt="DINO example 4"/>
  </p>
</figure>


### VisDrone dataset comparsion

| Method              | #epochs        |   AP    | AP_S          | AP_M           |    AP_L   |
|---------------------|:--------------:|:-------:|:-------------:|:--------------:|:---------:|
| MM                  | –              |   50    | 46.9          | 57.3           |66         |
| **Deform-DETR**     | **MM**         |   50    | 48.2 (+1.3)   | 61.9 (+4.6)    |66         |
| Conditional-DETR    | –              |   50    | 40.9          | 55.4           |66         |
| **Conditional-DETR**| **MM**         |   50    | 43.6 (+2.7)   | 57.7 (+2.3)    |66         |
| DAB-DETR            | –              |   50    | 45.7          | 59.6           |66         |
| **DAB-DETR**        | **MM**         |   50    | 47.8 (+2.1)   | 62.1 (+2.5)    |66         |
| DINO-DETR           | –              |   36    | 50.9          | 65.4           |66         |
| **DINO-DETR**       | **MM**         |   36    | 52.3 (+1.4)   | 68.7 (+3.3)    |66         |


### saliency map visualization









