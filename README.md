# Chapter 1. Setup Environment React Native

## Mobile Application Development, Semester 2, Tahun Akademik 2023/2024

## #Exercise 01

Pada Chapter ini kita akan melakukan instalasi [react native]. Pada latihan ini anda diminta untuk menginstall React Native CLI (Bukan Expo) dilaptop/PC masing-masing, dimana langkah-langkahnya adalah sebagai berikut:

- Install Node, JDK
- Install Android Studio & SDK
- Konfigurasi tambahan (khusus yang menggunakan processor [AMD])
- Configure the ANDROID_HOME environment variable & Add platform-tools to Path
- Install Android Emulator (optional - bisa dilewati jika anda ingin menjalankan aplikasi langsung dari hp. Baca dokumentasi [running on device])
- Create project React Native menggunakan npx
- Run project

## Status Instalasi

| Langkah-langkah                           | Status | Versi |
| ----------------------------------------- | ------ | ----- |
| Instalasi Node                            |done    |  v18.17.1     |
| Instalasi JDK                             |done    |   17    |
| Android Studio                            |done    | Android Studio Hedgehog 1013.1.1 patch 1|
| SDK                                       |done    |   29    |
| ANDROID_HOME & Add platform-tools to Path |done    | -     |
| Android Emulator (opt)                    |done    | Pixel_3a_API_34_extentesion_level_7_x86_64   |
| Create Project RN using npx               |done    | -     |
| Run Project on Emulator / Device          |done    11| -     |

Silahkan update status instalasi anda, apabila sudah terinstall silahkan isi versinya:
untuk mengetahui versi node ketik dari cmd (node -v) untuk mengetahui versi JDK ketik dari cmd (java --version).
Sebagai contoh :


## Langkah-langkah Pengumpulan Latihan

- Fork project github ini. Ada terdapat 3 branch yaitu: master, parallel-a, parallel-b, parallel-c
- Cloning repository hasil forking ke local laptop/PC.
- Dari local laptop/PC anda buat branch baru dengan nama sesuai dengan nama diikuti oleh nim. contoh: johndoe_105022110001. Dan masuk ke dalam branch tersebut
- Duplicate file README.md dan rename file tersebut sama seperti nama branch. contoh: johndoe_105022110001.md 
- Edit baru tersebut dengan mengisi status instalasi pada tabel yang sudah disediakan.
- git add dan commit dengan commit message "adding johndoe_105022110001.md" dan git push ke branch yang baru dibuat
- lakukan pull request ke dalam branch sesuai dengan parallel kelas anda. (Bukan Branch Master)

  [react native]: https://reactnative.dev/docs/environment-setup
  [running on device]: https://reactnative.dev/docs/running-on-device
  [amd]: https://android-developers.googleblog.com/2018/07/android-emulator-amd-processor-hyper-v.html
  [openjdk 11.0.5 2019-10-15]: https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/downloads-list.html
