# Analysis Data 
## Get Answers and Questions from Data
Menggunakan library pandas, pertanyaan dijawab berdasarkan data menggunakan fungsi groupby, agregasi, pengurutan data (sort_values), penghitungan nilai muncul (value_counts), dan operasi lainnya.
## Exploratory Data Analysis and Data Visualization
Kombinasi metode groupby dan visualisasi menggunakan scatter plot, bar plot, pie chart, box plot, dan pair plot untuk menjawab pertanyaan secara visual. Menggunakan visualisasi data memungkinkan pemahaman yang lebih dalam tentang pola dan hubungan dalam data.
## Create Machine Learning Model to Predict Termd and Question
Proses dimulai dengan normalisasi data menggunakan teknik Min-Max scaling untuk memastikan semua fitur berada dalam rentang yang sama. Setelah itu, fitur-fitur yang bersifat kategorikal diubah menjadi angka menggunakan LabelEncoder.Model machine learning dibangun menggunakan algoritma Decision Tree dari library sklearn. Decision Tree adalah pilihan yang baik untuk pemodelan klasifikasi, dan di sini digunakan untuk memprediksi term dan pertanyaan berdasarkan fitur-fitur yang ada dalam dataset. 
