# Island Timer

A small floating "island" for Windows 10/11: clock, music with covers, notifications, a GIF or photo in the pill, and a stopwatch with **Solo timer** and **Ladder mode** (two timers for 1 vs 1 games). Portable, no installation, 11 languages.

Made by **screw** · Discord: `screw_xgod`

> Source code is **not** published. Only the compiled program is available in [Releases](../../releases). See [LICENSE](LICENSE).

## Download

Get `Island-Timer-by-screw.zip` **only from the Releases page of this repository**. Unzip it anywhere you can save files (not Program Files) and run `IslandTimer.exe`. A short video guide is built into the program (Settings → Guide).

## Verify your download (important)

Copies of this program from other places may have been modified, for example to replace the donation wallets. Check the file before running it:

```powershell
Get-FileHash .\IslandTimer.exe -Algorithm SHA256
```

The hash must match the one in the release notes of the version you downloaded. If it does not, delete the file and download it again from here.

Current `IslandTimer.exe` SHA-256:

```
949E0D1578120D806D63E8DC4274C2CC977404E13E9813ADFA28FB4D405971CB
```

(The hash changes with every release; the release notes always list the current one.)

## Official donation addresses

These are the only addresses of the author. They are also shown in the program under **About**. If the addresses in your copy are different, it is **not** the original program.

| Coin | Address |
|------|---------|
| USDT (TRC20) | `TRpt62hJHPPNQbxWnJnkwK5GXVgotKupTQ` |
| BTC | `bc1q4uar8agw72tjct87zvpryaeuq6xyrwqv05ayn0` |
| DonationAlerts | https://www.donationalerts.com/r/screw__ |

Thank you for your support!

## Notes

- Windows may show a SmartScreen warning because the file is not signed: *More info → Run anyway*. Some antivirus programs can flag it because it listens to the keyboard globally for hotkeys; this is a false positive. If you don't trust the file, don't run it.
- To show Windows notifications, allow access in Windows Settings → Privacy → Notifications, then turn on "Show notifications" in the program (it is off by default).
- Uninstall: untick "Start with Windows" in Settings (if enabled), close the island and delete the folder.

## Русский

**Island Timer**: небольшой плавающий «остров» для Windows 10/11: часы, музыка с обложками, уведомления, GIF или фото на острове и секундомер с режимами **Solo timer** и **Ladder mode** (два таймера для игр 1 на 1). Не требует установки, 11 языков. Видео-гайд встроен в программу (Настройки → Guide).

Исходный код не публикуется, в Releases лежит только готовая программа. Скачивайте её **только со страницы Releases этого репозитория** и проверяйте хэш SHA-256 (см. выше). Адреса для донатов выше единственные настоящие; если в вашей копии программы в разделе «О программе» другие адреса, это подделка.
