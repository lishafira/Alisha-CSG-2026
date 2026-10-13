# Assignment 1 - Introduction to Quantum Physics

**Nama:** Alisha Shafira Qolby  
**NIM:** TF-48-02 / 101042400015  

---

## No. 1

1. **Apa yang dimaksud dengan *ultraviolet catastrophe*, dan bagaimana hipotesis Planck menyelesaikannya?**

   *Ultraviolet catastrophe* menjelaskan spektrum radiasi benda hitam di mana teori klasik memprediksi intensitas radiasi akan mendekati tak berhingga pada frekuensi tinggi atau daerah ultraviolet. Hipotesis Planck mengasumsikan bahwa energi radiasi tidak dipancarkan secara kontinu, melainkan dalam paket-paket diskrit yang disebut kuanta/foton dengan energi:
   `E = hν`

2. **Dalam *photoelectric effect*, mengapa menaikkan intensitas cahaya merah tidak membuat elektron terlepas dari logam, sedangkan cahaya ultraviolet redup dapat melakukannya?**

   Efek fotoelektrik bergantung pada frekuensi energi per foton cahaya. Cahaya merah memiliki frekuensi di bawah frekuensi ambang (ν₀) logam, sehingga meskipun intensitasnya dinaikkan, energi setiap foton tetap tidak cukup untuk melepaskan elektron. Sebaliknya, cahaya ultraviolet memiliki frekuensi di atas ambang batas, sehingga setiap fotonnya mampu melepaskan elektron meskipun cahayanya redup.

3. **Jelaskan apa yang terjadi pada eksperimen *double-slit* jika elektron ditembakkan satu per satu, dan apa yang berubah jika kita memasang detektor di salah satu celah.**

   Ketika elektron ditembakkan satu per satu, pola interferensi berupa garis-garis terang dan gelap tetap terbentuk secara perlahan di layar, menunjukkan bahwa satu elektron dapat berinterferensi dengan dirinya sendiri yakni memiliki sifat gelombang. Namun, jika detektor dipasang pada salah satu celah untuk mengetahui jalur elektron, sifat gelombang tersebut runtuh dan pola interferensi hilang, berganti menjadi dua garis lurus biasa karena elektron berperilaku sebagai partikel klasik.

4. **Wavefunction ψ bernilai kompleks dan tidak dapat diukur langsung. Lalu besaran apa yang memiliki makna fisis, dan apa artinya?**

   Besaran yang memiliki makna fisis adalah besaran kuadrat dari nilai mutlak fungsi gelombang yaitu kerapatan probabilitas:
   `|ψ|² = ψ*ψ`  
   Besaran ini menyatakan probabilitas menemukan partikel pada posisi dan waktu tertentu dalam ruang.

5. **Seorang teman berkata: *"Uncertainty principle muncul karena alat ukur kita belum cukup canggih."* Apakah pernyataan ini benar? Jelaskan.**

   Tidak benar karena *uncertainty principle* sendiri merupakan sifat yang fundamental dari alam semesta pada skala kuantum. Pasangan besaran seperti posisi dan momentum memiliki batas ketidakpastian fundamental:
   `Δx · Δp ≥ ℏ / 2`  
   Batas ini melekat pada sifat gelombang-partikel materi itu sendiri dan bukan merupakan kelemahan alat ukur.

6. **Mengapa kita tidak melihat efek interferensi saat melempar bola melalui dua pintu?**

   Panjang gelombang de Broglie dari sebuah bola dirumuskan sebagai:
   `λ = h / p`  
   Nilai panjang gelombang ini sangat kecil hingga mendekati nol dibandingkan dengan ukuran pintu dan jarak antar pintu. Akibatnya, sifat gelombang makroskopik teredam secara ekstrem dan bola sepenuhnya mengikuti hukum mekanika klasik.

---

## No. 2

### I. 
Sebuah laser pointer merah memancarkan cahaya λ = 650 nm dengan daya P = 5 mW.

* **(a) Berapa energi satu foton dalam joule dan eV?**

  `E = (hc) / λ = [(6.626 × 10⁻³⁴ J·s) × (3.00 × 10⁸ m/s)] / (650 × 10⁻⁹ m) = 3.058 × 10⁻¹⁹ J`

  Dalam satuan elektron-volt (eV):  
  `E = (3.058 × 10⁻¹⁹ J) / (1.602 × 10⁻¹⁹ C) = 1.909 eV`

* **(b) Berapa jumlah foton yang dipancarkan per detik?**

  `Daya P = 5 mW = 5 × 10⁻³ J/s`  
  `N = P / E = (5 × 10⁻³ J/s) / (3.058 × 10⁻¹⁹ J/foton) ≈ 1.635 × 10¹⁶ foton/detik`

---

### II. 
Natrium memiliki *work function* φ = 2.28 eV.

* **(a) Berapa panjang gelombang ambang (*threshold*) untuk natrium?**

  `λ₀ = (hc) / φ = [(6.626 × 10⁻³⁴) × (3.00 × 10⁸)] / (2.28 × 1.602 × 10⁻¹⁹) = 5.44 × 10⁻⁷ m = 544 nm`

* **(b) Jika disinari cahaya λ = 400 nm, berapa energi kinetik maksimum elektron yang terlepas (dalam eV)?**

  `E_foton = (hc) / λ = [(6.626 × 10⁻³⁴) × (3.00 × 10⁸)] / (400 × 10⁻⁹) = 4.9695 × 10⁻¹⁹ J = 3.102 eV`  
  `K_max = E_foton - φ = 3.102 eV - 2.28 eV = 0.822 eV`

* **(c) Berapa *stopping potential* yang diperlukan untuk menghentikan elektron tersebut?**

  `e · V_s = K_max`  
  `V_s = 0.822 eV / e = 0.822 V`

* **(d) Apakah cahaya λ = 600 nm dapat melepaskan elektron? Jelaskan.**

  Tidak, karena panjang gelombang 600 nm lebih besar daripada panjang gelombang ambang natrium (544 nm), yang berarti frekuensinya lebih kecil dari frekuensi ambang. Energi foton 600 nm adalah sekitar 2.07 eV, yang lebih kecil dari φ = 2.28 eV.

---

### III. 
* **(a) Pada eksperimen Davisson–Germer (1927), elektron dipercepat dengan beda potensial 54 V. Hitung panjang gelombang de Broglie-nya.**

  `K = e · V = (1.602 × 10⁻¹⁹ C) × (54 V) = 8.6508 × 10⁻¹⁸ J`  
  `λ = h / √(2 · m_e · K) = (6.626 × 10⁻³⁴) / √(2 × 9.109 × 10⁻³¹ × 8.6508 × 10⁻¹⁸) = 1.67 × 10⁻¹⁰ m = 0.167 nm`

* **(b) Berapa panjang gelombang de Broglie neutron termal yang bergerak dengan kecepatan 2200 m/s?**

  `λ = h / (m_n · v) = (6.626 × 10⁻³⁴) / [(1.675 × 10⁻²⁷ kg) × (2200 m/s)] = 1.798 × 10⁻¹⁰ m = 0.180 nm`

* **(c) Bandingkan hasil (a) dan (b) dengan jarak antar-atom pada kristal (~0.1 – 0.3 nm). Apa implikasinya?**

  Kedua nilai (≈ 0.167 nm dan ≈ 0.180 nm) berada dalam orde yang sama dengan jarak antar-atom kristal. Implikasinya adalah kristal dapat bertindak sebagai kisi difraksi alami untuk elektron dan neutron, yang memungkinkan terjadinya difraksi partikel.

---

### IV. 
* **(a) Sebuah elektron dibatasi dalam daerah selebar 1 nm. Hitung ketidakpastian minimum momentum dan kecepatannya.**

  `Δx = 1 nm = 10⁻⁹ m`  
  `Δp ≥ ℏ / (2 · Δx) = (1.055 × 10⁻³⁴) / (2 × 10⁻⁹) = 5.275 × 10⁻²⁶ kg·m/s`  
  `Δv = Δp / m_e = (5.275 × 10⁻²⁶) / (9.109 × 10⁻³¹) ≈ 5.79 × 10⁴ m/s`

* **(b) Lakukan perhitungan yang sama untuk sebuah debu bermassa 10⁻⁹ kg dengan ketelitian 1 μm. Bandingkan dan beri komentar.**

  `Δx = 10⁻⁶ m`  
  `Δp ≥ 5.275 × 10⁻²⁹ kg·m/s`  
  `Δv = (5.275 × 10⁻²⁹) / 10⁻⁹ = 5.275 × 10⁻²⁰ m/s`  
  Ketidakpastian kecepatan untuk objek makroskopik sangat kecil hingga mendekati 0. Prinsip ketidakpastian Heisenberg hanya berfungsi pada skala mikroskopis.

---

## No. 5

### Menggenggam Peluang Komputasi Masa Depan Melalui Qubit

Komputasi kuantum merupakan salah satu inovasi teknologi revolusioner di abad ke-21. Berbeda dengan komputer klasik yang memproses informasi menggunakan bit biner (0 atau 1), komputer kuantum memanfaatkan prinsip fundamental mekanika kuantum, yakni superposisi dan keterikatan (*entanglement*), untuk mengolah data secara masif dan simultan.

Prinsip utama yang dieksploitasi adalah superposisi di mana unit informasi kuantum atau disebut sebagai qubit dapat berada dalam kombinasi linear keadaan |0⟩ dan |1⟩ secara bersamaan. Dengan N qubit, sistem kuantum dapat merepresentasikan 2^N keadaan sekaligus. Hal ini memberikan percepatan eksponensial atau *quantum speedup* untuk menyelesaikan permasalahan komputasi yang sangat rumit, seperti simulasi molekul obat baru, optimasi logistik skala besar hingga pemecahan sandi kriptografi modern.

Sebagai contoh nyata, pada tahun 2019, Google AI Quantum mengumumkan pencapaian *quantum supremacy* menggunakan prosesor kuantum berbasis superkonduktor bernama Sycamore. Dalam eksperimen tersebut, Sycamore mampu menyelesaikan tugas komputasi khusus dengan pengambilan sampel dari sirkuit kuantum acak dalam waktu 200 detik, yang diklaim membutuhkan waktu sekitar 10.000 tahun jika dikerjakan oleh superkomputer klasik tercepat saat itu (Arute et al., 2019).

Bidang ini masih menghadapi tantangan utama, yaitu dekoherensi kuantum dan tingkat kesalahan atau *error rate* yang tinggi. Qubit sangat sensitif terhadap gangguan termal dan elektromagnetik dari lingkungan sekitar, sehingga informasi kuantum mudah rusak sebelum komputasi selesai. Oleh karena itu, pengembangan kode koreksi kesalahan kuantum (*quantum error correction*) menjadi fokus riset yang krusial di berbagai laboratorium riset dunia seperti IBM Quantum dan Google Quantum AI.

### Referensi
1. Arute, F., *et al.* (2019). Quantum supremacy using a programmable superconducting processor. *Nature*, **574**(7779), 505--510.
2. Nielsen, M. A., & Chuang, I. L. (2010). *Quantum Computation and Quantum Information*. Cambridge University Press.
