## Benutzung

Eine Fehlermeldung wird angezeigt, wenn das Protokoll von _Little Navmap_, _Little Navconnect_ oder _Little Xpconnect_ nicht übereinstimmt. Alle Programme sollten auf der neusten Version sein oder die bei _Little Navmap_ mitgelieferten Versionen verwendet werden.

### Flugsimulator Computer

_Little Navconnect_ muss auf dem Flugsimulator Computer installiert werden. Nach dem Starten müssen die farbigen Werte im Logfenster notiert werden. Es kann die IP-Addresse oder der Hostname verwendet werden.

Das Programm verbindet sich automatisch zu einem Flugsimulator über SimConnect, wenn ein laufender Simulator gefunden wird.
Wenn die Verbindung auf X-Plane umgestellt wird, verbindet sich das Programm automatisch zum _Little Xpconnect_ Plugin wenn X-Plane läuft. Wenn kein Simulator gefunden wurde, wird in 10 Sekunden Intervallen ein neuer Verbindungsversuch unternommen.

_Little Navconnect_ kann mehrere IP-Addressen oder Hostnamen, abhängig von den Netzwerkeinstellungen, anzeigen. Zum Beispiel, wenn eine Verbindung über Kabel als auch über WLAN besteht. Wenn nicht klar ist, welche Adresse genommen werden sollte, hilft ausprobieren.

![Little Navconnect](../images/littlenavconnect.jpg "Little Navconnect")

 **Bild oben:** Little Navconnect läuft und wartet auf einen Flugsimulator. Die _`FSX oder Prepar3D`_ und _`X-Plane`_ Knöpfe werden unter macOS und Linux, oder wenn SimConnect nicht verfügbar ist, verborgen.

Der Port muss im `Optionen` Dialog geändert werden, wenn ein Fehler wie unten angezeigt wird:

`[2017-02-30 16:58:29] Server kann nicht gestartet werden: Die Adresse wird bereits benutzt.`
<!--	TODO: Bitte durch exacte Fehlermeldung ersetzen.
	Mal sehen, wie lange es dauert, bis das jemandem auffällt ;-) -->

### Klient oder Entfernter Computer

1. _Little Navmap_ auf entferntem Computer starten.
2. Verbindungsdialog von _Little Navmap_ mit `Hauptmenü` -> `Werkzeuge` -> `Flugsimulatorverbindung` öffnen.

    ![Little Navmap Connect Dialog](../images/connect.jpg "Little Navmap Connect Dialog")

    _**Bild oben:** Verbindungsdialog mit korrekten Werten um auf _Little Navconnect_ zu zugreifen.

3. `Zu einem entfernten Simulator verbinden` auswählen.
4. Hostname oder die IP-Adresse eingeben. Dies kann entweder der Hostname oder die IP-Adresse sein, die von _Little Navconnect_ ausgegeben wurde.
5. Den Port überprüfen. `51968` ist der Standardport und muss in der Regel nicht geändert werden.
6. Auf `Verbinden` klicken. Der Dialog wird geschlossen und _Little Navmap_ wird im Hintergrund versuchen, eine Verbindung aufzubauen, was einige Zeit, abhängig vom Netzwerk, dauern kann. Das Flugzeug wird auf der Karte und im `Simulatorflugzeug` Fenster angezeigt, sobald eine ein Flug geladen ist. Eine Nachricht `Verbunden. Warte auf Aktualisierung` wird im `Simulatorflugzeug` Fenster angezeigt, wenn eine Verbindung besteht aber noch kein Flug geladen ist (z.B. Simulator zeigt noch den Ladebildschirm).

Achtung: Wenn falsche Werte für Hostnamen oder Port verwendet werden, kann es einige Zeit dauern bis ein Fehlermeldung angezeigt wird. 
