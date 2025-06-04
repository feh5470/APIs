## APIs
Basierend auf dem Kapitel 11 des Buches Software Engineering for Data Scientists

# Überblick Inhalt
- Eine API kann viele verschiedene Endpoints haben so wie GET- oder POST-Endpoints.
- In Python kann eine API sehr einfach mit der Requests library aufgerufen werden.
- Die Antwort des Servers beinhaltet einen Statuscode und bei erfolgreicher Anfrage auch die geforderten Daten in JSON- oder XML-Format.
- Zum Erstellen einer eigenen API bietet sich FastAPI an. Ebenfalls wird man hierbei auch eine web server library wie Uvicorn brauchen, um die API aufrufbar zu machen.


# Bedeutung von APIs
Als Data Scientist ruft man APIs auf, um Daten zu erlangen und mit ihnen Berechnungen auszuführen. Ebenfalls sind APIs nützlich, um die Funktionalität des eigenen Codes in standardisiertem Format mit anderen Leuten zu teilen.
Vor allem für einen sauberes, wiederverwendbares Projekt können APIs Abhilfe schaffen. Prozesse können automatisiert und durch den Aufruf einer API reproduzierbar gemacht werden, was ebenfalls viel Dokumentation sparen kann.
