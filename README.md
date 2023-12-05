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


## Linee Guida e-service

In questo paragrafo verrano descritti XXXXXX

1. [IFS01 Offerta Formativa](#ifs01-offerta-formativa)
2. [IFS02 Iscrizioni](#ifs02-iscrizioni)
3. [IFS03 Titoli](#ifs03-titoli)
4. [IFS04 Rettifica iscrizioni](#ifs04-rettifica-iscrizioni)
5. [IFS05 Rettifica titoli](#ifs05-ettifica-titoli)
6. [IFS06 Elenco Variazioni Iscrizioni](#ifs06-elenco-variazioni-iscrizioni)
7. [IFS07 Elenco variazione titoli](#ifs07-elenco-variazione-titoli)
8. [IFS08 Iscritti per fasce ISEE](#ifs03-iscritti-per-fasce-isee)
9. [IFS09 Iscritti a un corso per anno](#ifs09-iscritti-a-un-corso-per-anno)


<hr>

### IFS01 Offerta Formativa <img src="doc/05_gallery/rocket.svg" width="18" />
Vuole acquisire i dati dei corsi attivi ed offerti da un Istituto in un dato anno accademico

<img src="doc/05_gallery/swagger.svg" width="18
" /> Definizione [OpenApi.yaml](src/IFS01_Offerta-formativa.yaml)  

##### IFS01.1

Richiedi la lista dei corsi attivi offerti dall'Istituto in un anno accademico

<img src="doc/05_gallery/json.png" width="20
" />  Esempio IFS01.1 [Request](doc/03_analysis/io_schema/IFS01.1-request.json)

<img src="doc/05_gallery/json.png" width="20
" />  Esempio IFS01.1 [Response](doc/03_analysis/io_schema/IFS01.1-response.json)

> **_NOTE:_**   
> Se possibile prevedere la paginazione della response. Se tale funzionalità è implementata, nella request sarà necessario valorizzare anche il campo cursor

##### IFS01.2

Richiede il dettaglio di un corso


<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS01.2 [Request](doc/03_analysis/io_schema/IFS01.2-request.json)

<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS01.2 [Response](doc/03_analysis/io_schema/IFS01.2-response.json)

<hr>

### IFS02 Iscrizioni 🚀

Acquisisce il dettaglio delle iscrizioni accademiche.
Fornisce le informazioni di dettaglio riguardanti le iscrizioni di una studentessa o uno studente all'università o AFAM

<img src="doc/05_gallery/swagger.svg" width="18
" /> Definizione [OpenApi.yaml](src/IFS02_Iscrizioni.yaml)

##### IFS02.1

Acquisizione del dettaglio delle iscrizioni attive negli ultimi tre anni accademici di una studentessa o di uno studente

<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.1 [Request](doc/03_analysis/io_schema/IFS02.1-request.json)

<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.1 [Response](doc/03_analysis/io_schema/IFS02.1-response.json)
##### IFS02.2

Acquisizione delle prove riguardanti l'iscrizione agli studi di istruzione terziaria di una studentessa/studente

<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.2 [Request](doc/03_analysis/io_schema/IFS02.2-request.json)

<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.2 [Response](doc/03_analysis/io_schema/IFS02.2-response.json)
##### IFS02.3

Acquisizione delle prove riguardanti la trascrizione (corsi seguiti, voti ottenuti, ecc.) degli studi di istruzione terziaria di una studentessa/studente. La trascrizione può riferirsi a studi completati o in corso

<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.3 [Request](doc/03_analysis/io_schema/IFS02.3-request.json)

<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.3 [Response](doc/03_analysis/io_schema/IFS02.3-response.json)
##### IFS02.4

Acquisizione delle prove riguardanti l'ammissione agli studi di istruzione terziaria di una studentessa/studente;

<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.4 [Request](doc/03_analysis/io_schema/IFS02.4-request.json)

<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.4 [Response](doc/03_analysis/io_schema/IFS02.4-response.json)

##### IFS02.5

Acquisizione delle prove relative alle attività di apprendimento svolte al di fuori dell'istituzione di istruzione terziaria dalla quale una studentessa/studente ha ottenuto il proprio diploma

<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.5 [Request](doc/03_analysis/io_schema/IFS02.5-request.json)

<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.5 [Response](doc/03_analysis/io_schema/IFS02.5-response.json)

<hr>

#### IFS03 Titoli
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum

<hr>


#### IFS04 Rettifica iscrizioni
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum

<hr>

#### IFS05 Rettifica titoli
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum

<hr>

#### IFS06 Elenco Variazioni Iscrizioni
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum

<hr>

#### IFS07 Elenco variazione titoli
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum

<hr>

#### IFS08 Iscritti per fasce ISEE
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
<hr>



#### IFS09 Iscritti a un corso per anno
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum



<hr>


## Per maggiori informazioni:
* [Interoperabilità e PDND su Developers Italia](https://developers.italia.it/it/interoperabilita/)
* [Avvisi di PAdigitale 2026](https://areariservata.padigitale2026.gov.it/Pa_digitale2026_avvisi)

## Authors

* 
* 
* 
