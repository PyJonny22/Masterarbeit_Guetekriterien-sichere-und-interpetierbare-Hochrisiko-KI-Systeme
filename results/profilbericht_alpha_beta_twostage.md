# Profilbericht (zweistufig): α/β je Profil – Ökonomisch vs. Soziodemographisch

- **Anzahl Profile:** 10
- **Hinreichend-Schwelle:** β ≥ 0.7
- **Ökonomische Features:** Kreditbetrag, Dauer_in_Monaten, Ratenhöhe, Anzahl_bestehender_Kredite, Kreditgeschichte, Kreditverwendungszweck, Sparkonto_Wertpapiere, Vermögen, Status_des_Girokontos, Beschäftigt_seit, Andere_Ratenverpflichtungen, Weitere_Bürgen_Schuldner
- **Soziodemographische Features:** Alter, Wohnsitzdauer, Unterhaltspflichtige_Personen, Familienstand_Geschlecht, Wohnsituation, Telefon, Ausländischer_Arbeiter, Beruf

## Überblick (Anzahl notwendiger / hinreichender Features je Stufe)

|   profile_index |   econ_alpha_cnt |   econ_hinr_cnt |   socio_alpha_cnt |   socio_hinr_cnt |
|----------------:|-----------------:|----------------:|------------------:|-----------------:|
|               0 |                7 |              12 |                 2 |                8 |
|               1 |                1 |               0 |                 0 |                0 |
|               2 |                1 |               0 |                 0 |                0 |
|               3 |               11 |              12 |                 6 |                8 |
|               4 |                6 |               0 |                 5 |                0 |
|               5 |               11 |               0 |                 7 |                0 |
|               6 |                1 |               0 |                 0 |                0 |
|               7 |                0 |              12 |                 0 |                8 |
|               8 |                1 |              12 |                 0 |                8 |
|               9 |                2 |              11 |                 3 |                8 |

---

## Details je Profil


### Profil 0


**Ökonomische Features**

| Feature                     |   alpha_notwendig |   beta | α-Details (orig→cf)                                                                                         | β-Details (fixierter Wert)                                                                                         |   hinreichend (β≥0.70) |
|:----------------------------|------------------:|-------:|:------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------|-----------------------:|
| Kreditbetrag                |                 0 | 0.7605 | orig=6458 | keine CF-Änderung                                                                               | a=6458 | β=0.7605 | same/diff=1521/479 | y*=1 (p=0.551)                                                            |                      1 |
| Dauer_in_Monaten            |                 1 | 0.8355 | orig=18 → cf=48 (Δ=30 | p:0.551→0.494 | y:1→0)                                                              | a=18 | β=0.8355 | same/diff=1671/329 | y*=1 (p=0.551)                                                              |                      1 |
| Ratenhöhe                   |                 1 | 0.847  | orig=2 → cf=3.25 (Δ=1.25 | p:0.551→0.491 | y:1→0)                                                           | a=2 | β=0.8470 | same/diff=1694/306 | y*=1 (p=0.551)                                                               |                      1 |
| Anzahl_bestehender_Kredite  |                 0 | 0.764  | orig=2 | keine CF-Änderung                                                                                  | a=2 | β=0.7640 | same/diff=1528/472 | y*=1 (p=0.551)                                                               |                      1 |
| Kreditgeschichte            |                 1 | 0.757  | orig=alle Kredite bei dieser Bank wurden ordnungsgemäß zurückgezahlt → cf=A30 (Δ=— | p:0.551→0.492 | y:1→0) | a=alle Kredite bei dieser Bank wurden ordnungsgemäß zurückgezahlt | β=0.7570 | same/diff=1514/486 | y*=1 (p=0.551) |                      1 |
| Kreditverwendungszweck      |                 1 | 0.7435 | orig=Auto (neu) → cf=A46 (Δ=— | p:0.551→0.475 | y:1→0)                                                      | a=Auto (neu) | β=0.7435 | same/diff=1487/513 | y*=1 (p=0.551)                                                      |                      1 |
| Sparkonto_Wertpapiere       |                 1 | 0.8195 | orig=... < 100 DM → cf=A61 (Δ=— | p:0.551→0.479 | y:1→0)                                                    | a=... < 100 DM | β=0.8195 | same/diff=1639/361 | y*=1 (p=0.551)                                                    |                      1 |
| Vermögen                    |                 0 | 0.78   | orig=unbekannt/kein Eigentum | keine CF-Änderung                                                            | a=unbekannt/kein Eigentum | β=0.7800 | same/diff=1560/440 | y*=1 (p=0.551)                                         |                      1 |
| Status_des_Girokontos       |                 1 | 0.823  | orig=kein Girokonto → cf=A11 (Δ=— | p:0.551→0.474 | y:1→0)                                                  | a=kein Girokonto | β=0.8230 | same/diff=1646/354 | y*=1 (p=0.551)                                                  |                      1 |
| Beschäftigt_seit            |                 0 | 0.7605 | orig=.. >= 7 Jahre | keine CF-Änderung                                                                      | a=.. >= 7 Jahre | β=0.7605 | same/diff=1521/479 | y*=1 (p=0.551)                                                   |                      1 |
| Andere_Ratenverpflichtungen |                 1 | 0.763  | orig=Bank → cf=A141 (Δ=— | p:0.551→0.494 | y:1→0)                                                           | a=Bank | β=0.7630 | same/diff=1526/474 | y*=1 (p=0.551)                                                            |                      1 |
| Weitere_Bürgen_Schuldner    |                 0 | 0.759  | orig=keine | keine CF-Änderung                                                                              | a=keine | β=0.7590 | same/diff=1518/482 | y*=1 (p=0.551)                                                           |                      1 |

**Soziodemographische/sonstige Features**

| Feature                       |   alpha_notwendig |   beta | α-Details (orig→cf)                                                                       | β-Details (fixierter Wert)                                                                                          |   hinreichend (β≥0.70) |
|:------------------------------|------------------:|-------:|:------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------|-----------------------:|
| Alter                         |                 1 | 0.829  | orig=39 → cf=26.75 (Δ=12.25 | p:0.551→0.491 | y:1→0)                                      | a=39 | β=0.8290 | same/diff=1658/342 | y*=1 (p=0.551)                                                               |                      1 |
| Wohnsitzdauer                 |                 0 | 0.7825 | orig=4 | keine CF-Änderung                                                                | a=4 | β=0.7825 | same/diff=1565/435 | y*=1 (p=0.551)                                                                |                      1 |
| Unterhaltspflichtige_Personen |                 1 | 0.7535 | orig=2 → cf=1.125 (Δ=0.875 | p:0.551→0.495 | y:1→0)                                       | a=2 | β=0.7535 | same/diff=1507/493 | y*=1 (p=0.551)                                                                |                      1 |
| Familienstand_Geschlecht      |                 0 | 0.7985 | orig=männlich : ledig | keine CF-Änderung                                                 | a=männlich : ledig | β=0.7985 | same/diff=1597/403 | y*=1 (p=0.551)                                                 |                      1 |
| Wohnsituation                 |                 0 | 0.7925 | orig=Eigentum | keine CF-Änderung                                                         | a=Eigentum | β=0.7925 | same/diff=1585/415 | y*=1 (p=0.551)                                                         |                      1 |
| Telefon                       |                 0 | 0.7655 | orig=ja, unter dem Namen des Kunden registriert | keine CF-Änderung                       | a=ja, unter dem Namen des Kunden registriert | β=0.7655 | same/diff=1531/469 | y*=1 (p=0.551)                       |                      1 |
| Ausländischer_Arbeiter        |                 0 | 0.781  | orig=ja | keine CF-Änderung                                                               | a=ja | β=0.7810 | same/diff=1562/438 | y*=1 (p=0.551)                                                               |                      1 |
| Beruf                         |                 0 | 0.792  | orig=Management/selbstständig/hochqualifizierter Angestellter/Beamter | keine CF-Änderung | a=Management/selbstständig/hochqualifizierter Angestellter/Beamter | β=0.7920 | same/diff=1584/416 | y*=1 (p=0.551) |                      1 |

---

### Profil 1


**Ökonomische Features**

| Feature                     |   alpha_notwendig |   beta | α-Details (orig→cf)                                                                   | β-Details (fixierter Wert)                                                                                      |   hinreichend (β≥0.70) |
|:----------------------------|------------------:|-------:|:--------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------|-----------------------:|
| Kreditbetrag                |                 0 | 0.244  | orig=5595 | keine CF-Änderung                                                         | a=5595 | β=0.2440 | same/diff=488/1512 | y*=0 (p=0.240)                                                         |                      0 |
| Dauer_in_Monaten            |                 1 | 0.68   | orig=72 → cf=32.25 (Δ=39.75 | p:0.240→0.503 | y:0→1)                                  | a=72 | β=0.6800 | same/diff=1360/640 | y*=0 (p=0.240)                                                           |                      0 |
| Ratenhöhe                   |                 0 | 0.157  | orig=2 | keine CF-Änderung                                                            | a=2 | β=0.1570 | same/diff=314/1686 | y*=0 (p=0.240)                                                            |                      0 |
| Anzahl_bestehender_Kredite  |                 0 | 0.22   | orig=1 | keine CF-Änderung                                                            | a=1 | β=0.2200 | same/diff=440/1560 | y*=0 (p=0.240)                                                            |                      0 |
| Kreditgeschichte            |                 0 | 0.251  | orig=bestehende Kredite wurden bisher ordnungsgemäß zurückgezahlt | keine CF-Änderung | a=bestehende Kredite wurden bisher ordnungsgemäß zurückgezahlt | β=0.2510 | same/diff=502/1498 | y*=0 (p=0.240) |                      0 |
| Kreditverwendungszweck      |                 0 | 0.2545 | orig=Radio/TV | keine CF-Änderung                                                     | a=Radio/TV | β=0.2545 | same/diff=509/1491 | y*=0 (p=0.240)                                                     |                      0 |
| Sparkonto_Wertpapiere       |                 0 | 0.192  | orig=100 <= ... < 500 DM | keine CF-Änderung                                          | a=100 <= ... < 500 DM | β=0.1920 | same/diff=384/1616 | y*=0 (p=0.240)                                          |                      0 |
| Vermögen                    |                 0 | 0.24   | orig=wenn nicht A121/A122: Auto oder anderes, nicht in Attribut 6 | keine CF-Änderung | a=wenn nicht A121/A122: Auto oder anderes, nicht in Attribut 6 | β=0.2400 | same/diff=480/1520 | y*=0 (p=0.240) |                      0 |
| Status_des_Girokontos       |                 0 | 0.188  | orig=0 <= ... < 200 DM | keine CF-Änderung                                            | a=0 <= ... < 200 DM | β=0.1880 | same/diff=376/1624 | y*=0 (p=0.240)                                            |                      0 |
| Beschäftigt_seit            |                 0 | 0.2515 | orig=1 <= ... < 4 Jahre | keine CF-Änderung                                           | a=1 <= ... < 4 Jahre | β=0.2515 | same/diff=503/1497 | y*=0 (p=0.240)                                           |                      0 |
| Andere_Ratenverpflichtungen |                 0 | 0.2425 | orig=Keine | keine CF-Änderung                                                        | a=Keine | β=0.2425 | same/diff=485/1515 | y*=0 (p=0.240)                                                        |                      0 |
| Weitere_Bürgen_Schuldner    |                 0 | 0.253  | orig=keine | keine CF-Änderung                                                        | a=keine | β=0.2530 | same/diff=506/1494 | y*=0 (p=0.240)                                                        |                      0 |

**Soziodemographische/sonstige Features**

| Feature                       |   alpha_notwendig |   beta | α-Details (orig→cf)                                     | β-Details (fixierter Wert)                                                        |   hinreichend (β≥0.70) |
|:------------------------------|------------------:|-------:|:--------------------------------------------------------|:----------------------------------------------------------------------------------|-----------------------:|
| Alter                         |                 0 | 0.2885 | orig=24 | keine CF-Änderung                             | a=24 | β=0.2885 | same/diff=577/1423 | y*=0 (p=0.240)                             |                      0 |
| Wohnsitzdauer                 |                 0 | 0.211  | orig=2 | keine CF-Änderung                              | a=2 | β=0.2110 | same/diff=422/1578 | y*=0 (p=0.240)                              |                      0 |
| Unterhaltspflichtige_Personen |                 0 | 0.2145 | orig=1 | keine CF-Änderung                              | a=1 | β=0.2145 | same/diff=429/1571 | y*=0 (p=0.240)                              |                      0 |
| Familienstand_Geschlecht      |                 0 | 0.2045 | orig=männlich : verheiratet/witwer | keine CF-Änderung  | a=männlich : verheiratet/witwer | β=0.2045 | same/diff=409/1591 | y*=0 (p=0.240)  |                      0 |
| Wohnsituation                 |                 0 | 0.217  | orig=Eigentum | keine CF-Änderung                       | a=Eigentum | β=0.2170 | same/diff=434/1566 | y*=0 (p=0.240)                       |                      0 |
| Telefon                       |                 0 | 0.2445 | orig=kein Telefon | keine CF-Änderung                   | a=kein Telefon | β=0.2445 | same/diff=489/1511 | y*=0 (p=0.240)                   |                      0 |
| Ausländischer_Arbeiter        |                 0 | 0.222  | orig=ja | keine CF-Änderung                             | a=ja | β=0.2220 | same/diff=444/1556 | y*=0 (p=0.240)                             |                      0 |
| Beruf                         |                 0 | 0.2165 | orig=gelernt - Angestellter/Beamter | keine CF-Änderung | a=gelernt - Angestellter/Beamter | β=0.2165 | same/diff=433/1567 | y*=0 (p=0.240) |                      0 |

---

### Profil 2


**Ökonomische Features**

| Feature                     |   alpha_notwendig |   beta | α-Details (orig→cf)                                                                   | β-Details (fixierter Wert)                                                                                      |   hinreichend (β≥0.70) |
|:----------------------------|------------------:|-------:|:--------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------|-----------------------:|
| Kreditbetrag                |                 0 | 0.1875 | orig=951 | keine CF-Änderung                                                          | a=951 | β=0.1875 | same/diff=375/1625 | y*=0 (p=0.205)                                                          |                      0 |
| Dauer_in_Monaten            |                 0 | 0.143  | orig=12 | keine CF-Änderung                                                           | a=12 | β=0.1430 | same/diff=286/1714 | y*=0 (p=0.205)                                                           |                      0 |
| Ratenhöhe                   |                 0 | 0.2705 | orig=4 | keine CF-Änderung                                                            | a=4 | β=0.2705 | same/diff=541/1459 | y*=0 (p=0.205)                                                            |                      0 |
| Anzahl_bestehender_Kredite  |                 1 | 0.3605 | orig=4 → cf=1.25 (Δ=2.75 | p:0.205→0.501 | y:0→1)                                     | a=4 | β=0.3605 | same/diff=721/1279 | y*=0 (p=0.205)                                                            |                      0 |
| Kreditgeschichte            |                 0 | 0.253  | orig=bestehende Kredite wurden bisher ordnungsgemäß zurückgezahlt | keine CF-Änderung | a=bestehende Kredite wurden bisher ordnungsgemäß zurückgezahlt | β=0.2530 | same/diff=506/1494 | y*=0 (p=0.205) |                      0 |
| Kreditverwendungszweck      |                 0 | 0.257  | orig=Möbel/Ausstattung | keine CF-Änderung                                            | a=Möbel/Ausstattung | β=0.2570 | same/diff=514/1486 | y*=0 (p=0.205)                                            |                      0 |
| Sparkonto_Wertpapiere       |                 0 | 0.1955 | orig=100 <= ... < 500 DM | keine CF-Änderung                                          | a=100 <= ... < 500 DM | β=0.1955 | same/diff=391/1609 | y*=0 (p=0.205)                                          |                      0 |
| Vermögen                    |                 0 | 0.239  | orig=wenn nicht A121/A122: Auto oder anderes, nicht in Attribut 6 | keine CF-Änderung | a=wenn nicht A121/A122: Auto oder anderes, nicht in Attribut 6 | β=0.2390 | same/diff=478/1522 | y*=0 (p=0.205) |                      0 |
| Status_des_Girokontos       |                 0 | 0.1915 | orig=0 <= ... < 200 DM | keine CF-Änderung                                            | a=0 <= ... < 200 DM | β=0.1915 | same/diff=383/1617 | y*=0 (p=0.205)                                            |                      0 |
| Beschäftigt_seit            |                 0 | 0.2535 | orig=... < 1 Jahr | keine CF-Änderung                                                 | a=... < 1 Jahr | β=0.2535 | same/diff=507/1493 | y*=0 (p=0.205)                                                 |                      0 |
| Andere_Ratenverpflichtungen |                 0 | 0.247  | orig=Bank | keine CF-Änderung                                                         | a=Bank | β=0.2470 | same/diff=494/1506 | y*=0 (p=0.205)                                                         |                      0 |
| Weitere_Bürgen_Schuldner    |                 0 | 0.2475 | orig=keine | keine CF-Änderung                                                        | a=keine | β=0.2475 | same/diff=495/1505 | y*=0 (p=0.205)                                                        |                      0 |

**Soziodemographische/sonstige Features**

| Feature                       |   alpha_notwendig |   beta | α-Details (orig→cf)                                                 | β-Details (fixierter Wert)                                                                    |   hinreichend (β≥0.70) |
|:------------------------------|------------------:|-------:|:--------------------------------------------------------------------|:----------------------------------------------------------------------------------------------|-----------------------:|
| Alter                         |                 0 | 0.2685 | orig=27 | keine CF-Änderung                                         | a=27 | β=0.2685 | same/diff=537/1463 | y*=0 (p=0.205)                                         |                      0 |
| Wohnsitzdauer                 |                 0 | 0.2195 | orig=4 | keine CF-Änderung                                          | a=4 | β=0.2195 | same/diff=439/1561 | y*=0 (p=0.205)                                          |                      0 |
| Unterhaltspflichtige_Personen |                 0 | 0.2185 | orig=1 | keine CF-Änderung                                          | a=1 | β=0.2185 | same/diff=437/1563 | y*=0 (p=0.205)                                          |                      0 |
| Familienstand_Geschlecht      |                 0 | 0.203  | orig=weiblich : geschieden/getrennt/verheiratet | keine CF-Änderung | a=weiblich : geschieden/getrennt/verheiratet | β=0.2030 | same/diff=406/1594 | y*=0 (p=0.205) |                      0 |
| Wohnsituation                 |                 0 | 0.2155 | orig=Miete | keine CF-Änderung                                      | a=Miete | β=0.2155 | same/diff=431/1569 | y*=0 (p=0.205)                                      |                      0 |
| Telefon                       |                 0 | 0.243  | orig=kein Telefon | keine CF-Änderung                               | a=kein Telefon | β=0.2430 | same/diff=486/1514 | y*=0 (p=0.205)                               |                      0 |
| Ausländischer_Arbeiter        |                 0 | 0.228  | orig=ja | keine CF-Änderung                                         | a=ja | β=0.2280 | same/diff=456/1544 | y*=0 (p=0.205)                                         |                      0 |
| Beruf                         |                 0 | 0.214  | orig=gelernt - Angestellter/Beamter | keine CF-Änderung             | a=gelernt - Angestellter/Beamter | β=0.2140 | same/diff=428/1572 | y*=0 (p=0.205)             |                      0 |

---

### Profil 3


**Ökonomische Features**

| Feature                     |   alpha_notwendig |   beta | α-Details (orig→cf)                                                                                         | β-Details (fixierter Wert)                                                                                         |   hinreichend (β≥0.70) |
|:----------------------------|------------------:|-------:|:------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------|-----------------------:|
| Kreditbetrag                |                 1 | 0.8035 | orig=609 → cf=1766 (Δ=1157 | p:0.502→0.499 | y:1→0)                                                         | a=609 | β=0.8035 | same/diff=1607/393 | y*=1 (p=0.502)                                                             |                      1 |
| Dauer_in_Monaten            |                 1 | 0.8555 | orig=12 → cf=16.5 (Δ=4.5 | p:0.502→0.473 | y:1→0)                                                           | a=12 | β=0.8555 | same/diff=1711/289 | y*=1 (p=0.502)                                                              |                      1 |
| Ratenhöhe                   |                 0 | 0.7105 | orig=4 | keine CF-Änderung                                                                                  | a=4 | β=0.7105 | same/diff=1421/579 | y*=1 (p=0.502)                                                               |                      1 |
| Anzahl_bestehender_Kredite  |                 1 | 0.775  | orig=1 → cf=1.125 (Δ=0.125 | p:0.502→0.499 | y:1→0)                                                         | a=1 | β=0.7750 | same/diff=1550/450 | y*=1 (p=0.502)                                                               |                      1 |
| Kreditgeschichte            |                 1 | 0.745  | orig=alle Kredite bei dieser Bank wurden ordnungsgemäß zurückgezahlt → cf=A30 (Δ=— | p:0.502→0.366 | y:1→0) | a=alle Kredite bei dieser Bank wurden ordnungsgemäß zurückgezahlt | β=0.7450 | same/diff=1490/510 | y*=1 (p=0.502) |                      1 |
| Kreditverwendungszweck      |                 1 | 0.7345 | orig=Geschäft → cf=A40 (Δ=— | p:0.502→0.487 | y:1→0)                                                        | a=Geschäft | β=0.7345 | same/diff=1469/531 | y*=1 (p=0.502)                                                        |                      1 |
| Sparkonto_Wertpapiere       |                 1 | 0.8085 | orig=... < 100 DM → cf=A61 (Δ=— | p:0.502→0.439 | y:1→0)                                                    | a=... < 100 DM | β=0.8085 | same/diff=1617/383 | y*=1 (p=0.502)                                                    |                      1 |
| Vermögen                    |                 1 | 0.7465 | orig=Immobilie → cf=A122 (Δ=— | p:0.502→0.493 | y:1→0)                                                      | a=Immobilie | β=0.7465 | same/diff=1493/507 | y*=1 (p=0.502)                                                       |                      1 |
| Status_des_Girokontos       |                 1 | 0.8205 | orig=... >= 200 DM / Gehaltspfändung mindestens 1 Jahr → cf=A11 (Δ=— | p:0.502→0.397 | y:1→0)               | a=... >= 200 DM / Gehaltspfändung mindestens 1 Jahr | β=0.8205 | same/diff=1641/359 | y*=1 (p=0.502)               |                      1 |
| Beschäftigt_seit            |                 1 | 0.738  | orig=... < 1 Jahr → cf=A71 (Δ=— | p:0.502→0.427 | y:1→0)                                                    | a=... < 1 Jahr | β=0.7380 | same/diff=1476/524 | y*=1 (p=0.502)                                                    |                      1 |
| Andere_Ratenverpflichtungen |                 1 | 0.7395 | orig=Keine → cf=A141 (Δ=— | p:0.502→0.487 | y:1→0)                                                          | a=Keine | β=0.7395 | same/diff=1479/521 | y*=1 (p=0.502)                                                           |                      1 |
| Weitere_Bürgen_Schuldner    |                 1 | 0.7415 | orig=keine → cf=A101 (Δ=— | p:0.502→0.489 | y:1→0)                                                          | a=keine | β=0.7415 | same/diff=1483/517 | y*=1 (p=0.502)                                                           |                      1 |

**Soziodemographische/sonstige Features**

| Feature                       |   alpha_notwendig |   beta | α-Details (orig→cf)                                                                    | β-Details (fixierter Wert)                                                                    |   hinreichend (β≥0.70) |
|:------------------------------|------------------:|-------:|:---------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------|-----------------------:|
| Alter                         |                 1 | 0.742  | orig=26 → cf=22 (Δ=4 | p:0.502→0.490 | y:1→0)                                          | a=26 | β=0.7420 | same/diff=1484/516 | y*=1 (p=0.502)                                         |                      1 |
| Wohnsitzdauer                 |                 0 | 0.809  | orig=1 | keine CF-Änderung                                                             | a=1 | β=0.8090 | same/diff=1618/382 | y*=1 (p=0.502)                                          |                      1 |
| Unterhaltspflichtige_Personen |                 1 | 0.796  | orig=1 → cf=1.125 (Δ=0.125 | p:0.502→0.488 | y:1→0)                                    | a=1 | β=0.7960 | same/diff=1592/408 | y*=1 (p=0.502)                                          |                      1 |
| Familienstand_Geschlecht      |                 1 | 0.8035 | orig=weiblich : geschieden/getrennt/verheiratet → cf=A91 (Δ=— | p:0.502→0.474 | y:1→0) | a=weiblich : geschieden/getrennt/verheiratet | β=0.8035 | same/diff=1607/393 | y*=1 (p=0.502) |                      1 |
| Wohnsituation                 |                 1 | 0.7975 | orig=Eigentum → cf=A151 (Δ=— | p:0.502→0.483 | y:1→0)                                  | a=Eigentum | β=0.7975 | same/diff=1595/405 | y*=1 (p=0.502)                                   |                      1 |
| Telefon                       |                 1 | 0.7695 | orig=kein Telefon → cf=A191 (Δ=— | p:0.502→0.479 | y:1→0)                              | a=kein Telefon | β=0.7695 | same/diff=1539/461 | y*=1 (p=0.502)                               |                      1 |
| Ausländischer_Arbeiter        |                 0 | 0.7875 | orig=ja | keine CF-Änderung                                                            | a=ja | β=0.7875 | same/diff=1575/425 | y*=1 (p=0.502)                                         |                      1 |
| Beruf                         |                 1 | 0.8015 | orig=arbeitslos/ungelernt - nicht ansässig → cf=A171 (Δ=— | p:0.502→0.476 | y:1→0)     | a=arbeitslos/ungelernt - nicht ansässig | β=0.8015 | same/diff=1603/397 | y*=1 (p=0.502)      |                      1 |

---

### Profil 4


**Ökonomische Features**

| Feature                     |   alpha_notwendig |   beta | α-Details (orig→cf)                                                                                                     | β-Details (fixierter Wert)                                                                                                     |   hinreichend (β≥0.70) |
|:----------------------------|------------------:|-------:|:------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------|-----------------------:|
| Kreditbetrag                |                 0 | 0.3855 | orig=1.594e+04 | keine CF-Änderung                                                                                      | a=1.594e+04 | β=0.3855 | same/diff=771/1229 | y*=0 (p=0.478)                                                                   |                      0 |
| Dauer_in_Monaten            |                 1 | 0.501  | orig=54 → cf=48 (Δ=6 | p:0.478→0.510 | y:0→1)                                                                           | a=54 | β=0.5010 | same/diff=1002/998 | y*=0 (p=0.478)                                                                          |                      0 |
| Ratenhöhe                   |                 0 | 0.2105 | orig=3 | keine CF-Änderung                                                                                              | a=3 | β=0.2105 | same/diff=421/1579 | y*=0 (p=0.478)                                                                           |                      0 |
| Anzahl_bestehender_Kredite  |                 0 | 0.216  | orig=1 | keine CF-Änderung                                                                                              | a=1 | β=0.2160 | same/diff=432/1568 | y*=0 (p=0.478)                                                                           |                      0 |
| Kreditgeschichte            |                 1 | 0.252  | orig=keine Kredite aufgenommen / alle Kredite wurden ordnungsgemäß zurückgezahlt → cf=A33 (Δ=— | p:0.478→0.524 | y:0→1) | a=keine Kredite aufgenommen / alle Kredite wurden ordnungsgemäß zurückgezahlt | β=0.2520 | same/diff=504/1496 | y*=0 (p=0.478) |                      0 |
| Kreditverwendungszweck      |                 1 | 0.257  | orig=Geschäft → cf=A40 (Δ=— | p:0.478→0.509 | y:0→1)                                                                    | a=Geschäft | β=0.2570 | same/diff=514/1486 | y*=0 (p=0.478)                                                                    |                      0 |
| Sparkonto_Wertpapiere       |                 0 | 0.193  | orig=... < 100 DM | keine CF-Änderung                                                                                   | a=... < 100 DM | β=0.1930 | same/diff=386/1614 | y*=0 (p=0.478)                                                                |                      0 |
| Vermögen                    |                 1 | 0.238  | orig=unbekannt/kein Eigentum → cf=A121 (Δ=— | p:0.478→0.526 | y:0→1)                                                    | a=unbekannt/kein Eigentum | β=0.2380 | same/diff=476/1524 | y*=0 (p=0.478)                                                     |                      0 |
| Status_des_Girokontos       |                 1 | 0.196  | orig=0 <= ... < 200 DM → cf=A13 (Δ=— | p:0.478→0.524 | y:0→1)                                                           | a=0 <= ... < 200 DM | β=0.1960 | same/diff=392/1608 | y*=0 (p=0.478)                                                           |                      0 |
| Beschäftigt_seit            |                 1 | 0.2525 | orig=... < 1 Jahr → cf=A75 (Δ=— | p:0.478→0.501 | y:0→1)                                                                | a=... < 1 Jahr | β=0.2525 | same/diff=505/1495 | y*=0 (p=0.478)                                                                |                      0 |
| Andere_Ratenverpflichtungen |                 0 | 0.2455 | orig=Keine | keine CF-Änderung                                                                                          | a=Keine | β=0.2455 | same/diff=491/1509 | y*=0 (p=0.478)                                                                       |                      0 |
| Weitere_Bürgen_Schuldner    |                 0 | 0.2525 | orig=keine | keine CF-Änderung                                                                                          | a=keine | β=0.2525 | same/diff=505/1495 | y*=0 (p=0.478)                                                                       |                      0 |

**Soziodemographische/sonstige Features**

| Feature                       |   alpha_notwendig |   beta | α-Details (orig→cf)                                                                     | β-Details (fixierter Wert)                                                                    |   hinreichend (β≥0.70) |
|:------------------------------|------------------:|-------:|:----------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------|-----------------------:|
| Alter                         |                 0 | 0.081  | orig=58 | keine CF-Änderung                                                             | a=58 | β=0.0810 | same/diff=162/1838 | y*=0 (p=0.478)                                         |                      0 |
| Wohnsitzdauer                 |                 1 | 0.2285 | orig=4 → cf=2.875 (Δ=1.125 | p:0.478→0.505 | y:0→1)                                     | a=4 | β=0.2285 | same/diff=457/1543 | y*=0 (p=0.478)                                          |                      0 |
| Unterhaltspflichtige_Personen |                 1 | 0.219  | orig=1 → cf=1.25 (Δ=0.25 | p:0.478→0.514 | y:0→1)                                       | a=1 | β=0.2190 | same/diff=438/1562 | y*=0 (p=0.478)                                          |                      0 |
| Familienstand_Geschlecht      |                 1 | 0.2025 | orig=männlich : ledig → cf=A91 (Δ=— | p:0.478→0.511 | y:0→1)                            | a=männlich : ledig | β=0.2025 | same/diff=405/1595 | y*=0 (p=0.478)                           |                      0 |
| Wohnsituation                 |                 0 | 0.22   | orig=Miete | keine CF-Änderung                                                          | a=Miete | β=0.2200 | same/diff=440/1560 | y*=0 (p=0.478)                                      |                      0 |
| Telefon                       |                 1 | 0.251  | orig=ja, unter dem Namen des Kunden registriert → cf=A191 (Δ=— | p:0.478→0.536 | y:0→1) | a=ja, unter dem Namen des Kunden registriert | β=0.2510 | same/diff=502/1498 | y*=0 (p=0.478) |                      0 |
| Ausländischer_Arbeiter        |                 0 | 0.2325 | orig=ja | keine CF-Änderung                                                             | a=ja | β=0.2325 | same/diff=465/1535 | y*=0 (p=0.478)                                         |                      0 |
| Beruf                         |                 1 | 0.219  | orig=gelernt - Angestellter/Beamter → cf=A171 (Δ=— | p:0.478→0.506 | y:0→1)             | a=gelernt - Angestellter/Beamter | β=0.2190 | same/diff=438/1562 | y*=0 (p=0.478)             |                      0 |

---

### Profil 5


**Ökonomische Features**

| Feature                     |   alpha_notwendig |   beta | α-Details (orig→cf)                                                                                            | β-Details (fixierter Wert)                                                                                            |   hinreichend (β≥0.70) |
|:----------------------------|------------------:|-------:|:---------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------|-----------------------:|
| Kreditbetrag                |                 0 | 0.2    | orig=2223 | keine CF-Änderung                                                                                  | a=2223 | β=0.2000 | same/diff=400/1600 | y*=0 (p=0.489)                                                               |                      0 |
| Dauer_in_Monaten            |                 1 | 0.209  | orig=24 → cf=21.75 (Δ=2.25 | p:0.489→0.512 | y:0→1)                                                            | a=24 | β=0.2090 | same/diff=418/1582 | y*=0 (p=0.489)                                                                 |                      0 |
| Ratenhöhe                   |                 1 | 0.281  | orig=4 → cf=3.625 (Δ=0.375 | p:0.489→0.521 | y:0→1)                                                            | a=4 | β=0.2810 | same/diff=562/1438 | y*=0 (p=0.489)                                                                  |                      0 |
| Anzahl_bestehender_Kredite  |                 1 | 0.2505 | orig=2 → cf=1.875 (Δ=0.125 | p:0.489→0.505 | y:0→1)                                                            | a=2 | β=0.2505 | same/diff=501/1499 | y*=0 (p=0.489)                                                                  |                      0 |
| Kreditgeschichte            |                 1 | 0.2635 | orig=kritisches Konto / andere Kredite bestehen (nicht bei dieser Bank) → cf=A32 (Δ=— | p:0.489→0.517 | y:0→1) | a=kritisches Konto / andere Kredite bestehen (nicht bei dieser Bank) | β=0.2635 | same/diff=527/1473 | y*=0 (p=0.489) |                      0 |
| Kreditverwendungszweck      |                 1 | 0.273  | orig=Radio/TV → cf=A41 (Δ=— | p:0.489→0.657 | y:0→1)                                                           | a=Radio/TV | β=0.2730 | same/diff=546/1454 | y*=0 (p=0.489)                                                           |                      0 |
| Sparkonto_Wertpapiere       |                 1 | 0.19   | orig=100 <= ... < 500 DM → cf=A63 (Δ=— | p:0.489→0.526 | y:0→1)                                                | a=100 <= ... < 500 DM | β=0.1900 | same/diff=380/1620 | y*=0 (p=0.489)                                                |                      0 |
| Vermögen                    |                 1 | 0.2345 | orig=wenn nicht A121: Bausparvertrag/Lebensversicherung → cf=A121 (Δ=— | p:0.489→0.612 | y:0→1)                | a=wenn nicht A121: Bausparvertrag/Lebensversicherung | β=0.2345 | same/diff=469/1531 | y*=0 (p=0.489)                 |                      0 |
| Status_des_Girokontos       |                 1 | 0.1845 | orig=kein Girokonto → cf=A12 (Δ=— | p:0.489→0.505 | y:0→1)                                                     | a=kein Girokonto | β=0.1845 | same/diff=369/1631 | y*=0 (p=0.489)                                                     |                      0 |
| Beschäftigt_seit            |                 1 | 0.2535 | orig=.. >= 7 Jahre → cf=A72 (Δ=— | p:0.489→0.518 | y:0→1)                                                      | a=.. >= 7 Jahre | β=0.2535 | same/diff=507/1493 | y*=0 (p=0.489)                                                      |                      0 |
| Andere_Ratenverpflichtungen |                 1 | 0.2465 | orig=Bank → cf=A143 (Δ=— | p:0.489→0.536 | y:0→1)                                                              | a=Bank | β=0.2465 | same/diff=493/1507 | y*=0 (p=0.489)                                                               |                      0 |
| Weitere_Bürgen_Schuldner    |                 1 | 0.255  | orig=keine → cf=A101 (Δ=— | p:0.489→0.553 | y:0→1)                                                             | a=keine | β=0.2550 | same/diff=510/1490 | y*=0 (p=0.489)                                                              |                      0 |

**Soziodemographische/sonstige Features**

| Feature                       |   alpha_notwendig |   beta | α-Details (orig→cf)                                                         | β-Details (fixierter Wert)                                                        |   hinreichend (β≥0.70) |
|:------------------------------|------------------:|-------:|:----------------------------------------------------------------------------|:----------------------------------------------------------------------------------|-----------------------:|
| Alter                         |                 1 | 0.1175 | orig=52 → cf=55.25 (Δ=3.25 | p:0.489→0.516 | y:0→1)                         | a=52 | β=0.1175 | same/diff=235/1765 | y*=0 (p=0.489)                             |                      0 |
| Wohnsitzdauer                 |                 1 | 0.2245 | orig=4 → cf=2.875 (Δ=1.125 | p:0.489→0.504 | y:0→1)                         | a=4 | β=0.2245 | same/diff=449/1551 | y*=0 (p=0.489)                              |                      0 |
| Unterhaltspflichtige_Personen |                 1 | 0.2115 | orig=1 → cf=1.125 (Δ=0.125 | p:0.489→0.501 | y:0→1)                         | a=1 | β=0.2115 | same/diff=423/1577 | y*=0 (p=0.489)                              |                      0 |
| Familienstand_Geschlecht      |                 1 | 0.2085 | orig=männlich : ledig → cf=A91 (Δ=— | p:0.489→0.510 | y:0→1)                | a=männlich : ledig | β=0.2085 | same/diff=417/1583 | y*=0 (p=0.489)               |                      0 |
| Wohnsituation                 |                 0 | 0.2175 | orig=Eigentum | keine CF-Änderung                                           | a=Eigentum | β=0.2175 | same/diff=435/1565 | y*=0 (p=0.489)                       |                      0 |
| Telefon                       |                 1 | 0.249  | orig=kein Telefon → cf=A191 (Δ=— | p:0.489→0.532 | y:0→1)                   | a=kein Telefon | β=0.2490 | same/diff=498/1502 | y*=0 (p=0.489)                   |                      0 |
| Ausländischer_Arbeiter        |                 1 | 0.2225 | orig=ja → cf=A202 (Δ=— | p:0.489→0.575 | y:0→1)                             | a=ja | β=0.2225 | same/diff=445/1555 | y*=0 (p=0.489)                             |                      0 |
| Beruf                         |                 1 | 0.211  | orig=gelernt - Angestellter/Beamter → cf=A171 (Δ=— | p:0.489→0.507 | y:0→1) | a=gelernt - Angestellter/Beamter | β=0.2110 | same/diff=422/1578 | y*=0 (p=0.489) |                      0 |

---

### Profil 6


**Ökonomische Features**

| Feature                     |   alpha_notwendig |   beta | α-Details (orig→cf)                                                                   | β-Details (fixierter Wert)                                                                                      |   hinreichend (β≥0.70) |
|:----------------------------|------------------:|-------:|:--------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------|-----------------------:|
| Kreditbetrag                |                 0 | 0.3815 | orig=1.565e+04 | keine CF-Änderung                                                    | a=1.565e+04 | β=0.3815 | same/diff=763/1237 | y*=0 (p=0.228)                                                    |                      0 |
| Dauer_in_Monaten            |                 1 | 0.5705 | orig=60 → cf=11.25 (Δ=48.75 | p:0.228→0.503 | y:0→1)                                  | a=60 | β=0.5705 | same/diff=1141/859 | y*=0 (p=0.228)                                                           |                      0 |
| Ratenhöhe                   |                 0 | 0.163  | orig=2 | keine CF-Änderung                                                            | a=2 | β=0.1630 | same/diff=326/1674 | y*=0 (p=0.228)                                                            |                      0 |
| Anzahl_bestehender_Kredite  |                 0 | 0.2455 | orig=2 | keine CF-Änderung                                                            | a=2 | β=0.2455 | same/diff=491/1509 | y*=0 (p=0.228)                                                            |                      0 |
| Kreditgeschichte            |                 0 | 0.2585 | orig=Verzögerungen bei der Rückzahlung in der Vergangenheit | keine CF-Änderung       | a=Verzögerungen bei der Rückzahlung in der Vergangenheit | β=0.2585 | same/diff=517/1483 | y*=0 (p=0.228)       |                      0 |
| Kreditverwendungszweck      |                 0 | 0.26   | orig=Radio/TV | keine CF-Änderung                                                     | a=Radio/TV | β=0.2600 | same/diff=520/1480 | y*=0 (p=0.228)                                                     |                      0 |
| Sparkonto_Wertpapiere       |                 0 | 0.19   | orig=... < 100 DM | keine CF-Änderung                                                 | a=... < 100 DM | β=0.1900 | same/diff=380/1620 | y*=0 (p=0.228)                                                 |                      0 |
| Vermögen                    |                 0 | 0.2395 | orig=wenn nicht A121/A122: Auto oder anderes, nicht in Attribut 6 | keine CF-Änderung | a=wenn nicht A121/A122: Auto oder anderes, nicht in Attribut 6 | β=0.2395 | same/diff=479/1521 | y*=0 (p=0.228) |                      0 |
| Status_des_Girokontos       |                 0 | 0.1955 | orig=kein Girokonto | keine CF-Änderung                                               | a=kein Girokonto | β=0.1955 | same/diff=391/1609 | y*=0 (p=0.228)                                               |                      0 |
| Beschäftigt_seit            |                 0 | 0.26   | orig=4 <= ... < 7 Jahre | keine CF-Änderung                                           | a=4 <= ... < 7 Jahre | β=0.2600 | same/diff=520/1480 | y*=0 (p=0.228)                                           |                      0 |
| Andere_Ratenverpflichtungen |                 0 | 0.252  | orig=Keine | keine CF-Änderung                                                        | a=Keine | β=0.2520 | same/diff=504/1496 | y*=0 (p=0.228)                                                        |                      0 |
| Weitere_Bürgen_Schuldner    |                 0 | 0.2545 | orig=keine | keine CF-Änderung                                                        | a=keine | β=0.2545 | same/diff=509/1491 | y*=0 (p=0.228)                                                        |                      0 |

**Soziodemographische/sonstige Features**

| Feature                       |   alpha_notwendig |   beta | α-Details (orig→cf)                                                 | β-Details (fixierter Wert)                                                                    |   hinreichend (β≥0.70) |
|:------------------------------|------------------:|-------:|:--------------------------------------------------------------------|:----------------------------------------------------------------------------------------------|-----------------------:|
| Alter                         |                 0 | 0.2925 | orig=21 | keine CF-Änderung                                         | a=21 | β=0.2925 | same/diff=585/1415 | y*=0 (p=0.228)                                         |                      0 |
| Wohnsitzdauer                 |                 0 | 0.2115 | orig=4 | keine CF-Änderung                                          | a=4 | β=0.2115 | same/diff=423/1577 | y*=0 (p=0.228)                                          |                      0 |
| Unterhaltspflichtige_Personen |                 0 | 0.205  | orig=1 | keine CF-Änderung                                          | a=1 | β=0.2050 | same/diff=410/1590 | y*=0 (p=0.228)                                          |                      0 |
| Familienstand_Geschlecht      |                 0 | 0.185  | orig=männlich : ledig | keine CF-Änderung                           | a=männlich : ledig | β=0.1850 | same/diff=370/1630 | y*=0 (p=0.228)                           |                      0 |
| Wohnsituation                 |                 0 | 0.2105 | orig=Eigentum | keine CF-Änderung                                   | a=Eigentum | β=0.2105 | same/diff=421/1579 | y*=0 (p=0.228)                                   |                      0 |
| Telefon                       |                 0 | 0.2285 | orig=ja, unter dem Namen des Kunden registriert | keine CF-Änderung | a=ja, unter dem Namen des Kunden registriert | β=0.2285 | same/diff=457/1543 | y*=0 (p=0.228) |                      0 |
| Ausländischer_Arbeiter        |                 0 | 0.214  | orig=ja | keine CF-Änderung                                         | a=ja | β=0.2140 | same/diff=428/1572 | y*=0 (p=0.228)                                         |                      0 |
| Beruf                         |                 0 | 0.201  | orig=gelernt - Angestellter/Beamter | keine CF-Änderung             | a=gelernt - Angestellter/Beamter | β=0.2010 | same/diff=402/1598 | y*=0 (p=0.228)             |                      0 |

---

### Profil 7


**Ökonomische Features**

| Feature                     |   alpha_notwendig |   beta | α-Details (orig→cf)                                                                         | β-Details (fixierter Wert)                                                                                            |   hinreichend (β≥0.70) |
|:----------------------------|------------------:|-------:|:--------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------|-----------------------:|
| Kreditbetrag                |                 0 | 0.821  | orig=1299 | keine CF-Änderung                                                               | a=1299 | β=0.8210 | same/diff=1642/358 | y*=1 (p=0.662)                                                               |                      1 |
| Dauer_in_Monaten            |                 0 | 0.8985 | orig=6 | keine CF-Änderung                                                                  | a=6 | β=0.8985 | same/diff=1797/203 | y*=1 (p=0.662)                                                                  |                      1 |
| Ratenhöhe                   |                 0 | 0.891  | orig=1 | keine CF-Änderung                                                                  | a=1 | β=0.8910 | same/diff=1782/218 | y*=1 (p=0.662)                                                                  |                      1 |
| Anzahl_bestehender_Kredite  |                 0 | 0.719  | orig=3 | keine CF-Änderung                                                                  | a=3 | β=0.7190 | same/diff=1438/562 | y*=1 (p=0.662)                                                                  |                      1 |
| Kreditgeschichte            |                 0 | 0.752  | orig=kritisches Konto / andere Kredite bestehen (nicht bei dieser Bank) | keine CF-Änderung | a=kritisches Konto / andere Kredite bestehen (nicht bei dieser Bank) | β=0.7520 | same/diff=1504/496 | y*=1 (p=0.662) |                      1 |
| Kreditverwendungszweck      |                 0 | 0.753  | orig=Auto (neu) | keine CF-Änderung                                                         | a=Auto (neu) | β=0.7530 | same/diff=1506/494 | y*=1 (p=0.662)                                                         |                      1 |
| Sparkonto_Wertpapiere       |                 0 | 0.8255 | orig=... < 100 DM | keine CF-Änderung                                                       | a=... < 100 DM | β=0.8255 | same/diff=1651/349 | y*=1 (p=0.662)                                                       |                      1 |
| Vermögen                    |                 0 | 0.7785 | orig=Immobilie | keine CF-Änderung                                                          | a=Immobilie | β=0.7785 | same/diff=1557/443 | y*=1 (p=0.662)                                                          |                      1 |
| Status_des_Girokontos       |                 0 | 0.8225 | orig=... >= 200 DM / Gehaltspfändung mindestens 1 Jahr | keine CF-Änderung                  | a=... >= 200 DM / Gehaltspfändung mindestens 1 Jahr | β=0.8225 | same/diff=1645/355 | y*=1 (p=0.662)                  |                      1 |
| Beschäftigt_seit            |                 0 | 0.765  | orig=1 <= ... < 4 Jahre | keine CF-Änderung                                                 | a=1 <= ... < 4 Jahre | β=0.7650 | same/diff=1530/470 | y*=1 (p=0.662)                                                 |                      1 |
| Andere_Ratenverpflichtungen |                 0 | 0.7675 | orig=Keine | keine CF-Änderung                                                              | a=Keine | β=0.7675 | same/diff=1535/465 | y*=1 (p=0.662)                                                              |                      1 |
| Weitere_Bürgen_Schuldner    |                 0 | 0.766  | orig=keine | keine CF-Änderung                                                              | a=keine | β=0.7660 | same/diff=1532/468 | y*=1 (p=0.662)                                                              |                      1 |

**Soziodemographische/sonstige Features**

| Feature                       |   alpha_notwendig |   beta | α-Details (orig→cf)                                            | β-Details (fixierter Wert)                                                               |   hinreichend (β≥0.70) |
|:------------------------------|------------------:|-------:|:---------------------------------------------------------------|:-----------------------------------------------------------------------------------------|-----------------------:|
| Alter                         |                 0 | 0.9685 | orig=74 | keine CF-Änderung                                    | a=74 | β=0.9685 | same/diff=1937/63 | y*=1 (p=0.662)                                     |                      1 |
| Wohnsitzdauer                 |                 0 | 0.802  | orig=1 | keine CF-Änderung                                     | a=1 | β=0.8020 | same/diff=1604/396 | y*=1 (p=0.662)                                     |                      1 |
| Unterhaltspflichtige_Personen |                 0 | 0.7745 | orig=2 | keine CF-Änderung                                     | a=2 | β=0.7745 | same/diff=1549/451 | y*=1 (p=0.662)                                     |                      1 |
| Familienstand_Geschlecht      |                 0 | 0.804  | orig=männlich : ledig | keine CF-Änderung                      | a=männlich : ledig | β=0.8040 | same/diff=1608/392 | y*=1 (p=0.662)                      |                      1 |
| Wohnsituation                 |                 0 | 0.801  | orig=Eigentum | keine CF-Änderung                              | a=Eigentum | β=0.8010 | same/diff=1602/398 | y*=1 (p=0.662)                              |                      1 |
| Telefon                       |                 0 | 0.7675 | orig=kein Telefon | keine CF-Änderung                          | a=kein Telefon | β=0.7675 | same/diff=1535/465 | y*=1 (p=0.662)                          |                      1 |
| Ausländischer_Arbeiter        |                 0 | 0.7845 | orig=nein | keine CF-Änderung                                  | a=nein | β=0.7845 | same/diff=1569/431 | y*=1 (p=0.662)                                  |                      1 |
| Beruf                         |                 0 | 0.792  | orig=arbeitslos/ungelernt - nicht ansässig | keine CF-Änderung | a=arbeitslos/ungelernt - nicht ansässig | β=0.7920 | same/diff=1584/416 | y*=1 (p=0.662) |                      1 |

---

### Profil 8


**Ökonomische Features**

| Feature                     |   alpha_notwendig |   beta | α-Details (orig→cf)                                                                   | β-Details (fixierter Wert)                                                                                      |   hinreichend (β≥0.70) |
|:----------------------------|------------------:|-------:|:--------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------|-----------------------:|
| Kreditbetrag                |                 0 | 0.816  | orig=601 | keine CF-Änderung                                                          | a=601 | β=0.8160 | same/diff=1632/368 | y*=1 (p=0.610)                                                          |                      1 |
| Dauer_in_Monaten            |                 0 | 0.903  | orig=4 | keine CF-Änderung                                                            | a=4 | β=0.9030 | same/diff=1806/194 | y*=1 (p=0.610)                                                            |                      1 |
| Ratenhöhe                   |                 1 | 0.874  | orig=1 → cf=3.625 (Δ=2.625 | p:0.610→0.483 | y:1→0)                                   | a=1 | β=0.8740 | same/diff=1748/252 | y*=1 (p=0.610)                                                            |                      1 |
| Anzahl_bestehender_Kredite  |                 0 | 0.7875 | orig=1 | keine CF-Änderung                                                            | a=1 | β=0.7875 | same/diff=1575/425 | y*=1 (p=0.610)                                                            |                      1 |
| Kreditgeschichte            |                 0 | 0.7525 | orig=bestehende Kredite wurden bisher ordnungsgemäß zurückgezahlt | keine CF-Änderung | a=bestehende Kredite wurden bisher ordnungsgemäß zurückgezahlt | β=0.7525 | same/diff=1505/495 | y*=1 (p=0.610) |                      1 |
| Kreditverwendungszweck      |                 0 | 0.7525 | orig=Möbel/Ausstattung | keine CF-Änderung                                            | a=Möbel/Ausstattung | β=0.7525 | same/diff=1505/495 | y*=1 (p=0.610)                                            |                      1 |
| Sparkonto_Wertpapiere       |                 0 | 0.8205 | orig=... < 100 DM | keine CF-Änderung                                                 | a=... < 100 DM | β=0.8205 | same/diff=1641/359 | y*=1 (p=0.610)                                                 |                      1 |
| Vermögen                    |                 0 | 0.7715 | orig=Immobilie | keine CF-Änderung                                                    | a=Immobilie | β=0.7715 | same/diff=1543/457 | y*=1 (p=0.610)                                                    |                      1 |
| Status_des_Girokontos       |                 0 | 0.8175 | orig=kein Girokonto | keine CF-Änderung                                               | a=kein Girokonto | β=0.8175 | same/diff=1635/365 | y*=1 (p=0.610)                                               |                      1 |
| Beschäftigt_seit            |                 0 | 0.756  | orig=... < 1 Jahr | keine CF-Änderung                                                 | a=... < 1 Jahr | β=0.7560 | same/diff=1512/488 | y*=1 (p=0.610)                                                 |                      1 |
| Andere_Ratenverpflichtungen |                 0 | 0.759  | orig=Keine | keine CF-Änderung                                                        | a=Keine | β=0.7590 | same/diff=1518/482 | y*=1 (p=0.610)                                                        |                      1 |
| Weitere_Bürgen_Schuldner    |                 0 | 0.759  | orig=keine | keine CF-Änderung                                                        | a=keine | β=0.7590 | same/diff=1518/482 | y*=1 (p=0.610)                                                        |                      1 |

**Soziodemographische/sonstige Features**

| Feature                       |   alpha_notwendig |   beta | α-Details (orig→cf)                                                 | β-Details (fixierter Wert)                                                                    |   hinreichend (β≥0.70) |
|:------------------------------|------------------:|-------:|:--------------------------------------------------------------------|:----------------------------------------------------------------------------------------------|-----------------------:|
| Alter                         |                 0 | 0.712  | orig=23 | keine CF-Änderung                                         | a=23 | β=0.7120 | same/diff=1424/576 | y*=1 (p=0.610)                                         |                      1 |
| Wohnsitzdauer                 |                 0 | 0.7845 | orig=3 | keine CF-Änderung                                          | a=3 | β=0.7845 | same/diff=1569/431 | y*=1 (p=0.610)                                          |                      1 |
| Unterhaltspflichtige_Personen |                 0 | 0.761  | orig=2 | keine CF-Änderung                                          | a=2 | β=0.7610 | same/diff=1522/478 | y*=1 (p=0.610)                                          |                      1 |
| Familienstand_Geschlecht      |                 0 | 0.7955 | orig=weiblich : geschieden/getrennt/verheiratet | keine CF-Änderung | a=weiblich : geschieden/getrennt/verheiratet | β=0.7955 | same/diff=1591/409 | y*=1 (p=0.610) |                      1 |
| Wohnsituation                 |                 0 | 0.7855 | orig=Miete | keine CF-Änderung                                      | a=Miete | β=0.7855 | same/diff=1571/429 | y*=1 (p=0.610)                                      |                      1 |
| Telefon                       |                 0 | 0.756  | orig=kein Telefon | keine CF-Änderung                               | a=kein Telefon | β=0.7560 | same/diff=1512/488 | y*=1 (p=0.610)                               |                      1 |
| Ausländischer_Arbeiter        |                 0 | 0.775  | orig=ja | keine CF-Änderung                                         | a=ja | β=0.7750 | same/diff=1550/450 | y*=1 (p=0.610)                                         |                      1 |
| Beruf                         |                 0 | 0.7815 | orig=ungelernt - ansässig | keine CF-Änderung                       | a=ungelernt - ansässig | β=0.7815 | same/diff=1563/437 | y*=1 (p=0.610)                       |                      1 |

---

### Profil 9


**Ökonomische Features**

| Feature                     |   alpha_notwendig |   beta | α-Details (orig→cf)                                                                      | β-Details (fixierter Wert)                                                                                         |   hinreichend (β≥0.70) |
|:----------------------------|------------------:|-------:|:-----------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------|-----------------------:|
| Kreditbetrag                |                 0 | 0.724  | orig=9283 | keine CF-Änderung                                                            | a=9283 | β=0.7240 | same/diff=1448/552 | y*=1 (p=0.545)                                                            |                      1 |
| Dauer_in_Monaten            |                 0 | 0.6225 | orig=42 | keine CF-Änderung                                                              | a=42 | β=0.6225 | same/diff=1245/755 | y*=1 (p=0.545)                                                              |                      0 |
| Ratenhöhe                   |                 0 | 0.8825 | orig=1 | keine CF-Änderung                                                               | a=1 | β=0.8825 | same/diff=1765/235 | y*=1 (p=0.545)                                                               |                      1 |
| Anzahl_bestehender_Kredite  |                 1 | 0.7895 | orig=1 → cf=1.625 (Δ=0.625 | p:0.545→0.492 | y:1→0)                                      | a=1 | β=0.7895 | same/diff=1579/421 | y*=1 (p=0.545)                                                               |                      1 |
| Kreditgeschichte            |                 0 | 0.7445 | orig=alle Kredite bei dieser Bank wurden ordnungsgemäß zurückgezahlt | keine CF-Änderung | a=alle Kredite bei dieser Bank wurden ordnungsgemäß zurückgezahlt | β=0.7445 | same/diff=1489/511 | y*=1 (p=0.545) |                      1 |
| Kreditverwendungszweck      |                 0 | 0.7405 | orig=Auto (gebraucht) | keine CF-Änderung                                                | a=Auto (gebraucht) | β=0.7405 | same/diff=1481/519 | y*=1 (p=0.545)                                                |                      1 |
| Sparkonto_Wertpapiere       |                 1 | 0.817  | orig=... < 100 DM → cf=A63 (Δ=— | p:0.545→0.497 | y:1→0)                                 | a=... < 100 DM | β=0.8170 | same/diff=1634/366 | y*=1 (p=0.545)                                                    |                      1 |
| Vermögen                    |                 0 | 0.78   | orig=unbekannt/kein Eigentum | keine CF-Änderung                                         | a=unbekannt/kein Eigentum | β=0.7800 | same/diff=1560/440 | y*=1 (p=0.545)                                         |                      1 |
| Status_des_Girokontos       |                 0 | 0.82   | orig=0 <= ... < 200 DM | keine CF-Änderung                                               | a=0 <= ... < 200 DM | β=0.8200 | same/diff=1640/360 | y*=1 (p=0.545)                                               |                      1 |
| Beschäftigt_seit            |                 0 | 0.7665 | orig=arbeitslos | keine CF-Änderung                                                      | a=arbeitslos | β=0.7665 | same/diff=1533/467 | y*=1 (p=0.545)                                                      |                      1 |
| Andere_Ratenverpflichtungen |                 0 | 0.7565 | orig=Bank | keine CF-Änderung                                                            | a=Bank | β=0.7565 | same/diff=1513/487 | y*=1 (p=0.545)                                                            |                      1 |
| Weitere_Bürgen_Schuldner    |                 0 | 0.754  | orig=keine | keine CF-Änderung                                                           | a=keine | β=0.7540 | same/diff=1508/492 | y*=1 (p=0.545)                                                           |                      1 |

**Soziodemographische/sonstige Features**

| Feature                       |   alpha_notwendig |   beta | α-Details (orig→cf)                                                                                           | β-Details (fixierter Wert)                                                                                          |   hinreichend (β≥0.70) |
|:------------------------------|------------------:|-------:|:--------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------|-----------------------:|
| Alter                         |                 1 | 0.908  | orig=55 → cf=36.25 (Δ=18.75 | p:0.545→0.498 | y:1→0)                                                          | a=55 | β=0.9080 | same/diff=1816/184 | y*=1 (p=0.545)                                                               |                      1 |
| Wohnsitzdauer                 |                 0 | 0.8    | orig=2 | keine CF-Änderung                                                                                    | a=2 | β=0.8000 | same/diff=1600/400 | y*=1 (p=0.545)                                                                |                      1 |
| Unterhaltspflichtige_Personen |                 0 | 0.793  | orig=1 | keine CF-Änderung                                                                                    | a=1 | β=0.7930 | same/diff=1586/414 | y*=1 (p=0.545)                                                                |                      1 |
| Familienstand_Geschlecht      |                 1 | 0.8005 | orig=männlich : ledig → cf=A92 (Δ=— | p:0.545→0.465 | y:1→0)                                                  | a=männlich : ledig | β=0.8005 | same/diff=1601/399 | y*=1 (p=0.545)                                                 |                      1 |
| Wohnsituation                 |                 0 | 0.7975 | orig=kostenlos | keine CF-Änderung                                                                            | a=kostenlos | β=0.7975 | same/diff=1595/405 | y*=1 (p=0.545)                                                        |                      1 |
| Telefon                       |                 0 | 0.7665 | orig=ja, unter dem Namen des Kunden registriert | keine CF-Änderung                                           | a=ja, unter dem Namen des Kunden registriert | β=0.7665 | same/diff=1533/467 | y*=1 (p=0.545)                       |                      1 |
| Ausländischer_Arbeiter        |                 0 | 0.784  | orig=ja | keine CF-Änderung                                                                                   | a=ja | β=0.7840 | same/diff=1568/432 | y*=1 (p=0.545)                                                               |                      1 |
| Beruf                         |                 1 | 0.8    | orig=Management/selbstständig/hochqualifizierter Angestellter/Beamter → cf=A174 (Δ=— | p:0.545→0.496 | y:1→0) | a=Management/selbstständig/hochqualifizierter Angestellter/Beamter | β=0.8000 | same/diff=1600/400 | y*=1 (p=0.545) |                      1 |

---