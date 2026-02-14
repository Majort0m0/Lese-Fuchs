# 🦊 Lese-Fuchs

**Interaktive Webanwendung zur Leseförderung mit KI-Unterstützung.**

Der **Lese-Fuchs** ermöglicht es Lehrkräften, Texte didaktisch aufzubereiten, mit Übungen zu verknüpfen und als eigenständige HTML-Dateien zu exportieren. Die App arbeitet nach dem Prinzip **Privacy by Design** – alle Daten werden lokal im Browser verarbeitet.

---

## 🚀 Funktionen

* 📖 **Lesen & Hören:** Textanzeige in der lesefreundlichen Schrift "Andika" mit Wort-Hervorhebung und Vorlesefunktion (Web Speech API).
* ❓ **Interaktives Quiz:** Multiple-Choice-Fragen zur Überprüfung des Leseverständnisses.
* ✏️ **Lückentext:** Wörter per Drag & Drop in den Text ziehen.
* 🧩 **Zuordnen:** Spielerisches Training durch Verknüpfung von Wörtern mit Piktogrammen.
* 💾 **HTML-Export:** Übungen als autarke Dateien speichern und offline/ohne Login an Schüler weitergeben.

---

## 🤖 Eigene Inhalte erstellen (KI-Workflow)

Die Erstellung neuer Übungen basiert auf dem **JSON-Format**. Du kannst eine KI (wie ChatGPT oder Claude) nutzen, um diese Dateien in Sekunden zu erstellen:

1.  Klicke in der App auf **"KI-Generator"** und kopiere den Prompt.
2.  Füge den Prompt in die KI deiner Wahl ein und nenne dein Thema.
3.  Speichere den generierten Code-Block als `.json` Datei ab (z.B. `weltraum.json`).
4.  Lade die Datei über **"JSON laden"** in den Lese-Fuchs hoch.

---

## 🛡️ Datenschutz (Privacy by Design)

Diese Anwendung wurde mit Fokus auf Datensparsamkeit entwickelt:

* **Keine Server-Speicherung:** Es werden keine personenbezogenen Daten oder Lernergebnisse auf einem Server gespeichert.
* **Local Storage:** Es wird lediglich ein Flag (`lese-fuchs-terms-accepted`) lokal gespeichert, um die Nutzungsbedingungen zu bestätigen.
* **Externe Dienste:** Zur Darstellung werden Tailwind CSS, Google Fonts und die ARASAAC API (für Piktogramme) geladen. Hierbei wird technisch bedingt die IP-Adresse übertragen.

---

## ⚖️ Lizenzierung

Dieses Projekt ist unter der **Creative Commons Attribution-NonCommercial 4.0 International** lizenziert.

* **App-Lizenz:** [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.de) (Namensnennung - Nicht-kommerziell).
* **Piktogramme:** Die verwendeten Piktogramme stammen von [ARASAAC](https://arasaac.org/) (Sergio Palao) und stehen unter [CC BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/).

---
Ein Projekt von **[Lernsachen.blog](https://lernsachen.blog)**
