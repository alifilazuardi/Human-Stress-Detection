# Human-Stress-Detection
Perbandingan Metode K Nearest Neighbor dan Decision Tree Dalam Melakukan Klasifikasi Tingkat Stress Pada Dataset Human Stress Detection 

Stres merupakan kondisi dimana seorang individu mengalami sebuah tekanan akibat dari ketidaksesuaian harapan dan keadaan yang sebenarnya. Stres dapat dipicu oleh berbagai faktor seperti pendidikan, pekerjaan, maupun ekonomi. Stres dapat menimbulkan berbagai gangguan kesehatan yang dapat menjadi semakin parah seiring dengan berjalannya waktu.
Dataset yang digunakan pada penelitian ini didapatkan dari kaggle dengan nama Human Stress Detection berjumlah 2002 data yang terdiri dari tiga variabel yang dapat mempengaruhi tingkat stress yaitu temperature, humidity, dan step count. Terdapat klasifikasi level stress diantaranya low, normal, dan high yang dikalibrasi dan ditetapkan ke biner 0, 1, dan 2. Tabel 1 menunjukkan 5 data teratas dari dataset.

Klasifikasi stress level dapat dilakukan dengan berbagai parameter, seperti temperature, humidity, dan step count. Dalam dataset ini terdapat 3 kelas dari stress yang masing-masing datanya tersebar secara merata. Hubungan setiap fitur terhadap stress level yang paling kuat dimiliki oleh humidity dan temperatur dengan nilai korelasi 0.94. Sementara itu satu fitur lain yakni step count juga mempunyai korelasi yang cukup tinggi terhadap stress level yakni 0.83. Dengan demikian dapat disimpulkan bahwa humidity, temperature, dan step count mempunyai pengaruh yang kuat terhadap stress level. 
Berdasarkan penelitian di atas, diperoleh hasil bahwa algoritma KNN mampu melakukan klasifikasi tingkat stress yang lebih baik dibandingkan dengan algoritma decision tree. KNN mendapatkan nilai precision 0.997636, recall 0.99865, dan f1-score 0.998138 sedangkan decision tree mendapatkan nilai precision 0.99455, recall 0.995951, dan f1-score 0.995227. 
Pada pengujian confusion matrix KNN memiliki keunggulan karena hanya memiliki satu kesalahan klasifikasi tingkat stress sedangkan Decision Tree memiliki tiga kesalahan klasifikasi. Klasifikasi dilakukan dengan menggunakan ketiga atribut dari dataset yakni humidity, temperature, dan step count. Ketiga variabel ini digunakan karena ketiganya mempunyai pengaruh yang kuat terhadap masing masing tingkat stress. Jika nilai atribut semakin tinggi maka tingkat stress akan semakin tinggi. 
