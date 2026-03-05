# KalkulaÄŤka BonusĹŻ - AAA AUTO Poland - AKTUALIZACE v3.0

## Verze: 3.0 FINĂLNĂŤ (23.1.2026)

## đź†• KompletnĂ­ polskĂˇ lokalizace + Ăşprava nĂˇzvu

### NĂˇzev aplikace:
```
Kalkulator BonusĂłw SprzedaĹĽowych - KPI Poland
```

**ZmÄ›na:** OdstranÄ›no slovo "Winter" z nĂˇzvu (bylo: "KPI Winter Poland" â†’ nynĂ­: "KPI Poland")

### PĹ™eklady v tĂ©to verzi:
- âś… NĂˇzev: **"Kalkulator BonusĂłw SprzedaĹĽowych - KPI Poland"** (bez "Winter")
- âś… "LetnĂ­ sezona" â†’ **"Sezon letni"** â€ď¸Ź
- âś… "ZimnĂ­ sezona" â†’ **"Sezon zimowy"** âť„ď¸Ź
- âś… "NPS skĂłre" â†’ **"Wynik NPS"**

---

## đźŚź HlavnĂ­ funkce v3.0:

### 1. â€ď¸Ź / âť„ď¸Ź PĹ™epĂ­naÄŤ letnĂ­/zimnĂ­ sezona

**AutomatickĂˇ detekce sezony podle data:**
- **Sezon zimowy** (1.11 - 28.2): listopad, prosinec, leden, Ăşnor
- **Sezon letni** (1.3 - 31.10): bĹ™ezen - Ĺ™Ă­jen

**VizuĂˇlnĂ­ pĹ™epĂ­naÄŤ:**
```
â€ď¸Ź Sezon letni   [â”€â”€â—Ź]   âť„ď¸Ź Sezon zimowy
```

### KPI poĹľadavky podle sezony:

#### âť„ď¸Ź SEZON ZIMOWY (1.11 - 28.2):
| KPI | Walkin/dzieĹ„ | Opportunities/dzieĹ„ |
|-----|--------------|---------------------|
| **KPI 1** | â‰Ą 5.0 | â‰Ą 1.8 |
| **KPI 2** | â‰Ą 4.0 | â‰Ą 1.5 |
| **NO KPI** | < 4.0 | < 1.5 |

#### â€ď¸Ź SEZON LETNI (1.3 - 31.10):
| KPI | Walkin/dzieĹ„ | Opportunities/dzieĹ„ |
|-----|--------------|---------------------|
| **KPI 1** | â‰Ą 6.0 | â‰Ą 2.2 |
| **KPI 2** | â‰Ą 5.0 | â‰Ą 1.8 |
| **NO KPI** | < 5.0 | < 1.8 |

**Bonusy** jsou stejnĂ© po celĂ˝ rok (60/230, 50/180, 40/140 PLN).

---

### 2. đź“Š Oldstock vĂ˝poÄŤet
- Pod 4 kusy: **-300 PLN**
- 4-6 kusĹŻ: **0 PLN**
- **7+ kusĹŻ: celĂ˝ poÄŤet Ă— 50 PLN** (napĹ™. 10 ks = 500 PLN)

### 3. đźŽŻ NPS - Extra Bonus (2000 PLN)
**PodmĂ­nky (obÄ› musĂ­ bĂ˝t splnÄ›ny):**
- Wynik NPS **â‰Ą 80** (ĹˇkĂˇla -100 aĹľ +100)
- CelkovĂ˝ prodej **â‰Ą 40 vozĹŻ**

### 4. đźŚŤ CizajazyÄŤnĂ˝ prodej
- **100 PLN** za kaĹľdĂ˝ prodanĂ˝ vĹŻz v cizĂ­m jazyce

### 5. đź“± DalĹˇĂ­ funkce
- âś… VÄ›tĹˇĂ­ fonty (+15%) pro lepĹˇĂ­ ÄŤitelnost
- âś… Tisk bez loga - zaÄŤĂ­nĂˇ pĹ™Ă­mo jmĂ©nem prodejce
- âś… ResponzivnĂ­ design pro mobil

---

## đź“± Vzhled aplikace:

```
â”Śâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚ AAA AUTO  Kalkulator BonusĂłw SprzedaĹĽowych - KPI    â”‚
â”‚           Poland                                đź‡µđź‡±  â”‚
â”śâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
â”‚ Dane Sprzedawcy                                     â”‚
â”‚ [ImiÄ™]  [Nazwisko]                                  â”‚
â”śâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
â”‚ â€ď¸Ź Sezon letni   [â”€â”€â—Ź]   âť„ď¸Ź Sezon zimowy           â”‚
â”śâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
â”‚ SprzedaĹĽ - GĹ‚Ăłwne KPI                               â”‚
â”‚ [Cash] [Leasing] [Walkin] [Opportunities]           â”‚
â”śâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
â”‚ Oldstock i PozostaĹ‚e                                â”‚
â”‚ [Oldstock] [Extra] [Electric] [Swap]                â”‚
â”śâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
â”‚ NPS                                                  â”‚
â”‚ [Wynik NPS] [CizajazyÄŤnĂ˝ prodej]                    â”‚
â”śâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
â”‚ [OBLICZ BONUS]                                      â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
```

---

## đź“¦ Instalace:

```bash
cd salesman-bonus-calc

# ZkopĂ­ruj novĂ˝ index.html (pĹ™epsat)

git add .
git commit -m "v3.0 - odstranen Winter z nazvu + polska lokalizace"
git push
```

Za 30 sekund live: https://kedvin70.github.io/salesman-bonus-calc/

---

## đźŽŻ PĹ™Ă­klad vĂ˝poÄŤtu (Sezon zimowy):

### Vstup:
- **Sprzedawca:** Eda Kuhner
- **Sezon:** âť„ď¸Ź Zimowy (automaticky v lednu)
- **Walkin:** 5.5 / dzieĹ„
- **Opportunities:** 1.9 / dzieĹ„
- **SprzedaĹĽ Cash:** 30 szt
- **SprzedaĹĽ Leasing:** 12 szt (celkem 42 szt)
- **Oldstock:** 10 szt
- **Wynik NPS:** 85

### VĂ˝sledek:
```
Poziom KPI: KPI 1 âś… (5.5 â‰Ą 5.0 A 1.9 â‰Ą 1.8)

SprzedaĹĽ Cash: 30 szt Ă— 60.00 zĹ‚        1800.00 zĹ‚
SprzedaĹĽ Leasing: 12 szt Ă— 230.00 zĹ‚    2760.00 zĹ‚
Oldstock: 10 szt Ă— 50 zĹ‚                 500.00 zĹ‚
NPS - Extra Bonus: 85 / 42 szt âś“        2000.00 zĹ‚

SUMA CAĹKOWITA:                         7060.00 zĹ‚
```

---

## âś¨ KompletnĂ­ pĹ™ehled funkcĂ­:

### NovĂ© v3.0:
1. âś… **KompletnĂ­ polskĂˇ lokalizace** đź‡µđź‡±
2. âś… **NĂˇzev bez "Winter"** - Kalkulator BonusĂłw SprzedaĹĽowych - KPI Poland
3. âś… PĹ™epĂ­naÄŤ Sezon letni / Sezon zimowy
4. âś… AutomatickĂˇ detekce sezony
5. âś… RĹŻznĂ© KPI pro lĂ©to a zimu

### Z pĹ™edchozĂ­ch verzĂ­:
6. âś… Oldstock 7+ = celĂ˝ poÄŤet Ă— 50 PLN
7. âś… Wynik NPS (-100 aĹľ +100)
8. âś… NPS - Extra Bonus 2000 PLN
9. âś… CizajazyÄŤnĂ˝ prodej 100 PLN/ks
10. âś… VÄ›tĹˇĂ­ fonty (+15%)
11. âś… Tisk bez loga

---

## đź“‹ ZmÄ›ny nĂˇzvu:

| Verze | NĂˇzev |
|-------|-------|
| v1.0 - v2.0 | KalkulaÄŤka prodejnĂ­ch bonusĹŻ - KPI Winter Poland |
| **v3.0** | **Kalkulator BonusĂłw SprzedaĹĽowych - KPI Poland** âś… |

**ZmÄ›ny:**
- âś… ÄŚeskĂ© â†’ PolskĂ©
- âś… "Winter" odstranÄ›no
- âś… CeloroÄŤnÄ› platnĂ˝ nĂˇzev

---

## đźŚŤ JazykovĂˇ konzistence:

Aplikace je nynĂ­ **plnÄ› v polĹˇtinÄ›**:
- âś… VĹˇechny labely a popisy
- âś… NĂˇzvy sekcĂ­ (bez "Winter")
- âś… TlaÄŤĂ­tka
- âś… VĂ˝sledky vĂ˝poÄŤtĹŻ
- âś… NĂˇzvy bonusĹŻ

---

## Soubory v balĂ­ÄŤku:
- `index.html` - Aplikace v3.0 (polskĂˇ lokalizace, bez Winter)
- `AAA_AUTO_logo_white_only.png` - Logo
- `README-UPDATE.md` - Tento soubor

---

VytvoĹ™eno: 23.1.2026  
Verze: 3.0 FINĂLNĂŤ  
**ZMÄšNY:** OdstranÄ›no "Winter" z nĂˇzvu + kompletnĂ­ polskĂˇ lokalizace
