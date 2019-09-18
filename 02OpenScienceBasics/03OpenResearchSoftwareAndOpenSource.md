<img src="/Images/Icons/open_source_software.png" width="150" height="150" /> <img src="/Images/Icons/publish.png" width="150" height="150" />
## 3. Software aperto per la ricerca e Open Source

### Di che cosa si tratta?

Il concetto di “software di ricerca aperto”, o “software di ricerca open source” (a codice sorgente aperto), si riferisce all’uso e sviluppo di software di ricerca (per analisi, simulazione, visualizzazione, etc.) il  cui codice sorgente è interamente disponibile; in aggiunta a questo, però, secondo la [definizione di “Open Source”](https://opensource.org/osd), il software “open source” deve essere distribuito in formato sorgente e/o compilato \(nel secondo caso, con possibilità di accesso al codice sorgente\) e deve essere reso disponibile con una licenza che ne consenta il libero uso, la modifica, e la ri-distribuzione .

### Motivazione

La ricerca moderna si basa sul software; per portare avanti una certa ricerca -o riprodurne i risultati- è necessario poter accedere al codice sorgente del software usato \[Barnes, 2010](https://doi.org/10/cj8t6n); [Morin et al., 2012](https://doi.org/10/m5t); [Ince et al., 2012](https://doi.org/10/hqg); [Prins et al. 2015](https://doi.org/10/f3mn4p); [Lowndes et al., 2018](https://doi.org/10/gc4jb3)\). Come dicono Buckheit e Donoho, parafrasando Jon Claerbout, "Un articolo su un risultato computazionale è pubblicità, non scienza. La vera scienza sta nell’ambiente software completo, codice e dati, che ha prodotto quel risultato" \([Buckheit & Donoho, 1995](https://doi.org/10.1007/978-1-4612-2544-7_5)\). Tra l’altro, l’accesso libero al codice sorgente del software scientifico aumenta l’impatto della ricerca prodotta \[(Vandewalle, 2012](https://doi.org/10/gc5sjp)\).

La condivisione del software utilizzato per la ricerca \(sia per studi di natura prettamente computazionale che per studi che contengono un’analisi o interpretazione di dati basata su software\) è una condizione necessaria, ma non sufficiente, per la riproducibilità. Questo perché quando si descrive un software nel linguaggio naturale -ad esempio- in un articolo, un certo grado di imprecisione è inevitabile \[(Ince et al., 2012] (https://doi.org/10/hqg)\). Inoltre, molti programmi software (forse la maggior parte) possono contenere errori nascosti \[(Soergel, 2015] (https://doi.org/10/gc5sjg)\), quindi anche una "perfetta" descrizione per iscritto del software non sarebbe in grado di spiegare interamente i risultati.

Oltre all’aspetto della riproducibilità, la condivisione aperta del software permette di riconoscere il lavoro svolto dagli sviluppatori, sia attraverso la citazione diretta \([Smith et al., 2016] (https://doi.org/10/bw3g)\) che attraverso meta-articoli di software pubblicati, ad esempio, nel [Journal of Open Research Software] (http://openresearchsoftware.metajnl.com) o nel [Journal of Open Source Software](http://joss.theoj.org) \([Smith et al., 2018] (https://doi.org/10/gc5sjf)\). Esite un [elenco] (https://www.software.ac.uk/which-journals-should-i-publish-my-software) abbastanza nutrito di riviste di settore che pubblicano articoli di software, curato da Neil Chue Hong.

## <img src="/Images/Icons/finish.png" width="150" height="150" />
### Finalità didattiche 

1. Apprendere le caratteristiche del software “open source”; approfondire gli aspetti etici, legali, economici e quelli relativi all’impatto sulla ricerca, sia a favore sia contro il software  “open source”, nonché comprendere i requisiti di qualità del codice aperto.

2. Imparare ad usare i programmi “open source” esistenti e a farne un’attribuzione appropriata \(citazione\).

3. Imparare ad utilizzare i più comuni strumenti e servizi di condivisione aperta dei codici di ricerca.

4. Essere in grado di scegliere la licenza più appropriata per il proprio software e comprendere la differenza tra licenze permissive e non permissive.

### Componenti chiave

## <img src="/Images/Icons/brain.png" width="150" height="150" />
#### Conoscenza

Ci sono diverse piattaforme attraverso le quali si può collaborare a un software, a una ricerca, etc., e condividere i risultati. Per valutare il livello di apertura di un software di ricerca esistente si può usare questo test:

* Il software è disponibile per essere scaricato ed installato?

* Il software può essere facilmente installato su diverse piattaforme?

* L’uso del software è soggetto a restrizioni?

* Il codice sorgente è disponibile e consultabile?

* Esite una cronologia delle versioni a disposizione del pubblico?

* I requisiti (hardware e software) di sistema sono descritti adeguatamente? Questi requisiti \(o “dipendenze”\) si possono ottenere e utilizzare con uno sforzo ragionevolmente limitato?

Questi requisiti corrispondono, con qualche modifica, alla definizione di [Open Source](https://opensource.org/osd).

[GitHub] (www.github.com) è uno strumento molto usato per il controllo di versione, cioè per la gestione e il monitoraggio globale delle modifiche di un certo elemento di software. Servizi come [GitHub] (www.github.com), [GitLab] (https://about.gitlab.com/), [Bitbucket] (https://bitbucket.org/) e altri forniscono un'interfaccia allo strumento oltre a servizi di archiviazione remota che possono essere utilizzati per mantenere, condividere e collaborare su software di ricerca. GitHub è abbastanza diffuso e, sebbene presenti una certa curva di apprendimento iniziale, si è rivelato uno strumento prezioso per organizzare un flusso di lavoro di ricerca aperto e riproducibile.

Avere il software di ricerca su GitHub è solo il primo passo; è altrettanto importante associare ad esso un identificatore pubblicato e persistente, come un DOI. Ci sono diversi modi per attribuire un DOI ad un archivio GitHub; il più semplice è utilizzare [Zenodo] (www.https://zenodo.org/) \(un archivio generico aperto e gratuito creato da [OpenAIRE] (https://www.openaire.eu/) e [CERN] (https://home.cern/)\) anche se esistono altri archivi per depositare un software e ottenere un DOI, come [Figshare] (https://figshare.com/). [Zenodo si integra con GitHub] (https://guides.github.com/activities/citable-code/) per archiviare il software e creare un DOI ogni volta che viene fatta una release ufficiale su GitHub

Il software condiviso pubblicamente non è realmente “open source” se non è accompagnato da un’appropriata licenza; di default, infatti, il software \(come qualsiasi altra opera creativa\) è di proprietà esclusiva di chi l’ha creato, il che implica che nessuno può usare, copiare, distribuire o modificare l’opera di un altro \([choosealicense.com](https://choosealicense.com/no-permission/)\). \(Se si vuole condividere il proprio codice senza alcuna restrizione è anche possibile [renderlo di dominio pubblico]) (https://choosealicense.com/licenses/#unlicense). Perché sia  “open source” si deve  scegliere una licenza adeguata al proprio software, in base a ciò che si decide di permettere \(o di proibire\) agli altri di fare con quel codice; un’utile risorsa per imparare a distinguere tra le diverse licenze è il sito [choosealicense.org](https://choosealicense.com) anche se non riporta tutte le licenze “open source” disponibili o più diffuse. Una volta selezionata una licenza, si deve inserirne il testo nell’archivio del software – aggiungendo il nome dell'autore \(o degli autori\) e l'anno - come file di puro testo LICENSE.

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
