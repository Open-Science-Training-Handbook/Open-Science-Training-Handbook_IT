<img src="/Images/Icons/open_source_software.png" width="150" height="150" /> <img src="/Images/Icons/publish.png" width="150" height="150" />
## 3. Software aperto per la ricerca e Open Source

### Di che cosa si tratta?

Il concetto di “software di ricerca aperto”, o “software di ricerca open source” (a codice sorgente aperto), si riferisce all’uso e sviluppo di software di ricerca (per analisi, simulazione, visualizzazione, etc.) il  cui codice sorgente è interamente disponibile; in aggiunta a questo, però, secondo la [definizione di “Open Source”](https://opensource.org/osd), il software “open source” deve essere distribuito in formato sorgente e/o compilato \(nel secondo caso, con possibilità di accesso al codice sorgente\) e deve essere reso disponibile con una licenza che ne consenta il libero uso, la modifica, e la ri-distribuzione .

### Motivazione

La ricerca moderna si basa sul software; per portare avanti una certa ricerca -o riprodurne i risultati- è necessario poter accedere al codice sorgente del software usato \([Barnes, 2010](https://doi.org/10/cj8t6n); [Morin et al., 2012](https://doi.org/10/m5t); [Ince et al., 2012](https://doi.org/10/hqg); [Prins et al. 2015](https://doi.org/10/f3mn4p); [Lowndes et al., 2018](https://doi.org/10/gc4jb3)\). Come dicono Buckheit e Donoho, parafrasando Jon Claerbout, "Un articolo su un risultato computazionale è pubblicità, non scienza. La vera scienza sta nell’ambiente software completo, codice e dati, che ha prodotto quel risultato" \([Buckheit & Donoho, 1995](https://doi.org/10.1007/978-1-4612-2544-7_5)\). Tra l’altro, l’accesso libero al codice sorgente del software scientifico aumenta l’impatto della ricerca prodotta \([Vandewalle, 2012](https://doi.org/10/gc5sjp)\).

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

Anche se condividere il software, in qualunque forma, è comunque meglio che non condividerlo, esso avrà un impatto maggiore e sarà più facilmente utilizzabile da altri – e in futuro anche da voi stessi! - se  corredato di una documentazione. Questa può essere costituita da commenti inseriti nel codice che spiegano il **perché** si è deciso di fare una certa cosa \(non tanto **quello** che si è fatto, che dovrebbe essere già di per sè evidente\), un file README informativo che descrive ciò che il software è in grado di fare e che fornisce alcune informazioni utili (ad esempio, come installarlo, come citarlo, come eseguirlo, le dipendenze importanti), tutorial/esempi, e/o documentazione per le API \(quest’ultima può essere generata automaticamente da commenti opportunamente formattati nel codice\).

La mancanza o l’inaccessibilità di alcune dipendenze, o la carenza di documentazione sull'ambiente di calcolo, spesso costituiscono ostacolo al ri-utilizzo e alla riproducibilità. Un modo per rimuovere questi ostacoli è quello di distribuire, insieme al codice anche l’ambiente di calcolo, utilizzando la tecnologia dei contenitori (oggetto contenitore). I contenitori confezionano il codice insieme alle sue dipendenze e al suo ambiente computazionale, cosicché è più facile per un altro ripetere la vostra analisi. Esempi di implementazione dei contenitori nella ricerca includono [Rocker] (https://arxiv.org/abs/1710.03675), [Binder] (https://mybinder.readthedocs.io/en/latest/) e [Code Ocean] (https://codeocean.com/).

Quando si utilizza un software - sia che ne siate l’autore, o che sia stato prodotto da altri- citarlo appropriatamente è importante per la riproducibilità dei risultati ottenuti (per un approfondimento al riguardo si rimanda alla [sezione 4] (https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md); brevemente, la versione usata può cambiare i risultati o l'interpretazione) e anche per dare il giusto riconoscimento agli sviluppatori \([Niemeyer 2016] (doi.org/10/gc5sjd), [Smith 2016] (https://doi.org/10/bw3g)\). Se e quando citare il software è una decisione che spetta al ricercatore, ma raccomandiamo di farlo in tutti i casi in cui il software è parte integrante del lavoro -risultati, interpretazioni o conclusioni. Il modo migliore per rendere il codice facilmente citabile è utilizzare l'integrazione GitHub-Zenodo descritta sopra e fornire il DOI in una posizione bene in vista come ad esempio il file README, possibilmente insieme al formato raccomandato per la citazione. Quando si cita un software, si dovrebbe includere almeno il nome dell' autore (o degli autori), il titolo del software, il numero di versione e un identificatore/localizzatore unico \([Smith 2016] (https://doi.org/10/bw3g)\). Se si usa un software di altri che possiede un DOI, si può facilmente usare quest’ultimo per identificare e localizzare il software; se il software non è presente in un archivio, allora si dovrebbe indicare l’URL a cui il software può essere trovato ed il numero di versione o (per esempio) il codice hash dell’ultima modifica \(commit\).

Vi sono ulteriori concetti, un po’ più complicati, tra cui: test automatici e integrazione continua del software; il confezionamento del software in formato binario; e la governance e la gestione di progetti “open source” collettivi \(ad esempio, codici di condotta, guide contributive\). Alcuni di questi argomenti sono descritti da [Scopatz e Huff \(2015\)] (http://lilith.fisica.ufmg.br/~dickman/transfers/comp/textos/Effective%20Computation%20in%20Physics%20(Python).pdf). [Wilson et al.\ (2017\)] (https://doi.org/10/gbkbwp) forniscono anche una guida operativa alle buone pratiche per il calcolo scientifico che contiene consigli specifici sullo sviluppo di software di ricerca.

## <img src="/Images/Icons/laptop.png" width="150" height="150" />
##### Hardware “open source”

I principi “open source” descritti sopra si applicano anche all'hardware. I ricercatori spesso usano per la loro ricerca strumentazioni o hardware proprietario che non sono liberamente accessibili, riutilizzabili o adattabili. L'hardware scientifico comprende tutto, dagli strumenti per il sequenziamento, ai microscopi, alle apparecchiature di analisi specializzate, agli acceleratori di particelle. La comunità dell'Open Science Hardware \(OScH\), ad esempio, sta spingendo il movimento open source a occuparsi anche di strumenti scientifici, hardware e infrastrutture di ricerca attraverso la loro [Global Open Science Hardware Roadmap] (http://openhardware.science/global-open-science-hardware-roadmap/).

## <img src="/Images/Icons/gears.png" width="150" height="150" />
#### Competenze

* Creare un archivio GitHub e attivare l’integrazione con Zenodo. Coniare la prima versione del software.

*	Selezionare una licenza di software utilizzando ad esempio [choosealicense] (https://choosealicense.com) oppure [Open Source Initiative] (https://opensource.org/licenses).

* Creare la documentazione per un pacchetto software, inclusi README, commenti ed esempi.

* Citare correttamente il software utilizzato per un articolo

## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Domande, impedimenti ed equivoci comuni

Domanda: "Non me la sento di condividere il mio software - è troppo disordinato / non ha una buona documentazione / non ho inserito abbastanza commenti!”

Risposta: In tutto il mondo gli sviluppatori di software di ricerca hanno questa stessa sensazione - le persone raramente pensano che il loro codice sia "pronto" per essere condiviso pubblicamente o che sia "finito". Tuttavia, come dice [Barnes \(2010\)] (https://doi.org/10/cj8t6n), "se il tuo codice è abbastanza buono per fare il lavoro, allora è abbastanza buono per essere pubblicato - e pubblicarlo aiuterà la tua ricerca e il tuo settore”. In altre parole, se ci si sente abbastanza sicuri del proprio software per pubblicare uno studio o riportare i risultati, allora il codice è sufficientemente sviluppato per essere condiviso con i colleghi \(viceversa, se non si è sicuri di voler condividere il codice, allora forse quest’ultimo necessita di ulteriori sviluppi o test prima di venire utilizzato in una pubblicazione\). Inoltre, condividere un codice permette ad altri di migliorarlo e svilupparlo, producendo un impatto maggiore e una maggiore innovazione \(e anche più citazioni per te!\).

Domanda: "E se qualcuno si appropria del codice che ho condiviso e lo usa per scopi illeciti, o sostiene di averlo scritto?

Risposta: Scegliere una licenza appropriata per il proprio software serve a salvaguardarvi dall’uso improprio che altri possono farne; per esempio, la [licenza MIT] (https://choosealicense.com/licenses/mit/)  , abbastanza diffusa, prevede alcune limitazioni di responsabilità e precisa che non viene fornita alcuna garanzia. D’altra parte, se qualcuno prova a sostenere di essere l’autore di un vostro software diffuso al pubblico, voi potete citare la data e l'ora registrate nella vostra repository o sulle versioni archiviate a riprova del fatto che la vostra opera precede la rivendicazione.

Domanda: Se condivido il mio codice in un archivio online, sarò sommerso da richieste di supporto all’utente"

Risposta: Anche se i potenziali utenti possono chiedervi aiuto, sia via e-mail oppure \(ad esempio\) attraverso problemi segnalati nell’archivio online, voi non avete nessun obbligo di fornire assistenza se non volete o non potete farlo. Una licenza appropriata dà anche una protezione legale in questo senso \(ad esempio, la clausola di non garanzia della licenza MIT\) (https://choosealicense.com/licenses/mit/)\).

È un equivoco abbastanza comune pensare che il solo fatto di mettere un codice online lo renda “open source”. In realtà, a meno che il software non sia accompagnato da una licenza che conceda ad altri il permesso di usare, copiare, modificare e/o distribuire, lo sviluppatore (o gli sviluppatori) mantengono il copyright esclusivo. Per rendere un software “open source”, questo deve essere accompagnato da una licenza ”open source”.  

## <img src="/Images/Icons/output.png" width="150" height="150" />
### Obiettivi di apprendimento 

1. Essere in grado di condividere il software con la licenza più appropriata \(cioè, sapere scegliere sia gli strumenti che la licenza\).

2. Essere in grado di caricare, modificare e registrare un elemento di codice con un identificativo permanente.

3. Essere in grado di citare il software utilizzato per un articolo di ricerca

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Letture integrative

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
