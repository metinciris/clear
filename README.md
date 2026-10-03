# Şeffaf Hücre İçeren Renal Tümör – Algoritmik Yaklaşım

Patologlar için hazırlanmış, tek dosyalık ve tarayıcıda çalışan **renal clear-cell diferansiyel tanı karar destek aracı**.

Ana dosya: `index.html`

## Amaç

Araç; primer renal kitle veya metastatik odakta, tru-cut/küçük biyopsi ve rezeksiyon materyallerinde:

- morfoloji,
- CAIX / CK7 ekseni,
- bağlama göre PAX8 ve CD10,
- hedeflenmiş ikinci basamak immünohistokimya,
- gerektiğinde moleküler doğrulama

üzerinden pratik bir tanısal yol sunar.

> **Önemli:** Ekrandaki “güçlü / kısmi / zayıf fenotipik uyum” ifadeleri valide edilmiş olasılık skorları değildir. Kural tabanlı karar desteğidir.

## 3 Ekim 2026 bilimsel güncellemesi

- **Diffüz CK7/KER7 pozitifliği ccRCC'yi dışlamaz.** Moleküler doğrulanmış Tanaka 2026 serisinde herhangi bir KER7 pozitifliği %30, diffüz pozitiflik %16 idi.
- **CAIX/CA9 kaybı klinik bağlama göre yorumlanmalıdır.** Aynı seride primer ccRCC'lerde 0/54, metastatik ccRCC'lerde 8/54 (%14,8) CA9-negatiflik vardı. Primer kitlede CAIX negatifliği bu nedenle belirgin discordans olarak işaretlenir.
- **PAX8 negatifliği renal kökeni tek başına dışlamaz.** Primerlerde %3,8, metastazlarda %9,4 negatiflik vardı; fark istatistiksel olarak anlamlı değildi (P=0,437).
- **ELOC-mutated RCC moleküler bir tanıdır.** 2026'daki 35 olguluk seride CAIX güçlü-diffüz pozitifti, GPNMB değerlendirilen 28/28 olguda negatifti; kopya sayı analizi yapılan 26/26 olguda 8q kaybı vardı ve 3p kaybı saptanmadı.
- **GPNMB yardımcı/triage belirtecidir, tek başına ayırıcı değildir.** 2026 verileri MTOR-altere RCCFMS ile CCPRCT arasında zayıf/orta GPNMB ekspresyon örtüşmesi gösterebildiğini ortaya koymuştur.

## Temel dallar

- Clear cell RCC
- Clear cell papillary renal cell tumor (CCPRCT)
- ELOC-mutated RCC
- TSC1/TSC2/MTOR-altere RCC with fibromyomatous stroma
- TFE3-rearranged / TFEB-altered RCC
- FH-deficient RCC
- SDH-deficient RCC
- Chromophobe RCC / oncocytic spectrum
- ALK-rearranged RCC
- Renal olmayan clear-cell taklitçiler

## Kullanım ilkesi

1. Önce örnek tipi ve klinik bağlamı seçin.
2. Morfolojik paterni işaretleyin.
3. CAIX ve CK7 ile ana yönü belirleyin.
4. PAX8/CD10 ve ikinci basamak IHK'yi bağlama göre ekleyin.
5. Non-kanonik IHK, fibromyomatöz stroma, yüksek grade veya moleküler tanımlı RCC kuşkusunda uygun NGS/FISH/RNA füzyon testine geçin.
6. Tru-cut materyalinde doku rezervini korumak için “shotgun” panel yerine kademeli yaklaşım kullanın.

## Ana kaynaklar

1. Tanaka KS, et al. **Immunohistochemical profile of molecularly verified clear cell renal cell carcinomas.** Histopathology. 2026. DOI: 10.1111/his.70287.
2. WHO Classification of Tumours Editorial Board. **Urinary and Male Genital Tumours.** 5th ed. IARC; 2022.
3. Hou J, et al. **ELOC-mutated Renal Cell Carcinoma: Clinicopathologic, Immunohistochemical, and Molecular Genetic Analysis of 35 Cases.** Modern Pathology. 2026;39(4):100977. PMID: 41690476.
4. Wang JJ, et al. **ELOC-Mutated Renal Cell Carcinoma is a Rare Indolent Tumor With Distinctive Genomic Characteristics.** Modern Pathology. 2025;38:100777. PMID: 40246078.
5. Li H, et al. **Positive GPNMB Immunostaining Differentiates Renal Cell Carcinoma With Fibromyomatous Stroma Associated With TSC1/2/MTOR Alterations From Others.** Am J Surg Pathol. 2023. PMID: 37661807.
6. Skopal J, et al. **GPNMB expression in clear cell papillary renal cell tumour: Limited specificity and a potential diagnostic pitfall in clear cell renal neoplasms.** Ann Diagn Pathol. 2026. Epub 21 Aug 2026;85:152707. doi:10.1016/j.anndiagpath.2026.152707. PMID: 42641476.

## Sınırlılıklar

- Araç klinik validasyonu yapılmış bir tahmin modeli değildir.
- Tanaka 2026 kohortu NGS için seçilmiş olgulardan oluşur; bildirilen oranlar genel ccRCC prevalansı gibi yorumlanmamalıdır.
- İmmünohistokimya; preanalitik değişkenler, antikor klonu/platformu ve intratümoral heterojeniteden etkilenebilir.
- Nihai tanı morfoloji, klinik-radyolojik bağlam ve gerektiğinde moleküler verilerle bütünleştirilmelidir.

## Teknik

- Tek dosya: `index.html`
- Harici sunucu veya veritabanı gerekmez.
- Tarayıcıda çevrimdışı çalışabilir.
- Girilen veriler dışarı gönderilmez.

Son güncelleme: **3 Ekim 2026**
