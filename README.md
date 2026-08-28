# Penerapan Deep Learning untuk Klasifikasi Penyakit Jantung Berdasarkan Dataset UCI Heart Disease 
Penerapan metode Deep Learning untuk Klasifikasi Penyakit Jantung Berdasarkan Dataset UCI Heart Disease dengan Evaluasi Akurasi dan Recall.

<img width="1600" height="1077" alt="hdl" src="https://github.com/user-attachments/assets/78b54603-18fd-465d-8407-d0f64b5c3333" />


1. Business Problem Understanding
Tujuan :
- Memprediksi apakah seorang pasien memiliki penyakit jantung (1) atau tidak (0)

Manfaat :
- Membantu Diagnosis Awal
- Membantu Dokter untuk penanganan agar lebih tepat.

2. Data Collection and Data Cleaning
Dataset kurang lebih sudah optimal, pada data collection tidak perlu tindakan lebih lanjut.

3. Pre-processing data
   
<img width="1171" height="950" alt="image" src="https://github.com/user-attachments/assets/a3c18d51-d3c1-44fd-994e-682a77a4fb28" />

Pada kode diatas ada beberapa penjelasan : 
- Normalisasi digunakan untuk menjadikan semua fitur memiliki rentang nilai yang sebanding (biasanya 0–1)
- Memisahkan X dan Y, disini y untuk menentukan pasien itu memiliki penyakit jantung atau tidak.
- Karna disini klasifikasi, kita harus melakukan split data yaitu membagi data training dan data testing dengan perbandingan data training 80% dan data testing 20%.
- Setelah membagi data split, kita memodelkan data menggunakan DNN (Deep Neural Network) yang mana model pembelajaran mesin yang meniru cara otak manusia memproses informasi.
- Setelah itu kita uji coba datanya, menggunakan 50 epocs.

4. Hasil
Pada pengujian pertama didapatkan
- Akurasi : 80%

<img width="1255" height="582" alt="image" src="https://github.com/user-attachments/assets/195ca029-ae23-4a93-89c6-c0c3388d97a4" />


Karena akurasi yang didapat hanya 80% kita melakukan improvisasi agar nilai akurasinya lebih tinggi menggunakan TensorFlow (Keras)

Maka didapat akurasi bertambah 2%, yaitu 82%. dengan ROC Score : 89%

<img width="655" height="587" alt="image" src="https://github.com/user-attachments/assets/9fc5f96f-270f-4d57-b9ab-7fe4ef01f9b3" />

<img width="834" height="710" alt="image" src="https://github.com/user-attachments/assets/d17d99f7-59f9-41e0-a817-7cea26cdcaad" />

<img width="1284" height="728" alt="image" src="https://github.com/user-attachments/assets/ebb338e4-3e34-4d81-a4ec-ada669c2d30e" />


Link Google Collab : 
https://colab.research.google.com/drive/12bCxcSvP415SbI0yRR75cNaTmxCTaxCR?usp=sharing

