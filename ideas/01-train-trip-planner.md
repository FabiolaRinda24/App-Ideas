# 🚉 Train Trip Planner & Budget Estimator

> **Bahasa / Language:** Indonesia 🇮🇩 | English 🇬🇧  
> **Status:** 📝 Idea Stage  
> **Platform:** 📱 Mobile First (Android & iOS)  
> **Last Updated:** June 2026

---

## 🇮🇩 VERSI BAHASA INDONESIA

---

### 📋 Latar Belakang Masalah

Banyak masyarakat Indonesia yang gemar bepergian menggunakan kereta api — baik KRL untuk perjalanan harian maupun kereta jarak jauh untuk perjalanan antar kota. Namun, belum ada aplikasi khusus yang membantu mereka **merencanakan perjalanan sekaligus mengestimasi total biaya** dari awal hingga akhir perjalanan.

Aplikasi resmi seperti **Access by KAI** berfokus pada transaksi tiket, sementara aplikasi budget planner umum seperti **Money Manager** atau **Wallet** tidak memiliki konteks khusus perjalanan kereta. Hal ini membuat pengguna harus berpindah-pindah aplikasi dan menghitung manual di luar aplikasi.

---

### 👥 Target Pengguna

| Segmen | Usia | Karakteristik |
|---|---|---|
| 🧑‍💻 Gen Z | 17 – 27 tahun | Solo traveler, budget terbatas, serba digital |
| 👨‍💼 Milenial & Pekerja Produktif | 28 – 40 tahun | Perjalanan dinas atau weekend trip, butuh efisiensi |
| 👨‍👩‍👧 Keluarga Muda | 28 – 40 tahun | Traveling bersama keluarga, perlu breakdown biaya detail |
| 🎒 Backpacker Lokal | 18 – 35 tahun | Multi-kota, sering kombinasi KRL + Kereta Jauh |
| 👴 Pensiunan & Lansia | 55 tahun ke atas | Suka naik kereta, butuh tampilan simpel & mudah dipahami |

---

### 😣 Masalah yang Diselesaikan

1. Pengguna kesulitan **mengestimasi total biaya** perjalanan kereta sebelum berangkat
2. Tidak ada tools khusus untuk **merencanakan itinerary berbasis kereta** di Indonesia
3. Pengguna harus **berpindah-pindah aplikasi** antara pembelian tiket, maps, dan catatan keuangan
4. Tidak ada fitur **split bill** khusus untuk perjalanan kereta bersama teman
5. Tidak ada tempat untuk **mendokumentasikan histori perjalanan** kereta secara rapi

---

### ✨ Fitur Utama (MVP — Minimum Viable Product)

#### 🗂️ Trip Planner
- [ ] Buat rencana perjalanan baru (nama trip, tanggal, rute)
- [ ] Tambahkan stasiun keberangkatan & tujuan
- [ ] Pilih jenis kereta (KRL, Kereta Lokal, Kereta Jarak Jauh)
- [ ] Simpan & edit rencana perjalanan

#### 💰 Budget Estimator
- [ ] Input estimasi harga tiket kereta
- [ ] Tambahkan estimasi biaya lain (transportasi lokal, makan, penginapan)
- [ ] Tampilkan total estimasi biaya perjalanan
- [ ] Perbandingan estimasi vs pengeluaran aktual

#### 📊 Expense Tracker (Selama Perjalanan)
- [ ] Catat pengeluaran aktual per kategori
- [ ] Kategori khusus: Tiket, Transport Lokal, Makan, Penginapan, Oleh-oleh, Lainnya
- [ ] Notifikasi jika pengeluaran melebihi budget

#### 👫 Split Bill
- [ ] Tambahkan anggota perjalanan
- [ ] Hitung pembagian biaya otomatis per orang
- [ ] Rekap siapa yang masih hutang berapa

#### 📖 Trip History & Journal
- [ ] Simpan histori semua perjalanan
- [ ] Tambahkan foto & catatan per perjalanan
- [ ] Statistik perjalanan (total trip, total jarak, total pengeluaran)

---

### 🆚 Perbandingan dengan Kompetitor

| Fitur | Access by KAI | Money Manager | Traveloka | Train Trip Planner |
|---|---|---|---|---|
| Beli tiket resmi | ✅ | ❌ | ✅ | ❌ |
| Estimasi budget sebelum trip | ❌ | ⚠️ Manual | ❌ | ✅ |
| Itinerary planner kereta | ❌ | ❌ | ⚠️ Terbatas | ✅ |
| Expense tracker perjalanan | ❌ | ✅ Umum | ❌ | ✅ Khusus kereta |
| Split bill teman | ❌ | ❌ | ❌ | ✅ |
| Histori & jurnal perjalanan | ❌ | ❌ | ❌ | ✅ |
| Dirancang khusus kereta 🇮🇩 | ✅ | ❌ | ❌ | ✅ |

---

### 🎯 Keunikan Aplikasi (USP)

> *"Satu-satunya aplikasi yang dirancang khusus sebagai travel companion kereta api Indonesia — bukan untuk membeli tiket, melainkan untuk merencanakan, mengestimasi biaya, dan mendokumentasikan perjalanan kereta dari awal hingga akhir."*

---

### 🛠️ Tech Stack

| Layer | Teknologi | Fungsi |
|---|---|---|
| 📱 Mobile App | **Flutter** | Tampilan Android & iOS dari satu codebase |
| ☁️ Database & Auth | **Firebase** | Simpan data user, login, cloud sync |
| 🗺️ Peta & Lokasi | **Google Maps API** | Tampilkan rute & lokasi stasiun |
| 📢 Monetisasi Iklan | **Google AdMob** | Iklan non-intrusif sebagai sumber pendapatan |

---

### 📱 Platform

- 📱 **Mobile (Utama):** Android & iOS
- 🌐 **Web (Fase 2):** Versi browser responsive — direncanakan setelah MVP mobile selesai
- 💻 **Tablet:** Supported via responsive design Flutter

---

### 🔐 Keamanan Aplikasi

- 🔑 Login menggunakan **Google Account atau Email**
- 🔒 Data perjalanan bersifat **private per akun pengguna**
- ☁️ **Cloud backup otomatis** via Firebase
- 🛡️ Tidak menyimpan data keuangan sensitif (no kartu kredit/debit)

---

### 💰 Model Bisnis

**Gratis + Iklan (Free with Ads)**

| Tipe | Keterangan |
|---|---|
| 🆓 Gratis sepenuhnya | Semua fitur dapat diakses tanpa biaya |
| 📢 Iklan | Banner & interstitial ads via Google AdMob |
| 🚀 Versi Premium (Fase 2) | Opsi hapus iklan dengan pembayaran one-time |

---

### ⚠️ Keterbatasan & Kekurangan (Acknowledged)

Sebagai bentuk transparansi dan berpikir kritis, berikut adalah keterbatasan yang disadari:

1. **Tidak bisa beli tiket langsung** — pengguna tetap perlu membuka Access by KAI atau KAI.id
2. **Harga tiket diinput manual** — belum ada integrasi API resmi dari KAI
3. **Niche market** — hanya untuk pengguna kereta, bukan traveler pesawat atau bus
4. **Data rute & jadwal statis** — perlu update manual jika KAI mengubah rute atau harga
5. **Bergantung pada internet** — fitur cloud sync membutuhkan koneksi data

---

### 🗺️ Roadmap Pengembangan

```
Phase 1 — MVP (Minimum Viable Product)
├── Trip Planner (basic)
├── Budget Estimator
├── Expense Tracker
└── Trip History

Phase 2 — Enhanced Features  
├── Split Bill
├── Web Version
├── Notifikasi Budget
└── Versi Premium (no ads)

Phase 3 — Advanced
├── Integrasi jadwal kereta (jika API tersedia)
├── Rekomendasi destinasi wisata dekat stasiun
└── Komunitas traveler kereta
```

---

### 👤 Tentang Pembuat Ide

Ide ini lahir dari pengalaman pribadi sebagai mantan **Ticketing Officer di stasiun kereta api selama 4 tahun**, yang setiap hari menyaksikan penumpang bingung merencanakan perjalanan dan mengelola biaya perjalanan kereta mereka.

---
---

## 🇬🇧 ENGLISH VERSION

---

### 📋 Problem Statement

Many Indonesians enjoy traveling by train — whether commuting via KRL or taking long-distance trains between cities. However, no dedicated app exists to help them **plan their journey and estimate total travel costs** from start to finish.

Official apps like **Access by KAI** focus on ticket transactions, while general budget planners like **Money Manager** or **Wallet** lack train travel context. This forces users to switch between multiple apps and manually calculate expenses outside of any single platform.

---

### 👥 Target Users

| Segment | Age | Characteristics |
|---|---|---|
| 🧑‍💻 Gen Z | 17 – 27 y.o. | Solo travelers, limited budget, digitally native |
| 👨‍💼 Millennials & Professionals | 28 – 40 y.o. | Business trips or weekend getaways, need efficiency |
| 👨‍👩‍👧 Young Families | 28 – 40 y.o. | Family trips, need detailed cost breakdown |
| 🎒 Local Backpackers | 18 – 35 y.o. | Multi-city trips, often combine KRL + long-distance trains |
| 👴 Retirees & Seniors | 55+ y.o. | Prefer trains for comfort, need simple & clear UI |

---

### 😣 Problems Being Solved

1. Users struggle to **estimate total travel costs** before departure
2. No dedicated tool for **train-based itinerary planning** in Indonesia
3. Users must **switch between multiple apps** for ticket booking, maps, and expense tracking
4. No **split bill feature** designed specifically for group train travel
5. No single place to **document and review train trip history**

---

### ✨ Core Features (MVP)

#### 🗂️ Trip Planner
- [ ] Create new trip plan (name, date, route)
- [ ] Add departure & destination stations
- [ ] Select train type (KRL, Local Train, Long-Distance Train)
- [ ] Save & edit trip plans

#### 💰 Budget Estimator
- [ ] Input estimated train ticket prices
- [ ] Add other cost estimates (local transport, food, accommodation)
- [ ] Display total estimated trip cost
- [ ] Compare estimated vs actual spending

#### 📊 Expense Tracker (During Trip)
- [ ] Log actual expenses by category
- [ ] Custom categories: Tickets, Local Transport, Food, Accommodation, Souvenirs, Others
- [ ] Budget alert notification when overspending

#### 👫 Split Bill
- [ ] Add travel companions
- [ ] Auto-calculate cost split per person
- [ ] Summary of who owes what

#### 📖 Trip History & Journal
- [ ] Save all past trip history
- [ ] Add photos & notes per trip
- [ ] Travel statistics (total trips, total distance, total spending)

---

### 🆚 Competitor Comparison

| Feature | Access by KAI | Money Manager | Traveloka | Train Trip Planner |
|---|---|---|---|---|
| Official ticket purchase | ✅ | ❌ | ✅ | ❌ |
| Pre-trip budget estimation | ❌ | ⚠️ Manual | ❌ | ✅ |
| Train-based itinerary planner | ❌ | ❌ | ⚠️ Limited | ✅ |
| Travel expense tracker | ❌ | ✅ General | ❌ | ✅ Train-specific |
| Group split bill | ❌ | ❌ | ❌ | ✅ |
| Trip history & journal | ❌ | ❌ | ❌ | ✅ |
| Designed for 🇮🇩 train travel | ✅ | ❌ | ❌ | ✅ |

---

### 🎯 Unique Selling Point (USP)

> *"The only app designed specifically as an Indonesian train travel companion — not for buying tickets, but for planning, estimating costs, and documenting train journeys from start to finish."*

---

### 🛠️ Tech Stack

| Layer | Technology | Purpose |
|---|---|---|
| 📱 Mobile App | **Flutter** | Android & iOS from a single codebase |
| ☁️ Database & Auth | **Firebase** | User data storage, login, cloud sync |
| 🗺️ Maps & Location | **Google Maps API** | Display routes & station locations |
| 📢 Ad Monetization | **Google AdMob** | Non-intrusive ads as revenue source |

---

### 📱 Platform

- 📱 **Mobile (Primary):** Android & iOS
- 🌐 **Web (Phase 2):** Responsive browser version — planned after mobile MVP
- 💻 **Tablet:** Supported via Flutter responsive design

---

### 🔐 Security Features

- 🔑 Login via **Google Account or Email**
- 🔒 Trip data is **private per user account**
- ☁️ **Automatic cloud backup** via Firebase
- 🛡️ No sensitive financial data stored (no credit/debit card info)

---

### 💰 Business Model

**Free with Ads**

| Type | Description |
|---|---|
| 🆓 Fully free | All features accessible at no cost |
| 📢 Ads | Banner & interstitial ads via Google AdMob |
| 🚀 Premium Version (Phase 2) | Option to remove ads via one-time payment |

---

### ⚠️ Known Limitations

In the spirit of transparency and critical thinking:

1. **Cannot purchase tickets directly** — users still need Access by KAI or KAI.id
2. **Ticket prices are manually entered** — no official KAI API integration available
3. **Niche market** — designed only for train travelers, not for flights or buses
4. **Static route & schedule data** — requires manual updates if KAI changes routes or pricing
5. **Internet dependent** — cloud sync features require data connection

---

### 🗺️ Development Roadmap

```
Phase 1 — MVP (Minimum Viable Product)
├── Trip Planner (basic)
├── Budget Estimator
├── Expense Tracker
└── Trip History

Phase 2 — Enhanced Features
├── Split Bill
├── Web Version
├── Budget Notifications
└── Premium Version (no ads)

Phase 3 — Advanced
├── Live train schedule integration (if API available)
├── Destination recommendations near stations
└── Indonesian train traveler community
```

---

### 👤 About the Idea Creator

This idea was born from 4 years of personal experience as a **Train Station Ticketing Officer**, witnessing daily how passengers struggled to plan their journeys and manage travel expenses effectively.

---

*💡 This is an App Idea document — part of a portfolio to demonstrate product thinking, user empathy, and structured problem solving.*
