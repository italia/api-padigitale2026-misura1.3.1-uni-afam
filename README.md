<div align="center">
    <img title="Star on GitHub" src="https://img.shields.io/github/stars/italia/api-padigitale2026-misura1.3.1-uni-afam.svg?style=social&label=Star">
    <img title="Fork on GitHub" src="https://img.shields.io/github/forks/italia/api-padigitale2026-misura1.3.1-uni-afam.svg?style=social&label=Fork"> 
</div>  

<div align="center">
    <a href="https://github.com/italia/api-padigitale2026-misura1.3.1-uni-afam/graphs/contributors"><img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/italia/api-padigitale2026-misura1.3.1-uni-afam" /></a>
    <a href="https://github.com/italia/api-padigitale2026-misura1.3.1-uni-afam/issues"><img alt="Issues" src="https://img.shields.io/github/issues/italia/api-padigitale2026-misura1.3.1-uni-afam?color=0088ff" /></a>
    <a href="https://github.com/italia/api-padigitale2026-misura1.3.1-uni-afam/issues?q=is%3Aissue+is%3Aclosed"><img alt="Issues" src="https://img.shields.io/github/issues-closed/italia/api-padigitale2026-misura1.3.1-uni-afam?color=0088ff" /></a>
    <a href="https://github.com/italia/api-padigitale2026-misura1.3.1-uni-afam/pulse/monthly" alt="Activity"><img src="https://img.shields.io/github/commit-activity/m/italia/api-padigitale2026-misura1.3.1-uni-afam" /></a>        
  </div>



# API di PAdigitale2026 - Misura 1.3.1 - Avvisi per Università e AFAM pubblici

Questo repository contiene le specifiche delle API relative alla misura 1.3.1 per l'avviso dedicato alle Università pubbliche e AFAM (Alta Formazione Artistica, Musicale e Coreutica) pubblici, nell'ambito di PAdigitale2026. 

La tabella sottostante (Tabella 1) riporta il dettaglio del titolo e descrizione per tutte e nove le API (dalla IFS01 alla IFS09) che dovranno essere erogate dai Soggetti Attuatori in base alla fascia di appartenenza. 

:rocket: Link rapido alle [linee guida d'implementazione degli e-service](#linee-guida-agli-e-service)

:rocket: Link rapido alla [release note](/release-note.md)

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
      <td rowspan="2">ifs-&lt;codice istituto&gt;-offerta-formativa</td>
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
      <td rowspan="5">ifs-&lt;codice istituto&gt;-iscrizioni</td>
      <td>IFS02.1</td>
      <td>Acquisizione del dettaglio delle ultime iscrizioni per corso di studi negli ultimi tre anni
          accademici di una studentessa o di uno studente</td>
  </tr>
  <tr>
      <td>IFS02.2</td>
      <td>Acquisizione delle prove riguardanti l'iscrizione agli studi di istruzione
          terziaria di una studentessa/studente</td>
  </tr>
  <tr>
      <td>IFS02.3</td>
      <td>Acquisizione delle prove riguardanti la trascrizione (insegnamenti conseguiti, voti
          ottenuti, ecc.) degli studi di istruzione terziaria di una studentessa/studente. La trascrizione può
          riferirsi a studi completati o in corso</td>
  </tr>
  <tr>
      <td>IFS02.4</td>
      <td>Acquisizione delle prove riguardanti l'ammissione agli studi di istruzione
          terziaria di una studentessa/studente</td>

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
      <td rowspan="4">ifs-&lt;codice istituto&gt;-titoli</td>
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
      <td rowspan="4">ifs-&lt;codice istituto&gt;-rettifica-iscrizioni</td>
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
      <td rowspan="4">ifs-&lt;codice istituto&gt;-rettifica-titoli</td>
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
      <td>ifs-&lt;codice istituto&gt;-variazioni-iscrizioni</td>
      <td>IFS06.1</td>
      <td>Acquisizione delle "impronte (codifica hash)" di tutte le iscrizioni delle
          studentesse/degli studenti negli ultimi tre anni accademici al fine di identificarne le variazioni
          dal punto di vista del fruitore</td>
  </tr>
  <tr>
      <td>Variazioni titoli</td>
      <td>IFS07</td>
      <td>ifs-&lt;codice istituto&gt;-variazioni-titoli</td>
      <td>IFS07.1</td>
      <td>Acquisizione delle "impronte (codifica hash)" di tutti i titoli accademici al
          fine di identificarne le variazioni dal punto di vista del fruitore</td>
  </tr>
  <tr>
      <td>Iscritti per fasce ISEE</td>
      <td>IFS08</td>
      <td>ifs-&lt;codice istituto&gt;-iscrizioni-per-fasce-isee</td>
      <td>IFS08.1</td>
      <td>Acquisizione del numero di studentesse e studenti per fasce ISEE in un anno
          accademico</td>
  </tr>
  <tr>       
      <td>Iscritti a un corso per anno</td>
      <td>IFS09</td>
      <td>ifs-&lt;codice istituto&gt;-iscrizioni-per-corso</td>
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

## Da sapere prima di iniziare a leggere le linee guida agli e-service
**1** - Il Ministero dell'Università e della Ricerca (MUR) pubblica i seguenti vettori di dati codificati come open data a supporto dell'interoperabilità e dell'anagrafe ANIS
>1. Tipi di corsi
>1. Corsi di studio
>1. Classi di laurea
>1. Istituti di formazione superiore

:warning: **I canali di pubblicazione di questi vettori di dati da parte del MUR sono ancora in fase di definizione**

<img src="doc/05_gallery/info.svg" width="20" /> Lo schema dei dataset può essere approfondito nella sezione [risorse utili](#risorse-utili)

**2** -  **Nomi di pubblicazione degli e-service su PDND**</br>
:warning: Si ricorda che in fase di pubblicazione degli e-service sulla piattaforma PDND, il nome deve rispettare quello nella colonna denominata e-service della tabella 1, ossia il seguente pattern:
``` 
    ifs-<codice istituto>-<nome e-service>
    ifs-16-offerta-formativa 
    
    Dove (16) è il codice dell'istituto del Politecnico di Milano 
    nel dataset Istituti di formazione superiore menzionato al punto 1
```

**3** - La visualizzazione della specifica Open API e dei relativi esempi può essere ottenuta utlizzando [l'editor swagger](https://editor-next.swagger.io/) e copiando il contenuto dei file di tipo yaml che verranno forniti via via nella seguente trattazione di dettaglio.

**4** - Il **_person_id_** riportato nella specifica delle API far riferimento all’identificativo univoco ANPR (Anagrafe Nazionale della Popolazione Residente). 

**5** - Perché abbiamo scelto di usare principalmente il metodo POST: [GET Method vs POST Method](https://github.com/italia/api-padigitale2026-misura1.3.1-uni-afam/issues/91)
>1. [URIs, Addressability, and the use of HTTP GET and POST](https://www.w3.org/2001/tag/doc/whenToUseGet.html#:~:text=HTTP%20GET%20promotes%20URI%20addressability,(or%20of%20related%20resources).)
>1. [w3shools-ref  Compare GET vs. POST chapter](https://www.w3schools.com/tags/ref_httpmethods.asp)

**6** - Suggeriamo infine di fare riferimento sempre alla sezione 
[risorse utili](#risorse-utili) che è aggiornata periodicamente.

## Linee guida agli e-service

<p align="center">
 <img src="doc/05_gallery/umarell.png" width="80"/>
</p>

In questo paragrafo sono descritte le seguenti API:

1. [IFS01 Offerta Formativa](#ifs01-offerta-formativa)
2. [IFS02 Iscrizioni](#ifs02-iscrizioni)
3. [IFS03 Titoli](#ifs03-titoli)
4. [IFS04 Rettifica iscrizioni](#ifs04-rettifica-iscrizioni)
5. [IFS05 Rettifica titoli](#ifs05-rettifica-titoli)
6. [IFS06 Variazioni Iscrizioni](#ifs06-variazioni-iscrizioni)
7. [IFS07 variazione titoli](#ifs07-variazione-titoli)
8. [IFS08 Iscrizioni per fasce ISEE](#ifs08-iscrizioni-per-fasce-isee)
9. [IFS09 Iscrizioni per corso](#ifs09-iscrizioni-per-corso)




### IFS01 Offerta formativa

<img src="doc/05_gallery/swagger.svg" width="18
" /> Definizione [OpenApi.yaml](src/IFS01-offerta-formativa.yaml)  

#### :globe_with_meridians: IFS01.1 - educational-offering-list

:jigsaw: **caso d'uso tipico**: Alimentazione portale Universitaly

Acquisizione della lista dei corsi di studio offerti da un istituto di formazione superiore in un dato anno accademico

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" />  Esempio IFS01.1 [Request](doc/03_analysis/io_schema/IFS01.1-request.json)


&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" />  Esempio IFS01.1 [Response](doc/03_analysis/io_schema/IFS01.1-response.json)

> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni**
>
> * La richiesta prevede l'obbligatorietà della compilazione del campo **_academic_year_**. 
> * Nella risposta indicare solo corsi per i quali si può attivare una nuova coorte nell’anno accademico indicato. Includere corsi di Laurea, Dottorato, Diploma di specializzazione e Master.
> *  Nella risposta il **_degree_course_code_** si riferisce al codice identificativo indicato nel relativo dataset pubblicato dal MUR sul repository "Codifiche MUR" https://github.com/MIPA-CINECA/codifiche-mur.
> * Nella risposta per il **_course_area_** indicare la denominazione della Classe di Laurea
> * Per il **_course_location_** indicare il codice ISTAT del comune della sede del corso.
> * Nel caso di corsi associabili a molteplici classi di Laurea, ciascuna combinazione corso/classe è individuata da
degree_course_code differenti.
> * L'attributo  **_cursor_** è utile per la paginazione della risposta: </br>
&emsp;1. Alla prima invocazione non si valorizza l'attributo cursor </br>
&emsp;2. Se la response restituisce l'attributo cursor valorizzato, sarà necessario iterare le invocazioni per ottenere l'intero dataset </br>
&emsp;3. Per le invocazioni successive alla prima si valorizza il campo cursor con il valore ottenuto nell'ultima response
> * E' lasciata allo sviluppatore dell'API la gestione della paginazione e quindi della valorizzazione del cursor sulla response

#### :globe_with_meridians: IFS01.2 - educational-offering-detail

:jigsaw: **caso d'uso tipico**: Alimentazione portale universitaly

Acquisizione del dettaglio di un corso di studio offerto da un Istituto di formazione superiore

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS01.2 [Request](doc/03_analysis/io_schema/IFS01.2-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS01.2 [Response](doc/03_analysis/io_schema/IFS01.2-response.json)

> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni** 
>
> * Nella richiesta l'attributo **_degree_course_code_** è obbligatorio ed individua in modo univoco la combinazione: Corso, Classe, anno accademico della coorte, sede
> * **_degree_course_year_** - I corsi a scelta possono essere ristituiti valorizzando l'anno di corso a 0 e opzionalmente si possono indicare il numero degli insegnamenti a scelta  all'interno di ogni anno come insegnamenti generici con la relativa descrizione nel _learning_name_
> * Nella risposta è sufficente includere il solo primo anno di corso dell’offerta formativa disponibile per la coorte identificata dal codice corso inviato come parametro di ingresso nella richiesta
>
> **AFAM vs Università**
> * Nelle AFAM il **_degree_course_code_** è lo stesso per tutti gli anni accademici della coorte 
> * Nella response per le **università** compilare i campi learning_ssd e learning_cfu
> * Nella response per gli **AFAM** compilare i campi learning_sad e learning_cfa
> * Vedere gli esempi presenti nello yaml/swagger e nella cartella doc/03_analysis/io_schema

:arrow_double_up:	 [Back to top ](#linee-guida-e-service)



### IFS02 Iscrizioni

Acquisisce il dettaglio delle iscrizioni accademiche.
Fornisce le informazioni di dettaglio riguardanti le iscrizioni di una studentessa o uno studente all'università o AFAM

&emsp;&emsp;<img src="doc/05_gallery/swagger.svg" width="18" /> Definizione [OpenApi.yaml](src/IFS02-iscrizioni.yaml)

#### :globe_with_meridians: IFS02.1 - academic-enrollments 

:jigsaw: **caso d'uso tipico**: Alimentazione anagrafe ANIS

Acquisizione del dettaglio delle ultime iscrizioni per corso di studi negli ultimi tre anni accademici di una studentessa o di uno studente

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.1 [Request](doc/03_analysis/io_schema/IFS02.1-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.1 [Response](doc/03_analysis/io_schema/IFS02.1-response.json)

> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni**  
>
> Regole di obbligatorietà input
> * Nella request è obbligatorio il tax_code ed è desiderato anche il person_id per il futuro, oppure è obbligatorio il parametro key nel caso dello scenario descritto nell'API IFS06 per l'acquisizione delle variazioni
>
> Le regole di obbligatorietà di output  
> 1. Nella struttura "Personal Data" è necessario prevedere la restituizione delle informazioni relative al codice fiscale e/o codice fiscale + personID
>```
>ESEMPIO 1: 
>
>"personal_data": {
>    "tax_code": "RSSMRA80A01F205D"
>  }
>
>ESEMPIO 2: 
>
>"personal_data": {
>    "tax_code": "RSSMRA80A01F205D",
>    "person_id": "AB123456C"
>  }
>```
> 2. Nella struttura "Personal Data" se il codice fiscale e/o il personID non sono presenti, restituire le informazioni given_name/family_name/birth_date/birth_place. Questa tipologia di response ha senso solo con l'invocazone dell'API che utilizza il parametro key, relativamente allo scenario descritto in IFS06
>
>ESEMPIO 3: 
>
>```
>"personal_data": {
>    "given_name": Mario,
>    "family_name": Rossi,
>    "birth_date": 10-01-2022,
>    "birth_place": Roma, RM, Italia
>  }
>```
> 3. Nella struttura "enrollments" tutti i campi sono obbligatori tranne il degree_class_code. Nel caso in cui il degree_class_code non sia valorizzabile, è possibile passarlo con il valore NULL
> 4. Nella struttura "enrollments", qualora sia presente un attributo non valorizzabile (ad esclusione del attirubuto degree_class_code) l'istanza dell'iscrizione non deve essere restituita.
>
>```Di seguito l'obbligatorietà con "*"
>
>   enrollment
>      institute_code * 
>      institute_name * 
>      programme_type_code * 
>      degree_course_code * 
>      degree_class_code 
>      academic_year * 
>      degree_course_year * 
>      status *
>```

#### :globe_with_meridians: IFS02.2 - proof-tertiary-education-enrollments

:jigsaw: **caso d'uso tipico**: Acquisizione prove Single Digital Gateway (SDG)

Acquisizione delle prove riguardanti l'ultima iscrizione a ogni corso di studi di istruzione terziaria di una studentessa/studente negli ultimi 3 anni accademici

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.2 [Request](doc/03_analysis/io_schema/IFS02.2-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.2 [Response](doc/03_analysis/io_schema/IFS02.2-response.json)

> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni**    
> * **_expected_graduation_date_** 
Indicare convenzionalmente 31/12/(anno immat + durata normale del corso)
es. immatricolato Laurea Triennale 01/10/20 => expected_graduation_date = 31/12/2023
> * **_enrollment_date_**
Indicare convenzionalmente la data di inizio (es 01/10/xxxx) dell’anno accademico cui si riferisce l’ultima iscrizione attiva per il corso individuato dal degree_course_code

:jigsaw: **caso d'uso tipico**: Acquisizione prove Single Digital Gateway (SDG)


#### :globe_with_meridians: IFS02.3 - proof-tertiary-education-courses

Acquisizione delle prove riguardanti la trascrizione (insegnamenti conseguiti, voti ottenuti, ecc.) degli studi di istruzione terziaria di una studentessa/studente, sono quindi le attività che lo studente ha già sostenuto durante il percorso formativo. La trascrizione può riferirsi a studi completati o in corso negli ultimi 3 anni accademici. Si fa riferimento ad attività superate o convalidate dallo studente, attività presenti a piano di studio approvato ed
attività non sovrannumerarie

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.3 [Request](doc/03_analysis/io_schema/IFS02.3-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.3 [Response](doc/03_analysis/io_schema/IFS02.3-response.json)

> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni** 
> * Vanno considerate solo gli elementi del Piano degli Studi approvato con insegnamenti in posizione di effettivo (solo esclusi quelli in soprannumero) con esame sostenuto o convalidato
> * **_attended_learning_name_** Il nome dell’insegnamento va indicato nella lingua di erogazione dell’insegnamento stesso.
> * **_start_date/end_date_** Indicare date convenzionali in base all’anno accademico ed al semestre
> * **_grade_value_** Espressione regolare del tipo \<Voto numerico\>  o \<Voto numerico\> + 'L' o 'QUALIFIED' o null <br>
```30L o 30 o QUALIFIED o null ```

#### :globe_with_meridians: IFS02.4 - proof-tertiary-education-admission

:jigsaw: **caso d'uso tipico**: Acquisizione prove Single Digital Gateway (SDG)

Acquisizione delle prove riguardanti le ultime ammissioni ai corsi di studi di istruzione terziaria di una studentessa/studente negli ultimi 3 anni accademici


&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.4 [Request](doc/03_analysis/io_schema/IFS02.4-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.4 [Response](doc/03_analysis/io_schema/IFS02.4-response.json)

> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni** 
> * **_start_date_of_academic_year/end_date_of_academic_year_** Indicare date convenzionali di inizio/ fine anno accademico


#### :globe_with_meridians: IFS02.5 - proof-mobility-periods

:jigsaw: **caso d'uso tipico**: Acquisizione prove Single Digital Gateway (SDG)

Acquisizione delle prove relative alle attività di apprendimento svolte al di fuori dell'istituzione di istruzione terziaria dalla quale una studentessa/studente ha ottenuto il proprio titolo accademico

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.5 [Request](doc/03_analysis/io_schema/IFS02.5-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS02.5 [Response](doc/03_analysis/io_schema/IFS02.5-response.json)

> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni**
> * e-service ancora non completamente consolidato, è in corso l’analisi con il partner EU per il suo raffinamento. Nella versione corrente sembra riferito solo al Learning Agreement, che descrive le condizioni di avvio del programma di scambio e non comprende il consuntivo degli esami sostenuti, definito dal Trascript of Records. Da chiarire se sono di interesse anche gli scambi nazionali, per i quali non è previsto un Learning Agreement.
> * **_mobility_period_type_** Valore enumerato come di segutio <br>
 ```trimestrale, semestrale, annuale, breve_termine, lungo_termine```
> * **_destination_erasmus_code_**
L'informazione non è sempre disponibile => parametro opzionale
> * **_destination_institute_name_** 
La destinazione di uno scambio potrebbe non essere un Ateneo => parametro opzionale
> * **_destination_department_** L'informazione non è sempre disponibile => parametro opzionale
> * **_departure_department_**
L'informazione non è sempre disponibile => parametro opzionale
> * **birth_place** Dove possibile il campo deve contenere le informazioni concatenate della Nazione/Provincia/Comune. Il formato previsto prevede la seguente espressione regolare <br>
```.*,[a-zA-Z]*,[a-zA-Z]``` <br>
```<nome_nazione>,<codice_provincia>,<nome_comune> Esempio: birth_place="Italia,MI,Milano"```<br>
> Nel caso di comuni esteri, se non fosse possibile recuperare il codice_provincia, si potrà inserire la codifica EE<br>
> ```Esempio: birth_place="Austria,EE,Vienna" ```

:arrow_double_up:	 [Back to top ](#linee-guida-e-service)


### IFS03 Titoli
Restituisce l'elenco dei titoli conseguiti da una studentessa o uno studente

<img src="doc/05_gallery/swagger.svg" width="18" /> Definizione [OpenApi.yaml](src/IFS03-titoli.yaml)

#### :globe_with_meridians: IFS03.1 - academic-qualifications

:jigsaw: **caso d'uso tipico**: Alimentazione anagrafe ANIS

Acquisizione del dettaglio dei titoli accademici conseguiti da una studentessa/uno studente

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS03.1 [Request](doc/03_analysis/io_schema/IFS03.1-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS03.1 [Response](doc/03_analysis/io_schema/IFS03.1-response.json)

><img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni** 
> * Passare tutti i dati disponibili e la profondità storica dipende dagli istituti di formazione superiore. 
> * Includere tutti coloro che hanno conseguito un titolo di Laurea, Dottorato, Diploma di specializzazione o Master
> * In caso di Laurea congiunta esiste un unico titolo, sulla cui pergamena sono riportati entrambi gli Atenei e che è gestito dal solo Ateneo di riferimento (l’unico che comunica i dati della carriera ad ANSU).
> * **_qualification_grade_value_**: Espressione regolare del tipo \<Voto numerico\>  o \<Voto numerico\> + 'L' o 'QUALIFIED' o null <br>
```30L o 30 o QUALIFIED o null ``` 
> * Regole di [obbligatorietà output](#output) (si prega di verificare gli esempi sul file openapi):
>1) Nella struttura "Personal Data" è necessario prevedere la restituizione delle informazioni relative al codice fiscale e/o codice fiscale + personID
>
>```
>ESEMPI: 
>
>"personal_data": {
>    "tax_code": "RSSMRA80A01F205D"
>  }
>
>"personal_data": {
>    "tax_code": "RSSMRA80A01F205D",
>    "person_id": "AB123456C"
>  }
>```
>
>2) Nella struttura "Personal Data" se il codice fiscale e/o il personID non sono presenti, restituire le informazioni given_name/family_name/birth_date/birth_place
>```
>ESEMPIO: 
>
>"personal_data": {
>    "given_name": Mario,
>    "family_name": Rossi,
>    "birth_date": 10-01-2022,
>    "birth_place": Roma, RM, Italia
>  }
>```
>3) nel caso in cui uno dei valori presenti al punto 2 non sia possibile valorizzarlo, è necessario NON restituire l'istanza dell'iscrizione
>4) nella struttura "qualifications" tutti i campi sono obbligatori tranne il degree_class_code. Nel caso in cui il degree_class_code non sia valorizzabile, è possibile passarlo con il valore NULL
>5) nella struttura "qualifications", qualora sia presente un attributo non valorizzabile (ad esclusione degli attributi degree_class_code/qualification_grading_scale_maximum_grade/qualification_grading_scale_minimum_grade/) non dovrà essere restituito Item.  


#### :globe_with_meridians: IFS03.2 - proof-tertiary-education-qualifications

:jigsaw: **caso d'uso tipico**: Acquisizione prove Single Digital Gateway (SDG)

Acquisizione delle prove riguardanti il completamento degli studi di istruzione terziaria 

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS03.2 [Request](doc/03_analysis/io_schema/IFS03.2-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS03.2 [Response](doc/03_analysis/io_schema/IFS03.2-response.json)

> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni**    
> * Passare tutti i dati disponibili, la profondità storica dipende dagli atenei.
Includere tutti coloro che hanno conseguito un titolo di Laurea, Dottorato, Diploma di specializzazione o Master. In caso di Laurea congiunta esiste un unico titolo, sulla cui pergamena sono riportati entrambi gli Atenei, e che è gestito
dal solo Ateneo di riferimento (l’unico che comunica i dati della carriera ad ANSU).
>* Regole di [obbligatorietà output](#output) (si prega di verificare gli esempi sul file openapi):
>1) Nella struttura "Personal Data" è necessario prevedere la restituizione delle informazioni relative al codice fiscale e/o codice fiscale + personID
>2) Nella struttura "Personal Data" se il codice fiscale e/o il personID non sono presenti, restituire le informazioni given_name/family_name/birth_date/birth_place


#### :globe_with_meridians: IFS03.3 - proof-tertiary-education-qualifications-level

:jigsaw: **caso d'uso tipico**: Acquisizione prove Single Digital Gateway (SDG)

Acquisizione delle prove riguardanti il livello di qualifica degli studi di istruzione terziaria. Si fa riferimento ad attività superate o convalidate dallo studente, attività presenti a piano di studio approvato ed
attività non sovrannumerarie


&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS03.3 [Request](doc/03_analysis/io_schema/IFS03.3-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS03.3 [Response](doc/03_analysis/io_schema/IFS03.3-response.json)

> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni**  
> * **_has_parent_relation_** Si riferisce al legame di genitorialità (biologica o adottiva) tra un genitore e la persona di riferimento (richiedente). Se non calcolabile => null
> * **_degree_course_duration_in_months_**
Durata normale del corso espresso in mesi per gestire corsi di master di durata inferiore all’anno  
> * **_ects_learnings_** fanno riferimento agli insegnamenti conseguiti, ossia già sostenuti dallo studente
> * Regole di [obbligatorietà output](#output) (si prega di verificare gli esempi sul file openapi): 
>1) Nella struttura "Personal Data" è necessario prevedere la restituizione delle informazioni relative al codice fiscale e/o codice fiscale + personID
>2) Nella struttura "Personal Data" se il codice fiscale e/o il personID non sono presenti, restituire le informazioni given_name/family_name/birth_date/birth_place



#### :globe_with_meridians: IFS03.4 - proof-tertiary-education-qualifications-diploma-supplement

 :jigsaw: **caso d'uso tipico**: Acquisizione prove Single Digital Gateway (SDG)

Acquisizione delle prove relative allo strumento "Diploma Supplement". Si fa riferimento ad attività superate o convalidate dallo studente, attività presenti a piano di studio approvato ed attività non sovrannumerarie

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS03.4 [Request](doc/03_analysis/io_schema/IFS03.4-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS03.4 [Response](doc/03_analysis/io_schema/IFS03.4-response.json)

> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni**    
> * **_access_to_regulated_profession_**
Fare riferimento al punto 5.2 del Diploma Supplement “accesso ad una professione regolamentata” che elenca le
professioni per le quali è possibile ottenere l’abilitazione all’esercizio tramite il superamento di un Esame di Stato.
> * **_learning_start_date/ learning_end_date_**
Indicare date convenzionali in base all’anno accademico ed al semestre
> * **_attended_learnings_** Si fa riferimento agli insegnamenti conseguiti, ossia che lo studente ha già sostenuto
> * Regole di [obbligatorietà output](#output) (si prega di verificare gli esempi sul file openapi):
>1) Nella struttura "Personal Data" è necessario prevedere la restituizione delle informazioni relative al codice fiscale e/o codice fiscale + personID
>2) Nella struttura "Personal Data" se il codice fiscale e/o il personID non sono presenti, restituire le informazioni given_name/family_name/birth_date/birth_place


[Risorse utili](#risorse-utili)

> :pencil2: **Note compilazione campi**  
>
> **birth_place**: 
> * Dove possibile il campo deve contenere le informazioni concatenate del Nazione/Provincia/Comune. 
> * il formato previsto prevede la seguente forma: *<nome_nazione>,<codice_provincia>,<nome_comune>, *
>
> *Esempio: birth_place="Italia,MI,Milano"*
> * Nel caso di comuni esteri, se non fosse possibile recuperare il codice_provincia, si potrà inserire la codifica EE
>
> *Esempio: birth_place="Austria,EE,Vienna"*
>
> * RegEx applicata: .*,[a-zA-Z]*,[a-zA-Z]*

:arrow_double_up:	 [Back to top ](#linee-guida-e-service)

### IFS04 Rettifica iscrizioni

:jigsaw: **caso d'uso tipico**: Interazione con anagrafe ANIS

Richiede la rettifica dei dati di un’iscrizione mancante o in eccesso per una studentessa o uno studente che stia frequentando o abbia frequentato.

&emsp;&emsp;<img src="doc/05_gallery/swagger.svg" width="18
" /> Definizione [OpenApi.yaml](src/IFS04-rettifica-iscrizioni.yaml)


#### :globe_with_meridians: IFS04.1 - academic-enrollment-change-request

:jigsaw: **caso d'uso tipico**: Interazione con anagrafe ANIS

Richiesta di rettifica  di un'iscrizione accademica di una studentessa/uno studente all'Istituto di formazione superiore

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS04.1 [Request](doc/03_analysis/io_schema/IFS04.1-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS04.1 [Response](doc/03_analysis/io_schema/IFS04.1-response.json)



#### :globe_with_meridians: IFS04.2 - academic-enrollment-change-request-status

:jigsaw: **caso d'uso tipico**: Interazione con anagrafe ANIS

Acquisizione dello stato delle richieste di rettifica delle iscrizioni accademiche di una studentessa/uno studente all'Istituto di istruzione superiore

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS04.2 [Request](doc/03_analysis/io_schema/IFS04.2-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS04.2 [Response](doc/03_analysis/io_schema/IFS04.2-response.json)


#### :globe_with_meridians: IFS04.3 - academic-enrollment-change-request-cancellation

:jigsaw: **caso d'uso tipico**: Interazione con anagrafe ANIS

Richiesta di annullamento di una richiesta di rettifica di una iscrizione accademica di una studentessa/uno studente all'Istituto di istruzione superiore

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS04.3 [Request](doc/03_analysis/io_schema/IFS04.3-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS04.3 [Response](doc/03_analysis/io_schema/IFS04.3-response.json)

> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni**    
>
> * Valorizzare in input almeno un campo tra tax_code e person_id


#### :globe_with_meridians: IFS04.4 - enrollments-issues

:jigsaw: **caso d'uso tipico**: Interazione con anagrafe ANIS

Invio di una segnalazione dall'ente fruitore all'ente erogatore per comunicare eventuali anomalie sui dati delle iscrizioni accademiche

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS04.4 [Request](doc/03_analysis/io_schema/IFS04.4-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS04.4 [Response](doc/03_analysis/io_schema/IFS04.4-response.json)

> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni**   
> 
> * Valorizzare in input almeno un campo tra tax_code e person_id
> * nel caso in cui in input gli attributi tax_code/person_id non siano valorizzabili, compilare i parametri given_name/family_name/birth_date/birth_place

> :pencil2: **Note compilazione campi**  
>
> **birth_place**: 
> * Dove possibile il campo deve contenere le informazioni concatenate del Nazione/Provincia/Comune. 
> * il formato previsto prevede la seguente forma: *<nome_nazione>,<codice_provincia>,<nome_comune>, *
>
> *Esempio: birth_place="Italia,MI,Milano"*
> * Nel caso di comuni esteri, se non fosse possibile recuperare il codice_provincia, si potrà inserire la codifica EE
>
> *Esempio: birth_place="Austria,EE,Vienna"*
>
> * RegEx applicata: .*,[a-zA-Z]*,[a-zA-Z]*



:arrow_double_up:	 [Back to top ](#linee-guida-e-service)


### IFS05 Rettifica titoli
Richiede la rettifica dei dati di un’iscrizione mancante o in eccesso per una studentessa o uno studente che stia frequentando o abbia frequentato.

&emsp;&emsp;<img src="doc/05_gallery/swagger.svg" width="18
" /> Definizione [OpenApi.yaml](src/IFS05-rettifica-titoli.yaml)



#### :globe_with_meridians: IFS05.1 - academic-qualification-change-request

:jigsaw: **caso d'uso tipico**: Interazione con anagrafe ANIS

Richiesta di rettifica  di un titolo accademico di una studentessa/uno studente all'Istituto di formazione superiore

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS05.1 [Request](doc/03_analysis/io_schema/IFS05.1-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS05.1 [Response](doc/03_analysis/io_schema/IFS05.1-response.json)



#### :globe_with_meridians: IFS05.2 - academic-qualification-change-request-status

:jigsaw: **caso d'uso tipico**: Interazione con anagrafe ANIS

Acquisizione dello stato delle richieste di rettifica dei titoli accademici di una studentessa/uno studente all'Istituto di istruzione superiore

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS05.2 [Request](doc/03_analysis/io_schema/IFS05.2-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS05.2 [Response](doc/03_analysis/io_schema/IFS05.2-response.json)



#### :globe_with_meridians: IFS05.3 - academic-qualification-change-request-cancellation

:jigsaw: **caso d'uso tipico**: Interazione con anagrafe ANIS

Richiesta di annullamento di una richiesta di rettifica di un titolo accademico di una studentessa/uno studente all'Istituto di istruzione superiore

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS05.3 [Request](doc/03_analysis/io_schema/IFS05.3-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS05.3 [Response](doc/03_analysis/io_schema/IFS05.3-response.json)


#### :globe_with_meridians: IFS05.4 - academic-qualifications-issues

:jigsaw: **caso d'uso tipico**: Interazione con anagrafe ANIS

Invio di una segnalazione dall'ente fruitore all'ente erogatore per comunicare eventuali anomalie sui dati dei titoli accademici

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS05.4 [Request](doc/03_analysis/io_schema/IFS05.4-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS05.4 [Response](doc/03_analysis/io_schema/IFS05.4-response.json)


> :pencil2: **Note compilazione campi**  
>
> **birth_place**: 
> * Dove possibile il campo deve contenere le informazioni concatenate del Nazione/Provincia/Comune. 
> * il formato previsto prevede la seguente forma: *<nome_nazione>,<codice_provincia>,<nome_comune>, *
>
> *Esempio: birth_place="Italia,MI,Milano"*
> * Nel caso di comuni esteri, se non fosse possibile recuperare il codice_provincia, si potrà inserire la codifica EE
>
> *Esempio: birth_place="Austria,EE,Vienna"*
>
> * RegEx applicata: .*,[a-zA-Z]*,[a-zA-Z]*



:arrow_double_up:	 [Back to top ](#linee-guida-e-service)


### IFS06 Variazioni Iscrizioni

:jigsaw: **caso d'uso tipico**: Interazione con anagrafe ANIS

Richiede la lista delle ultime iscrizioni per ogni corso di studi negli ultimi 3 anni accademici.

&emsp;&emsp;<img src="doc/05_gallery/swagger.svg" width="18
" /> Definizione [OpenApi.yaml](src/IFS06-variazioni-iscrizioni.yaml)


#### :globe_with_meridians: IFS06.1 - student-enrollments-changes 

:jigsaw: **caso d'uso tipico**: Interazione con anagrafe ANIS

Acquisizione delle "impronte (codifica hash)" di tutte le iscrizioni delle studentesse/degli studenti negli ultimi tre anni accademici al fine di identificarne le variazioni dal punto di vista del fruitore

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS06.1 [Request](doc/03_analysis/io_schema/IFS06.1-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS06.1 [Response](doc/03_analysis/io_schema/IFS06.1-response.json)


> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni**
>    
> * Si ricorda di NON valorizzare il campo "cursor" nell'esecuzione della prima chiamata.
> * Qualora nella response fosse presente il campo "cursor" valorizzato, prevedere la sua valorizzazione nelle chiamate successive.
> * Prevedere, tramite l'attributo "cursor", una strategia di paginazione dei risultati restituiti dalla API. Qualora l'attributo fosse restituito NULLO (o non presente), nessuna chiamata successiva deve essere effettuata dal client.



#### Esempio: 
Scenario operativo di acquisizione delle variazioni delle iscrizioni fra l'anagrafe ANIS e un Istituto di istruzione superiore

<img src="doc/05_gallery/ifs06-ANIS update process.drawio.png"/> 

N.B. Si prega di visionare anche la sezione IFS02

:arrow_double_up:	 [Back to top ](#linee-guida-e-service)


### IFS07 Variazione titoli
Richiede la lista di tutti i titoli conseguiti


&emsp;&emsp;<img src="doc/05_gallery/swagger.svg" width="18
" /> Definizione [OpenApi.yaml](src/IFS07-variazioni-titoli.yaml)


#### :globe_with_meridians: IFS07.1 - student-qualifications-changes

:jigsaw: **caso d'uso tipico**: Interazione con anagrafe ANIS

Acquisizione delle "impronte (codifica hash)" di tutti i titoli accademici al fine di identificarne le variazioni dal punto di vista del fruitore

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS07.1 [Request](doc/03_analysis/io_schema/IFS07.1-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS07.1 [Response](doc/03_analysis/io_schema/IFS07.1-response.json)

> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni**
>
> * Si ricorda prevedere di NON valorizzare il campo "cursor" nell'esecuzione della prima chiamata.
> * Qualora nella response fosse presente il campo "cursor" valorizzato, prevedere la sua valorizzazione nelle chiamate successive.
> * Prevedere, tramite l'attributo "cursor", una strategia di paginazione dei risultati restituiti dalla API. Qualora l'attributo fosse restituito NULLO (o non presente), nessuna chiamata successiva deve essere effettuata dal client.
> * **university_system_type**, di seguito la descrizione delle codifiche disponibili per il campo: 
> 1. Il valore 'old' si riferisce a tutti i titoli accademici ottenuti prima del nuovo ordinamento Universitario/AFAM regolato dai decreti legislativi 509/99 per l'Università e 508/99 per l'AFAM.
> 1. Il valore 'new' si riferisce ai titoli accademici ottenuti a partire dal nuovo oridnamento Universitario/AFAM regolato dai decreti legislativi 509/99 per l'Università e 508/99 per l'AFAM.
> 1. Se questo parametro non è specificato, l'API restituisce i titoli accademici sia del vecchio che del nuovo ordinamento.
> * ***sync_mode***, di seguito la descrizione delle codifiche disponibili per il campo:
> 1. Il valore 'full' rappresenta tutti i titoli accademici
> 1. Il valore 'incremental' rappresenta:
> a) Ogni qualifica accademica ottenuta dallo studente negli ultimi 2 anni solari (basata sulla data di conseguimento del titolo).
> b) Qualsiasi titolo accademico rettificato negli ultimi 2 anni solari (basato sulla data di rettifica del titolo). Se uno studente non ha più alcun titolo accademico perché è stato eliminato, l'API restituisce null o un hash di un'entità null.
> 1. Se questo parametro non è valorizzato, il valore predefinito è **full**

#### Esempio: 
Vedere scenario operativo presente nel paragrafo delle iscrizioni di IFS06




:arrow_double_up:	 [Back to top ](#linee-guida-e-service)


### IFS08 Iscrizioni per fasce ISEE
Acquisisce il numero di studentesse e studenti per fasce ISEE in un anno accademico

&emsp;&emsp;<img src="doc/05_gallery/swagger.svg" width="18
" /> Definizione [OpenApi.yaml](src/IFS08-iscrizioni-per-fasce-isee.yaml)

#### :globe_with_meridians: IFS08.1 - count_academic_enrollments_by_isee_ranges

Acquisizione del numero di studentesse e studenti per fasce ISEE in un anno accademico



&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS08.1 [Request](doc/03_analysis/io_schema/IFS08.1-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS08.1 [Response](doc/03_analysis/io_schema/IFS08.1-response.json)

> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni**    
>
> - La API deve essere organizzata secondo la ripartizione degli scaglioni coerenti con i provvedimenti normativi in vigore relativamente alla tassazione universitaria (No-tax area e progressività) per gli Atenei statali e gli istituti AFAM statali (L. 232/2016, DM 1014/2021, DM 1016/2021). Si riportano di seguito la proposta di ripartizione degli scaglioni corente con la normativa vigente e con maggiore dettaglio per finalità amministrative di analisi
> - <b><i> E' di libero arbitrio degli istituti la scelta di definire una soglia minima di studenti entro la quale mostrare la fascia di reddito.</i></b>
>
>| scaglioni ISEE |
>|----------------------------------------------------------------|
>| <=13.000 |
>| 13.001-16.000 |
>| Classe di ampiezza 2.000 da 16.001-40.000 |
>| Classe di ampiezza 5.000 da 40.001-60.000 |
>| Classe di ampiezza 10.000 da 60.001-100.000 |
>| >100.000 |
>| ISEE non presentato |


:arrow_double_up:	 [Back to top ](#linee-guida-e-service)




### IFS09 Iscrizioni per corso
Ottiene il numero di studentesse e di studenti iscritti ad un IFS.

&emsp;&emsp;<img src="doc/05_gallery/swagger.svg" width="18
" /> Definizione [OpenApi.yaml](src/IFS09-iscrizioni-per-corso.yaml)

#### :globe_with_meridians: IFS09.1 - count_academic_enrollments_by_degree_courses

Acquisizione del numero di studentesse e studenti iscritti a un corso di studi per anno accademico

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS09.1 [Request](doc/03_analysis/io_schema/IFS09.1-request.json)

&emsp;&emsp;<img src="doc/05_gallery/json.png" width="20
" /> Esempio IFS09.1 [Response](doc/03_analysis/io_schema/IFS09.1-response.json)


> <img src="doc/05_gallery/info.svg" width="20" />  **Osservazioni**    
>
> * Il dato può cambiare nel corso dell’anno a causa di:
> 1. immatricolazioni al secondo semestre
> 1. immatricolazioni di dottorandi scaglionate su diverse finestre di ingresso
> 1. ricongiunzioni
> 1. avvio di nuove edizioni di Corsi di Master in qualsiasi mese dell’anno
> * vedere gli input/output di esempio sopra riportati
> * nel caso in cui i parametri male_enrollment_count o female_enrollment_count non siano valorizzabili -> restituire un valore nullo

:arrow_double_up:	 [Back to top ](#linee-guida-e-service)


## Scenario di utilizzo JSON-LD:

:construction: Work in progress

#### Risorse

* Visualizzatore OpenApi.yaml in formato Swagger:  https://editor.swagger.io/
* Convertitore di x-jsonle-context in json: https://yml2json.com/
* Convertitore di Json in Json-ld https://json-ld.org/playground/

<img src="doc/05_gallery/scenario.png" />



## Risorse utili 

#### Masterdata pubblicato dal Ministero dell'Università e della Ricerca

Per la valorizzazione dei campi  institude_code, programme_type_code, degree_course_code, degree_class_code si prega di fare riferimento al Master data pubblicato dal Ministero dell'Università e della Ricerca (MUR) con i seguenti dataset 

* institute
* programme-type
* degree-class
* degree-course

Lo schema del master data pubblicato dal MUR può essere scaricato a questo [link](doc/03_analysis/masterdata/MUR-masterdata.xlsx)
 
> :warning: Sono ancora in fase di definizione i canali di pubblicazione del Master data e il relativo schema. E' comunque consigliato realizzare una "cache" del Master data nei sistemi locali da aggiornare periodicamente.
>
> **Solo a titolo meramente esemplificativo**, possono essere ottenute informazioni aggiuntive nei [metadati](https://dati-ustat.mur.gov.it/dataset/metadati) pubblicati dall'Ufficio di Statistica del Ministero dell'Università e della Ricerca (MUR).
> 
> Per qualsiasi richeiesta di chiarimento potete [aprire una issue](https://github.com/italia/api-padigitale2026-misura1.3.1-uni-afam/issues/new) su questo repository GitHub


#### Cursor pagination
L'impaginazione basata sul cursore consente di recuperare in modo efficiente set di dati di grandi dimensioni da un database suddividendoli in "pagine" più piccole. 

#### Business canvas
Il [business canvas](https://docs.google.com/spreadsheets/d/1-H3R9vLX_Y3_7NxGN1I6WzSD8EdPJy4N/edit#gid=857294954) è il documento utilizzato dal gruppo di lavoro per la collaborazione e per la modellazione delle specifiche Open API.

## Per maggiori informazioni:
* [Interoperabilità e PDND su Developers Italia](https://developers.italia.it/it/interoperabilita/)
* [Avvisi di PAdigitale 2026](https://areariservata.padigitale2026.gov.it/Pa_digitale2026_avvisi)
* [Normativa e modelli relativi al Diploma Supplement](https://www.miur.gov.it/-/nuovo-supplemento-al-diploma-con-4-allegati-relativi-alla-compilazione-e-alle-linee-guida-nazionali-per-la-digitalizzazione)
## Ultima Modifica 🔬

29/05/2024

## Authors 🚶

* Denis Marini
* Davide Longo
* Lorenzo Doneda
