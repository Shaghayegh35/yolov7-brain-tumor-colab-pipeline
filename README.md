# YOLOv7 – Brain Tumor Detection (Google Colab Pipeline)

This repository contains a **Google Colab** script that trains, evaluates, and runs inference using **YOLOv7** on the **Figshare Brain Tumor Dataset** (Kaggle mirror).  
It sets up Google Drive paths, creates **empty labels for non-tumor images**, builds a dataset config, downloads pretrained weights, and then runs **train → test → detect**. Finally, it displays a few prediction images in-notebook.

> Task: **object detection** with a single class (`tumor`).  
> If you want *segmentation masks*, use **yolov7-seg** and the appropriate cfg instead.

---

## 🚀 Quickstart (Colab)

1. Open the notebook (or a new Colab) and paste the code from `colab_yolov7_tumor.py` (or use a `.ipynb`).
2. **Runtime → Change runtime type → GPU** (T4/Volta preferred).
3. Set your Google Drive base path:
   ```python
   base_path = '/content/drive/MyDrive/yolov7_tumor_segmentation'
   ## ✍️ Author
**Shaghayegh Khalighiyan**  
- Email: khaliqianshaqayeq@gmail.com
- LinkedIn: www.linkedin.com/in/shaghayegh-khalighiyan-493155199 
- GitHub: https://github.com/Shaghayegh35

