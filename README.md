# FYP_Prototype_Phase
## **Deepfake Detection Prototype**

A **clean, fully TensorFlow-based deepfake detection prototype** built with a focus on **simplicity, maintainability, and real-time performance**.

After wrestling with complex PyTorch-to-TensorFlow conversions, I went back to the drawing board to build something I could **understand, debug, and deploy with confidence**.

### **Core Components**

* **Spatial Feature Extraction**: Pretrained **XceptionNet** (ImageNet) — fast, stable, efficient.
* **Temporal Modeling**:

  * **InceptionResNetV2** for per-frame feature extraction
  * **Custom C3D-inspired block** with skip connections and depthwise separable 3D convolutions
  * **StandardAttention layer** to highlight temporal relevance
  * **Regularized classifier** for robust predictions
* **End-to-End TensorFlow Pipeline**: No conversions, no wrappers, fully optimized for both **video uploads** and **real-time streaming**.

### **Room for Improvement**

This prototype is **not perfect** — it has a lotttt of room for improvement, which I tried to address in my final version that I might put up later.
