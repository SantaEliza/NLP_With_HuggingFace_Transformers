<h1 align="center"> NLP With HuggingFace Transformers </h1>
<p align="center"> Berisi tentang pipeline dari HuggingFace Transformers untuk keperluan NLP (Natural Language Processing)</p>

<div align="center">

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">

</div>

<h2 align="center"> Analisis </h2> 

Analisis Pipeline:

1. Topic Classification. mengklasifikasikan teks ke dalam kategori/label yang telah ditentukan. Algoritma yang dipakai adalah zero-shot-classification. ZSL akan memetakan konteks dari kategori baru ke kategori-kategori yang telah dipelajari dan akhirya  bisa mengenali kategori/topik  yang benar tanpa contoh eksplisit seperti teks yang telah diinput.

2. Text Generator. Melanjutkan kata dari kalimat yang diinput. Model akan memperediksi lanjutan kata yang mungkin cocok untuk melengkapi kalimat dengan mengaitkan topik apa yang berhubungan dengan isi konteks kalimat.

3. Fill-Mask. Memprediksi kata yang hilang dalam sebuah kalimat. Contoh : Jalan-jalan ke ___ adalah impianku dari kecil. Model mungkin akan memberi daftar negara/tempat untuk mengisi bagian yang hilang.

4. Name Entity Recognition (NER). Mengklasifikasikan entitas yang ada pada teks yang diinput. Misalnya seperti entitas person(subject), lokasi, kelompok(group) yang terdapat pada teks dan outputnya berupa informasi.

5. Question Answering. Model akan menjawab  pertayaan yang kita berikan dengan mengekstrak jawaban dari informasi berupa teks/konteks yang sebelumnya kita berikan.

6. Sentiment Analysis. Mengidentifikasi apakah teks yang kita input itu bersifat positif, negatif ataupun netral. 

7. Summarization. Meringkas sebuah teks/informasi yang cukup banyak menjadi beberapa kalimat saja. Seperti merangkum sebuah artikel ataupun pertanyaan agar menjadi ringkas dan mendapat informasi dengan cepat.

8. Translation. Saya kira mirip dengan cara kerja google translate dimana kita menginput bahasa awal kemudian meminta untuk menerjemahkan ke bahasa asing seperti bahasa inggris, prancis dan lain-lain.

Dari beberapa pipeline yang ada, saya cukup tertarik dengan question answering karena sangat berguna jika nanti saya ingin melakukan riset dari dokumen -dokumen  yang ada dan mendapat jawaban dari model tanpa harus membaca seluruh isi dokumen yang pastinya cukup banyak.
