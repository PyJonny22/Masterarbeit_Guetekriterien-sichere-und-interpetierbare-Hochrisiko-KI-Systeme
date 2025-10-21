# Masterarbeit: Gütekriterien sicherer und interpretierbarer Hochrisiko-KI-Systeme

Dieses Repository dient als **technischer Anhang** zum Evaluationskapitel der Masterarbeit  
**„Sicherheit als Verstehen, Verstehen als Vertrauen – Theoretische Herleitung und angewandte Evaluation von Gütekriterien zur Erfüllung rechtlicher und ethischer Anforderungen an sichere und interpretierbare KI-Systeme“**.

---

## Ziel und Kontext

Im Zentrum steht die Entwicklung und exemplarische Anwendung von **Gütekriterien** für die Bewertung von Hochrisiko-KI-Systemen im Kreditkontext.  
Das Repository dokumentiert den **technischen Teil** der Arbeit – von der Datendekodierung über die Modellierung bis zur Evaluierung der epistemologischen Metriken.

---

## Inhalte

### 🧩 Jupyter-Notebooks

| Notebook | Beschreibung |
|-----------|---------------|
| **German Credit Data Lesbar** | Enthält die Dekodierung und Aufbereitung des *German Credit Data*-Datensatzes. |
| **German Credit ANN** | Implementiert das künstliche neuronale Netz (ANN), das auf dem *German Credit Data*-Datensatz trainiert wird. |
| **Selection** | Skript zur Auswahl von zehn möglichst diversen Profilen aus dem Datensatz auf Basis einer Distanz- und Clustering-Heuristik. |
| **Evaluation** | Berechnet die **α- (Notwendigkeit)** und **β- (Hinreichendkeits)**-Metriken für die ausgewählten Profile und visualisiert die Ergebnisse. |

---

### Ergebnisdateien

| Datei | Beschreibung |
|--------|---------------|
| **diverse_profiles.csv** | Die zehn im *Selection*-Notebook ermittelten, diversesten Profile. |
| **profilbericht_alpha_beta_twostage.md** | Der vollständige Profilbericht mit den Ergebnissen der Evaluation (α/β-Metriken) und einer aggregierten Analyse. |

---

## Reproduktion

### Voraussetzungen

- Python ≥ 3.10  
- Jupyter Notebook oder JupyterLab  
- Folgende Python-Bibliotheken:
  ```bash
  pip install numpy pandas torch matplotlib seaborn scikit-learn
