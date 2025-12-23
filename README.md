# 🧠 MRI 腦腫瘤分類系統  
**MRI Brain Tumor Classification**

## 📌 專案說明
本專案是一個利用 **深度學習（Convolutional Neural Network, CNN）** 技術來自動判讀腦部 MRI 影像的輔助診斷系統。  
系統的主要功能為 **快速分析 MRI 影像**，判斷腦部是否健康，或是否患有特定類型的腫瘤，旨在解決人工判讀 **耗時且容易受主觀因素影響** 的問題。

---

## 🎯 支援辨識類別
本系統可將 MRI 影像自動分類為以下四種狀況：

- **No Tumor**（健康無腫瘤）
- **Glioma**（神經膠質瘤）
- **Meningioma**（腦膜瘤）
- **Pituitary**（垂體瘤）

---

## 🛠️ 核心特色

### 🔍 更清晰的影像處理
使用 **CLAHE（Contrast Limited Adaptive Histogram Equalization，限制對比度自適應直方圖均衡化）** 技術，  
有效增強 MRI 影像對比度，使原本模糊的腫瘤紋理細節更加清楚，提升模型判斷的準確度。

---

### 🤖 精準的模型訓練
採用 **EfficientNetB0** 作為核心分類模型，  
並特別設計 **幾何保留策略（Geometry-Preserving Strategy）**，避免在資料增強過程中因過度旋轉影像而破壞腫瘤的重要空間位置資訊  
（例如：**垂體瘤通常位於影像中央**）。

---

## 🎥 Demo 演示
📺 點擊下方連結觀看系統實際操作影片：  
👉 [MRI 腦腫瘤分類系統 Demo 影片](https://drive.google.com/drive/folders/1ufUI_1adO4-r-xjZxLsLS2aNI07mXAfV?usp=sharing)
