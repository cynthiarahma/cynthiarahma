Cynthia Rahmawati - 5311421088 

Modul 4 - Teknik Pencarian Blind Search

1. Tentukan bagaimana algoritma BFS di atas dapat menentukan node ke 8, 6, dan 7.
![image](https://github.com/cynthiarahma/cynthiarahma/assets/149099370/1160bb6b-d055-4b52-8aee-619aebed7843)
Berdasarkan urutan langkah-langkah yang dijelaskan di atas, proses pencarian dengan algoritma Breadth-First Search (BFS) dimulai dari simpul ke-3 (n3) dengan jarak awal 0. Selanjutnya, BFS melanjutkan ke simpul n4 dengan jarak 1 karena n3 memiliki sambungan langsung ke n4. Namun, saat mencapai simpul n4, BFS menemukan bahwa simpul n2 sudah diwarnai GRAY, sehingga tidak melanjutkan ke n2. Selanjutnya, BFS menjelajahi simpul n4 yang memiliki sambungan dengan n5, dan karena n5 belum diwarnai, maka BFS melanjutkan ke n5 dengan jarak 2. Dari n5, BFS juga menemukan sambungan dengan n6 dan n1, yang keduanya belum diwarnai, sehingga melanjutkan ke keduanya dengan jarak yang sama, yaitu 2. Selanjutnya, saat mencapai simpul n6, BFS menemukan bahwa n6 memiliki tetangga n7 dan n8 yang belum diwarnai, sehingga BFS melanjutkan ke keduanya dengan jarak 3. Inilah bagaimana BFS bergerak dari simpul ke simpul dalam rangkaian langkah-langkah yang disebutkan menuju simpul ke-8, 6, dan 7.

2. Ubahlah method static void main sehingga bentuk tree seperti Gambar 4.4 dapat dibentuk. Kemudian tentukan bagaimana algoritma BFS dapat menemukan node 5.
![image](https://github.com/cynthiarahma/cynthiarahma/assets/149099370/e0c5f1a3-4605-426d-a488-dfb23dc78e9b)
Hasil tersebut memvalidasi kesesuaian antara hasil pohon yang dihasilkan oleh program dengan gambar 4.5. Proses dimulai dengan algoritma BFS ketika mencari node 5, di mana langkah pertama adalah memasukkan node 1 ke dalam antrian. Selanjutnya, node 1 akan mengeksplorasi node 2 dan node 3, yang langsung terhubung ke node 1 atau berada pada kedalaman tingkat 1. Proses berlanjut dengan node 3 yang mengeksplorasi node yang memiliki jarak atau kedalaman 2, memeriksa node 4, node 5, node 6, dan node 7. Setelah menemukan node 5, proses akan terus berlanjut sampai semua node yang terhubung dengan node awal telah diperiksa, sehingga node 5 akan ditemukan dan diproses sesuai dengan aturan algoritma BFS.

3. Ubahlah method static void main sehingga bentuk tree seperti Gambar 4.5 dapat dibentuk. Kemudian tentukan bagaimana algoritma BFS dapat menemukan node 9.
![image](https://github.com/cynthiarahma/cynthiarahma/assets/149099370/5e2a39c5-1466-40ed-8e07-51c256e0907f)
Hasil tersebut memverifikasi kesesuaian antara pohon hasil yang dihasilkan oleh program dengan gambar 4.6. Dalam upaya menemukan node 9, algoritma BFS dimulai dengan menempatkan node 1 ke dalam antrian. Selanjutnya, node 1 akan menjelajahi node 2, node 3, dan node 4 yang secara langsung terhubung dengan node 1 atau memiliki kedalaman tingkat 1. Kemudian, node 4 akan menjelajahi node dengan kedalaman 2, dimulai dari pemeriksaan node 5, node 6, node 7, dan node 8. Proses berlanjut dengan node 8, yang akan menjelajahi node 9. Setelah berhasil menemukan node 9, proses akan terus berlanjut untuk memeriksa node 10, node 11, dan node 12 hingga semua node yang terhubung dengan node awal telah diperiksa. Oleh karena itu, pada akhir proses BFS, node 9 akan ditemukan dan diolah sesuai dengan ketentuan algoritma BFS.

4. Ubahlah kode program di atas sehingga bentuk tree seperti Gambar 6 dapat dibentuk. Kemudian tentukan bagaimana algoritma BFS dapat menemukan node C.

