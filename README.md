# SimCLR
Implementation of SimCLR based on the paper (https://arxiv.org/pdf/2002.05709).

<img width="400" alt="image" src="https://github.com/user-attachments/assets/df0652f2-5c6f-46b6-a547-657a2f974015" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/ba9103ad-4707-4cf9-a711-f3eb7f31d803" />

https://github.com/user-attachments/assets/b1867aac-6bed-4dcb-937d-de3730c28243

| Architecture | Batch Size | Epochs | Projection head | Optimizer | Scheduler | Test Acc. |
| ------------ | ---------- | ------ | --------------- | --------- | --------- | --------- |
| ResNet-18 | 512 | 300 | 128-dimensions | SGD with Nesterov Momentum | Warmup -> Cosine Annealing | ~80% |
