# MCTI – Mission‑Critical Test Intelligence

**MCTI** ist eine interaktive Webanwendung zur Simulation, Analyse und
Visualisierung von Testabläufen in sicherheitskritischen Software‑ und
Hardwareumgebungen.  
Sie dient als **Portfolio‑Projekt**, um moderne Test-&Traceability‑Ketten und Labor‑Workflows realistisch, aber vollständig synthetisch darzustellen und einige Systeme wie das HF Modul nur in Verbindung mit echter Hardware funktionsfähig.

👉 Live-Demo: https://mcti.maazi.de  
👉 Portfolio: https://maazi.de

---

## 🚦 Zweck dieses Projekts

MCTI zeigt, wie komplexe Testprozesse in sicherheitskritischen Bereichen
transparent, nachvollziehbar und strukturiert dargestellt werden können:

- Anforderungen → Szenarien → Testläufe → Ergebnisse → Befunde
- Labor‑Assets → Revisionen → Messwerte → QA → NCR
- Vollständige Traceability und Auditierbarkeit
- Regelbasierte Analyse ohne Blackbox‑Modelle

---

## 🧭 Was die Demo zeigt (Funktionsüberblick)

Die Webanwendung besteht aus mehreren Modulen, die typische Abläufe aus
Testlaboren und sicherheitskritischen Entwicklungsprojekten simulieren:

### **Dashboard**

Verdichtetes Lagebild: Systemgesundheit, offene Befunde, Testabdeckung,
Teststand‑Status und letzte Testläufe.

### **Anforderungen**

Synthetische Anforderungen mit Safety‑Level (ISO 26262 / DO‑178C) und
V‑Modell‑Phasenbezug.

### **Szenario‑Designer**

Ausführbare Schrittfolgen (DSL) mit Bezug zu Anforderungen und Testphasen.

### **Testläufe**

Simulierte Ausführung gegen virtuelle Teststände inkl. Preflight‑Prüfung,
Konfigurationsbezug und reproduzierbaren Ergebnissen.

### **Telemetrie**

Live‑ und Playback‑Ansicht synthetischer Sensordaten (nur in Verbindung mit echter Hardware funktionsfähig):
Temperatur, Druck, Vibration, Latenzen, GNSS‑Werte, Versorgungsspannung usw.

### **Fault‑Injection**

Gezielte Störungen wie Sensor‑Ausfall, Bus‑Störung oder GNSS‑Verlust —
bewertet wird die Erkennung, nicht der Fehler selbst.

### **Bug‑Lifecycle**

Severity und Priority getrennt, vollständig nachvollziehbare Berechnung,
regelbasierte Workflows und RCA‑Pflicht.

### **Health‑Score**

Offengelegte Kennzahlen und Gewichte, interaktive Simulation der
Systemgesundheit.

### **Teststände**

Synthetisches Inventar mit Freigabe‑Workflow (Vier‑Augen‑Prinzip),
Firmware‑Ständen und Kompatibilitätsmatrix.

### **Labor‑Assets**

Synthetische Geräte, Revisionen, QA‑Abnahmen und NCR‑Prozesse.

### **HF‑Labor**

R&S‑orientierte HF‑Simulatoren (Spektrumanalysator, VNA) mit sicherer
Whitelist‑Konsole und synthetischen Sweeps (nur in Verbindung mit echter Hardware funktionsfähig):

### **Traceability**

Matrix von Anforderung → Szenario → Ergebnis → Befund, inkl. regelbasierter
Analyse.

### **Audit‑Log**

Append‑only‑Audit mit Live‑WebSocket‑Feed und vollständiger Transparenz.

---

## 🎯 Ziel dieses Repositories

- Präsentation der Webapplikation als realer **Showcase**
- Screenshots, Bilder und Beschreibungen (- Link zur Live‑Demo)

---

## 🌐 Links

- **Live-Demo:** https://mcti.maazi.de
- **Portfolio:** https://maazi.de

---

## 📄 Lizenz

Dieses Projekt ist ein privates Portfolio‑Demo‑Projekt.  
Die Inhalte dürfen nicht für produktive Systeme oder reale Testumgebungen
verwendet werden.
