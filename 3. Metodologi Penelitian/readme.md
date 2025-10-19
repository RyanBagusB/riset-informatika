# Metodologi Penelitian

## Pendekatan Penelitian

Penelitian ini menggunakan pendekatan **R&D (Research and Development)** dan **studi kasus**, dengan fokus pada implementasi Soulbound Token (SBT) untuk sertifikasi digital ijazah yang aman dan sesuai regulasi.

## Tahapan Penelitian

1. **Studi Literatur**
   - Menganalisis penelitian terdahulu tentang NFT dan SBT dalam sertifikasi digital.
   - Menelaah regulasi terkait perlindungan data pribadi di Indonesia, termasuk UU No. 27 Tahun 2022 dan peraturan Kemendikbudristek mengenai digitalisasi pendidikan.
   - Mengidentifikasi gap penelitian dan potensi novelty.

2. **Perancangan Sistem**
   - Mendesain arsitektur sertifikasi digital berbasis SBT.
   - Menentukan strategi **off-chain metadata encryption** di IPFS, sehingga hanya hash yang tersimpan di blockchain.
   - Merancang alur penerbitan, verifikasi, dan validasi ijazah digital.

3. **Implementasi Prototype**
   - Mengembangkan prototype SBT menggunakan blockchain yang kompatibel dengan EVM.
   - Mengintegrasikan enkripsi metadata off-chain untuk data pribadi siswa.
   - Menyediakan antarmuka sederhana untuk penerbitan dan verifikasi ijazah digital.

4. **Pengujian dan Evaluasi**
   - Menguji sistem dari sisi keamanan, integritas data, dan kepatuhan terhadap regulasi.
   - Mengevaluasi kemudahan penggunaan bagi penerbit (sekolah/universitas) dan penerima (siswa/alumni).
   - Membandingkan hasil implementasi dengan pendekatan NFT tradisional.

5. **Analisis dan Kesimpulan**
   - Menganalisis efektivitas penggunaan SBT dan enkripsi metadata off-chain.
   - Menyusun rekomendasi untuk pengembangan sertifikasi digital di masa depan.

## Alat dan Teknologi

- Blockchain EVM-compatible (contoh: Polygon)
- IPFS untuk penyimpanan metadata terenkripsi
- Solidity untuk smart contract SBT
- JavaScript/React untuk antarmuka pengguna
- Library kriptografi untuk enkripsi data
- Tools pengujian keamanan dan validasi data
