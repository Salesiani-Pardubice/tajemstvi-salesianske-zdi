# Tajemství salesiánské zdi

Jednoduchá webová aplikace pro testování znalostí základů salesiánské spirituality.

> [!NOTE]
> Tento README soubor byl vygenerován pomocí ChatGPT4.

Vítejte v repozitáři **Salesian Times**! Tento projekt je interaktivní webová hra, která zapojuje uživatele do objevování klíčových principů salesiánské spirituality prostřednictvím venkovní výzvy.



## Přehled projektu

**Salesian Times** je interaktivní zážitek, kde účastníci řeší hádanku objevením čtyř klíčových salesiánských principů napsaných na venkovní zdi. Po správném zadání slov na přihlašovací stránce jsou uživatelé přesměrováni na tajnou stránku s dalšími instrukcemi.



## Funkce

1. **Úvodní stránka**  
   - Obsahuje novinový feed s články zaměřenými na komunitní a mládežnické aktivity.  
   - Obsahuje přihlašovací formulář, kam účastníci zadávají čtyři objevená salesiánská slova.

2. **Tajná stránka**  
   - Zobrazuje gratulaci a detailní popisy čtyř principů: **škola, hřiště, domov, kostel**.  
   - Poskytuje pokyny pro další kroky ve hře.

3. **Responzivní design**  
   - Projekt používá inline CSS přímo v HTML souborech, což zajišťuje jednoduchost a snadné nasazení.  
   - Nevyžaduje žádný externí CSS soubor.

4. **Hostování na Cloudflare Pages**  
   - Web je hostován na **Cloudflare Pages** a je dostupný na adrese:  
     [https://salesian-times.salesianipardubice.cz](https://salesian-times.salesianipardubice.cz).

5. **Kompaktní struktura souborů**  
   - Obsahuje pouze základní HTML soubory (`index.html` a `secret.html`) s vestavěnými styly a skripty.



## Jak to funguje

1. **Krok 1**: Účastníci hledají čtyři slova napsaná na venkovní zdi u salesiánského střediska.  
2. **Krok 2**: Zadejte objevená slova do přihlašovacího formuláře na úvodní stránce.  
3. **Krok 3**: Správné zadání odemkne tajnou stránku s dalšími instrukcemi.



## Jak začít

### Požadavky
- Webový server pro hostování HTML souborů (pokud hostujete lokálně).  
- Základní znalost HTML pro případnou úpravu.

### Instalace
1. Naklonujte repozitář:
   ```bash
   git clone https://github.com/username/salesian-times.git
   ```
2. Přesuňte se do složky projektu:
   ```bash
   cd salesian-times
   ```
3. Nasazení projektu na libovolnou hostingovou platformu (např. Cloudflare Pages).



## Struktura souborů

- `index.html` - Úvodní stránka s přihlašovacím formulářem.  
- `secret.html` - Tajná stránka s principy a dalšími kroky.



## Použité technologie

- **HTML5**: Pro strukturování webových stránek.  
- **Inline CSS**: Pro responzivní a jednoduché styly přímo v HTML.  
- **JavaScript**: Pro validaci formuláře a navigaci.  
- **Cloudflare Pages**: Pro hostování projektu.



## Pravidla pro přispívání

Rádi přivítáme vaše příspěvky ke zlepšení projektu! Postupujte podle následujících kroků:

1. Vytvořte si fork repozitáře.  
2. Vytvořte novou větev:
   ```bash
   git checkout -b feature-name
   ```
3. Uložte své změny:
   ```bash
   git commit -m "Přidání nové funkce"
   ```
4. Nahrajte změny na svůj fork a vytvořte pull request.

## Licence

Tento projekt je licencován pod MIT licencí. Více informací naleznete v souboru `LICENSE`.
