# Dal reclamo alla bozza — Laboratorio IA per la Pubblica Amministrazione

**Web app didattica autonoma · 2 casi · uso individuale da remoto · durata consigliata: 20–30 minuti per caso**

## 1. Che cos'è

Una simulazione guidata che accompagna il partecipante **dalla lettura di un'istanza esterna alla predisposizione di una bozza di riscontro interlocutorio**, attraverso ostacoli e controlli progressivi. È progettata per corsi sull'uso responsabile dell'intelligenza artificiale nella Pubblica Amministrazione italiana e può essere riutilizzata con enti diversi.

I due fascicoli sono **interamente fittizi**. I documenti mostrati come “originali” rappresentano **le fonti di riferimento del caso didattico**, non atti amministrativi realmente emanati.

## 2. Come si avvia

1. Scarica `Laboratorio_IA_PA_Due_Istanze.html` oppure estrai lo ZIP della web app.
2. Apri il file HTML con un browser aggiornato: **Chrome, Edge, Firefox o Safari**.
3. Scegli una delle due istanze e procedi seguendo le istruzioni sullo schermo.

**Non servono** installazione, account, server, chiavi API o connessione Internet per la modalità di simulazione. HTML, CSS e JavaScript sono contenuti nello stesso file. Su alcuni dispositivi aziendali la policy del browser può limitare la copia negli appunti o i download: in quel caso utilizzare gli strumenti consentiti dall'ente.

## 3. I due casi disponibili

| Caso | Situazione | Punto critico |
| --- | --- | --- |
| **A — Accesso allo sportello** | Un cittadino reclama per difficoltà di prenotazione e accesso al servizio. | Non confondere il reclamo con un accertamento; non promettere appuntamenti, interventi o tempi non confermati. |
| **B — Contributo per libri di testo** | Un genitore contesta l'esclusione della figlia da un contributo per studenti della scuola secondaria di primo grado. | Distinguere una bozza salvata da una domanda effettivamente inviata; non dichiarare automaticamente ammissione, riesame accolto o guasti tecnici. |

È sufficiente svolgere **un caso** nella stessa esercitazione; il secondo può servire per un altro corso, una seconda prova o il confronto tra scenari.

## 4. Il percorso a ostacoli

L'applicazione guida attraverso questi passaggi, senza consentire di saltare quelli obbligatori:

1. **Presa in carico:** lettura dell'istanza e delle fonti; distinzione tra affermazioni del richiedente e fatti accertati.
2. **Minimizzazione:** identificazione dei dati da rimuovere, generalizzare o sostituire con segnaposto.
3. **Uso dello strumento:** verifica delle condizioni minime di utilizzo; in modalità esterna è richiesta la conferma dello strumento autorizzato.
4. **Costruzione del prompt:** obiettivo, ruolo di supporto, destinatario, fonti ammesse, vincoli e formato della bozza.
5. **Produzione della bozza:** simulazione offline oppure inserimento manuale di un output generato con un'IA esterna autorizzata.
6. **Controllo delle affermazioni:** confronto delle affermazioni proposte con le fonti del fascicolo.
7. **Revisione umana:** redazione del riscontro interlocutorio, separazione delle verifiche istruttorie aperte e conferma delle condizioni finali.
8. **Esito:** stato didattico **“BOZZA PER LA FIRMA”** ed esportazione del lavoro.

Se una scelta è errata o manca un requisito, il percorso **si blocca e presenta indicazioni di correzione**. Le verifiche automatiche sono controlli didattici predefiniti: non certificano l'esattezza giuridica di testi liberi.

## 5. Modalità di utilizzo dell'IA

### Simulazione offline — consigliata per la formazione

L'app mostra una **bozza già predisposta**, volutamente contenente errori e chiaramente identificata come simulata. **Non chiama un modello IA** e non genera autonomamente testi tramite servizi esterni.

### IA esterna autorizzata — facoltativa

L'app compone un prompt basato sui **soli dati e sulle fonti fittizie del fascicolo**. Il partecipante può:

1. Copiare il prompt.
2. Incollarlo manualmente in uno strumento di IA **espressamente autorizzato dall'ente**.
3. Riportare manualmente nell'app la bozza ottenuta.
4. Continuare le attività di verifica e revisione.

L'app **non possiede un'integrazione API** e non trasmette automaticamente il prompt a servizi di IA. **Non utilizzare casi reali né inserire dati personali o documenti riservati.**

## 6. Come salvare i risultati

Al termine, dalla schermata finale sono disponibili:

- **Stampa / Salva PDF**: apre la funzione di stampa del browser, da cui è possibile scegliere “Salva come PDF”.
- **Scarica il fascicolo TXT**: esporta prompt, bozza, classificazioni di verifica, testo revisionato e note interne.
- **Prova l'altro caso**: ricomincia il laboratorio, perdendo i dati della prova corrente non esportati.

**Attenzione:** non è previsto salvataggio automatico. **Aggiornare o chiudere la pagina fa perdere lo stato corrente**, se non è già stato esportato. I file prodotti rimangono sul dispositivo dell'utente secondo le impostazioni del browser.

## 7. Proposta di conduzione in aula virtuale

| Minuti | Attività |
| ---: | --- |
| 0–3 | Scegliere il caso, leggere l'istanza e aprire le fonti. |
| 3–7 | Completare presa in carico e minimizzazione. |
| 7–10 | Verificare le condizioni d'uso e costruire il prompt. |
| 10–14 | Ottenere la bozza simulata o incollarne una ottenuta con IA autorizzata. |
| 14–19 | Controllare le affermazioni rispetto alle fonti. |
| 19–25 | Preparare risposta interlocutoria e note interne, separatamente. |
| 25–30 | Esportare e discutere in plenaria gli errori più significativi. |

**Modalità:** un partecipante per postazione; nessun lavoro di gruppo o breakout room. Il formatore può chiedere in chat quale controllo ha creato più difficoltà, senza raccogliere dati personali. Se alcuni partecipanti finiscono prima, possono provare il secondo caso.

Nel pacchetto ZIP sono presenti anche `Guida_del_formatore.txt` (chiavi di correzione e conduzione) e `LEGGIMI.txt` (istruzioni sintetiche).

## 8. Limiti e avvertenze

- **Uso esclusivamente didattico.** Non è un gestionale di protocollo, di pratiche, di contributi o di firma elettronica.
- **“Bozza per la firma” non significa approvazione.** Il completamento certifica solo il superamento degli ostacoli formativi; non firma, protocolla, trasmette o valida un provvedimento.
- Il documento finale è una **bozza di riscontro interlocutorio**. L'esame del merito dell'istanza e ogni decisione amministrativa spettano agli uffici e ai soggetti competenti, secondo procedure e norme applicabili.
- Le fonti didattiche **non dimostrano la disciplina vigente di un ente reale**. Non riutilizzare avvisi, scadenze o condizioni dell'esercizio come riferimenti normativi autentici.
- Le condizioni di protezione dei dati dipendono dagli strumenti, dalla configurazione e dalle istruzioni dell'ente. Il completamento del quiz **non equivale a un'autorizzazione o a una verifica GDPR**.

## 9. Riutilizzo e personalizzazione

Per altri committenti il kit **non richiede modifiche**: i casi sono generici. Se si vogliono sostituire istanze o documenti, occorre intervenire nel file HTML e aggiornare **anche le risposte attese, le regole di blocco e la guida del formatore**; sostituire soltanto il testo a schermo renderebbe incoerente la correzione automatica.

## 10. File del pacchetto

```text
Laboratorio_IA_PA_Istanze.html  # web app autonoma inclusa nello ZIP
README.MD                       # questo documento
LEGGIMI.txt                     # istruzioni rapide
Guida_del_formatore.txt         # indicazioni e soluzioni riservate al formatore
```

La copia HTML distribuita singolarmente può essere denominata `Laboratorio_IA_PA_Due_Istanze.html`: il funzionamento è lo stesso.

---

**Obiettivo finale:** apprendere a usare l'IA come supporto alla redazione, proteggere i dati prima dell'invio, riscontrare le affermazioni sulle fonti e mantenere **verifica e decisione in capo alle persone competenti**.
