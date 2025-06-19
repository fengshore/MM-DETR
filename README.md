# MM-DETR
A new paradigm for initializing DETR using multimodality.

### Fig1: Semantic Alignment Module
<p align="center">
  <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/Semantic_Alignment_Module.png" 
       alt="Semantic Alignment Module" width="80%"/>
</p>

### Fig2: VisDrone dataset(MM-DETR on the left and DINO on the right)
<p align="center">
  <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdetr/vis/0000001_02999_d_0000005.jpg" width="45%" alt="figure1"/>
  <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdino/vis/0000001_02999_d_0000005.jpg" width="45%" alt="figure1-1"/>
</p>
<p align="center">
  <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdetr/vis/0000021_00000_d_0000001.jpg" width="45%" alt="figure2"/>
  <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdino/vis/0000021_00000_d_0000001.jpg" width="45%" alt="figure2-1"/>
</p>
<p align="center">
  <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdetr/vis/0000026_01000_d_0000026.jpg" width="45%" alt="figure3"/>
  <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdino/vis/0000026_01000_d_0000026.jpg" width="45%" alt="figure3-1"/>
</p>
<p align="center">
  <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdetr/vis/0000026_02000_d_0000028.jpg" width="45%" alt="figure4"/>
  <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/mmdino/vis/0000026_02000_d_0000028.jpg" width="45%" alt="figure4-1"/>
</p>

### Fig3: gradient heatmap
<p align="center">
  <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/hot_figure/output/compare1.png" width="45%" alt="figure4"/>
  <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/hot_figure/output/compare2.png" width="45%" alt="figure4-1"/>
</p>

### Table1: comparison on Visdrone datasets 
| Method    | #epochs |   AP   | AP<sub>S</sub>   | AP<sub>M</sub>   | AP<sub>L</sub>   |
|-----------|:-------:|:------:|:----------------:|:----------------:|:----------------:|
| RT-DETR   |   36    |  23.2  |      16.2        |      22.2        |      41.2        |
| DINO-DETR |   36    |  21.6  |      14.8        |      20.3        |      39.6        |
| MM-DETR   |   36    |  25.8  |      18.5(+3.7)  |      25.6(+5.3)  |      43.4(+3.8)  |



### saliency map visualization









