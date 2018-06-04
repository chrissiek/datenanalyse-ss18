# Bericht zur Einheit 3

## Partei: FP�
## Bezirk: Hartberg-F�rstenfeld

### Skalierungsniveaus:

* gkz = Nominalskala
* wahlberechtigt = Verh�ltnisskala
* abgegenen = Verh�lnisskala
* ung�ltig = Verh�ltnisskala
* Partien = Verh�lnisskala
* Altersgruppen = Verh�lnisskala
* Personen / Haushalt = Verh�ltnisskala
* Nationalit�t = Verh�lnisskala

__Zusammenfassung:__ Es handelt sich (mit Au�nahme der gkz) um
Verh�lnissskalen, da alle rechnerischen Operationen ausgef�hrt
werden k�nnen und es sich um quantitative Daten handelt.


### Korrektheit und Vollst�ndigkeit des Datensatzes:

#### Pr�fung auf Korrektheit anhand von Summenformel im Libre und Vergleichen mit
der Gesamtanzahl im Bezirk:

* Wahlberechtigte: korrekt
* abgegeben: Gesamtzahl (61757) weicht von Summe (54484) ab
* ung�ltig: Gesamtzahl (609) weicht von Summe (565) ab
* g�ltig: Gesamtzahl (61148) weicht von Summe (53919) ab
* sp�: Gesamtzahl (10178) weicht von Summe (8796) ab
* �vp: Gesamtzahl (24319) weicht von Summe (21520) ab
* fp�: Gesamtzahl (20766) weicht von Summe (18792) ab
* gr�ne: Gesamtzahl (1132) weicht von Summe (850) ab

__Zusammenfassung:__ Die zusammengerechneten Summenergebnisse der g�ltigen und ung�ltigen Stimmen 
ergeben allerdings die korrekte Gesamtzahl der abgegebenen Stimmen. Dies beruft
sich auf die Briefwahlstimmen.

#### Pr�fung auf Gesamtheit des Datensatzes:

Es werden zum Beispiel nicht alle Parteien angegeben, die zur Wahl
angetreten sind. Es fehlen: Liste Gilt, Liste Pilz, KP�, Wei�e, FL�, NBZ, ODP,
SLP, EUAUS, CP�, M, Neos;


### Interpretation der Metriken der Gesamtsteiermark:

* Wahlberechtigte: min = vieviel der Minimalwert der Wahlberechtigten in den steirischen 
		Gemeinden ist. max = H�stwert der Wahlberechtigten. range = Differenz 
		zwischen Maximal und Minimal. Quartil 1 = 25% der Gemeinden weniger oder
		oder gleich 1289 Wahlberechtigte haben. Quartil 3 = 25% der Gemeinden gr��er
		oder gleich  2359 Wahlberechtigte haben. Mean = Mittelwert der Wahlberechtigten
		pro Gemeinde in der Steiermark. Median = 1948 zeigt, dass 50% der Gemeinden weniger als diese
		Zahl an Wahlberechtigten haben und 50% der Gemeinden mehr als diese Zahl an 
		Wahlberechtigten haben.

* Abgegebene Stimmen: Quasi dasselbe wie im obrigen Beispiel. Der min zeigt den kleinsten Wert
		an abgebenen Stimmen an, der max die H�chstanzahl an abgegebenen Stimmen einer 
		Gemeinde in der Steiermark. Die Range ist die Differenz zwischen min und max.
		Q1 und Q3 zeigen jeweils wieder, dass weniger oder gleich 25% (Q1) bzw. mehr oder gleich
		25% (Q3) unter bzw �ber gleich diesem Wert sind. Mean ist wieder der arythmetische 
		Durchschnitt und der Median zeigt an, dass 50% der Gemeinden weniger als diese
		Zahl an Wahlberechtigten haben und 50% der Gemeinden mehr als diese Zahl an 
		Wahlberechtigten haben.

* Ung�ltig/G�ltig: Wieder dasselbe. min zeigt den minimalen, max den maximalen der g�ltigen bzw ung�ltigen
		Stimmen. Range wieder die Differenz der min und max Werte. Q1 zeigt, dass 25% der Gemeinden
		weniger oder gleich 3673 (g�ltig) 31 (ung�ltig) gew�hlt haben, w�hrend Q3 zeigt, dass 25%
		der Gemeinden gr��er oder gleich 2341 (g�ltig) 21 (ung�ltig) gew�hlt haben. Der Mean gibt den Mittelwert
		der jeweils g�ltig/ung�ltig abgegebenen Stimmen an und der Median zeigt, dass 50% der Gemeinden
		jeweils �ber oder unter diesem Wert g�ltig/ung�ltig gew�hlt haben.

* ...f�r die Metriken der Parteien, Altersklassen, Haushaltszugeh�rigkeiten und Nationalit�ten gelten prinzipiell
dieselben Regeln.

## Beantwortung der Fragen

### Welche Aussage bez�glich der Wahl kann mit der zugrundeliegenden Datenbasis getroffen werden?

* Welche Partei hat die Wahl gewonnen
* In welchem Bezirk wurde wie gew�hlt
* Wieviele Wahlberechtigte gab es 
* Wieviele Stimmen wurden (g�ltig + ung�ltig) abgegeben
* Wie wirkt sich das Alter auf das Wahlverhalten aus
* Wie wirkt sich �sterreich/Ausland auf das Wahlverhalten aus
* Wie wirkt sich die Anzahl der Personen im Haushalt auf das Wahlverhalten aus
* Wieviele Briefwahlstimmen gab es (siehe Begr�ndung oben)

### Sind alle Daten vorhanden, um das Wahlverhalten in der Steiermark bei der NRW17 zu beschreiben?

Prinzipiell ja. Man k�nnte noch weitere Faktoren wie zB. den Bildungsgrad, die Geschlechterverteilung und das Besch�ftigungsverh�ltnis in den Datensatz aufnehmen, um noch genauere Interpretationen zu bekommen, aber f�r eine generelle Analyse des Wahlverhaltens der SteirerInnen reichen die angegebenen Daten durchaus aus. Die wichtigsten Daten empfinde ich hierbei die Ergebnisse auf Gemeindeebene, also in welcher Gemeinde welche Partei wie h�ufig gew�hlt wurde.

### Sind dir irgendwelche Besonderheiten bzgl. des Datensets aufgefallen bzw. gab es etwas f�r dich Unerwartetes?

Ja. Beim Summenz�hlen sind uns in jedem Bereich (bis auf die Zahlen der Wahlberechtigten) unterschiede zwischen der angegebenen Gesamtzahl und eben der Summe der Werte aufgefallen. Diese Unterschiede sind auf die Wahlkarten-W�hler zur�ckzuf�hren, da diese nicht pro Gemeinde ausgez�hlt werden.

### Welche Einstellungen hast du f�r den Boxplot gew�hlt und warum?

Die Boxplots sind vertikal, da sich der Boxplot so sch�n abzeichnet und man auch die Ausrei�er gut erkennen kann.


## Ergebnisse der Metriken

### Partei FP�:
* min: 166
* max: 1443
* range: 1277
* mean: 522
*Q1: 311,25
* Median: 427
* Q3: 616

### 1-Personen-Haushalte:
* min: 60
* max: 1503
* range: 1443
* mean: 255,027
* Q1: 123,75
* Median: 176
* Q3: 273,5

### 30-44 Jahre:
* min: 152
* max: 1591
* range: 1439
* mean: 486,333
* Q1: 272,75
* Median: 406
* Q3: 521,25
