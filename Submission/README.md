
## 🚀 Cara Menjalankan Proyek

### 1. Clone / upload dataset ke Google Colab
### 2. Jalankan notebook:
- Preprocessing (rescale, resize, split)
- Training menggunakan Sequential CNN model
- Evaluasi akurasi (target: **≥ 85%**)
- Plot accuracy & loss

---

## 💾 Output Model

Model disimpan ke dalam **tiga format**:

```
.
├── saved_model/             # Untuk TensorFlow Serving / TFJS / TFLite
│   ├── saved_model.pb
│   └── variables/
├── tflite/                  # Untuk deployment mobile (Android, Edge)
│   ├── model.tflite
│   └── label.txt
└── tfjs_model/              # Untuk deployment web (browser)
    ├── model.json
    └── group1-shard1of1.bin
```

---

## 📊 Visualisasi

Grafik akurasi dan loss selama training:

- `Accuracy vs Epoch`
- `Loss vs Epoch`

---

## 📎 Requirements

Install dependencies dari file `requirements.txt`:
```bash
pip install -r requirements.txt
```

