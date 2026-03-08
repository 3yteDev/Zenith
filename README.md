# Zenith

SA-MP / open.mp Launcher & Anti-Cheat Solution

## Structure

zenith/
├── api/          → Rust + Axum (Backend API)
├── launcher/     → C# + WPF (PC Launcher)
├── anticheat/    → Rust (Anti-Cheat)
├── server/       → Pawn (open.mp gamemode)
├── admin/        → React + Tailwind (Web Admin)
├── bot/          → discord.js (Discord Bot)
└── tools/        → Rust CLI (Manifest Generator)

## Stack

- API        : Rust + Axum + SQLx + Redis
- Launcher   : C# + WPF + Rust FFI
- Anti-Cheat : Rust + windows-rs
- Server     : Pawn (open.mp)
- Admin      : React + Tailwind
- Bot        : discord.js
- DB         : MySQL + Redis
- Files      : Cloudflare R2 + Backblaze B2