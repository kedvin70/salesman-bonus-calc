# Kalkulačka Bonusů - AAA AUTO Poland

## Soubory v balíčku:
- `index.html` - Hlavní soubor aplikace
- `AAA_AUTO_logo_white_only.png` - Logo AAA AUTO

## Instalace do projektu:

### 1. Nahraď soubory v projektu
```bash
cd salesman-bonus-calc
# Zkopíruj oba soubory do této složky
```

### 2. Push na GitHub
```bash
git add .
git commit -m "oprava loga + mobilni optimalizace + oldstock vypocet"
git push
```

### 3. Zkontroluj web
Za 30 sekund: https://kedvin70.github.io/salesman-bonus-calc/

## Co bylo změněno:

✅ Logo nahrazeno PNG souborem (správná barva a tvar)
✅ Mobilní optimalizace (responsive design)
  - Grid 4 sloupce → 2 sloupce na mobilu
  - Grid 1 sloupec na velmi malých mobilech
  - Landscape mode optimalizace
✅ Oldstock zobrazuje logiku výpočtu
  - Pod 4 kusy: -300 zł
  - 4-6 kusů: 0 zł  
  - Nad 6 kusů: × 50 zł za každý další kus
✅ Oldstock Extra Bonus: 200 PLN (opraveno z 250 PLN)
✅ Tisk optimalizován na PŘESNĚ 1 stránku
  - Formulář (input pole) se při tisku SKRÝVÁ
  - Vlajka se při tisku SKRÝVÁ (kvůli problémy s zobrazením)
  - Zobrazují se pouze VÝSLEDKY výpočtu
  - Logo AAA AUTO centrované nahoře
  - Jméno prodejce a všechny bonusy
  - Kompaktní layout - vše na jedné stránce A4
  - Zjednodušený černobílý design pro tisk

## Struktura projektu:
```
salesman-bonus-calc/
├── index.html
└── AAA_AUTO_logo_white_only.png
```

## Další úpravy:
Pro další změny upravte index.html, uložte a pushněte na GitHub.

---
Vytvořeno: 17.1.2026
