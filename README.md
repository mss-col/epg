# EPG Malaysia OTT

Electronic Program Guide (EPG) untuk Malaysia OTT streaming services.

---

## EPG Links (2-Link Setup untuk Loading Pantas)

Gunakan **kedua-dua** link di bawah dalam IPTV player anda untuk loading optimum.

### 1. Astro + Sooka EPG

```
https://cdn.jsdelivr.net/gh/mss-col/epg@main/astro_epg.xml
```

| Item | Keterangan |
|------|------------|
| Format | XMLTV (.xml) |
| Update | Setiap hari (auto) |
| Coverage | 2 hari ke hadapan |
| Channels | 170+ saluran (Astro + Sooka) |
| Saiz | ~3.5 MB (trimmed dari 7 hari → 2 hari) |

### 2. Unifi TV EPG

```
https://cdn.jsdelivr.net/gh/mss-col/epg@main/unifi_epg.xml
```

| Item | Keterangan |
|------|------------|
| Format | XMLTV (.xml) |
| Update | Setiap hari (auto) |
| Coverage | 2 hari ke hadapan |
| Channels | 60+ saluran Unifi TV |
| Saiz | ~900 KB |

---

## Kenapa 2 Link?

| | 1 Link (Unified) | 2 Link (Recommended) |
|---|---|---|
| Loading | 60-80+ saat | **10-15 saat** |
| Sebab | Sequential download + parse | Parallel download + parse |
| Saiz total | ~5 MB (1 file) | ~4.4 MB (2 file, parallel) |

> IPTV player (OTT Navigator, TiviMate, dll.) download & parse multiple EPG sources secara **serentak**. 2 file kecil lebih pantas dari 1 file besar.

---

## Cara Penggunaan

1. Copy **kedua-dua** link EPG di atas
2. Paste dalam aplikasi IPTV player anda (OTT Navigator, TiviMate, IPTV Smarters, Kodi, dll.)
3. Tambah sebagai 2 EPG source yang berasingan
4. Refresh/reload EPG dalam player

---

## Penafian / Disclaimer

> **PENTING: SILA BACA DENGAN TELITI**

Perkhidmatan EPG ini disediakan **PERCUMA** selagi ianya diselenggara oleh MSS.

### Terma Penggunaan

1. **Tujuan Pendidikan & Penyelidikan**
   - Data EPG ini disediakan semata-mata untuk tujuan **pendidikan (education)** dan **penyelidikan pembangunan (research & development)** sahaja.

2. **Tiada Jaminan**
   - Data disediakan "SEBAGAIMANA ADANYA" (AS-IS) tanpa sebarang jaminan, sama ada tersurat atau tersirat.
   - Kami tidak menjamin ketepatan, kelengkapan, atau kebolehpercayaan data EPG.

3. **Had Liabiliti**
   - Pihak kami (MSS) **TIDAK BERTANGGUNGJAWAB** atas sebarang:
     - Kerugian langsung atau tidak langsung
     - Kerosakan data atau sistem
     - Kehilangan pendapatan atau keuntungan
     - Sebarang tuntutan pihak ketiga
   - Yang timbul daripada penggunaan atau ketidakupayaan menggunakan data dari repositori ini.

4. **Penggunaan Atas Risiko Sendiri**
   - Pengguna bertanggungjawab sepenuhnya atas penggunaan data EPG ini.
   - Penggunaan data ini adalah atas **RISIKO SENDIRI** pengguna.

5. **Hak Cipta & Tanda Dagangan**
   - Semua jenama, logo, dan tanda dagangan adalah hak milik pemilik masing-masing.
   - Kami tidak menuntut pemilikan atas mana-mana kandungan siaran.

6. **Perubahan & Penamatan**
   - Kami berhak untuk mengubah, menggantung, atau menamatkan perkhidmatan ini pada bila-bila masa tanpa notis.

### Persetujuan

Dengan menggunakan data dari repositori ini, anda **BERSETUJU** untuk mematuhi semua terma yang dinyatakan di atas.

---

## Sokongan

Jika anda mendapati EPG ini berguna, sila berikan **Star** pada repositori ini.

---

<p align="center">
  <sub>Diselenggara oleh <b>MSS</b> | Untuk tujuan pendidikan & penyelidikan sahaja</sub>
</p>
