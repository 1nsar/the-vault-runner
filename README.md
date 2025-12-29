# The Vault Runner

---

## 📘 Overview
**The Vault Runner** is a Python project that implements a **minimal programming language** to control a robot in a 2D grid world.  
The robot navigates walls, collects a key, opens a door, and exits using only local sensors.  
The language follows strict constraints: **≤20 tokens**, **one boolean flag**, and simple line-based syntax.

---

## 🧠 Language Summary

**Actions:** `FORWARD`, `LEFT`, `RIGHT`, `KEY`, `OPEN`, `EXIT`  
**Sensors:** `CHECKFRONT`, `CHECKKEY`, `CHECKDOOR`, `CHECKEXIT`  
**Control:** `IF`, `WHILE`, `=`, `==`, `YES`, `NO`, `STOP`  

- Single flag variable: `ROBOT_HAS_KEY`
- Indentation defines control blocks
- Each instruction directly maps to a robot action or sensor

---

## ▶️ How to Run
Open the `main.ipynb` file using Jupyter Notebook, JupyterLab, or VS Code

Run cells sequentially using **Shift + Enter**
