# Databáze
* Organizovaný soubor strukturovaných dat, v jehož rámci se sledují, shromažďují a systematicky zpracovávají informace určitého typu a obsahu

## Historie

| Rok | Hlavní Událost   | Informace                                                                   | Způsob uložení dat | Zpracování dat     |
| :-: | :-----------     | :-----------------------------------------------------                      | :---------------   | :---------------   |
| před 1890 | Papírové kartotéky | **Předchůdce databází**. Umožňovaly uspořádávání dat podle různých kritérií a zatřiďování nových položek                                            | Papírové kartotéky                    | Operace prováděny člověkem  |
| 1890 | Sčítání lidu v USA | První strojové zpracování dat na elektromechanických strojích.           | Děrné štítky       | Elektromechanické stroje |   
| 1959 | Vznik COBOL | Hierarchický databázový systém. Přechod na magnetické disky                | Magnetické disky   |                    |
| 1970 | Vznik relačních databázových systémů  | Na data pohlížejí jako na tabulky                 |                    |                    |
| 1974 | Vznik SQL | vznik první verze SQL. Plně implementován až od roku 1978 |                     | SQL dotazy |
| 1980 | Databázové systémy pro PC | Oracle vydal první verzi SQL databazi na trhu |                     |  |

## SQL databáze

### Struktura SQL databáze
- Tabulka
- Záznamy (řádky)
- Atributy (sloupce)

### Datové typy

## Struktura NoSQL databáze
- Kolekce (collection)
- Dokument (document)
- Pole (field)

### Sestavy
* Uspořádání dat do tiskového výstupu
* Zdrojem může být tabulka nebo sestava

## Druhy
### Hierarchické databáze
* Data uspořádaná se stromové struktuře
* První z datových modelů

### Síťová databáze
* Nástupce hierarchických databází, které značně vylepšil

### Relační databáze
* Moderní typ databáze, jak je známe dnes. 
* Data uložena v tabulkách (řádky tvoří jednotlivé záznamy)
* Jsou vzájemně propojené pomocí tzv. **klíčů** (Vyjadřují vztahy mezi daty.
  * **Primární klíč** - Musí být unikátní a nesmí být nulový (Slouží jako cizí klíč v ostatních tabulkách)
  * **Cizí klíč** - Odkazuje na další tabulku

### Objektové databáze
* Ukládají v databázích objekty

## Databáze vs Soubory
* databáze fungují mnohem rychleji, bývají optimalizovány pro přístup více uživatelů a obsahují mechanismy, které práci s daty usnadňují
