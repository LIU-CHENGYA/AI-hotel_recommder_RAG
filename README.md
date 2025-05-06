# AI-hotel_recommder_RAG

本專案使用 OpenAI GPT API 與 LangChain 設計一個智慧型台灣飯店推薦機器人，能夠根據使用者需求（如地點、預算、設施）進行多輪對話式推薦

## 使用技術

- Python, LangChain, OpenAI GPT API,Gradio
- 向量資料庫
- 運用RAG技術
- 飯店資料集（自建或開放資料）

## 功能簡介

- 對話式飯店推薦
- 根據輸入自動篩選飯店並回覆說明
- 可處理多輪提問與偏好調整
- 回覆內容可自定格式

##  專案結構

- `main.py`：主程式邏輯
- `打造虛擬的住宿資料.ipynb`：打造台灣飯店資料（可使用開放資料來源）
- `建立向量資料庫.ipynb`:建立向量資料庫
- `台灣飯店推薦RAG_系統.ipynb`：Colab 上的示範版本

##  Demo 示範

[Colab Demo 連結](https://colab.research.google.com/drive/1W292XGzMidcxxJTEYkaGmDhtkiRqNmM8?usp=sharing)

##  開發動機

本專案為課程作業的內容， 主要學習與實際運用RAG與向量資料庫，並學習 API 應用及 LangChain 建構流程的實作。目的是結合資料處理與語言模型能力，打造簡易的 AI 旅遊助手原型。
