## Dataset
Repositori ini berisi dataset untuk penelitian dan pengembangan model **Pengenalan Bahasa Isyarat Indonesia (SIBI)** secara otomatis. Dataset ini berasal dari dua sumber utama: hasil scraping dari video pembelajaran bahasa isyarat yang tersedia secara publik, serta data tambahan hasil perekaman langsung menggunakan MediaPipe. Setiap sampel data direpresentasikan dalam bentuk urutan koordinat (x, y, z) dari 543 titik landmark yang mencakup wajah, tangan kiri, dan tangan kanan. Data disimpan dalam format Parquet dan dilengkapi dengan file label untuk keperluan pelatihan model klasifikasi.

Dataset ini ditujukan untuk mendukung riset, pengembangan sistem bantu komunikasi untuk penyandang disabilitas, serta implementasi model deep learning seperti LSTM, GRU, dan model gabungan dalam konteks klasifikasi bahasa isyarat.

Data landmark berada pada file parquet sedangkan label terdapat pada csv
![StrukturData.](/images/StructureDataset.png.png "Struktur Dataset.")
