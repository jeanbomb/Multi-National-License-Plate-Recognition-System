# 多國車牌辨識系統 (Multi-National License Plate Recognition System)

本專案在 Kaggle 上開發，利用 YOLOv8 進行車牌偵測，並結合 EasyOCR、Tesseract 進行文字辨識，透過 OpenCV 進行影像處理，最後使用 Matplotlib 視覺化呈現結果。目前僅支援繁體中文與英文，辨識準確率仍有待提升。

## 📌 專案特色
- **YOLOv8 車牌偵測**：使用深度學習模型 YOLOv8 來準確偵測車牌位置。
- **OCR 文字辨識**：
  - **EasyOCR**：支援多國語言的快速辨識工具。
  - **Tesseract OCR**：進一步提升辨識精度。
- **OpenCV 影像處理**：強化影像品質，提高 OCR 讀取準確度。
- **Matplotlib 視覺化**：將偵測結果以圖像方式呈現。

## 📊 目前進度
✅ YOLOv8 訓練完成  
✅ EasyOCR + Tesseract 整合  
✅ 基本影像處理與視覺化  
❌ 仍有辨識錯誤，準確率待提升  

## 🔗 Kaggle 結果
🔍 [查看 Kaggle 結果](https://www.kaggle.com/code/game1g/yolov8-easyocr-tesseract-license-plate-detection)

## ⚙️ 主要技術
- **YOLOv8** (Ultralytics)
- **EasyOCR**
- **Tesseract OCR**
- **OpenCV**
- **Matplotlib**
- **Kaggle**

## 📌 未來改進方向
- **提升辨識準確率**
  - 增加數據增強 (Data Augmentation)
  - 微調 YOLOv8 參數
  - 測試不同影像處理方法
- **擴展語言支援**
  - 增加更多語言（目前僅支援繁中與英文）
