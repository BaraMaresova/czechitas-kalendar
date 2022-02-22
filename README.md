# Czechitas kalendář

Stránka s kalendářem na webu Czechitas ([https://www.czechitas.cz/kalendar](https://www.czechitas.cz/kalendar)) má několik problémů s reponzivitou. Jmenovitě jde především o tyto dva:

- rozpadající se hlavička při rozměru okna prohlížeče `992px až 1079px (včetně¨)`
- z okna přetékající boxy pro jednotlivé kurzy v seznamu při velikosti okna prohlížeče `992px až 1154px (včetně)`


## Popis kódu

Přiložené HTML je přímo vykopírované ze stránky Czechitas. Web se normálně spravuje v systému Webflow, ale pro účely tohoto úkolu máš k dispozici HTML, které je finálním výstupem z celého procesu. HTML kód můžeš upravit, pokud uznáš za vhodné, ale nemělo by to být nezbytně nutné.

Do HTML souboru jsou nalinkované 4 CSS soubory.
- **css/normalize.css** - Standardní normalizace výchozího vzhledu HTML značek mezi prohlížeči, toto CSS můžeš zcela ignorovat.
- **css/webflow.css** - Základní CSS styl redakčního systému Webflow, který obsahuje výchozí styl pro grid systém, apod. - toto CSS bys normálně neupravoval/a, ale pro účely tohoto úkolu bude asi nutné některé CSS třídy z tohoto souboru přestylovat.
- **css/style.css** - Obsahuje styly, které jsou unikátní pro web Czechitas. Zde je hlavní stylování celého webu, včetně media queries, apod.
- **reseni.css** - Sem napiš veškerý svůj kód.


## Úkol

- Identifikuj dříve zmíněné problémy s hlavičkou a zobrazením kurzů při zmenšeném okně prohlížeče.
- Navrhni vlastní řešení obou problémů. Vymysli, jak by šel v problematických místech web responzivně upravit, aby byl výsledek pro návštěvníka co  nejpoužitelnější a nejpohodlnější na prohlížení. **Svoje navrhované řešení slovy popiš** do komentáře v souboru **reseni.css** (stačí několik vět). Pokud k navrhovanému řešení budeš mít i vizuální nákres, bude to malé plus. Stačí v podobě jednoduchého wireframu tužkou na papír a naskenovat nebo vyfotit mobilem.
- Nakóduj navržené řešení v CSS. Svoje úpravy piš výhradně do souboru **reseni.css**. Pravděpodobně bude nutné přestylovat některé třídy ze souboru **webflow.css** a určitě třídy ze souboru **style.css**. Vyhni se použití `!important`, pokud je to jen trochu možné.
- Dej pozor, abys svými změnami nerozbil/a web v breakpointech, kde nyní funguje ok.

Nebudeš-li moci z nějakého důvodu úkoly úspěšně dokončit, popiš alespoň slovy svůj postup uvažování, co se povedlo a kde jsi se zasekl/a.

Odhadovaná náročnost úkolu *cca 1-3 hodiny*.


## Odevzdání vypracovaného řešení

Udělej si fork tohoto repozitáře. Odkaz na svůj repozitář s vypracovaným řešením nám pošli zpět.
