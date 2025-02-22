# Instalasi-Windows-11
Penjelasan dan Langkah-langkah

1. Persyaratan Sistem Minimum Windows 11
Sebelum melakukan instalasi, pastikan komputer memenuhi spesifikasi minimum:
	•	Motherboard: Minimal dengan Slot RAM DDR3 atau lebih tinggi.
	•	Motherboard Firmware Sistem: UEFI, mendukung Secure Boot.
	•	TPM (Trusted Platform Module): Versi 2.0. “PTT / fTPM”
	•	Prosesor: 1 GHz atau lebih cepat, dengan 4 atau lebih core pada prosessor.
	•	Bit: 64-bit / arsitektur x64
	•	RAM: Minimal 4 GB dengan Tipe DD3 atau lebih tinggi.
	•	Harddisk / SSD: Minimal memiliki 64 Gb ruang kosong setelah installasi.
	•	Kartu Grafis (VGA): DirectX 12 atau lebih baru dengan driver WDDM 2.0., VRAM 128 Mb atau lebih besar.
	•	Layar: Resolusi minimal 720p, ukuran layar 9 inci atau lebih besar.
	•	Koneksi Internet: Dibutuhkan untuk aktivasi dan pembaruan Windows.
2. Persiapan Instalasi
Alat yang Dibutuhkan
	•	File ISO Windows 11 (dapat diunduh dari situs resmi Microsoft).
	•	Rufus atau Media Creation Tool untuk membuat bootable USB.
	•	Flashdisk minimal 8GB.
	•	Komputer atau laptop yang mendukung Windows 11, dengan tersedianya Secure Boot,
		Platform Trust Technology (PTT) untuk prosessor INTEL / Firmware Trusted Platform Modul (fTPM) untuk prosessor AMD
		pada settingan biosnya.

# Membuat Bootable USB
1.	Gunakan Media Creation Tool
	o	Unduh Media Creation Tool dari situs Microsoft.
	o	Jalankan aplikasi dan pilih "Create installation media for another PC".
	o	Pilih bahasa, edisi, dan arsitektur (64-bit).
	o	Pilih "USB flash drive" dan pilih flashdisk yang akan digunakan.
	o	Tunggu proses selesai dan flashdisk siap digunakan.
2.	Gunakan Rufus
	o	Unduh Rufus dari situs resminya.
	o	Hubungkan flashdisk ke komputer.
	o	Buka Rufus dan pilih flashdisk di bagian "Device".
	o	Klik "Select" dan pilih file ISO Windows 11.
	o	Pastikan "Partition Scheme" menjadi UEFI: GPT 
	o	Klik "Start" dan tunggu hingga proses selesai.

3. Proses Instalasi Windows 11
	Langkah-langkah Instalasi
	1.	Masuk ke BIOS
		o	Sambungkan bootable USB/DVD.
		o	Nyalakan komputer dan tekan tombol F2, F12, Del, atau Esc untuk masuk BIOS (tergantung merek laptop/PC).
		o	Pastikan PTT / fTPM ter enable/aktif.
		o	Pastikan Secure Boot ter enable/aktif.
		o	Ubah Boot Order agar USB/DVD menjadi prioritas pertama.
		o	Simpan perubahan dan keluar dari BIOS / Save Change & Exit.
	2.	Memulai Instalasi
		o	Tekan Enter Ketika muncul Press any key to boot from CD/DVD or USB…
		o	Tunggu hingga layar instalasi Windows 11 muncul.
	3.	Proses Instalasi Windows 11
		o	Pilih bahasa, waktu, dan metode input keyboard, lalu klik Next.
		o	Klik Install Now.
		o	Jika diminta, masukkan Product Key, atau klik I don’t have a product key untuk melanjutkan tanpa aktivasi.
		o	Pilih edisi Windows 11 yang akan diinstal, lalu klik Next.
		o	Centang I accept the license terms, lalu klik Next.
		o	Pilih Custom: Install Windows only (advanced).
		o	Pilih partisi tempat Windows akan diinstal: 
				Jika ada partisi lama, hapus dan buat partisi baru.
				Pilih partisi yang telah disiapkan, lalu klik Next.
		o	Tunggu proses instalasi selesai (PC akan restart beberapa kali).
	4.	Konfigurasi Awal Windows 11
		o	Pilih negara dan layout keyboard.
		o	Hubungkan ke WiFi jika diperlukan.
		o	Pilih Pengaturan Akun: 
				Masuk dengan akun Microsoft atau gunakan akun lokal.
		o	Atur Pengaturan Privasi.
		o	Tunggu Windows menyelesaikan pengaturan.
	4. Instalasi Driver dan Software Pendukung
		Setelah Windows 11 terinstal:
			•	Periksa driver yang belum terinstal melalui Device Manager.
			•	Unduh dan instal driver resmi dari situs produsen laptop/PC.
			•	Instal aplikasi penting, seperti browser, Office, dan antivirus.
			•	Lakukan update Windows untuk memastikan sistem terbaru.
	5. Troubleshooting Umum
		•	Windows 11 tidak bisa diinstal: Periksa apakah PC memenuhi syarat TPM 2.0 dan Secure Boot.
		•	USB boot tidak terdeteksi: Pastikan format partisi dan mode boot sesuai (UEFI/GPT atau Legacy/MBR).
		•	PC restart berulang kali: Coba ulangi proses instalasi dengan menghapus partisi lama.
________________________________________
