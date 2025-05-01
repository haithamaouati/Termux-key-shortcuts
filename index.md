---
title: Termux Key Shortcuts
---

# Termux Key Shortcuts

A reference guide for using keyboard shortcuts in [Termux](https://termux.dev), the powerful terminal emulator for Android.

---

## Table of Contents

- [Introduction](#introduction)
- [Default Key Shortcuts](#default-key-shortcuts)
- [Function Keys (F1–F10)](#function-keys-f1f10)
- [Special Keys](#special-keys)
- [Customizing Extra Keys](#customizing-extra-keys)
- [References](#references)

---

## Introduction

Termux lacks a traditional hardware keyboard, but it offers keyboard shortcuts via the **Volume Up** key as a modifier. This enables essential terminal commands using a mobile device.

---

## Default Key Shortcuts

| Shortcut              | Description                        |
|-----------------------|------------------------------------|
| `Volume Up + A`       | `CTRL + A`                         |
| `Volume Up + B`       | `CTRL + B`                         |
| `Volume Up + C`       | `CTRL + C` – Interrupt process     |
| `Volume Up + D`       | `CTRL + D` – EOF / Logout          |
| `Volume Up + E`       | `CTRL + E`                         |
| `Volume Up + F`       | `CTRL + F`                         |
| `Volume Up + G`       | `CTRL + G`                         |
| `Volume Up + H`       | `CTRL + H` – Backspace             |
| `Volume Up + I`       | `CTRL + I`                         |
| `Volume Up + J`       | `CTRL + J`                         |
| `Volume Up + K`       | `CTRL + K`                         |
| `Volume Up + L`       | `CTRL + L` – Clear screen          |
| `Volume Up + M`       | `CTRL + M` – Enter                 |
| `Volume Up + N`       | `CTRL + N`                         |
| `Volume Up + O`       | `CTRL + O`                         |
| `Volume Up + P`       | `CTRL + P`                         |
| `Volume Up + Q`       | `CTRL + Q`                         |
| `Volume Up + R`       | `CTRL + R` – Search history        |
| `Volume Up + S`       | `CTRL + S`                         |
| `Volume Up + T`       | `CTRL + T`                         |
| `Volume Up + U`       | `CTRL + U` – Cut line              |
| `Volume Up + V`       | `CTRL + V`                         |
| `Volume Up + W`       | `CTRL + W` – Delete word           |
| `Volume Up + X`       | `CTRL + X`                         |
| `Volume Up + Y`       | `CTRL + Y`                         |
| `Volume Up + Z`       | `CTRL + Z` – Suspend process       |

---

## Function Keys (F1–F10)

| Shortcut              | Function Key   |
|-----------------------|----------------|
| `Volume Up + 1`       | `F1`           |
| `Volume Up + 2`       | `F2`           |
| `Volume Up + 3`       | `F3`           |
| `Volume Up + 4`       | `F4`           |
| `Volume Up + 5`       | `F5`           |
| `Volume Up + 6`       | `F6`           |
| `Volume Up + 7`       | `F7`           |
| `Volume Up + 8`       | `F8`           |
| `Volume Up + 9`       | `F9`           |
| `Volume Up + 0`       | `F10`          |

---

## Special Keys

| Shortcut              | Description                    |
|-----------------------|--------------------------------|
| `Volume Up + Enter`   | `ESC`                          |
| `Volume Up + K`       | Toggle extra keys              |
| `Volume Up + L`       | Toggle software keyboard       |

---

## Customizing Extra Keys

You can define custom buttons in the `.termux/termux.properties` file.

### Example

```properties
extra-keys = [['ESC','CTRL','ALT','TAB','LEFT','RIGHT','UP','DOWN']]
```

After editing the file, run:
```
termux-reload-settings
```
---

## References

[Termux Wiki - Touch Keyboard](https://wiki.termux.com/wiki/Touch_Keyboard)

[Termux GitHub](https://github.com/termux/termux-app)

---

> Keep hacking. Keep learning. Termux is more powerful than it looks.
