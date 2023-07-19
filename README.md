# API di PAdigitale2026 - Misura 1.3.1 - Avvisi per Università e AFAM pubblici

Questo repository contiene le specifiche delle API relative alla misura 1.3.1 per l'avviso dedicato a Università pubbliche e AFAM (Alta Formazione Artistica, Musicale e Coreutica) pubblici, nell'ambito di PAdigitale2026. 

La tabella sottostante (Tabella 1) riporta il dettaglio del titolo e descrizione per tutte e nove le API (dalla IFS01 alla IFS09) che dovranno essere erogate dai Soggetti Attuatori in base alla fascia di appartenenza. 

<table>
       <caption>Tabella 1 – Descrizione delle nove API assegnate alle cinque fasce di Università e AFAM</caption>

  <th>API ID</th><th>Titolo</th><th>Descrizione</th>
  <tr>
    <td>IFS01</td><td>Offerta formativa</td><td>Acquisizione dei dati dei corsi attivi ed offerti da un Istituto in un dato anno accademico</td>
  </tr>
  <tr>
    <td rowspan=3>IFS02</td>
    <td rowspan=3>Iscrizioni</td>
    <td>Acquisisce i dati di dettaglio delle iscrizioni di una studentessa o di uno studente in formato nazionale.</td>
    <tr>
    <td>Acquisisce i dati di dettaglio delle iscrizioni di una studentessa o di uno studente in formato transfrontaliero. </td>
    </tr>
  <tr>
    <td>Acquisisce gli esami sostenuti con voto (transcript) di una studentessa o di uno studente in formato transfrontaliero. </td>
  </tr>
  </tr>
    <tr>
    <td rowspan=3>IFS03</td>
    <td rowspan=3>Titoli</td>
    <td>Acquisisce i titoli conseguiti nell'istituto da una studentessa o uno studente in formato nazionale.</td>
    <tr>
    <td>Acquisisce il diploma supplement semplificato (senza voti degli esami) in formato transfrontaliero.</td>
    </tr>
  <tr>
    <td>Acquisisce il diploma supplement in formato transfrontaliero.</td>
  </tr>
  </tr>
  <tr>
    <td rowspan=2>IFS04</td>
    <td rowspan=2>Rettifica iscrizioni</td>
    <td>Richiede la rettifica dei dati di un’iscrizione o una iscrizione mancante o in eccesso per una studentessa o uno studente.  
  </tr>
  <tr>
    <td>Monitora lo stato della richiesta di rettifica delle iscrizioni</td>
  </tr>
</td>
  </tr>
  <tr>
    <td rowspan=2>IFS05</td>
    <td rowspan=2>Rettifica titoli</td>
    <td>Richiede la rettifica dei dati di un titolo conseguito o mancante di una studentessa o uno studente.  
  </tr>
  <tr>
  <td>Monitora lo stato della richiesta di rettifica dei titoli</td>
  </tr>
<tr>
  <td>IFS06</td>
  <td>Elenco Variazioni Iscrizioni</td>
  <td>Acquisisce lista delle studentesse e degli studenti che hanno subito un cambio di stato alla relativa iscrizione tra un istante t0 e uno t1 compresi (ad es. t0 = 1 gennaio 2019 e t1 = 31 dicembre 2019 per richiedere i dati relativi all'anno solare 2019)</td>
</tr> 
<tr>
  <td>IFS07</td>
  <td>Elenco variazione titoli</td>
  <td>Acquisisce la lista delle studentesse e degli studenti che hanno subito un cambio di stato ai relativi titoli conseguiti tra un istante t0 e uno t1 compresi (ad es. t0 = 1 gennaio 2019 e t1 = 31 dicembre 2019 per richiedere i dati relativi all'anno solare 2019)</td>
</tr>
<tr>
  <td>IFS08</td>
  <td>Iscritti per fasce ISEE</td>
  <td>Acquisisce il numero di studentesse e studenti per fasce ISEE in un anno accademico<td>
</tr>
<tr>
  <td>IFS09</td>
  <td>Iscritti a un corso per anno</td>
  <td>Acquisisce il numero di studentesse e studenti iscritti a uno specifico corso per anno accademico</td>
</tr>
</table>


Come indicato nella tabella sottostante (Tabella 2), gli Atenei e AFAM pubblici che possono aderire all’avviso sono divisi in fasce basate sul numero di iscritti, a cui corrisponde un numero preciso di API da erogare, dettagliate nella tabella 1. 

 
| Fascia | Iscritti | API (API ID) |
|--------|----------|--------------|
|1       |  <=1.000 | 7 (IFS01 – IFS07) |
|2       | 1.000 < iscritti <= 10.000 |8 (IFS01 – IFS08) |
|3       | 10.000 < iscritti <= 20.000 |8 (IFS01 – IFS08) |
|4       | 20.000 < iscritti <= 40.000 |9 (IFS01 – IFS09) |
|5       |> 40.000 | 9 (IFS01 – IFS09) |

Tabella 2 – Fasce di Università in base al numero di studentesse e studenti iscritti ed API da erogare per ogni fascia. 


Per maggiori informazioni:
* [Interoperabilità e PDND su Developers Italia](https://developers.italia.it/it/interoperabilita/)
* [Avvisi di PAdigitale 2026](https://areariservata.padigitale2026.gov.it/Pa_digitale2026_avvisi)
