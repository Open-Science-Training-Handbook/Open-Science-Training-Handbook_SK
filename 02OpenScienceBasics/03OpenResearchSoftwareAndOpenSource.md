<img src="/Images/Icons/open_source_software.png" width="150" height="150" /> <img src="/Images/Icons/publish.png" width="150" height="150" />
## 3. Otvorený výskumný softvér a otvorený zdrojový kód  Open Research Software and Open Source

### Čo je to?

Otvorený výskumný softvér alebo softvér s otvoreným zdrojovým kódom sa vzťahuje na používanie a vývoj softvéru na anlýzu, simuláci, vizualizáciu atď., ak je úplný zdrojový kód dostupný. Podľa definície otvoreného zdrojového kódu ([Open Source Definition](https://opensource.org/osd)) sa softvér s otvoreným zdrojovým kódom musí distribuovať vo forme zdrojového kódu a/alebo kompilovanej forme \(v druhom prípade s dostupným zdrojovým kódom\), a musí sa zdieľať pod licenciou, ktorá umožňuje modifikáciu, odvodenie a redistribúciu.

### Odôvodnenie

Moderný výskum sa spolieha na softvér a ďalšie rozvíjanie alebo reprodukovanie daného výskumu si vyžaduje prístup k úplnému zdrojovému kódu daného softvéru \([Barnes, 2010](https://doi.org/10/cj8t6n); [Morin et al., 2012](https://doi.org/10/m5t); [Ince et al., 2012](https://doi.org/10/hqg); [Prins et al. 2015](https://doi.org/10/f3mn4p); [Lowndes et al., 2018](https://doi.org/10/gc4jb3)\). Ako povedali Buckheit a Donoho, parafrázujúc Jona Claerbouta, "Článok  o výpočtovom výsledku je reklama, nie veda. Skutočný vedecký článok informuje o úplnom softvérovom prostredí, óde a dátach, ktoré vyprodukovali výsledok. ? Skutočná veda znamená úplné softvérové prostredie, kód a dáta, ktoré vyprodukovali ?priniesli výsledok. " An article about a computational result is advertising, not scholarship. The actual scholarship is the full software environment, code and data, that produced the result’’ \([Buckheit & Donoho, 1995](https://doi.org/10.1007/978-1-4612-2544-7_5)\). Otvorený prístup k otvorenému zdrojovému kódu výskumného softvéru tiež zlepšuje impakt výskumu \([Vandewalle, 2012](https://doi.org/10/gc5sjp)\).

Zdieľanie softvéru, ktorý sa použil vo výskume \(či už ide výpočtový výskum alebo výskum využívajúci analýzu/interpretáciu založenú na softvéri\), je potrebná ale nie postačujúca podmienka reprodukovateľnosti. Vyplýva to z nevyhnutnej nejednoznčnosti, ktorá vzniká pri snake o úplný opis softvéru pomocou prirodzeného jazyka, napr., v článku   This is due to the unavoidable ambiguity that arises when trying to fully describe software using natural language, e.g., in a paper \([Ince et al., 2012](https://doi.org/10/hqg)\). Mnoho \(ak nie väčšina\) softvérových programov môže navyše obsahovať nejaké nezistené chyby \([Soergel, 2015](https://doi.org/10/gc5sjg)\), takže dokonca aj "dokonale" napísaný opis softvéru by nedokázal vysvetliť?objasniť?zdôvodniť?zahrnúť všetky výsledky.  so even a "perfect" written description of software would not be able to account for all results.

Otvorené zdieľanie softvéru umožňujej okrem reprodukovateľnosti aj to, aby bol tvorcom, vývojárom, priznaný kredit za ich úsilie buď prostredníctvom citovania \([Smith et al., 2016](https://doi.org/10/bw3g)\) alebo meta-článkov o softvére publikovaných napríklad v časopise [Journal of Open Research Software](http://openresearchsoftware.metajnl.com) alebo [Journal of Open Source Software](http://joss.theoj.org). Neil Chue Hong vedie zoznam mnohých odborových časopisov ([list of many domain-specific journals](https://www.software.ac.uk/which-journals-should-i-publish-my-software)), ktoré uverejňujú články o softvére.

## <img src="/Images/Icons/finish.png" width="150" height="150" />
### Ciele vzdelávania

1. Naučiť sa charakteristiky ovtoreného softvéru; pochopiť etické, právne, ekonomické argumenty pre a proti otvorenému softvéru, ako aj argumenty o jeho dopade na výskum; porozumieť požiadavkám na kvalitu zótvoreného kódu.

2. Naučiť sa, ako používaťť existujúci otvorený softvér a ako ho správne citovať alebo uviesť autora.

3. Naučiť sa, ako používať spoločné?bežne nástroje a služby na otvorené zdieľanie výskumných kódov.   Learn how to use common tools and services for sharing research codes openly.

4. Vedieť vybrať vhodnú licenciu pre sofvtér a pochopiť rozdiel medzi permisívnymi a nepermisívnymi licenciami.

### Kľúčové prvky

## <img src="/Images/Icons/brain.png" width="150" height="150" />
#### Poznatky

K dispozícii máme niekoľko patforiem, ktoré do nejakej miery podporujú otvorené zdieľanie a spoluprácu na softvére, výskume. Najprv si overte otvorenosť existujúceho výskumného softvéru, na takéto hodnotenie môžete použiť tento kontrolný zoznam:  There are several different platforms that support open sharing and collaboration on software, research or otherwise. = nie je mi úplne jasné, na čo sa tu vzťahuje to "otherwise" First of all, you can use this checklist to evaluate openness of existing research software:

* Je softvér dostupná a dá stiahnuť a inštalovať? Is the software available to download and install?

* Dá sa softvér jednoducho inštalovať na rôznych platformách?  sCan the software easily be installed on different platforms?

* Má softvér podmienky na používanie?  Does the software have conditions on the use?

* Je zdrojový kód dostupný na kontrolu? Je môžné preskúmať zdrojový kód?  Is the source code available for inspection?

* Je úplná história zdrojového kódu k dispozícii na preskúmanie prostredníctvom verejne dostupnej histórie verzií?  Is the full history of the source code available for inspection through a publicly available version history?

* Sú závislosti (dependencies) sofvéru \(hardvér a softvér\) správne opísané? Vyžaduje získanie a použitie týchto závislostí iba priemrane minimálne úsilie?  Are the dependencies of the software (hardware and software) described properly?Do these dependencies require only a reasonably minimal amount of effort to obtain and use?

Tieto vlastnosti sa vzťahujú k definícii otvoreného zdrojového kódu ([Open Source Definition](https://opensource.org/osd)) a stavajú na nej.

[GitHub](www.github.com) je obľúbený nástroj, ktorý umožňuje kontrolu verzií: mamanžment a celkové sledovanie zmien v konkrétnej časti softvéru. Služby ako [GitHub](www.github.com), [GitLab](https://about.gitlab.com/), [Bitbucket](https://bitbucket.org/) a ďalšie poskytujú rozhranie, interfejs, na prístup k nástroju, ako aj služby vzdialeného úložiska, ktoré je možné využiť na udržiavanie a zdieľanie výskumného softvéru a spoluprácu na ňom. Nástroj je dosť rozšírený a hoci si na začiatku vyžaduje viac učenia, ukázalo sa, že je neoceniteľným nástrojom pri vytváraní otvorených a reprodukovateľných pracovných postupov výskumu.

Uložiť výskumný softvér na GitHub je len prvý krok, je rovnako dôležité, aby mal zverejnený trvalý identifikátor, ako napríklad DOI. Exituje niekoľko spôsobov, ako spojiť DOI s repozitárom GitHub: najjednoduchší spôsob na vytvorenie a pridelenie trvalého identifikátora je využitie repozitára [Zenodo](www.https://zenodo.org/) \(bezplatný, otvorený univerzálny repozitár vytvorený organizáciami [OpenAIRE](https://www.openaire.eu/) a [CERN](https://home.cern/)\), hoci k dispozícii sú aj ďalšie repozitáre na archivovanie softvéru a získanie DOI ako [Figshare](https://figshare.com/). [Zenodo sa integruje s GitHub](https://guides.github.com/activities/citable-code/) s cieľom archivovať softvér a prideliť  mu DOI, keď ho vývojári formálne zverejnia v GitHub-e.

Verejne zdieľaný softvér v skutočnosti nie je softvér s otvoreným zdrojovým kódom, pokiaľ nemá vhodnú licenciu, pretože softvér štandardne \(rovnkao ak iné výsledky tvorivej činnosti\) patrí pod výhradné autorské práva tvorcov. Znamená to, že nikto iný nemôže použiť, kopírovať, šíriť či modifikovať vašu prácu \([choosealicense.com](https://choosealicense.com/no-permission/)\). \(Ak skutočne chcete zdieľať svoj kód bez akýchkoľvek obmedzení, môžete ho venovať verejnej sfére ([dedicate it to the public domain](https://choosealicense.com/licenses/#unlicense)), pozn. prekl. - na Slovensku v súlade s autorským zákonom.\) Namiesto toho by ste mali pre svoj softvér vybrať vhodnú licenciu, a to na základe toho, čo chcete nechať iných používateľov robiť so svojím kódom \(alebo im v tom zabrániť\). Stránka na výber licencie ([choosealicense.org](https://choosealicense.com)) je užitočný zdrojom na rozlíšenie medzi licenciami, hoci neuvádza ([všetky dostupné alebo obľúbené open-source licencie](https://opensource.org/licenses)). Po výbere licencie, vložte text s menom autora/autorov a rokom vloženia do repozitára softvérov ako obyčajný textový súbor označneý ako LICENCIA (plaintext LICENSE file).

![](/Images/02%20Open%20Science%20Basics/02_open_research_software_open_source.png)

Although sharing software in any form is better than not sharing it, your software will have more impact and be more easily used by others—and your future self!—if you include documentation. This can include helpful comments in the code that explain **why** you did something \(rather than what you did, which should be evident\), an informative README file that describes what your software does and gives some helpful information \(e.g., how to install, how to cite, how to run, important dependencies\), tutorials/examples, and/or API documentation \(which may be automatically generated from properly formatted comments in the code\).

Missing or inaccessible dependencies or insufficient documentation of the computational environment are very common barriers to reuse and reproducibility. One approach to address these barriers is to share your code with your computational environment using container technology. Containers package the code with the dependencies and computational environment so others can more easily run your analysis. Examples of container implementation in research include [Rocker](https://arxiv.org/abs/1710.03675), [Binder](https://mybinder.readthedocs.io/en/latest/), and [Code Ocean](https://codeocean.com/).

When you use software — whether you wrote it, or someone else did and made it available — appropriate citation is important for reproducibility \(discussed more in [Section 4](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md); briefly, the version used can change your results or interpretation\) and giving credit to the developers of the software \([Niemeyer 2016](doi.org/10/gc5sjd), [Smith 2016](https://doi.org/10/bw3g)\). The decision of when to cite software is up to you as the researcher, but we recommend a citation whenever the software did some work integral to your results, interpretation, or conclusions. The best way to make _your_ code easily citable is to use the GitHub–Zenodo integration described before and provide the resulting DOI in an obvious place like the software’s README, perhaps along with a suggested citation format. When citing any software, you should include at minimum the author name\(s\), software title, version number, and unique identifier/locator \([Smith 2016](https://doi.org/10/bw3g)\). If you use someone else’s software and they provided a DOI, then you can easily use that to identify and point to the software; if they did not archive their software, then you should include a URL where the software can be found and the version number or \(e.g.\) commit hash.

Additional, more complicated concepts include automated testing and continuous integration of software, packaging of software in binary formats, and governance and management of multi-person open-source projects \(i.e., codes of conduct, contributing guides\). Some of these topics are described by [Scopatz and Huff \(2015\)](http://lilith.fisica.ufmg.br/~dickman/transfers/comp/textos/Effective%20Computation%20in%20Physics%20(Python).pdf). [Wilson et al. \(2017\)](https://doi.org/10/gbkbwp) also provide a practical guide to best practices for scientific computing that includes advice specifically on research software development.

## <img src="/Images/Icons/laptop.png" width="150" height="150" />
##### Open Source Hardware

The open source principles above extend to hardware. Researchers often use proprietary instrumentation or hardware in their research that is not freely accessible, reusable, or adaptable. Scientific hardware includes everything from sequencing tools and microscopes to specialized testing equipment and particle colliders. Open Science Hardware \(OScH\) community, for example, is leading a push for the open source movement to include scientific tools, hardware, and research infrastructures through their [Global Open Science Hardware Roadmap](http://openhardware.science/global-open-science-hardware-roadmap/).

## <img src="/Images/Icons/gears.png" width="150" height="150" />
#### Skills

* Create a repository on GitHub, and enable the integration with Zenodo. Mint the first release of the software.

* Choose a software license using \(e.g.\) [choosealicense](https://choosealicense.com) or the [Open Source Initiative](https://opensource.org/licenses).

* Create documentation for a software package, including README, comments, and examples.

* Appropriately cite software used for a paper.

## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Questions, obstacles, and common misconceptions

Q: "I can’t share my software—it’s too messy / it doesn’t have good documentation / I didn’t leave good comments!"

A: Developers of research software around the world empathize with this feeling—people rarely feel like their code is "ready" to publicly share or that it is “finished”. However, as [Barnes \(2010\)](https://doi.org/10/cj8t6n) put it, “if your code is good enough to do the job, then it is good enough to release—and releasing it will help your research and your field.” In other words, if you feel comfortable enough with your software to publish a study or report results, then the code is sufficiently developed to share with your colleagues. \(In the other direction, if you don’t feel comfortable sharing the code, then perhaps it requires more development or testing before using in a publication\). Plus, sharing your code allows others to improve and build upon it, leading to even greater impact and innovation \(and citations for you!\).

Q: "What if someone takes the code I have shared and uses it for nefarious purposes, or claims they wrote it?"

A: Selecting an appropriate license for your software will help protect you from any uses of your software by others; for example, the common [MIT License](https://choosealicense.com/licenses/mit/) includes both limitations of liability and states that no warranty is provided. If someone else tries to claim that they wrote the software you made available, then you can point to the timestamps on your repository or archived versions as proof of your prior work.

Q: "If I share my code in an online repository, I will be deluged with requests for user support."

A: Although potential users may ask you for help, either via email or \(e.g.\) issues filed on the online repository, you are under no obligation to provide support if you prefer not to or cannot do so. An appropriate license even provides you with legal protection for this \(e.g., the no-warranty clause of the [MIT License](https://choosealicense.com/licenses/mit/)\).

Common misconception: simply putting code online makes it open-source software. In fact, unless the software is accompanied by a license that grants permission for others to use, copy, modify, and/or distribute, then the developer\(s\) retain exclusive copyright. A open-source license needs to accompany the code to make it open-source software.

## <img src="/Images/Icons/output.png" width="150" height="150" />
### Learning outcomes

1. Be able to share software under the most appropriate license \(i.e., both the tools and the licensing\).

2. Be able to upload, version, and register a piece of code under a persistent identifier.

3. Be able to cite software used for a research article.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Further reading

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
