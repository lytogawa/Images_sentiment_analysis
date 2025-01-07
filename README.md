# Images_sentiment_analysis
Project images sentiment analysis

## Domain Proyek
Proyek ini berfokus pada analisis sentimen gambar, suatu domain yang relevan dengan bidang pembelajaran mesin dan visi komputer. Analisis ini bertujuan untuk mengevaluasi perasaan atau opini yang dapat diungkapkan oleh gambar berdasarkan konteks visualnya. Pendekatan ini berpotensi diterapkan dalam berbagai sektor, seperti pemasaran digital, analisis media sosial, dan aplikasi surveilans.

## Business Understanding
Tujuan utama proyek ini adalah memahami bagaimana gambar tertentu dapat mencerminkan sentimen tertentu, seperti positif, negatif, atau netral. Proyek ini dirancang untuk memberikan wawasan bisnis kepada perusahaan atau individu yang ingin memahami opini publik terhadap produk atau layanan mereka berdasarkan data visual.

## Data Understanding
Dataset yang digunakan terdiri dari data kuantitatif dengan lebih dari 500 sampel gambar, tepatnya 15.627 gambar yang dikategorikan berdasarkan sentimen menjadi 7 kelas. Setiap gambar diberi label sesuai sentimen untuk melatih model. Data telah diperiksa untuk memahami distribusi kategori sentimen, serta pola-pola visual yang mendukung analisis lebih lanjut. Sumber dataset : https://www.kaggle.com/datasets/nicolejyt/facialexpressionrecognition

### Memuat dataset
<img width="865" alt="Screenshot 2025-01-07 at 06 32 23" src="https://github.com/user-attachments/assets/84117f42-c8f0-43a9-a211-fc05ed3c86da" />

### Menampilkan tipe data dan missing value
<img width="877" alt="Screenshot 2025-01-07 at 06 33 14" src="https://github.com/user-attachments/assets/e1fe9908-45ac-4f29-ab93-27f5a6e17dbd" />

### Mapping emotion label berdasarkan dari dataset FER2013
<img width="863" alt="Screenshot 2025-01-07 at 08 49 49" src="https://github.com/user-attachments/assets/9d790011-e052-4f6c-94be-ff818659e778" />

### Mengkonversi pixel string ke array dengan ukuran 48x48
<img width="864" alt="Screenshot 2025-01-07 at 08 58 33" src="https://github.com/user-attachments/assets/ce72df62-ba84-43e3-b955-0ddc8734a96a" />

### Melihat kolom pada dataset dan juga head pada data
<img width="863" alt="Screenshot 2025-01-07 at 09 03 46" src="https://github.com/user-attachments/assets/73935a33-33c6-4107-87d8-c108475bd9c3" />

## Data Preparation

### Load dataset dan assign nama kolom
<img width="866" alt="Screenshot 2025-01-07 at 09 36 15" src="https://github.com/user-attachments/assets/d55629a4-d029-4c9e-8d86-4b7bf598ddd4" />

### Split dataset berdasarkan kolom Usage
<img width="863" alt="Screenshot 2025-01-07 at 09 37 08" src="https://github.com/user-attachments/assets/4e975e94-c253-4054-911c-fc20f515f226" />

### Mengulangi langkah convert string ke array dan drop data yang memiliki invalid rows
<img width="865" alt="Screenshot 2025-01-07 at 10 17 51" src="https://github.com/user-attachments/assets/be7a1e78-fc3c-45cb-be77-6703f495942d" />

### Hasil finalisasi dari beberapa langkah preprosesing diatas dan menampilkan contoh sample gambar dengan label
<img width="890" alt="Screenshot 2025-01-07 at 10 21 30" src="https://github.com/user-attachments/assets/447a84c4-4cbd-4223-b876-71308eb41e9a" />

### Menampilkan 9 sample gambar dengan label
<img width="889" alt="Screenshot 2025-01-07 at 10 23 06" src="https://github.com/user-attachments/assets/fe137db3-cbc2-45d6-91c8-9c9264d5239f" />

### Plot distribusi emotion
<img width="892" alt="Screenshot 2025-01-07 at 10 24 10" src="https://github.com/user-attachments/assets/538de136-a042-48d9-8d2a-6ca7360742f8" />

## Model Development

### Flatten semua pixel dan ploting histogram
<img width="890" alt="Screenshot 2025-01-07 at 10 44 41" src="https://github.com/user-attachments/assets/305fdaa4-58c9-4e0f-aeba-5ef9b0409700" />

### Menampilkan sample image setelah di flatten
<img width="891" alt="Screenshot 2025-01-07 at 10 45 53" src="https://github.com/user-attachments/assets/40bd06c8-d6ff-410a-b214-6d1ecad44680" />

### Data kemudian di augmentasi
<img width="890" alt="Screenshot 2025-01-07 at 10 46 39" src="https://github.com/user-attachments/assets/7bfd2ad0-44fb-4277-833b-c0ad2490f621" />

### Pendistribusian emotion per data split
<img width="890" alt="Screenshot 2025-01-07 at 10 47 25" src="https://github.com/user-attachments/assets/c8f996bc-926c-484a-97eb-96c9cffc7f04" />

## Evaluation Model

### Training data dan evaluasi model
<img width="889" alt="Screenshot 2025-01-07 at 10 49 07" src="https://github.com/user-attachments/assets/5152a68b-e224-458a-9ca9-1de7aef1e840" />

### Hasil training model
<img width="866" alt="Screenshot 2025-01-07 at 19 46 04" src="https://github.com/user-attachments/assets/062a39d6-0205-47cd-8a29-14d83ece71cf" />

## Kesimpulan
Pada images sentiment analysis disini menggabungkan antara sentiment analysis berbasis gambar, dimana saat ini hasilnya sudah menunjukkan klasifikasi sentimen berdasarkan image namun masih perlu banyak perbaikan untuk dapat meningkatkan akurasi.



















