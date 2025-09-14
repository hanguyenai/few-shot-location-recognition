# 🏞️ Few-Shot Location Recognition in TRECVID2022-DVU

This repository contains a **Jupyter-based implementation** for **few-shot location recognition** using **transfer learning with VGG16**.  
The task focuses on recognizing locations with **very limited training samples** — only **3–7 images per class** — as defined in the **[TRECVID2022-DVU dataset](https://www-nlpir.nist.gov/projects/tv2022/dvu.html)**.

---

## ✨ Key Features
- **Few-shot learning**: each location has only 3–7 annotated images.  
- **Data augmentation**: rotation, flipping, brightness/contrast adjustment, zoom, and cropping to improve generalization.  
- **Transfer learning**: VGG16 pretrained on ImageNet is fine-tuned for location recognition.  
