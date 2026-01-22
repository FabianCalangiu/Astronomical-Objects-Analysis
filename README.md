<h1>Astronomical objects Analysis and Classification</h1>
<h2>Progetto di Laboratorio di Big Data, Data Mining e Data Analytics</h2>
<h2>Autori:</h2>
<ul>
    <li><h3><b>Manuel Menghetti</b> - manuel.menghetti@studio.unibo.it</h3></li>
    <li><h3><b>Fabian Calangiu</b> - fabian.calangiu@studio.unibo.it</h3></li>
</ul>
<h2>Obiettivi</h2>
L'obiettivo del progetto riguarda l'analisi di un dataset astronomico multi-band con il fine di studiare
le proprietà osservabili di stelle, galassie e quasar. Il lavoro si propone quindi di:
<ul>
    <li>esplorare i dati fotometrici</li>
    <li>analizzare la relazione tra i colori e le rispettive proprietà fisiche degli oggetti</li>
    <li>applicare tecniche di classificazione supervisionata e clustering non supervisionato</li>
</ul>
<h2>Sommario</h2>
<ol>
    <li>
        <h3>Pulizia dei dati</h3>
        <p>Nella prima fase è stata effetuata la pulizia del dataset, rimuovendo le misure fotometriche non valide.
        Sono state rinominate le bande fotometriche per migliorarne la leggibilità e selezionati solo gli attributi rilevanti all'analisi, quali magnitudini ugriz e redshift
        Per determinate analisi si è reso necessario filtrare il dataset per classi.
        </p>
    </li>
    <li>
        <h3>Analisi esplorativa dei dati</h3>
        <ul>
            <li>
                <p>Analizzata la distribuzione delle principali classi di oggetti astronomici (stelle, galassie, quasar), evidenziando come il campione fosse sbilanciato, con un maggior numero di galassie, rispetto ad altre classi</p>
            </li>
            <li>
                <p>Sono stati costruiti i diagrammi colore-colore utilizzando le bande fotometriche, che mostrano la presenza di strutture continue e regioni di sovrapposizione tra le diverse classi fisiche.
                Nel caso delle stelle i diagrammi evidenziano la sequenza stellare, con una progressione dal tipo spettrale O/B fino alle stelle M
                </p>
            </li>
            <li>
                <p>Le galassie sono state divise in rosse e blue, dimostrando la predominanza delle rosse, coerente con l'evoluzione delle galassie verso stati passivi.</p>
            </li>
        </ul>
    </li>
    <li>
        <h3>Classificazione predittiva</h3>
        <p>Applicata una classificazione supervisionata per distinguere stelle, galassie e quasar a partire dai colori fotometrici. I risultati mostrano una buona capacità di distinzione, sia con classi sbilanciata che bilanciate.</p>
    </li>
    <li>
        <h3>Clustering</h3>
        <p>Applicato l'elbow method per determinare il numero di cluster. Il clustering non supervisionato nello spazio delle componenti principali dei colori fotometrici evidenzia una struttura continua, caratterizzata da regioni a diversa densità ma prive di confini netti.</p>
    </li>
</ol>