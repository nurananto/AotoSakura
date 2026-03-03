# Ao to Sakura

> Siswa SMA yang sulit berbaur dengan kelasnya, Fujieda Ao.Sepulang sekolah, ia selalu menyambangi perpustakaan lokal, tempat ia bertemu dengan seorang gadis.Gadis itu cerah, polos, dan penuh tawa — kebalikan dari dirinya.Namanya, Hidaka Sakura.Ao perlahan mulai tertarik pada Sakura.Pertemuan itu pun lambat laun berubah menjadi sebuah “cinta”.

---

## Info

| | |
|---|---|
| Judul | Ao to Sakura |
| Judul Alternatif | あおとさくら |
| Author | Kasuka Io |
| Artist | Matsumoto Komikan |
| Tipe | Manga (Hitam Putih) |
| Status | Tamat (Chapter Oneshot) |
| Genre | Drama · Shounen · Comedy · Romance · School Life · Slice of Life |
| Chapter | 1 chapter |

## Link

- [MangaDex](https://mangadex.org/title/7cf10b89-2c28-4df5-9087-39f076e79e4a/ao-to-sakura)
- [Raw](https://www.manga-up.com/titles/1208)

---

## Struktur

```
AotoSakura/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)