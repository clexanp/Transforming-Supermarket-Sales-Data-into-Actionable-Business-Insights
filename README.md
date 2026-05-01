# 📊 Transforming Supermarket Sales Data into Actionable Business Insights

## 📌 Project Overview

Project ini merupakan implementasi proses **Data Manipulation menggunakan Python Pandas** untuk menghasilkan insight bisnis dari dataset supermarket sales.
Dalam project ini, saya mencoba memposisikan diri sebagai seorang Data Analyst yang menerima data transaksi supermarket dari atasan untuk dianalisis menggunakan berbagai teknik manipulasi data.

Fokus utama project bukan hanya melakukan coding, tetapi bagaimana data dapat diterjemahkan menjadi:

* insight bisnis,
* pola perilaku customer,
* evaluasi operasional,
* hingga rekomendasi strategis untuk perusahaan.

Project ini dikerjakan menggunakan Google Colab dengan pendekatan analisis berbasis business understanding sebelum masuk ke tahap coding dan eksplorasi data.

---

# 🎯 Background Project

Di dunia Data Science, kemampuan melakukan manipulasi data merupakan salah satu skill fundamental yang wajib dimiliki oleh seorang Data Analyst maupun Data Scientist.

Dataset transaksi supermarket biasanya memiliki:

* data kategorikal,
* data numerikal,
* data waktu (datetime),
* hingga data multi tabel yang perlu digabungkan.

Melalui project ini, saya mencoba mengeksplor bagaimana teknik data manipulation dapat membantu perusahaan dalam:

* memahami perilaku customer,
* mengidentifikasi tren penjualan,
* mengevaluasi metode pembayaran,
* hingga menentukan strategi bisnis berdasarkan data.

---

# 🚀 Objective Project

Tujuan utama project ini adalah:

* Melakukan eksplorasi data menggunakan Python Pandas
* Mengimplementasikan berbagai metode data manipulation
* Mengubah data mentah menjadi business insight
* Menganalisis pola transaksi customer
* Menampilkan kemampuan analytical thinking
* Melatih kemampuan business understanding dalam proses analisis data

---

# 🗂️ Dataset Information

Dataset yang digunakan dalam project ini adalah:

### 🛒 Supermarket Sales Dataset

Dataset berisi informasi transaksi supermarket seperti:

* Invoice ID
* Branch
* Customer Type
* Gender
* Product Line
* Quantity
* Payment Method
* Rating
* Date & Time
* Total Transaction

Selain dataset utama, project ini juga menggunakan:

* `branch_info.csv`
* `product_info.csv`

yang digunakan pada proses join dan merge data.

---

# 🛠️ Tools & Technologies

Project ini dikerjakan menggunakan:

| Tools        | Kegunaan                     |
| ------------ | ---------------------------- |
| Python       | Bahasa pemrograman utama     |
| Pandas       | Data manipulation & analysis |
| NumPy        | Operasi numerik              |
| Matplotlib   | Visualisasi data             |
| Seaborn      | Visualisasi statistik        |
| Google Colab | Environment coding           |

---

# 📚 Data Manipulation Methods

Beberapa metode data manipulation yang digunakan dalam project ini:

* ✅ Filtering Data
* ✅ Sorting Data
* ✅ Grouping & Aggregation
* ✅ Join & Merge Data
* ✅ Pivot Table
* ✅ Crosstab Analysis
* ✅ Datetime Operations
* ✅ Data Transformation
* ✅ Feature Engineering

---

# 🔄 Workflow Analysis

Sebelum melakukan coding, proses analisis diawali dengan membuat business question terlebih dahulu agar analisis yang dilakukan memiliki arah yang jelas.

## Workflow project:

```text
1. Import Dataset
2. Data Understanding
3. Data Cleaning
4. Data Manipulation
5. Exploratory Data Analysis
6. Business Insight Extraction
7. Recommendation
```

Pendekatan ini membantu proses analisis menjadi lebih terstruktur dan tidak hanya berfokus pada coding semata.

---

# ❓ Business Questions

Beberapa pertanyaan bisnis yang digunakan dalam project ini:

* Apakah customer E-Wallet memiliki tingkat kepuasan lebih tinggi?
* Produk apa yang paling diminati customer pria?
* Apakah customer member memberikan kontribusi transaksi lebih besar?
* Product line apa yang paling laris di setiap cabang?
* Kapan peak hour transaksi supermarket terjadi?
* Apakah metode pembayaran berbeda di setiap cabang?

---

# 🔍 Step-by-Step Analysis

## 1️⃣ Filtering Data

Pada tahap ini dilakukan filtering terhadap customer yang menggunakan metode pembayaran E-Wallet.

Tujuan analisis:

* membandingkan rating customer E-Wallet,
* melihat tingkat kepuasan pelanggan,
* mengevaluasi pengalaman pembayaran digital.

### Insight:

Customer dengan metode pembayaran E-Wallet ternyata memiliki rata-rata rating lebih rendah dibanding metode pembayaran lainnya.

### Business Recommendation:

Perusahaan dapat melakukan evaluasi terhadap:

* sistem pembayaran digital,
* mesin E-Wallet,
* user experience transaksi digital.

---

# 2️⃣ Sorting Data

Analisis sorting digunakan untuk melihat distribusi pembelian customer pria terhadap:

* Health and Beauty
* Sports and Travel

Data diurutkan berdasarkan:

* bulan,
* total penjualan,
* kategori produk.

### Insight:

Customer pria lebih banyak membeli produk Health and Beauty dibanding Sports and Travel.

### Interpretasi:

Hal ini menunjukkan kecenderungan self reward indoor activity seperti:

* skincare,
* grooming,
* personal care.

### Recommendation:

Supermarket dapat meningkatkan promo produk Health and Beauty khusus customer pria.

---

# 3️⃣ Grouping & Aggregation

Tahap ini menggunakan:

* `groupby()`
* `agg()`

untuk menghitung:

* rata-rata pengeluaran,
* total transaksi,
* rata-rata rating.

### Insight:

Customer pria memiliki minat lebih tinggi terhadap produk Health and Beauty dibanding customer wanita.

### Business Value:

Insight ini cukup menarik karena produk Health and Beauty umumnya identik dengan customer wanita.

---

# 4️⃣ Join & Merge Data

Project ini juga menggunakan beberapa dataset tambahan yang digabungkan menggunakan:

* `merge()`
* relational key antar tabel.

Dataset tambahan:

* informasi cabang,
* informasi produk,
* region supermarket.

### Insight:

Customer member memiliki total pengeluaran lebih tinggi dibanding customer normal.

### Business Interpretation:

Program membership berhasil meningkatkan kontribusi transaksi customer.

Namun:
customer normal memiliki rata-rata rating lebih tinggi dibanding customer member.

### Recommendation:

Perusahaan perlu meningkatkan kualitas pelayanan customer member agar loyalitas tetap terjaga.

---

# 5️⃣ Pivot Table Analysis

Pivot table digunakan untuk melihat:

* distribusi product line,
* total quantity,
* cabang supermarket,
* produk terlaris.

### Insight:

Setiap cabang supermarket memiliki product line terlaris yang berbeda.

Contoh:

* Cabang A → Sports and Travel
* Cabang B → Home and Lifestyle
* Cabang C → Electronic Accessories

### Business Recommendation:

Perusahaan dapat melakukan strategi stok dan promosi berbeda pada tiap cabang.

---

# 6️⃣ Crosstab Analysis

Metode `crosstab()` digunakan untuk melihat frekuensi penggunaan metode pembayaran pada setiap cabang.

### Insight:

Penggunaan metode pembayaran berbeda pada setiap cabang supermarket.

Cabang tertentu lebih dominan menggunakan:

* Credit Card,
* sementara cabang lain lebih dominan E-Wallet.

### Recommendation:

Perusahaan dapat meningkatkan promosi penggunaan E-Wallet pada cabang yang masih didominasi Credit Card.

---

# 7️⃣ Datetime Operations

Pada tahap ini dilakukan eksplorasi terhadap:

* jam transaksi,
* periode waktu,
* peak hour supermarket.

Feature engineering dilakukan dengan mengubah:

* kolom time,
* menjadi kategori periode waktu:

  * pagi,
  * siang,
  * sore,
  * malam.

### Insight:

Peak hour penjualan terjadi pada periode siang.

Produk paling dominan:

* Sports and Travel.

### Business Recommendation:

Supermarket dapat membuat promo khusus pada jam sibuk untuk meningkatkan revenue.

---

# 🧠 Importance of Business Understanding

Salah satu hal penting yang saya pelajari dari project ini adalah:

Data analysis bukan hanya tentang coding.

Tetapi:

* memahami konteks bisnis,
* memahami perilaku customer,
* dan bagaimana data diterjemahkan menjadi keputusan bisnis.

Tanpa business understanding, hasil analisis sering kali hanya menjadi angka tanpa arah yang jelas.

---

# 📖 Importance of Data Storytelling

Dalam project ini, saya mencoba membangun alur analisis seperti seorang Data Analyst di dunia kerja nyata.

Mulai dari:

* membuat business question,
* melakukan eksplorasi data,
* menemukan insight,
* hingga memberikan recommendation.

Data storytelling membantu insight menjadi:

* lebih mudah dipahami,
* lebih actionable,
* dan lebih relevan untuk kebutuhan bisnis.

---

# 📊 Key Insights

## 🔑 Insight Utama Project

* Customer E-Wallet memiliki rating lebih rendah dibanding metode pembayaran lain
* Customer pria lebih dominan membeli produk Health and Beauty
* Customer member memiliki total pengeluaran lebih tinggi
* Product line terlaris berbeda di setiap cabang
* Terdapat perbedaan metode pembayaran di tiap cabang
* Peak hour supermarket terjadi pada periode siang
* Produk Sports and Travel mendominasi pada jam sibuk

---

# 💼 Business Recommendation

Beberapa rekomendasi bisnis yang dapat diterapkan:

* Evaluasi sistem pembayaran E-Wallet
* Menambahkan promo Health and Beauty khusus customer pria
* Optimasi program membership
* Menyesuaikan stok berdasarkan cabang
* Menjalankan promo berdasarkan peak hour
* Memperkuat strategi pembayaran digital

---

# ⚠️ Challenges During Analysis

Beberapa tantangan yang saya hadapi selama project:

### 🔹 Datetime Analysis

* Mengubah format waktu menjadi periode harian
* Mengelompokkan jam transaksi

### 🔹 Join & Merge

* Menentukan relational key antar dataset
* Menjaga konsistensi data setelah merge

### 🔹 Business Interpretation

* Mengubah angka menjadi insight bisnis
* Menentukan recommendation yang relevan

### 🔹 Data Manipulation

* Mengatur struktur data agar mudah dianalisis
* Menentukan metode manipulasi yang tepat

---

# 🎯 Key Skills Demonstrated

Project ini membantu saya melatih beberapa skill berikut:

* Data Manipulation
* Exploratory Data Analysis
* Business Analysis
* Data Cleaning
* Data Aggregation
* Data Visualization
* Business Insight Extraction
* Data Storytelling
* Python Pandas
* Analytical Thinking

---

# 📚 Key Learnings

Beberapa pembelajaran yang saya dapatkan:

* Pentingnya business question sebelum coding
* Pentingnya memahami struktur dataset
* Pentingnya data storytelling dalam Data Science
* Pentingnya data manipulation dalam proses analisis
* Insight bisnis dapat ditemukan dari proses manipulasi data sederhana

---

# ✅ Conclusion

Project ini menunjukkan bahwa proses data manipulation memiliki peran yang sangat penting dalam proses pengambilan keputusan bisnis.

Melalui berbagai teknik seperti:

* filtering,
* grouping,
* merge,
* pivot,
* hingga datetime operations,

data transaksi supermarket dapat diubah menjadi insight yang lebih meaningful dan actionable.

Selain meningkatkan kemampuan teknikal Python Pandas, project ini juga membantu saya memahami bagaimana seorang Data Analyst menerjemahkan data menjadi rekomendasi bisnis yang relevan.

---

# 🚀 Future Improvement

Beberapa pengembangan yang dapat dilakukan selanjutnya:

* Menambahkan dashboard interaktif menggunakan Power BI atau Tableau
* Menambahkan machine learning prediction
* Membuat customer segmentation analysis
* Menambahkan sales forecasting
* Menambahkan visualisasi yang lebih kompleks
* Menggunakan dataset dengan skala lebih besar

---

# 👨‍💻 Author Information

### Raihan Azhar Rafi

📌 Data Science Enthusiast
📌 Interested in Data Analysis, Business Intelligence, and Machine Learning
📌 Tools: Python, Pandas, SQL, Power BI, Google Colab

---

# ⭐ Final Notes

Project ini dibuat sebagai bagian dari proses pembelajaran Data Science dan pengembangan portfolio Data Analyst/Data Scientist.

Terima kasih sudah mengunjungi project ini 🚀
