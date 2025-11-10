# OVMF + Windows11 QCOW2 Builder 🚀

**Build & Ready-to-Use Cloud Workflow für UEFI-Firmware mit Windows11 VM**

---

## 🔹 Übersicht

Dieses Projekt liefert **fertige OVMF UEFI-Binaries** kombiniert mit einem **Windows11 QCOW2-Image**, sofort nutzbar in **QEMU, VirtualBox oder UTM**.  

- Kein lokales Build nötig  
- Kein Upload großer Dateien ins Repository  
- Alles läuft sauber über **GitHub Actions** in der Cloud  

---

## 🔹 Features

- **OVMF.fd**: Release Build, Secure Boot aktiviert  
- **Windows11_fixed.qcow2**: Vorbereitetes Image, startklar  
- **Artifact ZIP**: Enthält alles, Download direkt aus Actions  
- **Workflow flexibel**: Einfaches Forken und Run Workflow  

---

## 🔹 So benutzt du es

1. Forke das Repository: `ovmf-qcow2-builder`  
2. Gehe auf **Actions → Build OVMF + Windows11 QCOW2 → Run workflow**  
3. Nach 3–5 Minuten: Download ZIP aus **Artifacts → OVMF_QCOW2.zip**  
4. Enthalten:  
   - `OVMF.fd`  
   - `Windows11_fixed.qcow2`  

---

## 🔹 Hinweis zur Privatsphäre

- Dein Gerät / System wird **nicht im Repo oder Workflow sichtbar**  
- Alles läuft auf **GitHub Runnern (Ubuntu x86_64)**  
- Artefakte enthalten **nur OVMF + QCOW2**, keine persönlichen Daten
