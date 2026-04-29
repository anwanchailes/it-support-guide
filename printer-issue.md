# Printer Troubleshooting Guide

## 🔍 Masalah Umum

* Printer tidak terdeteksi di komputer
* Tidak bisa print (print queue stuck)
* Printer offline
* Hasil print kosong / tidak jelas

---

## 🛠️ Langkah Troubleshooting

### 1. Cek Koneksi

* Pastikan kabel USB / LAN terhubung dengan benar
* Jika printer jaringan, pastikan terhubung ke Wi-Fi yang sama

---

### 2. Cek Status Printer

* Buka **Control Panel → Devices and Printers**
* Pastikan printer tidak dalam status:

  * Offline
  * Pause printing

---

### 3. Restart Printer & Komputer

* Matikan printer, tunggu 10–15 detik, lalu nyalakan kembali
* Restart komputer untuk refresh sistem

---

### 4. Clear Print Queue

* Buka:
  Control Panel → Devices and Printers
* Klik kanan printer → See what’s printing
* Cancel semua document

---

### 5. Restart Print Spooler (Advanced)

* Tekan `Windows + R` → ketik `services.msc`
* Cari **Print Spooler**
* Klik:

  * Stop → lalu Start kembali

---

### 6. Cek Driver Printer

* Pastikan driver sudah terinstall dengan benar
* Jika error:

  * Uninstall printer
  * Install ulang driver terbaru

---

### 7. Test Print

* Lakukan test print dari:
  Printer Properties → Print Test Page

---

## ✅ Solusi Umum

* Restart printer & clear queue sering menyelesaikan masalah
* Driver bermasalah biasanya jadi penyebab utama printer tidak terdeteksi

---

## 📌 Tips IT Support

* Gunakan driver resmi dari vendor printer
* Dokumentasikan error yang sering terjadi
* Simpan installer driver untuk mempercepat troubleshooting

---

## 💡 Catatan

Masalah printer sering terjadi di lingkungan operasional, jadi penting untuk memiliki langkah troubleshooting yang cepat dan sistematis.
