# Analisis Komparatif CNN from Scratch vs Transfer Learning untuk Klasifikasi Citra Biner

**Proyek Individu - Tugas Pembelajaran Mesin 2** **Nama Mahasiswa :** Nada Lahfah Diha   
**NIM              :** 452024618093  
**Mata Kuliah      :** Deep Learning / Pemrosesan Sinyal Digital  
**Dosen Pengampu   :** Assoc. Prof. Dr. Ir. Oddy Virgantara Putra, S.Kom., M.T., IPP.  
**Universitas      :** Universitas Darussalam Gontor  

---

## 1. Deskripsi Proyek
Proyek ini melakukan studi komparatif mendalam mengenai efisiensi dan performa dua pendekatan arsitektur *Deep Learning* dalam menyelesaikan tugas klasifikasi citra dua kelas (*binary classification*):
* **Eksperimen 1 (CNN From Scratch):** Membangun dan melatih jaringan saraf konvolusi sendiri dari dasar menggunakan subset biner dari dataset **CIFAR-10** (fokus pada Kelas *Airplane* dan *Automobile*).
* **Eksperimen 2 (Transfer Learning):** Memanfaatkan model pra-latih (*pretrained model*) **MobileNetV2** yang telah dilatih pada jutaan gambar ImageNet, dikombinasikan dengan strategi *Feature Extraction* menggunakan dataset **Cats vs Dogs**.

---

## 2. Struktur Repository GitHub
Sesuai dengan regulasi dan ketentuan minimal yang diinstruksikan, repositori ini disusun dengan struktur folder sebagai berikut:
```text
project-cnn-vs-transfer-learning/
├── dataset/
│   └── link_dataset.txt
├── notebook/
│   └── cnn_vs_transfer_learning.ipynb
├── report/
│   └── laporan.pdf
├── README.md
└── requirements.txt
