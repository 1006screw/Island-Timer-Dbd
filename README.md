# Island Timer

A small floating "island" for Windows 10/11 that sits at the top of your screen: clock, music with covers, notifications, a GIF or photo in the pill, and a stopwatch with **Solo timer** and **Ladder mode** (two timers for 1 vs 1 games like Dead by Daylight).

Portable, no installation, tiny (about 60 MB of RAM and almost no CPU while idle), 11 languages.

Made by **screw** · Discord: `screw_xgod`

> Source code is **not** published. Only the compiled program is available in [Releases](../../releases). See [LICENSE](LICENSE).

## Features

- **Clock pill.** A compact pill with the time. Hover it and it expands: big clock, date, battery and the track that is playing. You can drag it anywhere on the screen, resize it and change its color and opacity. Choose how it expands: on hover, with a delay, on click, or only by hotkey / from the tray. A game guard keeps it closed when you accidentally hover it while a fullscreen game is focused.
- **Music.** Shows what is playing in the system media player (browsers such as YouTube, Spotify, VLC and other players): title, artist, cover, seek bar and play / pause / next / previous. Playback from Telegram is ignored on purpose.
- **Notifications.** Windows notifications can pop up on the island (off by default, turn on in Settings).
- **GIF or photo in the pill.** Put your own GIF or image on the collapsed island. Optional dimming while the timer is shown.
- **Timers.**
  - **Solo timer**: a regular stopwatch with start / stop / reset.
  - **Ladder mode**: two timers for a 1 vs 1 game (for example your chase time and your opponent's in Dead by Daylight). The selected timer is highlighted, each timer has its own color, and when a running timer gets within N seconds of the other one, its digits change color. A hotkey switches between timer 1 and 2, and "pass the turn" can start the next timer automatically.
- **Global hotkeys.** Work in any window, including games. Single keys without Ctrl / Alt (like F9 or NumPad) are allowed, and the key still reaches the game by default.
- **Settings window.** Themes (light, dark, AMOLED black, midnight, purple, or your own colors), background image or GIF, language, autostart with Windows, always on top, and more.
- **Built-in video guide** with English subtitles (Settings → Guide). It is shown automatically on the very first launch as a ▶ button on the island.
- **Updates.** Settings → About → *Check for updates*. The program only downloads releases from this repository and checks their SHA-256 before installing.
- **Languages:** English, Français, Português, Русский, Español, العربية, 中文, Deutsch, Srpski, 한국어, 日本語.

## Download

Get `Island-Timer-by-screw.zip` **only from the Releases page of this repository**. Unzip it anywhere you can save files (not Program Files) and run `IslandTimer.exe`. The island appears at the top center of the screen and an icon appears in the tray.

## Quick start

| Action | How |
|--------|-----|
| Expand / collapse | Hover the island (or click the tray icon) |
| Open settings or close | Right-click the island or the tray icon |
| Move the island | Drag it with the left mouse button (can be locked in Settings) |
| Start / stop / reset the timer | `Ctrl+Alt+F9` |
| Turn the timer off (show the clock again) | `Ctrl+Alt+F10` |
| Reset the timer | `Ctrl+Alt+F11` |
| Ladder mode: switch timer 1 / 2 | `Ctrl+Alt+F12` |
| Expand / collapse by hotkey | `Ctrl+Alt+Up` |

All hotkeys are defaults and can be changed in Settings → Hotkeys.

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

## FAQ

**Hotkeys don't work in a game.** If the game (or any window) runs as administrator, Windows does not pass key presses to a normal program. Run `IslandTimer.exe` as administrator too (right-click → Run as administrator).

**Windows shows a SmartScreen warning.** The file is not signed: click *More info → Run anyway*. Some antivirus programs may flag the program because it listens to the keyboard globally for hotkeys and can add itself to startup. This is a false positive. If you don't trust the file, don't run it.

**Notifications don't appear.** Allow access in Windows Settings → Privacy → Notifications, then turn on "Show notifications" in the program (it is off by default).

**Where are my settings stored?** In `settings.ini` next to `IslandTimer.exe`.

**How do I uninstall it?** Untick "Start with Windows" in Settings (if you enabled it), close the island (right-click → Close) and delete the folder.

Island Timer is an independent project and is not affiliated with, endorsed by or sponsored by Apple Inc.

## Русский

**Island Timer**: небольшой плавающий «остров» для Windows 10/11 в верхней части экрана: часы, музыка с обложками, уведомления, GIF или фото на острове и секундомер с режимами **Solo timer** и **Ladder mode** (два таймера для игр 1 на 1, например Dead by Daylight). Не требует установки, почти не грузит систему, 11 языков.

**Возможности:** компактные часы с раскрытием по наведению; музыка из системного плеера (браузер, Spotify, VLC и др., Telegram игнорируется); уведомления Windows (по умолчанию выключены); своя GIF или картинка на острове; два режима таймера; глобальные горячие клавиши, работающие и в играх; темы и свои цвета окна настроек, фон-картинка; встроенный видео-гайд с английскими субтитрами; проверка обновлений в «О программе» с проверкой SHA-256.

**Установка:** скачайте `Island-Timer-by-screw.zip` **только со страницы Releases этого репозитория**, распакуйте куда угодно (не в Program Files) и запустите `IslandTimer.exe`.

Исходный код не публикуется, в Releases лежит только готовая программа. Проверяйте хэш SHA-256 (см. выше). Адреса для донатов выше единственные настоящие; если в вашей копии программы в разделе «О программе» другие адреса, это подделка.
