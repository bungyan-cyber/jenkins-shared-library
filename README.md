# Jenkins Shared Library


**Jenkins Shared Library** adalah perpustakaan berbagi untuk proyek Jenkins yang menyediakan serangkaian fungsi, langkah-langkah, dan utilitas untuk digunakan secara bersama-sama dalam pipa CI/CD Anda.

## Pengantar

Proyek ini dibuat untuk memfasilitasi pengembangan dan pemeliharaan pipa CI/CD di Jenkins. Dengan menggunakan Shared Library, Anda dapat dengan mudah mendefinisikan langkah-langkah umum, menyederhanakan konfigurasi Jenkinsfile, dan memastikan konsistensi antara berbagai pipa proyek.

## Fitur Utama

- **Fungsi Terstandarisasi:** Sekumpulan fungsi yang dapat digunakan kembali untuk tugas umum dalam CI/CD.
- **Langkah-langkah Jenkinsfile:** Definisikan langkah-langkah umum dalam berkas Jenkinsfile Anda dengan mudah.
- **Dokumentasi yang Jelas:** Dokumentasikan setiap fungsi dan langkah-langkah untuk memudahkan penggunaan dan kontribusi.

## Penggunaan

1. Tambahkan repository ini sebagai submodule pada proyek Jenkins Anda:

    ```bash
    git submodule add https://github.com/bungyan-cyber/jenkins-shared-library.git vars/jenkinsSharedLibrary
    ```

2. Import dan gunakan fungsi atau langkah-langkah yang didefinisikan dalam Shared Library di Jenkinsfile proyek Anda:

    ```groovy
    @Library('jenkinsSharedLibrary') _
    // Panggil fungsi atau langkah-langkah dari Shared Library di sini
    ```

## Kontribusi

Kami menyambut kontribusi dari komunitas. Jika Anda ingin berkontribusi pada proyek ini, silakan ikuti langkah-langkah berikut:

1. Fork repositori ini.
2. Buat cabang baru (`git checkout -b fitur-baru`).
3. Lakukan perubahan Anda dan commit (`git commit -am 'Menambahkan fitur baru'`).
4. Push ke cabang (`git push origin fitur-baru`).
5. Buat permintaan tarik (pull request) baru.

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).
