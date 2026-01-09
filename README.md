# Tensorflow-in-Action
<img width="500" height="700" alt="image" src="https://github.com/user-attachments/assets/bd4fcb98-f98f-4350-bdab-0d495c7263cb" />


Code Reproduction + Theoretical Deep Dive from TensorFlow in Action (Thushan Ganegedara)

## Created by Group 13 DL TK-46-GAB
Darryl Satria Wibowo | 1103223057
Fakriza Bondan Pradipta | 1103223146

# Tensorflow-in-Action

Code reproduction dan **theoretical deep dive** dari buku _TensorFlow in Action (Covers TensorFlow 2.9)_ karya Thushan Ganegedara (Manning, 2022). Repo ini berisi rangkaian Jupyter Notebook yang mengikuti alur bab di buku, dengan eksperimen tambahan, catatan pribadi, dan beberapa modifikasi arsitektur/model. 

> ⚠️ Repo ini tidak berisi teks buku, hanya kode dan catatan turunan. Untuk materi lengkap (teori, penjelasan, dan soal latihannya), tetap perlu memiliki buku aslinya. 

---

## Tujuan Repo

Repo ini dibuat untuk:

- Merekam proses belajar TensorFlow 2.x dari dasar hingga MLOps berbasis buku **TensorFlow in Action**.   
- Mereproduksi dan memodifikasi contoh kode dari buku dalam bentuk notebook yang runnable.   
- Menambah eksperimen pribadi (variasi arsitektur, hyperparameter, dsb.) di atas baseline dari buku. 

Fokus utama:

- TensorFlow 2.x + Keras (modeling, training loop, dan data pipeline).  
- Computer Vision (image classification & segmentation). 
- Natural Language Processing (sentiment analysis, language modeling, seq2seq, Transformers).   
- Monitoring & MLOps dengan TensorBoard dan TFX + deployment via TensorFlow Serving/Docker. 

---

## Struktur Repo

Struktur aktual repo bisa berubah seiring waktu, tapi pola umumnya:

```text
Tensorflow-in-Action/
├── notebooks/
│   ├── ch01-*.ipynb                    # Intro TensorFlow & ML lifecycle
│   ├── ch02-*.ipynb                    # TF building blocks (Tensor, Variable, ops)
│   ├── ch03-*.ipynb                    # Keras APIs & data input pipelines
│   ├── ch04-*.ipynb                    # FCN, CNN, RNN dasar
│   ├── ch05-*.ipynb                    # Transformers (dasar)
│   ├── ch06-cnn-image-classification.ipynb
│   ├── ch07-regularization-gradcam.ipynb
│   ├── ch08-image-segmentation-deeplabv3.ipynb
│   ├── ch09-sentiment-analysis.ipynb
│   ├── ch10-language-modeling.ipynb
│   ├── ch11-12-seq2seq-attention.ipynb
│   ├── ch13-transformers-bert-qa.ipynb
│   ├── ch14-tensorboard.ipynb
│   └── ch15-tfx-mlops.ipynb
├── data/                               # Optional: dataset kecil (<100MB)
├── .gitignore
├── requirements.txt (jika sudah dibuat)
└── README.md


