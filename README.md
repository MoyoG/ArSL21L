# ArSL21L: Arabic sign language letter dataset benchmarking and an educational avatar for metaverse applications
**Authors:**

[Ganzorig Batnasan](https://github.com/ganzob/), [Munkhjargal Gochoo](https://github.com/moyog/), [Munkh-Erdene Otgonbold](https://github.com/omunkhuush/), , Fady Alnajjar, Timothy K. Shih



We present our collected and annotated Arabic Sign Language Letters Dataset (ArSL21L) consisting of 14202 images of 32 letter signs with various backgrounds collected from 50 people. We benchmarked our ArSL21L dataset on state-of-the-art object detection models, i.e., 4 versions of YOLOv5. Among the models, YOLOv5l achieved the best result with mAP of 0.83. Moreover, we provide comparison results of classification task between [ArSL2018](https://www.sciencedirect.com/science/article/pii/S2352340919301283) dataset, the only Arabic sign language letter dataset for classification task, and our dataset by running classification task on in-house short video. The results revealed that the model trained on our dataset has a superior performance over the model trained on ArSL2018.

![samples_long](https://github.com/MoyoG/ArSL21L/assets/73123564/3a18ade6-d11d-422f-8ce4-4c435a4fb2ee)
![F1_curve_l_26](https://github.com/MoyoG/ArSL21L/assets/73123564/05027a3c-5834-42dc-a344-eb58aa1e5160)
![ddd](https://github.com/MoyoG/ArSL21L/assets/73123564/9baefd7c-de5d-4e74-b04a-936c51dcb1f7)
![confusion_matrix2](https://github.com/MoyoG/ArSL21L/assets/73123564/1369c189-fa20-4ff3-8c66-35132207157d)


https://github.com/MoyoG/ArSL21L/assets/73123564/ec4ad568-631f-4815-9350-a8c2492ebb6d



# Dataset
- [Click to download the ArSL21L dataset](https://data.mendeley.com/datasets/8hrn3bvdvk)

# Paper
- [Click to download the paper](https://ieeexplore.ieee.org/abstract/document/9766497)


**The result of YOLOv5 models on ArSL21L dataset**

| Models   | Precision | Recall | mAP0.5 | mAP.5:.95 |
| -------- | --------- | ------ | ------ | ---------
| YOLOv5s  | 0.953     | 0.9408 | 0.9784 |  0.7661   |
| YOLOv5m  | 0.968     | 0.9468 | 0.9842 |  0.7768   |
| YOLOv5l  | 0.9787    | 0.9766 | 0.9909 |  0.8306   |
| YOLOv5x  | 0.9758    | 0.9743 | 0.9896 |  0.8224   |




**Classification model results on Arabic datasets**
|       | [ArSL2018](https://www.sciencedirect.com/science/article/pii/S2352340919301283) | ArSL21L (Ours) | Video |
| ----- | ---------- | ------- | ------- |
|ResNext1 ([ArSL2018](https://www.sciencedirect.com/science/article/pii/S2352340919301283))| 99.2% | 35% | 69% |
|ResNext2 (ArSL21L(Ours)) |   45.47%   | 91.04% | 92% |
|CNN ([ArSL2018](https://www.sciencedirect.com/science/article/pii/S2352340919301283)) |    92%  |       |      |

# Citation
```bibtex
@INPROCEEDINGS{gbatnasan2021,
  author={Batnasan, Ganzorig and Gochoo, Munkhjargal and Otgonbold, Munkh-Erdene and Alnajjar, Fady and Shih, Timothy K},
  booktitle={2022 IEEE Global Engineering Education Conference (EDUCON)}, 
  title={ArSL21L: Arabic Sign Language Letter Dataset Benchmarking and an Educational Avatar for Metaverse Applications}, 
  year={2022},
  volume={},
  number={},
  pages={1814-1821},
  doi={10.1109/EDUCON52537.2022.9766497}}
