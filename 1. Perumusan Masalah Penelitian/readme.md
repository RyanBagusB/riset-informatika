# BAB I – PENDAHULUAN

## Latar Belakang

Teknologi blockchain semakin banyak digunakan untuk aplikasi digital, termasuk di bidang pendidikan. Salah satu implementasi yang populer adalah penggunaan Non-Fungible Token (NFT) sebagai sertifikat digital. NFT memungkinkan pencatatan kepemilikan dan autentikasi dokumen secara transparan, sehingga banyak penelitian terdahulu fokus pada verifikasi ijazah, sertifikat pelatihan, atau pencapaian akademik menggunakan NFT. 

Meskipun NFT efektif dalam menjamin keaslian dokumen, ada kelemahan utama: NFT dapat dipindahtangankan. Dokumen yang seharusnya melekat pada pemiliknya bisa dialihkan atau dijual, sehingga menimbulkan risiko validitas sertifikat digital.

Sebagai alternatif, Soulbound Token (SBT) merupakan token non-fungible yang tidak dapat dipindahtangankan dan dirancang untuk merepresentasikan identitas, kredensial, atau pencapaian digital secara permanen. Dengan sifat terikat pada pemilik, SBT menawarkan solusi yang lebih aman untuk sertifikasi ijazah digital karena kepemilikan sertifikat tidak dapat dialihkan. Hal ini membuka peluang baru dalam penelitian blockchain untuk pendidikan, khususnya pada aspek validitas dan keamanan dokumen akademik.

Penerapan SBT menghadapi tantangan terkait privasi data. Sertifikat pendidikan memuat informasi sensitif seperti nama mahasiswa, NIM/NIK, nilai, dan jurusan. Menyimpan data ini langsung di blockchain membuatnya bersifat publik dan permanen, sehingga berpotensi melanggar privasi. Oleh karena itu, pendekatan off-chain metadata encryption diterapkan, di mana data sensitif disimpan secara terenkripsi pada IPFS, sementara blockchain hanya menyimpan hash atau referensinya. Dengan mekanisme ini, SBT tetap dapat diverifikasi secara publik tanpa mengorbankan kerahasiaan data pribadi.

Penerapan sertifikasi digital, khususnya dalam konteks ijazah, harus memperhatikan regulasi yang berlaku untuk memastikan perlindungan data pribadi. Di Indonesia, pengelolaan data pendidikan diatur oleh Undang-Undang Nomor 27 Tahun 2022 tentang Pelindungan Data Pribadi (UU PDP). UU ini mengatur mengenai asas, jenis data pribadi, hak subjek data pribadi, pemrosesan data pribadi, kewajiban pengendali data pribadi dan prosesor data pribadi, serta sanksi administratif bagi pelanggaran terhadap ketentuan dalam undang-undang ini.

## Rumusan Masalah

1. Bagaimana SBT dapat diterapkan sebagai media sertifikasi ijazah digital yang tidak dapat dipindahtangankan?  
2. Bagaimana mekanisme off-chain metadata encryption dapat meningkatkan privasi data pada SBT untuk ijazah digital?  
3. Bagaimana arsitektur sistem yang mengintegrasikan blockchain, IPFS, dan SBT untuk verifikasi ijazah digital yang aman, efisien, dan sesuai regulasi?

## Tujuan Penelitian

1. Mendesain dan mengimplementasikan model sertifikasi ijazah digital berbasis SBT.  
2. Menerapkan mekanisme off-chain metadata encryption untuk menjaga kerahasiaan data pribadi.  
3. Menyusun arsitektur sistem yang aman, efisien, dan patuh terhadap regulasi yang berlaku dalam digitalisasi sertifikasi ijazah.

## Manfaat Penelitian

1. Akademik: Menambah literatur terkait penerapan SBT dalam sertifikasi digital dengan fokus pada privasi data.  
2. Praktis: Memberikan solusi bagi institusi pendidikan dalam digitalisasi ijazah secara aman dan efisien.  
3. Teknis: Menjadi acuan dalam pengembangan sistem berbasis blockchain dengan integrasi penyimpanan off-chain untuk data sensitif.  
4. Regulasi: Menunjukkan kepatuhan terhadap undang-undang perlindungan data pribadi dan regulasi pendidikan digital.

## Batasan Penelitian

1. Penelitian ini hanya membahas penerapan SBT untuk sertifikasi ijazah.  
2. Data pribadi (nama, NIK, nilai) disimpan secara terenkripsi off-chain menggunakan IPFS.  
3. Blockchain yang digunakan bersifat testnet atau simulasi untuk demonstrasi konsep, bukan mainnet langsung.  
4. Penelitian fokus pada aspek arsitektur dan privasi, bukan aspek legal formal atau regulasi pendidikan secara rinci.
