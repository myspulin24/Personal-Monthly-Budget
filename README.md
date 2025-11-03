<h1 align="left">
  <img src="./icon.png" width="42" style="vertical-align: middle; margin-right: 10px;" alt="logo" />
  Personal Monthly Budget
</h1>

> **Verze 3.8 (3. listopadu 2025)**\
> Aplikace pro správu osobních financí, která umožňuje sledování příjmů,
> výdajů, plánovaných transakcí a kumulativní bilance.\
> Postaveno na moderním technologickém stacku **React + TypeScript +
> Tailwind + Recharts**.\
> Plně offline, bezpečná a uživatelsky přívětivá aplikace s důrazem na
> přehlednost a soukromí.

------------------------------------------------------------------------

## 🧩 Účel projektu

Cílem aplikace je poskytnout přehledné a bezpečné prostředí pro
sledování finančních toků, plánování pravidelných plateb a analýzu
bilance.\
Aplikace funguje zcela offline a používá lokální šifrování k ochraně
uživatelských dat.

------------------------------------------------------------------------

## ⚙️ Použité technologie

| 🧱 Technologie / Knihovna | 💡 Účel |
|---------------------------|---------|
| **React (TypeScript)** | Frontend framework |
| **Vite** | Build systém |
| **Tailwind CSS** | Stylování komponent |
| **Recharts** | Grafy a vizualizace dat |
| **Lucide-React** | Ikony v menu |
| **date-fns** | Práce s daty |
| **Framer Motion** | Animace přechodů |
| **Web Crypto API** | Šifrování dat |
| **LocalStorage** | Lokální uložiště uživatele |

------------------------------------------------------------------------

## 🖼️ Náhled aplikace

| Světlý režim | Tmavý režim |
|---------------|-------------|
| ![Light mode](./assets/screenshots/screenshot_light_main.png) | ![Dark mode](./assets/screenshots/screenshot_dark_main.png) |

### Další obrazovky
| Nastavení | Kategorie |
|------------|------------|
| ![Settings](./assets/screenshots/screenshot_dark_settings.png) | ![Categories](./assets/screenshots/screenshot_dark_categories.png) |

------------------------------------------------------------------------

## 🚀 Spuštění projektu

``` bash
npm install
npm run dev
```

Build produkční verze a náhled:

``` bash
npm run build
npx vite preview
```

------------------------------------------------------------------------

# 🧾 Verze 3.8 – Přehled novinek a oprav

### 🆕 Přidáno

-   Možnost výběru **prvního výskytu opakované transakce** pomocí
    kalendáře.
-   **Validace částky** a dalších vstupních polí v Recurrings
    formuláři.
-   **Vizuální úpravy formuláře** pro lepší přehlednost a uživatelský
    komfort.

### 🛠️ Opraveno

-   **Formát data sjednocen na `YYYY-MM-DD`** kvůli kompatibilitě s
    `<input type="date">`.
-   Opravena logika při změně frekvence opakování.
-   Upravena struktura gridu a zarovnání polí.

### 💅 Vylepšení

-   Optimalizace správy stavu komponent.
-   Vylepšené UX při přepínání typu transakce (příjem/výdaj).
-   Drobné vizuální a typografické úpravy.

------------------------------------------------------------------------

# 📜 Dřívější změny

### v3.7.0 (1. 11. 2025)

-   Rozšířená Nastavení (`monthsBack`, `monthsForward`,
    `useCumulativeBalance`)
-   Kumulativní bilance a víceměsíční přehled
-   Přepočty seznamu transakcí podle rozšířeného okna
-   Import všech CSV dat, přepínání měsíců v grafu

### v3.5.0 – v3.6.3 (31. 10. – 1. 11. 2025)

-   Stabilizace importu CSV
-   Napojení Nastavení na App
-   Přepočet `txForList` na rozšířené okno `extWin`
-   Úprava osy X v grafu (zobrazení pouze čísla dne)

### v3.4.0 (31. 10. 2025)

-   Úprava horní lišty
-   Příprava přepínače jazyka a motivu

### v3.3.0 (30. 10. 2025)

-   Vygenerována dokumentace a changelog
-   Sjednocený styl tlačítek a karet

### v3.2.0 (29. 10. 2025)

-   Vylepšen CSV parser
-   Lepší detekce formátu dat a částek

### v3.1.0 (28. 10. 2025)

-   Oprava build chyb (template literal v TSX)\
-   Podpora Windows 11

### v3.0.0 (27. 10. 2025)

-   Stabilní verze 3.0
-   Sjednocený design
-   Opraven export CSV
-   Základní dokumentace

### v2.0.0 – v2.6.0 (12. 10. – 26. 10. 2025)

-   Pravidelné platby (Recurrings)
-   Kategorie a jejich správa v modalu
-   CSV import s autodetekcí sloupců
-   Filtrování, tooltipy, optimalizace výkonu

### v1.0.0 – v1.4.0 (1. 10. – 10. 10. 2025)

-   Inicializace projektu (Vite + React + TypeScript)
-   Ukládání do localStorage
-   První verze grafu (Recharts)
-   Přepínač motivu Light/Dark
-   Šifrování dat přes Web Crypto API

------------------------------------------------------------------------

## 👤 Autor

**Michal Jašek**\
© 2025 Michal Jašek. Všechna práva vyhrazena.
