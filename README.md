# Analisis Jumlah Like Komentar Youtube Rewind 2023
Memodelkan jumlah kata dalam komentar berdasarkan jumlah like,  durasi komentar (waktu sejak komentar di-posting) dan balasan komentar utama . Dengan menggunakan regresi poisson, kita bisa memodelkan jumlah kata dalam komentar YouTube berdasarkan jumlah like, durasi komentar, dan balasan komentar utama. Model ini bisa membantu kita memahami faktor-faktor yang mempengaruhi panjang komentar di-platform YouTube.
<div style="display:flex;margin:20">
  <img src="./Screenshot(967).png" width="250" style="display: inline;"/>
  <img src="./Screenshot(968).png" width="250" style="display: inline;"/>
  <img src="./Screenshot(969).png" width="250" style="display: inline;"/>
  <img src="./Screenshot(970).png" width="250" style="display: inline;"/>
</div>
Hasil prediksi dari model menunjukkan nilai panjang komentar yang diprediksi (predicted_comment_length) dibandingkan dengan nilai panjang komentar aktual (comment_length). Perbandingan ini memberikan gambaran tentang seberapa baik model memprediksi panjang komentar berdasarkan variabel-variabel independen yang digunakan. Secara keseluruhan, model ini memberikan wawasan berharga tentang faktor-faktor yang mempengaruhi panjang komentar di YouTube dan dapat digunakan untuk memprediksi panjang komentar berdasarkan variabel independen yang diberikan. <br>
Kesimpulan dari hasil ini adalah bahwa jumlah like, waktu sejak komentar di-posting, dan apakah komentar adalah balasan atau bukan, semuanya merupakan prediktor signifikan untuk panjang komentar
