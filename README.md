## Langkah-langkah:

`cmd: python face_taker.py`

1) Ambil gambar dengan menggunakan skrip face_taker.py. Skrip tersebut akan menyimpan 30 gambar wajah Anda di dalam folder images setelah Anda memasukkan nomor ID (HARUS berupa bilangan bulat dan bertambah (mulai dari 1, kemudian 2, 3, ...)
Catatan: Pastikan wajah Anda berada di tengah. Jendela akan menutup setelah semua 30 gambar diambil.

`cmd: python face_train.py`

2) Skrip face_train.py akan melatih model untuk mengenali semua wajah dari 30 gambar yang diambil menggunakan skrip face_taker.py, dan menyimpan hasil pelatihan di dalam file training.yml.

`cmd: python face_recognizer.py`

3) Skrip face_recognizer.py adalah skrip utama. Anda perlu menambahkan nama setiap orang yang melihat gambar wajahnya diambil pada skrip face_taker.py. Program akan mengenali wajah sesuai dengan ID yang diberikan pada skrip face_taker.py. Jika Joe memiliki ID 1, namanya harus muncul dalam daftar sebagai indeks 1 seperti ini names = ['None', 'Joe'] # simpan None dan tambahkan nama ke dalam daftar ini

Persyaratan:

- `pip install opencv-python`
- `pip install opencv-contrib-python --upgrade` or `pip install opencv-contrib-python --user`


