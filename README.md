# Multi-rate-Directed-T-GCN
    Aggregate Together We See Through: 
    WiFi-based Through-wall2D Human Pose Estimation via Multi-rate Directed T-GCN


* [Architecture](#architecture)

* [Visulization](#visulization)

* [Result](#result)

## Architecture
![image](https://github.com/fingerk28/Multi-rate-Directed-T-GCN/blob/master/image/Architecture.png)

## Visulization
Our demo for wifi based 2D human pose estimation

Proposed Model | Baseline
---|---
![image](https://github.com/fingerk28/Multi-rate-Directed-T-GCN/blob/master/image/proposed_model.gif)|![image](https://github.com/fingerk28/Multi-rate-Directed-T-GCN/blob/master/image/baseline.gif)


## Result
The PCK(Percentage of Correct Keypoint) and MPJPE(Mean Per Joint Position Error) of provided models are shown here:
| Model|**Multi-rate-Directed-T-GCN** (Ours)|Baseline[1]|WISPPN[2]|
| :------| :------: | :------: | :------: |
|PCK@20|  **82.22**    | 77.06   |  69.82   |
|MPJPE|  **??.??**    | 41.71   |  ??.??   |

[1] Fei Wang, Stanislav Panev, Ziyi Dai, Jinsong Han, and Dong Huang. 2019. Canwifi estimate person pose?arXiv preprint arXiv:1904.00277(2019).

[2] Fei Wang, Sanping Zhou, Stanislav Panev, Jinsong Han, and Dong Huang. 2019.Person-in-WiFi: Fine-grained person perception using WiFi. InProceedings of theIEEE International Conference on Computer Vision. 5452–5461.
