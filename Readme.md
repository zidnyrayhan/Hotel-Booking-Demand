#Hotel Booking Demand Classification
  Project Introduction

Pembatalan reservasi (hotel booking cancellation) adalah salah satu masalah utama yang sering dihadapi oleh hotel. Tingginya tingkat pembatalan dapat menyebabkan kerugian finansial, karena kamar yang seharusnya terisi menjadi kosong.

Tujuan dari project ini adalah membangun model machine learning untuk memprediksi apakah sebuah reservasi akan dibatalkan (is_canceled = 1) atau tidak (is_canceled = 0). Dengan adanya model ini, hotel dapat mengidentifikasi risiko pembatalan lebih awal dan mengambil langkah pencegahan, misalnya:

Memberlakukan deposit tambahan untuk reservasi berisiko tinggi.

Menerapkan strategi overbooking secara lebih aman.

Menyusun strategi pemasaran yang lebih tepat untuk pelanggan yang loyal.
# Files in Repository

README.md → Project introduction.

capstone2_notebook.ipynb → Notebook dokumentasi pengerjaan project.

model_random_forest.pkl → File model terbaik yang sudah disimpan dengan Pickle.

#  Dataset

Dataset yang digunakan adalah Hotel Booking Demand.
Fitur utama yang digunakan antara lain:

country → negara asal tamu.

market_segment → segmentasi pelanggan.

previous_cancellations → jumlah pembatalan sebelumnya.

deposit_type → tipe deposit yang dilakukan.

total_of_special_requests → jumlah permintaan khusus.

Target: is_canceled → 1 jika reservasi dibatalkan, 0 jika tidak.

# Modeling & Evaluation

Tiga algoritma digunakan dalam modeling:

Logistic Regression (baseline).

Random Forest.

Gradient Boosting.

Model dievaluasi menggunakan ROC-AUC score dan classification report.
 Hasil terbaik diperoleh dengan Random Forest, yang memiliki ROC-AUC paling tinggi.

# Conclusion & Recommendation

Model terbaik: Random Forest.

Manfaat untuk bisnis: membantu hotel mengurangi kerugian akibat pembatalan dengan prediksi yang lebih akurat.

Rekomendasi:

Terapkan deposit tambahan pada reservasi berisiko tinggi.

Update model secara berkala agar performa tetap baik.

Gunakan insight dari model untuk strategi pemasaran.
