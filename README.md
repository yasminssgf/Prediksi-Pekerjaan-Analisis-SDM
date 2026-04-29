# Prediksi Pekerjaan Analisis SDM

Proyek ini merupakan proyek yang merupakan tugas dari kursus advanced data analytics yang merupakan kursus sertifikasi data analysis yang diadakan oleh coursera.

**Tujuan**
Untuk merancang sebuah model yang memprediksi apakah seorang karyawan akan meninggalkan perusahaan berdasarkan jabatan, departemen, jumlah proyek, jam kerja bulanan rata-rata, dan poin data relevan lainnya. 

**Problem**

Salifort Motors berupaya meningkatkan retensi karyawan dan menjawab pertanyaan berikut:

"Apa yang kemungkinan besar akan membuat karyawan meninggalkan perusahaan?"


### Mempelajari dan Memahami dataset HR

Pada [dataset](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv) ini, Terdapat 14.999 baris, 10 kolom, dan variabel-variabel berikut:

Variabel  |Deskripsi |
-----|-----|
satisfaction_level|Tingkat kepuasan kerja yang dilaporkan oleh karyawan [0&ndash;1]|
last_evaluation|Skor penilaian kinerja terakhir karyawan [0&ndash;1]|
number_project|Jumlah proyek yang dikerjakan karyawan|
average_monthly_hours|Rata-rata jumlah jam kerja karyawan per bulan|
time_spend_company|Lama masa kerja karyawan di perusahaan (tahun)
Work_accident|Apakah karyawan tersebut mengalami kecelakaan saat bekerja atau tidak
left|Apakah karyawan tersebut meninggalkan perusahaan atau tidak
promotion_last_5years|Apakah karyawan tersebut dipromosikan dalam 5 tahun terakhir atau tidak
Department|Departemen karyawan
salary|Gaji karyawan (U.S. dollars)

**Ringkasan**

Karena variabel yang ingin diprediksi bersifat kategorikal, tim dibangun model regresi logistik atau model pembelajaran mesin berbasis pohon. Model random forest sedikit lebih unggul daripada model decision tree.

Model ini membantu memprediksi apakah seorang karyawan akan keluar dan mengidentifikasi faktor mana yang paling berpengaruh. Wawasan ini dapat membantu HR dalam mengambil keputusan untuk meningkatkan retensi karyawan.

**Rekomendasi**

* Batasi jumlah proyek yang dapat dikerjakan oleh karyawan.
* Pertimbangkan untuk mempromosikan karyawan yang telah bekerja di perusahaan setidaknya selama empat tahun, atau lakukan penyelidikan lebih lanjut tentang mengapa karyawan yang telah bekerja selama empat tahun begitu tidak puas.
* Berikan penghargaan kepada karyawan yang bekerja lembur, atau jangan mewajibkan mereka untuk melakukannya.
* Jika karyawan belum familiar dengan kebijakan pembayaran lembur perusahaan, beri tahu mereka tentang hal ini. Jika ekspektasi terkait beban kerja dan waktu istirahat tidak dijelaskan secara eksplisit, jelaskan dengan jelas.
* Selenggarakan diskusi di seluruh perusahaan dan di dalam tim untuk memahami dan mengatasi budaya kerja perusahaan, secara menyeluruh dan dalam konteks spesifik.
* Nilai evaluasi tinggi tidak seharusnya hanya diberikan kepada karyawan yang bekerja lebih dari 200 jam per bulan. Pertimbangkan skala proporsional untuk memberi penghargaan kepada karyawan yang memberikan kontribusi lebih banyak/mencurahkan lebih banyak usaha.





