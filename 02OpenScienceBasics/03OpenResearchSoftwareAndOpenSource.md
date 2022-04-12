<img src="/Images/Icons/open_source_software.png" width="150" height="150" /> <img src="/Images/Icons/publish.png" width="150" height="150" />
## 3. Otvorený výskumný softvér a otvorený zdrojový kód  

### Čo je to?

Otvorený výskumný softvér alebo softvér s otvoreným zdrojovým kódom znamená, že ide o používanie a vývoj softvéru na analýzu, simuláciu, vizualizáciu atď., ktorého zdrojový kód je úplne dostupný. Podľa definície otvoreného zdrojového kódu ([Open Source Definition](https://opensource.org/osd)) sa softvér s otvoreným zdrojovým kódom musí distribuovať vo forme zdrojového kódu a/alebo kompilovanej forme \(v druhom prípade s dostupným zdrojovým kódom\) a musí sa zdieľať pod licenciou, ktorá umožňuje jeho modifikáciu, odvodenie a redistribúciu.

### Odôvodnenie

Moderný výskum sa spolieha na softvér a ďalší rozvoj alebo reprodukovanie daného výskumu si vyžaduje prístup k úplnému zdrojovému kódu daného softvéru \([Barnes, 2010](https://doi.org/10/cj8t6n); [Morin et al., 2012](https://doi.org/10/m5t); [Ince et al., 2012](https://doi.org/10/hqg); [Prins et al. 2015](https://doi.org/10/f3mn4p); [Lowndes et al., 2018](https://doi.org/10/gc4jb3)\). Ako povedali Buckheit a Donoho, parafrázujúc Jona Claerbouta, "Článok  o výpočtovom výsledku je reklama, nie veda. Skutočný vedecký článok informuje o úplnom softvérovom prostredí, kóde a dátach, ktoré priniesli výsledok." \([Buckheit & Donoho, 1995](https://doi.org/10.1007/978-1-4612-2544-7_5)\). Otvorený prístup k otvorenému zdrojovému kódu výskumného softvéru tiež zlepšuje impakt výskumu \([Vandewalle, 2012](https://doi.org/10/gc5sjp)\).

Zdieľanie softvéru, ktorý sa použil vo výskume \(či už ide výpočtový výskum alebo výskum využívajúci analýzu/interpretáciu založenú na softvéri\), je potrebná ale nie postačujúca podmienka reprodukovateľnosti. Vyplýva to z nevyhnutnej nejednoznačnosti, ktorá vzniká pri snahe o úplný opis softvéru pomocou prirodzeného jazyka, napr. v článku \([Ince et al., 2012](https://doi.org/10/hqg)\). Mnoho \(ak nie väčšina\) softvérových programov môže navyše obsahovať nejaké nezistené chyby \([Soergel, 2015](https://doi.org/10/gc5sjg)\), takže dokonca aj "dokonale" napísaný opis softvéru by nedokázal vysvetliť?objasniť?zdôvodniť?zahrnúť všetky výsledky.  so even a "perfect" written description of software would not be able to account for all results.

Otvorené zdieľanie softvéru umožňuje okrem reprodukovateľnosti aj to, aby bol tvorcom, vývojárom, priznaný kredit za ich úsilie buď prostredníctvom citovania \([Smith et al., 2016](https://doi.org/10/bw3g)\) alebo meta-článkov o softvére publikovaných napríklad v časopise [Journal of Open Research Software](http://openresearchsoftware.metajnl.com) alebo [Journal of Open Source Software](http://joss.theoj.org). Neil Chue Hong vedie zoznam mnohých odborových časopisov ([list of many domain-specific journals](https://www.software.ac.uk/which-journals-should-i-publish-my-software)), ktoré uverejňujú články o softvére.

## <img src="/Images/Icons/finish.png" width="150" height="150" />
### Ciele vzdelávania

1. Poznať charakteristiky otvoreného softvéru; pochopiť etické, právne, ekonomické argumenty pre otvorený softvér a proti nemu, ako aj argumenty o jeho dopade na výskum; porozumieť požiadavkám na kvalitu otvoreného kódu.

2. Naučiť sa, ako používať existujúci otvorený softvér a ako ho správne citovať alebo uviesť autora.

3. Naučiť sa, ako používať bežné nástroje a služby na otvorené zdieľanie výskumných kódov.   Learn how to use common tools and services for sharing research codes openly.

4. Vedieť vybrať vhodnú licenciu pre softvér a pochopiť rozdiel medzi permisívnymi a nepermisívnymi licenciami.

### Kľúčové prvky

## <img src="/Images/Icons/brain.png" width="150" height="150" />
#### Poznatky

K dispozícii máme niekoľko platforiem, ktoré do nejakej miery podporujú otvorené zdieľanie a spoluprácu na softvére či výskume. Najprv si overte otvorenosť existujúceho výskumného softvéru, na jeho hodnotenie môžete použiť tento kontrolný zoznam:

* Je softvér dostupný a dá sa stiahnuť a inštalovať? 

* Dá sa softvér jednoducho inštalovať na rôznych platformách?  

* Má softvér podmienky na používanie?  

* Je možné preskúmať zdrojový kód?  Is the source code available for inspection?

* Je vývoj verzií zdrojového kódu k dispozícií na preskúmanie prostredníctvom verejne dostupnej histórie verzií?  Is the full history of the source code available for inspection through a publicly available version history?

* Sú závislosti (dependencies) softvéru \(hardvér a softvér\) správne opísané? Vyžaduje získanie a použitie týchto závislostí iba primerane minimálne úsilie?  Are the dependencies of the software (hardware and software) described properly?Do these dependencies require only a reasonably minimal amount of effort to obtain and use?

Tieto vlastnosti sa vzťahujú k definícii otvoreného zdrojového kódu ([Open Source Definition](https://opensource.org/osd)) a stavajú na nej.

[GitHub](www.github.com) je obľúbený nástroj, ktorý umožňuje kontrolu verzií: manažment a celkové sledovanie zmien v konkrétnej časti softvéru. Služby ako [GitHub](www.github.com), [GitLab](https://about.gitlab.com/), [Bitbucket](https://bitbucket.org/) a iné poskytujú rozhranie na prístup k nástroju, ako aj služby vzdialeného úložiska, ktoré je možné využiť na spoluprácu a udržiavanie a zdieľanie výskumného softvéru  Nástroj je dosť rozšírený a hoci si na začiatku vyžaduje viac učenia, ukázalo sa, že je neoceniteľným nástrojom pri vytváraní otvorených a reprodukovateľných pracovných postupov výskumu.

Uložiť výskumný softvér na GitHub je len prvý krok, je rovnako dôležité, aby mal zverejnený trvalý identifikátor, ako napríklad DOI. Exituje niekoľko spôsobov, ako spojiť DOI s repozitárom GitHub: najjednoduchší spôsob na vytvorenie a pridelenie trvalého identifikátora je využitie repozitára [Zenodo](www.https://zenodo.org/) \(bezplatný, otvorený univerzálny repozitár, ktorý vytvorili organizácie [OpenAIRE](https://www.openaire.eu/) a [CERN](https://home.cern/)\), hoci k dispozícii sú aj ďalšie repozitáre na archivovanie softvéru a získanie DOI, napríklad [Figshare](https://figshare.com/). [Zenodo sa integruje s GitHub](https://guides.github.com/activities/citable-code/) s cieľom archivovať softvér a prideliť  mu DOI, keď ho vývojári formálne zverejnia v GitHub-e.

Verejne zdieľaný softvér v skutočnosti nie je softvér s otvoreným zdrojovým kódom, pokiaľ nemá vhodnú licenciu, pretože na softvér sa štandardne \(rovnako ako iné výsledky tvorivej činnosti\) vzťahujú výhradné autorské práva tvorcov. Znamená to, že nikto iný nemôže použiť, kopírovať, šíriť či modifikovať vašu prácu \([choosealicense.com](https://choosealicense.com/no-permission/)\). \(Ak skutočne chcete zdieľať svoj kód bez akýchkoľvek obmedzení, môžete ho venovať verejnej sfére ([dedicate it to the public domain](https://choosealicense.com/licenses/#unlicense)), (pozn. prekl. - na Slovensku treba postupovať v súlade so slovenským autorským zákonom.\) Namiesto toho by ste mali pre svoj softvér vybrať vhodnú licenciu, a to na základe toho, čo chcete umožniť iným používateľov robiť so svojím kódom \(alebo im v tom zabrániť\). Stránka na výber licencie ([choosealicense.org](https://choosealicense.com)) je užitočný zdroj na rozlíšenie medzi licenciami, hoci neuvádza ([všetky dostupné alebo obľúbené open-source licencie](https://opensource.org/licenses)). Po výbere licencie vložte text s menom autora/autorov a rokom vloženia do repozitára softvérov ako obyčajný textový súbor označený ako LICENCIA (plaintext LICENSE file).

![](/Images/02%20Open%20Science%20Basics/02_open_research_software_open_source.png)

Hoci je lepšie zdieľať softvér v akejkoľvek forme ako ho nezdieľať vôbec, jeho dopad bude väčší a ďalší používatelia, vrátane vás samotných v budúcnosti, ho budú môcť použiť jednoduchšie, ak budete zdieľať aj dokumentáciu. Táto môže zahŕňať užitočné poznámky v kóde, ktoré vysvetlia **prečo** ste niečo urobili \(skôr ako to, čo ste urobili, pretože to by malo byť zrejmé\), informatívny README súbor, ktorý opisuje to, čo váš softvér robí a obsahuje užitočné informácie \(napr., spôsob inštalácie, citovanie, spustenia, dôležité závislosti\), tutoriály/príklady a/alebo API dokumentáciu \(ktorá sa môže automaticky vygenerovať zo správne naformátovaných poznámok v kóde\).

Chýbajúce alebo nedostupné závislosti alebo nedostatočná dokumentácia výpočtového prostredia predstavujú veľmi časté prekážky opätovného použitia a reprodukovateľnosti. Jeden zo spôsobov ako odstrániť tieto prekážky je zdieľať kód s výpočtovým prostredím pomocou kontajnerovej technológie. Kontajnery obsahujú kód so závislosťami a výpočtovým prostredím, takže ďalší používatelia môžu vašu analýzu spustiť jednoduchšie. Medzi príklady implementácie kontajnerov vo výskume patria platformy [Rocker](https://arxiv.org/abs/1710.03675), [Binder](https://mybinder.readthedocs.io/en/latest/) a [Code Ocean](https://codeocean.com/).

Keď používate softvér, či už ste ho napísali vy alebo niekto iný, kto ho aj sprístupnil, je dôležité, aby ste softvér správne citovali kvôli reprodukovateľnosti \(viac v [Časti 4](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md); stručne - verzia, ktorú ste použili, môže zmeniť výsledky alebo interpretáciu\) a priznaniu autorstva (kreditu) tvorcom softvéru \([Niemeyer 2016](doi.org/10/gc5sjd), [Smith 2016](https://doi.org/10/bw3g)\). Rozhodnutie o tom, kedy citovať, je na vás ako na vedcovi, ale odporúčame citovať vždy, keď softvér vykonal nejakú činnosť, ktorá je neoddeliteľnou súčasťou vašich výsledkov, interpretácie alebo záverov. Najlepší spôsob ako umožniť, aby sa dal _váš_ kód ľahko citovať, je využiť prepojenie repozitárov GitHub a Zenodo, spomenuté vyššie v texte, a uviesť výsledný identifikátor digitálneho objektu (DOI) na zrejmom mieste, ako je README súbor softvéru, možno spolu s navrhovanou formou citácie. Pri citovaní softvéru by ste mali uviesť minimálne meno autora/autorov, názov softvéru, číslo verzie a jedinečný identifikátor/lokátor \([Smith 2016](https://doi.org/10/bw3g)\). Ak používate softvér niekoho iného, kto uviedol aj DOI, môžete pomocou tohto identifikátora jednoducho identifikovať softvér a nasmerovať naň. Pokiaľ softvér nearchivovali, mali by ste uviesť adresu URL, kde sa dá softvér nájsť a číslo verzie alebo \(napr.\) commit hash (pozn. prekl., ide o identifikátor (hash) zmeny súboru (commit)).

Komplikovanejšie koncepty obsahujú aj automatické testovanie a nepretržitú integráciu softvéru, balíky softvéru v binárnych formátoch a správu a manažment projektov s otvoreným zdrojovým kódom, ktoré rieši viacero osôb \(t.j., kódexy správania, príručky prispievateľov/contributing guides\).  Niektorým témam sa venujú [Scopatz a Huff \(2015\)](http://lilith.fisica.ufmg.br/~dickman/transfers/comp/textos/Effective%20Computation%20in%20Physics%20(Python).pdf). [Wilson et al. \(2017\)](https://doi.org/10/gbkbwp) tiež poskytujú praktického sprievodcu najlepších postupov vedeckého programovanie (scientific computing), ktorý obsahuje rady špecifické pre vývoj výskumného softvéru.

## <img src="/Images/Icons/laptop.png" width="150" height="150" />
##### Open-source hardvér 

Vyššie uvedené princípy otvoreného zdroja sa vzťahujú aj na hardvér. Vedci vo svojom výskume často používajú proprietárne prístroje alebo hardvér, ktorý nie je voľne prístupný, nedá sa opätovne použiť alebo prispôsobiť. Vedecký hardvér zahŕňa všetko od sekvenčných nástrojov a mikroskopov až po špecializované testovacie zariadenia a urýchľovače častíc. Napríklad komunita pre otvorený vedecký hardvér \(OScH\, z angl. Open Science Hardware) prostredníctvom svojho Globálneho plánu otvoreného vedeckého hardvéru ([Global Open Science Hardware Roadmap](http://openhardware.science/global-open-science-hardware-roadmap/))presadzuje, aby hnutie za otvorený softvér zahrnulo aj vedecké nástroje, hardvér a výskumnú infraštruktúru.

## <img src="/Images/Icons/gears.png" width="150" height="150" />
#### Zručnosti

* Vytvoriť repozitár vo webovej službe GitHub a umožniť integráciu s repozitárom Zenodo. Zabezpečiť prvé vydanie softvéru.    Create a repository on GitHub, and enable the integration with Zenodo. Mint the first release of the software.

* Vybrať  softvérovú licenciu pomocou nástroja \(napr.\) [choosealicense](https://choosealicense.com) alebo iniciatívy [Open Source Initiative](https://opensource.org/licenses).

* Vytvoriť dokumentáciu pre softvérový balík, vrátane súboru README, poznámok a príkladov.

* V článku správne citovať použitý softvér. ? Správne citovať softvér použitý pre článok. Appropriately cite software used for a paper.

## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Otázky, prekážky a bežné mylné predstavy 

Otázka: "Nemôžem zdieľať svoj softvér - je príliš chaotický / nemá dobrú dokumentáciu / neurobil som dobré poznámky!"

Odpoveď: Vývojári výskumného softvéru na celom svete tento pocit chápu - tvorcovia majú málokedy pocit, že ich kód je pripravený na verejné zdieľanie alebo že je "dokončený". Avšak ako napísal [Barnes \(2010\)](https://doi.org/10/cj8t6n), “ak je váš kód dostatočne dobrý na to, aby urobil svoju úlohu, je dosť dobrý na to, aby sa mohol vydať - a jeho vydanie pomôže vášmu výskumu, aj vašej oblasti." Inými slovami, ak ste so svojím softvérom takí spokojní, že publikujete štúdiu alebo oznámite výsledky, tak je kód dostatočne vyvinutý na to, aby ste ho mohli zdieľať so svojimi kolegami. \(Naopak, ak nemáte dobrý pocit zo zdieľania kódu, potom možno potrebuje viac času na vývoj alebo testovanie pred tým, ako ho použijete v publikácii.\). Okrem toho zdieľaním svojho kódu umožníte iným, aby ho zlepšovali a ďalej rozvíjali, čo povedie k ešte väčšiemu dopadu a inovácii \(a citáciám pre vás!\).

Otázka: "Čo ak niekto použije kód, ktorý som zdieľal, na nekalé účely alebo bude tvrdiť, že ho napísal?"

Odpoveď: Výberom vhodnej licencie na svoj softvér si zabezpečíte ochranu pred tým, aby iní ľudia akokoľvek použili váš softvér. Napríklad často používaná licencia MIT ([MIT License](https://choosealicense.com/licenses/mit/)) obsahuje aj obmedzenie zodpovednosti a zároveň deklaruje, že sa neposkytuje žiadna záruka. Ak sa bude niekto iný snažiť tvrdiť, že napísal softvér, ktorý ste vy sprístupnili, môžete poukázať na časové pečiatky (timestamps) vo svojom repozitári alebo archivované verzie ako na dôkaz toho, že vaša práca bola prvá.         Selecting an appropriate license for your software will help protect you from any uses of your software by others; for example, the common [MIT License](https://choosealicense.com/licenses/mit/) includes both limitations of liability and states that no warranty is provided. If someone else tries to claim that they wrote the software you made available, then you can point to the timestamps on your repository or archived versions as proof of your prior work.

Otázka: "Ak budem zdieľať svoj kód v online repozitári, zaplavia ma žiadosti o používateľskú podporu."

Odpoveď: Hoci je možné je vás potencionálni používatelia požiadajú o pomoc, buď cez email alebo \(napr.\) podaním otázky/problému v online repozitári, nemáte žiadnu povinnosť poskytnúť odporu, ak tak nechcete alebo nemôžete urobiť. Vhodná licencia vás dokonca pred tým právne ochráni \(napr. klauzula o neposkytnutí žiadnych záruk licencie MIT ([MIT License](https://choosealicense.com/licenses/mit/)\)).

Bežné mylné predstavy: zverejnenie kódu online stačí na to, aby bol softvér otvorený. V skutočnosti je to tak, že pokiaľ softvér nemá licenciu, ktorá udeľuje povolenie iným používateľom na použite, kopírovanie, modifikovanie a/alebo distribúciu, znamená to, že si vývojár/vývojári ponecháva/jú výhradné autorské práva. Ku kódu musí byť pripojená open-source licencia, aby sa softvér mohol považovať za softvér s otvoreným zdrojovým kódom.

## <img src="/Images/Icons/output.png" width="150" height="150" />
### Výsledky vzdelávania

1. Naučiť sa zdieľať softvér pod najvhodnejšou licenciou \(t.j., vedieť používať aj nástroje, aj licencie\).

2. Vedieť sa nahrať (upload), vytvárať verzie a registrovať časť kódu s trvalým identifikátorom.  Be able to upload, version, and register a piece of code under a persistent identifier.

3. Vedieť citovať softvér použitý vo vedeckom článku.  Be able to cite software used for a research article.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Ďalšie odporúčané čítanie

* Balasegaram et al. (2017). An open source pharma roadmap. [doi.org/10.1371/journal.pmed.1002276](https://doi.org/10.1371/journal.pmed.1002276) 

* Dryden et al. (2017). Upon the Shoulders of Giants: Open-Source Hardware and Software in Analytical Chemistry. [doi.org/10.1021/acs.analchem.7b00485](https://pubs.acs.org/doi/abs/10.1021/acs.analchem.7b00485) 

* Ince et al. (2012). The case for open computer programs.[doi.org/10.1038/nature10836](https://doi.org/10.1038/nature10836)

* Iskoujina and Roberts (2015). Knowledge sharing in open source software communities: motivations and management. [PDF](https://pdfs.semanticscholar.org/f2a2/c5129cf5656af7acc7ffaf84c9c9bafe72c5.pdf)

* Jiménez et al. (2017).Four simple recommendations to encourage best practices in research software. [doi.org/10.12688/f1000research.11407.1](https://doi.org/10.12688/f1000research.11407.1) 

* Martinez-Torres and Diaz-Fernandez (2013).Current issues and research trends on open-source software communities [PDF](https://idus.us.es/xmlui/bitstream/handle/11441/32245/Current%20issues%20and%20research%20trends.pdf?sequence=1) 

* Morin et al. (2012). Shining Light into Black Boxes. [PDF](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4203337/pdf/nihms588981.pdf)

* Oishi et al. (2018). Perspectives on Reproducibility and Sustainability of Open-Source Scientific Software from Seven Years of the Dedalus Project. [arXiv:1801.08200v1 [astro-ph.IM]](https://arxiv.org/abs/1801.08200)

* Scacchi (2010). The Future of Research in Free/Open Source Software Development. [PDF](http://www.ics.uci.edu/~wscacchi/Papers/New/FoSER-Scacchi-2010.pdf)

* Sandve et al. (2013). Ten simple rules for reproducible computational research [doi.org/10.1371/journal.pcbi.1003285](https://doi.org/10.1371/journal.pcbi.1003285) 

* Shamir et al. (2013).Practices in source code sharing in astrophysics. [arXiv:1304.6780v1 [astro-ph.IM]](https://arxiv.org/abs/1304.6780) 

* Steinmacher et al. (2014). A systematic literature review on the barriers faced by newcomers to open source software projects. [PDF](http://igor.pro.br/publica/papers/IST_SysReview_PrePrint.pdf) 

* Stodden (2010). The Scientific Method in Practice: Reproducibility in the Computational Sciences.[PDF](http://datascienceassn.org/sites/default/files/The%20Scientific%20Method%20in%20Practice%20-%20Reproducibility%20in%20the%20Computational%20Sciences.pdf)

* Vandewalle (2012). Code Sharing Is Associated with Research Impact in Image Processing. [PDF](https://infoscience.epfl.ch/record/206184/files/Vandewalle12.pdf) 
