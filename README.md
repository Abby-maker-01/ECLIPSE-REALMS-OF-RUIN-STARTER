# ECLIPSE: REALMS OF RUIN — Android Starter

Prototype RPG pixel top-down dengan movement, eksplorasi wilayah, level/XP/rank, stats, ras, 10 class, quest, monster, koin, dan inventori.

## Penting
Ini adalah starter game yang bisa dijalankan di browser dan dibungkus menjadi APK. **Belum merupakan MMORPG online**: multiplayer real-time, akun/login, penyimpanan server, chat, party/guild, PvP, dan anti-cheat membutuhkan server backend yang belum disertakan. Label MODE LOKAL sengaja ditampilkan agar tidak mengklaim online palsu.

## Jalankan lokal
Buka `index.html` di browser modern.

## Build APK melalui GitHub Actions
Workflow Android dapat ditambahkan setelah mengunggah isi ZIP ini ke repo GitHub. Untuk Capacitor Android, biasanya proyek Android dibuat di lingkungan Linux/CI menggunakan `npx cap add android`, lalu build Gradle. Pastikan Node dan Java cocok dengan versi Capacitor yang dipakai.

## Fitur prototype
- Top-down pixel-style world canvas dan kontrol sentuh/keyboard
- 4 wilayah, monster, EXP, level-up, rank E sampai S
- 10 class: Fighter, Mage, Assassin, Marksman, Tank, Support, Berserker, Ranger, Summoner, Paladin
- 10 ras: Human, Elf, Dark Elf, Dwarf, Beastkin, Dragonkin, Demon, Angel, Undead, Spirit
- Stats STR, AGI, INT, VIT, DEX, LUK; quest, loot, koin, potion
