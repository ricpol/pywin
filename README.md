Python e Windows: guida per principianti
========================================

Questa è una guida per chi vuole iniziare a programmare (e a programmare in Python!) su Windows. 

Perché questa guida?
--------------------

Perché è difficile avere informazioni di base, chiare, e _in Italiano_. Questa guida nasce dalle ripetute domande dei principianti sul forum di [Python-it.org](http://www.python-it.org/forum). All'inizio doveva essere una FAQ, poi ho pensato che un piccolo manuale sarebbe stato più utile. 
L'idea è: se siete principianti e volete usare Python su Windows, prima di fare domande sul forum assicuratevi di aver letto e digerito queste pagine.

Perché Windows?
---------------

Windows può non essere l'ambiente di lavoro più esaltante per (un certo tipo di) programmatori. Ma è usato, e usato soprattutto dalle persone a cui questa guida si rivolge. C'è chi si avvicina alla programmazione per curiosità o per necessità, e non ha familiarità con Linux, la shell, compilare i sorgenti ("compilare i sorgenti?!?"). 
Rispondere a queste persone "scordati Windows, installa Linux e imparalo" non è carino, e forse neanche efficace. 

Perché Python?
--------------

Python potrà non essere il linguaggio di programmazione ideale per fare... tutto (e d'altra parte, quale altro linguaggio lo è?). Ma è relativamente facile da apprendere, molto flessibile, molto utilizzato e con un enorme parco di librerie. Molti principianti sono naturalmente attratti da Python per imparare a programmare. E molti guru della programmazione usano Python - ma questa guida non è per loro!

Per chi non è adatta questa guida?
----------------------------------

- Per i programmatori esperti. Se avete molta esperienza con la programmazione su Linux (anche non in Python), ma non sapete dove mettere le mani su Windows, questa guida _non_ fa comunque per voi. Probabilmente potete arrivare comunque dove volete in mezz'ora di intenso rapporto con google. 

- Per chi ha già una buona esperienza di Windows. Se sapete usare una shell in Windows, e magari avete già anche programmato un po', allora forse questa guida potrebbe esservi utile ugualmente, per la parte Python. Ma probabilmente fate prima a leggervi un buon manuale, a questo punto. 

- Per chi intende _restare_ un principiante. Questa guida non è una collezione di ricette da seguire passo-passo. Mostriamo dei concetti, e scendiamo anche nel dettaglio: ma si parte sempre dal presupposto che dovete ragionare da soli, magari andare un po' a tentativi, ma insomma cavarvela in qualche modo senza nessuno che vi tiene la mano.

Che cosa insegna questa guida?
------------------------------

Questa guida cerca di andare oltre la ricetta "come installare Python su Windows". 
L'idea è che, per programmare, occorre avere un'idea di come funziona il sistema operativo, e come organizzare la propria attività di programmatore. 
Quindi parleremo di molte cose, prima di arrivare a installare Python: la shell, la path, gli strumenti che conviene avere sotto mano...
E parleremo di molte cose anche dopo aver installato Python: come si eseguono gli script, come si installano i pacchetti, come si lavora in un virtual environment, come si usa un sistema di controllo di versione...
La speranza è di portare il principiante a "fare la cosa giusta" su Windows, ambientando i suoi primi lavori in Python all'interno di un contesto di buone pratiche di programmazione, che a lungo andare ripagheranno. 

Che cosa non insegna questa guida?
----------------------------------

- Questa guida non è un manuale di programmazione in Python. Diamo per scontato che chi legge non ha mai visto Python prima d'ora, e pertanto spieghiamo i concetti fondamentali, ma solo quanto basta a capire gli esempi basilari che presentiamo. 

- Questa guida non è un manuale di Windows, né di qualunque altro software che useremo. Parleremo della shell e di git, ma in maniera neanche lontanamente sufficiente per farvi diventare degli esperti in materia. Diventare esperti è ciò che inizierete a fare dopo aver finito questa guida. 

- Questa guida non è una raccolta di "trucchi" per Windows, o per Python su Windows. Parleremo di buone pratiche e di metodi facili per razionalizzare un po' il lavoro, questo sì. Ma i trucchi per sgamati si imparano più tardi, quando si diventa, appunto, più sgamati. 

- Questa guida non parla di tecniche "avanzate", mai. Parliamo solo di quello che serve realisticamente a un principiante. Non descriviamo come compilare un pacchetto su Windows, perché si trovano già in rete tutti i pacchetti pre-compilati di cui un principiante può aver bisogno (ovvero: se avete bisogno di un pacchetto e nessuno lo ha compilato prima, vuol dire che non siete più un principiante, complimenti). Invece, parleremo di come installare da una repository git, perché potrebbe capitare a chiunque, di questi tempi. 

E comunque, chi sono io?
------------------------

Un principiante dotato di una certa pazienza, dovessi dire. La pazienza e la curiosità di fermarmi a capire finché non ho capito. 
Programmo in Python da un certo numero di anni (la 2.3 se ben ricordo), ma sempre piuttosto per conto mio. Uso Windows per necessità, e (di recente, ma solo di recente) con una punta di soddisfazione ogni tanto. 
Frequento volentieri [Python-it.org](http://www.python-it.org/forum) dove in particolare cerco di dare una mano a chi sta litigando con wxPython. Questo ha generato i miei [Appunti wxPython](https://appunti-wxpython.readthedocs.org/en/latest/), che oggi sono la risorsa più completa in Italiano sull'argomento (credo!), e crescono lentamente nel tempo. 

Questa guida sarebbe il mio secondo tentativo.
