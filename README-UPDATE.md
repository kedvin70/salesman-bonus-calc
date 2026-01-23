# Kalkulačka Bonusů - AAA AUTO Poland - AKTUALIZACE v2.0

## Verze: 2.0 FINÁLNÍ (17.1.2026)

## Nové změny v této verzi:

### 1. ✅ Oldstock výpočet upraven
**ZMĚNA:** Při 7 a více kusech oldstock se nyní platí **CELÝ POČET × 50 PLN**

**Před:**
- 10 kusů = (10 - 6) × 50 = 200 PLN

**Po:**
- 10 kusů = 10 × 50 = **500 PLN** ✅

**Logika:**
- Pod 4 kusy: -300 PLN
- 4-6 kusů: 0 PLN
- 7+ kusů: **celý počet × 50 PLN** (nově!)

### 2. ✅ NPS - Extra Bonus 2000 PLN
Nová sekce: **NPS**
Nové pole: **NPS skóre** (hodnota od -100 do +100)

**⚠️ NPS není procento, ale hodnota:**
- Škála: **-100 až +100**
- Příklady hodnot: -50, 0, 35, 80, 95

**PODMÍNKY PRO BONUS 2000 PLN:**

Bonus se vyplácí JEN když jsou splněny **OBĚ DVĚ podmínky současně:**

1. ✓ NPS musí být **80 A VÍCE** (ne 80%!)
2. ✓ Celkový prodej musí být **40 vozů A VÍCE** (cash + leasing dohromady)

**Pokud jsou splněny OBĚ podmínky = 2000 PLN**  
**Pokud chybí jakákoliv podmínka = 0 PLN**

**Příklady:**
```
NPS 85 + 46 vozů = 2000 PLN ✅
NPS 90 + 50 vozů = 2000 PLN ✅
NPS 85 + 35 vozů = 0 PLN ❌ (málo vozů)
NPS 75 + 50 vozů = 0 PLN ❌ (nízké NPS)
NPS 82 + 42 vozů = 2000 PLN ✅
NPS -20 + 45 vozů = 0 PLN ❌ (záporné NPS)
NPS 50 + 60 vozů = 0 PLN ❌ (NPS pod 80)
```

### 3. ✅ Cizajazyčný prodej (NOVÉ!)
Nové pole: **Cizajazyčný prodej (szt)**

**Bonus: 100 PLN za každý prodaný vůz v cizím jazyce**

**Příklady:**
- 3 cizajazyčné prodeje = 3 × 100 = **300 PLN**
- 5 cizajazyčných prodejů = 5 × 100 = **500 PLN**
- 0 cizajazyčných prodejů = **0 PLN**

### 4. ✅ Větší fonty v input polích
Fonty v zadávacích polích zvětšeny o **15%** (z 15px na 17px) pro lepší čitelnost.

---

## 📊 Co je NPS?

**NPS (Net Promoter Score)** měří lojalitu zákazníků.

**Škála hodnot:**
- **-100 až -1** = Záporné NPS (více kritiků než příznivců)
- **0 až 29** = Nízké NPS
- **30 až 49** = Průměrné NPS
- **50 až 69** = Dobré NPS
- **70 až 79** = Velmi dobré NPS
- **80 až 100** = Excelentní NPS ✅ → **BONUS 2000 PLN** (pokud i 40+ vozů)

**Typické hodnoty:**
- Špatný měsíc: -10 až 40
- Průměrný měsíc: 50 až 70
- Skvělý měsíc: 80 až 95
- Výjimečný měsíc: 95+

---

## Nová sekce ve formuláři:

```
┌─────────────────────────────────────┐
│ NPS                                  │
├─────────────────────────────────────┤
│ NPS skóre: [___]  (-100 až +100)    │
│ Cizajazyčný prodej (szt): [___]     │
└─────────────────────────────────────┘
```

---

## Instalace do projektu:

### 1. Nahraď soubory v projektu
```bash
cd salesman-bonus-calc
# Zkopíruj index.html a AAA_AUTO_logo_white_only.png
```

### 2. Push na GitHub
```bash
git add .
git commit -m "v2.0 final - NPS -100 to +100, cizajazycny prodej"
git push
```

### 3. Zkontroluj web
Za 30 sekund: https://kedvin70.github.io/salesman-bonus-calc/

---

## 📊 Kompletní příklad výpočtu:

### Vstup:
- **Jméno:** Eda Kuhner
- **KPI:** 5.83 walkin / 1.83 opp. = KPI 1
- **Cash:** 33 ks
- **Leasing:** 13 ks (celkem 46 vozů)
- **Oldstock:** 10 ks
- **Oldstock Extra:** 1 ks
- **Electric:** 2 ks
- **Swap:** 11 ks
- **Cizajazyčný prodej:** 3 ks
- **NPS:** 85 ✓ (excelentní!)

### Výsledek:

| Položka | Výpočet | Částka |
|---------|---------|--------|
| Cash | 33 × 60 | 1980 PLN |
| Leasing | 13 × 230 | 2990 PLN |
| **Oldstock** | **10 × 50** | **500 PLN** ✅ |
| Oldstock Extra | 1 × 200 | 200 PLN |
| Electric | 2 × 100 | 200 PLN |
| Swap | 11 × 50 | 250 PLN |
| Extra Sold Cars | 46 ks | 1350 PLN |
| Leasing Extra | 13 ks | 700 PLN |
| **Cizajazyčný** | **3 × 100** | **300 PLN** ✅ |
| **NPS - Extra** | **85 + 46 vozů** | **2000 PLN** ✅ |

**CELKEM:** **10 470 PLN** 💰💰💰

*(Původně: 8 020 PLN → zvýšení o 2 450 PLN!)*

---

## 📱 Co se zobrazí ve výsledcích:

### Když jsou splněny OBĚ podmínky:
```
NPS - Extra Bonus: 85 / 46 szt ✓ (splněno obě podmínky)    2000.00 zł
```

### Když není splněn počet vozů:
```
NPS - Extra Bonus: 85 / 35 szt (nesplněno - potřeba 40+ vozů)    0.00 zł
```

### Když není splněno NPS:
```
NPS - Extra Bonus: 75 / 46 szt (nesplněno - potřeba NPS 80+)    0.00 zł
```

### Když není splněno nic:
```
NPS - Extra Bonus: 50 / 30 szt (nesplněno - potřeba NPS 80+ a 40+ vozů)    0.00 zł
```

### Cizajazyčný prodej:
```
Cizajazyčný prodej: 3 szt × 100 zł    300.00 zł
```

---

## 🎯 Jak získat NPS - Extra Bonus (2000 PLN):

1. ✓ Dosáhnout NPS **80 nebo více** (excelentní úroveň)
2. ✓ Prodat **40 nebo více vozů** celkem
3. ✅ = **2000 PLN extra!**

---

## ✨ Shrnutí vylepšení:

| Změna | Dopad příklad |
|-------|---------------|
| Oldstock 7+ | **+300 PLN** (při 10 ks: 500 místo 200) |
| NPS 80+ A 40+ vozů | **+2000 PLN** (mimořádný bonus) |
| Cizajazyčný prodej | **+100 PLN za kus** (3 ks = 300 PLN) |
| Větší fonty | Lepší čitelnost ✓ |
| **CELKEM** | **+2600 PLN** možné navíc! 💰 |

---

## Soubory v balíčku:
- `index.html` - Finální aplikace (v2.0)
- `AAA_AUTO_logo_white_only.png` - Logo
- `README-UPDATE.md` - Tento soubor

---

Vytvořeno: 17.1.2026  
Verze: 2.0 FINÁLNÍ  
**OPRAVENO:** NPS škála -100 až +100 (ne procenta!)  
**Změny:** Oldstock 7+, NPS - Extra Bonus, Cizajazyčný prodej 100 PLN/ks
