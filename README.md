# Bigscoin Classification - Chart Pattern Recognition
> ## Explainable Bitcoin Pattern Alert and Forecasting Service

## Model
<p align="center">
  <img src="https://user-images.githubusercontent.com/68328871/179261887-935ff2c9-2dd7-4ec6-959a-9358caa1585d.png" />
</p>

- The model reads Bitcoin chart patterns and classifies them into 5 patterns.
- In the output, we provide explanation for classification results using Grad-Cam. (Using Target layer: red)

### Learning Curve
![image](https://user-images.githubusercontent.com/68328871/179258071-624f81c9-0a4c-4567-bffe-dce5d6848e92.png)
- Test Accuracy: 70.3704%


## Example
- pred: rising / label: rising
<p align="center">
  <img src="https://user-images.githubusercontent.com/68328871/179255907-67031e30-7459-47be-b6a7-3e183979f906.png" />
</p>

- pred: ascending / label: rising
<p align="center">
  <img src="https://user-images.githubusercontent.com/68328871/179256288-9d84f562-bd95-4a98-ab6a-d5097f1ebce0.png" />
</p>

## Pattern type

![image](https://user-images.githubusercontent.com/68328871/179253097-cfe214c6-f0d8-437a-912c-4e7f302afc87.png)

## File Directory  

```bash
.
├─── dataset
│    ├── data.csv
│    └── dataset.ipynb
│     
├─── Model
     ├── model.ipynb
     └── grad_cam.py
```

## Reference

- [Stock Chart Pattern recognition with Deep Learning](https://arxiv.org/abs/1808.00418)

