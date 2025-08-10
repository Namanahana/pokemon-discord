# 🐉 Async Pokémon Bot

Bot Pokémon berbasis **Python** yang menggunakan [PokeAPI](https://pokeapi.co/) untuk mengambil data Pokémon secara asynchronous dengan `aiohttp` & `asyncio`.

---

## 📦 Fitur
- Ambil data Pokémon (!go) (nama, XP, abilities, tipe, gambar).
- Sistem pertarungan (!attack):
  - **Wizard**: Kadang memakai perisai.
  - **Fighter**: Memiliki serangan super.
- Sistem makan (!feed) untuk memulihkan HP setelah waktu tertentu.

---

## 📜 Kelas
- **Pokemon** → Kelas dasar, menyimpan data & fungsi umum.
- **Wizard** → Turunan `Pokemon` dengan peluang perisai.
- **Fighter** → Turunan `Pokemon` dengan serangan super.

---

## Contoh

![contoh tampilan bot pokemon](https://github.com/user-attachments/assets/94ebd223-ddc6-4abc-b36f-16c89637b887)
