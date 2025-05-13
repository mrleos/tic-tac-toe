# 🎮 One Piece Tic Tac Toe Game  
**Tic Tac Toe bertema karakter One Piece dengan animasi, suara, dan karakter pilihan!**

## Deskripsi  
Game Tic Tac Toe interaktif dengan sentuhan tema **One Piece**. Pemain dapat:
- Memasukkan nama pemain (`X` dan `O`)
- Memilih karakter ikonik seperti **Luffy**, **Zoro**, atau **Sanji**
- Menikmati musik latar dan efek suara karakter
- Melihat animasi kemenangan dengan GIF

Dibuat dengan **HTML**, **CSS (Bootstrap)**, dan **JavaScript** murni tanpa framework tambahan.

---

## Fitur Utama  
✅ Input nama pemain  
✅ Seleksi karakter One Piece (Luffy, Zoro, Sanji)  
✅ Animasi hover pada gambar karakter  
✅ Efek suara karakter saat dipilih  
✅ Musik latar (BGM) yang bisa dimute/unmute  
✅ Tampilan papan Tic Tac Toe responsif  
✅ Modal animasi kmenangan dengan GIF  
✅ Tombol reset dan main ulang  

---

## Demo  
![Demo One Piece Tic Tac Toe](/assets/images/demo1.png )  
![Demo One Piece Tic Tac Toe](/assets/images/demo2.png )  

---

## Cara Menjalankan  
1. **Clone repositori** atau unduh file `index.html`  
2. Pastikan struktur folder berikut tersedia:
/assets
/images
- bg3.jpg (latar belakang)
- pzoro.jpg, pluffy.jpg, Sanji.jpg (gambar kepala karakter)
- czoro.jpg, cluffy.jpg, csanji.jpg (gambar full body)
- winner.gif (animasi kemenangan)
/sound
- backsound.mp3 (musik latar)
- zoro.mp3, luffy.mp3, sanji.mp3 (efek suara karakter)
3. Buka file `index.html` dengan browser  

---

## Cara Menggunakan  
1. **Masukkan nama pemain** untuk `X` dan `O`  
2. **Pilih karakter** untuk kedua pemain dari daftar One Piece  
3. Mainkan Tic Tac Toe!  
- Klik kotak untuk menempatkan karakter  
- Modal akan muncul saat ada pemenang atau seri  
4. Gunakan tombol **Reset** untuk mengulang permainan  
5. Aktifkan/mematikan musik latar dengan tombol **Mute/Unmute**

---

## Kustomisasi  
### 1. Menambah/Mengubah Karakter  
Edit objek `characters` di JavaScript:  
```javascript
const characters = {
 1: { 
     profile: 'assets/images/pzoro.jpg', // Gambar kepala
     fullBody: 'assets/images/czoro.jpg', // Gambar full body
     sound: 'assets/sound/zoro.mp3' // Efek suara
 },
 // Tambahkan karakter lain di sini
};
