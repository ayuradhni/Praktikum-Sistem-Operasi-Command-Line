# Praktikum Sistem Operasi Command Line

1. `mkdir SKU`     Membuat directory baru bernama SKU.
2. `ls`     Menampilkan isi directory saat ini.
3. `cd SKU`     Masuk ke directory SKU.
4. `pwd`     Menampilkan lokasi directory saat ini.
5. `touch tugas.txt`     Membuat file kosong bernama tugas.txt.
6. `echo "Halo Ubuntu"`     Menampilkan teks "Halo Ubuntu" pada Terminal.
7. `echo "Tugas Sistem Operasi" > keterangan.txt`     Menulis teks ke dalam file keterangan.txt.
8. `cat keterangan.txt`     Menampilkan isi file keterangan.txt.
9. `cp keterangan.txt salinan.txt`     Menyalin file keterangan.txt menjadi salinan.txt.
10. `ls -l`     Menampilkan isi directory secara detail.
11. `ls -a`     Menampilkan isi directory termasuk file tersembunyi.
12. `mkdir latihan`     Membuat directory baru bernama latihan.
13. `cd latihan`     Masuk ke directory latihan.
14. `touch data.txt`     Membuat file kosong bernama data.txt.
15. `echo "Data latihan" > data.txt`     Menulis teks ke dalam file data.txt.
16. `cat data.txt`     Menampilkan isi file data.txt.
17. `cp data.txt data2.txt`     Menyalin file data.txt menjadi data2.txt.
18. `mv data2.txt hasil.txt`     Mengubah nama data2.txt menjadi hasil.txt.
19. `ls -R`     Menampilkan isi directory dan subdirectory secara rekursif.
20. `du -sh .`     Menampilkan ukuran total directory saat ini.
21. `cd ..`     Kembali ke directory induk.
22. `find . -name "tugas.txt"`     Mencari file bernama tugas.txt.
23. `head keterangan.txt`     Menampilkan bagian awal file keterangan.txt.
24. `tail keterangan.txt`     Menampilkan bagian akhir file keterangan.txt.
25. `wc keterangan.txt`     Menghitung jumlah baris, kata, dan karakter dalam file.
26. `sort keterangan.txt`     Mengurutkan isi file berdasarkan urutan teks.
27. `grep "Tugas" keterangan.txt`     Mencari kata "Tugas" di dalam file.
28. `file keterangan.txt`     Menampilkan jenis atau tipe file.
29. `stat keterangan.txt`     Menampilkan informasi detail mengenai file.
30. `ls -lh`     Menampilkan isi directory secara detail dengan ukuran yang mudah dibaca.
31. `ls -l /home`     Menampilkan isi directory /home secara detail.
32. `find . -maxdepth 2 -type f`     Mencari file sampai kedalaman maksimal dua directory.
33. `ls -l /etc`     Menampilkan isi directory /etc secara detail.
34. `ls -l /usr/bin | head -20`     Menampilkan 20 data pertama dari directory /usr/bin.
35. `ls -l /var/log`     Menampilkan isi directory /var/log.
36. `find /usr/share -maxdepth 1 -type d`     Menampilkan directory yang berada di dalam /usr/share.
37. `uname -a`     Menampilkan informasi lengkap sistem dan kernel Linux.
38. `uptime`     Menampilkan lama sistem telah berjalan dan beban sistem.
39. `df -h`     Menampilkan penggunaan ruang penyimpanan disk.
40. `free -h`     Menampilkan penggunaan RAM dan swap.
41. `lsblk`     Menampilkan informasi perangkat penyimpanan atau block device.
42. `lscpu`     Menampilkan informasi mengenai CPU.
43. `ps aux`     Menampilkan proses yang sedang berjalan pada sistem.
44. `history | tail -20`     Menampilkan 20 command terakhir yang telah dijalankan.
45. `ip addr`     Menampilkan informasi interface dan alamat jaringan.
46. `ip route`     Menampilkan tabel routing jaringan.
47. `who`     Menampilkan pengguna yang sedang login ke sistem.
48. `history`     Menampilkan riwayat command yang telah digunakan.
49. `env`     Menampilkan environment variable pada sistem.
50. `getent passwd`     Menampilkan daftar akun pengguna pada sistem.
51. `date`     Menampilkan tanggal dan waktu saat ini.
52. `whoami`     Menampilkan nama pengguna yang sedang aktif.
53. `hostname`     Menampilkan nama komputer atau hostname.
54. `id`     Menampilkan informasi ID pengguna dan grup.
55. `groups`     Menampilkan grup yang dimiliki atau diikuti pengguna.
56. `cal`     Menampilkan kalender pada Terminal.
57. `du -h --max-depth=1 .`     Menampilkan ukuran directory dan isinya dengan format mudah dibaca.
58. `uname -r`     Menampilkan versi kernel Linux yang digunakan.
59. `ls -d */`     Menampilkan directory yang terdapat pada lokasi saat ini.
60. `which bash`     Menampilkan lokasi program bash.
61. `echo $HOME`     Menampilkan lokasi home directory pengguna.
62. `echo $USER`     Menampilkan nama pengguna yang sedang digunakan.
63. `echo $SHELL`     Menampilkan shell yang sedang digunakan.
64. `ls -F`     Menampilkan isi directory dengan tanda pembeda berdasarkan jenis file.
65. `ls -t`     Menampilkan file berdasarkan waktu modifikasi.
66. `du -sh *`     Menampilkan ukuran setiap file dan directory di lokasi saat ini.
67. `basename "$PWD"`     Menampilkan nama directory saat ini.
68. `dirname "$PWD"`     Menampilkan lokasi directory induk.
69. `printf "Halo dari Ubuntu\n"`     Menampilkan teks menggunakan command printf.
70. `type cd`     Menampilkan informasi mengenai command cd.
