# SOAL LATIHAN UJIAN CORPORATE FINANCE
## Berdasarkan Kisi-Kisi Semester 1 TA 2025-2026

---

## CHAPTER 20: RAISING CAPITAL (KONSEP)

### Soal 1
Jelaskan perbedaan antara Initial Public Offering (IPO) dan Seasoned Equity Offering (SEO). Berikan contoh situasi kapan perusahaan sebaiknya menggunakan masing-masing metode tersebut.

**JAWABAN:**

**IPO (Initial Public Offering):**
- Penawaran saham pertama kali kepada publik oleh perusahaan yang sebelumnya berstatus privat
- Mengubah status perusahaan dari private menjadi public company
- Biasanya dilakukan oleh perusahaan yang ingin ekspansi besar atau pemilik awal ingin exit
- Contoh situasi: Startup teknologi yang sudah mature dan ingin mendapat dana untuk ekspansi global

**SEO (Seasoned Equity Offering):**
- Penawaran saham tambahan oleh perusahaan yang sudah go public
- Status perusahaan tetap public, hanya menambah jumlah saham beredar
- Dilakukan untuk penambahan modal kerja, akuisisi, atau melunasi hutang
- Contoh situasi: Perusahaan publik yang ingin mengakuisisi kompetitor dan membutuhkan dana segar

**Perbedaan Utama:**
1. IPO = pertama kali go public; SEO = sudah public, tambah saham
2. IPO lebih kompleks dan mahal (due diligence, roadshow, underwriting)
3. SEO lebih cepat prosesnya karena perusahaan sudah punya track record publik
4. IPO menghadapi underpricing phenomenon; SEO menghadapi dilusi untuk pemegang saham existing

---

### Soal 2
Apa yang dimaksud dengan "underpricing" dalam konteks IPO? Mengapa fenomena ini sering terjadi? Sebutkan minimal 3 teori yang menjelaskan underpricing.

**JAWABAN:**

**Definisi Underpricing:**
Underpricing adalah fenomena dimana harga saham pada hari pertama perdagangan di pasar sekunder lebih tinggi dibandingkan dengan harga penawaran di pasar perdana (offering price). Biasanya diukur dengan initial return = (P1 - P0)/P0 × 100%.

**Mengapa Terjadi:**
Underpricing merugikan perusahaan dan pemegang saham lama (karena "uang tertinggal di meja"), namun menguntungkan investor yang mendapat alokasi saham IPO.

**3 Teori Underpricing:**

1. **Asymmetric Information Theory (Winner's Curse)**
   - Informed investors hanya membeli jika harga murah
   - Uninformed investors mendapat adverse selection
   - Underwriter sengaja underprice agar uninformed investors tetap mau membeli

2. **Signaling Theory**
   - Perusahaan berkualitas baik sengaja underprice di IPO pertama
   - Sebagai sinyal kualitas untuk SEO di masa depan
   - Biaya underpricing adalah investasi untuk reputasi

3. **Institutional Explanation**
   - Underwriter ingin menjaga reputasi dengan investor
   - Underwriter lebih konservatif dalam pricing untuk menghindari risiko IPO gagal
   - Konflik kepentingan: underwriter lebih loyal ke buyer daripada issuer

**Teori Tambahan:**
- **Lawsuit Avoidance**: Hindari tuntutan hukum jika harga turun drastis
- **Partial Adjustment Phenomenon**: Harga tidak disesuaikan penuh saat permintaan tinggi di bookbuilding

---

### Soal 3
PT Maju Jaya berencana melakukan IPO dengan menerbitkan 100 juta saham baru. Sebelum IPO, perusahaan memiliki 400 juta saham. Underwriter menetapkan offering price Rp 2.500 per saham. Pada hari pertama perdagangan, harga saham ditutup pada Rp 3.200 per saham.

Hitung:
a) Berapa dana yang diperoleh perusahaan dari IPO?
b) Berapa persentase underpricing yang terjadi?
c) Berapa "uang yang tertinggal di meja" (money left on the table)?
d) Berapa persentase dilusi kepemilikan pemegang saham lama?

**JAWABAN:**

**a) Dana yang diperoleh perusahaan:**
```
Dana = Jumlah saham IPO × Offering price
Dana = 100 juta × Rp 2.500
Dana = Rp 250 miliar
```

**b) Persentase underpricing:**
```
Underpricing = (P1 - P0) / P0 × 100%
Underpricing = (3.200 - 2.500) / 2.500 × 100%
Underpricing = 700 / 2.500 × 100%
Underpricing = 28%
```

**c) Money left on the table:**
```
Money left = Jumlah saham IPO × (Harga penutupan - Offering price)
Money left = 100 juta × (3.200 - 2.500)
Money left = 100 juta × 700
Money left = Rp 70 miliar
```
Ini adalah uang yang seharusnya bisa diperoleh perusahaan jika offering price ditetapkan pada Rp 3.200.

**d) Persentase dilusi:**
```
Saham sebelum IPO = 400 juta
Saham setelah IPO = 400 juta + 100 juta = 500 juta

Kepemilikan lama sebelum IPO = 100%
Kepemilikan lama setelah IPO = 400/500 = 80%

Dilusi = 100% - 80% = 20%
```

**Interpretasi:**
- Pemegang saham lama mengalami dilusi 20%
- Namun nilai perusahaan meningkat signifikan karena ada dana segar Rp 250 miliar
- Underpricing 28% cukup tinggi, menandakan ada mispricing atau strategi tertentu dari underwriter

---

## CHAPTER 22: OPTIONS AND CORPORATE FINANCE (HITUNGAN)

### Soal 4
Sebuah call option untuk saham PT XYZ memiliki data sebagai berikut:
- Harga saham saat ini (S₀) = Rp 5.000
- Strike price (K) = Rp 4.500
- Waktu jatuh tempo = 3 bulan
- Harga call option (C) = Rp 700

Hitung:
a) Nilai intrinsik call option
b) Nilai time value call option
c) Apakah opsi ini in-the-money, at-the-money, atau out-of-the-money?

**JAWABAN:**

**a) Nilai Intrinsik:**
```
Intrinsic Value = Max(S₀ - K, 0)
Intrinsic Value = Max(5.000 - 4.500, 0)
Intrinsic Value = Max(500, 0)
Intrinsic Value = Rp 500
```

**b) Nilai Time Value:**
```
Time Value = Harga Option - Intrinsic Value
Time Value = 700 - 500
Time Value = Rp 200
```

**c) Status Opsi:**
**In-the-money (ITM)**

Alasan: Karena harga saham saat ini (Rp 5.000) lebih tinggi dari strike price (Rp 4.500), call option ini menguntungkan jika dieksekusi sekarang.

**Klasifikasi opsi:**
- **In-the-money (ITM)**: S₀ > K untuk call option
- **At-the-money (ATM)**: S₀ = K
- **Out-of-the-money (OTM)**: S₀ < K untuk call option

**Interpretasi:**
- Intrinsic value Rp 500 menunjukkan keuntungan langsung jika opsi dieksekusi
- Time value Rp 200 mencerminkan nilai dari kemungkinan harga saham naik lebih tinggi dalam 3 bulan
- Total premi Rp 700 adalah harga yang harus dibayar investor untuk hak membeli saham

---

### Soal 5
Seorang investor membeli 1 kontrak put option dengan data:
- Strike price (K) = Rp 10.000
- Premium yang dibayar = Rp 500
- Pada saat expiration, harga saham = Rp 8.500

Hitung:
a) Payoff dari put option
b) Profit/loss bersih investor
c) Break-even price untuk strategi ini

**JAWABAN:**

**a) Payoff Put Option:**
```
Payoff = Max(K - ST, 0)
Payoff = Max(10.000 - 8.500, 0)
Payoff = Max(1.500, 0)
Payoff = Rp 1.500
```

**b) Profit/Loss Bersih:**
```
Profit = Payoff - Premium
Profit = 1.500 - 500
Profit = Rp 1.000 per saham
```
Investor mendapat **keuntungan Rp 1.000**

**c) Break-even Price:**
```
Break-even terjadi ketika: Payoff = Premium
K - ST = Premium
ST = K - Premium
ST = 10.000 - 500
ST = Rp 9.500
```

**Analisis:**
- Jika harga saham di bawah Rp 9.500 → Profit
- Jika harga saham = Rp 9.500 → Break-even
- Jika harga saham di atas Rp 9.500 → Loss
- Maximum loss = Premium = Rp 500 (jika ST ≥ K)
- Maximum profit = K - Premium = Rp 9.500 (jika ST = 0, secara teoritis)

**Payoff Diagram:**
```
Profit
  |
1.500|         /
  |        /
1.000|       /
  |      /
  500|     /
  |    /
    0|___/__________ Harga Saham
  |  /    9.500  10.000
-500| /
     (Maximum Loss)
```

---

### Soal 6
PT Teknologi Maju sedang mengevaluasi proyek investasi dengan karakteristik real option. Investasi awal = Rp 5 miliar. Jika kondisi pasar baik, NPV = Rp 8 miliar. Jika kondisi buruk, perusahaan bisa abandon project dan recover Rp 2 miliar.

Probabilitas kondisi baik = 60%, kondisi buruk = 40%.

Hitung:
a) NPV tanpa mempertimbangkan opsi abandonment
b) Nilai opsi abandonment
c) NPV dengan mempertimbangkan opsi (expanded NPV)

**JAWABAN:**

**a) NPV tanpa opsi abandonment:**

Jika kondisi baik:
```
NPV_baik = 8 miliar - 5 miliar = Rp 3 miliar
```

Jika kondisi buruk (tanpa opsi):
```
NPV_buruk = 0 - 5 miliar = -Rp 5 miliar
```

Expected NPV tradisional:
```
E(NPV) = (0,6 × 3 miliar) + (0,4 × -5 miliar)
E(NPV) = 1,8 miliar - 2 miliar
E(NPV) = -Rp 0,2 miliar
```

**Kesimpulan:** Proyek ditolak karena NPV negatif

**b) Nilai opsi abandonment:**

Dengan opsi abandonment, jika kondisi buruk:
```
Recovery value = Rp 2 miliar
Loss setelah abandonment = -5 miliar + 2 miliar = -Rp 3 miliar
```

Nilai opsi:
```
Option value = NPV_buruk_tanpa_opsi - NPV_buruk_dengan_opsi
Option value = -5 miliar - (-3 miliar)
Option value = Rp 2 miliar
```

Atau bisa dihitung:
```
Expected value of option = Probabilitas_buruk × Recovery_value
Expected value of option = 0,4 × 2 miliar
Expected value of option = Rp 0,8 miliar
```

**c) Expanded NPV:**

```
NPV dengan opsi = (0,6 × 3 miliar) + (0,4 × -3 miliar)
NPV dengan opsi = 1,8 miliar - 1,2 miliar
NPV dengan opsi = Rp 0,6 miliar
```

Atau:
```
Expanded NPV = Traditional NPV + Option value
Expanded NPV = -0,2 miliar + 0,8 miliar
Expanded NPV = Rp 0,6 miliar
```

**Kesimpulan dan Interpretasi:**
- Tanpa real option: NPV = -Rp 0,2 miliar → **TOLAK**
- Dengan real option: NPV = Rp 0,6 miliar → **TERIMA**
- Opsi abandonment memberikan nilai tambah Rp 0,8 miliar
- Real options membuat proyek yang tadinya tidak layak menjadi layak
- Fleksibilitas manajemen memiliki nilai ekonomis

---

## CHAPTER 24: WARRANTS AND CONVERTIBLES (KONSEP)

### Soal 7
Jelaskan perbedaan antara warrant dan call option. Mengapa perusahaan lebih sering menerbitkan warrant sebagai "pemanis" (sweetener) dalam penerbitan obligasi?

**JAWABAN:**

**Perbedaan Warrant vs Call Option:**

| Aspek | Warrant | Call Option |
|-------|---------|-------------|
| **Penerbit** | Diterbitkan oleh perusahaan | Diterbitkan oleh investor/pihak ketiga |
| **Sumber saham** | Saham baru (dilusi) | Saham existing di pasar |
| **Jangka waktu** | Jangka panjang (3-10 tahun) | Jangka pendek (hari-bulan) |
| **Efek pada modal** | Menambah modal perusahaan saat exercise | Tidak ada efek pada modal perusahaan |
| **Dilusi** | Menyebabkan dilusi kepemilikan | Tidak ada dilusi |
| **Detachable** | Bisa dipisah dan diperdagangkan terpisah | Biasanya tidak bisa dipisah |

**Mengapa Warrant Digunakan sebagai Sweetener:**

1. **Menurunkan Biaya Bunga:**
   - Dengan memberikan warrant, perusahaan bisa menawarkan kupon lebih rendah
   - Investor bersedia menerima bunga lebih rendah karena ada kompensasi dari potensi capital gain warrant
   - Contoh: Obligasi normal 10%, obligasi + warrant cukup 7%

2. **Menarik Investor:**
   - Warrant memberikan upside potential
   - Investor mendapat kombinasi: fixed income (dari obligasi) + equity participation (dari warrant)
   - Lebih menarik dibanding obligasi biasa

3. **Efisien untuk Startup/Growth Companies:**
   - Perusahaan dengan risiko tinggi bisa menawarkan warrant untuk kompensasi risiko
   - Cash flow dihemat di awal (bunga rendah)
   - Dilusi baru terjadi di masa depan ketika perusahaan sudah berkembang

4. **Tax Benefit:**
   - Bunga obligasi tax-deductible
   - Exercise warrant bukan beban perusahaan, hanya dilusi

5. **Signal Confidence:**
   - Management yakin harga saham akan naik
   - Dilusi di masa depan tidak masalah karena pie sudah lebih besar

**Contoh Struktur:**
```
Bond + Warrant Package:
- Face value: Rp 100 juta
- Kupon: 7% per tahun (vs 10% tanpa warrant)
- Warrant: Hak beli 1.000 saham @ Rp 10.000
- Maturity: 5 tahun
- Warrant expiration: 3 tahun
```

---

### Soal 8
PT Berkah menerbitkan 1.000 lembar convertible bond dengan ketentuan:
- Face value = Rp 100 juta per lembar
- Conversion ratio = 10.000 saham per bond
- Harga saham saat ini = Rp 8.500
- Harga pasar convertible bond = Rp 105 juta

Hitung:
a) Conversion price
b) Conversion value
c) Conversion premium per saham
d) Conversion premium ratio

**JAWABAN:**

**a) Conversion Price:**
```
Conversion Price = Face Value / Conversion Ratio
Conversion Price = Rp 100.000.000 / 10.000 saham
Conversion Price = Rp 10.000 per saham
```

**b) Conversion Value:**
```
Conversion Value = Conversion Ratio × Harga Saham Saat Ini
Conversion Value = 10.000 × Rp 8.500
Conversion Value = Rp 85.000.000
```

**c) Conversion Premium per Saham:**
```
Conversion Premium/share = Conversion Price - Harga Saham
Conversion Premium/share = Rp 10.000 - Rp 8.500
Conversion Premium/share = Rp 1.500
```

**d) Conversion Premium Ratio:**
```
Conversion Premium Ratio = (Conversion Price - Harga Saham) / Harga Saham × 100%
Conversion Premium Ratio = (10.000 - 8.500) / 8.500 × 100%
Conversion Premium Ratio = 1.500 / 8.500 × 100%
Conversion Premium Ratio = 17,65%
```

**Atau dihitung dari harga pasar bond:**
```
Market Conversion Price = Harga Pasar Bond / Conversion Ratio
Market Conversion Price = Rp 105.000.000 / 10.000
Market Conversion Price = Rp 10.500

Market Conversion Premium = (10.500 - 8.500) / 8.500 × 100%
Market Conversion Premium = 23,53%
```

**Interpretasi:**

1. **Conversion Price Rp 10.000:**
   - Investor effectively membeli saham di harga Rp 10.000 jika konversi
   - Saat ini saham masih Rp 8.500, jadi belum menguntungkan untuk konversi

2. **Conversion Value Rp 85 juta:**
   - Nilai obligasi jika langsung dikonversi sekarang
   - Lebih rendah dari face value Rp 100 juta
   - Lebih rendah dari market price Rp 105 juta

3. **Conversion Premium 17,65%:**
   - Saham harus naik 17,65% agar konversi impas
   - Break-even price = Rp 10.000
   - Investor bersedia bayar premium karena:
     * Downside protection (tetap dapat face value + kupon)
     * Upside potential (jika saham naik)

4. **Market Price Rp 105 juta > Face Value Rp 100 juta:**
   - Bond trading at premium karena ada option value
   - Investor menilai probabilitas saham naik cukup tinggi
   - Premium Rp 5 juta = nilai opsi konversi

**Keputusan:**
- **Jangan konversi sekarang** (rugi Rp 20 juta)
- **Tunggu** hingga harga saham > Rp 10.500 (untuk impas dengan harga pasar)
- Atau tetap hold bond dan terima kupon

---

## CHAPTER 25: DERIVATIVES AND HEDGING RISK (KONSEP)

### Soal 9
PT Eksportir Indonesia akan menerima pembayaran USD 1.000.000 dalam 6 bulan. Manajemen khawatir rupiah akan menguat (USD melemah).

Jelaskan 3 strategi hedging yang bisa dilakukan menggunakan derivatives:
a) Forward contract
b) Futures contract
c) Currency option

Bandingkan kelebihan dan kekurangan masing-masing!

**JAWABAN:**

**a) FORWARD CONTRACT**

**Mekanisme:**
- Perusahaan masuk kontrak dengan bank untuk menjual USD 1 juta pada kurs tertentu 6 bulan ke depan
- Misal: forward rate = Rp 15.500/USD
- Kontrak OTC (over-the-counter), customized

**Contoh:**
```
Hari ini: Spot rate = Rp 15.800/USD
Forward rate 6 bulan = Rp 15.500/USD

6 bulan kemudian:
Scenario 1 - Spot = Rp 15.000/USD (rupiah menguat)
→ Tetap jual di Rp 15.500 → Untung dari hedging
→ Receive: 1.000.000 × 15.500 = Rp 15,5 miliar

Scenario 2 - Spot = Rp 16.000/USD (rupiah melemah)
→ Tetap jual di Rp 15.500 → Rugi opportunity
→ Receive: 1.000.000 × 15.500 = Rp 15,5 miliar
```

**Kelebihan:**
- Certainty: kepastian cash flow
- Tidak ada upfront cost
- Customizable (jumlah, tanggal)
- Perfect hedge

**Kekurangan:**
- Tidak bisa menikmati pergerakan kurs yang menguntungkan
- Counterparty risk (bank bisa default)
- Tidak liquid, sulit keluar dari kontrak
- Require credit line dengan bank

---

**b) FUTURES CONTRACT**

**Mekanisme:**
- Kontrak standar diperdagangkan di bursa
- Margin requirement
- Marked-to-market daily
- Settlement melalui clearinghouse

**Contoh:**
```
Kontrak: USD/IDR Futures di ICDX
Size: USD 10.000 per contract
Butuh: 1.000.000 / 10.000 = 100 contracts
Initial margin: misal 5% × Rp 15,5 miliar = Rp 775 juta
```

**Kelebihan:**
- Liquid, bisa keluar kapan saja
- Tidak ada counterparty risk (ada clearinghouse)
- Transparent pricing
- Lebih murah dari forward (spread lebih kecil)

**Kekurangan:**
- Standardized (tidak custom)
- Margin call risk
- Basis risk (tanggal kontrak vs kebutuhan aktual)
- Kompleksitas administrasi (daily settlement)

---

**c) CURRENCY PUT OPTION**

**Mekanisme:**
- Beli hak (bukan kewajiban) untuk jual USD di strike price tertentu
- Bayar premium di muka
- Bisa pilih untuk exercise atau tidak

**Contoh:**
```
Put option: Hak jual USD @ Rp 15.500
Premium: 2% × Rp 15,5 miliar = Rp 310 juta

6 bulan kemudian:
Scenario 1 - Spot = Rp 15.000/USD
→ Exercise option, jual di Rp 15.500
→ Receive: Rp 15,5 miliar - premium = Rp 15,19 miliar

Scenario 2 - Spot = Rp 16.000/USD  
→ Biarkan option expired
→ Jual di spot Rp 16.000
→ Receive: Rp 16 miliar - premium = Rp 15,69 miliar
```

**Kelebihan:**
- Flexible: protect downside, keep upside
- Bisa pilih untuk exercise atau tidak
- Cocok jika uncertain tentang timing cash flow
- Psychological comfort

**Kekurangan:**
- Mahal (harus bayar premium)
- Premium hangus jika tidak exercise
- Kompleks dalam pricing
- Require sophistication dalam strategi

---

**PERBANDINGAN LENGKAP:**

| Kriteria | Forward | Futures | Option |
|----------|---------|---------|---------|
| **Cost** | Gratis | Margin | Premium mahal |
| **Flexibility** | Rendah | Sedang | Tinggi |
| **Liquidity** | Rendah | Tinggi | Sedang |
| **Customization** | Tinggi | Rendah | Sedang |
| **Upside potential** | Hilang | Hilang | Tetap ada |
| **Complexity** | Sederhana | Sedang | Kompleks |
| **Best for** | Certain cash flow | Active trading | Uncertain timing |

---

**REKOMENDASI untuk PT Eksportir:**

**Gunakan FORWARD jika:**
- Cash flow pasti USD 1 juta, pasti 6 bulan
- Ingin certainty budget
- Tidak mau ribet administrasi
- Punya hubungan baik dengan bank

**Gunakan FUTURES jika:**
- Perlu flexibility keluar masuk
- Volume besar dan sering hedging
- Punya team treasury yang sophisticated

**Gunakan OPTION jika:**
- Ada kemungkinan pembayaran tidak jadi
- Ingin tetap bisa profit jika rupiah melemah
- Budget cukup untuk bayar premium
- Skala besar dan long-term relationship dengan client

**Kombinasi Strategi:**
Bisa juga kombinasi, misal:
- Forward 70% (core exposure)
- Option 30% (untuk flexibility)

---

### Soal 10
Jelaskan perbedaan antara hedging dan spekulasi dalam penggunaan derivatives. Berikan contoh kasus masing-masing dan analisis dampak pada risk profile perusahaan.

**JAWABAN:**

**DEFINISI:**

**Hedging:**
Penggunaan derivatives untuk mengurangi atau menghilangkan risiko yang sudah ada (existing exposure). Tujuan: proteksi, bukan profit.

**Spekulasi:**
Penggunaan derivatives untuk mengambil posisi risiko dengan harapan mendapat profit dari pergerakan harga. Tujuan: profit, bukan proteksi.

---

**CONTOH KASUS HEDGING:**

**PT Garuda Airline:**

**Existing Exposure:**
- Konsumsi 1 juta barrel avtur per tahun
- Harga avtur saat ini: USD 80/barrel
- Budget berdasarkan harga USD 80
- Khawatir harga naik → biaya operasional membengkak

**Strategi Hedging:**
```
Beli call option untuk 1 juta barrel
Strike price: USD 80
Premium: USD 3/barrel
Total premium: 1.000.000 × 3 = USD 3 juta
```

**Skenario 1: Harga naik ke USD 100**
```
Tanpa hedging:
Cost = 1.000.000 × 100 = USD 100 juta

Dengan hedging:
Exercise option, beli di USD 80
Cost = (1.000.000 × 80) + premium = USD 83 juta
Saving = USD 17 juta
```

**Skenario 2: Harga turun ke USD 60**
```
Tanpa hedging:
Cost = 1.000.000 × 60 = USD 60 juta

Dengan hedging:
Biarkan option expired, beli di spot
Cost = (1.000.000 × 60) + premium = USD 63 juta
Opportunity cost = USD 3 juta (premium)
```

**Risk Profile:**
- **Sebelum hedging:** Exposed ke volatilitas harga avtur
- **Setelah hedging:** Maximum cost terkunci (USD 83 juta), bisa lebih murah jika harga turun
- **Dampak:** Certainty dalam budgeting, stabilitas margin operasional

---

**CONTOH KASUS SPEKULASI:**

**PT Investama (Hedge Fund):**

**Tidak Ada Existing Exposure:**
- Tidak butuh avtur untuk operasional
- Melihat peluang harga avtur akan naik karena tension Timur Tengah

**Strategi Spekulasi:**
```
Beli futures contract avtur
Size: 1 juta barrel
Futures price: USD 80/barrel
Margin: 10% = USD 8 juta
```

**Skenario 1: Prediksi benar, harga naik ke USD 100**
```
Profit = (100 - 80) × 1.000.000 = USD 20 juta
ROI = 20 juta / 8 juta = 250%
```

**Skenario 2: Prediksi salah, harga turun ke USD 60**
```
Loss = (60 - 80) × 1.000.000 = USD -20 juta
ROI = -20 juta / 8 juta = -250%
Mungkin kena margin call
```

**Risk Profile:**
- **Sebelum spekulasi:** Zero exposure ke harga avtur
- **Setelah spekulasi:** Fully exposed ke volatilitas, leveraged position
- **Dampak:** High risk, high return; bisa untung besar atau rugi besar

---

**PERBEDAAN KARAKTERISTIK:**

| Aspek | Hedging | Spekulasi |
|-------|---------|-----------|
| **Posisi awal** | Ada exposure | Tidak ada exposure |
| **Tujuan** | Reduce risk | Increase risk (for return) |
| **Motivasi** | Proteksi | Profit |
| **Risk profile** | Menurun | Meningkat |
| **Leverage** | Minimal | Maksimal |
| **Holding period** | Match dengan exposure | Trading oriented |
| **Accounting** | Hedge accounting | Mark-to-market P&L |
| **Ethical view** | Conservative, prudent | Aggressive |

---

**CONTOH AMBIGUITAS (Gray Area):**

**PT Tambang Emas:**

**Situasi:**
- Produksi emas 10 ton/tahun
- Hedge 10 ton → **Pure hedging**
- Hedge 15 ton → **Over-hedging = partly speculation**
- Hedge 50 ton → **Pure speculation**

**Pertanyaan:**
Dimana batas antara prudent hedging dan reckless speculation?

**Jawaban:**
- Regulasi umumnya: hedging boleh max 100% of projected production/consumption
- Over-hedging 110-120% mungkin masih acceptable (buffer untuk uncertainty)
- Over-hedging >150% clearly speculation

---

**DAMPAK PADA RISK PROFILE PERUSAHAAN:**

**Hedging:**
```
Risk Profile:
Before: ═══════════ (High volatility)
After:  ═══         (Low volatility)
```
- Stabilitas cash flow ↑
- Certainty dalam planning ↑
- Volatility earnings ↓
- Cost of capital ↓ (lower risk)

**Spekulasi:**
```
Risk Profile:
Before: ═══         
After:  ═══════════════ (Very high volatility)
```
- Volatility earnings ↑↑
- Risk of financial distress ↑
- Stakeholder concern ↑
- Cost of capital ↑ (higher risk)

---

**KASUS NYATA:**

**Hedging Success: Southwest Airlines**
- Consistently hedge 70-85% fuel exposure
- Saved billions during oil spike 2008
- Competitive advantage vs competitors

**Speculation Disaster: Metallgesellschaft (1993)**
- Oil trading company
- Speculation di oil futures
- Loss: USD 1.3 miliar
- Near bankruptcy

**Speculation Disaster: Société Générale (2008)**
- Rogue trader Jérôme Kerviel
- Unauthorized speculation di index futures
- Loss: EUR 4.9 miliar
- Largest trading loss in history (at that time)

---

**KESIMPULAN:**

**Hedging:**
- Legitimate business practice
- Part of risk management
- Should be transparent and within policy limits
- Reduce total risk of the firm

**Spekulasi:**
- Controversial practice
- Often outside core business
- Can destroy shareholder value
- Increase total risk of the firm

**Best Practice:**
- Clear derivatives policy
- Board oversight
- Segregation of duties (trader vs risk management)
- Regular reporting and VaR monitoring
- Match derivatives with underlying exposure

---

## CHAPTER 29: MERGERS, ACQUISITIONS, AND DIVESTITURES (KONSEP)

### Soal 11
PT Alpha akan mengakuisisi PT Beta dengan data sebagai berikut:
- Nilai pasar PT Alpha = Rp 50 miliar (10 juta saham @ Rp 5.000/saham)
- Nilai pasar PT Beta = Rp 20 miliar (5 juta saham @ Rp 4.000/saham)
- Estimasi synergy dari merger = Rp 8 miliar
- PT Alpha menawarkan Rp 25 miliar cash untuk mengakuisisi PT Beta

Hitung:
a) Nilai gabungan perusahaan setelah merger (dengan synergy)
b) Gain dari merger
c) Berapa gain yang diperoleh pemegang saham PT Beta?
d) Berapa gain yang diperoleh pemegang saham PT Alpha?
e) NPV akuisisi bagi PT Alpha
f) Apakah akuisisi ini menguntungkan bagi PT Alpha?

**JAWABAN:**

**a) Nilai Gabungan dengan Synergy:**
```
V_AB = V_A + V_B + Synergy
V_AB = 50 miliar + 20 miliar + 8 miliar
V_AB = Rp 78 miliar
```

**b) Total Gain dari Merger:**
```
Gain = Synergy = Rp 8 miliar
```
Ini adalah total value created dari merger.

**c) Gain Pemegang Saham PT Beta:**
```
Harga akuisisi = Rp 25 miliar
Nilai pasar Beta sebelum akuisisi = Rp 20 miliar
Gain Beta = 25 miliar - 20 miliar = Rp 5 miliar

Premium yang dibayar = (25 - 20) / 20 × 100% = 25%
```

Pemegang saham Beta mendapat **Rp 5 miliar gain** (62,5% dari total synergy).

**d) Gain Pemegang Saham PT Alpha:**
```
Total gain merger = Rp 8 miliar
Gain untuk Beta = Rp 5 miliar
Gain untuk Alpha = 8 miliar - 5 miliar = Rp 3 miliar
```

Alternatif perhitungan:
```
Nilai Alpha setelah akuisisi:
= Nilai gabungan - Cash yang dibayar
= 78 miliar - 25 miliar = Rp 53 miliar

Nilai Alpha sebelumnya = Rp 50 miliar
Gain Alpha = 53 miliar - 50 miliar = Rp 3 miliar
```

Pemegang saham Alpha mendapat **Rp 3 miliar gain** (37,5% dari total synergy).

**e) NPV Akuisisi bagi PT Alpha:**
```
NPV = Gain Alpha - Cost
Di mana Cost = Premium yang dibayar
Cost = 25 miliar - 20 miliar = Rp 5 miliar

Cara 1:
NPV = 3 miliar (gain Alpha sudah net of cost)

Cara 2:
NPV = Synergy - Premium
NPV = 8 miliar - 5 miliar = Rp 3 miliar
```

**NPV = Rp 3 miliar**

**f) Keputusan:**
**YA, menguntungkan bagi PT Alpha**

Alasan:
- NPV positif (Rp 3 miliar)
- Walaupun Alpha harus membayar premium 25%, masih tersisa gain Rp 3 miliar
- Alpha capture 37,5% dari synergy
- Nilai per saham Alpha meningkat:
  ```
  Nilai per saham setelah = 53 miliar / 10 juta = Rp 5.300
  Kenaikan = 5.300 - 5.000 = Rp 300 per saham (+6%)
  ```

---

**DISTRIBUSI GAIN:**

```
Total Synergy: Rp 8 miliar (100%)
├─ Gain Beta: Rp 5 miliar (62,5%)
└─ Gain Alpha: Rp 3 miliar (37,5%)
```

**Interpretasi:**
- **Beta shareholders:** Sangat untung, dapat premium 25%
- **Alpha shareholders:** Cukup untung, dapat Rp 3 miliar
- **Distribution:** Beta dapat porsi lebih besar dari synergy karena posisi tawar mereka (Alpha perlu bayar premium untuk "membeli" persetujuan)

---

**ANALISIS SENSITIVITAS:**

**Jika premium lebih tinggi:**
```
Premium 30%:
Harga akuisisi = 20 miliar × 1,30 = Rp 26 miliar
NPV = 8 miliar - 6 miliar = Rp 2 miliar → Masih OK

Premium 40%:
Harga akuisisi = 20 miliar × 1,40 = Rp 28 miliar
NPV = 8 miliar - 8 miliar = Rp 0 → Break-even

Premium 50%:
Harga akuisisi = 20 miliar × 1,50 = Rp 30 miliar
NPV = 8 miliar - 10 miliar = -Rp 2 miliar → TOLAK!
```

**Break-even premium:**
```
Synergy = Premium
8 miliar = Harga - 20 miliar
Harga = 28 miliar
Premium = 8/20 = 40%
```

**Maximum premium yang boleh dibayar = 40%**

---

**KRITERIA AKUISISI YANG BAIK:**

✅ **Good Acquisition (contoh kasus ini):**
- NPV > 0
- Synergy realistis dan achievable
- Alpha dapat fair share dari synergy
- Win-win solution

❌ **Bad Acquisition:**
- NPV < 0 (overpay)
- Synergy overestimated atau tidak realistis
- Hanya Beta yang untung, Alpha rugi (winner's curse)

---

### Soal 12
Jelaskan perbedaan antara Horizontal Merger, Vertical Merger, dan Conglomerate Merger. Berikan contoh nyata dan analisis dari sisi:
a) Motivasi merger
b) Potensi synergy
c) Risiko regulasi/antitrust

**JAWABAN:**

---

**1. HORIZONTAL MERGER**

**Definisi:**
Merger antara dua perusahaan yang beroperasi di industri yang sama dan pada level value chain yang sama (kompetitor).

**Contoh Nyata:**
- **Disney + 21st Century Fox (2019)**: USD 71 miliar
  - Kedua perusahaan di industri entertainment/media
  - Disney dapat content library Fox (X-Men, Avatar, The Simpsons)
  
- **Exxon + Mobil (1999)**: USD 81 miliar
  - Dua perusahaan minyak terbesar bergabung
  - Menjadi ExxonMobil

- **Facebook + Instagram (2012)**: USD 1 miliar
  - Dua platform social media

**a) Motivasi:**
1. **Economies of scale**
   - Fixed cost spread across larger output
   - Contoh: Disney + Fox share studio facilities, distribution channels

2. **Market power**
   - Increase market share
   - Reduce competition
   - Pricing power meningkat

3. **Eliminate redundancy**
   - Close overlapping offices/stores
   - Merge IT systems
   - Consolidate functions (HR, finance, legal)

4. **Capacity management**
   - Remove excess capacity in declining industry

**b) Potensi Synergy:**

**Cost Synergy (lebih dominan):**
```
Contoh ExxonMobil:
- Eliminate duplicate gas stations in same area
- Consolidate refineries
- Merge exploration teams
- Shared R&D
Target cost saving: USD 2.8 miliar/tahun
```

**Revenue Synergy:**
```
Contoh Disney + Fox:
- Larger content library → Stronger Disney+
- Cross-selling opportunities
- Bundle pricing power
```

**Magnitude:** Biasanya 5-20% dari combined revenue

**c) Risiko Regulasi:**

**SANGAT TINGGI ❗❗❗**

Alasan:
- Reduce competition
- Increase market concentration
- Potential monopoly power
- Consumer harm (higher prices, less choice)

**Contoh Kasus Ditolak:**
- **AT&T + T-Mobile (2011)**: Ditolak oleh FCC
  - Too much concentration di pasar US telecom
  
- **Halliburton + Baker Hughes (2016)**: Dibatalkan
  - 90% pasar oilfield services

**Approval Conditions:**
- Divest certain assets
- Keep brands separate
- Price caps
- Behavioral remedies

**Regulator Focus:**
- HHI (Herfindahl-Hirschman Index)
- Market share > 30-40% → red flag
- Impact on consumer welfare

---

**2. VERTICAL MERGER**

**Definisi:**
Merger antara perusahaan di different stages of value chain dalam industri yang sama (buyer-supplier).

**Contoh Nyata:**
- **Amazon + Whole Foods (2017)**: USD 13.7 miliar
  - Amazon (retail/tech) + Whole Foods (grocery)
  - Forward integration
  
- **AT&T + Time Warner (2018)**: USD 85 miliar
  - AT&T (distributor) + Time Warner (content creator)
  - Backward integration

- **Tesla + Battery Manufacturing**
  - Car maker integrate ke battery production

**a) Motivasi:**

1. **Secure supply chain**
   - Guaranteed supply of critical inputs
   - Avoid supply disruptions
   - Contoh: Tesla need stable lithium battery supply

2. **Reduce transaction costs**
   - No negotiation costs
   - No contracting costs
   - Faster decision making

3. **Improve coordination**
   - Better quality control
   - Faster time-to-market
   - Proprietary technology protection

4. **Capture margin**
   - Internalize supplier profit or distributor margin
   - Contoh: Amazon cut out middlemen in grocery

**b) Potensi Synergy:**

**Operational Synergy:**
```
Contoh AT&T + Time Warner:
- AT&T dapat distribute Time Warner content directly
- No need pay licensing to third party
- Proprietary content for AT&T customers
- Better data integration (viewing behavior)
```

**Strategic Synergy:**
```
Contoh Amazon + Whole Foods:
- Amazon dapat test drone delivery di Whole Foods
- Whole Foods products di Amazon Prime
- Amazon tech (cashierless) di Whole Foods stores
- Data on grocery shopping habits
```

**Magnitude:** Biasanya 3-15% dari combined revenue (lebih kecil dari horizontal)

**c) Risiko Regulasi:**

**SEDANG ⚠️**

Alasan:
- Tidak langsung menghilangkan kompetitor
- Tapi bisa vertical foreclosure

**Concern:**
1. **Input foreclosure**
   - Supplier refuse sell to competitors
   - Contoh: Time Warner bisa refuse content ke Comcast

2. **Customer foreclosure**
   - Distributor refuse buy from rival suppliers
   - Contoh: AT&T only show Time Warner content

**Contoh Almost Ditolak:**
- AT&T + Time Warner: Sempat digugat DOJ tapi akhirnya disetujui dengan kondisi

**Approval lebih mudah jika:**
- Commit to non-discrimination
- Licensing agreement tetap honor
- No price increase

---

**3. CONGLOMERATE MERGER**

**Definisi:**
Merger antara perusahaan di industri yang completely unrelated.

**Contoh Nyata:**
- **Berkshire Hathaway Portfolio**:
  - Insurance (GEICO) + Railroad (BNSF) + Utilities + Coca-Cola + Apple stock + dll
  
- **Samsung Group**:
  - Electronics + Construction + Shipbuilding + Insurance + Hotels

- **GE (dulu)**:
  - Aviation + Healthcare + Power + Financial Services + Appliances

**a) Motivasi:**

1. **Diversification**
   - Reduce business risk
   - Smooth earnings volatility
   - Contoh: Recession hit insurance, tapi railroad masih OK

2. **Internal capital market**
   - Efficient capital allocation across divisions
   - Funding growth division dengan cash dari mature division

3. **Tax benefits**
   - Loss di satu unit offset profit di unit lain
   - Transfer pricing opportunities

4. **Empire building**
   - CEO ego dan size (tidak value-creating)

**b) Potensi Synergy:**

**MINIMAL atau TIDAK ADA ❌**

Alasan:
- No operational overlap
- No supply chain integration
- No technology sharing
- Different core competencies

**Possible Financial Synergy:**
```
- Lower cost of capital (if well-diversified)
- Tax shields
- Debt capacity increase (coinsurance effect)
```

**BUT:**
- Shareholders bisa diversify sendiri (lebih murah)
- Conglomerate discount: trading below sum-of-parts value

**c) Risiko Regulasi:**

**RENDAH ✅**

Alasan:
- Tidak mengurangi competition di manapun
- No antitrust concern
- No vertical foreclosure

**Hampir selalu disetujui**

**Tapi ada risiko lain:**
- **Too big to fail**: Jika terlalu besar, systemic risk
- **Too complex to manage**: Value destruction

---

**PERBANDINGAN RINGKAS:**

| Aspek | Horizontal | Vertical | Conglomerate |
|-------|-----------|----------|--------------|
| **Relationship** | Competitors | Buyer-Supplier | Unrelated |
| **Synergy** | 🔥🔥🔥 Very High | 🔥🔥 High | 🔥 Very Low |
| **Type** | Cost + Revenue | Operational | Financial only |
| **Antitrust** | 🚨 Very High Risk | ⚠️ Medium Risk | ✅ Low Risk |
| **Integration** | Difficult (culture) | Complex (system) | Easy (separate) |
| **Trend** | Popular 1990s-now | Popular 2010s | Declining (1960s peak) |

---

**EVOLUSI TREND:**

**1960s:** Conglomerate era
- "Diversification is king"
- ITT, Gulf+Western, Textron

**1980s-90s:** Horizontal consolidation
- Break up conglomerates
- Focus on core business
- "Do what you do best"

**2000s-2010s:** Vertical integration comeback
- Control full value chain
- Technology enable coordination
- Amazon model

**2020s:** Tech ecosystem building
- Mix of horizontal + vertical
- Platform approach
- Apple, Google, Meta

---

**KESIMPULAN:**

✅ **Horizontal:** Highest synergy, highest regulatory risk
✅ **Vertical:** Medium synergy, medium regulatory risk, strategic importance
❌ **Conglomerate:** Lowest synergy, lowest regulatory risk, declining trend

**Best Practice:**
- Horizontal: Prepare strong antitrust defense, show consumer benefits
- Vertical: Demonstrate no foreclosure intent
- Conglomerate: Need very strong strategic rationale (otherwise "conglomerate discount")

---

## CHAPTER 30: FINANCIAL DISTRESS (KONSEP)

### Soal 13
Jelaskan perbedaan antara:
a) Technical Insolvency vs Bankruptcy
b) Chapter 7 (Liquidation) vs Chapter 11 (Reorganization) 
c) Private Workout vs Formal Bankruptcy

Dalam situasi apa perusahaan sebaiknya memilih masing-masing opsi?

**JAWABAN:**

---

**a) TECHNICAL INSOLVENCY vs BANKRUPTCY**

**TECHNICAL INSOLVENCY (Liquidity Crisis)**

**Definisi:**
Perusahaan tidak mampu membayar kewajiban jangka pendek yang jatuh tempo, meskipun total aset masih lebih besar dari total liabilities.

**Kondisi:**
```
Current Assets < Current Liabilities
ATAU
Cash tidak cukup untuk bayar bunga/principal yang jatuh tempo

TAPI:
Total Assets > Total Liabilities (masih solvent di neraca)
```

**Contoh:**
```
PT Sementara Kesulitan:
Total Assets = Rp 100 miliar
Total Liabilities = Rp 70 miliar
Equity = Rp 30 miliar (positif!) ✅

TAPI:
Cash = Rp 5 miliar
Current Liabilities (jatuh tempo bulan ini) = Rp 20 miliar
→ Short Rp 15 miliar → Technical Insolvency
```

**Karakteristik:**
- Temporary problem
- Assets masih berharga
- Business model masih viable
- Hanya perlu waktu untuk convert assets to cash

**Solusi:**
- Short-term loan
- Sell assets (quick sale)
- Renegotiate payment terms
- Factoring receivables

---

**BANKRUPTCY (Accounting Insolvency)**

**Definisi:**
Total nilai aset lebih kecil dari total liabilities. Equity negatif. Perusahaan benar-benar insolvent.

**Kondisi:**
```
Total Assets < Total Liabilities
Equity < 0 (negatif)
```

**Contoh:**
```
PT Benar-Benar Bangkrut:
Total Assets = Rp 70 miliar
Total Liabilities = Rp 100 miliar
Equity = -Rp 30 miliar (negatif!) ❌

→ True Bankruptcy / Economic Insolvency
```

**Karakteristik:**
- Structural problem
- Value destruction has occurred
- Business model might be broken
- Permanent impairment

**Solusi:**
- Formal bankruptcy filing
- Debt restructuring (haircut)
- Equity infusion
- Asset sales
- Liquidation

---

**PERBEDAAN KUNCI:**

| Aspek | Technical Insolvency | Bankruptcy |
|-------|---------------------|------------|
| **Balance Sheet** | Healthy (equity > 0) | Broken (equity < 0) |
| **Problem** | Liquidity (timing) | Solvency (value) |
| **Seriousness** | Temporary | Structural |
| **Solution** | Cash injection, sell assets | Debt forgiveness, restructure |
| **Analogy** | Flu (recoverable) | Cancer (serious) |
| **Legal status** | Can avoid bankruptcy | Likely bankruptcy |

---

**Scenario Combinations:**

1. **Technically Insolvent tapi NOT Bankrupt** (common)
   - Real estate company dengan property bernilai tinggi
   - Tapi slow to sell, cash flow negatif
   - Solution: Bridge loan

2. **Technically Solvent tapi WILL BECOME Bankrupt**
   - Declining industry, bleeding cash
   - Assets losing value quickly
   - Hanya matter of time

3. **Both Technically Insolvent DAN Bankrupt** (worst case)
   - No cash, negative equity
   - Must file bankruptcy immediately

---

**b) CHAPTER 7 (LIQUIDATION) vs CHAPTER 11 (REORGANIZATION)**

**CHAPTER 7 - LIQUIDATION**

**Konsep:**
"Tutup pintu, jual semua, bayar kreditor, game over."

**Proses:**
1. Court appoint **Trustee**
2. Trustee takes control of company
3. **Liquidate semua aset** (auction, fire sale)
4. Distribute proceeds to creditors sesuai **Absolute Priority Rule**:
   ```
   1. Secured creditors
   2. Administrative expenses
   3. Unsecured creditors
   4. Subordinated debt
   5. Preferred stock
   6. Common stock (biasanya dapat $0)
   ```
5. Company **ceased to exist**

**Contoh:**
```
PT Tutup:
Asset liquidation value = Rp 60 miliar
Liabilities:
- Secured debt = Rp 40 miliar
- Unsecured debt = Rp 30 miliar
- Equity = ?

Distribution:
- Secured creditors: Rp 40 miliar (100% recovery) ✅
- Unsecured creditors: Rp 20 miliar (67% recovery) ⚠️
- Equity holders: Rp 0 (0% recovery) ❌
```

**Kapan Digunakan:**
✅ Business not viable (declining, obsolete)
✅ Going concern value < Liquidation value
✅ No reasonable restructuring plan
✅ Creditors prefer cash now than wait

**Contoh Real:**
- **Toys "R" Us (2018)**: E-commerce killed the business
- **Borders Books (2011)**: Amazon disruption
- **Blockbuster (2010)**: Netflix disruption

---

**CHAPTER 11 - REORGANIZATION**

**Konsep:**
"Perusahaan masih viable, restruktur debt, continue operations."

**Proses:**
1. Company files Chapter 11
2. **Automatic stay**: Creditors tidak bisa tagih
3. Company tetap operate (Debtor in Possession - DIP)
4. Company propose **Reorganization Plan**:
   - Debt haircut (reduction)
   - Debt-to-equity swap
   - Extended maturity
   - Lower interest rate
5. Creditors vote on plan
6. Court approve jika fair
7. **Company emerge** dari bankruptcy sebagai going concern

**Contoh:**
```
PT Restruktur:
Going concern value = Rp 100 miliar
Liquidation value = Rp 60 miliar
Liabilities:
- Secured debt = Rp 40 miliar
- Unsecured debt = Rp 60 miliar
Total debt = Rp 100 miliar

Reorganization Plan:
- Secured debt: Tetap Rp 40 miliar
- Unsecured debt: 
  → Rp 30 miliar cash (50% haircut)
  → Rp 30 miliar convert to equity (debt-to-equity swap)
- Old equity: Diluted 70%

Result:
- Company survive ✅
- Debt reduced to Rp 70 miliar
- Unsecured creditors become shareholders
```

**Kapan Digunakan:**
✅ Business fundamentally viable
✅ Going concern value > Liquidation value
✅ Temporary financial distress (not business model failure)
✅ Restructuring can restore profitability
✅ Stakeholders prefer long-term value

**Contoh Real:**
- **General Motors (2009)**: Successfully emerged, government bailout
- **American Airlines (2011-2013)**: Merged with US Airways
- **Hertz (2020)**: COVID-19 impact, emerged 2021
- **PG&E (2019)**: California wildfire liabilities

---

**PERBANDINGAN:**

| Aspek | Chapter 7 | Chapter 11 |
|-------|-----------|------------|
| **Outcome** | Death | Rebirth |
| **Operations** | Stop | Continue |
| **Assets** | Sold | Retained |
| **Employees** | Fired | Mostly retained |
| **Management** | Replaced by Trustee | Often stay (DIP) |
| **Timeline** | Fast (months) | Slow (years) |
| **Cost** | Lower | Very high (legal, advisory) |
| **Creditor recovery** | Lower | Potentially higher |
| **Viability** | Not viable | Viable with restructure |

---

**FAKTOR KEPUTUSAN:**

```
Going Concern Value > Liquidation Value?
    |
    Yes → Chapter 11
    No → Chapter 7

Contoh:
Tech company: 
- Going concern = $100M (IP, talent, customers)
- Liquidation = $20M (used laptops, furniture)
→ Chapter 11!

Real estate company:
- Going concern = $50M (distressed, no tenants)
- Liquidation = $60M (sell buildings)
→ Chapter 7!
```

---

**c) PRIVATE WORKOUT vs FORMAL BANKRUPTCY**

**PRIVATE WORKOUT (Out-of-Court Restructuring)**

**Definisi:**
Negosiasi langsung antara perusahaan dan kreditor untuk restruktur debt tanpa melalui pengadilan.

**Proses:**
1. Company hire restructuring advisor
2. Approach major creditors informally
3. Propose restructuring terms
4. Negotiate one-on-one
5. Reach agreement
6. Execute new debt agreement
7. **No court involvement**

**Contoh Struktur:**
```
Pre-Workout:
Debt = Rp 100 miliar, interest 15%, maturity 2025

Post-Workout Agreement:
Debt = Rp 80 miliar (20% forgiveness)
Interest = 10% (reduced)
Maturity = 2030 (extended)
Plus: Equity kicker (warrant) untuk creditors
```

**Kelebihan:**
✅ **Faster**: Months vs years
✅ **Cheaper**: No court fees, lower legal costs
✅ **Private**: No public disclosure, protect reputation
✅ **Flexible**: Customized solution
✅ **Less disruptive**: Business continues normally
✅ **Preserve relationships**: Less adversarial

**Kekurangan:**
❌ **Holdout problem**: One creditor can block entire deal
❌ **No automatic stay**: Creditors can still sue
❌ **Limited enforceability**: Dissenting creditors not bound
❌ **No cramdown**: Can't force recalcitrant creditors
❌ **Requires cooperation**: All parties must agree

**Kapan Berhasil:**
✅ Few creditors (simple structure)
✅ Relationship-based lending (banks yang sudah kenal)
✅ Moderate distress (not too deep)
✅ Creditors rational and cooperative
✅ Viable business with clear path to recovery

**Contoh Real:**
- **Many private companies**: Never disclosed
- **Friendly bank workout**: Very common
- **Asian crisis (1997)**: Many Indonesian companies

---

**FORMAL BANKRUPTCY (Court-Supervised)**

**Definisi:**
Restructuring melalui pengadilan sesuai Bankruptcy Code (Chapter 11).

**Proses:**
- (Sudah dijelaskan di bagian Chapter 11)

**Kelebihan:**
✅ **Automatic stay**: Creditors must stop collection
✅ **Cramdown power**: Force dissenters to accept plan (if meets criteria)
✅ **Binding**: All creditors bound by confirmed plan
✅ **DIP financing**: Priority financing available
✅ **Reject contracts**: Can terminate unfavorable contracts
✅ **Solve coordination problem**: One framework for all creditors

**Kekurangan:**
❌ **Expensive**: Legal fees bisa puluhan miliar
❌ **Slow**: 1-3 tahun typical
❌ **Public**: All filings public record
❌ **Stigma**: Reputation damage
❌ **Disruptive**: Customers/suppliers may flee
❌ **Management distraction**: CEO spends time in court, not running business
❌ **Risk of liquidation**: Bisa berakhir di Chapter 7

**Kapan Necessary:**
✅ Complex capital structure (banyak kreditor)
✅ Bondholders (public debt) involved
✅ Uncooperative creditors
✅ Need cramdown power
✅ Severe distress
✅ Need to reject contracts/leases

**Contoh Real:**
- (Sama dengan contoh Chapter 11 di atas)

---

**DECISION TREE:**

```
Financial Distress
    |
    ├─ Simple structure + Cooperative creditors → Private Workout
    |
    ├─ Complex structure OR Uncooperative creditors → Formal Bankruptcy
    |
    └─ Private Workout gagal → Pivot to Formal Bankruptcy
```

**Statistic:**
- ~60% private workout attempts succeed
- ~40% eventually file bankruptcy
- Median cost: Private workout $2M vs Bankruptcy $20M

---

**CASE STUDY: PROGRESSION**

**PT Contoh Distress:**

**Stage 1: Technical Insolvency**
```
Month 1-3:
- Missed interest payment
- Try private workout
- Negotiate with 3 banks
- Agreement: extend maturity
→ Success! ✅
```

**Stage 2: Private Workout Fails**
```
Month 4-6:
- Business deteriorates further
- Bondholders (1000s of them) refuse to cooperate
- Holdout problem
→ Must file Chapter 11
```

**Stage 3: Chapter 11**
```
Month 7-18:
- File Chapter 11
- Automatic stay
- Propose reorganization plan
- Debt-to-equity swap
- Emerge as new company
→ Success! ✅
```

**Alternative Bad Ending:**
```
Month 19:
- Reorganization plan rejected
- Business continues to decline
- Convert to Chapter 7
- Liquidation
→ Game over ❌
```

---

**INDONESIA CONTEXT (PKPU):**

Indonesia menggunakan sistem berbeda:
- **PKPU** (Penundaan Kewajiban Pembayaran Utang) ≈ Chapter 11
- **Kepailitan/Pailit** ≈ Chapter 7

**Perbedaan:**
- PKPU lebih creditor-friendly
- Automatic stay lebih lemah
- Reorganization jarang berhasil (banyak berakhir pailit)

**Contoh:**
- **Sariwangi (2006)**: PKPU, akhirnya dijual
- **Nyonya Meneer (2017)**: Pailit, likuidasi

---

**KESIMPULAN:**

**Best Strategy:**
1. **Prevent** technical insolvency (cash management)
2. If distress inevitable → Try **private workout** first
3. If workout fails → File **Chapter 11** quickly (don't wait until Chapter 7 inevitable)
4. **Chapter 7** only if truly no hope

**Red Flag for Equity Holders:**
- Technical insolvency → Concerned 😟
- Private workout → Very concerned 😰
- Chapter 11 → Probably wiped out 💀
- Chapter 7 → Definitely wiped out ⚰️

---

### Soal 14
Jelaskan konsep "Agency Costs of Financial Distress" dan berikan 3 contoh konkret bagaimana konflik kepentingan antara shareholders dan bondholders dapat menghancurkan nilai perusahaan yang mengalami financial distress.

**JAWABAN:**

---

**KONSEP AGENCY COSTS OF FINANCIAL DISTRESS**

**Definisi:**
Biaya yang timbul akibat konflik kepentingan antara shareholders (equity holders) dan bondholders (debt holders) ketika perusahaan mengalami financial distress. Konflik ini menyebabkan keputusan yang suboptimal dan menghancurkan total nilai perusahaan.

**Situasi:**
Ketika perusahaan near bankruptcy, shareholders dan bondholders memiliki insentif yang bertolak belakang karena mereka berbeda posisi dalam capital structure priority.

---

**CONTOH 1: RISK SHIFTING (Asset Substitution Problem)**

**Scenario:**

```
PT Dalam Kesulitan:
Debt = Rp 100 miliar (jatuh tempo 1 tahun)
Asset value sekarang = Rp 90 miliar
Equity value = Rp 0 (out of the money)

Ada 2 proyek investasi:
```

**Proyek A - Conservative (NPV positif):**
```
Investment = Rp 10 miliar
Outcome (certain):
Success: Firm value = Rp 110 miliar

NPV = 110 - 90 - 10 = Rp 10 miliar ✅

Payoff:
- Bondholders: Rp 100 miliar (fully repaid)
- Shareholders: Rp 10 miliar
```

**Proyek B - Gamble (NPV negatif):**
```
Investment = Rp 10 miliar
Outcome (50-50):
Success (50%): Firm value = Rp 200 miliar
Failure (50%): Firm value = Rp 20 miliar

Expected value = 0,5(200) + 0,5(20) = Rp 110 miliar
NPV = 110 - 90 - 10 = Rp 10 miliar

Tapi lihat distribusinya:

If Success:
- Bondholders: Rp 100 miliar
- Shareholders: Rp 100 miliar 🤑

If Failure:
- Bondholders: Rp 20 miliar (loss Rp 80 miliar!)
- Shareholders: Rp 0 (can't lose more!)

Expected Payoff Shareholders = 0,5(100) + 0,5(0) = Rp 50 miliar
```

**Keputusan Shareholders:**
- Pilih Proyek B! (Expected payoff Rp 50 miliar vs Rp 10 miliar)
- Walaupun NPV sama, distribusi payoff lebih favorable

**Keputusan Bondholders:**
- Prefer Proyek A! (Certain Rp 100 miliar vs Expected Rp 60 miliar)

**HASIL:**
- Shareholders pilih Proyek B (risk shifting!)
- **"Heads I win big, tails you (bondholders) lose big"**
- **Bondholders bear downside risk, shareholders capture upside**
- Total firm value bisa destroyed jika Proyek B lebih risky

**Dalam Kenyataan:**
- Manager (act for shareholders) ambil excessive risk
- "Double or nothing" strategy
- Pursue long-shot projects
- Enter new risky businesses

**Value Destruction:**
```
Optimal choice = Proyek A (safe)
Actual choice = Proyek B (gamble)
Hasil Failure → Firm value = 20 (vs 110)
Loss = Rp 90 miliar ❌
```

---

**CONTOH 2: UNDERINVESTMENT PROBLEM (Debt Overhang)**

**Scenario:**

```
PT Terlalu Banyak Hutang:
Existing debt = Rp 150 miliar (jatuh tempo 2 tahun)
Current firm value = Rp 100 miliar
Equity value = Rp 0 (deeply underwater)

Muncul proyek baru dengan NPV positif:
```

**Proyek Baru:**
```
Investment required = Rp 20 miliar (dari shareholders)
PV of project = Rp 50 miliar
NPV = 50 - 20 = Rp 30 miliar ✅ (value-creating!)

Firm value after project = 100 + 50 = Rp 150 miliar
```

**Distribusi Payoff:**

**Jika Shareholders Invest Rp 20 miliar:**
```
Firm value = Rp 150 miliar
Debt = Rp 150 miliar

Payoff:
- Bondholders: Rp 150 miliar (naik dari Rp 100 miliar) 🎉
- Shareholders: Rp 0 (masih underwater)

Net untuk Shareholders:
Pay Rp 20 miliar → Get Rp 0
Loss = -Rp 20 miliar ❌
```

**Jika Shareholders TIDAK Invest:**
```
Firm value = Rp 100 miliar
Bondholders: Rp 100 miliar
Shareholders: Rp 0

Net untuk Shareholders: Rp 0 (better than -20!)
```

**KEPUTUSAN:**
- **Shareholders TOLAK proyek (walaupun NPV positif!)**
- All benefit goes to bondholders
- Shareholders subsidize bondholders
- **Rational untuk shareholders, tapi destroys firm value**

**Value Destruction:**
```
Foregone NPV = Rp 30 miliar
Perusahaan lewatkan growth opportunity
Competitive position memburuk
Eventually bangkrut
```

**Dalam Kenyataan:**
- Reject profitable projects
- Underinvest in R&D
- Cut marketing budget
- Defer maintenance
- "Milk the firm" strategy

**Ironi:**
- Proyek bagus ditolak bukan karena tidak profitable
- Ditolak karena distribusi payoff tidak adil
- **"I'm not investing to save your (bondholders) money"**

---

**CONTOH 3: MILKING THE PROPERTY (Asset Stripping)**

**Scenario:**

```
PT Hampir Bangkrut:
Firm value = Rp 80 miliar (assets bisa dijual)
Debt = Rp 100 miliar (jatuh tempo 6 bulan)
Equity = Rp 0

Shareholders tahu firm akan bankrupt, bondholders akan take over.
```

**Strategi "Milking":**

**Action 1: Extraordinary Dividend**
```
Jual beberapa asset seharga Rp 30 miliar (fire sale, below value)
Distribute sebagai dividend ke shareholders
Firm value turun jadi Rp 50 miliar

Result:
- Shareholders: Dapat Rp 30 miliar cash 🤑
- Bondholders: Recovery turun dari 80 ke 50 (loss Rp 30 miliar) 😡
```

**Action 2: Strip Valuable Assets**
```
Transfer intellectual property to new company (owned by same shareholders)
Charge minimal price (sweetheart deal)
Old company (dengan bondholders) jadi shell

Result:
- Shareholders: Asset valuable di new company
- Bondholders: Stuck di old company yang jadi worthless
```

**Action 3: Related-Party Transactions**
```
Sell inventory to related party at below-market price
Overpay for "consulting services" from related party
Pay excessive management bonuses
Lease equipment from related party at above-market price

Result:
- Cash keluar dari firm
- Masuk ke pockets of shareholders/management
- Bondholders get empty shell
```

**Value Destruction:**
```
Potential recovery untuk bondholders = Rp 80 miliar
After milking = Rp 50 miliar atau kurang
Wealth transfer = Rp 30+ miliar dari bondholders ke shareholders
Plus: Destroy going concern value
Total value loss bisa > Rp 50 miliar
```

**Dalam Kenyataan:**
- Pay large dividends right before bankruptcy
- Related-party transactions
- Sale-leaseback at unfavorable terms
- "Loot the company"

**Famous Cases:**
- **Enron**: Asset transfers, SPV shenanigans
- **Parmalat**: Siphon billions to family companies
- **Many Indonesian conglomerates (1998)**: Strip valuable assets before default

---

**SUMMARY: AGENCY COSTS OF FINANCIAL DISTRESS**

| Problem | Shareholder Behavior | Bondholder Impact | Value Destroyed |
|---------|---------------------|-------------------|-----------------|
| **Risk Shifting** | Take excessive risk | Bear downside risk | Failed risky projects |
| **Underinvestment** | Reject good projects | Lose growth value | Foregone NPV |
| **Asset Stripping** | Extract cash/assets | Recovery reduced | Going concern value |

---

**TOTAL COST OF FINANCIAL DISTRESS:**

```
Direct Costs:
+ Legal fees (lawyers, consultants)
+ Court costs
+ Advisory fees (investment banker, accountants)
+ Management time

Indirect Costs (AGENCY COSTS):
+ Lost sales (customers flee)
+ Higher supplier costs (demand cash on delivery)
+ Employee turnover (talent leaves)
+ Underinvestment
+ Asset substitution
+ Asset stripping
+ Fire sales of assets
= VERY LARGE (often 10-20% of firm value)
```

---

**SOLUTIONS TO AGENCY COSTS:**

**1. Protective Covenants in Bond Contract:**
```
- Limitation on dividends
- Limitation on asset sales
- Limitation on additional debt
- Maintenance of working capital
- Restriction on mergers
- Positive covenants (must maintain insurance, etc.)
```

**2. Convertible Bonds:**
```
- Bondholders dapat participate dalam upside
- Align interests
```

**3. Secured Debt:**
```
- Collateral mengurangi asset stripping
- Bondholders have first claim on specific assets
```

**4. Short Maturity:**
```
- Monitor more frequently
- Less time untuk mischief
```

**5. Reputation Concerns:**
```
- Repeat player management care about reputation
- Future financing will be harder/expensive
```

**6. Shareholder Inject Equity Early:**
```
- Dilute debt overhang
- Restore positive equity value
- Realign incentives
```

---

**IMPLICATIONS FOR CAPITAL STRUCTURE:**

**Pecking Order dengan Financial Distress:**
```
Optimal Debt Level:
= Tax benefit of debt
- Expected cost of financial distress (direct + agency)

Too much debt → High probability distress → High agency costs
→ Destroy more value than tax savings
→ Optimal to have LESS debt
```

**Firms with High Agency Costs Should:**
- Use less debt
- Use more equity
- Use secured debt (if use debt)
- Have strong governance
- Maintain financial flexibility

**Examples:**
- **Tech companies:** Low debt (high growth options, high underinvestment risk)
- **Utilities:** High debt (stable cash flow, low risk shifting opportunity)

---

**KESIMPULAN:**

**Agency costs of financial distress are REAL and LARGE:**
1. Destroy firm value through suboptimal decisions
2. Transfer wealth from bondholders to shareholders (zero-sum)
3. Make everyone worse off in aggregate (negative-sum)
4. Can be prevented with proper contracting and governance

**Key Insight:**
> "Financial distress doesn't just reduce value because of direct bankruptcy costs. The conflict between shareholders and bondholders leads to value-destroying decisions that compound the problem."

**Philosophical Question:**
- If going bankrupt is certain, is it rational untuk shareholders to "milk" the company?
- Legally: Gray area (fiduciary duty to corporation, not bondholders)
- Ethically: Questionable
- Economically: Destroys total surplus

**Role of Law:**
- Bankruptcy code tries to prevent this
- Automatic stay
- Fraudulent conveyance rules
- Preferences (certain transactions void)
- Equitable subordination

---

## CHAPTER 31: INTERNATIONAL CORPORATE FINANCE (Materi Terbuka)

**Catatan:** Bab ini tidak ada jenis soal spesifik (konsep atau hitungan), jadi saya akan berikan overview dan soal campuran yang mungkin muncul.

### Soal 15
Jelaskan bagaimana perusahaan multinasional dapat terekspos pada 3 jenis foreign exchange risk:
a) Transaction exposure
b) Translation (accounting) exposure
c) Economic exposure

Berikan contoh konkret dan strategi hedging untuk masing-masing.

**JAWABAN:**

---

**a) TRANSACTION EXPOSURE**

**Definisi:**
Risiko dari transaksi yang sudah committed (kontrak sudah ditandatangani) dalam foreign currency, tapi belum settled. Risiko bahwa cash flow aktual berbeda dari yang diharapkan karena perubahan exchange rate.

**Contoh:**

```
PT Eksportir Indonesia (tanggal 1 Januari):
- Jual barang ke US buyer seharga USD 1 juta
- Payment terms: 90 days (due 1 April)
- Exchange rate saat kontrak: Rp 15.000/USD
- Expected receipt: 1.000.000 × 15.000 = Rp 15 miliar
```

**Scenario 1 April (Settlement):**

```
Scenario A - Rupiah menguat:
Exchange rate = Rp 14.000/USD
Actual receipt = 1.000.000 × 14.000 = Rp 14 miliar
Loss = Rp 1 miliar ❌

Scenario B - Rupiah melemah:
Exchange rate = Rp 16.000/USD
Actual receipt = 1.000.000 × 16.000 = Rp 16 miliar
Gain = Rp 1 miliar ✅
```

**Karakteristik:**
- **Short-term** (days to months)
- **Contractual commitment**
- **Known amount and timing**
- **Cash flow impact** langsung terlihat

---

**Strategi Hedging Transaction Exposure:**

**1. Forward Contract** (paling umum)
```
Tanggal 1 Jan:
Lock in forward rate 90 days = Rp 14.800/USD

Tanggal 1 April:
Jual USD 1 juta at Rp 14.800 (regardless of spot)
Certain receipt = Rp 14,8 miliar
```

**2. Money Market Hedge**
```
Tanggal 1 Jan:
1. Pinjam USD di US market (assume rate 5% p.a.)
   Present value USD 1 juta = 1.000.000 / 1.0125 = USD 987.654
2. Convert ke Rupiah at spot = 987.654 × 15.000 = Rp 14.814.810.000
3. Invest di Indonesia (assume rate 10% p.a.)

Tanggal 1 April:
1. Receive USD 1 juta dari customer
2. Repay USD loan = USD 1 juta
3. Rupiah investment mature = 14.814.810.000 × 1,025 = Rp 15.185.180.250
```

**3. Currency Option**
```
Buy put option:
Strike = Rp 15.000/USD
Premium = Rp 200/USD
Total cost = Rp 200 juta

Tanggal 1 April:
If spot < 15.000: Exercise put, sell at 15.000
If spot > 15.000: Let expire, sell at spot

Worst case = (15.000 - 200) = Rp 14.800/USD
Best case = Unlimited upside
```

**4. Leading and Lagging**
```
If expect rupiah strengthen (bad for exporter):
→ Lead: Minta customer bayar early (kasih discount)

If expect rupiah weaken (good for exporter):
→ Lag: Offer customer extended terms
```

**5. Invoicing in Home Currency**
```
Instead of invoice in USD, invoice in IDR
→ Customer bears FX risk
→ Tapi might lose competitiveness
```

---

**b) TRANSLATION (ACCOUNTING) EXPOSURE**

**Definisi:**
Risiko dari translasi laporan keuangan subsidiary dalam foreign currency ke home currency untuk consolidation. Nilai aset dan liabilities berubah di balance sheet karena exchange rate movement, meskipun tidak ada cash flow impact.

**Contoh:**

```
PT Indonesia memiliki subsidiary di Singapura:

PT Singapore Subsidiary (SGD)
Balance Sheet (31 Dec 2025):
Assets = SGD 100 juta
Liabilities = SGD 60 juta
Equity = SGD 40 juta

Exchange rate 31 Dec 2025: Rp 11.000/SGD
```

**Konsolidasi 31 Dec 2025:**
```
Assets = 100 juta × 11.000 = Rp 1.100 miliar
Liabilities = 60 juta × 11.000 = Rp 660 miliar
Equity = 40 juta × 11.000 = Rp 440 miliar
```

**Konsolidasi 31 Dec 2026 (Exchange rate berubah ke Rp 10.000/SGD):**
```
Assets = 100 juta × 10.000 = Rp 1.000 miliar (turun Rp 100 miliar)
Liabilities = 60 juta × 10.000 = Rp 600 miliar (turun Rp 60 miliar)
Equity = 40 juta × 10.000 = Rp 400 miliar (turun Rp 40 miliar)

Translation loss = Rp 40 miliar
→ Reported di "Other Comprehensive Income" atau "CTA" (Cumulative Translation Adjustment)
```

**Karakteristik:**
- **Accounting effect**, bukan cash flow
- **Balance sheet risk**
- **Reported earnings volatility**
- **Net investment exposure**

**Important Note:**
- No actual cash gain/loss
- Hanya "paper gain/loss"
- Tapi impact investor perception dan compliance (debt covenants)

---

**Strategi "Hedging" Translation Exposure:**

**Catatan:** Banyak perusahaan TIDAK hedge translation exposure karena:
- No cash flow impact
- Expensive
- Long-term nature

**Tapi jika mau hedge:**

**1. Balance Sheet Hedge**
```
Match currency composition of assets and liabilities

Example:
Singapore subsidiary punya assets SGD 100 juta
→ Borrow SGD 60 juta (instead of IDR/USD)
→ Net exposure = Asset - Liability = SGD 40 juta (reduced)

If SGD depreciates:
Asset value ↓ but Liability value ↓ (offset)
```

**2. Forward Contract on Net Investment**
```
Sell forward SGD 40 juta (net equity exposure)
Maturity = 1 tahun
→ Lock in translation rate

Tapi mahal karena long-term forward, dan perlu roll over setiap tahun
```

**3. Cross-Currency Swap**
```
Swap IDR floating for SGD floating
Notional = SGD 40 juta
→ Synthetic SGD liability to offset SGD asset
```

**4. Natural Hedge**
```
Diversify subsidiaries:
US subsidiary (USD assets)
+ Europe subsidiary (EUR assets)
+ Singapore subsidiary (SGD assets)
→ Not all currencies move together → portfolio effect
```

**5. Do Nothing**
```
Many companies choose this:
- Long-term perspective
- No cash impact
- Focus on economic exposure instead
```

---

**c) ECONOMIC EXPOSURE (Operating Exposure)**

**Definisi:**
Risiko terhadap future cash flows dan competitive position dari perubahan exchange rate. Ini adalah long-term, strategic exposure yang mempengaruhi competitive advantage.

**Contoh 1: Domestic Company dengan Import Competition**

```
PT Garment Indonesia:
- Jual di pasar lokal (IDR)
- Kompetitor: import dari China (CNY)
- Cost structure: 70% lokal, 30% imported fabric

Scenario: CNY melemah 20% vs IDR
```

**Impact:**
```
Chinese imports jadi 20% lebih murah di Indonesia
→ Market share PT Garment turun
→ Pricing pressure (must cut price to compete)
→ Margin compressed
→ Long-term profitability ↓

Ini ECONOMIC EXPOSURE walaupun PT Garment tidak punya transaksi foreign currency!
```

---

**Contoh 2: Exporter dengan Production Flexibility**

```
Toyota Japan:
- Jual mobil ke US (USD revenue)
- Produksi di Japan (JPY cost)

Scenario: JPY menguat 30% vs USD
```

**Impact:**
```
USD revenue convert ke JPY → Turun 30%
Tapi JPY cost tetap
→ Profit margin destroyed

Competitive position:
- US domestic producers (Ford, GM) jadi lebih competitive
- Market share Toyota turun
- Long-term brand value impact
```

---

**Strategi Managing Economic Exposure:**

**1. Production Diversification (Paling Efektif)**
```
Toyota response to JPY strength:
- Build plants di US
- Build plants di Thailand, Indonesia
- "Natural hedge": Cost dalam USD/THB/IDR match revenue currency

Result:
- Less dependent on JPY/USD rate
- Competitive position stabilized
```

**2. Market Diversification**
```
Don't rely on one export market

Example PT Eksportir:
Instead of 100% export to US
→ Diversify: 40% US, 30% EU, 30% Asia
→ Currency basket reduces volatility
```

**3. Product Differentiation**
```
Create strong brand loyalty
→ Less price-sensitive
→ Can maintain price even when currency moves

Example: Apple iPhone
- Premium brand
- Even if USD strong, customers still buy
- Less vulnerable to FX fluctuation
```

**4. Operational Flexibility**
```
Option to source from different countries based on FX

Example Multinational Manufacturer:
If EUR weak → Source more dari European suppliers
If CNY weak → Source more dari China
→ "Flexible sourcing strategy"
```

**5. Pricing Strategy**
```
Pass-through FX changes to customers

Examples:
- Quarterly price adjustment clauses
- FX surcharge mechanism
- "This price valid for 30 days"

Tapi tergantung competitive intensity
```

**6. Financial Hedging (Limited Use)**
```
Long-term forward contracts
Currency swaps
Options strategies

Tapi:
- Expensive for long-term
- Hard to quantify exact exposure
- Operational hedges lebih efektif
```

---

**COMPARISON:**

| Type | Time Horizon | Impact | Ease to Hedge | Example |
|------|--------------|--------|---------------|---------|
| **Transaction** | Short-term | Cash flow | Easy | Account receivable USD |
| **Translation** | Ongoing | Accounting | Medium | Foreign subsidiary assets |
| **Economic** | Long-term | Competitive | Hard | Market share vs imports |

---

**INTEGRATED EXAMPLE:**

**PT Indonesia Export-Import:**

**Transaction Exposure:**
```
Receivable: USD 10 juta (due 3 months)
Payable: EUR 5 juta (due 2 months)

Hedge:
- Forward contract sell USD 10 juta
- Forward contract buy EUR 5 juta
```

**Translation Exposure:**
```
Subsidiary di Thailand:
Net assets = THB 500 juta

Hedge:
- Borrow THB 300 juta
- Net exposure reduced to THB 200 juta
```

**Economic Exposure:**
```
70% revenue dari export (USD)
50% cost dari import (EUR)

Long-term strategy:
- Setup production di US (reduce USD exposure)
- Develop local suppliers (reduce EUR exposure)
- Diversify export markets ke Asia (JPY, CNY)
```

---

**KESIMPULAN:**

**Priority:**
1. **Must hedge:** Transaction exposure (certain, short-term, cash impact)
2. **Consider hedge:** Translation exposure (jika impact covenant atau investor perception)
3. **Strategic manage:** Economic exposure (operational solutions better than financial)

**Best Practice:**
- Centralized FX risk management (treasury department)
- Clear hedging policy dan benchmark
- Combine financial and operational hedges
- Focus on economic exposure yang paling strategic

**Remember:**
> "The goal is not to eliminate all FX risk (impossible and expensive), but to manage it intelligently to protect competitive position and shareholder value."

---

---

# PENUTUP

**Tips Menghadapi Ujian:**

1. **Konsep:** Pahami logic di balik setiap konsep, jangan hapal mentah
2. **Hitungan:** Latihan soal berulang-ulang sampai formula masuk kepala
3. **Interpretasi:** Selalu explain hasil perhitungan, jangan cuma angka
4. **Real-world connection:** Hubungkan dengan kasus nyata/berita
5. **Time management:** Kerjakan soal yang paling confident dulu

**Formula yang MUST KNOW:**

- **NPV akuisisi** = Synergy - Premium
- **Conversion value** = Conversion ratio × Stock price
- **Underpricing** = (P1 - P0) / P0
- **Put payoff** = Max(K - ST, 0)
- **Call payoff** = Max(ST - K, 0)

**Good luck dengan ujian Anda! 🍀📚**

---

*Soal latihan ini dibuat berdasarkan kisi-kisi yang Anda berikan. Jika ada bab spesifik yang ingin ditambahkan lebih banyak soal atau ada topik yang perlu diperdalam, silakan beritahu saya!*
