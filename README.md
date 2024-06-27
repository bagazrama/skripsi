Project ini terdiri dari beberapa file dan folder yang memiliki peran masing-masing dalam proses pengolahan citra. Berikut adalah flow dan penjelasan singkat mengenai file dan folder yang terlibat.

Flow rada gampang:

![image](https://github.com/bagazrama/skripsi/assets/85323158/2fd621d1-3396-4059-919a-463d1c99ea02)

1. **Start Files**
    - `fix_prepro.ipynb`
    - `fix_ujidataset.ipynb`
    - `fix_algo.ipynb`

2. **Folders**
    - **dataset**: Folder ini berisi gambar awal citra yang belum di apa-apain.
    - **uji_dataset**: Folder ini juga berisi gambar awal citra yang belum di apa-apain, bedanya folder ini digunakan untuk uji.
    - **segmented_images**: Folder ini berisi hasil dari proses preprocessing (`fix_prepro.ipynb`).
    - **uji_segmented_images**: Folder ini berisi hasil dari `fix_ujidataset.ipynb`, bedanya folder ini digunakan untuk uji.
    - Folder dan file lain digunakan untuk trial and error Saya.

## Cara Penggunaan
1. Jalankan file `fix_prepro.ipynb` untuk melakukan preprocessing pada gambar di folder `dataset`.
2. Jalankan file `fix_ujidataset.ipynb` untuk melakukan preprocessing pada gambar di folder `uji_dataset`.
3. Jalankan file `fix_algo.ipynb` untuk menjalankan algoritma pada hasil preprocessing.

Selamat mencoba!
