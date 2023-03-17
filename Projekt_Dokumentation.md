# Projekt-LF8
von Pascal Wagler, Niklas Wagner, Philipp Müller, Chris Leonhardt, Jonas Reinecke und Henning Löwe 
<hr>

<h2>Phase 1:</h2>
Beschreibung der Geschäftsprozessszenarien des Kunden<br><br>

<p>Im nachfolgenden Dokument haben wir uns zuerst Gedanken darüber gemacht, welche Anforderungen unsere Software hat.<br>
Darauf folgend haben wir uns damit beschäftigt, welche Zielplattformen für unser Programm in Frage kommen.
Zum Abschluss von Phase 1 haben wir ein Use-Case Diagramm (Anwendungsfall-Diagramm) erstellt.</p>

<a href="https://github.com/HenningBSZ/Projekt-LF9/blob/main/Phase%201.pdf">Zum Dokument</a>
<h4>Anwendungsfall-Diagramm</h4>
<a href="https://github.com/HenningBSZ/Projekt-LF9/blob/main/Use-Case-DiagrammV2.drawio.png">Zum Dokument</a>

<br>
<h2>Phase 2:</h2>
Einrichtung der gemeinsamen Dokumentenablage mit git (bzw. bei anderen Vorlieben auch gern einer Alternative)<br><br>

<p>In Phase 2 haben wir uns mit Git beschäftigt und folgende Begriffe:Repository, Remote Repository, Commit, Push, Pull, Clone gelernt.<br>
Anschließend haben wir uns alle ein GitHub-Konto erstellt. Danach haben wir ein Repository eröffnet und alle Datein hochgeladen 
</p>

<a href="https://github.com/HenningBSZ/Projekt-LF9">Zum Repository</a>
<br>
<br>

<h2>Phase 3:</h2>
 Darstellung der zeitlichen Reihenfolge der Tätigkeiten<br><br>

<p>Wir haben ein Sequenz-Diagramm erstellt, welches den Ablauf einer Kundeabfrage dokumentiert und weitere Aufgaben unseres Serviceprozesses darstellt.</p>

<a href="https://github.com/HenningBSZ/Projekt-LF9/blob/main/Sequenzdiagramm.drawio.png">Zum Sequenzdiagramm</a>


<h2>Phase 5:</h2>
Analyse von Datenquellen und der elektronischen Varianten<br><br>


<h2>Phase 6:</h2>
 Erstellung einer Benutzerverwaltung<br><br>

<p>Identifizieren der Nutzer des zukünftigen Software-Systems und dessen Datenbestandes.<br>
Notieren aller für die Nutzer die notwendigen Rechte auf die Datenquellen.<br>
Entscheiden, wie die Nutzerverwaltung praktisch im System umgesetzt werden könnten.</p>

<a href="https://github.com/HenningBSZ/Projekt-LF9/blob/main/Phase%206.pdf">Zum Dokument</a>

<h2>Phase 6:</h2>
 Identifizieren Sie die Nutzer des Systems 
 <p> Kunde 				          schreiben 
     Mitarbeiter         Außendienst 	lesen, schreiben 
     Projekt Planer 			  lesen, schreiben, bearbeiten 
     Lieferant 			       lesen 
     ITSystemhaus DD 		  lesen, schreiben, bearbeiten 


Definieren Sie die Schnittstelle zwischen eigenen Software-Anwendungen und der gewählten Nutzerverwaltung.

Vom Kunden und Lieferanten zur ITSystemhaus DD 	Schnittstelle: 
Webserver, auf den Nutzer öffentlich zugreifen können, um Daten einzugeben und zu versenden.

Von ITSystemhaus DD zum Projekt Planer und Mitarbeiter im Außendienst:
Schnittstelle: Mithilfe eines Datenbankservers können die Projekt Planer und Mitarbeiter im Außendienst die benötigten Daten, welche vom Nutzer eingegeben wurden anzeigen lassen.  

Bei einem Telefongespräch fragt der Kunde nach, ob die Daten im zu erstellenden Software-System auch sicher sind. Der Kunde äußerst Sorgen, dass Hacker oder ein nicht loyaler Mitarbeiter wichtige Unternehmensdaten unbemerkt entwenden können. Sie beruhigen Ihn und stellen Ihm ein Sicherheitskonzept in Aussicht.

Der Datenbankserver, auf dem die Kundendaten gespeichert sind befinden sich in einer entmilitarisierten Zone im privaten Netzwerk. Diese wird durch mindestens eine Firewall abgesichert.Die Mitarbeiter können zwar lesen und schreiben, die Daten können sie jedoch nicht bearbeiten. Bei der Anmeldung an dem Datenbankserver zur Eingabe von Daten wird das Nutzer-Account des Mitarbeiters zur Anmeldung benötigt. Dadurch können unbefugte Zugriffe erkannt und nachverfolgt werden. Die Mitarbeiter können keine Daten aus der Datenbank löschen. Die Daten werden bei einem Versuch der Löschung lediglich nicht mehr angezeigt, sind aber noch vorhanden. Die Daten werden mithilfe von regelmäßigen Backups zusätzlich abgesichert. </p>

