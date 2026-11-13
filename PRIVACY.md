# Handybar privacy policy

_Last updated: 13 November 2026_

Handybar is a quick-access toolkit for Windows. It runs entirely on your PC. **It doesn't collect, send or share any of your data, and it never connects to the internet.** There's no account, no analytics, no advertising and no tracking.

This page explains what Handybar looks at on your PC to do its job, what it keeps, and where.

## What Handybar uses, and why

| Feature | What it reads | What happens to it |
|---|---|---|
| **Clipboard** | Text and images you copy | Kept in a history inside Handybar so you can paste them again. Unpinned items live only in memory and are gone when Handybar closes (25 at most). Pinned items are saved on your PC. Anything an app marks as private, such as a password from a password manager, is never recorded. |
| **Text from screen** | A picture of the screen, taken only when you click "Text from screen" | The text in the area you select is read by Windows' own built-in text recognition, on your PC, and put on your clipboard. The picture is never saved. |
| **Privacy lights** | Which apps are using your camera or microphone, from Windows | Shown in the pill and the open bar while it's happening. Never saved. |
| **Now playing** | The song, artist and artwork that Windows reports for media playing on your PC | Shown in the Now playing card. Never saved. |
| **Quick toggles** | Whether your microphone or sound is muted, and whether Windows is in light or dark mode | Changed only when you click a toggle. |
| **Shelf** | The files you drop onto it | Their locations (not the files themselves) are saved so the shelf is still there next time. |
| **Emoji** | The emoji you pick | The ones you used recently are saved so they're at hand next time. Emoji are typed into the app you were using, the same way a keyboard types; your clipboard isn't touched. |
| **System stats** | CPU and memory use | Shown in the pill. Never saved. |
| **Wallpaper frost** | Your desktop wallpaper | Used to draw the bar's frosted background. Never copied or saved elsewhere. |

## What Handybar saves, and where

Everything is in one folder on your PC: `%LocalAppData%\Workbench` (named after Handybar's working title).

- `settings.json`: your Handybar settings
- `clipboard.json`: clipboard items you've pinned
- `shelf.json`: the locations of files on your shelf
- `emoji-recent.json`: emoji you used recently
- `crash.log`: details of any crash, to help fix it (only written if Handybar crashes, and never sent anywhere)

You can delete any of these at any time, or the whole folder to start fresh. Uninstalling Handybar and deleting this folder removes everything it kept.

## Children

Handybar doesn't collect personal information from anyone, including children.

## Changes to this policy

If Handybar ever starts handling data differently, this page will be updated first, with a new date at the top.

## Contact

Questions about privacy in Handybar: open an issue at <https://github.com/alexandruvalentin/Handybar/issues>.
