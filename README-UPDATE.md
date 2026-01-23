# Kalkulačka Bonusů - AAA AUTO Poland - AKTUALIZACE v2.0

## Verze: 2.0 FINÁLNÍ (23.1.2026)

## Všechny změny v této verzi:

### 1. ✅ Oldstock výpočet upraven
**ZMĚNA:** Při 7 a více kusech oldstock se nyní platí **CELÝ POČET × 50 PLN**

**Logika:**
- Pod 4 kusy: -300 PLN
- 4-6 kusů: 0 PLN
- 7+ kusů: **celý počet × 50 PLN** (nově!)

Příklad: 10 kusů = 10 × 50 = **500 PLN** (místo původních 200 PLN)

### 2. ✅ NPS - Extra Bonus 2000 PLN
Nová sekce: **NPS**
Nové pole: **NPS skóre** (hodnota od -100 do +100)

**⚠️ PODMÍNKY PRO BONUS 2000 PLN:**

Bonus se vyplácí JEN když jsou splněny **OBĚ DVĚ podmínky současně:**

1. ✓ NPS musí být **80 A VÍCE**
2. ✓ Celkový prodej musí být **40 vozů A VÍCE** (cash + leasing)

**Příklady:**
- NPS 85 + 46 vozů = **2000 PLN** ✅
- NPS 85 + 35 vozů = **0 PLN** ❌ (málo vozů)
- NPS 75 + 50 vozů = **0 PLN** ❌ (nízké NPS)

### 3. ✅ Cizajazyčný prodej
Nové pole: **Cizajazyčný prodej (szt)**

**Bonus: 100 PLN za každý prodaný vůz v cizím jazyce**

Příklad: 3 cizajazyčné prodeje = 3 × 100 = **300 PLN**

### 4. ✅ Větší fonty v input polích
Fonty zvětšeny o **15%** pro lepší čitelnost.

### 5. ✅ Tisk zjednodušen (NOVĚ!)
**Při tisku se SKRÝVÁ:**
- ❌ Logo AAA AUTO
- ❌ Název kalkulačky
- ❌ Vstupní formulář

**Tisk začíná přímo jménem prodejce:**
```
Sprzedawca: Eda Kuhner
────────────────────────
Wyniki Obliczeń
...
```

---

## 📄 Struktura tisku:

```
┌─────────────────────────────────┐
│ Sprzedawca: Eda Kuhner         │ ← ZAČÁTEK TISKU
├─────────────────────────────────┤
│ Wyniki Obliczeń                 │
│                                 │
│ Poziom KPI: KPI 1               │
│ Sprzedaż Cash: ...  1980.00 zł  │
│ Sprzedaż Leasing: ... 2990 zł   │
│ Oldstock: 15 szt      750 zł    │
│ ...                             │
├─────────────────────────────────┤
│ SUMA CAŁKOWITA:    10 620.00 zł │
└─────────────────────────────────┘
```

**Žádné logo, žádný název - čistý, profesionální výpis!**

---

## 📊 Co je NPS?

**NPS (Net Promoter Score)** - míra loajality zákazníků

**Škála hodnot: -100 až +100**

| Hodnota | Význam |
|---------|--------|
| -100 až -1 | Záporné NPS |
| 0 až 49 | Průměrné NPS |
| 50 až 69 | Dobré NPS |
| 70 až 79 | Velmi dobré NPS |
| **80 až 100** | **Excelentní** ✅ → BONUS 2000 PLN! |

---

## Instalace do projektu:

```bash
cd salesman-bonus-calc

# Zkopíruj nový index.html (přepsat)

git add .
git commit -m "v2.0 - tisk bez loga, NPS -100 to +100"
git push
```

Za 30 sekund live: https://kedvin70.github.io/salesman-bonus-calc/

---

## 📊 Kompletní příklad:

### Vstup:
- Cash: 33 ks
- Leasing: 13 ks (celkem 46 vozů)
- Oldstock: 15 ks
- Cizajazyčný: 3 ks
- NPS: 80

### Výsledek:

| Položka | Částka |
|---------|--------|
| Cash | 1980 PLN |
| Leasing | 2990 PLN |
| Oldstock (15 × 50) | **750 PLN** |
| Oldstock Extra | 200 PLN |
| Electric | 100 PLN |
| Swap | 250 PLN |
| Extra Sold Cars | 1350 PLN |
| Leasing Extra | 700 PLN |
| Cizajazyčný (3 × 100) | **300 PLN** |
| NPS - Extra (80 + 46) | **2000 PLN** |

**CELKEM: 10 620 PLN** 💰

---

## ✨ Shrnutí:

| Změna | Benefit |
|-------|---------|
| Oldstock 7+ | +300-500 PLN |
| NPS 80+ A 40+ vozů | +2000 PLN |
| Cizajazyčný prodej | +100 PLN/ks |
| **Tisk bez loga** | **Čistý výpis** ✓ |
| Větší fonty | Lepší čitelnost ✓ |

---

## Soubory v balíčku:
- `index.html` - Finální aplikace (v2.0)
- `AAA_AUTO_logo_white_only.png` - Logo (jen pro web)
- `README-UPDATE.md` - Tento soubor

---

Vytvořeno: 23.1.2026  
Verze: 2.0 FINÁLNÍ  
**NOVÉ:** Tisk bez loga a názvu - začíná přímo jménem prodejce
