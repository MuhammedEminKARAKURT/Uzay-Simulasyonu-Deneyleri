# 🌌 Uzay Simülasyonu Laboratuvarı (C Programı)

Bu proje, **Bursa Teknik Üniversitesi – Uzay Simülasyonu Laboratuvarı** kapsamında geliştirilen,
farklı gezegenlerdeki fiziksel olayları **C dili** kullanarak simüle eden bir konsol uygulamasıdır.

Program; gezegenlerin yerçekimi ivmelerini kullanarak çeşitli **klasik mekanik deneylerini**
kullanıcıdan alınan parametrelere göre hesaplar ve sonuçları karşılaştırmalı olarak sunar.

---

## 🚀 Özellikler

- 8 farklı gezegen için fiziksel hesaplamalar:
  - Merkür
  - Venüs
  - Dünya
  - Mars
  - Jüpiter
  - Satürn
  - Uranüs
  - Neptün
- Menü tabanlı, kullanıcı dostu arayüz
- Hatalı girişlere karşı dayanıklı veri doğrulama
- Pointer kullanımı ile diziler üzerinde işlem
- Fizik ve C programlama dersleri için uygundur

---

## 🧪 İçerdiği Deneyler

| No | Deney Adı |
|----|----------|
| 1  | Serbest Düşme Deneyi |
| 2  | Yukarı Atış Deneyi |
| 3  | Ağırlık Deneyi |
| 4  | Kütleçekimsel Potansiyel Enerji |
| 5  | Hidrostatik Basınç |
| 6  | Arşimet Kaldırma Kuvveti |
| 7  | Basit Sarkaç Periyodu |
| 8  | Sabit İp Gerilmesi |
| 9  | Asansör Deneyi |

---

## 🧠 Kullanılan Fiziksel Formüller

- **Serbest düşme:**  
  \[
  h = \frac{1}{2} g t^2
  \]

- **Maksimum yükseklik:**  
  \[
  h_{max} = \frac{v_0^2}{2g}
  \]

- **Ağırlık:**  
  \[
  G = m \cdot g
  \]

- **Potansiyel enerji:**  
  \[
  E_p = m \cdot g \cdot h
  \]

- **Hidrostatik basınç:**  
  \[
  P = \rho \cdot g \cdot h
  \]

- **Arşimet kaldırma kuvveti:**  
  \[
  F_k = \rho \cdot g \cdot V
  \]

- **Basit sarkaç periyodu:**  
  \[
  T = 2\pi \sqrt{\frac{L}{g}}
  \]

- **Asansör etkin ağırlığı:**  
  \[
  N = m(g \pm a)
  \]

---

## ⚙️ Kurulum ve Çalıştırma

### Derleme
```bash
gcc uzay_simulasyonu.c -o uzay_simulasyonu -lm
