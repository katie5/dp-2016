#Partner Portal Singnup#

Na tomto procesu bude demonstrováno, jak probíhal jeho postupný přepis a změna. Tento proces byl vytypovaný, jako jede z klíčových procesů pro sales tým.

##Charakteristika procesu##
Proces má vést k úspěšnému získání nového partnera a jeho správnémů založení v SFDC, potažmo v KISSU a dále jsou partnerovi poskytnuty přístupy do partnerského portálu či online storu.(pokud je požaduje)

Už ze samotné zběžné charakteristiky procesu je patrné, že je proces docela komplikovaný sám o sobě - proběhne zde několik rozhodnutí, která rozhodují o dalším směřování procesu. Další komplikací je, že procesu se účastní hned několik členů týmu.

**Rozhodnutí, které je potřeba v průběhu procesu učinit:**
- Je partner Direct/indirect?
- Má už přístup do KPP? *vysvětlivka pod čárou-KPP je Kerio Partner Portal

Původní proces je rozdělen takto:
1. rozhodnutí - Existing Parnter / New partner
- Existing partner je pak rozdělen do podsekcí:
1. Direct / indirect - No Previous Partner Portal Acces
1. Direct - Approved for Partner Portal
1. Indirect - Approved for Partner Portal
- New Partner je pak dále rozdělen do podsekcí:
1.Direct
1.Indirect

 [obrázek jednotlivých zanoření]
Už z výše uvedeného je patrné, že samotná struktura procesu je poněkud komplikovaná.

Na části procesu která se věnuje Novým partnerům, konkrétně Direct partnerům, je vidět hned několik (ve své podstatě všechny) problémů, které už byly pojmenovány. 

Zde je dle mého názoru výčet těch nejpatrnějších:

1. proces je dlouhý a jsou v něm promíchány kroky pro více rolí.
2. došlo zde k promíchání kroků, které je potřeba provést, vysvětlujících informací a také nejsou vyčleněny spouštěcí události
3. nejsou jasně definované role, které proces mají vykonat
4. dochází zde k duplicitám

Na příkladu je patrné, že se některé části procesu zbytečně opakují. Pak je pro čtenáře / vykonavatele procesu mnohem těžší najít, v čem se proces liší od jiného.

[Obrázek porovnání dvou vedle sebe obrázku Partne P singup..tam kde se opakuji, zvýraznit kde se liší]

Proces bylo potřeba vyčistit, hlavně od těchto duplicit. Tím došlo k redukci počtu stránek, na kterých byl původní proces napsán.

V průběhu pročištění bylo zjištěno, že některé části procesu se liší velmi málo, například jenom v jednom kroku. Proto mohly být některé části procesu textově sloučeny.

Na jednotlivé stránky, kde se procesy nořily do sebe, pak byly přidány jednoduché diagramy, jejichž účelem bylo pomoci při orientaci ve fázích procesu.

Pro lepší pochopení celého procesu, bylo potřeba proces namodelovat, aby bylo možné ho přepsat do srozumitelnější formy.

Proces bylo potřeba upravit potřeba upravit jak po stránce textové, tak i po stránce průběhové.
Pro lepší průběh celého procesu, bylo potřeba ho namodelovat.
[obrázek modelů, původní proces..]

Další změny:
k procesu byl přidán další souběžný proces, který je zaměený na onboarding partnera.
Tím se trochu změnila povaha procesu pro Directy a Indirecty. Proces mohl být rozdělen do sekcí podle toho, která role mám daný kus procesy vykonat.

Procesní deskripce mezi sebou byly různě prolinkované..

Nejdříve bylo potřeba celý proces pochopit, jak probíhá, kdo v něm funguje atd. To zahrnovalo přečíst deskripce, udělat si poznámky a na základě poznámek vytvořit zběžný model, ze ktého bylo víc patrné, jak proces probíhá a kde je možné ho měnit.

Model byl prostý vývojový diagram, k jeho vytvoření stačil papír a tužka.

**uspořádání na stránkách**
.................................................................

Výchozí situace už tedy byla nastíněná.
V prní fázi jsem proces prošla a snažila se ho smysluplně rozdělit a zkrtátit.
Bylo zachováno dělení na Existujicí a Nové partnery. V obou větvích procesu, pak byly vytknuty části, které se opakovaly. V tomto případě se jedná o invitaci partnera do Kerio Partner Portalu (KPP).

Tato verze procesu nějakou dobu fungovala, za nějaký čas opět doško ke změnám (* Tento proces se v průběhu zpracování práce změnil hned několikrát.)

Předposlední výrazná změna byla to, zahrnout do procesu SDR, ta kvalifikovala Lead, čili potencionálnho partnera.
Dalším přídavkem do procesu, byl proces Partner onboardingu, který na tento proces přímo navazuje (na část s Direct Partnerem). Proces probíhá souběžně s dokončováním procesu partnerské registrace.

PO těchto změnnách bylo možné proces rozdělit přímo do sekcí, podle toho kdo, kterou část procesu vykonává.

SRR - Qualification
PAM - Invitation to KPP, sending Annex A
Ops - Partner set up in KISS
SM - Parnter Onboarding

Přitom dělení na Nové a stávající partnery bylo zachováno.

Další důležitým atributem procesu je jeho měřitelnost. Nad tímto procesem je sestaven report, který reportuje množštví kontaktů přidaných do KPP.

Poslední změna souvisí i s tímto. Vedením Sales týmu byl vznesen požadavek na lepší měřitelnost výstupu tohoto procesu - argument je na snadě: marketingové kampaně stojí velmi mnoho peněž, je potřeba začít lépe zjišťovat jejich dopad.
S tím, že celý proces je ukončen v momentě, kdy partner poprvé objedná jakýkoliv kreio produkt.

V souvislosti s požadavkem na měření, bylo potřeba rozdělit objekty, které vyplnění formuláře spustí celý proces.

Pro nové partnery byl vytvořen nový speciálni formulář, ten po vyplnění vytvoří Lead, který je kvalifikovaný. Dále lead prověří SDR a pokračuje v procesu. To je také významná změna, v předchozí verzi SDR pouze okvalifikovala Case, ano změnil s i objekt, který je tvořen v SFDC, a pak ho poslala dám na PAM a ta proces dokončila.

Teď, halvně díky technickým vylepšením v KISu, je SFD schopná provést celý proces kvalifikace a pozvání do KPP sama.
Pokud se jedná o Nového Direct partnerá, SDR vytvoří opportunitu pro SM, který s partnerem dále pracuje (onboarding). Onboarding končí momentem první objednávky partnera.

Fáze procesu se tedy změnili do tohoto stavu:
SDR - kvalificace lídu, zkonverování do opportunity, po dokončení pozvánky do KPP a založení partnera v KISSU je opportunita zavřená se statusem Closed - Won. Pokud se jednalo o Direct partnera, SDR vytvoří Case pro SM - a ten pokračuje v onboardingu.

Nyní je možné lepe reportovat úspěšnot nabírání nových partnerů. Hodnocení je založené na množství opportunit, které jsou úspěšné. Dá se na základě toho vyhodnocovat dopady různých kampaní. Díky Casům, které mají speciálni RT, je pak možné vyhodnocovat, kolik nových partnerů nakonec opravdu objedná zboží.

Proces se tedy z původních 3(až 4) pracovníků dostal na dva(respektive 3). SDR zvládne udělat většinu úkonů sama - poslat Annex A, pozvat partnera do KPP i založit partnera v KISSU.

Poslední dně možnosti jsou možné hlavně díky systémovým vylepšením. 
Pozvávní do KPP bylo dříve možné jen přes aplikaci speciálně pro toto určenou - Admin Lite. Nyní je možné partnera pozvat pomocí tlačítka přímo ze SFDC, které bylo vyvinuto - Manage KPP Acces. Toto tlačítko partnera založí v KPP, přiradí ho do správných skupin na základě údajů na jeho Accountu v SFDC.

Pro založení partnera v kissu a přidělení mu přihlašovacích údajů do online storu, bylo do nedávna potřeba jít do KISSU a manuálně ho založit.

Opět díky vyvinutí tlačítka v SFDC, je nyní možné založit partnera v KISSU na jeden klik. Do KISSu jsou posláný základní údaje o partnerovi z Accountu ze SFDC - tím se chybám, ke ktrým mohlo dojít při manuálním založení.
Toto založení není zcela automatické, do KISSU je stále potřeba se přihlásit a poslat partnerovi přihlašovací údaje do online strou a nastavit speciálni flagy.
Propojení SFDC a KISS je nyní zajištěno Caší. Synchronizace mezi oběma systému probíhá každé dvě hodiny.

Proces tedy nebyl jenom zkráce, ale byl i technicky vylepšen. Protože bylo zjištěno, že příliš mnoho manuální práce v průběhu procesu, způsobuje v procesu chyby..

Postup práce:
1. pochopit proces, jak probíhá, kde se mnění
2. zjistit kdo proces vykonává
3. ověřit aktuálnost procesu
4. vyčistit a zkrátit processní popis
5 vytknout části, které se v procesu opakují

Takový byl postup zde, ale i uvšech přepsaných procesů. 
