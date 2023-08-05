# progetto-sistemi-automatici-di-misura
**Progetto di Sistemi Automatici di Misura 2023 - Corso della Laurea Magistrale in Ingegneria Elettronica (indirizzo: Hardware-Software CoDesign)**
<br><br>
Un progetto che prevede l'acquisizione automatica della temperatura, dell'umidità e della temperatura percepita tramite sensore DHT11 e configurazione mediante Arduino. L'interfaccia, realizzata in LabVIEW, permette di visualizzare in tempo reale l'andamento dell'acquisizione corrente e consente di salvare su richiesta i dati sia su file che in locale. Nello specifico è stato sviluppato un server, tramite il framework Spring Boot in Java, mediante il quale è possibile salvare i dati su un database e, se richiesto, è possibile ottenere misurazioni in riferimento ad un certo periodo di tempo. Inoltre, è possibile specificare sia l'intervallo di tempo di acquisizione tramite Arduino sia quanti campioni salvare all'interno del database.
