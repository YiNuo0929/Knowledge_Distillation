## 專案要求
• Teacher model: ResNet34
• Student model: ResNet18
• Dataset: Cifar10
## 兩種蒸餾方法
Response-based distillation 
Feature-based distillation 
## report內容大綱
1. 比較學生模型train from scratch和經過2種方法蒸餾後的結果和分析
2. 在response-based KD中，說明如何選擇temperature和alpha這2個參數
3. 在feature-based KD中，說明選了哪些layer的feature、你是如何實作這個部分
4. 說明如何設計response-based和feature-based KD的損失函數
5. 實作過程中遇到的困難及你後來是如何解決的
