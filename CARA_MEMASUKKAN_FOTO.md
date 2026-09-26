# 📸 CARA MEMASUKKAN FOTO ANDA

## Metode Otomatis (Termudah)

Letakkan foto Anda di folder yang sama dengan file `index.html` dengan salah satu nama berikut:

```
foto.jpg       ← direkomendasikan
foto.png
photo.jpg
profile.jpg
fadilatul.jpg
fadilatul.png
```

File HTML akan **otomatis mendeteksi dan menampilkan foto Anda** di:
- 🖼 Cover
- 👤 Astronaut Profile
- 🏁 Closing

## Metode Manual (Jika Otomatis Tidak Berhasil)

Buka `index.html` dengan text editor (Notepad++, VS Code, dll), kemudian:

1. Cari teks: `cover-photo-el`
2. Ganti elemen `<div id="cover-photo-el" ...>` dengan:
   ```html
   <img id="cover-photo-el" src="foto.jpg" style="width:160px;height:160px;border-radius:50%;object-fit:cover;border:3px solid rgba(201,169,110,0.5);box-shadow:0 0 40px rgba(201,169,110,0.25);" />
   ```

Lakukan hal yang sama untuk:
- `profile-photo-el` (ukuran 180px)
- `closing-photo-el` (ukuran 120px)

## Format Foto yang Disarankan

- Format: JPG atau PNG
- Rasio: 1:1 (persegi) atau close-up wajah
- Resolusi minimal: 400x400 px
- Background: berwarna solid atau bersih lebih baik

---

> 💡 **Tips**: Foto dengan background netral/polos akan terlihat lebih elegan dengan efek border dan glow yang ada.
