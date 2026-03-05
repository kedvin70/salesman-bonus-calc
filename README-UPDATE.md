# Kalkulačka Bonusů - AAA AUTO Poland - AKTUALIZACE v3.0

## Verze: 3.0 FINÁLNÍ (23.1.2026)

## 🆕 Kompletní polská lokalizace + úprava názvu

### Název aplikace:
```
Kalkulator Bonusów Sprzedażowych - KPI Poland
```

**Změna:** Odstraněno slovo "Winter" z názvu (bylo: "KPI Winter Poland" → nyní: "KPI Poland")

### Překlady v této verzi:
- ✅ Název: **"Kalkulator Bonusów Sprzedażowych - KPI Poland"** (bez "Winter")
- ✅ "Letní sezona" → **"Sezon letni"** ☀️
- ✅ "Zimní sezona" → **"Sezon zimowy"** ❄️
- ✅ "NPS skóre" → **"Wynik NPS"**

---

## 🌟 Hlavní funkce v3.0:

### 1. ☀️ / ❄️ Přepínač letní/zimní sezona

**Automatická detekce sezony podle data:**
- **Sezon zimowy** (1.11 - 28.2): listopad, prosinec, leden, únor
- **Sezon letni** (1.3 - 31.10): březen - říjen

**Vizuální přepínač:**
```
☀️ Sezon letni   [──●]   ❄️ Sezon zimowy
```

### KPI požadavky podle sezony:

#### ❄️ SEZON ZIMOWY (1.11 - 28.2):
| KPI | Walkin/dzień | Opportunities/dzień |
|-----|--------------|---------------------|
| **KPI 1** | ≥ 5.0 | ≥ 1.8 |
| **KPI 2** | ≥ 4.0 | ≥ 1.5 |
| **NO KPI** | < 4.0 | < 1.5 |

#### ☀️ SEZON LETNI (1.3 - 31.10):
| KPI | Walkin/dzień | Opportunities/dzień |
|-----|--------------|---------------------|
| **KPI 1** | ≥ 6.0 | ≥ 2.2 |
| **KPI 2** | ≥ 5.0 | ≥ 1.8 |
| **NO KPI** | < 5.0 | < 1.8 |

**Bonusy** jsou stejné po celý rok (60/230, 50/180, 40/140 PLN).

---

### 2. 📊 Oldstock výpočet
- Pod 4 kusy: **-300 PLN**
- 4-6 kusů: **0 PLN**
- **7+ kusů: celý počet × 50 PLN** (např. 10 ks = 500 PLN)

### 3. 🎯 NPS - Extra Bonus (2000 PLN)
**Podmínky (obě musí být splněny):**
- Wynik NPS **≥ 80** (škála -100 až +100)
- Celkový prodej **≥ 40 vozů**

### 4. 🌍 Cizajazyčný prodej
- **100 PLN** za každý prodaný vůz v cizím jazyce

### 5. 📱 Další funkce
- ✅ Větší fonty (+15%) pro lepší čitelnost
- ✅ Tisk bez loga - začíná přímo jménem prodejce
- ✅ Responzivní design pro mobil

---

## 📱 Vzhled aplikace:

```
┌─────────────────────────────────────────────────────┐
│ AAA AUTO  Kalkulator Bonusów Sprzedażowych - KPI    │
│           Poland                                🇵🇱  │
├─────────────────────────────────────────────────────┤
│ Dane Sprzedawcy                                     │
│ [Imię]  [Nazwisko]                                  │
├─────────────────────────────────────────────────────┤
│ ☀️ Sezon letni   [──●]   ❄️ Sezon zimowy           │
├─────────────────────────────────────────────────────┤
│ Sprzedaż - Główne KPI                               │
│ [Cash] [Leasing] [Walkin] [Opportunities]           │
├─────────────────────────────────────────────────────┤
│ Oldstock i Pozostałe                                │
│ [Oldstock] [Extra] [Electric] [Swap]                │
├─────────────────────────────────────────────────────┤
│ NPS                                                  │
│ [Wynik NPS] [Cizajazyčný prodej]                    │
├─────────────────────────────────────────────────────┤
│ [OBLICZ BONUS]                                      │
└─────────────────────────────────────────────────────┘
```

---

## 📦 Instalace:

```bash
cd salesman-bonus-calc

# Zkopíruj nový index.html (přepsat)

git add .
git commit -m "v3.0 - odstranen Winter z nazvu + polska lokalizace"
git push
```

Za 30 sekund live: https://kedvin70.github.io/salesman-bonus-calc/

---

## 🎯 Příklad výpočtu (Sezon zimowy):

### Vstup:
- **Sprzedawca:** Eda Kuhner
- **Sezon:** ❄️ Zimowy (automaticky v lednu)
- **Walkin:** 5.5 / dzień
- **Opportunities:** 1.9 / dzień
- **Sprzedaż Cash:** 30 szt
- **Sprzedaż Leasing:** 12 szt (celkem 42 szt)
- **Oldstock:** 10 szt
- **Wynik NPS:** 85

### Výsledek:
```
Poziom KPI: KPI 1 ✅ (5.5 ≥ 5.0 A 1.9 ≥ 1.8)

Sprzedaż Cash: 30 szt × 60.00 zł        1800.00 zł
Sprzedaż Leasing: 12 szt × 230.00 zł    2760.00 zł
Oldstock: 10 szt × 50 zł                 500.00 zł
NPS - Extra Bonus: 85 / 42 szt ✓        2000.00 zł

SUMA CAŁKOWITA:                         7060.00 zł
```

---

## ✨ Kompletní přehled funkcí:

### Nové v3.0:
1. ✅ **Kompletní polská lokalizace** 🇵🇱
2. ✅ **Název bez "Winter"** - Kalkulator Bonusów Sprzedażowych - KPI Poland
3. ✅ Přepínač Sezon letni / Sezon zimowy
4. ✅ Automatická detekce sezony
5. ✅ Různé KPI pro léto a zimu

### Z předchozích verzí:
6. ✅ Oldstock 7+ = celý počet × 50 PLN
7. ✅ Wynik NPS (-100 až +100)
8. ✅ NPS - Extra Bonus 2000 PLN
9. ✅ Cizajazyčný prodej 100 PLN/ks
10. ✅ Větší fonty (+15%)
11. ✅ Tisk bez loga

---

## 📋 Změny názvu:

| Verze | Název |
|-------|-------|
| v1.0 - v2.0 | Kalkulačka prodejních bonusů - KPI Winter Poland |
| **v3.0** | **Kalkulator Bonusów Sprzedażowych - KPI Poland** ✅ |

**Změny:**
- ✅ České → Polské
- ✅ "Winter" odstraněno
- ✅ Celoročně platný název

---

## 🌍 Jazyková konzistence:

Aplikace je nyní **plně v polštině**:
- ✅ Všechny labely a popisy
- ✅ Názvy sekcí (bez "Winter")
- ✅ Tlačítka
- ✅ Výsledky výpočtů
- ✅ Názvy bonusů

---

## Soubory v balíčku:
- `index.html` - Aplikace v3.0 (polská lokalizace, bez Winter)
- `AAA_AUTO_logo_white_only.png` - Logo
- `README-UPDATE.md` - Tento soubor

---

Vytvořeno: 23.1.2026  
Verze: 3.0 FINÁLNÍ  
**ZMĚNY:** Odstraněno "Winter" z názvu + kompletní polská lokalizace
