# Built-in features for rustline-os

Purpose: Rust development

1. **organize project files** — run rustline-os-workspace. It creates ~/Documents/rustline-os-workspace/ with Inbox, Projects, Archive folders.
2. **draft a session plan** — run rustline-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/rustline-os-session-plans/.
3. **check task readiness** — run rustline-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/rustline-os-workspace features/rustline-os-plan features/rustline-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for Rust development:

1. **Wireshark** — org.wireshark.Wireshark
2. **KiCad** — org.kicad.KiCad
3. **Arduino IDE 2** — cc.arduino.IDE2

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for Rust development:

1. **Thonny** — write and debug Python code (org.thonny.Thonny)
2. **Godot Engine** — build and test 2D and 3D games (org.godotengine.Godot)
3. **DB Browser for SQLite** — inspect SQLite databases (org.sqlitebrowser.sqlitebrowser)
4. **OpenSCAD** — model parametric 3D parts in code (org.openscad.OpenSCAD)
5. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
6. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
7. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
8. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
9. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
10. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **Pixelorama** (com.orama_interactive.Pixelorama) — draw pixel-art sprites and frame-based animations.
2. **Synfig Studio** (org.synfig.SynfigStudio) — create vector-based 2D animations.
3. **OpenToonz** (io.github.OpenToonz) — produce hand-drawn and cutout 2D animation.
4. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
5. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
6. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
7. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
8. **LMMS** (io.lmms.LMMS) — compose electronic music and loops.
9. **Hydrogen** (org.hydrogenmusic.Hydrogen) — program drum patterns and percussion tracks.
10. **Guitarix** (org.guitarix.Guitarix) — shape guitar tone with amp and effects processing.
11. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
12. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
13. **GIMP** (org.gimp.GIMP) — edit raster graphics and textures.
14. **Krita** (org.kde.krita) — paint digital illustrations.
15. **Inkscape** (org.inkscape.Inkscape) — create vector illustrations and diagrams.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.
