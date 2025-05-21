# R.E.P.O Save Manager

A simple backup and restore tool for the game **R.E.P.O**, designed to protect your save progress from being wiped on death. Built with Python and [ttkbootstrap](https://ttkbootstrap.readthedocs.io/) for a clean, modern UI.

---

## 📦 Features

* 🔄 **Backup your save file** with a custom label (e.g. `LVL3REPO_SAVE_2025_05_19_23_43_15.es3`)
* 🧩 **Restore from backup** — select from a sortable list of save files
* 🌙 **Dark mode UI** with `ttkbootstrap`
* 📁 Automatically opens the file location after backup/restore
* ✅ Compatible across different users (auto-detects save path)
* 🧑 Author: [kaiminn05](https://github.com/kaiminn05)
* 💾 Version: v0.1

---

## 🚀 How to Use

1. Download the latest release `.exe` from the [Releases](https://github.com/kaiminn05/repo-save-manager/releases) tab.
2. Run the `.exe` directly (no installation required).
3. Use the GUI to:

   * Backup your current save
   * Restore any previous backup

### ⚠️ Warnings & Notes

* Please follow the instructions carefully when using the app.
* Ensure you select the correct save file during backup and restore.
* This tool does not prevent the game from deleting your current save if you die — it only allows you to restore a previous one.
* Any data loss or corrupted saves due to misuse of this app is **your responsibility**. Use at your own risk.
* This tool is created solely to assist players — it is not intended for any illegal, exploitative, or commercial use.

---

## 📂 Save Game Path (Auto-detected)

```plaintext
C:\Users\<YourUsername>\AppData\LocalLow\semiwork\Repo\saves
```

This is dynamically detected using the Windows environment variables.

---

## 📜 File Naming

* Backup files are saved as:

  ```
  LVL3REPO_SAVE_2025_05_19_23_43_15.es3
  ```
* The app shows file name, size, and save date in a list for easy selection.

---

## 🧙 Author Info

* Created by **kaiminn05**
* GitHub: [https://github.com/kaiminn05](https://github.com/kaiminn05)
* Version: `v0.1`

> ⚡ This app was created with the assistance of **AI (ChatGPT)** to accelerate development and improve quality.


---

## 📄 License

This project is free to use. Source code is not included in this distribution.
