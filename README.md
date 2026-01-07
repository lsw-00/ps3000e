# PicoScope 3000e - LabVIEW Integration

Dieses Repository enthält Beispiele und Tests für die Ansteuerung des PicoScope 3000e mittels LabVIEW.

## 📋 Voraussetzungen

* **Hardware:** PicoScope 3000e Serie
* **Software:** LabVIEW (Version 2024Q3 oder neuer)
* **Treiber:** PicoScope Software 

## 1. Installation & Hardware-Setup

**Wichtig:** Bitte die Software installieren, **bevor** das Oszilloskop per USB angeschlossen wird.

1.  **Software herunterladen:**
    Lade die aktuelle Software (PicoScope 7) hier herunter:
    [https://www.picotech.com/downloads](https://www.picotech.com/downloads)

    > *Hinweis: Die Standard-Installation beinhaltet in der Regel die notwendigen Treiber. Sollten Probleme auftreten, bitte prüfen, ob das "PicoSDK" separat installiert werden muss.
    Falls das der Fall sein sollte bitte mich kontaktieren, dass ich das ganze mal anschauen kann.*

2.  **Installation:**
    Installiere die Software und führe sie einmalig aus, um sicherzustellen, dass die Treiber korrekt registriert sind.

3.  **Anschließen:**
    Schließe das PicoScope nun per USB an den PC an. Windows sollte die Hardware nun erkennen.

## 2. Repository Clonen

Öffne deine Git Bash (oder Terminal) und führe folgenden Befehl aus:

```bash
git clone https://github.com/picotech/picosdk-ni-labview-examples.git
```
## Jetzt kannst du die Labview Applikation ausführen!
- Bei ersten start muss man gewisse dateien dem Programm "zeigen", dies dient zur orientierung für die file struktur. Nach 2-3 Dateien sollte es aber den rest von alleine finden!
- Bitte auf dein Memory schauen! Bei großen Datenmengen die vom Oszi auf deinen PC übertragen werden kann schnell dein RAM vollaufen!
Viel Spaß beim Verzeweifeln :)
