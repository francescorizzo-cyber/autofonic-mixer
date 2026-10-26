# Hai un ZOOM LiveTrak L-20? Aiutami a provarlo

*[English below](#english)*

AutoFonic Mixer è verificato sul banco con il **L12next**.  Il **L-20** dovrebbe funzionare allo stesso modo,
ma nessuno l'ha ancora provato con un mixer vero.  Con mezz'ora del tuo tempo e il tuo L-20 puoi dirmi se
funziona su **Windows**, **Linux** o **Mac**.  Il programma ti guida e alla fine prepara da solo **un file zip**
da mandarmi per email.

## Cosa ti serve

- Il **L-20** con il **cavo USB** collegato al computer.
- L'adattatore Bluetooth **ZOOM BTA-1** inserito nel L-20 (se ce l'hai: senza, la prova vale a metà).
- Un computer con **Windows 10/11**, **Linux** (Ubuntu/Debian 64 bit) o **Mac** (Apple Silicon).
- Qualcosa da collegare ai canali: un microfono, una chitarra, un lettore mp3...
- La **DEMO gratuita** di AutoFonic Mixer dalle [Release](../../releases) (va benissimo per la prova).

## 1. Installa

- **Windows**: prima installa il **driver ZOOM del L-20** (dal sito ZOOM: serve per l'audio di tutti i canali),
  poi lancia `AutoFonicMixer-DEMO-...-windows-x64-setup.exe`.  Se SmartScreen avvisa: *Ulteriori informazioni*
  → *Esegui comunque*.  Il BTA-1 **non** va abbinato nelle impostazioni di Windows.
- **Linux**: scompatta `AutoFonicMixer-DEMO-...-linux-x86_64.tar.gz`, nella cartella `sh installa.sh`, poi esci
  dalla sessione e rientra.
- **Mac**: apri il `.dmg` e trascina l'app in Applicazioni.  La prima volta: tasto destro → *Apri*.  Consenti
  **microfono** (serve per leggere l'audio USB del mixer) e **Bluetooth**.

## 2. Prepara il L-20 (dal manuale ZOOM) - a mixer SPENTO

Questi interruttori sul retro si leggono solo all'accensione: impostali **prima** di accendere.
- **MODE** su **AUDIO INTERFACE** (non CARD READER, non USB HOST).
- **SAMPLE RATE** su **44.1 o 48 kHz**: a 96 kHz l'interfaccia audio USB non funziona.
- **CLASS COMPLIANT MODE**: su **Linux** e **Mac** mettilo su **ON** (su Linux non esiste il driver ZOOM; sul Mac
  con ON non serve il driver).  Su **Windows** lascialo su OFF e usa il driver ZOOM.
- Inserisci il **BTA-1 prima di accendere** il mixer: il manuale dice che va collegato a mixer spento.

## 3. Collega

1. Apri AutoFonic Mixer e in alto a sinistra scegli **L20**.
2. Accendi il L-20, collega il cavo USB e il BTA-1.  Chiudi l'app ZOOM sul telefono (il mixer accetta un solo
   collegamento Bluetooth).
3. Aspetta un minuto: il programma cerca il mixer da solo.  La riga in alto dice cosa ha trovato (USB, audio,
   Bluetooth).  Premi **Leggi stato dal mixer**.

Fai una **foto dello schermo** in questo momento: serve per vedere cosa ha trovato.

## 4. Prova mixer (il pulsante in alto)

1. **Prova canali audio**: il programma ti dice "suona solo nel CH1", poi CH2...  Suona o parla **solo** in
   quel canale: il programma vede da solo quale canale USB si accende.  Per i canali senza niente collegato
   premi **Salta**.  Alla fine, se l'ordine è diverso da quello che il programma pensava, premi **Salva
   l'ordine**.
2. **Prova comandi**: "muovi il fader del CH1 sul mixer", "premi MUTE"...  Fai quello che chiede sul mixer.
   Poi il programma prova ad accendere MUTE e SOLO del CH1 e ti chiede se si sono accesi: rispondi **Sì** o
   **No** guardando il mixer.
3. **Salva rapporto**: crea il file `AutoFonicMixer_rapporto_L20_<data>.zip` sulla **Scrivania** (o nella
   tua cartella utente).

## 5. Se hai tempo: altre due prove

- **Sound check**: premi *Sound check* e segui le fasi con quello che hai collegato.  Dimmi se i consigli
  ("alza", "abbassa", "fermati qui") corrispondono a quello che senti.
- **Esporta SD**: registra qualche secondo sulla SD del L-20, poi metti la SD nel computer (oppure spegni il
  mixer, metti MODE su **CARD READER** e riaccendi) e premi **Esporta SD**.  Fai una **foto dell'elenco dei file** dentro la cartella della registrazione sulla SD (es.
  `PROJECT/251025_203000`): mi serve per sapere come il L-20 chiama i file.

Dopo queste prove salva di nuovo il rapporto (punto 4): così contiene tutto.

## Se qualcosa non va

| Cosa vedi | Cosa fare |
|---|---|
| **"Nessun L-20 trovato" sull'USB, meter spenti, "Audio assente"** | A mixer spento metti **MODE** su AUDIO INTERFACE e **SAMPLE RATE** a 44.1 o 48 kHz.  Su **Linux** e **Mac** metti **CLASS COMPLIANT MODE su ON**; su **Windows** installa il driver ZOOM del L-20.  Poi riaccendi. |
| **Muovi i fader via Bluetooth ma l'USB resta "non collegato"** | Normale per i comandi: sul L-20 passano solo dal Bluetooth (BTA-1).  Conta l'**audio** USB: se il riquadro "Audio" non diventa verde, vedi la riga sopra. |
| **Il Bluetooth non trova il L-20** | Spegni il mixer, inserisci il **BTA-1**, riaccendi.  Chiudi l'app ZOOM su iPad/telefono (il BTA-1 accetta un solo collegamento).  Avvicina il computer: muri e pareti insonorizzate bloccano il segnale. |
| **"Esporta SD" non trova le registrazioni** | Premi "Scegli cartella..." e indica la SD o la cartella FOLDER01...  (oppure MODE su CARD READER e riaccendi). |

In ogni caso salva il rapporto (punto 4) e mandamelo: anche un rapporto di "non funziona" mi aiuta.

## 6. Cosa mandarmi

Scrivi a **autofonic.mixer@gmail.com**, oggetto **"Prova L-20"**, e allega:

1. il file **`AutoFonicMixer_rapporto_L20_<data>.zip`** (l'ultimo che hai salvato);
2. le **foto dello schermo** (punto 2 ed eventualmente la cartella della SD);
3. due righe:
   - sistema: **Windows / Linux / Mac** (e versione, es. Windows 11);
   - cosa ha funzionato e cosa no (es. "i fader si muovono sullo schermo ma il MUTE dal programma non si
     accende sul mixer").

Nello zip ci sono solo dati tecnici del programma e del mixer: porte e schede audio trovate, messaggi
scambiati con il mixer, il diario del programma e le risposte alle prove.  Niente file personali.

**Grazie!**  Con il tuo rapporto il L-20 diventa "verificato" per tutti.

---

## English

# Do you have a ZOOM LiveTrak L-20? Help me test it

AutoFonic Mixer is verified on the bench with the **L12next**.  The **L-20** should work the same way, but
nobody has tried it with a real mixer yet.  With half an hour and your L-20 you can tell me whether it works on
**Windows**, **Linux** or **Mac**.  The program guides you and at the end creates **one zip file** to email me.

**You need**: the L-20 with the **USB cable** to the computer, the **ZOOM BTA-1** Bluetooth adapter (if you
have it), something plugged into the channels (a mic, a guitar, an mp3 player), and the free **DEMO** from the
[Releases](../../releases).

1. **Install** - Windows: install the **ZOOM L-20 driver** first, then the setup.exe (do not pair the BTA-1 in
   Windows settings).  Linux: unpack, `sh installa.sh`, log out and in.  Mac: open the .dmg, drag the app to
   Applications, first time right click → Open, allow microphone and Bluetooth.
2. **Prepare the L-20 (from ZOOM's manual), with the desk OFF** - the rear switches are read only at power-on:
   **MODE** on **AUDIO INTERFACE**; **SAMPLE RATE** 44.1 or 48 kHz (USB audio does not work at 96 kHz);
   **CLASS COMPLIANT MODE** **ON** on **Linux** and **Mac** (there is no ZOOM driver for Linux), OFF on Windows
   with the ZOOM driver; plug the **BTA-1 in before switching on**.
3. **Connect** - choose **L20** at the top left, switch on the L-20, plug in USB and BTA-1, close the ZOOM
   phone app, wait a minute, press **Read mixer state**.  Take a **screenshot**.
4. **Test mixer** (button at the top) - **Audio channel test** (play only into the channel it asks; *Skip* for
   empty channels; *Save the order* at the end if it is different), **Command test** (do what it asks on the
   mixer, then answer Yes/No when it tries MUTE and SOLO), **Save report**: it creates
   `AutoFonicMixer_rapporto_L20_<date>.zip` on the **Desktop**.
5. **If you have time** - try the **Sound check**, and **SD export** with a short recording (SD card in the PC, or MODE on CARD READER): take a
   **screenshot of the file list** inside the recording folder on the SD card.  Then save the report again.
6. **Email** to **autofonic.mixer@gmail.com**, subject **"L-20 test"**: the **zip** file, the **screenshots**,
   and two lines: your system (**Windows / Linux / Mac** and version) and what worked and what did not.

**If something does not work**
- **"No L-20 found" on USB, no meters, "No audio"**: with the desk OFF set **MODE** to AUDIO INTERFACE and **SAMPLE
  RATE** to 44.1 or 48 kHz.  On **Linux** and **Mac** set **CLASS COMPLIANT MODE ON**; on **Windows** install the
  ZOOM L-20 driver.  Then switch on again.
- **Faders move over Bluetooth but USB stays "not connected"**: normal for commands, on the L-20 they only go
  through the BTA-1.  What matters is the USB **audio**: if the "Audio" box does not turn green, see above.
- **Bluetooth does not find the L-20**: switch the desk off, plug in the **BTA-1**, switch on.  Close the ZOOM app
  on iPad/phone (one connection only).  Move the computer closer: walls and soundproofing block the signal.
- **SD export finds no recordings**: press "Choose folder..." and pick the SD card or a FOLDER01... folder.

Save the report anyway and send it: a "it doesn't work" report helps too.

The zip only contains technical data of the program and the mixer (ports and audio devices found, messages
exchanged with the mixer, the program log, your answers to the tests): no personal files.

**Thank you!**  With your report the L-20 becomes "verified" for everyone.
