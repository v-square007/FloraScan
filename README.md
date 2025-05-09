# 🌱 FLORASCAN – AN AI-DRIVEN PLANT DISEASE DETECTION SYSTEM FOR SUSTAINABLE AGRICULTURE

**FloraScan** is an AI-driven plant disease detection system built with a lightweight custom CNN model. It empowers farmers with real-time, multilingual diagnosis of plant diseases, offering actionable treatment suggestions and prevention techniques even in remote or low-resource agricultural settings.

---

## 🔍 Features

- ✅ **Custom CNN** trained on 87,000+ images across 38 disease classes
- 🌐 **Multilingual interface** for inclusive usage
- ⚡ **Real-time predictions** (~2s inference time on-device)
- 🌿 Designed for **smallholder and rural farmers**
- 📊 **~99% accuracy** in field tests

---

## 📁 Project Structure

| File/Folder | Description |
|-------------|-------------|
| `FloraScan_Streamlit.pynb` | Streamlit web app for diagnosis |
| `train_plant_disease.ipynb` | Custom CNN training notebook |
| `test_plant_disease.ipynb` | Testing & inference notebook |
| `model_weights/` | Folder to place downloaded model |
| `requirements.txt` | Python dependency list |
| `assets` | Screenshots and demo media |

---

## 📥 Download Model

Due to size limitations, the trained CNN model is hosted externally.

- ⬇️ Download [`florascan_model.h5`](https://drive.google.com/drive/folders/1bvsbJHdUdGvrcvthH_RGgxCZhi_oyiCf?usp=drive_link)
- After downloading, **place it inside the `model_weights/` folder**.

---

## ⚙️ Setup Instructions

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/FloraScan.git
cd FloraScan
pip install -r requirements.txt
