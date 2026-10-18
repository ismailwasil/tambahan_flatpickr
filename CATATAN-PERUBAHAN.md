# Ganti FullCalendar -> Flatpickr

File baru
- assets/js/tampil-flatpickr-for-item-aset.js  (gantikan tampil-fullCalendar-For-item-aset.js)

File diubah (timpa file lama dengan struktur folder yang sama)
- application/views/templates/pages/lasada/bus_pemda.php, bpu_ktp.php, bpu_spg.php, mess_sby.php, pesanggerahan.php
- application/views/templates/pages/lasada/admin_item_aset.php
- application/views/templates/page_footer.php

Tidak diubah
- Lasada.php (get_events tetap sama), semua modal dan form, admin_Bus_Pemda.php, admin_BPU_spg.php (tidak dipanggil controller mana pun)
- Baris jquery.min.js dari folder assets-fullcalendar sengaja dibiarkan agar urutan jQuery di halaman tidak berubah.

Setelah semua halaman diuji, folder assets/assets-fullcalendar bisa dihapus
(kecuali jquery.min.js bila masih dipakai) dan assets/js/tampil-fullCalendar-For-item-aset.js.
