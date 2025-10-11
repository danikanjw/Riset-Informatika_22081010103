# Methods vs Methodology

## **Paper 1**  
**Judul:** *The importance of data transformation in RNA-Seq preprocessing for bladder cancer subtyping* \
**Link:** https://link.springer.com/article/10.1186/s13104-025-07138-x

### **Isi bagian Methods**
> “We evaluated twelve combinations of preprocessing methods on three molecular subtype classifiers using four bladder cancer datasets: GSE148079 (n = 8), GSE179440 (n = 12), GSE186610 (n = 100) and TCGA (n = 378). The preprocessing workflow included quality control, alignment (STAR, Hisat2), quantification (FeatureCounts, StringTie, HTSeq), and pseudoalignment (Salmon, Kallisto), using hg38 annotations. Different normalization and/or transformation methods (TMM, TPM and log2TPM), together with rawData and log2rawData were studied. ConsensusMIBC, LundTax, and TCGAclas classifiers were assessed using separation and coincidence metrics.”

### **Kenapa ini termasuk Methods**
Karena yang dijelaskan adalah **alat/teknik spesifik yang dipakai untuk mengolah data** (aligner *STAR/Hisat2*, quantifier *FeatureCounts*, dsb).  
Bagian ini **tidak membahas alasan pemilihan data** atau **kerangka berpikir risetnya**, melainkan menjelaskan proses teknis yang digunakan untuk melakukan analisis.

---

## **Paper 2**  
**Judul:** *Detection and mitigation of soil salinization risk from saline/brackish water aquaculture in coastal areas: an application of remote sensing and managed aquifer recharge* \
**Link:** https://link.springer.com/article/10.1007/s11852-024-01067-w#Sec1

### **Kenapa ini termasuk Methodology**
Alasan mengapa bagian ini tergolong **metodologi** adalah karena penulis tidak hanya menyebutkan alat atau teknik pengumpulan data, tetapi menjelaskan **keseluruhan pendekatan penelitian**, mulai dari:

#### **1. Theoretical underpinning / Rationale**
- Penelitian didasarkan pada permasalahan salinisasi tanah akibat akuakultur di wilayah pesisir.  
- Argumen konseptual mengarah pada kebutuhan mitigasi melalui *Managed Aquifer Recharge (MAR)* dan peran penginderaan jauh sebagai alat deteksi.

#### **2. Data collection (What, From where, How)**
- **Apa:** Data salinitas tanah (*electrical conductivity/EC*) pada lapisan 0–20 cm.  
- **Dari mana:** Lokasi spesifik di empat provinsi Delta Mekong (*Bac Lieu, Soc Trang, Tra Vinh, Ben Tre*).  
- **Bagaimana:** Pengambilan sampel menggunakan bor tangan pada musim kering (April 2016), kemudian dianalisis di laboratorium untuk mengukur EC.

#### **3. Data analysis (How you analyze it)**
- Penerapan algoritma **Random Forest** untuk klasifikasi citra satelit.
- Pengembangan indeks spektral baru (D-index) untuk meningkatkan deteksi salinitas.
- Integrasi data lapangan dengan hasil klasifikasi untuk validasi.
- Analisis statistik melalui ANOVA dan K-means clustering.
- Perhitungan neraca air (water balance equation) dan model hidrogeologi untuk menilai potensi infiltrasi kolam (pond infiltration).
  
Dengan demikian, bagian ini mencerminkan kerangka kerja penelitian secara menyeluruh, yang sesuai dengan definisi metodologi sebagai “the overall approach to the research process, from the theoretical underpinning to the collection and analysis of the data”.
