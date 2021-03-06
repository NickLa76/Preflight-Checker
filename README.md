Beispielanwendung "CarManufacture"
=========================

Kurzbeschreibung
----------------

Dies ist ein Beispiel für eine in Java realisierte, serverseitige MVC-Webanwendung.
Die Anwendung setzt dabei ganz klassisch auf der „Jakarta Enterprise Edition”
(ehemals „Java Enterprise Edition“) auf und läuft daher in einem speziell dafür
ausgelegten Applikationsserver. Sämtliche Anwendungslogik wird dabei vom Server
implementiert, so dass für jedes URL-Pattern der Anwendung ein komplett serverseitig
generierte HTML-Seite abgerufen und im Browser dargestellt wird. 
Die Anwendung wurde für die Automobilbranche erstellt, hiermit wird es den Automobilhersttelern ermöglicht die Fertigung mit Hilfe eines intelligenten Dashboards zu steuern.


Verwendete Technologien
-----------------------

Die App nutzt Maven als Build-Werkzeug und zur Paketverwaltung. Auf diese Weise
werden die für Jakarta EE notwendigen APIs, darüber hinaus aber keine weiteren
Abhängigkeiten, in das Projekt eingebunden. Der Quellcode der Anwendung ist dabei
wie folgt strukturiert:

 * **Servlets** dienen als Controller-Schicht und empfangen sämtliche HTTP-Anfragen.
 * **Enterprise Java Beans** dienen als Model-Schicht und kapseln die fachliche Anwendungslogik.
 * **Persistence Entities** modellieren das Datenmodell und werden für sämtliche Datenbankzugriffe genutzt.
 * **Java Server Pages** sowie verschiedene statische Dateien bilden die View und generieren den
   auf dem Bildschirm angezeigten HTML-Code.

Folgende Entwicklungswerkzeuge kommen dabei zum Einsatz:

 * [NetBeans:](https://netbeans.apache.org/) Integrierte Entwicklungsumgebung für Java und andere Sprachen
 * [Maven:](https://maven.apache.org/) Build-Werkzeug und Verwaltung von Abhängigkeiten
 * [Git:](https://git-scm.com/") Versionsverwaltung zur gemeinsamen Arbeit am Quellcode
 * [TomEE:](https://tomee.apache.org/) Applikationsserver zum lokalen Testen der Anwendung
 * [Derby:](https://db.apache.org/derby/) In Java implementierte SQL-Datenbank zum Testen der Anwendung
 
 Hinweis zur Ausführung des SOAP-Webservices:
 Nachdem das eigentliche Projekt CarManufacture geöffnet wurde muss nun noch das SOAP-Projekt geöffnet werden dies lässt sich als separates Project in NetBeans öffnen.

Screenshots
-----------

<table style="max-width: 100%;">
    <tr>
        <td>
            <a href="Login.png">
                <img src="Login.png" style="display: block; width: 100%;" />
            </a>
        </td>
        <td>
            <a href="Registrierung.png">
                <img src="Registrierung.png" style="display: block; width: 100%;" />
            </a>
        </td>
    </tr>
    <tr>
        <td>
            Login
        </td>
        <td>
            Registrierung
        </td>
    </tr>
</table>

<table style="max-width: 100%;">
    <tr>
        <td>
            <a href="Dashboard.png">
                <img src="Dashboard.png" style="display: block; width: 100%;" />
            </a>
        </td>
        <td>
            <a href="Liste_Bestellungen.png">
                <img src="Liste_Bestellungen.png" style="display: block; width: 100%;" />
            </a>
        </td>
    </tr>
    <tr>
        <td>
            Dashboard
        </td>
        <td>
            Liste mit Bestellungen
        </td>
    </tr>
</table>

<table style="max-width: 100%;">
    <tr>
        <td>
            <a href="BestellungBearbeiten.png">
                <img src="BestellungBearbeiten.png" style="display: block; width: 100%;" />
            </a>
        </td>
        <td>
            <a href="Fahrzeugkategorie.png">
                <img src="Fahrzeugkategorie.png" style="display: block; width: 100%;" />
            </a>
        </td>
    </tr>
    <tr>
        <td>
            Bestellung bearbeiten
        </td>
        <td>
            Kategorien bearbeiten
        </td>
    </tr>
</table>

<table style="max-width: 100%;">
    <tr>
        <td>
            <a href="MeinProfil.png">
                <img src="MeinProfil.png" style="display: block; width: 100%;" />
            </a>
        </td>
        <td>
            <a href="ProfilBearbeiten.png">
                <img src="ProfilBearbeiten.png" style="display: block; width: 100%;" />
            </a>
        </td>
    </tr>
    <tr>
        <td>
            MeinProfil
        </td>
        <td>
            Profil Bearbeiten
        </td>
    </tr>
</table>
Copyright
---------

Dieses Projekt ist lizenziert unter
[_Creative Commons Namensnennung 4.0 International_](http://creativecommons.org/licenses/by/4.0/)

© 2018 – 2019 Nick Lampert, Justin Deurer <br/>

E-Mail: [lampert.nick@student.dhbw-karlsruhe.de](mailto:lampert.nick@student.dhbw-karlsruhe.de) <br/>
Webseite: https://www.wir-haben-keine-webseite.de
