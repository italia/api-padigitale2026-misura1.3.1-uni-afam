# API di PAdigitale2026 - Misura 1.3.1 - Avvisi per Università e AFAM pubblici

Questo repository contiene le specifiche delle API relative alla misura 1.3.1 per l'avviso dedicato a Università pubbliche e AFAM (Alta Formazione Artistica, Musicale e Coreutica) pubblici, nell'ambito di PAdigitale2026. 

La tabella sottostante (Tabella 1) riporta il dettaglio del titolo e descrizione per tutte e nove le API (dalla IFS01 alla IFS09) che dovranno essere erogate dai Soggetti Attuatori in base alla fascia di appartenenza. 


<table>
       <caption>Tabella 1 – Descrizione delle nove API assegnate alle cinque fasce di Università e AFAM</caption>


  <th>Use Case</th>
  <th>API-ID</th>
  <th>e-service-name</th>
  <th>API-Method</th>
  <th>e-service description</th>
  
  <tr>
      <td rowspan="2">Offerta formativa</td>
      <td rowspan="2">IFS01</td>
      <td rowspan="2">ifs-offerta-formativa</td>
      <td>IFS01.1</td>
      <td>Acquisizione della lista dei corsi di studio offerti da un Istituto di
          formazione superiore in un dato anno accademico</td>
  </tr>
  <tr>
      <td>IFS01.2</td>
      <td>Acquisizione del dettaglio di un corso di studio offerto da un Istituto di
          formazione superiore</td>
  </tr>
  <tr>
      <td rowspan="5">Iscrizioni</td>
      <td rowspan="5">IFS02</td>
      <td rowspan="5">ifs-iscrizioni</td>
      <td>IFS02.1</td>
      <td>Acquisizione del dettaglio delle iscrizioni attive negli ultimi tre anni
          accademici di una studentessa o di uno studente</td>
  </tr>
  <tr>
      <td>IFS02.2</td>
      <td>Acquisizione delle prove riguardanti l'iscrizione agli studi di istruzione
          terziaria di una studentessa/studente</td>
  </tr>
  <tr>
      <td>IFS02.3</td>
      <td>Acquisizione delle prove riguardanti la trascrizione (corsi seguiti, voti
          ottenuti, ecc.) degli studi di istruzione terziaria di una studentessa/studente. La trascrizione può
          riferirsi a studi completati o in corso</td>
  </tr>
  <tr>
      <td>IFS02.4</td>
      <td>Acquisizione delle prove riguardanti l'ammissione agli studi di istruzione
          terziaria di una studentessa/studente;</td>

  </tr>
  <tr>
      <td>IFS02.5</td>
      <td>Acquisizione delle prove relative alle attività di apprendimento svolte al di
          fuori dell'istituzione di istruzione terziaria dalla quale una studentessa/studente ha ottenuto il
          proprio diploma</td>
  </tr>
  <tr>
      <td rowspan="4">Titoli</td>
      <td rowspan="4">IFS03</td>
      <td rowspan="4">ifs-titoli</td>
      <td>IFS03.1</td>
      <td>Acquisizione del dettaglio dei titoli accademici conseguiti da una
          studentessa/uno studente</td>
  </tr>
  <tr>
      <td>IFS03.2</td>
      <td>Acquisizione delle prove riguardanti il completamento degli studi di
          istruzione terziaria </td>
  </tr>
  <tr>
      <td>IFS03.3</td>
      <td>Acquisizione delle prove riguardanti il livello di qualifica degli studi di
          istruzione terziaria</td>
  </tr>
  <tr>
      <td>IFS03.4</td>
      <td>Acquisizione delle prove relative allo strumento "Diploma Supplement"</td>
  </tr>
  <tr>
      <td rowspan="4">Rettifica iscrizioni</td>
      <td rowspan="4">IFS04</td>
      <td rowspan="4">ifs-rettifica-iscrizioni</td>
      <td>IFS04.1</td>
      <td>Richiesta di rettifica di un'iscrizione accademica di una studentessa/uno
          studente all'Istituto di formazione superiore</td>
  </tr>
  <tr>
      <td>IFS04.2</td>
      <td>Acquisizione dello stato delle richieste di rettifica delle iscrizioni
          accademiche di una studentessa/uno studente all'Istituto di istruzione superiore</td>
  </tr>
  <tr>
      <td>IFS04.3</td>
      <td>Richiesta di annullamento di una richiesta di rettifica di una iscrizione
          accademica di una studentessa/uno studente all'Istituto di istruzione superiore</td>
  </tr>
  <tr>
      <td>IFS04.4</td>
      <td>Invio di una segnalazione dall'ente fruitore all'ente erogatore per comunicare
          eventuali anomalie sui dati delle iscrizioni accademiche</td>
  </tr>
  <tr>
      <td rowspan="4">Rettifica titoli</td>
      <td rowspan="4">IFS05</td>
      <td rowspan="4">ifs-rettifica-titoli</td>
      <td>IFS05.1</td>
      <td>Richiesta di rettifica di un titolo accademico di una studentessa/uno studente
          all'Istituto di formazione superiore</td>
  </tr>
  <tr>
      <td>IFS05.2</td>
      <td>Acquisizione dello stato delle richieste di rettifica dei titoli accademici di
          una studentessa/uno studente all'Istituto di istruzione superiore</td>
  </tr>
  <tr>
      <td>IFS05.3</td>
      <td>Richiesta di annullamento di una richiesta di rettifica di un titolo
          accademico di una studentessa/uno studente all'Istituto di istruzione superiore</td>
  </tr>
  <tr>
      <td>IFS05.4</td>
      <td>Invio di una segnalazione dall'ente fruitore all'ente erogatore per comunicare
          eventuali anomalie sui dati dei titoli accademici</td>
  </tr>
  <tr>
      <td>Variazioni Iscrizioni</td>
      <td>IFS06</td>
      <td>ifs-variazioni-iscrizioni</td>
      <td>IFS06.1</td>
      <td>Acquisizione delle "impronte (codifica hash)" di tutte le iscrizioni delle
          studentesse/degli studenti negli ultimi tre anni accademici al fine di identificarne le variazioni
          dal punto di vista del fruitore</td>
  </tr>
  <tr>
      <td>Variazioni titoli</td>
      <td>IFS07</td>
      <td>ifs-variazioni-titoli</td>
      <td>IFS07.1</td>
      <td>Acquisizione delle "impronte (codifica hash)" di tutti i titoli accademici al
          fine di identificarne le variazioni dal punto di vista del fruitore</td>
  </tr>
  <tr>
      <td>Iscritti per fasce ISEE</td>
      <td>IFS08</td>
      <td>ifs-iscrizioni-per-fasce-isee</td>
      <td>IFS08.1</td>
      <td>Acquisizione del numero di studentesse e studenti per fasce ISEE in un anno
          accademico</td>
  </tr>
  <tr>       
      <td>Iscritti a un corso per anno</td>
      <td>IFS09</td>
      <td>ifs-iscrizioni-per-corso</td>
      <td>IFS09.1</td>
      <td>Acquisizione del numero di studentesse e studenti iscritti a un corso di studi
          per anno accademico</td>
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
