# Pravidla repozitáře nastroje

Veřejný repozitář = galerie mikronástrojů publikovaná přes GitHub Pages. Kód i obsah vidí kdokoli na internetu.

## Co sem nikdy nepatří
- osobní údaje, data klientů, firemní dokumenty (TTC, HiPP)
- hesla, API klíče, tokeny (cokoli v kódu stránky je veřejné)
- nástroje, které za běhu volají AI nebo cizí weby

## Struktura
- jeden nástroj = jedna složka s názvem bez diakritiky (`kalkulacka-uroku/`) a souborem `index.html`
- jeden samostatný HTML soubor: styly a skript uvnitř, bez serveru, data neopouštějí prohlížeč
- rozhraní česky

## Postup při přidání nebo změně nástroje
1. Zadání podle šablony `2-Areas/AI-system/prompty/sablona-zadani-nastroje.md` (Google Disk).
2. Výpočty ověř nezávisle (vzorec nebo ruční příklad) a otestuj okrajové vstupy.
3. Přidej kartu do `index.html` (galerie) a řádek do tabulky v `README.md`.
4. Před commitem se zeptej Petra. Commit popisuje, co se změnilo a proč.
