# StreamIMDB — LG webOS Homebrew Repository

Homebrew Channel repository za instalaciju **StreamIMDB** aplikacije na LG webOS TV.

## 📺 Instalacija

### Metoda 1: Homebrew Channel Repository (preporučeno)

1. Na TV-u otvori **Homebrew Channel**
2. Idi na **Settings (⚙️) → Repositories → Add repository**
3. Unesi URL:
   ```
   https://raw.githubusercontent.com/TVOJ_USERNAME/streamimdb-webos/main/apps.json
   ```
4. Potvrdi i sačekaj da se repo učita
5. Pronađi **StreamIMDB** u listi i klikni **Install**

### Metoda 2: Direktna IPK instalacija

1. Preuzmi `streamimdb_1.0.0_all.ipk`
2. Prebaci na USB stick
3. U Homebrew Channel → **Install from local file**

## 📦 Sadržaj

| Fajl | Opis |
|------|------|
| `apps.json` | Homebrew Channel repo manifest |
| `streamimdb_1.0.0_all.ipk` | Instalabilni webOS paket |

## ℹ️ O aplikaciji

- **ID:** `ru.streamimdb.app`
- **Verzija:** 1.0.0
- **Tip:** Web app (otvara streamimdb.ru u fullscreen-u)
- **Back tipka:** navigira unazad kroz stranicu

## ⚙️ Kompatibilnost

- LG webOS 3.x, 4.x, 5.x, 6.x, 22, 23, 24
- Potreban: [Homebrew Channel](https://github.com/webosbrew/homebrew-channel)
