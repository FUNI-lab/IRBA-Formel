# 🧪 IRBA-Formel | FUNI-lab

**Projektarbeit:** Implementierung und Analyse der A-IRBA Risikogewichtungsfunktionen.

Dieses Repository enthält den Code, die Datenaufbereitung und die Quarto-Berichte zur Berechnung der regulatorischen Kapitalanforderung (RWA) basierend auf den Parametern PD, LGD, EAD und der effektiven Restlaufzeit (M).

## 🛡️ Data Governance
Es gilt das strikte **Sandbox-Prinzip**:
* **Keine Echtdaten:** Echte Bestandsdaten verbleiben ausschließlich lokal im Ordner `data/raw/` und werden durch die `.gitignore` blockiert.
* **Synthetische Daten:** Für die Lauffähigkeit des Codes auf GitHub liegen anonymisierte Test-Portfolios unter `data/synthetic/`.

## 🛠️ Setup & Reproduzierbarkeit
* **Sprache:** R (Tidyverse, native Pipes `|>`)
* **Reporting:** Quarto (`reports/`)
* **Paket-Management:** [Ggf. renv aktivieren und hier erwähnen]

Bitte bei der Entwicklung auf explizite Namespaces (z. B. `dplyr::mutate()`) achten.