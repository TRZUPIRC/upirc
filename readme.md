<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F0FF,50:7B2FFF,100:FF00E5&height=220&section=header&text=UPirc&fontSize=84&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=IRC%20Client%20for%20Android%20%E2%80%A2%20mIRC-style%20%E2%80%A2%20Neon%20Tech&descSize=18&descAlignY=62" alt="UPirc banner" width="100%"/>

<img src="assets/logo.png" alt="UPirc logo" width="140"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=900&color=00F0FF&center=true&vCenter=true&width=700&lines=%2Fconnect+irc.upirc.com+6697+%F0%9F%94%92;Klien+IRC+Android+bergaya+mIRC;TLS+%E2%80%A2+SASL+%E2%80%A2+Multi-server+%E2%80%A2+Moderasi+lengkap;Join+%23UPirc+%E2%80%94+ngobrol%2C+main+game%2C+ketemu+bot" alt="Typing SVG"/>
</a>

<br/>

![Platform](https://img.shields.io/badge/Platform-Android-39FF14?style=for-the-badge&logo=android&logoColor=white&labelColor=0D1117)
![Kotlin](https://img.shields.io/badge/Kotlin-Jetpack%20Compose-7B2FFF?style=for-the-badge&logo=kotlin&logoColor=white&labelColor=0D1117)
![Version](https://img.shields.io/github/v/release/TRZUPIRC/upirc?style=for-the-badge&color=00F0FF&labelColor=0D1117&label=Release)
![TLS](https://img.shields.io/badge/TLS%2FSSL-6697-FF00E5?style=for-the-badge&logo=letsencrypt&logoColor=white&labelColor=0D1117)
![Package](https://img.shields.io/badge/com.trz.upirc-FFB800?style=for-the-badge&labelColor=0D1117)

<br/>

[**⬇️ Download APK**](https://github.com/TRZUPIRC/upirc/releases/latest) &nbsp;•&nbsp; [**📜 Changelog**](#-riwayat-rilis--release-history) &nbsp;•&nbsp; [**💬 Join #UPirc**](#-komunitas--community)

</div>

---

## ⚡ Tentang UPirc

**UPirc** adalah klien **IRC untuk Android** dengan nuansa klasik **mIRC** yang dibungkus tampilan modern bertema neon. Dibuat untuk pengguna IRC serius: stabil, cepat, kaya alat moderasi, dan punya perangkat jaringan bawaan.

> 🇬🇧 **UPirc** is an **Android IRC client** with the classic **mIRC** feel, wrapped in a modern neon-tech interface. Built for serious IRC users: stable, fast, loaded with moderation tools and built-in network utilities.

```text
┌──────────────────────────────────────────────┐
│ [Status] [#UPirc] [#channel] [PM: nick] ...  │
│──────────────────────────────────────────────│
│ * Connected to irc.upirc.com:6697 (TLS)      │
│ <nick> halo semua 👋                         │
│ * nick2 is away (auto-reply aktif)           │
│──────────────────────────────────────────────│
│ > /whois nick_                               │
└──────────────────────────────────────────────┘
```

---

## 🚀 Fitur Utama · Key Features

<table>
<tr>
<td width="50%" valign="top">

### 🌐 Koneksi · Connectivity
- 🗂️ Tab **Status**, channel, **PM**, & **multi-server**
- 💾 Profil server tersimpan
- 🔒 **TLS/SSL** + sambung ulang otomatis
- 🔑 **Login SASL**, **OPER otomatis**
- 🛡️ "Percayai semua sertifikat" per profil

</td>
<td width="50%" valign="top">

### 💬 Chat · Messaging
- ✉️ Pesan, aksi (`/me`), dan **NOTICE**
- 🎨 Warna & format **mIRC**
- 😄 Emoji & **autocomplete nick**
- 🔍 Cari teks & aksi pada baris chat
- 🧾 Riwayat input & template pesan

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ Moderasi · Moderation
- 🚫 Daftar **ban** & **Host Scanner**
- 👥 Aksi kelompok & deteksi **clone**
- 📋 **Shitlist** & akses otomatis
- ⚙️ Pengaturan proteksi channel
- 🏅 Daftar user dengan level akses

</td>
<td width="50%" valign="top">

### 🧰 Utilitas · Utilities
- 💤 **Away** auto-reply
- 🔔 **Notify** list
- ⌨️ Alias perintah kustom
- 👁️ `/seen`
- 📻 Radio opsional

</td>
</tr>
</table>

### 🛰️ Alat Jaringan · Network Toolkit

| Perintah | Fungsi |
|:--|:--|
| `/dns` `/rdns` | Resolusi DNS & reverse DNS |
| `/ip` `/asn` | Info alamat IP & ASN |
| `/dnsbl` | Cek blacklist DNSBL |
| `/ping` `/port` `/tracert` | Uji konektivitas & rute |
| `/ssl` `/http` | Inspeksi sertifikat & HTTP |
| `/domain` `/myip` | Info domain & IP kamu |
| `/lag` `/net` | Latensi & status jaringan |

### 🎮 Khusus #UPirc · #UPirc Exclusives

- 🌈 Tab bergaya **neon**
- 👋 **Kartu sambutan**
- 🕹️ Tombol **Game** (7 permainan)
- 🤖 Bot resmi **Inem** & **Vina**

---

## 📥 Instalasi · Installation

1. Buka halaman [**Releases**](https://github.com/TRZUPIRC/upirc/releases/latest).
2. Unduh file **`.apk`** versi terbaru.
3. Izinkan *Install dari sumber tak dikenal* bila diminta, lalu pasang.
4. Buka UPirc → server bawaan sudah siap. 🎉

## 🔌 Server Bawaan · Default Server

| | |
|:--|:--|
| **Host** | `irc.upirc.com` |
| **Port** | `6697` (TLS) |
| **Channel** | `#UPirc` (Auto-join bawaan, bisa dihapus di Pengaturan) |

```irc
/server irc.upirc.com 6697
/join #UPirc
```

---

## 📜 Riwayat Rilis · Release History

<details open>
<summary><b>🟣 UPirc 1.1.0</b> — Server bawaan, SASL, seleksi teks</summary>

### 🇮🇩 Indonesia

**✨ Baru**
- Server bawaan: `irc.upirc.com` (TLS 6697); tab **#UPirc** selalu pertama setelah Status; #UPirc masuk Auto-join bawaan (bisa dihapus di Pengaturan).
- Seleksi teks Status per kata/karakter: tekan lama, geser pegangan bebas, **Salin** hanya teks terpilih.
- **Login SASL**, **OPER otomatis**, dan "Percayai semua sertifikat" per profil server.
- Perintah operator ditambah, kotak cepat **Identify/Oper**, WHOIS dan `/dns` `/rdns` lebih ringkas.
- Notifikasi koneksi tetap ada, dengan tombol **Keluar**.

**🛠️ Perbaikan**
- Crash layanan latar di Android 15+ dan crash acak saat "Server baru".
- Login SASL tertunda ±15 dtk; tombol "Tutup chat PM" tidak berfungsi.

**🔄 Perubahan**
- Gambar Inem & Vina dihapus.

### 🇬🇧 English

**✨ New**
- Default server: `irc.upirc.com` (TLS 6697); **#UPirc** tab always right after Status; #UPirc is in Auto-join by default (removable in Settings).
- Character-level text selection in Status: long-press, drag handles freely, **Copy** copies only the selected text.
- **SASL login**, **auto OPER**, and "Trust all certificates" per server profile.
- More operator commands, quick **Identify/Oper** boxes, tidier WHOIS and `/dns` `/rdns`.
- Connection notification stays pinned, with an **Exit** button.

**🛠️ Fixes**
- Background service crash on Android 15+ and random crash on "New server".
- SASL login delayed ~15 s; "Close PM" button did nothing.

**🔄 Changes**
- Inem & Vina artwork removed.

</details>

<details>
<summary><b>🔵 UPirc 1.0.0</b> — Rilis pertama · First release</summary>

### 🇮🇩 Indonesia

Rilis pertama: klien IRC Android bergaya mIRC.
- Tab Status, channel, pesan pribadi (PM), dan multi-server; profil server tersimpan.
- Koneksi TLS/SSL, sambung ulang otomatis, daftar user dengan level akses.
- Pesan, aksi, dan NOTICE; warna/format mIRC, emoji, autocomplete nick, cari dan aksi pada baris chat.
- Kelola channel dan moderasi: daftar ban, Host Scanner, aksi kelompok, deteksi clone, shitlist, akses otomatis, pengaturan proteksi.
- Away auto-reply, Notify list, alias perintah kustom, /seen, riwayat input, template pesan, radio opsional.
- Alat jaringan: `/dns` `/rdns` `/ip` `/asn` `/dnsbl` `/ping` `/port` `/tracert` `/ssl` `/http` `/domain` `/myip` `/lag` `/net`.
- Khusus #UPirc: tab bergaya neon, kartu sambutan, tombol Game (7 permainan), dan bot resmi Inem & Vina.

### 🇬🇧 English

First release: an mIRC-style IRC client for Android.
- Status, channel, private message (PM) tabs and multi-server; saved server profiles.
- TLS/SSL, auto-reconnect, user list with access levels.
- Messages, actions and NOTICE; mIRC colors/formatting, emoji, nick autocomplete, chat search and line actions.
- Channel management and moderation: ban list, Host Scanner, group actions, clone detection, shitlist, auto access, protection settings.
- Away auto-reply, Notify list, custom command aliases, /seen, input history, message templates, optional radio.
- Network tools: `/dns` `/rdns` `/ip` `/asn` `/dnsbl` `/ping` `/port` `/tracert` `/ssl` `/http` `/domain` `/myip` `/lag` `/net`.
- #UPirc extras: neon-styled tab, welcome card, Game button (7 games), and the official Inem & Vina bots.

</details>

---

## 🧪 Teknologi · Tech Stack

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![IRC](https://img.shields.io/badge/Protocol-IRC-00F0FF?style=flat-square)
![SASL](https://img.shields.io/badge/Auth-SASL-FF00E5?style=flat-square)
![TLS](https://img.shields.io/badge/Security-TLS%2FSSL-39FF14?style=flat-square)

---

## 💬 Komunitas · Community

Gabung dan ngobrol langsung dengan pengguna lain, main game, dan kenalan dengan bot **Inem** & **Vina**:

```irc
Server  : irc.upirc.com
Port    : 6697 (TLS)
Channel : #UPirc
```

---

<div align="center">

**Dibuat dengan ❤️ dan ☕ oleh [TRZUPIRC](https://github.com/TRZUPIRC)**

<sub>Jika UPirc bermanfaat, beri ⭐ pada repo ini!</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF00E5,50:7B2FFF,100:00F0FF&height=110&section=footer" width="100%" alt="footer"/>

</div>
