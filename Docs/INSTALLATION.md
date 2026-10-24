# Installazione / Installation

## Italiano

1. Consulta il [progetto MakerWorld](https://makerworld.com/en/models/3316603) e le note della release JD2 scelta.
2. Scarica l'installer Windows allegato alla release. Non usare gli archivi automatici **Source code** come installer. Se la release offre un pacchetto portable, estrai tutta la cartella prima di avviare `JoyDeckHub.exe` e conserva insieme tutti i file.
3. Installa il programma e completa l'attivazione gratuita, se richiesta. Le richieste vengono elaborate da DGVeLab; attendi il codice prima di ripetere l'invio.
4. Verifica il firmware indicato dalla release per il tuo dispositivo. La versione Hub documentata usa il protocollo seriale JoyDeck 2: un vecchio firmware può esporre la COM senza essere riconosciuto dall'Hub. Non scegliere un firmware soltanto in base al numero di versione.
5. Per la programmazione usa lo strumento indicato nelle note firmware. Il [Flash Center](https://dgvelab.github.io/DGVeLab-Flash-Center/) può essere usato quando il catalogo o le istruzioni della release identificano il firmware corretto. Per file locali usa soltanto gli offset forniti con quel firmware. [ESP-Programmer](https://github.com/DGVeLab/ESP-Programmer) contiene ulteriori risorse e driver.
6. Chiudi flasher, browser collegato alla seriale, IDE e vecchio Hub. Scollega e ricollega la USB se necessario.
7. Avvia JD2, seleziona la COM, premi **Connect** e lascia lo stick al centro durante la calibrazione.
8. Configura una direzione, prova **Test action** e premi **Save**.

Il profilo di pubblicazione del progetto è Windows x64 self-contained. Un pacchetto generato con quel profilo include il runtime .NET; non richiede l'installazione separata del runtime. Questa indicazione va verificata nelle note del pacchetto effettivamente scaricato.

La programmazione può sovrascrivere le impostazioni del dispositivo. Esporta la configurazione dell'Hub prima di cambiare installazione o firmware.

## English

1. Start from the [MakerWorld project](https://makerworld.com/en/models/3316603) and read the selected JD2 release notes.
2. Download the attached Windows installer. Automatic **Source code** archives are not installers. If a portable package is offered, extract the entire folder before running `JoyDeckHub.exe` and keep its files together.
3. Install and complete free activation if requested. DGVeLab processes activation requests; allow time for the code to arrive.
4. Use firmware specifically identified for the selected JD2 release and your hardware. The documented Hub uses JoyDeck serial protocol 2. A visible COM port alone does not establish firmware compatibility.
5. Follow the firmware's flashing instructions. Use the [Flash Center](https://dgvelab.github.io/DGVeLab-Flash-Center/) only with a matching catalog entry or the release's explicit instructions. For local images, use the offsets supplied with that firmware. See [ESP-Programmer](https://github.com/DGVeLab/ESP-Programmer) for additional resources and drivers.
6. Close other applications using the serial port, reconnect USB if necessary, then start JD2.
7. Select the COM port, click **Connect** and keep the joystick centered during calibration.
8. Configure a direction, use **Test action** and **Save**.

The project's Windows x64 self-contained publish profile includes the .NET runtime. Check the actual release notes to confirm the downloaded package uses that profile.

Flashing can overwrite device settings. Export your Hub configuration before changing installation or firmware.
