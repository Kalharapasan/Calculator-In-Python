
# 🧮 Scientific Calculator Collection

This repository includes four different calculator programs written in Python. The calculators range from basic terminal applications to advanced graphical scientific calculators built with `Tkinter` and `PyQt5`.

---

## 📁 Files

| File Name         | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| `colculater.py`   | A simple command-line calculator supporting basic arithmetic operations.   |
| `colculater2.py`  | Command-line calculator with history feature.                              |
| `colculater3.py`  | GUI-based scientific calculator using Tkinter.                             |
| `colculater4.py`  | Advanced GUI calculator using PyQt5 with scientific and memory functions.  |

---

## 🖥️ How to Run

### 🔹 Terminal Calculators

These calculators are text-based and run in the terminal.

#### Run `colculater.py`
```bash
python colculater.py
```

#### Run `colculater2.py`
```bash
python colculater2.py
```

#### Features:
- Basic operations: `+`, `-`, `*`, `/`, `%`, `^`
- Commands:
  - `#` → Exit program
  - `$` → Reset input
  - `?` → Show history (only in `colculater2.py`)

---

### 🔹 GUI Calculators

#### Run `colculater3.py` (Tkinter-based)
```bash
python colculater3.py
```

##### Features:
- GUI calculator with buttons
- Functions: `sin`, `cos`, `tan`, `log`, `ln`, `sqrt`, `n!`, `deg`, `rad`
- Constants: `pi`, `e`
- Basic and scientific operations

#### Run `colculater4.py` (PyQt5-based)
```bash
pip install PyQt5
python colculater4.py
```

##### Features:
- Sleek GUI using PyQt5
- Angle mode switching (DEG)
- Scientific functions like `x²`, `1/x`, `mod`, `exp`, `log`, `ln`, `n!`
- Memory operations: `MC`, `MR`, `M+`, `M-`, `MS`
- History button (not implemented, placeholder for future use)

---

## 📌 Notes

- Python 3 is required to run all versions.
- GUI calculators provide more advanced functionality and user-friendly interfaces.
- All GUI files are standalone and do not require external assets.
