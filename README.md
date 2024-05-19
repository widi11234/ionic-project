# IONIC UI - MAS WIDI

## Yang harus diinstall
1. Android studio
2. Visual Studio Code
3. Samakan versi IONIC sesuai gambar di bawah ini : 
<img width="710" alt="Screenshot 2024-05-18 at 19 49 53" src="https://github.com/dimaspndw/ionic-app-widi/assets/65652924/a04f396a-e918-4bc0-850d-cb79c2add633">


## Installation

Clone repo dari github

```bash
git clone https://github.com/dimaspndw/ionic-app-widi.git 
```

Kemudian buka code di visual studio code. 

Jalankan berikut pada terminal :

```bash
ionic serve
```
Maka akan membuka ionic server pada web browser. 

1. Inspect elemen browser dan pilih tampilan mobile pada inspect element
2. Edit dan sesuaikan dulu tampilan pada mode mobile web
3. Jika sudah maka lanjut ke langkah dibawah ini : 

Jika telah selesai mengubah dan menyesuaikan kode, langkah selanjutnya adalah build aplikasi android.

1. Jalankan command berikut pada terminal
```bash
ionic build
```
<img width="442" alt="Screenshot 2024-05-18 at 19 50 54" src="https://github.com/dimaspndw/ionic-app-widi/assets/65652924/d1408a8a-e52d-4410-ab7f-24d0416b8672">
<img width="914" alt="Screenshot 2024-05-18 at 19 51 08" src="https://github.com/dimaspndw/ionic-app-widi/assets/65652924/5345bfa7-fc56-49f5-89e7-fbeb577e0606">


2. Kemudian jalankan

```bash
ionic cap open android
```
3. Secara otomatis akan auto membuka android studio yang anda punya. Dan membuild APK anda.
4. Selanjutnya tinggal "Run App" pada emulator atau real device anda.


## JIKA MAU MENGUBAH CODE !!
1. Kembali ke visual studio code
2. Hapus folder android
3. Ubah code, jika telah dirasa sesuai jalankan command berikut
```bash
ionic build
```
4. Kemudian jalankan
```bash
ionic cap open android
```
5. Secara otomatis akan auto membuka android studio yang anda punya. Dan membuild APK anda.
6. Selanjutnya tinggal "Run App" pada emulator atau real device anda.
