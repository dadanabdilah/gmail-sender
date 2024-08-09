## Gmail SMTP Sender API

**Konfigurasi ENV**:
   - Ubah nama file  `env` menjadi `.env`.
   - Lalu ubah nilai EMAIL_USER dan EMAIL_PASS pada file env sesuai akun anda

Setelah melakukan konfigurasi end point API projek sudah bisa diakses `http://localhost:3000/send-email` untuk testing dengan postman dengan mengirimkan data json seperti berikut :
`{ "to": "email@example.com", "subject": "Test Email", "text": "TTest email sent from the Node.js API." }`