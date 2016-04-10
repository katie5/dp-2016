#Partner Portal Signup#

Na tomto procesu bude demonstrováno, jak probíhal jeho postupný přepis a změna. Tento proces byl vytypovaný, jako jede z velmi důležitých procesů.

##Charakteristika procesu##
Proces má vést k úspěšnému získání nového partnera a jeho správném založení v SFDC, potažmo v KISSU. Po založení v těchto systémech jsou partnerovi poskytnuty přístupy do partnerského portálu či online storu(pokud je požaduje).

Proces je docela komplikovaný sám o sobě - proběhne zde několik rozhodnutí, která určují další směřování procesu. Další komplikací je, že procesu se účastní hned několik členů týmu.

##Postup úprav##
1. pochopit proces, jak probíhá, kde se mnění
2. zjistit kdo proces vykonává
3. ověřit aktuálnost procesu
4. vyčistit a zkrátit procesní popis
5. vytknout části, které se v procesu opakují
6. ověřit správnost přepsaného procesu
7. publikace procesu Sales týmu.

Tento postup práce byl dodržen s minimálními obměnami u všech přepsaných procesů. Klíčový byl bod jedna. Jako člověkovi s venku, který se musel postupně se systémém SFDC seznámit to nebyo jednoduché. První procesy šly velmi ztuha. Čím déle sem ovšem se systémem pracovala, a začala chápat různá propojení, tím jednodušší přepisy začaly být.

Procesy pak byly přepisovány mimo hlavní stránku a to z toho důvodu, aby v případě použití procesu, nedošlo ke zmatení.

##Textové úpravy##

V rámci pochopení toho,jak proces probíhá, bylo také nutné pochopit jednotlivá zanoření procesu do sebe a rozhodnutí, která je potřeba v průběhu procesu činit.

**Rozhodnutí, které je potřeba v průběhu procesu učinit:**
- Je partner Direct/indirect?
- Má už přístup do KPP? 
*vysvětlivka pod čárou-KPP je Kerio Partner Portal

[obrázek jednotlivých zanoření]

Výchozí proces byl rozdělen takto:
1. rozhodnutí - Existing Parnter / New partner
- Existing partner je pak rozdělen do podsekcí:
1. Direct / indirect - No Previous Partner Portal Acces
1. Direct - Approved for Partner Portal
1. Indirect - Approved for Partner Portal
- New Partner je pak dále rozdělen do podsekcí:
1.Direct
1.Indirect

Z obrázku i popisu je patrné, že i samotná struktura procesu je poněkud komplikovaná.

Na části procesu která se věnuje Novým partnerům, konkrétně Direct partnerům, je vidět hned několik problémů, které už byly pojmenovány. 
[Obrázek porovnání dvou vedle sebe obrázku Partne P singup..tam kde se opakuji, zvýraznit kde se liší]

Zde je dle mého názoru výčet těch nejpatrnějších:

1. proces je dlouhý a jsou v něm promíchány kroky pro více rolí.
2. došlo zde k promíchání kroků, které je potřeba provést, vysvětlujících informací a také nejsou vyčleněny spouštěcí události
3. nejsou jasně definované role, které proces mají vykonat
4. dochází zde k duplicitám

Na příkladu je patrné, že se některé části procesu zbytečně opakují. Pak je pro čtenáře / vykonavatele procesu mnohem těžší najít, v čem se proces liší od jiného.

Proces bylo potřeba vyčistit, hlavně od těchto duplicit. Tím došlo k redukci počtu stránek, na kterých byl původní proces napsán.

V průběhu pročištění bylo zjištěno, že některé části procesu se liší velmi málo, například jenom v jednom kroku. Proto mohly být některé části procesu textově sloučeny.Případně, pokud se část procesu opakovala, byla vytknuta mimo.

Na jednotlivé stránky, kde se procesy nořily do sebe, pak byly přidány jednoduché diagramy, jejichž účelem bylo pomoci při orientaci ve fázích procesu.
[obrázek průběžný]

##Úpravy průběhu##
Proces bylo potřeba upravi jak po stránce textové, tak i po stránce průběhové.
Pro lepší průběh celého procesu, bylo potřeba ho namodelovat.

[obrázek modelů, původní proces..]


Nejdříve bylo potřeba celý proces pochopit, jak probíhá, kdo v něm funguje atd. To zahrnovalo přečíst deskripce, udělat si poznámky a na základě poznámek vytvořit zběžný model, ze ktého bylo víc patrné, jak proces probíhá a kde je možné ho měnit.

Model byl prostý vývojový diagram, k jeho vytvoření stačil papír a tužka. Model prezentovaný v této diplomové práci je pak zpracován v programu MS Visio. Pro spracování modelu bylo potřeba zvolit takový program, který se ve firmě běžně používá.

##Práce##

Výchozí situace už tedy byla nastíněná.
V první fázi jsem proces prošla a snažila se ho smysluplně rozdělit a zkrátit.
Bylo zachováno dělení na Existujicí a Nové partnery. V obou větvích procesu, pak byly vytknuty části, které se opakovaly. V tomto případě se jedná o invitaci partnera do Kerio Partner Portalu (KPP).
[obrázek ze sešitu číslo 2]

Tato verze procesu nějakou dobu fungovala, za nějaký čas opět doško ke změnám (* Tento proces se v průběhu zpracování práce změnil hned několikrát.)

Dalšími změnami, které ovlivnily proces byly tyto:
- zapojení SDR (nyní ISM) - ta má na starosti kvalifikaci Lead, čili potencionálnho partnera.
-návazný proces Partner Onboardingu, který je určený pouze pro Direct Partnery. Proces probíhá souběžně s dokončováním procesu partnerské registrace.

Po těchto změnách bylo možné proces rozdělit přímo do sekcí, podle toho kdo, kterou část procesu vykonává.

- SRR - Qualification
- PAM - Invitation to KPP, sending Annex A
- Ops - Partner set up in KISS
- SM - Parnter Onboarding

Přitom dělení na Nové a stávající partnery bylo zachováno.

Je důležité zminit, že doposud se proces spoštěl vyplněním formuláře, který byl stejný jak pro Nové tak Existující partnery. K jejjich oddělení docházelo až v průběhu kvalifikace. (viz. model)

Zmíniť je to důležité v souvislosti z další změnou. Ta se týká měření výkonosti tohoto procesu.

Možnost měřitelnosti je důležitým atributem každého procesu Účinnost každého procesu je možno ověřit pomoci reportu sestaveného v SFDC. I nad tímto procesem je sestaven report, který reportuje množství kontaktů přidaných do KPP. Ovšem to přestalo stačit. To že je partner úspěšně přidán a zaregistrován, neznamená, že společnosti začal vydělávat peníze.

Poslední významná změna v procesu tedy souvísí s vylepšením měřitelnosti tohoto procesu.   
Vedením Sales týmu byl vznesen požadavek na lepší měřitelnost výstupu, argument je na snadě: marketingové kampaně stojí velmi mnoho peněž, je potřeba začít lépe zjišťovat jejich dopad.
Marketingové kampaně jsou primárně spravovány přes Marketo, ovšem to je synchronizované ze SFDC, pokud se tedy pro nové partnery bude použivat správny objekt v SFDC, bude možné určit, z jaké kampaně partner přišel.

Bylo tedy potřeba změnit objekty, které se v SFDC tvoří.
V původním procesu to byl Case pro Nového i Existujícího partnera.
V inovovaném procesu byl vytvořen separátní formulář pro nové partnery a separátní formulář pro partnery ecistující.

Tím došlo i k odlenění Existujících partnerů od Novým potencionálních partnerů přímo v systému. Po vyplnění formuláře se vytvoří v SFDC pro každého partnera jiný objekt - pro nové se tvoři Lead, pro existující se tvoří Case.

[obrázek hig level průběhu Existing New]

Teď, hlavně díky technickým vylepšením v KISSu a SFDC, je SDR schopná provést celý proces kvalifikace a pozvání do KPP sama.
Pokud se jedná o Nového Direct partnerá, SDR vytvoří opportunitu pro SM, který s partnerem dále pracuje (onboarding). Onboarding končí momentem první objednávky partnera.

Fáze procesu se tedy změnili do tohoto stavu:
SDR - kvalificace lídu, zkonverování do opportunity, po dokončení pozvánky do KPP a založení partnera v KISSU je opportunita zavřená se statusem Closed - Won. Pokud se jednalo o Direct partnera, SDR vytvoří Case pro SM - a ten pokračuje v onboardingu.

[Hig level průběh nového partnera]

Nyní je možné lepe reportovat úspěšnot nabírání nových partnerů. Hodnocení je založené na množství opportunit, které jsou úspěšné. Dá se na základě toho vyhodnocovat dopady různých kampaní. Díky Casům, které mají speciálni RT, je pak možné vyhodnocovat, kolik nových partnerů nakonec opravdu objedná zboží.

Proces se tedy z původních 3(až 4) pracovníků dostal na dva(respektive 3). SDR zvládne udělat většinu úkonů sama - poslat Annex A, pozvat partnera do KPP i založit partnera v KISSU. 

###Systémová vylepšení###
Poslední dně možnosti jsou možné hlavně díky systémovým vylepšením. 
Pozvávní do KPP bylo dříve možné jen přes aplikaci speciálně pro toto určenou - Admin Lite. Nyní je možné partnera pozvat pomocí tlačítka přímo ze SFDC, které bylo vyvinuto - Manage KPP Access. Toto tlačítko partnera založí v KPP, přiradí ho do správných skupin na základě údajů na jeho Accountu v SFDC.

Pro založení partnera v kissu a přidělení mu přihlašovacích údajů do online storu, bylo do nedávna potřeba jít do KISSU a manuálně ho založit.

Opět díky vyvinutí tlačítka v SFDC, je nyní možné založit partnera v KISSU na jeden klik. Do KISSu jsou posláný základní údaje o partnerovi z Accountu ze SFDC - tím se minimalizují chyby, ke ktrým mohlo dojít při manuálním založení.
Toto založení není zcela automatické, do KISSU je stále potřeba se přihlásit a poslat partnerovi přihlašovací údaje do online strou a nastavit speciálni flagy.
Propojení SFDC a KISS je nyní zajištěno Caší. Synchronizace mezi oběma systému probíhá každé dvě hodiny.

Proces tedy nebyl jenom zkrácen, ale byl i technicky vylepšen. Protože bylo zjištěno, že příliš mnoho manuální práce v průběhu procesu, způsobuje v procesu chyby.
