# WinClone

> ### ⚠️ FANMADE / CONCEPT PROJECT
> WinClone is a **fan-made concept piece** — a hobby tribute to desktop operating
> systems that runs entirely in a browser tab.
>
> It is **not** a real operating system. It is **not** Microsoft Windows. It contains
> **no** Microsoft code, artwork, icons or assets — everything in it was written and
> drawn from scratch. It is **not** affiliated with, endorsed by, sponsored by or
> connected to Microsoft Corporation. It is free and is never sold.
>
> "Windows" and "Microsoft" are trademarks of their respective owners and are
> referenced descriptively only, to explain what this project is a tribute to.

A whole pretend desktop in one browser tab: a lock screen, a taskbar, draggable
windows, a virtual file system that remembers your files, and a pile of little
built-in apps.

## What's in it

- **A real window manager** — drag, resize, minimise, maximise, snap to screen edges
- **Task View and virtual desktops** — live window thumbnails, up to 8 desktops,
  drag windows between them, and an Alt+Tab switcher
- **Python** — a from-scratch interpreter with an editor, a console and a little
  graphics library (`wcgame`), so `.py` games really run. Examples in `Documents\Python`
- **WinLang** — a programming language of WinClone's own, where a *picture is a
  value*. Type the word `draw` in your code and a box appears in the line; click
  it, sketch something on a transparent pad, and `wl.display(draw#1)` paints it
  on the canvas when the program runs. The drawings are stored inside the `.wl`
  file itself, so one file holds the code and the art. Examples in `Documents\WinLang`
- **A neural network** — `brain.py`, one of those examples, trains itself with
  real backpropagation, guesses the digit you draw with the mouse, and learns
  your handwriting when you tell it what you actually drew
- **CloneDOOM** — an original first-person raycaster: textured walls, sliding
  doors, demons, a shotgun. Because someone always asks whether it runs DOOM
- **Screen FX** — twenty effects that happen to the *screen* rather than in a
  window: the desktop shakes, spins, melts, cracks, flips upside down or fills
  with static, and everything underneath carries on working
- **System Restore Points** — snapshot the machine before you break it, and
  roll back later
- **A password-protected lock screen**, with a security question if you forget it
- **A virtual file system** that persists, with folders, a Recycle Bin and shortcuts
- **Desktop icons** you can drag around a grid; they stay where you put them
- **Apps** — File Explorer, Notepad, a document editor, Calculator, Terminal,
  Settings, a browser, Photos, Media Player, Paint, Task Manager, Minesweeper,
  Snake, Python, WinLang, CloneDOOM and more
- **A pretend security suite**, with pretend malware to catch (all fake — it never
  touches your real computer)
- **BIOS setup, a recovery console and a blue screen of death**, because of course

## Running it

Download the folder and double-click `index.html`. No installer, no build step,
no dependencies, no server. It works offline.

## A note on your data

Everything WinClone saves — your files, settings, wallpaper and password — lives in
your own browser's `localStorage` on your own machine. Nothing is uploaded anywhere.
Clearing your browser data, or using BIOS ▸ *Restore Factory Defaults*, wipes it.

The lock screen is a **toy**, not real security: anyone with browser devtools can
read or clear it. Don't use a password you use anywhere real.

## Licence

Copyright © 2026 thisisuhhplanetring. All rights reserved.

You may run it, read the source, modify your own private copy, and fork this repo
on GitHub. You may **not** rehost or republish it as a site of your own, strip the
attribution, pass it off as your own work, or sell it.

See [LICENSE.txt](LICENSE.txt) for the full terms.

> **Licence change:** versions released before 27 July 2026 were published under the
> MIT Licence. Those releases remain MIT — that grant isn't withdrawn. Everything
> from 27 July 2026 onward uses the terms in `LICENSE.txt`.
