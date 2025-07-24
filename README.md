# 🧠 Image Analyzer Chatbot

A full-stack Flask web application that allows users to upload one or more images and receive intelligent analysis, including:
- Object detection using YOLOv8
- Image captioning using BLIP
- Visual Question Answering (VQA) using BERT
- Natural language-based summaries of visual content

---

## 🚀 Demo

🔗 [Live Demo (Add your deployed URL here)](https://your-live-demo-url.com)

---

## 🎯 Use Case

This application is ideal for:
- Demonstrating Machine Learning model integration in web apps
- Image-based QA interfaces
- Showcasing full-stack AI skills for interviews or portfolios

---

## 🖼️ Application Flow

```text
     [User Uploads Image(s)]
               ↓
        Flask Backend Receives
               ↓
    ┌─────────────────────────────┐
    │    Image Processing Logic   │
    │                             │
    │  • YOLOv8 → Object Detection│
    │  • BLIP → Image Captioning  │
    │  • BERT → Visual QA         │
    └─────────────────────────────┘
               ↓
     [Summary Returned to Frontend]
               ↓
     [User Can Ask Further Questions]
