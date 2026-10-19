# Built-in features for home-circuit-os

Purpose: home automation

1. **organize a personal routine** — run home-circuit-os-workspace. It creates ~/Documents/home-circuit-os-workspace/ with Plans, Journal, Reference folders.
2. **plan a personal session** — run home-circuit-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/home-circuit-os-session-plans/.
3. **check routine readiness** — run home-circuit-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/home-circuit-os-workspace features/home-circuit-os-plan features/home-circuit-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for home automation:

1. **Wireshark** — org.wireshark.Wireshark
2. **KiCad** — org.kicad.KiCad
3. **Arduino IDE 2** — cc.arduino.IDE2

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
