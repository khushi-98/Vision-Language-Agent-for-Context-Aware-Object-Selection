# Vision-Language-Agent-for-Context-Aware-Object-Selection

# Vision-Language-Agent-for-Context-Aware-Object-Selection

## 📌 Overview
This project implements a **Vision–Language Agent** that combines **computer vision** and **natural language understanding** to identify and select objects from images using human-like textual commands.  
A **custom-trained YOLO object detection model** is integrated with a **Large Language Model (FLAN-T5)** to enable **intent-aware, affordance-based, and spatially grounded object reasoning**.

The system supports interactive commands such as *"I want to write notes"* or *"Select the object left of the bottle"* and highlights the most relevant object accordingly.

---

## ✨ Features
- Custom-trained **YOLO object detection**
- Natural language **intent understanding**
- **Affordance-based object selection**
- **Spatial reasoning** (left, right, above, below)
- Context memory for reference resolution
- **LLM-based conversational responses**
- Visual object highlighting with bounding boxes

---

## 🛠️ Tech Stack
- **Python**
- **YOLO (Ultralytics)** – retrained on custom data
- **Hugging Face Transformers (FLAN-T5)**
- **OpenCV**
- **PyTorch**
- **Matplotlib**

---

## 🧠 System Workflow
1. User uploads an image  
2. Custom-trained YOLO detects objects in the image  
3. User provides a natural language command  
4. Intent and object affordances are extracted  
5. Spatial and contextual reasoning is applied  
6. Relevant object is selected and highlighted  
7. LLM generates a natural language response  

---

## 📂 Dataset & Model Training
- YOLO model is **retrained on custom datasets**
- Dataset contains task-specific objects such as:
  - Pen, pencil, bottle, book, calculator, ball, headphones
- Custom training improves detection accuracy in real-world desk and study environments

---

## 🏋️ Model Training
To train the YOLO model on custom data, run:

```bash
python finalcodetesting.py

