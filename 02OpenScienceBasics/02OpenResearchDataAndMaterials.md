## <img src="/Images/Icons/open_data.png" width="200" height="200" />
## 2. Otvorené výskumné dáta a materiály

### Čo je to?

Otvorené výskumné dáta sú voľne prístupné dáta, ktoré je možné opätovne použiť, remixovať a opätovne šíriť na účely akademického výskumu a výučby ako aj mimo nich. V ideálnom prípade nie je opätovné použitie alebo šírenie otvorených dát nijako obmedzené a dáta majú vhodné licencie. Vo výnimočných prípadoch, napríklad na ochranu identity ľudských subjektov, sú stanovené špeciálne alebo ohraničené obmedzenia prístupu k dátam. Otvorené zdieľanie dát umožňuje dáta preskúmať, čím sa vytvára základ overenia a reprodukovateľnosti výskumu a otvára sa cesta širšej spolupráci. Na otvorené dáta sa môže vzťahovať nanajvýš požiadavka uviesť autora a podmienka rovnakého šírenia (attribute and sharealike) \(pozri [Open Data Handbook](http://opendatahandbook.org/guide/en/what-is-open-data)\).


## <img src="/Images/Icons/data2.png" width="150" height="150" />
### Odôvodnenie

Výskumné dáta sú často najcennejším výstupom mnohých výskumných projektov. Slúžia ako primárne zdroje, ktoré umožňujú podporiť vedecký výskum a odvodiť teoretické alebo aplikované zistenia?poznatky?...derivation of theoretical or applied findings. Aby sa zistenia/štúdie dali replikovať alebo aspoň reprodukovať či opätovne použiť \(pozri [Reprodukovateľný výskum a analýza dát](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md)\) akýmkoľvek iným spôsobom, ako najlepšia prax sa odporúča, aby boli výskumné dáta také otvorené a [FAIR](https://www.force11.org/fairprinciples) ako je možné, pričom sa berú do úvahy etické, komerčné obmedzenia a obmedzenia súvisiace s ochranou súkromia, citlivých a proprietárnych dát.


## <img src="/Images/Icons/finish.png" width="150" height="150" />

### Ciele vzdelávania

1. Pochopiť základné charakteristiky a princípy otvorených a FAIR výskumných dát, vrátane primeraného spracovania a dokumentácie, ktoré umožnia ďalším ľuďom porozumieť, reprodukovať a opätovne použiť dáta iným spôsobom.

2. Oboznámiť sa s druhmi dát, ktoré sa môžu považovať za citlivé, a s obmedzeniami, ktoré bránia takéto dáta otvorene zdieľať.

3. Vedieť konvertovať "zatvorený" súbor dát na "otvorený" implementáciou potrebných opatrení do plánu manažmentu dát, primeranou správou dát a metadátami.

4. Vedieť využiť plán manažmentu dát a zabezpečiť prístup k dátam a ich vyhľadateľnosť, dokonca aj v prípade, ak obsahujú citlivé údaje.

5. Pochopiť plusy a mínusy otvoreného zdieľania rôznych typov dát \(napr., súkromie, citlivosť, anonymizácia dát(de-identifikácia), sprostredkovaný prístup\).

6. Pochopiť dôležitosť primeraných metadát na udržateľné archivovanie výskumných dát. 

7. Pochopiť základné pracovné postupy a nástroje na zdieľanie výskumných dát.  

### Kľúčové prvky
## <img src="/Images/Icons/brain.png" width="150" height="150" /><img src="/Images/Icons/gears.png" width="150" height="150" />
#### Poznatky a zručnosti
##### Princípy FAIR

V roku 2014 boli navrhnuté základné princípy na optimalizáciu opätovného použitia výskumných dát pod názvom [FAIR Data Principles](https://www.force11.org/group/fairgroup/fairprinciples). Predstavujú súbor princípov a najlepších postupov vypracovaných komunitou s cieľom zabezpečiť, aby boli dáta alebo akékoľvek digitálne objekty **F**indable (vyhľadateľné), **A**ccessible (prístupné), **I**nteroperable (interoperabilné a **R**e-usable (opätovne použiteľné):    

**Findable (vyhľadateľné):** Prvá vec, ktorú treba zabezpečiť, aby sa dali dáta opätovne použiť, je ich vyhľadateľnosť. Ľudia aj počítače by mali dokázať nájsť dáta ľahko a jednoducho. Automatické a spoľahlivé vyhľadanie súborov dát a služieb závisí od strojovo čitateľných trvalých identifikátorov \(PID\) a metadát.

**Accessible(prístupné):** \(Meta\)dáta by sa mali dať vyhľadať podľa identifikátora pomocou štandardizovaného a otvoreného komunikačného protokolu, s možnosťou autentifikácie autorizácie. Metadáta by mali byť dostupné aj v prípade, ak samotné dáta už nie sú viac dostupné.

**Interoperable(interoperabilné):** Dáta by sa mali dať kombinovať a používať s inými dátami alebo nástrojmi. Formát dát by preto mal byť otvorený a interpretovateľný rôznymi nástrojmi, vrátane iných záznamov dát. Interoperabilita sa vzťahuje na dáta, ako aj metadáta. \(Meta\)dáta by mali používať slovníky, ktoré sa riadia princípmi FAIR.     

**Re-usable(opätovne použiteľné):** V konečnom dôsledku je cieľom princípov FAIR optimalizácia opätovného použitia dát. Na dosiahnutie tohto cieľa musia byť metadáta a dáta opísané tak dobre, aby sa dali replikovať a/alebo kombinovať v rôznych kontextoch. Opätovné použitie \(meta\)dát tiež musí byť stanovené v jasnej a prístupne licencii/licenciách.

Na rozdiel od partnerských iniciatív zameraných na vedca - človeka kladú princípy FAIR osobitný dôraz na zlepšenie schopnosti strojov automaticky nájsť a použiť dáta alebo akékoľvek digitálne objekty, ako aj na podporu ich opätovného použitia jednotlivcami. Princípy FAIR sú usmerňujúce zásady, nie normy. Pojem FAIR opisuje vlastnosti alebo správanie, ktoré je potrebné na to, aby sa dáta dali čo najviac opätovne použiť \(napr., opis, citovanie\). Tieto vlastnosti je možné dosiahnuť pomocou rôznych štandardov.

![](/Images/02%20Open%20Science%20Basics/02_open_research_data_material.png)

##### Publikovanie dát

Väčšina výskumníkov je už viac alebo menej informovaná o uverejňovaní článkov a kníh v režime otvoreného prístupu \(pozri kapitola 5\). V poslednej dobe, aj z dôvodov uvedených vyššie, si získava čoraz väčšiu pozornosť publikovanie dát. Stále viac financovateľov očakáva, že dáta vyprodukované v rámci výskumných projektov, ktoré financujú, budú vyhľadateľné, prístupné a také otvorené, ako je možné.    

Dáta sa dajú sprístupniť niekoľkými spôsobmi, vrátane \([Wikipedia](https://en.wikipedia.org/wiki/Data_publishing)\):

* Zverejniť dáta ako doplňujúci materiál súvisiaci s výskumným článkom ([research article](https://en.wikipedia.org/wiki/Research_article)), súbory dát sú zvyčajne uložené u vydavateľa článku.

* Uložiť dáta na verejne dostupne webovej stránke, odkiaľ  sa súbory dajú stiahnuť. 

* Uložiť dáta v repozitári, ktorý bol založený na podporu zverejňovania dát, napr., [Dataverse](https://en.wikipedia.org/wiki/Dataverse), [Dryad](https://en.wikipedia.org/wiki/Dryad_(repository)), [figshare](https://en.wikipedia.org/wiki/Figshare), [Zenodo](https://en.wikipedia.org/wiki/Zenodo).

* Na uloženie svojich dát majú výskumníci tiež k dispozícii veľké množstvo všeobecných, odborových a predmetových (tematických) repozitárov.

* Publikovať dátový článok (data paper) o súbore dát, môže byť zverejnený ako preprint v časopise alebo dátovom časopise (data journal) zameranom na podporu dátových článkov. Dáta môže mať uložené časopis alebo môžu byť uložené osobitne v dátovom repozitári. Medzi príklady dátových časopisov patrí [Scientific Data](https://www.nature.com/sdata/) \(od SpringerNature\) a [Data Science Journal](http://www.codata.org/publications/data-science-journal) \(od CODATA\). Komplexnú recenziu dátových časopisov nájdete v článku [Candela et al](https://doi.org/10.1002%2Fasi.23358).

Príručka konzorcia CESSDA ERIC, Sprievodca manažmentom dát [Expert tour guide on Data Management](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/6.-Archive-Publish/Data-publishing-routes), poskytuje prehľad plusov a mínusov rôznych ciest publikovania dát. Financovateľ alebo iná tretia strana môže od vás niekedy vyžadovať, aby ste použili konkrétny repozitár. Ak je voľba na vás, mohli by ste zvážiť výber podľa odporúčaní organizácie OpenAIRE [recommendations by OpenAIRE](https://www.openaire.eu/opendatapilot-repository-guide):

1. Na uchovanie dát v súlade s uznávanými štandardami vo svojej disciplíne použite externý dátový archív alebo repozitár, ktorý už máte vo svojom odbore výskumu k dispozícii.

2. Ak je dostupný, použite inštitucionálny repozitár výskumných dát alebo existujúcu infraštruktúru manažmentu dát, ktorú má vaša výskumná skupina k dispozícii.

3. Použite bezplatný dátový repozitár, ako napríklad [Dataverse](https://dataverse.org/), [Dryad](https://datadryad.org/pages/faq#depositing-cost), [figshare](https://figshare.com/) alebo [Zenodo](https://zenodo.org/).

4. Vyhľadajte repozitár v Registri dátových repozitárov [re3data](https://www.re3data.org/). V registri re3data nie je samostatná možnosť filtrovať výsledky vyhľadávania podľa princípov FAIR, ale nájsť repozitáre kompatibilné s princípmi FAIR vám pomôžu aj tieto možnosti filtrovania: kategórie prístupu, licencie na používanie dát, dôveryhodné dátové repozitáre \(s certifikátom alebo explicitne dodržiavajúce štandardy archivovania\) a to, či repozitár prideľuje dátam trvalý identifikátor \(PID\). Ďalší aspekt, ktorý treba zobrať do úvahy, je to, či repozitár podporuje verziovanie.

## <img src="/Images/Icons/archive.png" width="150" height="150" />
To, kde uložíte a zverejníte svoje dáta, by ste mali zvážiť už pri príprave plánu manažmentu výskumných dát (DMP, z angl. data management plan). Konzorcium CESSDA odporúča zvážiť napríklad tieto praktické otázky: Ktoré dáta a súvisiace metadáta, dokumentácia a kód sa uložia? Ako dlho treba dáta uchovávať? Ako dlho by mali dáta ostať opätovne použiteľné? Ako sa dáta sprístupnia? Akú kategóriu prístupu vyberiete? Viac otázok nájdete v príručke CESSDA, Sprievodca manažmentom dát, v 6. časti Vytvorte si svoj DMP,   [Adapt your DMP: part 6](https://www.cessda.eu/Research-Infrastructure/Training/Expert-Tour-Guide-on-Data-Management/6.-Archive-Publish/Adapt-your-DMP-part-6). Na druhej strane si nezabudnite overiť, či vybraný repozitár spĺňa požiadavky vášho výskumu a financovateľa výskumu. Niektoré repozitáre už získali osvedčenie ako napríklad CoreTrustSeal, ktoré potvrdzuje, že repozitáre sú dôveryhodné a spĺňajú základné požiadavky dôveryhodného dátového repozitára (Core Trustworthy Data Repositories Requirements). Treba sa zmieniť aj o tom, že niektoré odborové repozitáre môžu akceptovať iba dáta vysokej kvality s potenciálom na opätovné použitie a ktoré sa môžu verejne zdieľať.

Keďže existuje niekoľko ciest publikovania dát, mali by ste vedieť, že na to, aby sa dátový súbor "rátal" ako publikácia, mal by prejsť podobným publikačným procesom ako článok \([Brase et al., 2009](https://doi.org/10.3233/ISU-2009-0595)\) a mal by:

* mať primeranú dokumentáciu a metadáta;

* prejsť preskúmaním kvality, napr., obsah výskumu, metodológia, relevantnosť, právna konzistentnosť a dokumentácia materiálov;

* vyhľadateľný v katalógoch \(alebo databázach\);

* citovateľný v článkoch.

## <img src="/Images/Icons/metadata.png" width="150" height="150" />
##### Citovanie dát

Služby citovania dát pomáhajú vedecko-výskumným komunitám spoľahlivo vyhľadať, identifikovať a citovať výskumné dáta \(a často iné výskumné objekty\). Toto zvyčajne zahŕňa tvorbu a pridelenie identifikátorov digitálnych objektov \(DOI\) a sprievodných metadát prostredníctvom služieb ako [DataCite](https://www.datacite.org). DOI a metadáta je možné integrovať do pracovných postupov a štandardov. Ide o vznikajúcu oblasť, ktorá zahŕňa aspekty, ako je presvedčenie vydavateľom o dôležitosti správneho citovania dát v článkoch alebo umožnenie prelinkovanie samotných článkov na podkladové dáta. Citovateľné dáta sa takto stanú oprávneným príspevkom k procesu vedeckej komunikácie a pomôžu pripraviť cestu novým metrikám a modelom vydávania, ktoré budú uznávať a odmeňovať zdieľanie dát.

Pracovná skupina (Data Citation Synthesis Group) hnutia FORCE11 predložila Spoločnú deklaráciu princípov citovania dát, [Joint Declaration of Data Citation Principles](https://doi.org/10.25490/a97f-egyk), ako prvotný krok smerom k dobrej praxi citovania dát. Deklarácia sa zameriava na výskumníkov a aj poskytovateľov dátových služieb. Podľa týchto princípov poskytujú repozitáre výskumníkom odkaz/link (reference), ktorý môžu použiť, keď sa zmienia o danom súbore dát.

## <img src="/Images/Icons/database.png" width="150" height="150" />
##### Spracovanie dát (Data packaging)

Balíky dát (Data packages) sú súbory na opis a zdieľanie sprievodných dátových súborov, zvyčajne obsahujú súbor s metadátami opisujúci vlastnosti a kontext súboru dát. Zahŕňa to aspekty, ako sú informácie o vytvorení, pôvode, veľkosti, formátoch, definície polí, ako aj akékoľvek relevantné kontextové súbory ako skripty na vytvorenie dát či textovú dokumentáciu. Zdroj [Data Packaging Guide](https://github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md):

* Dáta sú navždy: súbory dát prežijú svoj pôvodný účel. Obmedzenia dát môžu byť zjavné v rámci ich pôvodného kontextu, napríklad knižničný katalóg, ale nemusia byť očividné potom, ako sa dáta oddelia od účelu na, ktorý boli vytvorené.

* Dáta nemôžu stáť samostatne: aby mohli používatelia zodpovedne interpretovať dáta, potrebujú informácie o ich kontexte a pôvode - ako a prečo vznikli, aké objekty a pojmy zo skutočného sveta predstavujú, aké sú obmedzenia hodnôt.

* Štruktúrovanie metadát súborov dát je štandardným, strojovo čitateľným spôsobom, ktorý podporuje propagáciu, zdieľateľnosť a opätovné použitie dát.

## <img src="/Images/Icons/privacy.png" width="150" height="150" />
##### Zdieľanie citlivých a proprietárnych dát

Aj veľmi citlivé a proprietárne  dáta sa môžu zdieľať, opätovne použiť a zároveň byť FAIR, ak sa dodrží primeraný manažment dát. Metadáta sa môžu zdieľať takmer vždy. Usmernenia a najlepšie prax na zdieľanie citlivých dát sú vždy špecifické pre daný región, a to kvôli odlišným predpisom \(pozri napríklad Sprievodný materiál k Príručke manažmentu a zdieľania výskumných dát dátovej služby UK Data Service, [Companion material for Managing and Sharing Research Data handbook](https://www.ukdataservice.ac.uk/manage-data/handbook)\). Medzinárodná asociácia informačných služieb a technológií v spoločenských vedách, [International Association for Social Science Information Services and Technology](http://www.iassistdata.org/resources/data-management/best-practices), udržiava zoznam medzinárodných usmernení pre manažment dát, ktorý je dobrým východiskovým bodom. Dobrý manažment dát môžu výskumníci dosiahnuť aj pomocou niekoľkých prístupov a iniciatív. Online nástroj Centra digitálneho kurátorstva (DCC, Digital Data Curations) [DMPonline tool](http://www.dcc.ac.uk/dmponline) obsahuje mnoho šablón pre financovateľov. Príručka konzorcia CESSDA, Sprievodca manažmentom dát, časť o Ochrane a etike a ochrane dát, [The CESSDA Expert Tour Guide on Data Management](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Ethics-and-data-protection), poskytuje informácie a praktické príklady o tom, ako zdieľať osobné údaje a otázkach súvisiacich s autorskými právami a databázami v Európskych krajinách. Sprievodca tiež obsahuje prehľad dopadov Všeobecného nariadenia o ochrane osobných údajov (GDPR), ktoré má harmonizovať legislatívu o ochrane osobných údajov v Európe \(Máj 2018\) a poskytuje aktualizovaný prehľad rôznej praxe pri ochrane dát v EÚ, [EU diversity on data protection](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Processing-personal-data/Diversity-in-data-protection).[ ](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Processing-personal-data/Diversity-in-data-protection)

###### Dátoví sprostredkovatelia (Data brokers)

Dátoví sprostredkovatelia sú informovaní, nezávislí aktéri, ktorí pôsobia ako správcovia dát pre citlivé dáta. Výskumníci môžu preniesť citlivé dáta a kontrolu nad prístupom k nim na sprostredkovateľa. Tento postup je bežný najmä pri údajoch pacientov z klinických štúdií. Sprostredkovatelia zabezpečujú určitú mieru nezávislosti v hodnotení toho, ktoré žiadosti o dáta sú vedecky platné a neporušia súkromie účastníkov výskumu. Medzi dátových sprostredkovateľov patria [The YODA Project](http://yoda.yale.edu/), [ClinicalStudyDataRequest.com](https://www.clinicalstudydatarequest.com/), [National Sleep Research Resource](https://sleepdata.org/) a [Supporting Open Access for Researchers \(SOAR\)](https://dcri.org/our-approach/data-sharing/).

## <img src="/Images/Icons/data.png" width="150" height="150" />
##### Analytické portály 

Analytické portály sú platformy, ktoré umožňujú realizovať schválenú analýzu dát bez toho, aby bol umožnený úplný prístup \(pozretie alebo stiahnutie\) alebo kontrola toho, kde a kto dostane prístup. Niektorí dátoví sprostredkovatelia tiež využívajú analytické portály. Analytické portály rozhodujú, aké ďalšie súbory dát sa môžu spojiť s citlivými dátami, ako aj to, aké analýzy sa môžu vykonať, aby sa zaistilo, že osobné údaje sa počas opätovnej analýzy neodhalia. Medzi virtuálne analytické portály patria [Project Data Sphere](https://www.projectdatasphere.org/projectdatasphere/html/home), [Vivli](http://vivli.org/), [RAIRD](http://raird.no/), [Corpuscle](http://clarino.uib.no/korpuskel/page) a [INESS](http://clarino.uib.no/iness/page).

Výskumníci z oblasti spoločenských a iných vied s citlivými dátami používajú analytické portály umiestnené na jedinom mieste (single-site analysis portal), ktoré sú prístupné len v kontrolovanom režime. Schválení výskumníci môžu získať prístup k dátam priamo na mieste, v bezpečnej miestnosti, na vedecké účely. Ale metadáta opisujúce dáta by mali byť otvorene dostupné a dodržiavať princípy FAIR.

##### Anonymizované a syntetické dáta (De-identified and synthetic data)

Mnohé dátové súbory, ktoré obsahujú osobné informácie účastníkov, sa môžu zdieľať potom, ako bol daný súbor dát anonymizovaný \(Safe Harbor method\) alebo expert stanovil, že súbor dát jednotlivca sa nedá identifikovať \(Expert Determination method\). Konzultujte so svojou Radou pre etický výskum / Rada pre inštitucionálny dohľa (Research Ethics Board / Institutional Review Board), ako dáta anonymizovať. Tiež odporúčame Sprievodcu manažmentom dát konzorcia CESSDA, časť o Ochrane a etike a ochrane dát, [the CESSDA Expert Tour Guide on Data Management](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Ethics-and-data-protection), ktorá obsahuje  informácie a praktické príklady o tom, ako zdieľať osobné dáta. Niektoré súbory dát sa však nedajú bezpečne anonymizovať (de-identifikovať) a zdieľať. Aj napriek tomu môžu výskumníci zlepšiť otvorenosť výskumu takýchto dát tým, že vytvoria a zdieľajú syntetické dáta. Syntetické dáta sa štruktúrou, obsahom a distribúciou podobajú skutočným dátam a ich cieľom je nadobudnúť "analytickú validitu": výsledky štatistickej analýzy budú rovnaké pri syntetických dátach rovnako ako pri skutočných dátach. Napríklad Americký úrad pre sčítanie ľudu (United States Census Bureau) používa aj syntetické dáta, aj  analytické portály ([synthetic data and analysis portals](https://census.gov/content/dam/Census/programs-surveys/sipp/methodology/SSBdescribe_nontechnical.pdf)), aby umožnil opätovné použitie veľmi citlivých dát.

###### Označenia dát (DataTags)

Systém označení dát, [DataTags](https://datatags.org/), je navrhnutý na to, aby umožnil počítačom asistované hodnotenie právnych a zmluvných obmedzení a obmedzení vyplývajúcich z politík, ktoré podmieňujú rozhodnutia o zdieľaní dát. Systém kladie používateľovi rad otázok s cieľom zistiť kľúčové vlastnosti daného súboru dát a aplikuje logické pravidlá s cieľom určiť, ktoré zákony, kontrakty a najlepšie postupy sú uplatniteľné. Výstupom je odporúčaný súbor označení dát (DataTags) alebo jednoduchých, ikonických štítkov predstavujúcich dátovú politiku, ktorá je čitateľná pre človeka a strojovo využiteľná, a licenčnú dohodu, ktorá je prispôsobená jednotlivemé súboru dát. Systém DataTags je navrhnutý tak, aby sa dal integrovať so softvérom dátových repozitárov, bude tiež fungovať ako samostatný nástroj. DataTags vyvíja Harvardská univerzita. V Európe pracuje holandský inštitút DANS (Data Archiving and Networked Services) na prispôsobení systému DataTags európskej legislatíve / Všeobecnému nariadeniu o ochrane osobných údajov \([GDPR](https://www.eugdpr.org/)\) \(cf. [DANS GDPR DataTags](https://zingtree.com/host.php?style=buttons&tree_id=442670046&persist_names=Restart&persist_node_ids=58#58)\).

Ako je uvedené vyššie, konečný cieľ zdieľania výskumných dát je dosiahnuť to, aby sa dali v čo najväčšej miere opätovne použiť. Aby to bolo možné, predtým ako budete dáta zdieľať, mali by ste ich ošetriť podľa zásad najlepšej praxe. Tieto okrem iného zahŕňajú aj dokumentáciu a výber otvorených formátov súborov a licencií. Viac sa o tom dočítate v [Časti 4: Reprodukovateľný výskum a analýza dát](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md) a v [Časti 6: Otvorené licencie a formáty súborov](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/06OpenLicensingAndFileFormats.md).


## <img src="/Images/Icons/usb.png" width="150" height="150" />
##### Otvorené materiály

Okrem zdieľania dát závisí otvorenosť výskumu aj od zdieľanie materiálov. Použitie materiálov podmieňuje vedná disciplína a niekedy samotné laboratórium. Nižšie v texte sú uvedené príklady materiálov, ktoré môžete zdieľať, ale vždy sa poraďte so kolegami vo svojej disciplíne, aby ste zistili, ktoré repozitár sa používajú. Keď máte materiál, dáta a publikácie z toho istého výskumného projektu uložené v rôznych repozitároch, prepojte ich krížovými odkazmi a jedinečným identifikátorom, aby sa dali ľahko nájsť.

###### Činidlá (Reagens)

Činidlo je látka, zlúčenina alebo zmes, ktorá sa môže pridať do systému s cieľom vyvolať chemickú alebo inú reakciu. Činidlá sa môžu uložiť v repozitároch ako [Addgene](https://www.addgene.org/), [The Bloomington Drosophila Stock Center](https://bdsc.indiana.edu/), a [ATCC](https://www.atcc.org/), aby k nim mali ľahký prístup iní výskumníci. Prideľte licenciu svojmu materiálu, aby ho mohli opätovne použiť iní výskumníci. 

###### Protokoly

Protokol opisuje formálny alebo oficiálny záznam vedeckých experimentálnych pozorovaní v štruktúrovanom formáte. Použite [Protocols.](https://www.protocols.io/)[io](https://www.protocols.io/) na uloženie virtuálnych protokolov na účely citovania, adaptovania a opätovného použitia.

###### Záznamy/dokumenty, kontajnery, softvér a hardvér 

Reprodukovateľnú analýzu podporuje použitie dokumentovaného programovania (literate programming), kontajnerovej technológie a virtualizácie. Okrem zdieľania kódu a dát, by ste tiež mali zdieľať záznamy/dokumenty (napr. z webovej aplikácie Jupyter Notebook), otvorený softvér (napr. šablóny Docker Image) alebo iné analytické materiály alebo softvérové závislosti (software dependancies). Zdieľajte záznamy/dokumnety prostredníctvom otvorených služieb ako [mybinder](http://mybinder.org), ktoré umožňujú verejné prezeranie alebo spustenie celého dokumentu (notebook) na zdieľaných zrdojoch. Kontajnery a záznamy/dokumenty sa môžu zdieľať prostredníctvom projektu [Rocker](https://arxiv.org/abs/1710.03675) alebo platformy [Code Ocean](https://codeocean.com/). Softvér a hardvér, ktorý používate vo svojom výskume, by sa mal zdieľať v súlade s najlepšou praxou pre dokumentáciu, ako je to navrhnuté v [Časti 3](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/03OpenResearchSoftwareAndOpenSource.md). Protokoly prístupné iba na čítanie by ste mali uložiť v registri svojho odboru, ako je [ClinicalTrials.gov](https://clinicaltrials.gov/) a [SocialScienceRegistry](https://www.socialscienceregistry.org/) alebo vo všeobecnom registri ako [Open Science](https://osf.io/)[ Framework](https://osf.io/). Mnoho časopisov ako [Trials](https://trialsjournal.biomedcentral.com/), [JMIR Research Protocols](https://www.researchprotocols.org/) alebo [Bio-Protocol](https://bio-protocol.org/) uverejnia váš protokol. Najlepšie postupy na publikovanie protokolu v otvorenom režime sú rovnaké ako postupy na publikovanie vašej správa v otvorenom režime \(pozri [Časť 5](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/05OpenAccessToPublishedResearchResults.md)\).


## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Otázky, prekážky a bežné mylné predstavy

Q: "Is it sufficient to make my data openly available?"

A: "No—openness is a necessary but not sufficient condition for maximum reuse. Data have to be FAIR in addition to open."

Q: "What do the FAIR principles mean/imply for different stakeholders/audiences?"

A: "This is a great topic for discussion!"

Obstacle: Researchers may be reluctant to share their data because they are afraid that others will reuse them before they have extracted the maximum usage from them, or that others might not fully understand the data and therefore mis-use them.

\(suggested\) A: You may publish your data to make them findable with metadata, but set an embargo period on the data to make sure that you can publish your own article\(s\) first.

Q: "Is making my data FAIR a lot of extra work?"

A: "Not necessarily! Making data FAIR is not only the responsibility of the individual researchers but of the whole group. The best way to ensure that your data is FAIR is to create a Data Management Plan and plan everything beforehand. During the data collection and data processing follow the discipline standards and measures recommended by a repository.

Q: "I want to share my data. How should I license them?"

A: "That’s a good question. First of all think about who owns the data? A research funder or an institution that you work for. Then, think about authorship. Applying a suitable license to your data is crucial in order to make them reusable. For more information about licensing, please see [6. Open Licensing and File Formats](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/tree/master/02OpenScienceBasics/06OpenLicensingAndFileFormats).

Q: "I cannot make my data directly available—they are too large to share conveniently / have restrictions related to privacy issues. What should I do?"

A: "You should talk to experts in domain specific repositories on how to provide sufficient instructions to make your data findable and accessible."


## <img src="/Images/Icons/output.png" width="150" height="150" />
### Výsledky vzdelávania

1. Understand the characteristics of open data, and in particular the FAIR principles.

2. Be familiar with some of the arguments for and against open data.

3. Be able to differentiate and address sensitive data and opFAIR data; these two categories are not necessarily incompatible.

4. Be able to transform a dataset into one that is sufficient for open sharing \(non-proprietary format\), meets the standards of the FAIR principles, and is designed for maximized accessibility, transparency and re-use by providing sufficient metadata.

5. Know the difference between raw and processed \(or cleaned\) data, and the importance of version labels.

6. Know commonly used file formats and community standards for maximum re-usability.

7. Be able to write a data management plan.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Ďalšie odporúčané čítanie
* Averkamp et al. (2018). Data packaging guide. [github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md](https://github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md).

* Barend et al. (2017). Cloudy, increasingly FAIR; revisiting the FAIR Data guiding principles for the European Open Science Cloud. [doi.org/10.3233/ISU-170824](https://doi.org/10.3233/ISU-170824)

* Brase et al. (2009). Approach for a joint global registration agency for research data. [doi.org/10.3233/ISU-2009-0595](https://doi.org/10.3233/ISU-2009-0595)

* Candela et al. (2015). Data journals: A survey. [doi.org/10.1002/asi.23358](https://doi.org/10.1002/asi.23358)

* CESSDA Training Working Group (2017-2018a). CESSDA Data Management Expert Guide. Bergen, Norway: CESSDA ERIC. [cessda.eu/DMGuide](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management)

* CESSDA Training Working Group (2017-2018b). CESSDA Data Management Expert Guide: Citing your data. Bergen, Norway: CESSDA ERIC.[cessda.eu/DMGuide/citingdata](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/6.-Archive-Publish/Publishing-with-CESSDA-archives/Citing-your-data)

* FAIRsharing.org (2016). FAIR. The FAIR Principles. [doi.org/10.25504/FAIRsharing.WWI10U](https://doi.org/10.25504/FAIRsharing.WWI10U)

* Force 11 (n.y.). Guiding principles for Findable, Accessible, Interoperable, and Re-usable data publishing Version B1.0. [force11.org/fairprinciples](https://www.force11.org/fairprinciples)

* Gorgolewski et al. (2013). Making data sharing count: a publication-based solution. [doi.org/10.3389/fnins.2013.00009](https://doi.org/10.3389/fnins.2013.00009)

* Kratz and Strasser (2015). Making Data Count. [doi.org/10.1038/sdata.2015.39](https://www.nature.com/articles/sdata201539) 

* Piwowar and Vision (2013). Data reuse and the open data citation advantage. [doi.org/10.7717/peerj.175](https://doi.org/10.7717/peerj.175)

* Wilkinson et al. (2016). The FAIR Guiding Principles for scientific data management and stewardship. [doi.org/10.1038/sdata.2016.18](https://doi.org/10.1038/sdata.2016.18)

* Wilkinson et al. (2918). A design framework and exemplar metrics for FAIRness. [doi.org/10.1038/sdata.2018.118](https://doi.org/10.1038/sdata.2018.118)


#### Iniciatívy a projekty

* DANS GDPR DataTags. [zingtree.com](https://zingtree.com/host.php?style=buttons&tree_id=442670046&persist_names=Restart&persist_node_ids=58#58)

* FAIR Metrics. [fairmetrics.org](http://fairmetrics.org/)

* GO FAIR Initiative. [go-fair.org](https://www.go-fair.org/)

*  The FAIR Data Principles explained. [go-fair.org](https://www.go-fair.org/fair-principles/)

*  5★ OPEN DATA. [5stardata.info](http://5stardata.info/en/)


