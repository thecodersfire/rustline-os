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
