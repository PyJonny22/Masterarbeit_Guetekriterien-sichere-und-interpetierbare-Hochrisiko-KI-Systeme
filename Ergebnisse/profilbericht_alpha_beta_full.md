# Profilbericht: α (Notwendigkeit) & β (Suffizienz)

- **Anzahl Profile:** 10
- **Features:** Kreditbetrag, Dauer_in_Monaten, Alter, Status_des_Girokontos, Beschäftigt_seit, Sparkonto_Wertpapiere
- **Hinreichend-Schwelle (β):** β ≥ 0.7

## Aggregierte Feature-Ergebnisse

**α-Rate pro Feature (Anteil notwendig):**

|                       |   alpha_rate |
|:----------------------|-------------:|
| Kreditbetrag          |          0.2 |
| Dauer_in_Monaten      |          0.2 |
| Beschäftigt_seit      |          0.2 |
| Alter                 |          0.1 |
| Status_des_Girokontos |          0.1 |
| Sparkonto_Wertpapiere |          0.1 |

**β-Mean pro Feature (Häufigkeit hinreichend im Mittel):**

|                       |   beta_mean |
|:----------------------|------------:|
| Alter                 |     0.7466  |
| Dauer_in_Monaten      |     0.7261  |
| Status_des_Girokontos |     0.71815 |
| Kreditbetrag          |     0.714   |
| Sparkonto_Wertpapiere |     0.70685 |
| Beschäftigt_seit      |     0.7043  |

## Profil-Ranking nach Explainability-Score

|   profile_index |   alpha_mean |   beta_sufficient_mean |   explainability_score |
|----------------:|-------------:|-----------------------:|-----------------------:|
|               2 |     0.833333 |               1        |              0.916667  |
|               0 |     0        |               1        |              0.5       |
|               9 |     0        |               1        |              0.5       |
|               4 |     0        |               1        |              0.5       |
|               5 |     0        |               1        |              0.5       |
|               6 |     0        |               1        |              0.5       |
|               7 |     0        |               1        |              0.5       |
|               8 |     0        |               0.833333 |              0.416667  |
|               1 |     0.5      |               0        |              0.25      |
|               3 |     0.166667 |               0        |              0.0833333 |

**Top-Profil (höchster Explainability-Score):** 2

**Bottom-Profil (niedrigster Explainability-Score):** 3


---

## Detailansicht je Profil


### Profil 0

| Feature               |   alpha_notwendig |   beta |   hinreichend(β≥0.70) |   ¬alpha_notwendig |   ¬hinreichend |
|:----------------------|------------------:|-------:|----------------------:|-------------------:|---------------:|
| Kreditbetrag          |                 0 | 0.8775 |                     1 |                  1 |              0 |
| Dauer_in_Monaten      |                 0 | 0.8655 |                     1 |                  1 |              0 |
| Alter                 |                 0 | 0.811  |                     1 |                  1 |              0 |
| Status_des_Girokontos |                 0 | 0.746  |                     1 |                  1 |              0 |
| Beschäftigt_seit      |                 0 | 0.9205 |                     1 |                  1 |              0 |
| Sparkonto_Wertpapiere |                 0 | 0.7975 |                     1 |                  1 |              0 |

*alpha_mean:* 0.000 | *beta_sufficient_mean:* 1.000 | *Explainability-Score:* **0.500**


### Profil 1

| Feature               |   alpha_notwendig |   beta |   hinreichend(β≥0.70) |   ¬alpha_notwendig |   ¬hinreichend |
|:----------------------|------------------:|-------:|----------------------:|-------------------:|---------------:|
| Kreditbetrag          |                 1 | 0.4625 |                     0 |                  0 |              1 |
| Dauer_in_Monaten      |                 0 | 0.259  |                     0 |                  1 |              1 |
| Alter                 |                 0 | 0.1495 |                     0 |                  1 |              1 |
| Status_des_Girokontos |                 0 | 0.1505 |                     0 |                  1 |              1 |
| Beschäftigt_seit      |                 1 | 0.178  |                     0 |                  0 |              1 |
| Sparkonto_Wertpapiere |                 1 | 0.1755 |                     0 |                  0 |              1 |

*alpha_mean:* 0.500 | *beta_sufficient_mean:* 0.000 | *Explainability-Score:* **0.250**


### Profil 2

| Feature               |   alpha_notwendig |   beta |   hinreichend(β≥0.70) |   ¬alpha_notwendig |   ¬hinreichend |
|:----------------------|------------------:|-------:|----------------------:|-------------------:|---------------:|
| Kreditbetrag          |                 1 | 0.817  |                     1 |                  0 |              0 |
| Dauer_in_Monaten      |                 1 | 0.893  |                     1 |                  0 |              0 |
| Alter                 |                 1 | 0.9645 |                     1 |                  0 |              0 |
| Status_des_Girokontos |                 1 | 0.84   |                     1 |                  0 |              0 |
| Beschäftigt_seit      |                 1 | 0.8885 |                     1 |                  0 |              0 |
| Sparkonto_Wertpapiere |                 0 | 0.8175 |                     1 |                  1 |              0 |

*alpha_mean:* 0.833 | *beta_sufficient_mean:* 1.000 | *Explainability-Score:* **0.917**


### Profil 3

| Feature               |   alpha_notwendig |   beta |   hinreichend(β≥0.70) |   ¬alpha_notwendig |   ¬hinreichend |
|:----------------------|------------------:|-------:|----------------------:|-------------------:|---------------:|
| Kreditbetrag          |                 0 | 0.2125 |                     0 |                  1 |              1 |
| Dauer_in_Monaten      |                 1 | 0.344  |                     0 |                  0 |              1 |
| Alter                 |                 0 | 0.1415 |                     0 |                  1 |              1 |
| Status_des_Girokontos |                 0 | 0.0385 |                     0 |                  1 |              1 |
| Beschäftigt_seit      |                 0 | 0.1745 |                     0 |                  1 |              1 |
| Sparkonto_Wertpapiere |                 0 | 0.09   |                     0 |                  1 |              1 |

*alpha_mean:* 0.167 | *beta_sufficient_mean:* 0.000 | *Explainability-Score:* **0.083**


### Profil 4

| Feature               |   alpha_notwendig |   beta |   hinreichend(β≥0.70) |   ¬alpha_notwendig |   ¬hinreichend |
|:----------------------|------------------:|-------:|----------------------:|-------------------:|---------------:|
| Kreditbetrag          |                 0 | 0.8785 |                     1 |                  1 |              0 |
| Dauer_in_Monaten      |                 0 | 0.8935 |                     1 |                  1 |              0 |
| Alter                 |                 0 | 0.963  |                     1 |                  1 |              0 |
| Status_des_Girokontos |                 0 | 0.907  |                     1 |                  1 |              0 |
| Beschäftigt_seit      |                 0 | 0.8125 |                     1 |                  1 |              0 |
| Sparkonto_Wertpapiere |                 0 | 0.8095 |                     1 |                  1 |              0 |

*alpha_mean:* 0.000 | *beta_sufficient_mean:* 1.000 | *Explainability-Score:* **0.500**


### Profil 5

| Feature               |   alpha_notwendig |   beta |   hinreichend(β≥0.70) |   ¬alpha_notwendig |   ¬hinreichend |
|:----------------------|------------------:|-------:|----------------------:|-------------------:|---------------:|
| Kreditbetrag          |                 0 | 0.7465 |                     1 |                  1 |              0 |
| Dauer_in_Monaten      |                 0 | 0.779  |                     1 |                  1 |              0 |
| Alter                 |                 0 | 0.881  |                     1 |                  1 |              0 |
| Status_des_Girokontos |                 0 | 0.843  |                     1 |                  1 |              0 |
| Beschäftigt_seit      |                 0 | 0.8845 |                     1 |                  1 |              0 |
| Sparkonto_Wertpapiere |                 0 | 0.837  |                     1 |                  1 |              0 |

*alpha_mean:* 0.000 | *beta_sufficient_mean:* 1.000 | *Explainability-Score:* **0.500**


### Profil 6

| Feature               |   alpha_notwendig |   beta |   hinreichend(β≥0.70) |   ¬alpha_notwendig |   ¬hinreichend |
|:----------------------|------------------:|-------:|----------------------:|-------------------:|---------------:|
| Kreditbetrag          |                 0 | 0.8325 |                     1 |                  1 |              0 |
| Dauer_in_Monaten      |                 0 | 0.889  |                     1 |                  1 |              0 |
| Alter                 |                 0 | 0.8575 |                     1 |                  1 |              0 |
| Status_des_Girokontos |                 0 | 0.9075 |                     1 |                  1 |              0 |
| Beschäftigt_seit      |                 0 | 0.7605 |                     1 |                  1 |              0 |
| Sparkonto_Wertpapiere |                 0 | 0.817  |                     1 |                  1 |              0 |

*alpha_mean:* 0.000 | *beta_sufficient_mean:* 1.000 | *Explainability-Score:* **0.500**


### Profil 7

| Feature               |   alpha_notwendig |   beta |   hinreichend(β≥0.70) |   ¬alpha_notwendig |   ¬hinreichend |
|:----------------------|------------------:|-------:|----------------------:|-------------------:|---------------:|
| Kreditbetrag          |                 0 | 0.776  |                     1 |                  1 |              0 |
| Dauer_in_Monaten      |                 0 | 0.8165 |                     1 |                  1 |              0 |
| Alter                 |                 0 | 0.922  |                     1 |                  1 |              0 |
| Status_des_Girokontos |                 0 | 0.959  |                     1 |                  1 |              0 |
| Beschäftigt_seit      |                 0 | 0.801  |                     1 |                  1 |              0 |
| Sparkonto_Wertpapiere |                 0 | 0.9125 |                     1 |                  1 |              0 |

*alpha_mean:* 0.000 | *beta_sufficient_mean:* 1.000 | *Explainability-Score:* **0.500**


### Profil 8

| Feature               |   alpha_notwendig |   beta |   hinreichend(β≥0.70) |   ¬alpha_notwendig |   ¬hinreichend |
|:----------------------|------------------:|-------:|----------------------:|-------------------:|---------------:|
| Kreditbetrag          |                 0 | 0.7745 |                     1 |                  1 |              0 |
| Dauer_in_Monaten      |                 0 | 0.6685 |                     0 |                  1 |              1 |
| Alter                 |                 0 | 0.8205 |                     1 |                  1 |              0 |
| Status_des_Girokontos |                 0 | 0.8385 |                     1 |                  1 |              0 |
| Beschäftigt_seit      |                 0 | 0.8185 |                     1 |                  1 |              0 |
| Sparkonto_Wertpapiere |                 0 | 0.91   |                     1 |                  1 |              0 |

*alpha_mean:* 0.000 | *beta_sufficient_mean:* 0.833 | *Explainability-Score:* **0.417**


### Profil 9

| Feature               |   alpha_notwendig |   beta |   hinreichend(β≥0.70) |   ¬alpha_notwendig |   ¬hinreichend |
|:----------------------|------------------:|-------:|----------------------:|-------------------:|---------------:|
| Kreditbetrag          |                 0 | 0.7625 |                     1 |                  1 |              0 |
| Dauer_in_Monaten      |                 0 | 0.853  |                     1 |                  1 |              0 |
| Alter                 |                 0 | 0.9555 |                     1 |                  1 |              0 |
| Status_des_Girokontos |                 0 | 0.9515 |                     1 |                  1 |              0 |
| Beschäftigt_seit      |                 0 | 0.8045 |                     1 |                  1 |              0 |
| Sparkonto_Wertpapiere |                 0 | 0.902  |                     1 |                  1 |              0 |

*alpha_mean:* 0.000 | *beta_sufficient_mean:* 1.000 | *Explainability-Score:* **0.500**
