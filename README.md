# Icarus56 ZMK Firmware

ZMK firmware for the Icarus56, a DIY wireless split keyboard running on two Seeed XIAO nRF52840 mcus.

---

## Layers

| Layer | How to activate | What it does |
|---|---|---|
| **0 - Default** | Always on | Standard QWERTY |
| **1 - Lower** | Hold `MO1` (left thumb) | Symbols, F-keys |
| **2 - Raise** | Hold `MO2` (right thumb) | Arrow keys, navigation |
| **3 - Adjust** | Hold Lower + Raise | Bluetooth, bootloader |

---

## Encoders

| Side | Action | Binding |
|---|---|---|
| Left | Rotate | Volume Up / Volume Down |
| Right | Rotate | Brightness Up / Brightness Down |

> Encoder **switch** (press) is mapped in the key matrix. Assign it a key in the keymap like any other switch.

---

## Bluetooth

On **Layer 3 (Adjust)**:

| Key | Action |
|---|---|
| `BT_SEL 0–4` | Switch to Bluetooth profile 0–4 |
| `BT_CLR` | Clear current paired device |
| `bootloader` (corners) | Enter bootloader for flashing |

## Resources

- [ZMK Docs](https://zmk.dev/docs)
- [ZMK Keycode Reference](https://zmk.dev/docs/codes)
- [Seeed XIAO nRF52840 Pinout](https://wiki.seeedstudio.com/XIAO_BLE/)
- [ZMK Discord](https://zmk.dev/community/discord/invite)
