# Absensi QR Kelas 6 — MIS Cokroaminoto Panyingkiran

Aplikasi web absensi siswa menggunakan QR Code untuk Kelas 6 MIS Cokroaminoto Panyingkiran.

**Wali Kelas:** Abdul Rahman, S.Pd.

## Fitur
- Dashboard kehadiran
- Scan QR melalui kamera HP/laptop
- Input absensi manual
- Tambah, edit, hapus siswa
- Import daftar siswa CSV
- Export data siswa CSV
- Generate QR per siswa
- Cetak kartu QR seluruh siswa
- Rekap bulanan Hadir/Izin/Sakit/Alpa
- Export rekap ke Excel `.xlsx`
- Data tersimpan di `localStorage` browser

## Menjalankan
Buka `index.html` di browser. Untuk fitur kamera, gunakan HTTPS (misalnya GitHub Pages) karena browser modern biasanya mensyaratkan secure context untuk akses kamera.

## Format template CSV
Gunakan kolom:
`NISN/ID,Nama,Jenis Kelamin`

Contoh:
`00001,Ahmad,L`

## GitHub Pages
1. Upload seluruh file repository.
2. Buka Settings → Pages.
3. Source: Deploy from a branch.
4. Branch: `main`, folder `/root`.
5. Simpan dan tunggu proses deployment.

## Catatan data
Versi ini menyimpan data pada browser/perangkat yang digunakan. Data tidak otomatis tersinkron antar perangkat. Untuk penggunaan sekolah multi-perangkat, tahap berikutnya dapat dihubungkan ke Google Sheets/Google Apps Script sebagai database pusat.
