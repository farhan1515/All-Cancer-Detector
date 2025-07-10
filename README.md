# 🧠 All-Cancer-Detector: Real-Time Cancer Detection using XAI and LLM

A real-time cancer detection application designed to assist doctors and engineers with interpretable medical image analysis using advanced Explainable AI (XAI) techniques and Large Language Models (LLMs).

## 💡 Key Features

- 🖼️ Upload or capture MRI images for instant processing.
- 📊 Utilizes Grad-CAM, Saliency Maps, and LIME for visual explanations of tumor predictions.
- 🤖 Generates human-friendly confidence reports and technical insights using an embedded LLM engine.
- 🩺 Dual Interface: Designed for both **Doctors/Engineers** and **Patients** for tailored explanations.

## 🚀 How It Works

- The model predicts presence of tumors in real-time from medical images.
- XAI modules highlight the regions of interest for enhanced interpretability.
- LLM provides patient-friendly summaries and technical insights based on the output.

## 🖼️ Screenshot

![screenshot](https://github.com/user-attachments/assets/6d7938c6-f3a2-471e-ab78-32560b0e6e2a)




## 🛠️ Tech Stack

- Python (Tkinter GUI)
- Grad-CAM, Saliency Map, LIME (Explainable AI)
- Pre-trained CNN Model
- OpenAI-compatible LLM for generating output text

## 📂 Output Format

- JSON output with model prediction, confidence level, XAI visualization, and LLM explanation.
- Sample path: `real_time_xai_output.json`

## 📌 Use Case

This tool is intended for assisting early detection and interpretation of cancer in histopathology or MRI scans and can be extended to other medical diagnostics use cases.


