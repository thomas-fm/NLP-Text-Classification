# NLP-Text-Classification

## BERT Fine-Tuning:
Link Model:
[Fine-Tuning BERT](https://drive.google.com/file/d/1yund8a0yFH80Xd5a0-URDbUbufO6CETJ/view?usp=sharing)

Harap gunakan Google Colab untuk melakukan tuning agar lebih cepat dan aman untuk perangkat.

**Untuk menjalankan model PASTIKAN terdapat class yang ada dalam notebook BERT_classification.**

Lalu load menggunakan library pickle seperti berikut:
```python
import pickle
model = pickle.load(open([PATH], 'rb'))
``` 

## Deep Learning Fasttext: 
Sebelum run program unduh terlebih dahulu vector Fasttext pada: 
[Fasttext File](https://fasttext.cc/docs/en/crawl-vectors.html) 

Pilih Bahasa Indonesia dan file format text, setelah itu run seperti biasa dari cell pertama. 

## Deep Learning Word2vec: 
Sebelum run program unduh terlebih dahulu vector word2vec versi Bahasa Indonesia pada: 
[word2vec File](https://drive.google.com/file/d/1WFBBCDIssfHDeFpYgWPtj14e71vYkX6o/view) 

Ekstrak dan keluaran isi file dalam folder lalu jalankan program.
