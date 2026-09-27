# Anime Builder — download

Installer ufficiali di **Anime Builder** e file usati dall'aggiornamento automatico dell'app.
Il codice sorgente non è pubblico: questo repository contiene solo le release.

## Scarica l'ultima versione

Vai su **[Releases → Latest](https://github.com/Zaruka96/Anime-Builder-releases/releases/latest)** e scegli il file per il tuo sistema:

| Sistema | File |
|---|---|
| Windows 10/11 (x64) | `Anime-Builder_<versione>_windows-x64-setup.exe` (oppure `.msi`) |
| macOS Apple Silicon (M1…M4) | `Anime-Builder_<versione>_macos-arm64.dmg` |
| macOS Intel | `Anime-Builder_<versione>_macos-x64.dmg` |
| Docker / NAS | `docker pull ghcr.io/zaruka96/anime-builder:latest` |

### Primo avvio

Le app non sono firmate con certificati Apple/Microsoft:

- **macOS**: dopo aver trascinato l'app in Applicazioni, clic destro sull'app → **Apri** → **Apri**. Se macOS dice che l'app è danneggiata: `xattr -dr com.apple.quarantine "/Applications/Anime Builder.app"`.
- **Windows**: se compare SmartScreen, **Ulteriori informazioni** → **Esegui comunque**.

Dopo la prima installazione gli aggiornamenti arrivano direttamente dall'app (controllo a ogni avvio o da Impostazioni → Aggiornamenti).
