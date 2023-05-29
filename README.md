# Capstone Project Module 3 : Machine Learning
Capstone Project 3 JCDSOL Purwadhika Batch 09 : Machine Learning
Nama : Estevani Linggi Tambane
Case Studi : Daegu Apartment Price Prediction

**Context**

Daegu merupakan kota terbesar ke-3 di Korea Selatan setelah Seoul dan Busan. Memiliki Penduduk sekitar 2,5 Juta jiwa. Daegu dikelilingi oleh pegunungan Palgong-san di utara, Biseul-san di selatan, kaki bukit Gaya-san di barat, dan satu deretan bukit kecil di timur.Dengan pemandangan indah dan suasana yang tampak cukup sejuk ini, Daegu tetap saja seperti kota-kota metropolitan lainnya. Kehidupan perkotaan yang padat penduduk namun lahan terbatas membuat Daegu seperti kota metropolitan lainnya yang mengandalkan apartment sebagai pilihan untuk tempat tinggal penduduknya. Karena perkembangan Daegu yang pesat, permintaan akan perumahan apartemen pun meningkat. Hingga pada tahun 2021, jumlah total gedung apartemen di Daegu, Korea Selatan sudah mencapai jumlah kurang lebih 240 ribu. Di Korea Selatan sendiri terutama di kota-kota besar kebanyakan orang lebih memilih menjual/membeli apartment melalui agen properti. Ini membuat banyaknya agen properti yang menjajakan jasanya dalam membantu menjual atau membeli apartment. Karena jika menggunakan jasa agen properti, pembeli maupun penjual tidak perlu kesusahan dalam transaksi maupun pengurusan surat-surat.

[sumber 1](https://en.wikipedia.org/wiki/Daegu)<br>
[sumber 2](https://www.statista.com/statistics/1303257/south-korea-apartments-in-daegu-by-number-of-stories/#statisticContainer)

**Problem Statement**

Dibutuhkan model yang tepat untuk menyelesaikan masalah penentuan harga jual apartment. Dengan harapan dapat menghasilkan keuntungan kepada pemilik maupun agen properti dengan menentukan harga jual apartemen yang lebih kompetitif. Dengan kata lain, agar harga jual apartemen dalam wilayah Daegu memiliki rata-rata harga yang tidak berbeda jauh antar satu dengan yang lainnya.

**Goals** 

Berdasarkan permasalahan yang ada, Agen properti tentu perlu memiliki 'tool' yang dapat memprediksi serta membantu klien mereka (dalam hal ini pemilik apartemen) **untuk dapat menentukan harga jual properti yang tepat**. Adanya perbedaan pada berbagai fitur yang terdapat pada suatu properti, seperti tahun dibangunnya, jarak ke fasilitas publik terdekat, lokasi, dan tipe apartemen dapat meningkatkan keakuratan prediksi harga jual yang mana diharapkan dapat menghasilkan profit bagi pemilik apartemen.

**Analytic Approach**

Jadi, yang perlu kita lakukan adalah menganalisis data untuk dapat menemukan pola dari fitur-fitur yang ada, yang membedakan satu apartment dengan yang lainnya.
Selanjutnya, kita akan membangun suatu model regresi yang akan membantu pemilik unit untuk dapat menyediakan 'tool' prediksi harga unit , yang mana akan berguna untuk pemilik dalam menentukan harga unit.

**Metric Evaluation**

Metric evaluation yang digunakan untuk model regresi adalah RMSE, MAE, MAPE. Namun MAPE dipilih sebagai metric evaluation paling utama untuk memberikan hasil yang mudah diinterpretasikan dan dapat membantu dalam menjelaskan kesalahan prediksi kepada stakeholder yaitu agent real estate.
