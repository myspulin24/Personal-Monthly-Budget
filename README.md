# Personal Monthly Budget

Aplikace **Personal Monthly Budget** je moderní offline nástroj pro správu osobních financí postavený na **React + TypeScript**.
Vznikla v rámci projektu *Homework* v období říjen–listopad 2025.

---

## 🧩 Účel projektu
Cílem aplikace je poskytnout přehledné a bezpečné prostředí pro sledování příjmů, výdajů, plánovaných transakcí a kumulativní bilance.
Aplikace funguje zcela offline s důrazem na ochranu dat prostřednictvím lokálního šifrování.

---

## ⚙️ Použité technologie
| Technologie / Knihovna | Účel |
|-------------------------|------|
| **React (TypeScript)** | Frontend framework |
| **Vite** | Build systém |
| **Tailwind CSS** | Stylování komponent |
| **Recharts** | Grafy a vizualizace dat |
| **Lucide-React** | Ikony v menu |
| **date-fns** | Práce s daty |
| **Framer Motion** | Animace přechodů |
| **Web Crypto API** | Šifrování dat |
| **LocalStorage** | Lokální uložiště uživatele |

---

## 📁 Architektura projektu
```
src/
 ├─ components/
 │   ├─ App.tsx
 │   ├─ MenuBar.tsx
 │   ├─ SummaryCards.tsx
 │   ├─ CashflowChart.tsx
 │   ├─ CategoriesModal.tsx
 │   ├─ ImportModal.tsx
 │   ├─ Recurrings.tsx
 │   ├─ UI.tsx
 │   └─ Modal.tsx
 ├─ lib/
 │   ├─ storage.ts
 │   ├─ crypto.ts
 │   ├─ theme.ts
 │   └─ date.ts
 ├─ types.ts
 ├─ index.css
 └─ main.tsx
```

---

## 🚀 Spuštění projektu
```bash
npm install
npm run dev
```
Build produkční verze a náhled:
```bash
npm run build
npx vite preview
```

---

## 📈 Aktuální verze – 3.7 (1. 11. 2025)
### Novinky
- Přidány nové parametry do Nastavení: `monthsBack`, `monthsForward`, `useCumulativeBalance`.
- Přehled příjmů/výdajů rozšířen o víceměsíční výpočet.
- Kumulativní bilance – výpočet všech předchozích období.
- Přepínání měsíců v grafu pomocí tlačítek.
- Upraven formát osy X v grafu (zobrazování pouze čísla dne).
- Import CSV nyní bez filtru, importuje všechna data.
- Lepší kontrast v Dark módu.

---

# CHANGELOG – Personal Monthly Budget
-----------------------------------
Časová osa vývoje: 1. října 2025 – 1. listopadu 2025

v1.0.0 (01.10.2025)
  • Inicializace projektu (Vite + React + TypeScript)
  • Základní komponenty UI – Button, Card, Input, Label, Select

v1.1.0 (03.10.2025)
  • Přidány SummaryCards (Příjmy/Výdaje/Bilance)
  • Implementováno ukládání transakcí do localStorage

v1.2.0 (06.10.2025)
  • Přidáno šifrování přes Web Crypto API
  • Export/Import JSON dat
  • Heslové odemykání databáze

v1.3.0 (08.10.2025)
  • Recharts – první graf Cashflow
  • Přepínač motivu Light/Dark (Tailwind)
  • date-fns – výpočty datových intervalů

v1.4.0 (10.10.2025)
  • Přidány kategorie a jejich správa v modalu
  • Filtrování transakcí podle kategorií

v2.0.0 (12.10.2025)
  • Pravidelné platby (Recurrings)
  • UI panel pro přehled plánovaných plateb

v2.1.0 (15.10.2025)
  • Import CSV s autodetekcí sloupců Datum/Částka/Kategorie
  • Zavedeno měsíční filtrování importu

v2.2.0 (18.10.2025)
  • Refaktor App.tsx
  • Optimalizace useMemo a lepší výkon
  • Tooltipy v grafu

v2.3.0 (20.10.2025)
  • MenuBar (Lucide ikony)
  • Akce: Nastavení, Kategorie, Export, Import, Reset, Dark Mode

v2.4.0 (22.10.2025)
  • Potvrzovací modal pro mazání transakcí
  • Lepší UX při přihlašování

v2.5.0 (24.10.2025)
  • Výkonové optimalizace a zlepšené škálování grafu

v2.6.0 (26.10.2025)
  • Úklid kódu a příprava na verzi 3.x

v3.0.0 (27.10.2025)
  • Stabilní verze 3.0 – sjednocený design, opravy exportu CSV
  • Základní dokumentace projektu

v3.1.0 (28.10.2025)
  • Oprava build chyb (template literal v TSX)
  • Podpora Windows 11

v3.2.0 (29.10.2025)
  • Vylepšen CSV parser (oddělovače, bílé znaky)
  • Lepší detekce dat a částek

v3.3.0 (30.10.2025)
  • Vygenerována dokumentace a patch notes
  • Vylepšení UI (sjednocení stylu tlačítek a karet)

v3.4.0 (31.10.2025)
  • Úprava horní lišty, příprava přepínače jazyka a motivu

v3.5.0 – 3.6.3 (31.10.–01.11.2025)
  • Stabilizace importu CSV a Settings
  • Napojení Settings na App (monthsBack/Forward)
  • Přepočet txForList na rozšířené okno extWin
  • Úprava osy X (jen čísla dnů)

v3.7.0 (01.11.2025)
  • Rozšířená Nastavení (monthsBack, monthsForward, useCumulativeBalance)
  • Přepočty seznamu a souhrnů podle rozšířeného okna
  • Kumulativní bilance, import všech CSV dat
  • Přepínání měsíců v grafu
  • Dokončení README a detailní changelog

---

## 👤 Autor
**Michal Jašek**  
© 2025 Michal Jašek. Všechna práva vyhrazena.
