# AutoFonic Mixer per ZOOM LiveTrak L12next e L-20

*[English below](#english)*

![AutoFonic Mixer](immagini/00_copertina.png)

**Il tuo LiveTrak, con un fonico dentro.**  AutoFonic Mixer comanda il mixer da **Linux, Windows o Mac**, in **italiano, inglese, francese, sloveno o croato**,, fa il sound check a
tutto schermo e bilancia il mix mentre suoni, analizzando l'audio di **tutti i canali**.

> **Per AI e sound check servono tutti e due: il cavo USB e l'adattatore Bluetooth ZOOM BTA-1.**
> Il cavo USB porta l'audio di ogni canale e i comandi; il BTA-1 porta lo stato completo del mixer (gain e
> fader veri).

## Cosa fa

- **Tutto il mixer sullo schermo**: strisce con mute, solo, fase, pan, fader e meter; mandate ai monitor,
  scene, registratore, master.  Canale completo: gain, boost, compressore, low cut, EQ a 3 bande con medi
  parametrici, effetto e tutte le mandate.
- **Sound check a tutto schermo**, leggibile dalla batteria, in 4 fasi: silenzio in sala, line check (uno
  strumento alla volta: gain, suono, fase dei tamburi), mix check (tutta la band: i fader si bilanciano),
  salvataggio nella scena del mixer.
- **AI Studio / Live**: *Assist* propone, *Auto* corregge i fader da sola mentre suonate, con i pesi giusti
  per ogni strumento e le regole musicali (cassa e basso, coppia di overhead, batteria come gruppo).
- **Tutti i canali**: 10 sul L12next, 18 sul L-20.  Un mic ambientale, su qualsiasi canale, ascolta la sala.
- **Strumenti al volo**: tocca il nome sotto una striscia e scegli cassa, rullante, tom, overhead, voce,
  basso, tastiera, lettore/base (mp3, computer, telefono)...  AI e sound check si adeguano subito.
- **Rispetta il tuo mixer**: non cambia mai scena da solo, non tocca monitor ne' master; a fine sound check
  scegli tu in quale scena salvare.
- **Si vede dal banco**: quando si collega, i MUTE del L12next si accendono in sequenza e tornano com'erano
  (solo in silenzio, mai mentre suonate).
- **Finestra Stato**: cosa sta facendo il programma adesso, i canali con livello, gain e fader, e il diario
  in diretta di ogni correzione.

| | |
|---|---|
| ![Mixer](immagini/01_mixer_L12next.png) | ![Sound check](immagini/02_soundcheck_line_check.png) |
| ![Fasi del sound check](immagini/02_soundcheck_fasi.png) | ![Salvataggio](immagini/03_salvataggio_scene.png) |
| ![Strumento al volo](immagini/04_strumento_al_volo.png) | ![Stato](immagini/05_finestra_stato.png) |
| ![Canale completo e Canali](immagini/06_canale_e_canali.png) | ![L-20](immagini/07_L20.png) |

*Le immagini sono schermate reali del programma, prese con un mixer simulato.*

## Mixer supportati

| Mixer | Comandi | AI | Sound check |
|---|---|---|---|
| ZOOM LiveTrak **L12next** | USB + Bluetooth (BTA-1), verificati | Assist e Auto | completo (gain automatico) |
| ZOOM LiveTrak **L-20** | in prova | Assist (posizione consigliata dei fader) | a consigli (giri tu il gain) |

L6 e L-8 non sono supportati: non hanno il BTA-1.

**Hai un L-20?** Aiutami a verificarlo: apri il programma, premi **Prova mixer**, fai le prove guidate
(canali audio e comandi) e manda il rapporto che salva sulla Scrivania all'indirizzo qui sotto.

## DEMO e versione completa

Qui trovi la **DEMO gratuita** (nelle [Release](../../releases)).

| | DEMO | Completa |
|---|---|---|
| Comandi del mixer (strisce, mandate, scene, registratore) | si | si |
| Primi 14 giorni | **tutto come la completa** | - |
| Sound check (dopo 14 giorni) | primi 2 canali, senza mix check | tutti i canali, 4 fasi |
| AI Assist (dopo 14 giorni) | 10 minuti a sessione | sempre |
| AI Auto (dopo 14 giorni) | no | si |
| Finestra Stato, strumenti al volo | si | si |

**Versione completa: con un'offerta libera, anche minima, per sostenere il progetto** su
**[paypal.me/AutoFonicMixer](https://paypal.me/AutoFonicMixer)**, poi scrivi a **autofonic.mixer@gmail.com**
e ricevi la versione completa.

## Download

Nelle [Release](../../releases) trovi la DEMO per i due sistemi:

| Sistema | File |
|---|---|
| Windows 10 / 11 (64 bit) | `AutoFonicMixer-DEMO-<versione>-windows-x64-setup.exe` |
| Linux (Ubuntu / Debian, 64 bit) | `AutoFonicMixer-DEMO-<versione>-linux-x86_64.tar.gz` |

## Installazione su Windows

1. Installa il **driver ZOOM** del tuo mixer (dal sito ZOOM): serve per l'audio di tutti i canali (ASIO).
2. Lancia `AutoFonicMixer-DEMO-...-windows-x64-setup.exe` (non servono i permessi di amministratore).
   Se SmartScreen avvisa "app non riconosciuta": *Ulteriori informazioni* → *Esegui comunque*.
3. Avvia **AutoFonic Mixer** dal menu Start.
4. Accendi il Bluetooth del PC.  Il BTA-1 **non** va abbinato nelle impostazioni di Windows: il programma lo
   trova da solo.  Attacca il cavo USB: anche quello viene trovato da solo.

## Installazione su Linux (Ubuntu / Debian, PC 64 bit)

1. Scarica dalle [Release](../../releases) il file `AutoFonicMixer-DEMO-...-linux-x86_64.tar.gz` e scompattalo.
2. Nella cartella: `sh installa.sh` (installa gli strumenti ALSA e Bluetooth, i permessi e l'icona nel menu).
3. Esci dalla sessione e rientra.
4. Avvia: `autofonic-mixer` (oppure `autofonic-mixer L20`), o dal menu "AutoFonic Mixer".
5. Accendi il mixer, attacca il cavo USB e il BTA-1: il programma li trova **da solo** (USB, audio e Bluetooth) e si ricollega se il cavo si stacca.

## Avvertenze

Progetto indipendente, **non affiliato, sponsorizzato o approvato da ZOOM Corporation**.  ZOOM, LiveTrak,
L12next, L-20 e BTA-1 sono marchi di ZOOM Corporation.  Il programma e' fornito senza garanzia: provalo a
volume basso prima di usarlo dal vivo.  Licenza: vedi [LICENSE](LICENSE).

---

## English

**Your LiveTrak, with a sound engineer inside.**  AutoFonic Mixer controls the ZOOM LiveTrak **L12next** and
**L-20** from **Linux, Windows or Mac**, runs a full-screen sound check and balances the mix while you play,
analysing the audio of **every channel**.  The program is in **English, Italian, French, Slovenian and Croatian** (menu "Language").

> **AI and sound check need both the USB cable and the ZOOM BTA-1 Bluetooth adapter.**

- **The whole mixer on screen**: strips, sends, scenes, recorder, master; full channel with gain, comp, EQ.
- **Full-screen sound check** in 4 phases: room silence, line check (gain, sound, drum phase), mix check,
  save to the scene you choose.
- **AI Studio / Live**: *Assist* suggests fader positions, *Auto* corrects them while you play.
- **Respects your mixer**: never changes scene by itself, never touches monitor sends or master.
- **Instruments on the fly**, including a **player / backing track** (mp3, computer, phone).
- **Test mixer**: guided tests and a report to send when something does not work.

| Mixer | Commands | AI | Sound check |
|---|---|---|---|
| ZOOM LiveTrak **L12next** | USB + Bluetooth (BTA-1), verified | Assist and Auto | full (automatic gain) |
| ZOOM LiveTrak **L-20** | being tested | Assist (recommended faders) | advice (you turn the gain) |

**Download** the free **DEMO** from the [Releases](../../releases): Windows 10/11 (`...-windows-x64-setup.exe`,
install the ZOOM driver first), Linux (`...-linux-x86_64.tar.gz`, then `sh installa.sh`), Mac Apple Silicon
(`...-mac-arm64.dmg`, being tested).  The DEMO works **fully for 14 days**; after that: sound check on the first
2 channels without mix check, AI Assist 10 minutes per session, no AI Auto.

**Full version: with a free donation, even a small one, to support the project** at
**[paypal.me/AutoFonicMixer](https://paypal.me/AutoFonicMixer)**, then write to **autofonic.mixer@gmail.com**
and you will receive the full version.

Independent project, not affiliated with ZOOM Corporation.  ZOOM, LiveTrak, L12next, L-20 and BTA-1 are
trademarks of ZOOM Corporation.  License: see [LICENSE](LICENSE).
