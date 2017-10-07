this is the file README.md for db2phpsite - it is written in English and in German / deutsch

# [English summary](#summary-english)
# [Deutsche Zusammenfassung](#summary-german)

# db2phpsite

-----------------------------------------------------
<a name="summary-english"></a>English summary
-----------------------------------------------------

Do you want to move your database to the Web without programming a dedicated application? Do you want to create a Web application without coding? Then you need a database application builder such as db2phpsite. db2phpsite is much more than a form builder: it's a piece of software which makes the creation of PHP online database applications easy and fast.

No coding is required: If you have a MySQL database you can create your first basic CRUDL (Create, Read, Update, Delete, List large data sets) database front-end in minutes.

Moreover the PHP CLI application db2phpsite is highly configurable: You may, but do not need to configure the generation of the code via a script file and you can customize the generated object oriented PHP code (with CSS and Javascript portions) easily in order to build a more sophisticated database application.

## Overview

db2phpsite is a code generator, which analyzes the contents of a database and then creates a web site, which  is based on the data in the database.

db2phpsite produces CRUDL-forms: The data can be created, read, updated, deleted and listed. The forms are written in object-oriented PHP supported by CSS and Javascript shares. Dependign on the data type fitting controls are available to input the data values.

The program supports Master-Detail views. Then it creates record-based and listing-based PDFs, too.

Out of the box there is an user management system included. The users and user groups can be granted view, table and field rights.

The generatd website is able to manage mandatories and accounting areas. Therefore you can deploy it to an institution, which is divided into ancillary institutions.

The generated code runs in a XAMP (LAMP, WAMP etc.consisting of Apache web server, MySQL database and PHP environment ) environment. Therefore it is runnable on any imaginable operating system - may it be Linux, MS Windows or Mac OS/X. The necessary software packages with web server, SQL-database and PHP environment are free of charge and free open source software. They are successfully used on millions of internet platforms, well-maintained and highly efficient.

The clients merely need a web browser to interact with the datbase and the website resides cntrally on a server, which makes the maintainance easy-peasy.

For sure the server and the client can be installed on the same machine for one user, too. But the website will be able to serve hundreds and thousands of users fast in principle. Thus the chosen software components are highly scalable and support the client-server-paradigma,

db2phpsite supports easy internationalizing, too; new language packages can be added easily to your application.

The generated PHP code can be maintained later by a programmer and the changes will be consistent between later runs of db2phpsite. Moreover the output of the program can be configured by a script file via hundreds of options without programming knnowledge.

db2phpsite supports the deveolper by taking lots of detail works, so as to the developer can concentrate on the important things. For example creates db2phpsite in 90 seconds out of a database with 36 tables and 288 fields a website, which consists of 1.700 modules and approximately 60.000 lines of code. In order to produce this amount of code by yourself you would need months.

Other features are the cloning of modules and the ability to add new pages to the website, which are written by the programmer.

Coming soon: This repository is under heavy development yet and will be published about January 2018. 

If you are interested in helping to produce the prototype then you are welcome! We would need 
- PHP and C/C++ Programmers,
- web developers,
- web designers, 
- documentators,
- database specialists,
- translators,
- Testers.

Greets,

Rainer Stötter

-----------------------------------------------------
<a name="summary-german"></a>Deutsche Zusammenfassung
-----------------------------------------------------

Möchten Sie Ihre Datenbank ins Web transportieren, ohne eine dedizierte Anwendung zu programmieren?  Möchten Sie eine internetfähige Applikation ohne Programmieraufwand? Dann benötigen Sie ein Programm, welches Datenbankanwendungen erzeugt wie etwa db2phpsite. db2phpsite ist dabei mehr als ein Formulargenerator: Es ist ein Programm, welches die Erzeugung einer auf PHP basierenden Online-Datenbankapplikation einfach und schnell macht.

Dabei ist kein Programmieraufwand nötig: Wenn Sie eine MySQL Datenbank besitzen, dann können Sie Ihre erste Basisversion eines CRUDL Datenbank-Frontends innerhalb von Minuten bewerkstelligen. CRUDL steht für Create, Read, Update, Delete, List large data sets. Damit soll ausgedrückt werden, dass die Datensätze erzeugt, gelesen, verändert, gelöscht und aufgelistet werden können.

Zudem ist das in PHP geschriebene CLI- ( kommandozeilenorientierte ) Programm db2phpsite hochkonfigurierbar: Sie können, müssen aber nicht, die Erzeugung des Zielcodes über eine Skriptdatei steuern; zudem können Sie den generierten objektorientierten PHP-Code (mit Anteilen in CSS and Javascript) leicht an Ihre Bedürfnisse anpassen, um eine ausgereiftere Datenbankapplikation zu erhalten.

## Überblick

db2phpsite ist ein Codegenerator, welcher die Inhalte einer Datenbank ausliest und dann eine Webpräsenz erzeugt, welche auf den Daten in der Datenbank beruht.

db2phpsite produziert CRUDL-Formulare: Die einzelnen Felder sind alle auflistbar, editierbar, ansehbar, löschbar und neue
Datensätze können hinzugefügt werden. Die Formulare sind objektorientiert aufgebaut in PHP mit CSS und Javascript-Anteilen. Je nach Datentyp kommen entsprechende Steuerelemente für die Eingabe der Daten zum Einsatz.

Master-Detail-Ansichten sind ebenso konfigurierbar wie PDF-Ausdrucke des Listings bzw von einzelnen Datensätzen.

Out of the Box liefert das Programm auch noch eine  Benutzerverwaltung; den Benutzer und Benutzergruppen können Rechte auf Tabellenebene, auf Feldebene oder basierend auf Formularen zugesprochen werden.

Auch ist die erzeugte Website obendrein mandanten- sowie buchungskreisfähig. Also kann etwa eine  Einrichtung, die wiederum untergeordnete Einheiten verwaltet, bedient werden. Die Webpräsenz kann in einer XAMP- ( LAMP, WAMP usw, also Apache Webserver, MySQL-Datenbank und PHP-Umgebung) Umgebung laufen, ist also auf jedem denkbaren Betriebssystem lauffähig - sei es nun
Linux, MS Windows oder OS/X usw. Die nötigen Programmpakete mit Webserver, SQL-Datenbankserver und PHP-Umgebung sind übrigens kostenlos und freie Software und sind auf Millionen von Internetplattformen im Einsatz, gut gewartet und hoch leistungsfähig.

Die Klienten benötigen nur einen Webbrowser zur Bedienung und die Webpräsenz lagert zentral auf einem Server, so dass die Wartung ein Kinderspiel ist.

Natürlich können Server und Client auch auf einer einzelnen Maschine für den Einbenutzerbetrieb installiert sein. Doch ist die Webpräsenz prinzipiell dazu in der Lage, hunderte und tausende Benutzer schnell zu bedienen, ohne dass Änderungen am
Programm erforderlich wären. Die verwendeten Programmkomponenten sind also hoch skalierbar und sie unterstützen voll die Client-Server-Technik.

db2phpsite unterstützt auch die Internationalisierung: Neue Sprachpakete können Ihrer Webapplikation leicht hinzugefügt werden.

Der generierte PHP-Code kann vom Anwender nachträglich verändert werden und diese Änderungen bleiben auch bei neuen Programmläufen erhalten. Zudem ist das Programm über hunderte von Parametern hochkonfigurierbar über eine steuernde Datei , ohne dass zusätzliche Programmierarbeit zu leisten ist.

db2phpsite nimmt dem Entwickler sehr viele Detailarbeiten ab, so dass er sich dann auf das Wesentliche konzentrieren kann. Zum Beispiel erzeugt db2phpsite derzeit in eineinhalb Minuten aus einer Datenbank mit 288 Felder in 36 Tabellen eine Webpräsenz, die aus 1.703 einzelnen Modulen besteht, die wiederum insgesamt etwa 60.000 Zeilen umfassen. Um das eigenhändig auszuprogrammieren wären sicher einige Monate an Arbeit nötig.

Weitere Features sind etwa das Klonen von Modulen oder aber das Hinzufügen von Modulen, die nur vom Programmierer geschriebenen Code enthalten.

Coming soon: Dieses Repository befindet sich derzeit in Entwicklung und soll etwa ab Januar 2018 erhältlich sein. 

Wenn Sie Interesse daran haben, an der Erstellung des Prototypen mitzuwirken, dann sind Sie dazu herzlich willkommen! Wir benötigen unter anderem 
- PHP and C/C++ Programmierer,
- Web-Entwickler, 
- Web-Designer, 
- Dokumentatoren ,
- Datenbankspezialisten,
- Übersetzer,
- Tester.

Herzliche Grüße

Rainer Stötter


