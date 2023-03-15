# Credit Card Default

**Latar Belakang**
Dataset Credit Card Approval di Kaggle adalah kumpulan data yang berisi informasi mengenai pengajuan kartu kredit dan apakah pengajuan tersebut disetujui atau ditolak oleh pemberi kartu kredit. Dataset ini berisi berbagai variabel seperti informasi demografis, data keuangan, dan riwayat kredit dari pemohon. Tujuan dari dataset ini adalah untuk membangun model prediksi yang dapat memprediksi apakah sebuah pengajuan kartu kredit akan disetujui atau ditolak berdasarkan variabel yang ada dalam dataset. Dalam konteks ini, problem statement-nya adalah bagaimana membangun model prediksi yang akurat untuk memprediksi keputusan persetujuan pengajuan kartu kredit berdasarkan informasi yang tersedia dalam dataset Credit Card Approval di Kaggle.

**Goals:**  
Sebagai perusahaan pemberi kartu kredit, kami ingin menganalisa karakteristik pemohon kartu kredit yang dapat mempengaruhi keputusan persetujuan dan potensi default pada pengembalian pembayaran kartu kredit. Oleh karena itu, perusahaan ingin membangun model prediksi yang dapat memprediksi apakah seseorang berpotensi melakukan default atau tidak mampu membayar kembali kartu kredit berdasarkan informasi yang tersedia pada pengajuan kartu kredit. Dengan memiliki model prediksi ini, perusahaan dapat mengantisipasi risiko potensial default dari pemegang kartu kredit dan mengambil tindakan pencegahan yang sesuai seperti menyesuaikan batas kredit, menawarkan program khusus untuk membantu pelanggan mengelola hutang mereka, atau menolak pengajuan kartu kredit dari pemohon dengan risiko default yang tinggi. Dengan demikian, perusahaan dapat meminimalkan risiko keuangan dan reputasi dari perusahaan, serta memastikan pemberian layanan kartu kredit yang lebih bertanggung jawab dan menguntungkan bagi kedua belah pihak.

**Analytical Approach:**  
Jadi pada projek ini akan membangun sebuah model klasifikasi yang mampu membedakan nasabah yang berpotensi default atau tidak dalam pengajuan kartu kredit.

**Metrics Evaluation**  
Metrik kinerja yang paling penting untuk pemodelan risiko default biasanya adalah nilai recall atau precision pada kelas minoritas. Sebagai contoh, dalam konteks deteksi default, kami ingin memaksimalkan nilai true positive rate dan menangkap sebanyak mungkin kasus default, sehingga recall untuk kelas minoritas adalah metrik yang ingin kami optimalkan. Dalam hal ini, nilai recall yang tinggi akan menunjukkan kemampuan model untuk mengidentifikasi dengan akurat pemohon kartu kredit yang berisiko default dan mengambil tindakan pencegahan yang sesuai. Oleh karena itu, memonitor recall pada kelas minoritas menjadi kritis dalam membangun model prediksi risiko default yang akurat dan dapat diandalkan.
- Konsekuensi:
    - Kerugian Keuangan: Default dapat menyebabkan kerugian keuangan bagi perusahaan karena perusahaan tidak akan menerima pembayaran penuh dari peminjam dan bahkan mungkin tidak mendapatkan pembayaran sama sekali.

    - Meningkatnya Biaya Operasional: Default dapat menyebabkan peningkatan biaya operasional perusahaan karena perusahaan harus mengambil tindakan hukum untuk menagih pembayaran dari peminjam yang gagal membayar.

    - Turunnya Reputasi Perusahaan: Jika terjadi default secara massal, reputasi perusahaan dapat terganggu karena dapat memicu ketidakpercayaan dari investor dan pelanggan. Hal ini dapat menyebabkan penurunan nilai saham dan pendapatan yang dapat berdampak jangka panjang bagi perusahaan.

    - Penghambatan Akses ke Sumber Dana: Jika terjadi default secara terus-menerus, perusahaan dapat menghadapi kesulitan dalam mengakses sumber dana baru di masa depan. Hal ini dapat membatasi kemampuan perusahaan untuk melakukan ekspansi atau investasi.

    - Peningkatan Tingkat Risiko: Default dapat meningkatkan tingkat risiko dalam portofolio kredit perusahaan dan dapat mempengaruhi kemampuan perusahaan untuk mendapatkan pendanaan di masa depan. Hal ini dapat mengganggu pertumbuhan perusahaan dan menurunkan nilai perusahaan dalam jangka panjang.

    - Meningkatnya Beban Regulasi: Default dapat meningkatkan beban regulasi pada perusahaan karena perusahaan harus memenuhi persyaratan peraturan untuk menangani situasi default. Hal ini dapat memakan waktu dan sumber daya perusahaan dan mempengaruhi produktivitas dan kinerja perusahaan secara keseluruhan.
    
Sehingga dengan demikian metrik evaluasi yang akan kita fokuskan adalah recall.
