# 🧠 Multi-Modal Product Tagger (CLIP + SAM)

A powerful computer vision demo that combines [Segment Anything Model (SAM)](https://github.com/facebookresearch/segment-anything) by Meta and [CLIP](https://github.com/openai/CLIP) by OpenAI to **automatically segment and label objects in images** — all wrapped in a clean [Gradio](https://gradio.app) interface.

---

## 🔍 Overview

This project takes an input image, segments all objects using **SAM**, and classifies each object using **CLIP** against ImageNet labels. Results are visualized with bounding boxes and labels directly on the image.

---

## 🚀 Demo

![demo](https://user-images.githubusercontent.com/demo-placeholder.gif)

Try it locally using the Gradio interface — no complex UI code needed.

---

## 🧰 Features

- 🔍 Object segmentation using SAM
- 🧠 Semantic classification using CLIP
- 🎨 Real-time visualization of segments
- 🌐 Simple, shareable Gradio interface

---

## 🛠 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/multimodal-product-tagger.git
cd multimodal-product-tagger
# SAM-CLIP-Tagger
