# Open Government Data (OGD) und Statistik in Uster
In der Stadt Uster steht füf statistische Analysen die Statistiksoftware [RStudio](https://de.wikipedia.org/wiki/RStudio) zur Verfügung. Die Software ist Open Source und kann bei der städtischen Informatik kostenlos freigeschalten werden. Applikationsverantwortlicher ist Andreas Wyss.

## Zur Bedeutung von Daten in der öffentlichen Verwaltung
Im Alltag bilden Daten wichtige Grundlagen um gewisse Leistungen überhaupt anbieten resp. erbringen zu können. Im Zuge der Digitalisierung nimmt die Bedeutung von Daten weiter zu. Daten und die Verknüpfung von verschiedenen Datenbeständen können als Grundlage für Entscheidungen dienen oder neue Dienstleistungen ermöglichen.

Die Stadt Uster arbeitet in verschiedenen Systemen mit einer grossen Anzahl an Daten. Aus diesen lassen sich mit geeigneten Mitteln Erkenntnisse gewinnen und nutzbar machen. Auch Onlinedienste sind auf eine guten Datenbasis angewiesen und bauen nicht selten auf diesen auf.

Um Daten einfach nutzen zu können, müssen sie in strukturierter Form vorliegen. Wenn sich Daten strukturiert ablegen lassen, sollte dies daher auch gemacht werden. Damit kann sichergestellt werden, dass sie maschinenlesbar sind oder zumindest mit geringem Aufwand maschinenlesbar gemacht werden können. Beispielsweise sollten Kennzahlen nicht in Word- oder PDF-Dateien zusammengefasst und gespeichert werden, sondern zumindest in einer XLSX-Datei. Ein stärkere Standardisierung bei der bestehenden Ablage von strukturierten Daten (bis hin zu einem verbindlich geregeltem Data Management) wären die weiteren Entwicklungsschritte und dürften langfristig auch in Uster ein Thema werden.

Frei nutzbare Daten fördern Transparenz und Zusammenarbeit. Daten, die in der Verwaltungsarbeit ohnehin anfallen und bearbeitet werden, sollten daher auch der Allgemeinheit zur Verfügung stehen. Über den [kantonalen Katalog für offene Daten](https://www.web.statistik.zh.ch/ogd/datenkatalog/standalone/?keywords=ogd) können Daten einfach zugänglich gemacht werden. Gerne teilen wir mit anderen Verwaltungseinheiten unsere Erfahrungen bei der Publikation von Daten.

## «Community of Practice»
Die Stadt Uster hat kein statistisches Amt. Die einzelnen Verwaltungseinheiten sind für ihre Daten und die Auswertungen selbst verantwortlich. Wir sollten uns daher gegenseitig bei unseren statistischen Vorhaben oder der Publikation von Daten unterstützen. Wer Interesse an Open Data, der Arbeit mit R und RStudio oder sich sonstwie mit Daten beschäftigt, ist eingeladen, mit uns eine «Community of Practice» aufzubauen. Es geht darum, möglichst praxisnahe und einfache Lösungen für den beruflichen Alltag zu finden und das datengestützte Handeln gemeinsam zu fördern.

Unter dem Motto “Wissen teilen statt horten” kann die Zusammenarbeit gefördert und Daten nutzbarer gemacht werden. Daten sollen im Alltag der Verwaltung wie auch für die Bevölkerung einen Mehrwert bieten. Wir sind überzeugt, dass sich das Engagement durch Effizienzsteigerung und gegenseitige Unterstützung betrieblich auszahlt.
Es besteht in MS Teams ein eigenes Team für "Open Data" und eine (diese) gemeinsame GitHub-Organisation. Zudem besteht ein gemeinsame Ablage auf dem S-Laufwerk, um ggf. mit vertraulichen Daten arbeiten zu können. Interessierte sind herzlich eingeladen und erhalten bei Bedarf eine Einleitung in die Funktionsweise der unterschiedlichen Systeme.

## Eine kurze Einführung in R und RStudio
R und RStudio steht als Softwarepaket auf Computer der Stadt Uster zur Verfügung und kann, da es sich um Open Source Software handelt auch auf eigenen Geräten kostenlos installiert werden. Wenn jemand R und RStudio kennenlernen und einsetzen will stehen wir gerne unterstützend zur Seite.

**R** ist eine freie Programmiersprache für statistische Berechnungen und Grafiken. Zahlreiche frei verfügbare Pakete enthalten zusätzliche Funktionen, um Daten zu analysieren, ebenso können eigene Funktionen erstellt werden. R grenzt sich in mehrerer Hinsicht von anderen bekannten Statistik-Umgebungen ab. Es lassen sich damit auch sehr komplexe Aufgaben lösen und automatisieren.

**RStudio** ist eine integrierte Open-Source-Entwicklungsumgebung und grafische Benutzeroberfläche für die Statistik-Programmiersprache R.

## Installation von R und RStudio
* R mit RStudio kann bei der städtischen Informatik kostenlos freigeschalten werden und steht nach dem Neustart auf dem städtischen Computer zur Verfügung. Es ist jedoch nicht über Remote zugänglich.
* Nach der Installation muss unbedingt folgende Anpassung an den Einstellungen vorgenommen werden:  
Global option -> Packages -> *UNCHECK* Use secure download method for HTTP

## R-Package UsteR
Über das R-Package UsteR können diverse Ustermer Datensätze sowie Uster-Spezifische Funktionen genutzt werden. Wenn das R-Package auf einem Computer der Stadt eingesetzt wird, stehen zudem auch einige nicht-öffentliche Daten zur Verfügung. Das Package wird kontinuierlich weiterentwickelt und neue Funktionen und Daten eingebunden. Das Package steht allen städtischen Mitarbeitenden zur Nutzung zur Verfügung: https://github.com/DataStadtUsterZH/UsteR

## Weiterführende Links
* Offizielle R-Webseite: https://www.r-project.org/ 
* Wikipedia über R: https://de.wikipedia.org/wiki/R_(Programmiersprache)#Versionen
* OGD Fachstelle des Kantons: https://www.zh.ch/de/direktion-der-justiz-und-des-innern/statistisches-amt/open-government-data.html
* GitHub-Organisation der Community: https://github.com/DataStadtUsterZH
* Kostenlose Open Source Bücher zur Arbeit mit R: https://bookdown.org/
