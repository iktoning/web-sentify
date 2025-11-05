## Cara Menjalankan aplikasi

Untuk menjalankan aplikasi, ikuti langkah-langkah berikut ini:

1. Masuk ke terminal
2. Install poetry dengan mengetik "pip install poetry"
3. Clone project repository github dengan mengetik "git clone "
4. Masuk ke direktori "web-sentify" dengan mengetik "cd sentify-web"
5. Masuk ke virtual environment dengan mengetik "poetry shell"
6. Buat file `.env` berdasarkan `.env.example` yang disediakan:

- Untuk Windows ketik "copy .env.example .env"
- Untuk Linux ketik "cp .env.example .env"

7. Konfigurasikan file `.env` dengan pengaturan yang diperlukan.
8. Install dependencies project dengan mengetik "poetry install"
9. Aplikasi sudah bisa dijalankan. Untuk menjalankan aplikasi ketik "cd main" dan ketik lagi "flask run"
10. Aplikasi sudah bisa digunakan.
