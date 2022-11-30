# Semantic Segmentation for Real Point Cloud Scenes via Bilateral Augmentation and Adaptive Fusion (CVPR 2021)

## My personal experimental implementation. 
## SemanticKITTI part of the code borrowed from [RandLA-Net](https://github.com/QingyongHu/RandLA-Net). and almost identical
## Mostly same as [original repo](https://github.com/ShiQiu0419/BAAF-Net).

## Performance Comparison: 
On the validation set, the results are close to those reported by the original Repo

| Model | mIoU | car  | bicycle | motorcycle | truck | other-vehicle | person | bicyclist | motorcyclist | road | parking | sidewalk | other-ground | building | fence | vegetation | trunk | terrain | pole | traffic-sign |
| ---- | ---- | ------- | ---------- | ----- | ------------- | ------ | --------- | ------------ | ---- | ------- | -------- | ------------ | -------- | ----- | ---------- | ----- | ------- | ---- | ------------ | ---- |
| Original Repo Report |**58.71** | 94.75| 12.41| 52.01| 80.57| 46.41| 59.77| 75.02| 0.01| 93.11| 44.72| 80.74| 2.56| 89.84| 51.45| 87.09| 66.55| 77.33| 57.92| 43.23|
| Ours |**58.83** |94.54| 11.29| 50.35| 87.36| 52.44| 59.05| 73.08| 0.00| 93.24| 46.84| 81.05| 1.31| 89.33| 48.42| 86.30| 66.49| 77.44| 57.30| 42.02|


| **Log** | **Pretrain-model** | **Our Validation results** | **Original Repo Validation results**|
| ---------------- | --------------- | ------------------ | ------------------ | 
| [Link](train_log/log.txt) | [Link](results/Log_2022-11-27_14-29-54/snapshots) | [Link](results/test.zip) | [Link](https://drive.google.com/file/d/1grQ57rZXL34mAOmI_3IASovu_APOPMI3/view?usp=sharing) |