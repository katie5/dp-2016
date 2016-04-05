
###První problém###
V původních procesech nebyl jasně nadefinován vlastník procesu, což v mnohém stěžovalo situaci v průběhu přepisu. Nové verze bylo potřebovat prokonzultovat s tím daným direktorem, který je za ni odpovědný.
Zde je nutno podotknout, že jednotlivé definice a odpovědnosti jednotlivých rolí byly nalezeny až později, paradoxně i ti, kteří je vytvořili, už zapomněli, že něco takového existuje.

**Řešení**

K procesům je potřeba přidat jasnou definici process ownera/business ownera procesu, který je odpovědný za jeho definici a posléze i za schvalování změn v tomto procesu. 
Dále je potřeba udržovat popisy pracovních rolí aktuální.

Zde je potřeba nadefinovat pojem proces owner a busines owner:

"**Vlastník procesu** - představuje konkrétní osobu, která je odpovědná za realizaci procesu, jeho aktualizaci a zlepšování" U obecných procesů, které jsou společné pro více organizačních jednotek, garantuje vlastník procesu obecný popis platný pro všechny uživatele procesu.Proces owner má možnost provádět požadované změny v procesu aby dosáhl cílu procesu.

["**Busines owner** - rozhoduje o procesech v celé obchodní sféře, typické rozhodnutí pro tento orgán zahrnuje:
- odpovědnost za konečný návrh procesů a klíčových ukazatelů výkonosti
- odpovědnost za úspěšnou relaizaci společných postupů v rámci celého podniku],

!!**DOPAST ROZDÍL MEZI OWNERAMA** ->DOHLEDAT V KNIZE!!!

!!Připsat náležitosti procesu.!!


###Problém dva###
Dalším možným problémem a zároveň omezením je, že všechny procesní deskripce se nacházejí v produktu Samepage, který společnost Kerio využívá pro spolupráci.
Nevýhody:
 -  produkt SIO se pořád vyvíjí a mění
 -  vyhledávání v SIO není dokonalé - existují zde spousty vytvořených dokumentů, ve kterých se těžko hledá, pokud není klíčové slovo velmi výstižné

**Řešení**

Důležité je sjednotit  lay-out procesních deskripcí. Vzhledem k tomu že se produkt stále vyvíjí, je potřeba ho zanechat jednoduchý, připravený na případnou migraci do nového prostředí.
U přepisu je také potřeba brát ohled na správné pojmenování procesu a tím se pokusit vylepšit vvyhledávání na SIO. Pokud budou správně použitá klíčová slova, vyhledávání by mělo být jednodušší.

Možným řešením je i najít jiný nástroj ve kterém by se procesní deskripce udržovaly, pokud SIO přestane vyhovovat.

###Problém tři###
V původních procesních popisech nebylo jasně definováno, kdo mám proces vykonávat.

**Řešení**
V procesech je potřeba tyto role definovat. V úvahu připadá definice rolí na základě barev. Tyto definice je potřeba pak globálně udržovat a dodržovat jejich používání. Toto použití je potřeba nadefinovat

###Problém čtyři###
Každý proces byl jiný, jinak napsaný, měl jiné náležitosti, podle toho, kdo ho vytvořil (napsal)

**Řešení**
Je potřeba vytvořit jasná pravidla podle kterých se bude proces tvořit a kde bude nadefinováno, jaké náležitosti proces musí mít.


Výše uvedená řešení byla shrnuta v průběhu přepisu do souhrného dokumentu Global Gudiance, kde byly jednotlivá řešení problému nadefinována. Jsou zde nadefinované barvy pro role, kterých se proces týká, je zde nadefinován lay-out procesu a stejně tak náležitosti, které by měla procesní deskripce obsahovat.

###Problém pět###
Procesy jsou dlouhé, mnohdy nesrozumitelné, proto je většina členů Sales týmu nečte, i přesto, že zadávání informací do systému, či zpracování jednotlivých úkonů v určitém pořadí je pro správnost dat v systému klíčové

**Řešení**
Řešením v tomto případě je revize všech procesů, kontrola jejich správnosti, vytřídění nepotřebných informací do separátní sekce procesu a zanechání pouze čisté procesní deskripce, která bude krátká, vystížná a bude obsahovat pouze kroky nutné k úspěšnému vykonání procesu od začátku do konce.

###Procesní struktura###
Problém šest - špatné třídění procesů.

**Řešení**
Řešením v tomto případě je nepochybně setřídění procesů do smysluplných celků. Dále je potřeba vytřídit procesy, které už se nepoužívají a ty pak přesunout do složky archivu, kterou je potřeba také vytvořit. U setřídění je potřeba také překontrolovat práva, která jsou udělena na jednotlivé stránky, aby bylo zajištěno, že ti pracovníci, kterým jsou procesy určtěny se na ně dostanou. U Archivu pak bude přístup zamezen, aby nedocházelo k případnému zmatení.

Dále je potřeba vzít v uvahu rozdělení společností a to, že společnsot Samepage bude mít svuj vlastní systém SFDC. Proto budou zvlášt vytříděny procesy pro zpracování zákazníků SIO - s těmi to se dále pracovat nebude, protože momentálně není možné rozhodnout, které z nich jsou dále pro Kerio Sales tým relevantní, a které ne.(* Tato problematika byla projednána ze Sales Directorem, který toto měl na starosti, tyto procesy pro společnost kerio momentáně nejsou prioritní)

Třetí sloužkou, která bude vyčleněna, bude složka obsahující procesy, které jsou vykonávány pouze v systému KISS. Tyto procesy jsou prováděny povětšinou rolí Sales Ops, proto je lepší je ze Sales procesů vyčlenit.

V Sales procesech tedy zůstanou procesy relevantní pro členy Sales týmu.

###Problém sedm###
Přehlednost procesu, tím že se často opakují, často se může stát, že pracovník nemůže rychle najít, jak pokračovat. Rozhodující informace se v tu chvíli ztratí v přehršli textu.

**Řešení**
Odstranění duplicit. Případné opakování vytknout do podprocesu a na ten pak v průběhu hlavního procesu odkazovat. Tím se zlepší i udržovatelnost procesu samotného - případné zmněny se provedou pouze na jednom místě, nebude třeba procházet množství procesů a provádět úpravy jednotlivě.
Celkové zjednodušení procesu je již zahrnuto v řešení problému číslo pět. Všechny problémy a řešení jsou mezi sebou svým způsobem propojeny.

###Problém osm###
Tím, že se procesy hodně opakují a nepoužívají se odkazy. Dochází k tomu, že jejich údržba a udržení aktuálnosti je velmi obtížná. Pokud změním krok na jednom místě, měla by se tato změna promítnout i do ostatních procesů. Dále je zde potřeba udržovat značné množství printsceeru.

**Řešení**
Opět na sebe řešení jednotlivých problému navazují, kokrténě řešení problému číslo 7 - vytknutí opakujících se části procesu. 
Printcreene je potřeba omezit a v průběhu přepisu se maximálního množství stávajích, neaktuálních zbavit. Je potřeba 