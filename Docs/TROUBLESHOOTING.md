# Risoluzione dei problemi / Troubleshooting

| Problema | Controlli |
|---|---|
| La COM non compare | Usa un cavo USB dati, prova un'altra porta, aggiorna l'elenco e verifica il driver USB-seriale. |
| Porta occupata / accesso negato | Chiudi JD1, IDE, monitor seriali e flasher, incluso il browser se collegato via USB. |
| COM presente, dispositivo non riconosciuto | Verifica firmware compatibile con JD2, porta corretta e applicazioni concorrenti. Dopo il flash scollega e ricollega la USB. |
| Una direzione parte da sola | Ricollega con stick centrato e regola la dead zone. |
| Non posso aggiungere Mouse move o Orbital | Una delle due modalità è già assegnata su Page 1 o Page 2. Rimuovi l'assegnazione esistente prima di spostarla. |
| Hold o Spam resta attivo | Ripeti la stessa direzione e la stessa procedura di attivazione per disattivarlo. |
| Sono in una modalità persistente | Nelle modalità che lo prevedono, tieni premuto il pulsante per uscire. |
| Timeout richiesta attivazione | Verifica Internet e accesso consentito da firewall/antivirus; riavvia il programma e riprova più tardi. |
| Bambu connesso ma dati incompleti | Mantieni aperto il monitor e attendi il report completo. Dopo riaperture ravvicinate possono servire circa cinque minuti. |
| Bambu richiede di nuovo l'accesso | La sessione può essere scaduta o revocata. Accedi nuovamente da Cloud settings. |
| Manca una lettura Bambu | Le misure disponibili dipendono dal modello e dalla telemetria ricevuta. Non interpretare un campo iniziale vuoto come una lettura reale. |

## English

- **No COM port:** check the USB data cable, driver, USB port and refreshed port list.
- **Port busy:** close the old Hub, serial monitors, IDEs and flashing tools, including a connected browser.
- **Port visible but no compatible device:** verify the JD2 firmware, select the correct port and reconnect USB after flashing.
- **Unwanted directions:** reconnect with the stick centered, then adjust dead zone.
- **Mouse move / Orbital assignment rejected:** remove the existing assignment on either page first; only one instance of either mode is allowed.
- **Key Hold / Spam still running:** repeat the same direction and trigger procedure to turn it off.
- **Persistent mode active:** use a long press to exit where supported.
- **Activation timeout:** check connectivity and firewall access, then retry later.
- **Incomplete Bambu data:** keep the monitor open and wait for a full report. Rapid reopening can require about five minutes.
- **Expired Bambu session:** sign in again in Cloud settings.
- **Missing Bambu measurements:** available readings depend on the printer and its reports.

## Segnalazioni / Reporting a problem

Include Hub version, firmware version, Windows version, trigger mode and exact steps. For Bambu issues, add printer model and the screen involved. Share only the relevant redacted log excerpt. Never post activation codes, account tokens, email verification codes, printer identifiers or private webhook URLs.
