# Audio-Benchmarking-ESC-50

# Audio-CRNN-Benchmarking-ESC50

Nama Folder Pengumpulan: 15322001_SitiRamadina_AudioN
N masih harus diganti

|Identitas||
|--|--|
|Nama|Siti Ramadina Goethe K.|
|NIM|15322001|
|Kode Mahasiswa|MHS-06|

## Task Specification
|Aspect|Specification|
|--|--|
|Topic|Audio|
|Main model|CRNN|
|Baseline model|ResNet-18 Mel-Spec|
|SOTA model|ViT Audio|
|Methods| Benchmarking|
|Dataset|[ESC-50: Dataset for Environmental Sound Classification](https://github.com/karolpiczak/ESC-50)|

## Folder Structure
```
NIM_NamaSingkat_TopikN/
├── report.pdf
├── slides_presentasi.pdf
│
├── model_utama/
│   ├── config.yaml
│   ├── train_curve.png
│   ├── val_curve.png
│   ├── metrics.json
│   ├── confusion_matrix.png
│   ├── benchmark_embeddings.csv ← N × d matrix
│   ├── rsm_cosine.csv ← N × N matrix
│   ├── rsm_heatmap.png
│   ├── saliency/
│   └── [sample_id].png (20–30 sampel)
│
├── model_pembanding_1/
│   └── (struktur sama dengan model_utama)
│
├── model_pembanding_2/
│   └── (struktur sama dengan model_utama)
│
├── komparasi/
│   ├── tabel_metrik_semua_model.csv
│   ├── rsm_comparison.png ← side-by-side RSM
│   └── saliency_comparison.png ← side-by-side saliency
│
└── reproducibility/
    ├── requirements.txt
    ├── readme.txt
    └── notebook_atau_script/
```
