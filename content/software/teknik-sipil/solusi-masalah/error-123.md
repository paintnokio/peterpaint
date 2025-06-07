---
title: "Mengatasi Error 123"
date: 2025-06-07
tags: 
  - autocad
  - error
  - solusi
---

## Gejala
Muncul pesan error:

> [!WARNING]
> FATAL ERROR: Unhandled Exception 123.

## Penyebab
Terjadi konflik antara versi AutoCAD dan driver grafis

```markdown {filename=Solusi}
1. Update driver VGA ke versi terbaru
2. Jalankan AutoCAD sebagai administrator
3. Tambahkan parameter di shortcut:
   `"C:\Program Files\Autodesk\AutoCAD 2025\acad.exe" /nohardware`
4. Jika masih error, gunakan [Autodesk Clean Uninstall Tool](https://www.autodesk.com/support/clean-uninstall-tool).
```