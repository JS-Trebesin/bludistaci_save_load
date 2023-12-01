# Bludišťáci save & load

Může se hodit [oficiální dokumentace k csv modulu ](https://docs.python.org/3/library/csv.html), ale není nutně potřeba, ani jedna funkce nevyžaduje nové znalosti, stačí využít kód z hodiny a koncepty, které jsme již probírali. 

## 1. funkce ulozit_data

- po spuštění otevře .csv soubor a uloží data - aneb náš dictionary `bludistaci`
- na každém řádku bude jméno a počet bludišťáků
- výsledek v csv by měl vypadat takto

![image](https://github.com/JS-Trebesin/bludistaci_save_load/assets/84028625/740074fd-c9ac-4b69-a984-febbf2593ea0)


*Pokud by se nezobrazovala správně diakritika v konečném souboru, použijte jména bez diakritiky*

*Pokud někdo používá operační systém a office v angličtině, je možné, že bude muset použít delimeter="," místo ";"*

## 2. funkce nacist_data

- po spuštění otevře .csv soubor a načte data do dictionary `bludistaci`
- v této fázi chcete již pracovat s prázdným dictionary a načítat do něj data z .csv souboru


  ```py
  bludistaci = {}
  ```

*Tato funkce bude trochu složitější, než je zápis dat. Kontrolujte si, co vám píše konzole v případě chyb*

*Pravděpodobně budete muset pracovat s listem (seznamem) a přistupovat správně k indexům*

*Nezapomeňte, že funkci `int()` můžete využít kdykoliv, nejen u inputu.*

*Stejným způsobem, jako funguje `for x in seznam` lze použít také `for x in reader`*

*Nezapomeňte si pro testovací účely printovat do konzole dictionary `bludistaci`, abyste věděli, jestli data správně načítáte*
