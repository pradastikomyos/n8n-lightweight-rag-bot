# n8n-lightweight-rag-bot

**Lightweight RAG-style Telegram Chatbot using n8n, Gemini API, and Google Sheets**

Bot ini merupakan implementasi sederhana dari konsep **Retrieval-Augmented Generation (RAG)**. Menggunakan **n8n** sebagai orchestrator low-code, chatbot ini mengambil data dari **Google Sheets**, menggabungkannya ke dalam prompt, lalu mengirim ke **Gemini API** untuk menghasilkan respons yang relevan.

## ✨ Fitur Utama
- **Retrieval**: Query data dari Google Sheets berdasarkan input pengguna.
- **Augmentation**: Sisipkan data ke dalam prompt untuk memperkaya konteks.
- **Generation**: Gunakan Gemini API untuk menghasilkan jawaban.
- **Short-Term Memory**: Menyimpan histori chat singkat untuk respons yang lebih kontekstual.
- **Telegram Interface**: Respon dikirim langsung via bot Telegram.

## 🧠 Konsep yang Diterapkan
- Adaptasi ringan dari RAG tanpa vector store atau embedding.
- Nggak pakai database — cukup Google Sheets sebagai source of truth.
- Workflow sepenuhnya dibangun di n8n.

## 📸 Dokumentasi Visual
Lihat screenshot dan diagram alur pada folder `/docs` atau langsung di README ini.

## 💡 Catatan
Proyek ini ditujukan untuk pembelajaran dan eksplorasi integrasi LLM dalam alur kerja low-code. Cocok untuk prototype ringan atau integrasi cepat dengan data eksternal yang terstruktur.

---

<img width="1417" height="736" alt="f3abd9ce-79e5-4355-a15c-0be7b2cfb4d9" src="https://github.com/user-attachments/assets/b8f59ee8-6c07-474f-a856-dbec36b41716" />
<img width="749" height="882" alt="Screenshot_9" src="https://github.com/user-attachments/assets/c92bb589-b1c8-41f6-bd7c-01d44c4a2947" />
<img width="588" height="675" alt="Screenshot_10" src="https://github.com/user-attachments/assets/70ec6fd6-c701-4e94-acbf-934263b7de7c" />
<img width="662" height="622" alt="Screenshot_11" src="https://github.com/user-attachments/assets/46e6510c-99f9-4f70-afd1-b03504374a22" />
