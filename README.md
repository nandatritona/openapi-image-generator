# OpenAI Image Generator

Ini adalah generator gambar sederhana yang dibangun dengan node.js dan ekspres yang digunakan [OpenAI's Dall-E models](https://beta.openai.com/docs/guides/images) untuk menghasilkan gambar.

![Screenshot 2023-04-18 143424](https://user-images.githubusercontent.com/75880817/232705226-b546d357-93da-4c28-8783-9cbbf80929ca.png)

## Usage

Buat file `.env` untuk setting API

Dapatkan API KEY di [OpenAI](https://beta.openai.com/) lalu tambahkan ke `.env` file.

Instal dependensi

```bash
npm install
```

Jalankan server

```bash
npm start
```

Visit `http://localhost:5001`di browser Anda.

Titik akhir ada di `POST http://localhost:5001/openai/generateimage`.
