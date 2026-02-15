<h1>👕 Fashion MNIST – Encoder Model Implementation</h1>

<hr>

<h2>👤 Identitas</h2>

<ul>
  <li><b>Nama:</b> Najla Putri Kaliandra Sabilillah</li>
  <li><b>Kegiatan:</b> Ujian Praktikum</li>
  <li><b>Tema:</b> Encoder</li>
</ul>

<hr>

<h2>📌 Deskripsi Proyek</h2>

<p>
Proyek ini merupakan implementasi model <b>Encoder</b> menggunakan dataset 
<b>Fashion MNIST</b>. Model dirancang untuk mempelajari representasi fitur 
dari citra pakaian melalui proses encoding.
</p>

<p>
Tujuan utama proyek ini adalah memahami bagaimana model neural network 
dapat mengekstrak fitur penting dari data citra grayscale berukuran kecil.
</p>

<hr>

<h2>📂 Dataset</h2>

<ul>
  <li><b>Nama Dataset:</b> Fashion MNIST</li>
  <li><b>Sumber:</b> 
    <a href="https://www.kaggle.com/datasets/zalando-research/fashionmnist">
    Fashion MNIST – Zalando Research (Kaggle)
    </a>
  </li>
  <li><b>Jumlah Kelas:</b> 10 kategori pakaian</li>
  <li><b>Ukuran Gambar:</b> 28x28 pixels (grayscale)</li>
</ul>

<p>
Dataset terdiri dari berbagai kategori pakaian seperti T-shirt, Trouser, 
Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, dan Ankle Boot.
</p>

<hr>

<h2>🧠 Model Architecture</h2>

<p>
Model menggunakan pendekatan <b>Neural Network Encoder</b> untuk:
</p>

<ul>
  <li>Mengekstraksi fitur dari input citra</li>
  <li>Mengurangi dimensi representasi data</li>
  <li>Mempelajari pola visual dari dataset Fashion MNIST</li>
</ul>

<p>
Arsitektur terdiri dari beberapa layer neural network 
yang bertujuan mengubah input gambar menjadi representasi fitur yang lebih ringkas.
</p>

<hr>

<h2>🚀 Tahapan Implementasi</h2>

<ul>
  <li>Load dataset Fashion MNIST</li>
  <li>Normalisasi pixel (rescaling)</li>
  <li>Membangun model encoder</li>
  <li>Training model</li>
  <li>Evaluasi hasil encoding</li>
</ul>

<hr>

<h2>📊 Hasil</h2>

<p>
Model berhasil mempelajari representasi fitur dari dataset 
dan mampu melakukan proses encoding terhadap citra Fashion MNIST.
</p>

<hr>

<h2>📁 Struktur Project</h2>

<pre>
├── fashion_minst.ipynb
</pre>

<hr>

<h2>🛠 Tech Stack</h2>

<ul>
  <li>🐍 Python</li>
  <li>🤖 TensorFlow / Keras</li>
  <li>📊 NumPy</li>
  <li>📈 Matplotlib</li>
</ul>
