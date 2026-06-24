NPC Kereta By Noctyx

Sistem NPC Kereta untuk SA-MP / Open.MP menggunakan NPC Recorder (.rec) dan beberapa NPC mode yang berjalan secara bersamaan untuk mensimulasikan perjalanan kereta otomatis.

Features

- NPC Kereta otomatis
- Menggunakan file recording (.rec)
- Mendukung beberapa NPC kereta
- Mudah dipasang pada server SA-MP maupun Open.MP
- Source code Pawn (.pwn) disertakan

File Structure

npckeretabynoctyx/
│
├── system_kereta.pwn
│
└── npcmodes/
    ├── system_kereta.pwn
    ├── system_kereta.amx
    ├── system_kereta2.pwn
    ├── system_kereta2.amx
    ├── system_kereta3.pwn
    ├── system_kereta3.amx
    ├── system_kereta4.pwn
    ├── system_kereta4.amx
    ├── system_kereta5.pwn
    ├── system_kereta5.amx
    │
    └── recordings/
        └── [SAP]Kereta[40].rec

Installation

1. Ekstrak seluruh file ke folder server SA-MP/Open.MP.
2. Salin file NPC ke folder:

npcmodes/

3. Pastikan file recording berada di:

npcmodes/recordings/

4. Tambahkan NPC pada script server menggunakan:

ConnectNPC("NamaNPC", "system_kereta");

Sesuaikan dengan nama NPC mode yang digunakan:

system_kereta
system_kereta2
system_kereta3
system_kereta4
system_kereta5

5. Jalankan server dan pastikan plugin NPC aktif.

Requirements

- SA-MP 0.3.7 atau lebih baru
- Open.MP (recommended)
- NPC Recorder Support

Credits

- Original Author: Noctyx
- Recording: [SAP]Kereta[40]

License

Gunakan dan modifikasi sesuai kebutuhan server Anda.
Tetap berikan kredit kepada author asli apabila digunakan secara publik.
