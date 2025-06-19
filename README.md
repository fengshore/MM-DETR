# MM-DETR
A new paradigm for initializing DETR using multimodality.
| Method              | Initialization | #epochs | AP ↑          | AR ↑           |
|---------------------|:--------------:|:-------:|:-------------:|:--------------:|
| Deform-DETR         | –              |   50    | 46.9          | 57.3           |
| **Deform-DETR**     | **MM**         |   50    | 48.2 (+1.3)   | 61.9 (+4.6)    |
| Conditional-DETR    | –              |   50    | 40.9          | 55.4           |
| **Conditional-DETR**| **MM**         |   50    | 43.6 (+2.7)   | 57.7 (+2.3)    |
| DAB-DETR            | –              |   50    | 45.7          | 59.6           |
| **DAB-DETR**        | **MM**         |   50    | 47.8 (+2.1)   | 62.1 (+2.5)    |
| DINO-DETR           | –              |   36    | 50.9          | 65.4           |
| **DINO-DETR**       | **MM**         |   36    | 52.3 (+1.4)   | 68.7 (+3.3)    |
