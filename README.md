# Pose and Shape Estimation of Humans in Vehicles

Pose and Shape Estimation of Humans in Vehicles (paper link will be available)

> Kwang-Lim Ko, Jun-Sang Yoo, Changwoo Han, Jungyeop Kim, and Seung-Won Jung


## HIVE dataset

HIVE (Humans In VEhicle)

A synthetic dataset consists of synthesized humans with different shapes and poses in vehicels.

Download link will be available upon publication of our paper.

## In-vehicle human 3D joints

An in-vehicle human 3D joint dataset captured in real-world.

Download link will be available upon publication of our paper.


## Demo examples

The blue mesh represents the results from the SPIN (_Kolotouros et al_.) and the pink mesh represents the results from ours.

For each posture, the top parts are RGB images and the bottom parts are NIR images. 



---

![teaser1](teaser1.gif)

---

![teaser2](teaser2.gif)

---

![teaser3](teaser3.gif)

---

![teaser4](teaser4.gif)

## Ablation studies on Drive & Act dataset

For a cross-validation for other dataset, we applied our and compared models to the public dataset Drive&Act.

Table below shows the pose evaluation result on the real in-vehicle test set and Drive & Act dataset: The state-ofthe-art models are evaluated, and their fine-tuned models with the HIVE dataset are reported with †.

Our method shows the best performance on Drive&Act, and the performance of the other models is improved
when they are fine-tuned with the HIVE dataset.

|    | Drive & Act |   | In-vehicle test set (ours)| |
| :---         |     :---:   |   |       :---:       |  |
|  **Model**         |     **MPJPE** | **PA-MPJPE**  |      **MPJPE**     | **PA-MPJPE** |
| SPIN    |261.3 | 95.6   | 229.1|  83.5        |
| HMR     | 242.0 |  89.2    | 178.6 |    71.9      |
HMR-EFT | 246.7 | 90.0  |184.8  |63.1
SPEC  |282.5 | 93.2 | 199.0  |78.1
PARE  |286.1 | 94.9 | 178.2 | **57.3**
3DCrowdNet  |231.7 | 82.3 | 223.1  |70.6
Jiang et al. | 198.3  |68.3  |201.8  |74.3
||
SPIN† |234.4| 87.5 |182.1 |73.6
HMR†| 221.5 |82.4| 177.5| 69.0
HMR-EFT†| 195.1 |108.6 |180.8| 68.0
SPEC† |169.6 |77.5 |170.2| 73.1
PARE†| 204.6 |81.6| 160.4| 58.5
3DCrowdNet† |212.5 |81.0 |178.4 |62.9
Jiang et al.†| 185.2| 70.1| 173.5| 70.6
||
**Ours**|**147.1** |**65.2**| **123.6**| 59.1

---

The figure below shows the examples of the visualized 3D joints estimated from SPIN and ours. The qualitative results display the effectiveness of our method.


![teaser5](Drive_act_vis.png)


