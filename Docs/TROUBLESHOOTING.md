# Troubleshooting

| Problem | Checks |
|---|---|
| COM port not listed | Use a USB data cable, try another USB port, refresh the port list and check the USB-to-serial driver. |
| Port busy / access denied | Close JD1, IDEs, serial monitors and flashing tools, including the browser if connected via USB. |
| COM port available, device not recognized | Check that the firmware is compatible with JD2, the correct port is selected and no other applications are using it. After flashing, disconnect and reconnect the USB cable. |
| A direction activates on its own | Reconnect with the stick centered and adjust the dead zone. |
| Cannot assign Mouse move or Orbital | One of these modes is already assigned on Page 1 or Page 2. Only one instance of either mode is allowed across both pages. Remove the existing assignment before moving it. |
| Hold or Spam remains active | Repeat the same direction and activation procedure to deactivate it. |
| A persistent mode is active | In modes that support it, press and hold the button to exit. |
| Activation request timeout | Check the Internet connection and ensure that the firewall/antivirus allows access; restart the program and try again later. |
| Bambu connected, but data incomplete | Keep the monitor open and wait for the full report. Reopening it shortly after closing may require a wait of approximately five minutes. |
| Bambu requests sign-in again | The session may have expired or been revoked. Sign in again through Cloud settings. |
| A Bambu reading is missing | Available measurements depend on the model and the telemetry received. Do not interpret an initially empty field as an actual reading. |

## Reporting a problem

Include Hub version, firmware version, Windows version, trigger mode and exact steps. For Bambu issues, add printer model and the screen involved. Share only the relevant redacted log excerpt. Never post activation codes, account tokens, email verification codes, printer identifiers or private webhook URLs.
