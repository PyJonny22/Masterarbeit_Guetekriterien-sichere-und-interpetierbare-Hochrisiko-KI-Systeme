# Masterarbeit: Gütekriterien für sichere und interpretierbare Hochrisiko-KI-Systeme

Dieses Repository dient als **technischer Anhang** zum programmbasierten Teil der Evaluation der Masterarbeit mit dem Titel **„Sicherheit als Verstehen, Verstehen als Vertrauen – Theoretische Herleitung und angewandte Evaluation von Gütekriterien zur Erfüllung rechtlicher und ethischer Anforderungen an sichere und interpretierbare KI-Systeme“**.

---


## Ziel 
Die Schritte 14-22 aus dem Ablaufplan (Kapitel 7.4) adressieren die praktische Umsetzung dieser Gütekriterien. Die kleine Fallstudie dient primär dem Zweck die Umsetzung der technischen Kriterien anhand eines vereinfachten Fallbeispiels zu simulieren. Dadurch werden die bis hierhin etwas abstrakten Gütekriterien für die geneigten Leser:innen anschaulicher und wir können darauf aufbauend Implikationen, Möglichkeiten zur Anwendung und Erweiterungen, sowie Grenzen diskutieren. Im einem realen Fall würden Teile der hier beschrieben Ergebnisse anschließend nochmal in das Informationssicherheitskonzepts, der Betriebsanleitung und das Sicherheitsprotokolls überführt werden. Um Redundanz zu vermeiden, wird auf die Ausformulierung dieser Dokumente verzichtet. 

## Disclaimer
Die Evaluation dient der Veranschaulichung und Problematisierung und nicht dem Zweck eine vollständige und umfassende Validierung dieser Gütekriterien vorzunehmen, dies ließe sich nur anhand einer Serie von Fallstudien mit deutlich komplexeren Modellen und Datensätzen realisieren. Daraus folgt auch insbesondere, dass das hier veranschlagte Modell als auch die generierten Erklärungen nicht für den direkten Praxistransfer geeignet sind. Ich ziele darauf ab, den Grundaufbau plausibel zu simulieren und behaupte nicht, dass die generiere Erklärungslogik in realen Fällen überzeugt. Um die kontextuelle Sachlogik für Kreditanalysen vollständig zu erfassen, wäre eine noch deutlich ausführlichere Evaluation und Auswertung nötig, dies würde jedoch den Rahmen dieser Arbeit sprengen. 

---

## Inhalte

### Jupyter-Notebooks

| Notebook | Beschreibung |
|-----------|---------------|
| **German Credit Data Lesbar** | Enthält den Quellcode für die Dekodierung und Aufbereitung des *German Credit Data*-Datensatzes. |
| **German Credit ANN** | Implementiert das künstliche neuronale Netz (ANN), das auf dem *German Credit Data*-Datensatz trainiert wird. |
| **Selection** | Skript zur Auswahl von zehn möglichst diversen Profilen aus dem Datensatz auf Basis einer Distanz- und Clustering-Heuristik. |
| **Evaluation** | Berechnet die **α- (Notwendigkeit)** und **β- (Hinreichendkeits)**-Metriken für die ausgewählten Profile und visualisiert die Ergebnisse. |

---

### Masterarbeit

| Documents | Beschreibung |
|-----------|---------------|
| **Masterarbeit_Niehus** | Enthält den Gesamttext der fertigen Masterarbeit inklusive Anhang. |

---

### Data

| Documents | Beschreibung |
|-----------|---------------|
| **German.Data** | Enthält den Originaldatensatz in der Standardcodierung. |

---

### Ergebnisdateien

| Datei | Beschreibung |
|--------|---------------|
| **diverse_profiles.csv** | Die zehn im *Selection*-Notebook ermittelten Profile. |
| **profilbericht_alpha_beta_twostage.md** | Der vollständige Profilbericht mit den Ergebnissen der Evaluation (α/β-Metriken) |

---

## Reproduktion

### Voraussetzungen

- Python ≥ 3.10  
- Jupyter Notebook oder JupyterLab  
- Folgende Python-Bibliotheken:
  ```bash
  pip install numpy pandas torch matplotlib seaborn scikit-learn

## Lizenz & Zitation

Diese Arbeit entstand im Rahmen der Masterarbeit an der **Universität Osnabrück** (2025).  
Bitte zitiere bei Verwendung wie folgt:

> Niehus, Jonas (2025): _Sicherheit als Verstehen, Verstehen als Vertrauen._  
> Masterarbeit, Universität Osnabrück. Institut für Kognitionswissenschaften  
> Technischer Anhang: [GitHub-Repository](https://github.com/PyJonny22/Masterarbeit_Guetekriterien-sichere-und-interpetierbare-Hochrisiko-KI-Systeme)

## Lizenz
© 2025 PyJonny22
Der **Code** (z. B. alle Python-Notebooks und Skripte) steht unter der **MIT-Lizenz**.  
Die **Texte, Auswertungen und Dokumente** der Masterarbeit stehen unter der  
**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** Lizenz.

➡️ Siehe [LICENSE](./LICENSE) für vollständige Details.
