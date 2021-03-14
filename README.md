# Neu_Portofolio
Final Project Data Science SA 


# TUGAS AKHIR 
## HR ANALYTICS : JOB CHANGE OF  DATA SCIENTISTS
![alt text](https://greatpeopleinside.com/wp-content/uploads/2019/06/analytics-1030x618.jpg)

## Latar belakang
* Proses rekrutmen Data Scientist.
* Perusahaan ingin mempekerjakan data scientist di antara orang-orang yang berhasil lulus dari beberapa pelatihan yang diselenggarakan oleh perusahaan. 
* Perusahaan ingin mengetahui kandidat mana yang benar-benar ingin bekerja untuk perusahaan setelah mengikuti pelatihan dan tidak akan mencari pekerjaan baru, sehingga dapat membantu mengurangi biaya dan waktu dalam pencarian kandidat yang tepat.

## Tujuan
untuk mengaplikasikan supervised learning dalam memahami hal-hal sebagai berikut:
* Prediksi adanya kemungkinan seseorang untuk mencari pekerjaan baru.
* Identifikasi faktor yang berpengaruh kepada keputusan karyawan.

## Manfaat
### Praktis
* Sebagai dasar pertimbangan dalam menentukan kandidat yang tepat sesuai dengan sasaran sehingga proses rekrutmen bisa berjalan efektif dan efisien.
* Dapat menambah wawasan dan pengalaman langsung tentang pengaplikasian machine learning dalam penelitian
### Teoritis
* Sebagai referensi literatur bagi pembelajaran data science, khususnya machine learning.
* Sebagai pijakan pada project selanjutnya yang berhubungan dengan pengaplikasian  machine learning di bidang lainnya.

***
## EDA
***
melihat hubungan target dengan kategori-kategori  

![alt text](https://github.com/pembelajardata/Neu_Portofolio/blob/main/EDA1.png)
![alt text](https://github.com/pembelajardata/Neu_Portofolio/blob/main/EDA2.png)
![alt text](https://github.com/pembelajardata/Neu_Portofolio/blob/main/EDA4.png)
![alt text](https://github.com/pembelajardata/Neu_Portofolio/blob/main/EDA5.png)
![alt text](https://github.com/pembelajardata/Neu_Portofolio/blob/main/EDA6.png)
![alt text](https://github.com/pembelajardata/Neu_Portofolio/blob/main/EDA7.png)
![alt text](https://github.com/pembelajardata/Neu_Portofolio/blob/main/EDA8.png)
![alt text](https://github.com/pembelajardata/Neu_Portofolio/blob/main/EDA9.png)
![alt text](https://github.com/pembelajardata/Neu_Portofolio/blob/main/EDA10.png)
![alt text](https://github.com/pembelajardata/Neu_Portofolio/blob/main/EDA11.png)
![alt text](https://github.com/pembelajardata/Neu_Portofolio/blob/main/EDA12.png)
Distribusi untuk jumlah jam pelatihan cenderung positively skewed dengan nilai mean lebih besar  dari median.


### Hasil pengamatan:
1. Ada kemungkinan jenis kelamin tidak dapat menjadi prediktor yang baik untuk orang yang ingin berganti pekerjaan.
2. Jika seseorang tidak memiliki pengalaman relevan sebelumnya, kemungkinan besar dia akan mencari pekerjaan baru.
3. Mereka yang mendaftar untuk kursus penuh waktu lebih cenderung mencari pekerjaan baru.
4. Mereka yang memiliki sedikit atau tanpa pengalaman kerja (yaitu, pengalaman kerja kurang dari 1 tahun) adalah yang paling mungkin untuk mencari pekerjaan baru, dengan kata lain, semakin banyak pengalaman yang Anda miliki, semakin kecil kemungkinan Anda akan mencari pekerjaan. untuk pekerjaan baru.
5. Perbedaan tahun antara pekerjaan sebelumnya dan pekerjaan saat ini, berkorelasi negatif dengan kemungkinan mencari pekerjaan baru, semakin besar jangka waktu pekerjaan yang Anda miliki sebelumnya, semakin kecil kemungkinan Anda mencari pekerjaan baru. 
6. CDI memberikan insight, secara umum semakin kecil CDI, semakin besar kemungkinan dia akan melakukannya. mencari pekerjaan baru. 


![image](https://user-images.githubusercontent.com/80607564/111066239-80a13c80-84f0-11eb-9d9a-91f3ae7c516c.png)


## Categorical Data

![alt text](https://github.com/pembelajardata/Neu_Portofolio/blob/main/Categorical%20Data.png)

## Balancing Data

![alt_text](https://github.com/pembelajardata/Neu_Portofolio/blob/main/Balancing%20Data1.png)

## Classification Selection

![alt_text](https://github.com/pembelajardata/Neu_Portofolio/blob/main/Classification%20Selection.png)

## Spliting & Scaling Data

![alt_text](https://github.com/pembelajardata/Neu_Portofolio/blob/main/Spliting%20%26%20Scaling%20Data.png)

## Modeling

### LogisticRegression

### RandomForest

### Gradient Boosting

### XGBoosting

## Kesimpulan
1. Dari beberapa model klasifikasi yang diuji untuk memprediksi “Job change of Data Scientist” diperoleh hasil terbaik dengan menggunakan model klasifikasi Gradient Boosting dengan hasil precision prediksi mencapai 83%, dan setelah dilakukan hyperparameter tunning mencapai 79%.
2. Faktor-faktor yang dapat digunakan untuk menentukan apakah seseorang akan bekerja untuk perusahaan setelah mengikuti pelatihan dan tidak akan mencari pekerjaan baru antara lain kota, indeks perkembangan kota (CDI), total pengalaman dalam beberapa tahun, jenis kelamin laki-laki, serta memiliki pengalaman yang relevan. 



