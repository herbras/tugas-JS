# README

## Prasyarat

Pastikan `bun` sudah terinstal.

Jika belum, jalankan perintah berikut di terminal:

```bash
powershell -c "irm bun.sh/install.ps1|iex"

bun --version
```

## Struktur Proyek

```
- utils.js
- main.js
```

* `utils.js` berisi fungsi-fungsi utilitas (add, divide, createUser, greetUser, dll.).
* `main.js` berisi contoh penggunaan fungsi-fungsi dari `utils.js`.

## Menjalankan Proyek

Di dalam folder yang sama, jalankan perintah:

```bash
bun main.js
```

atau sebagai alternatif:

```bash
bun run main.js
```

> Bun akan mengeksekusi `main.js` dan menampilkan hasilnya di terminal.
