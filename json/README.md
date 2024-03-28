# Schemi dati e versioni LD corrispondenti

Nelle cartelle sottostanti si possono trovare 3 tipi di file:
1. IFSxx.json è la traduzione in JSON dell'esempio relativo allo schema dati
2. IFSxx-LD.json è la versione corrispondente in JSON-LD del JSON al punto 1.
3. IFSxx-LD-TM.handlebars è un template in formato handlebars.js che permette di convertire in modo automatico i dati al punto 1. nel dato al punto 2.

## Come si possono usare i file handlebars

È possibile aprire il [Playground Handlebars](https://handlebarsjs.com/playground.html), quindi:
* inserire nella casella "Template" il contenuto del file IFSxx-LD-TM.handlebars
* inserire nella casella "Input" il contenuto del file IFSxx.json

Nella casella "Output" si otterrà il contenuto del file IFSxx-LD.json
