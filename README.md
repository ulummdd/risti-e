## Analisis dan Prediksi Performa Mahasiswa Menggunakan Model Regresi Terbaik
Ikhya Ulummuddin (20081010120)
### Pendahuluan
**Latar Belakang**  
Performa seorang mahasiswa dapat dipengaruhi oleh berbagai faktor, salah satunya dalah hasil nilai akademis. Faktor tersebut dapat membantu institusi pendidikan dalam mengambil langkah-langkah yang tepat agar dapat meningkatkan hasil pendidikan dengan cara menganalisis dan memprediksi performa mahasiswanya. Namun, banyaknya data dapat memakan banyak waktu dan sumber daya untuk melakukan proses aktivitas tersebut. Oleh karena itu, dibutuhkanlah program machine learning dengan model regresi terbaik untuk analisis dan prediksi performa mahasiswa. Ada beberapa model regresi yang dianalisis dan hanya digunakan salah satu dari yang terbaik, yaitu Linear regression, Lasso, Ridge, K-Neighbors, SVR, Decision tree, Random forest, dan Extra trees.

**Tujuan**  
Membuat program machine learning dengan model regresi terbaik untuk memprediksi performa mahasiswa kedepannya berdasarkan dataset yang tersedia.

**Rumusan Masalah**  
1. Bagaimana cara menganalisis dan memprediksi performa mahasiswa kedepannya menggunakan dataset yang tersedia.
2. Bagaimana cara membuat program machine learning untuk memprediksi performa mahasiswa kedepannya menggunakan dataset yang tersedia.
3. Bagaimana cara memilih model regresi terbaik untuk memprediksi performa mahasiswa kedepannya menggunakan dataset yang tersedia.

### Tinjauan Pustaka
**Model regresi**  
Model regresi merupakan teknik statistik yang befungsi dalam memahami hubungan antar satu atau banyak variabel prediktor dengan hasil prediksi. Ada beberapa jenis model regresi yang dapat digunakan untuk memprediksi sesuatu, seperti regresi linear, non-linier, dan logistik. Setiap jenis model regresi memiliki cara dan tipe prediksi masing-masing, tergantung dengan data yang ingin diprediksi.

**Prediksi performa**  
Performa baik dari setiap mahasiswa di dalam kampus sangat diperlukan agar mendapatkan hasil yang memuaskan. Tidak sedikit kampus yang ingin memprediksi performa para mahasiswanya untuk mengetahui kebutuhan apa yang harus dipenuhi. Ada beberapa faktor yang memengaruhi performa dari seorang mahasiswa, mulai dari latar belakang keluarga, motivasi, dan keterlibatan belajar.

### Metode Penelitian
**Dataset**  
Dataset yang digunakan dapat diakses melalui tautan sebagai berikut.  
https://docs.google.com/spreadsheets/d/1UZ_HSxKu2Bgppq9hYts71o8H0jlnbeBoQlI8Tm1AA7Y/edit?usp=sharing  

**Deskripsi data**  
Mengecek data yang kosong dan statistik deskriptif dari dataset.  

**Preprocessing data**  
Mengubah data kategorikal di dalam kolom menjadi numerik atau meng-encode-kan data agar bisa dilakukan proses selanjutnya.  

**Training model**  
Menggunakan beberapa model algoritma regresi dari scikit-learn, yaitu Linear regression, Lasso, Ridge, K-Neighbors, SVR, Decision tree, Random forest, dan Extra trees serta dievaluasi menggunakan metrik skor R2, Mean Absolute Error (MAE), dan Mean Squared Error (MSE). Hasil evaluasi model terbaik akan digunakan sebagai alat prediksi performa mahasiswa.

**Prediksi data**  
Prediksi IPK melalui data baru yang telah dimasukkan dan di-encode menggunakan model terbaik yang telah dievaluasi sebelumnya.  

### Hasil
**Distribusi data**  
- Data kategorikal  
![alt text](https://github.com/ulummdd/risti-e/blob/main/img/distrubusi-data-kategorikal.png?raw=true)
- Data numerikal  
![alt text](https://github.com/ulummdd/risti-e/blob/main/img/distrubusi-data-numerikal.png?raw=true)

**Evaluasi model**  
```
Evaluasi model Ridge():

Skor R2:
0.6042267438633778

Mean Absolute Error (MEA):
0.3729555533933517

Mean Squared Error (MSE):
0.21257139896400434
```

**Hasil prediksi**  
![alt text](https://github.com/ulummdd/risti-e/blob/main/img/hasil-prediksi.png?raw=true)

### Penutup
**Kesimpulan**  
