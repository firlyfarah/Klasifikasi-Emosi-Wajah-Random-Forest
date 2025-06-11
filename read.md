# 😃 Penerapan Random Forest dalam Deteksi dan Klasifikasi Emosi Wajah Berbasis Citra Digital

Proyek ini menerapkan algoritma **Random Forest** untuk mendeteksi serta mengklasifikasikan ekspresi emosi pada wajah manusia menggunakan data citra. Pendekatan ini mampu menangani kompleksitas visual data wajah dengan tetap mempertahankan fitur-fitur paling representatif untuk tugas klasifikasi emosi.

## 📊 Dataset
Dataset yang digunakan adalah **FER-2013** (Facial Expression Recognition 2013), tersedia di:
👉 [https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer](https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer)

Dataset ini berisi lebih dari 35.000 gambar wajah berukuran 48x48 piksel yang diklasifikasikan ke dalam 7 emosi:  
- **Angry**
- **Disgust**
- **Fear**
- **Happy**
- **Sad**
- **Surprise**
- **Neutral**

## 🧪 Metodologi
1. **Pra-pemrosesan Data:**
   - Resize gambar
   - Normalisasi pixel
   - Augmentasi 

2. **Deteksi Wajah:**
   - Menggunakan Haar Cascade
   - Mengisolasi area wajah untuk ekstraksi fitur

3. **Klasifikasi:**
   - **Random Forest Classifier**
   - Tuning parameter seperti jumlah dan kedalaman pohon
   - Pelatihan model pada data latih, evaluasi pada data uji

4. **Evaluasi Model:**
   - Metrik evaluasi: Accuracy, Precision, Recall, F1-Score

## 👩‍💻 Author

- Alin Tifana Safitri: [@alintifana9306](https://github.com/alintifana9306)
- Firly Farah Aulia: [@firlyfarah](https://github.com/firlyfarah)
- Jesika Trisyanda

