---
description: Komponen DAO...
cover: .gitbook/assets/covet-gitbook (1).png
coverY: 0
---

# 🔏 Bagian 02

DAO, seperti tubuh manusia, hanya bisa berjalan kalau organ-organnya bekerja bersama. Di DAO, _organ-organ_ ini tidak terlihat secara fisik, tapi semuanya hidup di atas jaringan blockchain.

Mari kita sama-sama lihat komponen utamanya.

<figure><img src=".gitbook/assets/03.png" alt=""><figcaption><p>Komponen DAO</p></figcaption></figure>

***

#### 🪙 **1. Token — Simbol Kepemilikan & Suara**

Token di DAO bukan sekadar _aset digital_. Ia adalah:

* **Simbol keanggotaan**
* **Alat voting**
* **Akses untuk membuat atau mendukung proposal**

Jenis token biasanya:

* **ERC-20** → untuk governance umum
* **NFT (ERC-721/1155)** → bisa jadi simbol keanggotaan eksklusif

Semakin banyak token Anda miliki, semakin besar _pengaruh suara_ Anda dalam DAO. Tapi ini bisa membawa masalah jika tidak diatur (nanti dibahas di bagian Tantangan DAO).

<figure><img src=".gitbook/assets/03a.png" alt=""><figcaption><p>Token - Simbol Kepemilikan &#x26; Suara</p></figcaption></figure>

***

#### 🗳️ **2. Proposal — Gagasan yang Diuji Bersama**

Semua keputusan besar dimulai dari **proposal**:

* Siapa pun (yang punya cukup token) bisa membuat proposal.
* Proposal bisa berisi: pendanaan, perubahan aturan, kerjasama baru, dll.
* Proposal kemudian diumumkan dan dibuka untuk voting.

Biasanya ada _periode diskusi_, lalu _periode voting_, agar setiap anggota DAO bisa membaca dan mempertimbangkan dengan matang.

<figure><img src=".gitbook/assets/03b.png" alt=""><figcaption><p>Proposal - Gagasan yang Diuji Bersama</p></figcaption></figure>

***

#### 📈 **3. Voting — Mekanisme Pengambilan Keputusan**

Sistem voting DAO bisa berbeda-beda, tapi prinsip umumnya:

* 1 token = 1 suara (token-weighted voting)
* Ada batas waktu voting (misalnya 7 hari)
* Harus memenuhi **kuorum** (jumlah minimal partisipasi)
* Harus memenuhi **mayoritas** (misalnya 50% +1)

DAO bisa memilih:

* **Simple majority** (51% setuju = jalan)
* **Supermajority** (67% atau lebih untuk perubahan besar)
* **Quadratic voting** (melawan dominasi whale, dibahas nanti)

Semua hasil voting dieksekusi otomatis atau disiapkan untuk eksekusi oleh smart contract.

<figure><img src=".gitbook/assets/03c.png" alt=""><figcaption><p>Voting - Mekanisme Pengambilan Suara</p></figcaption></figure>

***

#### 🏦 **4. Treasury — Dompet Bersama DAO**

Inilah **“uang kas organisasi”**, tapi disimpan dalam bentuk kripto (ETH, OiOi, dll.) di smart contract yang:

* Hanya bisa diakses lewat hasil proposal yang disetujui.
* Semua transaksi tercatat secara terbuka (on-chain).
* Tidak bisa diubah atau dicuri sepihak oleh siapa pun.

Contoh penggunaan:

* Mendanai proyek komunitas
* Membayar developer open source
* Membeli aset kolektif (seperti NFT, domain, atau IP)

<figure><img src=".gitbook/assets/03d.png" alt=""><figcaption><p>Treasury - Dompet Bersama DAO</p></figcaption></figure>

***

#### ⚙️ **5. Smart Contract — Aturan yang Tidak Bisa Dilanggar**

Semua logika DAO, mulai dari proposal, voting, hingga pencairan dana, **ditulis dalam smart contract**.

Smart contract ini bersifat:

* **Immutable** (tidak bisa diubah semaunya setelah diluncurkan)
* **Terbuka** (siapa saja bisa melihat isi kodenya)
* **Otomatis** (mengeksekusi hasil voting tanpa campur tangan manusia)

Kalau aturan ditulis:

> “Jika 60% suara mendukung, maka kirim 100 ETH ke wallet pengembang,”\
> maka sistem akan melakukannya tanpa bisa dibatalkan oleh siapa pun — kecuali aturan diubah lewat proposal baru.

<figure><img src=".gitbook/assets/03e.png" alt=""><figcaption><p>Smart Contract - Aturan yang Tidak Bisa Dilanggar</p></figcaption></figure>

***

Dengan semua komponen ini, DAO bisa berjalan tanpa kantor, tanpa bos, tanpa korupsi. Tapi, apakah semuanya sesederhana itu?

Mari kita telusuri **Bagian 3: Cara Kerja DAO** — dan lihat bagaimana semua komponen ini bersinergi dalam praktik.

***
