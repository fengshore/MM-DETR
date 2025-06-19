# MM-DETR
A new paradigm for initializing DETR using multimodality.

### Semantic Alignment Module
<p align="center">
  <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/Semantic_Alignment_Module.png" 
       alt="Semantic Alignment Module" width="80%"/>
</p>








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


### compare

<p align="center">
  <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/hot_figure/output/output-1.jpg" width="45%" alt="Output 1"/>
  <img src="https://github.com/fengshore/MM-DETR/blob/main/figure/hot_figure/output/output-1.jpg" width="45%" alt="Output 1"/>
</p>



