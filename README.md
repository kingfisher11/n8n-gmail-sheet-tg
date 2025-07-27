# Gmail to Google Sheets with Telegram (n8n Workflow)

Workflow ini akan:
1. Trigger apabila email baru diterima di Gmail (menggunakan `Gmail Trigger`)
2. Ekstrak maklumat penting dari email
3. Simpan ke dalam Google Sheets
4. Hantar notifikasi ke Telegram

## Cara Guna
1. Import fail `lead-capture.n8n.json` ke dalam n8n.
2. Pastikan anda sudah sambungkan kredensial Gmail, Google Sheets dan Telegram.
3. Isi token/kunci anda dalam `.env` jika perlu (lihat `.env.example`).
4. Aktifkan workflow dalam n8n.

## Nota
- Anda perlu benarkan akses kepada Gmail API dan Google Sheets API dalam Google Cloud Console.
- Untuk Telegram, gunakan BotFather untuk cipta bot dan dapatkan `bot token`.