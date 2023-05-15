# as-wisata-diy
Laporan Project Analisis Sentimen Tempat Wisata di Daerah Istimewa Yogyakarta

Google Maps memiliki kemampuan untuk mencari dan menampilkan informasi tentang suatu tempat. Informasi ini berasal dari masukan yang diberikan oleh pengunjung dan pemilik tempat. Salah satu jenis informasi yang ditampilkan adalah ulasan pengunjung. Ulasan ini dapat memberikan pandangan orang lain tentang tempat tersebut kepada calon pengunjung.

Menurut survei dari brightlocal, 78% pengunjung lebih mempercayai ulasan online daripada rekomendasi dari individu lain secara langsung. Oleh karena itu, ulasan pengunjung memiliki peran yang penting bagi pengelola tempat wisata. Namun, semakin banyaknya ulasan yang ada dapat menjadi tantangan bagi pengelola untuk memahami inti dari setiap ulasan untuk dapat meningkat kualitas tempat wisata. Oleh karena itu, penerapan data mining, khususnya analisis sentimen, memiliki peran penting dalam mengatasi hal tersebut.

Analisis sentimen digunakan untuk memperoleh pendapat pengguna dengan lebih efisien. Dalam penelitian ini, analisis sentimen digunakan untuk menentukan apakah ulasan pengunjung bersifat positif atau negatif, serta untuk mengidentifikasi aspek-aspek yang dibahas dalam seluruh ulasan tersebut, seperti kebersihan, daya tarik, fasilitas, dan pelayanan

Project ini menggunakan 2434 data dari beberapa tempat wisata di DIY seperti Candi Prambanan, Gembira Loka, Hartono Mall, Jogja Bay, Pantai Depok, Pantai Parangtritis, dan Tebing Breksi, yang diperoleh dari Google Maps Review. 

Proses pembuatan model klasifikasi menggunakan Support Vector Machine dengan proses ekstraksi fitur menggunakan TF-iDF.

Berdasarkan hasil evaluasi dan interpretasi model yang telah dilakukan, dapat diambil beberapa kesimpulan antara lain :
•	Model memiliki akurasi yang baik dalam cross validation sebesar 84,1% dan metrik lain yang seimbang dalam classification report. 
•	Wordcloud positif dan negatif mampu menunjukkan beberapa aspek yang dapat dijadikan pertimbangan bagi pengelola tempat wisata, misalnya dalam wordcloud negatif muncul kata ‘parkir’,’mahal’,’panas’. Kata-kata dari wordcloud negatif tersebut dapat menjadi masukan bagi pengelola tempat wisata untuk dapat meningkatkan kualitas tempat tersebut.
•	Hasil pengujian kalimat dengan fokus pada bagian negasi, konteks kalimat, dan sarkasme menunjukkan hasil yang tidak sesuai. Output yang dihasilkan oleh model hanya mempertimbangkan bobot atau kekuatan dari setiap kata. Model tidak mampu untuk memahami makna atau konteks suatu kalimat.
