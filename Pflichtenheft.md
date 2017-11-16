## Pflichtenheft


### Allgemeine Beschreibung des Projekts

Community-Plattform für Computerspiele

### Navigationsleiste
Die Navigationsleiste ist allen anderen Objekten übergeordnet. Sie wird also über jedem Objekt dargestellt.
Sie beinhaltet die wichtigsten Verweise. Ein Verweis auf die Registrierung, Anmeldung oder Abmeldung.
Ihr Inhalt der Navigationsleiste lautet wie folgt:
* Logo der Plattform (Verweis auf die Startseite)
* Terminplaner
* Spielebibliothek
* Gruppen/Freunde (Community)
* Registrierung und Anmeldung oder Abmeldung  
<img src="./images/Navigation.png" width="400"><img src="./images/Navigation_Mobile.png" width="400">

### Registrierung
Jede Person kann sich registrieren, egal ob über die Web-Anwendung, Desktop-Anwendung oder Mobile-Anwendung.
Für die Registration muss man einen noch nicht vergebenen Benutzernamen, eine noch nicht verwendete E-Mail und ein Passwort angeben.
Das Passwort muss wiederholt werden um Schreibfehler vorzubeugen.  
<img src="./images/Registration_Web.png" width="340"> <img src="./images/Registration_Desktop.png" width="320"> <img src="./images/Registration_Mobile.png" width="180">

### Anmeldung
Jede Person die sich erfolgreich registriert hat, kann sich anmelden.
Um sich anzumelden, muss eine korrekte Eingabe von Benutzername und Passwort getätigt werden.
<img src="./images/Login_Web.png" width="340"> <img src="./images/Login_Desktop.png" width="350"> <img src="./images/Login_Mobile.png" width="180">

### Spielebibliothek
In der Spielebibliothek werden alle verfügbaren (gekauften) Spiele angezeigt.
Diese können dann aus der Spielebibliothek gestartet werden.
Spiele können über ein Menü der Bibliothek hinzugefügt werden. Für jedes Spiel wird eine Beschreibung,
eine Bewertung und die Benutzer angezeigt, welche im Moment dieses Spiel spielen und somit auch besitzen müssen.  
<img src="./images/Library_Web2.png" width="400"> <img src="./images/Library_Desktop.png" width="380">

### User-Stories

| Rolle        | In meiner Rolle möchte ich                      | so dass                                            | Akzeptanz                                                                   | Priorität  |
|--------------|-------------------------------------------------|----------------------------------------------------|-----------------------------------------------------------------------------|------------|
| Als Benutzer | meine gekauften Spiele sehen                    | ich auf einen Blick sehe welche Spiele ich besitze | In der Spielebibliothek werden 0-n gekaufte Spiele angezeigt.               | 1 – Must   |
| Als Benutzer | meine Spiele auswählen                          | ich erweiterte Informationen zum Spiel bekomme     | Bei Auswahl eines Spiels wird eine erweiterte Ansicht angezeigt             | 1 – Must   |
| Als Benutzer | meine Spiele starten                            | ich meine Spiele spielen kann                      | Startbutton wird in der erweiterten Ansicht angezeigt                       | 1 – Must   |
| Als Benutzer | gekaufte Spiele einlösen                        | ich sie meiner Bibliothek hinzuzufügen             | es einen Menüpunkt gibt, mit dem man Spiele aktivieren kann                 | 1 – Must   |
| Als Benutzer | wissen wer das aktuell ausgewählte Spiel spielt | ich das Spiel gemeinsam mit Freunden spielen kann  | bei jedem Spiel werden 0-n Freunde angezeigt, die das Spiel aktuell spielen | 2 – Should |
| Als Benutzer | die Beschreibung lesen                          | ich weiß worum es in dem Spiel geht                | eine Beschreibung angezeigt wird                                            | 3 – Could  |

### Bewertungsfunktion
Die Bewertungsfunktion (Verweis / Bewertungssterne) wird bei jedem Spiel angezeigt.
Jeder Benutzer kann sie individuell ausfüllen, falls er das dazugehörige Spiel besitzt.
Allerdings kann jedes Spiel nur einmal pro Benutzer bewertet werden.
Jeder Benutzer kann zu seiner Bewertung von einem bis zu fünf Sternen einen kleinen Text verfassen,
indem er seine Meinung zum entsprechenden Spiel schreibt.
Andere Benutzer sehen bei jedem Spiel, die Bewertungen jener Benutzer,
die das Spiel bewertet haben und können diese Bewertungen mit einem Daumen hoch oder runter ebenfalls bewerten.  
Mit einem Daumen nach oben bewertet man das Spiel positiv, mit einem Daumen nach unten negativ.
<img src="./images/Review_Web.png" width="300"> <img src="./images/Review_Desktop.png" width="336"> <img src="./images/Review_Mobile.png" width="230">

### Gruppen
Jeder angemeldete Benutzer kann eine Gruppe erstellen. Gruppen dienen zur Organisation von Freunden und Freundesfreunden. Um eine Gruppe zu erstellen braucht man nicht zwingend Freunde in der Kontaktliste; Da man die Option hat, die Gruppe auf "Öffentlich" zu stellen, sodass jeder Benutzer beitreten kann.
Stellt man die Gruppe auf "Privat" können nur Mitglieder beitreten, die von einem berechtigten Mitglied der Gruppe eingeladen werden.
Der Admin kann an die Mitglieder Rollen verteilen, die jeweils verschiedene Rechte haben. Mit diesen Rechten kann man Mitglieder einladen bzw. rauswerfen, die Beschreibung der Gruppe ändern oder Foren erstellen und bearbeiten.
Den Mitgliedern einer Gruppe ist es möglich sich in einem Forum zu organisieren.
In diesem Forum können verschiedene Obertabs erstellt werden und in diesen Beiträge verfasst werden. Ein Obertab kann nur von einem Mitglied erstellt werden, der Forumrechte hat. Mitglieder ohne diese Rechte können nur in den Oberthemen Unterthemen erstellen.
Beiträge können als gelesen und ungelesen markiert werden. Ein Beitrag ist ungelesen, wenn er neu erstellt wurde oder ein oder mehrere neue Kommentare hinzugefügt wurden. Der Benutzer kann sie über eine Schaltfläche als gelesen markieren oder den Beitrag öffnen, damit er als ungelesen markiert wird.  
Bei jedem Beitrag gibt es eine Kommentarfunktion, wo sich die Mitglieder zu dem Thema austauschen können.
Außerdem können Gruppen Termine zu verschiedenen Anlässe erstellen im Terminplaner.
Auf der Mobilenansicht wird in der Mitgliederliste der aktuelle Status der Mitglieder über einen farbigen Punkt dargestellt. Jede Farbe steht dabei für eine Aktivität: Grün - Online, Gelb - Abwesen, Rot - Offline, Blau - Im Spiel

<img src="./images/Groups_Profile_Desktop.png" width="280">
<img src="./images/Groups_Profile_Web.png" width="280">
<img src="./images/Groups_Profile_Mobile.png" width="280">
<br>
<img src="./images/Groups_Forum_Desktop.png" width="280">
<img src="./images/Groups_Forum_Web.png" width="280">
<img src="./images/Groups_Forum_Mobile.png" width="280">
<br>
<img src="./images/Groups_Forum_Post_Desktop.png" width="280">
<img src="./images/Groups_Forum_Post_Web.png" width="280">
<img src="./images/Groups_Forum_Post_Mobile.png" width="280">
<br>
<img src="./images/Groups_Members_MemberView_Desktop.png" width="280">
<img src="./images/Groups_Members_MemberView_Web.png" width="280">
<img src="./images/Groups_Members_MemberView_Mobile.png" width="280">
<br>
<img src="./images/Groups_Members_AdminView_Desktop.png" width="280">
<img src="./images/Groups_Members_AdminView_Web.png" width="280">
<img src="./images/Groups_Members_AdminView_Mobile.png" width="280">

### Gruppenrollen
| Name | Vergabe | Rechte |
|:------------|:------------|:------------|
| Ersteller | Beim Erstellen der Gruppe | Alle |
| Admin | Vergabe durch Admin oder Ersteller | Rechte des Foren-Admins + Einladen, Ausladen von Mitgliedern, Ernennung von anderen Admins |
| Foren-Admin | Vergabe durch Admin oder Ersteller | Rechte eines Mitglieds + Bearbeitung des Forums |
| Mitglied | Beim Beitritt in die Gruppe | Schreiben von Beiträgen, Erstellen von Terminen, Erstellen von Notizen |

### User-Stories

| Rolle | In meiner Rolle möchte ich | so dass | Akzeptanz | Priorität |
|-------|----------------------------|---------|-----------|-----------|
| Als Benutzer | Gruppen erstellen | ich Freunde zur Gruppe hinzufügen kann | Erzeugung der Gruppe | MUSS |
| Als Benutzer | Gruppen öffentlichen Gruppen beitreten oder Gruppeneinladungen Akzeptieren | ich mit der Gruppe Kommunizieren und an Terminen teilnehmen kann | Man sieht sich selbst in und die Inhalte der Gruppe | MUSS |
| Als Benutzer | Chats der Gruppe beitreten | ich mit anderen Gruppenmitgliedern reden kann | Aktiver Chat mit Gruppenmitgliedern | MUSS |
| Als Gruppenadmin | die Sichtbarkeit der Gruppe ändern | sie Öffentlich oder Privat ist |  | MUSS |
| Als Gruppenadmin | Rollen erstellen und diese verteilen können | ausgewählte Gruppenmitglieder besondere Rechte haben |  | MUSS |
| Als Gruppenadmin/Benutzer mit der Rolle | Obertabs in den Foren erstellen | Diskussionen im Forum geordneter sind | sichtbare Oberthemen im Forum | MUSS |
| Als Gruppenmitglied | Unterthemen im Forum erstellen | Diskussionen angeregt werden | sichtbare Unterthemen im Forum | MUSS |
| Als Gruppenmitglied | meine Unterthemen als gelesen und ungelesen markieren | erkannt wird, ob alles gelesen wurde oder nicht | Themen sind markiert als gelesen oder ungelesen | MUSS |
| Als Gruppenmitglied | meine Kommentare and Unterthemen senden | jeder meine Meinung zum Thema sehen kann | Kommentar wird im Unterthema angezeigt | MUSS |
| Als Mobilnutzer | die Aktivität anderer Gruppenmitglieder sehen | ich weiß ob sie gerade anwesend sind oder nicht | Benutzer sind in der Mitgliederliste mit Punkten markiert | MUSS |

### Chaträume
Es wird zwischen Privatchat-, Gruppenchat- und öffentlichen Chaträumen unterschieden. In den Chaträumen stehen Emojis zur Verfügung. Hyperlinks müssen anklickbar sein. Beim Senden einer Textnachricht wird zuerst der Benutzername und dann die Textnachricht, getrennt mit einem ":", angezeigt.
Man kann Privatchats über einen Doppelklick auf den jeweiligen Kontakt öffnen. Öffentliche Chaträume können erstellt und mit Passwörtern versehen werden. Jeder öffentlicher Chatraum muss einen einzigartigen Namen haben. Es steht eine Liste mit aktiven in den Chat beigetretenen Benutzern zur Verfügung. Über diese Liste können Benutzer zu den Kontakten hinzugefügt werden. Benutzer können Stumm geschaltet werden.
Über die Gruppenliste kommt man per Doppelklick in den Gruppenchat. Rechts des Gruppenchats wird eine Liste mit den Mitgliedern angezeigt.
Um eine bessere Übersicht in den Notizen zu haben, falls man mehrere Mitarbeiter hat, kann man sich eine Farbe auswählen. Mit dieser Farbe wird der vom Benutzer geschriebene Text hinterlegt. Jede Farbe kann dabei nur von einem Benutzer verwendet werden um Verwechslungen zu vermeiden.
<br>
<img src="./images/Chaträume_Desktop.png" width="280">
<img src="./images/Chaträume_Browser.png" width="280">
<img src="./images/Chaträume_Mobile.png" width="280">
<br>
<img src="./images/Öffentlicher&Gruppen_Chatraum_Desktop.png" width="280">
<img src="./images/Öffentlicher&Gruppen_Chatraum_Browser.png" width="280">
<img src="./images/Öffentlicher&Gruppen_Chatraum_Mobile.png" width="280">
<br>
<img src="./images/Privatchat_Desktop.png" width="280">
<img src="./images/Privatchat_Browser.png" width="280">
<img src="./images/Privatchat_Mobile.png" width="280">


### Freundesliste
Es gibt die Tabs "Freunde" und "Gruppen". In dem Tab "Freunde" werden die Freunde des jeweiligen Benutzers aufgelistet und in dem "Gruppen" Tab die Gruppen. Es können Freunde hinzufügt und gelöscht werden. Diese Freunde werden dann mit einem Status angezeigt. Der Status kann zwischen Online, Offline, Beschäftigt und Abwesend, die jeweils mit einer Farbe makiert sind, variieren. Außerdem bekommt man angezeigt, in welchem Chatraum bzw. Spiel sie sich gerade befinden. Es sind ebenfalls Funktionen zum Öffnen eines Privatchats, Löschen des Freundes, Hinzufügen des Freundes und zum Wechseln des Status vorhanden. Das Anzeigen des derzeitigen Spiels/Chatraums erfolgt automatisch. Es können Gruppen erstellt und gelöscht werden. Man kann Gruppe beitreten und sie verlassen. Andere Kontakte können in Gruppen eingeladen werden.<br>
<img src="./images/Freundesliste_Desktop.png" width="280">
<img src="./images/Freundesliste_Browser.png" width="280">
<img src="./images/Freundesliste_Mobile.png" width="280">

### Terminplaner

#### Beschreibung

Im Terminplaner soll es für den Benutzer möglich seine Termine einzutragen und auch wieder zu bearbeiten. Das bearbeiten geschieht durch drücken des Sclüssel Symbols neben dem Termin. Diese Termine können für den Benutzer selber sein oder auch für eine ganze Gruppe in der Anwendung. Wenn der Benutzer sich dafür entscheidet ein Termin für eine Gruppe zu planen, können andere für den Termin abstimmen und somit zeigen, dass sie an  dem Tag Zeit haben oder für den Termin absagen. Außerdem wird ein Gruppenmitglied zeitnah benachrichtigt, wenn eine Veranstaltung ansteht. Zur Übersicht werden die Termine in einem Kalender dargestellt, indem man auch an einem bestimmten Tag ein Termin eintragen kann. Neben dem ausgewählten Datum wird angezeigt welche Termine für dieses Datum anstehen. Tage an denen es Termine gibt, werden markiert. Beim hinzufügen, kann man den Terminnamen, die Terminbeschreibung und die Beschränkungen festlegen. Der Termin ersteller kann Leute zuweisen, welche diesen Termin sehen und eventuell auch bei dem Termin beteiligt sind. Die Teilnehmer werden in einer Liste angzeigt und können dort auch hinzugefügt werden. Dann werden sie in der Liste als hinzugefügt markiert und können auch wieder aus dem Termin entfernt werden, wenn nötig.

#### Mockups

<img src="./images/Terminplaner Web.png" width="450"><img src="./images/Terminplaner hinzufügen Web.png" width="450">
<img src="./images/Terminplaner Desktop.png" width="550"><img src="./images/Terminplaner hinzufügen Desktop.png" width="330">
<img src="./images/Terminplaner Mobil.png" width="550"><img src="./images/Terminplaner hinzufügen Mobil.png" width="330">

#### User-Stories

| Rolle | In meiner Rolle möchte ich | so dass | Akzeptanz | Priorität |
|-------|----------------------------|---------|-----------|-----------|
| Als Benutzer | möchte ich Termine anlegen, | so dass ich sehe, wann ich verplant bin. | Die Termine werden im Kalendar farblich markiert. | MUSS |
| Als Benutzer | möchte ich meine Termine mit Freunden teilen und ebenso deren geteilten Termine mit mir sehen, | so dass ich mich mit meinen Freunden verabreden kann und sie sehen wann ich verplant bin. || MUSS |
| Als Benutzer | möchte ich detaillierte Beschreibung von Terminen bestimmten Daten sehen, | so dass ich sehe, welche Termine an bestimmten Tagen anliegen.|| MUSS |
| Als Gruppen-Admin| möchte ich Termine mit Gruppen teilen, | so dass meine Gruppe sieht, wie unser Spielplan ist. || MUSS |
| Als Gruppenmitglied | möchte ich die Termine meiner Gruppe sehen, | so dass ich sehe, wann meine Gruppe Termine zum Spielen geplant hat. | Die Termine sollen im Kalendar farblich markiert werden | MUSS |
| Als Gruppen-Admin/Gruppenmitglied | möchte ich sehen, welche Gruppenmitglieder an einem Termin teilnehmen und welche nicht, | so dass ich sehe wer mitmachen wird.|| MUSS |


### Notizen
Dem Benutzer ist es möglich Notizen anzulegen. Diese kann er außerdem mit anderen Benutzern oder Gruppen teilen. Die Notizen können dadurch angeguckt oder von anderen bearbeitet werden. Der Notizenersteller, kann aber auch festlegen, wer diese Notiz bearbeiten darf. Die Notizen können dann auch den Benutzer oder die Benutzergruppe über festgelegte Zeit benachrichtigen.<br>
Zur besseren Übersicht der Notiz werden die Beiträge eines Mitgliedes in einer Farbe hinterlegt, welche man über eine Farbauswahl auswählen kann. Jede Farbe kann nur von einem Mitglied benutzt werden um Verwechslung zu vermeiden.

<img src="./images/Notizen_Web.png" width="280"> <img src="./images/Notizen_Desktop.png" width="280"> <img src="./images/Notizen_Mobile.png" width="200">

#### User-Stories
| Rolle | In meiner Rolle möchte ich | so dass | Akzeptanz | Priorität |
|-------|----------------------------|---------|-----------|-----------|
|Als Benutzer|möchte ich Notizen anlegen|so dass ich wichtige Informationen immer im Blick habe.||MUSS|
|Als Benutzer|möchte ich vorhandene Notizen bearbeiten|so dass ich bei kleinen Änderungen keine neue Notiz anlegen muss.||MUSS|
|Als Benutzer|möchte ich Notizen einen Titel geben|so dass ich meine Notizen auseinanderhalten kann.|Der Titel soll über der eigentlichen Notiz dauerhaft angezeigt werden.|MUSS|
|Als Benutzer|möchte ich unter meinen verschiedenen Notizen auswählen|so dass ich aussuchen kann, welche ich einsehen will.|Die Notizen werden nur in Form ihrer Titel aufgelistet um daraus auswählen zu können.|SOLL|
|Als Notizenersteller|möchte ich meine Notizen mit anderen Nutzern oder ganzen Gruppen teilen|so dass andere meine Notizen sehen können.|Mitglieder werden neben der eigentlichen Notiz aufgeführt.|MUSS|
|Als Notizenersteller|möchte ich Mitgliedern die Bearbeitung der Notiz erlauben|so dass auch andere Personen Informationen zu der Notiz beitragen können.|Der von einem Nutzer verfasste Text soll mit einer Nutzerspezifischen Farbe hinterlegt werden.|SOLL|
|Als Mitglied|möchte ich die Farbe mit der mein Text hinterlegt ist auswählen|so dass ich die Verfasser der Textabschnitte unterscheiden kann.|Jede Farbe soll nur einmal vorkommen um Verwechslung vorzubeugen.|SOLL|

### Frontend
 **Clientbeschreibungen für ProjectZero**

#### Webclient
**Responsiver Webclient mit PHP, CSS, JavaScript**

| Framework | Sprache
|:------------ |:--------- |
| Laravel | PHP |
| Bootstrap | CSS |
| Angular 4 | JavaScript |


#### Mobilclient für Android und iOS
**Ionic Framework basierend auf HTML5 und AngularJS**

| Framework | Sprache
|:------------ |:--------- |
| Ionic | HTML5, AngularJS |


#### Desktop-Client für Windows
**Desktopanwendung geschrieben in C#**

### Backend

#### Server:
Ein Webserver wird für die Backend-Applikation benötigt.
Der Server benötigt mindestens diese Anforderungen, da Laravel als Backend für das Projekt benutzt wird.
Laravel ist ein PHP-Framework, welches als eine RESTful-API-Lösung benutzt wird, um die Client Anfragen zu verarbeiten und mit der Datenbank kommuniziert.

https://laravel.com/

##### Server Anforderung:

##### System:
* PHP >= 7.0.0
* OpenSSL PHP Extension
* PDO PHP Extension
* Mbstring PHP Extension
* Tokenizer PHP Extension
* XML PHP Extension

##### Software:
* Nginx oder Appache
* Composer
* Datenbank (MySQL)
* Node
* Git

#### Datenbank:
Die Datenbank kann auch in Laravel aufgebaut werden. Dafür können Migrations verwendet werden.

>Migrations are like version control for your database, allowing your team to easily modify and share the application's database schema. Migrations are
>typically paired with Laravel's schema builder to easily build your application's database schema. If you have ever had to tell a teammate to manually
>add a column to their local database schema, you've faced the problem that database migrations solve.

[Quelle](https://laravel.com/docs/5.5/migrations)

#### Systemarchitekturdiagramm

<img src="./images/Systemarchitekturdiagramm.png" width="600">


### Optionale Features
* Forum
* Shop
* Blog

### Glossar
Unser Stichwort- bzw. Begriffsverzeichnis mit Definition und Beschreibungen ebendieser.

#### Account
Ein Account ist ein Benutzerkonto, dass den Benutzer auf unserer Community-Plattform authentifiziert und autorisiert verschiedene Rollen einzunehmen.
Dieser besteht aus Benutzername, Passwort sowie E-Mail-Adresse.

#### Backend
Die logische Teil unseres Projektes. Dieser beinhaltet die Server-Applikation, die Datenbank und die Server-Hardware.

#### Benutzer
Person, die auf der Community-Plattform mindestens einen Account besitzt.

#### Benutzername
Anzeigename, den der Benutzer, bei seiner Registrierung gewählt hat. Dieser Name ist öffentlich d.h. für alle Benutzer sichtbar. Der Benutzername des Accounts darf sich aus drei bis 16 Schriftzeichen zusammensetzen. Zu den erlaubten Schriftzeichen gehören Klein- und Großbuchstaben des lateinischen Alphabets von A bis Z, die deutschen Umlaute "Ä", "Ö" und "Ü" sowie die Ziffern von 0 bis 9. Sonderzeichen und Symbole sind nicht zugelassen.

#### Bewertung
Benutzer können zu Spielen, in deren Besitz, eine individuelle Beurteilung verfassen. Jeder Benutzer darf pro Spiel maximal eine Bewertung abgeben. Diese Bewertung besteht aus einer Benotung aus Sternen von eins bis fünf (von schlecht bis sehr gut) und einem optionalen Bewertungstext aus maximal 1000 Zeichen, in dem sich die Meinung des Benutzers zum entsprechenden Computerspiel widerspiegelt. Zudem können Benutzer die Bewertungen anderer Benutzer positiv bzw. negativ bewerten. Die durchschnittliche Bewertung gibt das Mittel aus allen abgegebenen Bewertungen wider.

#### Blog
Ankündigungen über Neuigkeiten und Änderungen werden hier veröffentlicht.

#### Chat
Digitale Textnachrichtenkommunikation zwischen den Benutzern über die Community-Plattform.

#### Chatraum(e)
Fenster, um mit diversen Benutzern/Benutzergruppen Nachrichten auszutauschen. Die Aufteilung erfolgt in privaten, Gruppen- und öffentlichen Chats.

#### Community
Bezeichnet die Menge aller Accounts unserer Community-Plattform für Computerspiele.

#### Datenbank
Speicherstruktur, welche alle Benutzeranmeldedaten (Accounts) enthält.

#### Forum
Moderierte Plattform, um sich innerhalb der Community über diverse Themen auszutauschen.
Jeder angemeldete Benutzer darf Themen erstellen.

#### Freund(e)
Benutzer, die der angemeldete Benutzer zu seiner Freundeliste hinzugefügt hat.

#### Freundeliste
Liste aller Benutzer, die als Freund hinzugefügt wurden.

#### Frontend
Der visuelle Teil unseres Projektes. Die für jeden Benutzer sichtbare graphische Oberfläche (GUI), in Form der Desktop-Applikation für Desktop-Betriebssysteme, Mobile-Applikation für Smartphone-Betriebssysteme sowie der Web-Oberfläche, die plattformunabhängig verwendet werden kann. Dieser läuft auf der Client-Hardware der Benutzer.

#### Gruppe(n)
Zusammenschluss von mindestens zwei verschiedenen Benutzern, um bspw. zusammen zu chatten oder ein Computerspiel zu spielen. Die maximale Gruppengröße liegt derzeit bei 100 Benutzern.

#### Gruppenrolle(n) bzw. Rolle(n)
Benutzer haben verschiedene Rechte innerhalb einer Gruppe, die anhand der Rollen "Ersteller", "Admin", "Foren-Admin" und "Mitglied" autorisiert werden.

#### Navigationsleiste
Oberste Leiste, die den Benutzerstatus und die wichtigsten Funktionen enthält.

#### Objekt(e)
Auswählbare funktionale Elemente unsere Benutzeroberfläche.

#### Passwort
Zeichenfolge zur Authentifizierung, die der Benutzer, bei seiner Registrierung gewählt hat. Das Passwort des Accounts darf sich aus acht bis 32 Schriftzeichen zusammensetzen. Zu den erlaubten Schriftzeichen gehören Klein- und Großbuchstaben des lateinischen Alphabets von A bis Z, die deutschen Umlaute "Ä", "Ö" und "Ü", die Ziffern von 0 bis 9 sowie die üblichen Sonderzeichen "ß", "?", "!", ".", ",", "#", "@", "*", "&", "$", "€". Weitere Sonderzeichen und Symbole sind nicht zugelassen.

#### ProjectZero
Codename unseres Gruppenprojektes, welches eine Community-Plattform für Computerspiele wird.

#### Registrierung
Erstellung eines Accounts, um ein Benutzer der Community-Plattform zu werden.

#### Shop
Fenster, um PC-Spiele, Zusatzinhalte für PC-Spiele (DLC & Add-On), Lootboxen für PC-Spiele sowie Mods (Spielemodifikationen) kostenlos und kostenpflichtig zu erwerben.

#### Software
Zur Entwicklung des Projektes verwendete Anwendungen.

#### Software-System
Die Bezeichnung, für die komplette Software inklusive Server-Anwendung, Client-Anwendung sowie Dokumentation.

#### Spielebibliothek
Fenster, das alle Spiele im Besitz des jeweiligen Benutzers anzeigt.

#### Termin
Eintrag und Erinnerung an eine Veranstaltung oder Ereignis, das öffentlich, in der Gruppe oder nur privat einsehbar ist. Der Benutzer kann einem Termin zu- oder absagen.

#### Terminplaner
Kalender, der Termine für sämtliche Veranstaltungen und Ereignisse enthält. Dazu zählen öffentliche, Gruppen- und persönliche bzw. private Termine.

**Fehlende Einträge, sowie Rollenverteilung werden hinzugefügt, sobald es zur Entwicklung kommt.**
