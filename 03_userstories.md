# User Stories 
*Im Folgenden finden Sie ein Beispiel, wie eine User Story aussehen könnte. Sie können die eigenen User Stories nach eigenen Bedürfnissen mehr oder weniger formal ausdrücken. Sie brauchen aber mindestens einen Titel, ein Ziel (sofern der Titel dieses nicht präzise genug ausdrückt) und einen normalen Ablauf. Sie können sich zum Beispiel an den Templates in https://en.wikipedia.org/wiki/Use_case orientieren*

## Export der Termine (UC-001)

### Ziel
Die eigenen, vereinbarten Termine sollen in eine eigene Kalender-Anwendung übernommen werden. Dazu wird ein iCaleder File nach [RFC 5545](https://tools.ietf.org/html/rfc5545) verwendet. Das Systemstellt nur die Datei zur Verfügung, der Import in die Zielanwendung muss manuell erfolgen.

### Vorbedingungen
* Benutzerin muss eingeloggt sein (Rolle: Mentorin, Studierende)
* Es müssen für die Benutzerin Termine angelegt worden sein

### Normaler Ablauf
* Die Benutzerin wählt aus, dass sie ihre Termine als Calender Datei exportieren möchte.
* Das System generiert die Datei und bietet diese zum Download an. 

### Alternative Abläufe
Wenn keine Termine vorhanden sind, bietet das System den Export nicht an.
