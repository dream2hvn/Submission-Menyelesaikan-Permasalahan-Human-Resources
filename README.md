# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Jaya Jaya Maju

## ***Business Understanding***

Jaya Jaya Maju 🌟 adalah sebuah perusahaan multinasional yang didirikan pada tahun 2000. Perusahaan ini memiliki lebih dari 1000 karyawan 👥 yang tersebar di berbagai daerah di seluruh negara 🇮🇩.

### Permasalahan Bisnis

Meskipun telah berkembang menjadi perusahaan yang cukup besar 📈, Jaya Jaya Maju masih berjuang untuk mengelola karyawannya dengan efektif. Tingginya tingkat attrisi 📊, yang mencapai lebih dari 10% 🚪, menjadi sinyal bahwa ada yang tidak beres. Karyawan yang pergi meninggalkan jejak pertanyaan: "Apa yang salah?"

### Cakupan Proyek

Dalam proyek ini, kita berkomitmen untuk menggali lebih dalam 🔍. Kita akan mengidentifikasi berbagai faktor yang berkontribusi terhadap tingginya tingkat attrisi 📉 dan menciptakan sebuah business dashboard 📊 yang akan membantu memantau faktor-faktor tersebut. Dengan menggunakan data karyawan dan alat seperti Looker Studio dan bahasa pemrograman Python, kita akan menciptakan visualisasi dan pengembangan model machine learning ke dalam proyek ini.

### Persiapan
Sumber data: https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee <br>
Proyek ini dibuat melalui Google Colaboratory (Google Colab).
```
https://colab.research.google.com/drive/16ZtTSCnY4v9akQoj2ZrQx1CAyNQmh13y?usp=sharing
```
Namun jika tidak menggunakan colab anda bisa menggunakan Jupyter Notebook, ikuti langkah setup environment dibawah ini:
```
pip install numpy==2.0.2 matplotlib==3.10.0 seaborn==0.13.2 scikit-learn==1.6.1 pandas==2.2.2 joblib==1.4.2
```

### Business Dashboard
Business dashboard menggunakan dataset yang telah melalui tahapan persiapan. Dataset tersebut diekspor dalam format CSV dari notebook.ipynb dan setelah itu diimpor ke dalam Looker Studio. Selain itu, pada Looker Studio ada penyesuaian dan modifikasi tipe data pada beberapa variabel. 

#### Isi dari Dashboard
Pada dashboard yang sudah saya buat, terdapat filter yang terdiri dari gender, age, attrition, dan juga ada jumlah karyawan. <br>
    
Lalu ada 2 tabel: <br>
    1.Employee by Job Level: Jenjang pekerjaan yang dipegang oleh setiap karyawan<br>
    2.Employee by Education Field: Bidang pendidikan yang ditempuh oleh masing-masing karyawan<br>
    
Ada 3 Pie Chart: <br>
    1. Employee by Gender: Jenis kelamin dari tiap karyawan<br>
    2. Employee by Distance: Jarak antar rumah karyawan dengan perusahaan<br>
    3. Employee by Marital status: Status pernikahan dari setiap karyawan<br>
     
Selanjutnya, ada grafik yang terdiri dari 3 grafik: <br>
    1. Employee by Age Group: menjelaskan jumlah persebaran tiap karyawan berdasarkan umur yang ada di perusahaan tersebut<br>
    2. Employee by Education: background pendidikan dari karyawan<br>
    3. Employee by Involvement: menjelaskan mengenai keterlibatan karyawan dengan project yang sudah pernah dilakukan <br>
    

 ##### Dashboard Preview

![Jaya Jaya Maju Company HR Analytics Preview](https://github.com/dream2hvn/Submission-Menyelesaikan-Permasalahan-Human-Resources/blob/main/Dashboard%20Preview)

###### Kesimpulan dari Dashboard
Melalui gambar diatas, Dapat disimpulkan bahwa attrition terbesar dimiliki oleh gender pria, dengan status pernikahan "single" dan distance / jarak rumah yang intermediete_distance
    
Link business dashboard:
```
https://lookerstudio.google.com/reporting/e801aee8-04d0-4bb2-b9b2-11e95f78d54e/page/nIFFF
```

### Conclusion
Berikut konklusi dari proyek ini:
---

Jumlah karyawan yang keluar dari Perusahaan **Jaya Jaya Maju** adalah sebanyak **179 orang** dari total **1058 karyawan**, atau apabila dipresentasekan sebanyak **16,9%**.  

Beberapa faktor yang mempengaruhi karyawan untuk keluar dari perusahaan antara lain:  

1️⃣ **Jarak tempat tinggal ke kantor** 🚗  
   - Karyawan yang memiliki jarak tempat tinggal ke kantor **"Intermediete_distance"** lebih dominan untuk keluar dari perusahaan.  

2️⃣ **Generasi Milenial (Millennials) 🧑‍💻**  
   - Kebanyakan yang keluar dari perusahaan adalah **karyawan dari generasi milenial**.  
   - Milenial menginginkan peluang untuk **berkembang dan belajar** dalam pekerjaan mereka.  
   - Kurangnya kesempatan untuk promosi, pelatihan, atau pengembangan keterampilan membuat mereka **merasa terjebak dan tidak termotivasi**, sehingga mendorong mereka untuk mencari peluang lain.  

3️⃣ **Tingkat Pendidikan 🎓**  
   - Sebagian besar karyawan yang keluar adalah lulusan **sarjana (S1)**.  
   - Hal ini menunjukkan bahwa **harapan mereka terhadap jenjang karir dan kesempatan pengembangan** mungkin tidak terpenuhi.  

4️⃣ **Status Pernikahan 💍**  
   - Karyawan **berstatus single** memiliki tingkat attrition yang lebih tinggi.  
   - **Milenial lajang** cenderung lebih fokus pada **pengembangan diri**, seperti pendidikan, perjalanan, atau membangun jaringan profesional.  
   - Mereka mungkin menunda pekerjaan permanen untuk fokus pada **prioritas pribadi** atau mencari **pekerjaan yang lebih fleksibel**.  

Dengan memahami faktor-faktor di atas, diharapkan perusahaan dapat mengambil langkah-langkah strategis untuk **mengurangi angka attrition** dan menciptakan lingkungan kerja yang lebih kondusif serta menarik bagi karyawan. 🚀✨
### Rekomendasi Action Items 
Berikut ini beberapa rekomendasi action items yang harus dilakukan oleh perusahaan:
---

### 1️⃣ **Meningkatkan Sistem Penghargaan dan Pengakuan 🏆**  
- 🎖️ Memberikan apresiasi kepada karyawan berprestasi melalui insentif finansial (bonus, kenaikan gaji) maupun non-finansial (sertifikat, penghargaan).  
- 🤝 Menerapkan sistem **peer-to-peer recognition** agar karyawan dapat saling memberikan apresiasi atas kontribusi mereka.  
- 🏅 Menyediakan penghargaan berkala, seperti **"Employee of the Month"**, untuk meningkatkan motivasi dan loyalitas karyawan.  

### 2️⃣ **Menyediakan Program Retensi untuk Talenta Kunci 🏅**  
- 🔍 Mengidentifikasi karyawan berperforma tinggi dan memberikan program khusus seperti **beasiswa studi lanjut** atau **kesempatan rotasi antar departemen**.  
- 🗣️ Membangun **jalur komunikasi yang lebih personal** antara manajemen dan karyawan untuk memahami kebutuhan mereka.  
- 🎯 Menyediakan **insentif tambahan** bagi talenta kunci untuk meningkatkan kepuasan kerja dan mengurangi kemungkinan mereka berpindah ke perusahaan lain.  

### 3️⃣ **Menganalisis dan Menyesuaikan Gaji dengan Pasar 💰**  
- 📊 Melakukan **benchmarking gaji** secara berkala agar tetap kompetitif dengan industri dan menarik bagi karyawan potensial.  
- 💵 Menawarkan **insentif tambahan** seperti **opsi saham perusahaan** atau **bonus berbasis kinerja** untuk meningkatkan retensi.  
- 📈 Menyesuaikan skema **kenaikan gaji berdasarkan pencapaian** agar karyawan merasa dihargai atas kontribusi mereka.  

### 4️⃣ **Meningkatkan Budaya Perusahaan yang Inklusif dan Kolaboratif 🤝**  
- 🚀 Membangun **budaya kerja yang terbuka**, di mana karyawan bebas menyampaikan ide dan masukan tanpa rasa takut.  
- 🏢 Mengadakan **program kerja sama lintas departemen** agar meningkatkan teamwork dan engagement antar karyawan.  
- 🌍 Mendorong **diversitas dan inklusi** dengan menciptakan lingkungan kerja yang lebih ramah dan suportif bagi semua karyawan.  

### 5️⃣ **Meningkatkan Proses Rekrutmen dan Onboarding 🏗️**  
- 🏆 Mengoptimalkan proses **perekrutan** untuk menarik kandidat yang lebih sesuai dengan nilai dan budaya perusahaan.  
- 📚 Menyediakan **program onboarding yang komprehensif** agar karyawan baru dapat lebih cepat beradaptasi dengan lingkungan kerja.  
- 👨‍🏫 Mengadakan **mentorship program** bagi karyawan baru agar mereka mendapatkan bimbingan dari senior yang berpengalaman.  

### 6️⃣ **Menawarkan Benefit yang Lebih Menarik 🎁**  
- 🚕 Menyediakan **subsidi transportasi** atau **akomodasi** bagi karyawan yang tinggal jauh dari kantor.  
- 🏥 Menawarkan **asuransi kesehatan premium** dan **opsi program pensiun** yang lebih menarik untuk meningkatkan loyalitas karyawan jangka panjang.  
- 🎓 Memberikan **dukungan finansial untuk pendidikan lanjutan** seperti pelatihan profesional atau kursus sertifikasi.  

### 7️⃣ **Melakukan Survei Karyawan Secara Rutin 📋**  
- 📢 Mengadakan **survei kepuasan karyawan** secara berkala untuk mengidentifikasi masalah dan harapan mereka.  
- 📊 Menggunakan hasil survei untuk **merancang kebijakan perusahaan** yang lebih sesuai dengan kebutuhan karyawan.  
- 🔄 Menyediakan **kotak saran anonim** agar karyawan merasa lebih bebas dalam menyampaikan masukan mereka.  

---

Dengan menerapkan rekomendasi ini, diharapkan perusahaan dapat lebih efektif dalam mempertahankan karyawan, mengurangi tingkat attrition, dan menciptakan lingkungan kerja yang lebih produktif serta menyenangkan. 🚀✨
