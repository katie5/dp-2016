##Nový proces##

V průběhu přepisování  stávajících procesů vznikaly i požadavky na nové procesy a dekripce k nim.
Zpracování těchto deskripcí bylo mnohem jednodušší
Bylo moné si proces vyzkoušet, určit správný postup, otestovat ho se zástupci Sales týmu a pak vypublikovat

Práce na tvorbě nového procesu a jeho deskripce je jednoduššní, než podle zastaralé deskripce zjišťovat, jak by proces měl podle deskripce fungovat a jak funguje doopravdy.

Požadavky na nové procesy povětšinou přichází ze strany Directorů Sales týmu. 

##HW Evaluation##

Tento proces, respektive Try and Buy program, je určen pro partnery a má sloužit ke zvýšení prodejů hardwarového řešení pro firewall - Controll boxů.
Pokud se partner do tohoto programu zapojí, může pak 30 zdarma používat produkt naplno bez jakéholiv omezení. Po uplynutí "evaluační" doby se pak musí rozhodnout, zda si produkt koupí nebo ho vrátí.

 
HW Evaluation je proces, který měl na samém začátku omezení. Omezení se týkalo hlavně hardwaru, jehož množství pro proces bylo omezené. To z toho důvodu, že se nevědělo, jestli bude mít program u partnerů úspěch či ne.
 
Program Try and Buy byl po nějakém času od spuštění vyhodnocen jako úspěšný na základě množství vrácených boxů, které bylo minimální. To vedlo k tomu, že výše zmíněné omezení mohlo být s procesu odstraněno.

###Vývoj procesu###

Nicméně na počátku bylo potřeba pracovat s oběmi možnostmi, jak mohl proces probíhat a to buď:
-  bez omezení, pro malé boxy
-  s omezením, pro velké boxy, v každém Kerio regionu byl určitý počet velkých boxů, které bylo možné do programu zapojit

**Systémová konfigurace**

Proces je opět spuštěn přes vyplnění formuláře na KPP - programu se tedy mohou účastnit je stávající partneři. 
Formulář se odešle a v systému SFDC je vytvořena Oppotunita. Vzhledem k tomu, že není možné odhadnout, zda z Opportunity bude nějaký příjem či ne a také proto, že se jednalo o nový program - bylo potřeba množství a úspěšnost opportunit měřit.

Proto byl vytvořen speciální RT pro tento typ opportunity - HW Evaluation.

I díky tomuto kroku, vyčlenení tohoto typu opporunity, bylo možné hodně věcí v procesu zautomatizovat.

Bylo zde nastaveho hned několik workflows, které se spustí na základě provedené změny na opportunitě. 

U tvoření tohoto procesu zde byla maximálni snaha o to, aby sales museli zasahovat manuálně - snažili sme se předejít případným chybám.

Procesu se účastní Sm/Pam *vysvětlivka pod čaru: občas se procesní role, které mají proces vykonávat překrývají. a Sales Ops. 

!!Z odstupem času je možné říci, že definovat role pomocí barev nebylo nejšastnější řešení.

Hig level procesu byl nastíněn následovně:
Budeme mít formulář ve kterém si partner zvolí typ boxu,v případě distributora pak zadá i svého partnera, pro kterého box pořizuje.
Pravidlo je jasné - každý partner může mít maximálně jeden evaluační box. Aby se nestávalo, že si je pořídí do zásoby a nezaplatí je.

V momentě kdy partner projeví zájem o malý box, odešle formulář, ten vytvoří v SFDC již zmíněnou opporunitu se kterou se dále pracuje. Partnerovi zavolá SM a zjistí, jaká je zde možnost, že box opravud koupí. Na základě této kvalifikace proces pokračuje buď dál, a nebo je partnerův požadavek zamítnut.
Pokud proces pokračuje dál, je potřeba objednat box (spolu s objednávkou se vytváří faktura) a nastavit na oportunitě časovou lhůtu 30 dní. Dále bylo určtěno že 5 dní ped koncem této doby SM partnerovi zavolá a zjistí, zda si box chce ponechat nebo vrtátit.

Pokud vrátit, má na to 5 dní. Pokud do té doby neodevzdá odesílací údaje boxu, nebude mu vystornována faktura.


Co bylo potřeba vyřešit:
1 - omezené počty velkých boxů
2 - časové lhůty
3 - posílání boxů zpět

U velkých bylo potřeba vyřešit ještě jeden problém - pokud jsou v regionu všechny v oběhu, je potřeba partnera nechat čekat a kontaktovat znovu. Bylo potřeba vyřešit, jaký termín může SM partnerovi zdělit - čili, kdy bude na řadě. Tento problém byl vyřešen sestavením reportu, kdy mohli SM identifikovat, kdy je teoreticky možné že bude box volný. Pokud se box prodal, mohli objednat nový box.

Toto omezení nebylo dlouhodobé a bylo v procesu jenom z počátku, aby se zjistilio, zda se budou boxy vrace či ne. Množství vrácenýc boxů však nebyl nijak závratné proto se od tohoto omezení upustilo.





