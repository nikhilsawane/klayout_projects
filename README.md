# KLayout Projects

This repository contains all ongoing and archived KLayout designs used in the development and fabrication of micro-scale devices.

## 🔀 Repository Structure

- `main`: Stable branch with tested and released layouts (e.g., v1.0.0 and above)
- `35um-devices`: Development branch focused on designs with 35 µm active area

## 🛠 Requirements

- [KLayout](https://www.klayout.de/) (tested on version 0.28.12 or later)

## 📌 Notes

- Work-in-progress designs are tracked in feature branches
- Releases are tagged using `vX.Y.Z` format (e.g., `v1.0.0`)

# KLayout Projects Repository

This repository organizes and tracks microdevice layout designs developed using [KLayout](https://www.klayout.de/), structured by device area size.

---

## 📂 Branch Organization

Each branch contains work-in-progress and finalized layout files for a specific active area size:

| Branch Name        | Description                          |
|--------------------|--------------------------------------|
| `35um-devices`     | Layouts for 35 µm × 35 µm devices    |
| `50um-devices`     | Layouts for 50 µm × 50 µm devices    |
| `75um-devices`     | Layouts for 75 µm × 75 µm devices    |

The `main` branch contains only metadata, documentation, and release notes.

---

## 🛠 Tools

- **KLayout** version ≥ 0.28.12
- Scripts/macros are compatible with Python or Ruby interface

---

## 🧾 Versioning

Release tags (e.g., `v1.0.0`) will be applied only to stable commits merged into `main`.



