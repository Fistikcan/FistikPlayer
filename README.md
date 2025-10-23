# 🎧 Fıstık Player - Akıllı Müzik Oynatıcı / Smart Music Player

> **Önemli Not:** Uygulama geliştirme aşamasında olduğu için hatalar veya eksiklikler içerebilir. Yaşayabileceğiniz aksaklıklar için şimdiden özür dileriz!
>
> **Important Note:** As the application is under development, it may contain bugs or incompleteness. We sincerely apologize in advance for any inconvenience you may experience!

Fıstık Player, Python ve PyQt6 kullanılarak geliştirilmiş modern, masaüstü odaklı bir müzik çalardır. Klasör tabanlı gezinme, senkronize şarkı sözü (LRC) desteği ve gelişmiş oynatma kontrolleri sunar.

Fistik Player is a modern desktop music player developed using Python and PyQt6. It offers folder-based navigation, built-in favorite and playlist management, and synchronized lyric (LRC) support.

## ✨ Temel Özellikler / Core Features

| Özellik (TR) | Feature (EN) |
| :--- | :--- |
| **Akıllı Dizin Gezintisi** | **Smart Directory Navigation** |
| **LIFO (4 → 3 → 2 → 1) Geçmiş** | **LIFO (Last-In, First-Out) History:** Consistent **4 → 3 → 2 → 1** folder navigation. |
| **LRC (Senkronize Söz) Desteği** | **LRC (Synchronized Lyrics) Support** |
| **Kalıcı Veri (Favoriler/Playlist)** | **Persistent Data (Favorites/Playlist)** |
| **Spleeter Entegrasyonu** | **Spleeter Integration** (External vocal separation tool support). |
| **Modern Koyu Tema** | **Modern Dark Theme** |

## 🛠 Kurulum ve Çalıştırma / Setup and Running

### 1. Ön Gereksinimler / Prerequisites

Projeyi çalıştırmak için sisteminizde **Python 3.8 veya üzeri** yüklü olmalıdır. / Python 3.8 or later must be installed on your system.

### 2. Bağımlılıkları Yükleme / Installing Dependencies

Projenin ana dizininde Komut İstemi'ni (CMD) veya terminali açın ve gerekli Python kütüphanelerini kurun: / Open the Command Prompt or terminal in the project's root directory and install the required Python libraries:

```bash
pip install PyQt6 requests mutagen
