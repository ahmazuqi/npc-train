# NPC Kereta By Noctyx

Sistem NPC Kereta untuk SA-MP / Open.MP menggunakan file recording (.rec) untuk menjalankan kereta otomatis di dalam server.

## Features

- NPC kereta otomatis
- Menggunakan file recording (.rec)
- Mendukung beberapa NPC sekaligus
- Kompatibel dengan SA-MP dan Open.MP
- Source code Pawn disertakan

## File Structure

```text
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
```

## Installation

1. Extract semua file ke direktori server.
2. Pastikan seluruh file NPC berada di folder:

```text
npcmodes/
```

3. Pastikan file recording berada di folder:

```text
npcmodes/recordings/
```

4. Jalankan NPC menggunakan:

```pawn
ConnectNPC("Train_1", "system_kereta");
ConnectNPC("Train_2", "system_kereta2");
ConnectNPC("Train_3", "system_kereta3");
ConnectNPC("Train_4", "system_kereta4");
ConnectNPC("Train_5", "system_kereta5");
```

## Requirements

- SA-MP 0.3.7 R2 atau lebih baru
- Open.MP (Recommended)
- NPC Recording Support

## Credits

**Author:** Noctyx

**Recording:** [SAP]Kereta[40]

## License

Free to use and modify.

Please keep the original credits when redistributing this project.
