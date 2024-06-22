# Simulasi Pinjaman

Ini adalah aplikasi web sederhana untuk mensimulasikan pinjaman. Aplikasi ini memungkinkan pengguna untuk memasukkan jumlah pinjaman, jangka waktu, suku bunga, dan tipe perhitungan bunga, kemudian menghitung angsuran bulanan dan menyajikan tabel angsuran yang dapat diekspor ke PDF.

## Fitur

- Input jumlah pinjaman dengan format ribuan (Rp).
- Memilih bulan dan tahun mulai meminjam.
- Memilih jangka waktu pinjaman (12 hingga 120 bulan).
- Memilih tipe perhitungan bunga (Anuitas atau Flat).
- Menghitung angsuran bulanan dan menyajikan tabel angsuran.
- Ekspor hasil perhitungan ke PDF.

## Instalasi

1. Clone repository ini ke lokal:
    ```sh
    git clone https://github.com/username/repository-name.git
    cd repository-name
    ```

2. Buka file `index.html` di browser.

## Penggunaan

1. Masukkan jumlah pinjaman dalam format ribuan (contoh: 10000000).
2. Pilih bulan dan tahun mulai meminjam.
3. Pilih jangka waktu pinjaman (12 hingga 120 bulan).
4. Masukkan suku bunga per tahun.
5. Pilih tipe perhitungan bunga (Anuitas atau Flat).
6. Klik tombol **Hitung** untuk melihat tabel angsuran.
7. Klik tombol **Ekspor ke PDF** untuk mengekspor hasil perhitungan ke file PDF.

## Teknologi yang Digunakan

- HTML
- CSS (Bootstrap)
- JavaScript
- jsPDF (untuk ekspor PDF)
- jsPDF-AutoTable (untuk tabel di PDF)

## Lisensi

Proyek ini dilisensikan di bawah MIT License - lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.
