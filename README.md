## Tugas 02 Pembelajaran Mesin
Nama : Furqan Ramadhan
NPM  : 2108107010013

## Petunjuk Tugas
Artikel berikut menjadi referensi dalam mengerjakan Tugas 2 - Pembelajaran Mesin:

https://medium.com/@youness.habach/support-vector-machines-svm-explanation-mini-project-9d4b4962be52

Anda diminta untuk menggunakan SVM dalam menyelesaikan 2 kasus yaitu Klasifikasi dan Regresi dengan menggunakan dataset yang tidak sama dengan dataset yang ada pada referensi.

Tugas dikumpulkan melalui Repository Github yang berisi:

- Source code Regresi
- Source code Klasifikasi
- README.md (Penjelasan tentang cara menjalankan source code dan dataset yang digunakan)

# Penjelasan 
Tugas 02 menjelaskan tentang membangun model machine learning dengan Supervised Learning yaitu algoritma Support Vector Machine (SVM) dan Support Vector Regression (SVR), dimana label sudah diketahui dan bagaimana membangun dan melatih model berdasarkan fitur yang ada. Juga diperhatikan akurasi dan nilai koefisien matrix, serta visualisasi plot.

1. Support Vector Machine
Dataset berisikan tentang sample darah dari beberapa ratus catatan sel manusia, yang masing-masing berisi nilai dari sekumpulan karakteristik sel. Terdapat atribut dengan keterangan sebagai berikut

| **Field**         | **Keterangan**                |
|:------------------|:-----------------------------:|
| `ID`              | Item data                     |
| `Clump`           | Clump thickness               |
| `UnifSize`        | Uniformity of cell size       | 
| `UnifShape`       | Uniformity of cell shape      | 
| `MargAdh`         | Marginal adhesion             | 
| `SingEpiSize`     | Single epithelial cell size   | 
| `BareNuc`         | Bare nuclei                   | 
| `BlandChrom`      | Bland chromatin               | 
| `NormNucl`        | Normal nucleoli               | 
| `Mit`             | Mitoses                       | 


Label yang akan dijadikan target adalah Class, dimana class 2 adalah sel kanker yang bersifat jinak, dan class 4 adalah sel kanker yang bersifat ganas. Kita ingin mengetahui persebaran dari dataset tersebut, untuk mengetahui seberapa besar akurasi model dengan tanpa parameter, di tuning dengan default paramater, atau menggunakan rbf kernel dengan nilai c yang diperlukan untuk membuat akurasi semakin baik.  



2. Support Vector Regression
Dataset berisikan tentang fitur fitur yang mengkalkulasikan sebuah konstruksi bangunan dengan kekuatan Concrete Strength. Adapun variabel independen nya adalah Cement dan variabel dependennya adalah 'Strength'. Kita ingin melihat seberapa besar korelasi antara keduanya dengan atribut sebagai berikut


| **Field**              | **Keterangan**                              |
|:-----------------------|:-------------------------------------------:|
| `Cement`               | Amount of cement used                       |
| `Blast Furnace Slag`   | Slag Produced in Blast Furnace              |
| `Fly Ash`              | Amount of ash produced                      | 
| `Water`                | Amount of water required                    | 
| `Super-plasticizer`    | Rigidity of cement after drying             | 
| `Coarse Aggregate`     | The coarse nature of the cement particles   | 
| `Fine Aggregate`       | Fineness of the cement                      | 
| `Age`                  | Age or time before it needs repairing       | 
