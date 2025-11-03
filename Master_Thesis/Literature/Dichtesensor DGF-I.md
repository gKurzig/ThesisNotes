## Rethink Sensing

# Dichtesensor DGF-I

## Datenblatt I Technische Beschreibung und Installationsanleitung

Dokumentnummer: DB-KU-100084-7 Ab Firmware Version 14.

Erstellungsdatum: Februar 2022


## Inhalt

   -
- Hinweise zum Datenblatt
- Sicherheitshinweise
- Produktbeschreibung
- Installation, Inbetriebnahme und Deinstallation
- Reinigung und Reparatur
- Entsorgung
- Produktspezifikation


## Hinweise zum Datenblatt 3

## Hinweise zum Datenblatt

Verwendung und Aufbewahrung

•	Dieses Datenblatt ist fester Bestandteil des

```
Dichtesensors.
```
•	Das Datenblatt in unmittelbarer Nähe des Verwen-

```
dungsorts aufbewahren.
```
•	Bei einer Weitergabe an Dritte, Datenblatt oder re-

```
levante Inhalte an diese weitergeben.
```
•	Das Datenblatt sorgfältig lesen.

•	Änderungen sind vorbehalten.

Funktion

Das Datenblatt liefert Informationen zur sicheren Ver-

wendung und Installation des Dichtesensors.

Symbolverwendung

Die folgenden Symbole werden im Datenblatt verwen-

det, um auf gefährliche Situationen hinzuweisen und

Handlungsanweisungen zu kennzeichnen:

```
Symbol Beschreibung
```
```
WARNUNG
```
```
Führt bei Nichtvermeidung zu Tod oder
zu schwerer Körperverletzung.
```
### HINWEIS

```
Informationen zu Sachverhalten, die
keine Körperverletzung nach sich zie-
hen.
```
**▸** Einschrittige Handlungsanweisung

**1.** / **2.** / **3.** Mehrschrittige Handlungsanweisung

## Sicherheitshinweise

Bestimmungsgemässe Verwendung

```
•	Der Dichtesensor ist ausschliesslich für die Dichte-
messung von Gasen einzusetzen. Es dürfen nur zu-
lässige	Messstoffe	verwendet	werden.
•	Ein Nichtbeachten des Anwendungsbereichs kann
die 	Sicherheit	beeinträchtigen.	Der 	Hersteller	haftet
nicht für Schäden, die aus unsachgemässer Verwen-
dung entstehen.
```
Personalqualifikation

```
•	Der Dichtesensor darf nur von Fachpersonal instal-
liert und betrieben werden.
```
Betriebssicherheit

```
•	Der Betreiber ist für einen störungsfreien Betrieb
des Dichtesensors verantwortlich.
•	Den Dichtesensor nur in einem technisch einwand-
freien und betriebssicheren Zustand betreiben.
•	 Bei erhöhter	 Messstofftemperatur	 einen Berüh-
rungsschutz sicherstellen, um Verbrennungen zu
vermeiden.
•	Eigenmächtige Umbauten oder Reparaturen am
Dichtesensor sind nicht zulässig und können zu un-
vorhersehbaren Gefahren führen.
•	 Gesetzliche	Richtlinien	für	 Messstoffe	und	 Einsatz-
bereich beachten.
•	Überprüfen ob der Sensor für den vorgesehenen Ge-
brauch im zulassungsrelevanten Bereich eingesetzt
werden	 kann (z.B. Hygiene-Vorschriften,	 Explosi-
onsschutz, Druckgerätesicherheit).
•	 Sicherheitsdatenblatt	des	Messstoffes	beachten.
```
Produktsicherheit

```
•	Der Dichtesensor ist konform mit den Richtlinien,
die in der EU-Konformitätserklärung aufgelistet
sind. Mit der Anbringung des CE-Zeichens bestätigt
die TrueDyne Sensors AG diesen Sachverhalt.
```

## Produktbeschreibung 4

## Produktbeschreibung

Überblick

Der Dichtesensor DGF-I1 wurde konzipiert, um die

Dichte von Gasen und daraus abgeleitete Messgrössen

z.B. die Konzentration von binären Gasgemischen zu

bestimmen. Dies geschieht mit einem mikromecha-

nischen System (MEMS) mit einem Schwinger in Form

einer Stimmgabel sowie einem Temperatursensor und

einem Drucksensor. Die Sensoren sind auf einer Platine

befestigt und von einem kompakten Metallgehäuse

umgeben. Über einen integrierten Anschluss wird der

Dichtesensor direkt in eine Gasleitung oder in einen

Gastank eingeschraubt. Zum Schutz vor Verschmut-

zung ist im Dichtesensor ein Filter eingebaut.

Befindet	sich	 Messstoff	im	 Dichtesensor,	werden	über	

die Messung der Resonanzfrequenz der Stimmgabel,

die Messung der Temperatur sowie die Messung des

Drucks	die	Dichte	des	Messstoffes	bestimmt.

Die Messwerte werden im Anschluss dem übergeord-

neten System als Signal über eine RS485-Schnittstelle

zugespielt. Verwendet wird dazu ein Modbus-Befehls-

protokoll (Protokoll).

So	 sind	 Dichtemessungen	im	 Bereich	0...19  kg/m^3

mit	 einer	 Messrate	von	 10 Hz	 (10	 Messwerte	pro	 Sekun-

de) realisierbar.

```
Funktionsprinzip: DGF-I
```
MEMS-Schwinger

```
Der MEMS-Schwinger, ein vibronisches Mikrosystem,
ist das Herz des Messsystems und dient der Sensor-
signalgenerierung im Gesamtsystem. Wesentlicher
Bestandteil dieses Mikrosystems ist eine Stimmgabel,
die piezoelektrisch in Schwingung versetzt wird. Die
Stimmgabel ist in einer Halterung montiert und von
einem gasdurchlässigen Gehäuse umgeben, um sie ge-
genüber	mechanischen	Einflüssen	zu	schützen.	
```
Dichtemessung

```
Zur Dichtemessung verwendet der Dichtesensor so-
wohl den MEMS-Schwinger als auch den Druck- und
Temperatursensor. Während der Dichtemessung ist die
Stimmgabel	vom	 Messstoff	umgeben	und	 wird durch
die zugehörige Schaltung in Schwingung versetzt.
```
```
Die resultierende Resonanzfrequenz der Stimmgabel
ist von der Dichte des umgebenen Mediums abhängig
```
```
Messprinzip: MEMS-Schwinger
```
```
und wird ebenfalls durch die Schaltung des MEMS-
Schwingers	ausgelesen.	Je	 grösser	die	 Messstoffdichte,	
desto kleiner ist die Resonanzfrequenz. Die Resonanz-
frequenz	ist	somit	eine	Funktion	der	Messstoffdichte.
```
Anwendungsmöglichkeiten

```
Die Dichteinformation des Dichtesensors kann direkt
und indirekt verwendet werden. Während mit der di-
rekten Verwendung des Dichtewerts eine Produktqua-
lität ermittelt werden kann, ermöglicht eine indirekte
Verwendung anhand von Tabellen und Berechnungs-
algorithmen zum Beispiel die Konzentrationsbestim-
mung von binären Gasgemischen.
```
```
Der Dichtesensor kann unter anderem in folgenden
Applikationen eingesetzt werden:
•	Überwachung von Schweissgasgemischen.
•	Überwachung von Gasgemischen für Lebensmittel-
verpackungen.
•	Überwachen von Reingasen
```

## Installation, Inbetriebnahme und Deinstallation 5

Produktaufbau

```
2
```
```
1
```
```
8
7
6
```
```
5
```
```
4
```
```
3
```
_Produktaufbau Dichtesensor DGF-I_

_1 Elektrische Schnittstelle: M8-Anschluss, 4-polig
2 Gehäuse
3 Auslass G1⁄8“-Gewinde
4 Verschlussstopfen G1⁄8“
5 Fluidische Schnittstelle: G½“-Gewinde
6 Mit Sicherungsring und Federring eingebauter Filter
7 Dichtungsring für G½“-Gewinde
8 Auflagefläche für Gabelschlüssel (27 mm)_

Lieferumfang

•	Dichtesensor (inkl. Transportsicherungen)

•	Informationsblatt mit Download-Links

•	Verschlussstopfen (G^1 _⁄ 8_ ")

Produktidentifikation

```
Die	 Identifizierung	des	 Dichtesensors	erfolgt	über	
eine fortlaufende, 14-stellige Seriennummer. Diese ist
aussen auf dem Gehäuse angebracht und kann zudem
über das Modbus RTU (Protokoll) Kommunikationspro-
tokoll eingesehen werden.
```
## Installation, Inbetriebnahme und Deinstallation

Dichtesensor fluidisch anschliessen

```
WARNUNG
Verletzungsgefahr durch gefährliche Prozessbedin-
gungen und mangelnde Prozessdichtheit
‣ Rohrleitung vor Einbau des Dichtesensors entleeren
und Druck ablassen.
‣ Darauf achten, dass Dichtungen unbeschädigt und
sauber sind.
‣ Darauf achten, dass Dichtungen korrekt eingelegt sind.
‣ Fluidische Anschlüsse im Betrieb nicht lösen.
‣ Entfernen und Austausch des Verschlussstopfens nur
durch Fachpersonal.
‣ Hohe Temperaturen berücksichtigen.
```
**1.** Sämtliche Reste der Transportverpackung entfernen.
**2.** Transportsicherungen	 an fluidischen	 Anschlüssen
    entfernen.
       **3.** Gegebenenfalls	Adapter	für	 fluidische	Schnittstelle	
          auf Dichtesensor schrauben (Anzugsmoment: 40
          Nm).
       **4.** Dichtesensor an Rohr- oder Tankwand auf Gewinde-
          stutzen montieren (Anzugsmoment: 40 Nm). Einbau
          möglichst mit M8-Anschluss nach oben.
       **5.** Gegebenenfalls Seitengewinde G^1 ⁄ 8 " zur Durchströ-
          mung mit Klemmringverschraubung oder Schlauchan-
          schluss ergänzen und auf Dichtheit überprüfen.
       **6.** Alle Sensoren werden nach dem neuesten Stand der
          Technik kalibriert. Ein Nullpunktabgleich im Feld ist
          deshalb grundsätzlich nicht erforderlich. Nur bei
          höchsten Ansprüchen an die Messgenauigkeit respek-
          tive	 bei	 extremen	Prozess-	oder	 Betriebsbedingungen
          ist ein Reingas- bzw. Konzentrationsabgleich empfeh-
          lenswert.

Dichtesensor elektrisch anschliessen

```
WARNUNG
Tod oder schwere Verletzungen durch falschen Anschluss
‣ Elektrische Anschlussarbeiten nur von entsprechend
ausgebildetem Fachpersonal ausführen lassen.
‣ National	gültige	Installationsvorschriften	beachten.
‣ Örtliche	Arbeitsschutzvorschriften	einhalten.
```
```
WARNUNG
Keine strombegrenzende Sicherung
‣ Überstromschutz	durch 	externe	Beschaltung	mittels
einer	Sicherung	(max.	2	A	)	sicherstellen.
```

## Installation, Inbetriebnahme und Deinstallation 6

```
WARNUNG
```
Einsatz in explosionsgefährdeten Bereichen

Der Dichtesensor besitzt keine Zulassung für die Ver-

wendung	in	explosionsgefährdeten	Bereichen.

‣ Bei	 Betreiben	in	 explosionsgefährdeten	Bereichen	

```
Explosionsschutz	sicherstellen.
```
```
WARNUNG
```
Verletzungsgefahr durch mangelnde Prozessdichtheit

Die	 Elektronik	ist	 vom	 Messstoff	umgeben.	Bei	 Lösen	

des	M8-Anschlusses	kann	Messstoff	entweichen.

‣ Mutter des M8-Anschlusses nicht lösen.

‣ 4-polig M8-Stecker mit Anschluss verbinden. Dabei

```
Anforderungen an M8-Stecker beachten, siehe
„Elektrische Schnittstelle“ auf Seite 10. Der M8-Ste-
cker ist im Lieferumfang nicht enthalten.
```
‣ Dichtesensor an übergeordnetes System anschlies-

```
sen. Dabei Pinbelegung beachten, siehe „Elektrische
Schnittstelle“ auf Seite 10.
```
Dichtesensor in System integrieren

Der Dichtesensor bietet keine eigene Bedienmöglich-

keit. Das Auslesen der Daten erfolgt über eine serielle

Kommunikation im RS485-Standard. Dazu ist ein Aus-

lesesystem erforderlich. Der Dichtesensor sendet über

die Datenleitung ein Modbus RTU-Kommunikations-

protokoll (Protokoll) an das Auslesesystem.

```
Standardeinstellungen:
```
```
Baud rate 19200 BAUD
```
```
Data bits 8
```
```
Parity Even
```
```
Byte order 1-0-3-
```
```
Stop bits 1 bit
Modbus Slave
Address
```
### 247

```
Transmission type Modbus RTU (Protocol)
```
```
Temperature unit °C
```
```
Pressure unit bar
```
```
Density unit kg/m^3
```
```
Temperature
damping 0 [s]
```
```
Pressure damping 0 [s]
```
```
Density damping 0 [s]
```
```
Selected mixture 0
```
```
Selected carrier gas Gas
```
```
Reference
temperature unit °C
```
```
Reference
temperature
```
### 0 [°C]

```
Reference
pressure unit bar
```
```
Reference
pressure 1.01325 [bar]
```
```
Concentration min 0 [%]
```
```
Concentration max 100 [%]
```
```
Folgende Modbus RTU Funktionen werden unterstützt:
Code Name Beschreibung
```
```
0x03 Read
Holding
Registers
```
```
Lesen eines fortlaufenden Holding
Register Blocks
```
```
0x04 Read Input
Registers
```
```
Lesen eines oder mehrerer aufeinan-
derfolgender Register
```
```
0x06 Write
Single
Register
```
```
Schreiben eines einzelnen Registers
```
```
0x10 Write
Multiple
Registers
```
```
Schreiben mehrerer aufeinanderfolgen-
der Register
```
### HINWEIS

‣ ENUM entspricht UINT16 bei den Registerinformationen

```
Folgende RTU Funktionen werden nicht unterstützt
‣ 0x01	 Read	Coils
‣ 0x02	 Read	Discrete	Inputs
‣ 0x05	 Write	Single	Coil
‣ 0x0F	 Write	Multiple	Coils
‣ 0x07	 Read	Exception	Status
‣ 0x08	 Diagnostics
‣ 0x0B	 Get	Comm	Event	Counter
‣ 0x0C	 Get	Comm	Event	Log
```

## Installation, Inbetriebnahme und Deinstallation 7

Modbus	RTU	 Registerinformationen	mit	 read/write-	Zugriff:

Name Adresse Datentyp Auswahl/
Eingabe

Baud rate 4912 ENUM
UINT

### 0: 1200

### 1: 2400

### 2: 4800

### 3: 9600

### 4: 19200

### 5: 38400

### 6: 57600

### 7: 115200

Parity 4914 ENUM
UINT

```
0: None
1: Even
2: Odd
```
Byte order 4915 ENUM
UINT

### 0: 0-1-2-

### 1: 3-2-1-

### 2: 2-3-0-

### 3: 1-0-3-

Stop bits 4916 ENUM
UINT

```
0: 1 Bit
1: 2 Bits
```
Modbus address 4910 UINT16 1 - 247

Access code 200 UINT

Device tag 113 STRING

Temperature unit 2109 ENUM
UINT

### 0: °C

### 1: K

### 2: °F

### 3: °R

Pressure unit 2130 ENUM
UINT

```
0: bar
1: psi
2: Pa
```
```
Name Adresse Datentyp Auswahl/
Eingabe
Density unit 2107 ENUM
UINT
```
```
0: g/cm^3
1: Reserved
2: kg/dm^3
3: kg/l
4: kg/m^3
```
```
Temperature
damping
```
```
5127 FLOAT32 0 - 30 [s]
```
```
Pressure damping 5506 FLOAT32 0 - 30 [s]
```
```
Density damping 5508 FLOAT32 0 - 30 [s]
```
```
Selected mixture 210 ENUM
UINT
```
```
0-14: See
«Selected	mix-
ture	matrix»
```
```
15-19:	Cust.	mix
Restart Device 202 ENUM
UINT
```
```
0: False
1: True
Enable Modbus
Termination
```
### 205 ENUM

### UINT

```
0: False
1: True
Clean gas
adjustment
```
### 206 ENUM

### UINT

```
0: False
1: True
Reset
adjustment
```
### 207 ENUM

### UINT

```
0: False
1: True
```
```
HINWEIS
Reingasmessung:
Die	 Konfiguration	des	 Sensors	erfordert	die	 Auswahl	
eines Gasgemisches. Dadurch kann der Sensor für die
Konzentrationsbestimmung mit höchstmöglicher Ge-
nauigkeit verwendet werden. Bei einem Reingas han-
delt es sich um ein Gasgemisch, in welchem ein Gas zu
100% vorliegt. Für die Reingasmessung sollte in der
Konfiguration	des	 Sensors	somit	 ein	 Gasgemisch	aus-
```
```
gewählt werden, welches das zu analysierende Reingas
enthält. Beispiel:
‣ Reingas: Argon (Ar)
‣ Mögliche zu wählende Gasgemische:
Ar / H 2 , Ar / He, N 2 / Ar, Air / Ar, O 2 / Ar
Um die Dichtemessung für ein Gas bzw. Gasgemisch zu
optimieren,	das 	in 	der	Standardkonfiguration	des 	Sensors
nicht enthalten ist, kontaktieren Sie bitte den Hersteller.
```
```
H 2 He N 2 Air O 2 Ar CO 2
```
```
H 2
```
```
He
```
```
N 2 0 4 9 12
```
```
Air 1 5 10 13
```
```
O 2 6 11 14
```
```
Ar 2 7
```
```
CO 2 3 8
```
```
Gas
```
```
Gas
```
```
Selected Mixture Matrix
```
```
Name Adresse Datentyp Auswahl/
Eingabe
Selected carrier gas 211 ENUM
UINT
```
```
0: Gas
1: Gas
```
```
Reference
temperature unit
```
### 218 ENUM

### UINT

### 0: °C

### 1: K

### 2: °F

### 3: °R

```
Reference
pressure unit
```
### 226 ENUM

### UINT

```
0: Bar
1: psi
2: Pa
```

## Installation, Inbetriebnahme und Deinstallation 8

Name Adresse Datentyp Auswahl/
Eingabe

Reference
temperature

### 220 FLOAT

Reference
pressure

### 222 FLOAT

Concentration
adjust

### 224 FLOAT32 0-100 [%]

Concentration
min

### 7000 FLOAT32 [%]

Concentration
max

### 7002 FLOAT32 [%]

### HINWEIS

Benutzerdefiniertes Gasgemisch:

Neben den voreingestellten Gasgemischen für die Kon-

zentrationsmessung kann der Sensor für weitere Gas-

gemische	konfiguriert	werden.	Kontaktieren	Sie	 hierfür	

bitte den Hersteller.

Es wird zwischen Reingasabgleich und Konzentrati-

onsabgleich unterschieden.

Auswahl Reingasabgleich

**1.** Sicherstellen, dass das Reingas verschmutzungsfrei

```
im Sensor vorhanden ist.
```
**2.** Sicherstellen, dass das Trägergas («Carrier Gas») mit

```
dem Reingas im Sensor übereinstimmt.
```
```
a. Im Selected Carrier Gas Register (MB: 211) kann
Gas 1 oder Gas 2 ausgewählt werden.
```
```
b. Gas 1 bezeichnet das erste, Gas 2 das zweite Gas
in	 der	 gewählten	Gasmischung	im	 Selected	Mix-
ture Register (MB: 210).
```
**3.** Stabile Temperatur- und Druckverhältnisse im Sen-
    sor sicherstellen.
**4.** Clean Gas Adjustment Register (MB: 206) auf TRUE
    setzen.
**5.** Warten, bis der Abgleich beendet ist.

```
a. Bei Beendung wird das Clean Gas Adjustment Re-
gister (MB: 206) automatisch wieder auf FALSE
gesetzt. Zusätzlich ist das Adjustment Failure Re-
gister (MB: 13) auf FALSE.
```
```
b. Im Fehlerfall ist das Adjustment Failure Register
auf TRUE. Das Adjustment Error Register (MB:
208) gibt dann Aufschluss auf eine mögliche
Fehlerquelle. Der Sensor wiederholt automatisch
den Abgleich, bis dieser erfolgreich durchgeführt
wurde. Um den Prozess zu stoppen, das Reset
Adjustment Register (MB: 207) auf TRUE setzen.
Frühere Abgleiche werden dadurch zurückge-
setzt.
```
```
Auswahl Konzentrationsabgleich:
```
**1.** Sicherstellen, dass die gewünschte Gasmischung im
    Selected	Mixture	Register	(MB:	 210)	 eingestellt	ist	
    und	sich	die	Gasmischung	im	Sensor	befindet.
**2.** Stabile Temperatur-, Druck- und Konzentrationsver-

```
hältnisse im Sensor sicherstellen.
```
**3.** Gewünschte Soll-Konzentration im Concentration
    Adjustment Register (MB: 224) eingeben: Angabe
    in % des verdünnten Gases («Diluted Gas») im Trä-
    gergas («Carrier gas»).
**4.** Warten, bis der Abgleich beendet ist.

```
a. Bei Beendung wird das Concentration Adjust-
ment Register (MB: 224) automatisch wieder auf
NAN gesetzt. Zusätzlich ist das Adjustment Failu-
re Register (MB: 13) auf FALSE.
```
```
b. Im Fehlerfall ist das Adjustment Failure Register
(MB: 13) auf TRUE. Das Adjustment Error Re-
gister (MB: 208) gibt dann Aufschluss auf eine
mögliche Fehlerquelle. Der Sensor wiederholt
automatisch den Abgleich, bis dieser erfolgreich
durchgeführt wurde. Um den Prozess zu stoppen,
das Reset Adjustment Register (MB: 207) auf
TRUE setzen. Frühere Abgleiche werden dadurch
zurückgesetzt.
```
```
Abgleich zurücksetzen:
(Reingas- & Konzentrationsabgleich)
```
**1.** Reset Adjustment Register (MB: 207) auf TRUE set-
    zen. Der Abgleich wird zurückgesetzt.
**2.** Das Reset Adjustment Register wird automatisch
    wieder auf FALSE gesetzt.


## Reinigung und Reparatur 9

Modbus	RTU	Registerinformationen	mit	read-Zugriff:

Name Adresse Datentyp Auswahl/
Eingabe

Memory version 100 UINT

Serial number 101 STRING

Software version 108 UINT

Software build 109 UINT

Starter counter 110 UINT

Access level 111 ENUM
UINT

0: Operator
1: Maintenance
Device identity 1 UINT

Temperature 9513 FLOAT

Pressure 2017 FLOAT

Density 2013 FLOAT

Reference density 2015 FLOAT

Concentration 2598 FLOAT

Adjustment
error

### 208 ENUM

### UINT

```
0: No error
1: Calibration
in process
2: Pressure
unstable
3: Temperature
unstable
4: Density
unstable
5:	Offset	to
large
6:	Offset	NAN
```
Sensor failure 10 ENUM
UINT

```
0: False
1: True
```
```
Memory error 11 ENUM
UINT
```
```
0: False
1: True
Density out of
range
```
### 12 ENUM

### UINT

```
0: False
1: True
Concentration out
of range
```
### 18 ENUM

### UINT

```
0: False
1: True
Adjustment failure 13 ENUM
UINT
```
```
0: False
1: True
Temperature out of
range
```
### 14 ENUM

### UINT

```
0: False
1: True
Pressure out of
range
```
### 15 ENUM

### UINT

```
0: False
1: True
Oscillator failure 16 ENUM
UINT
```
```
0: False
1: True
Pressure Sensor
failure
```
### 17 ENUM

### UINT

```
0: False
1: True
```
```
HINWEIS
Referenzdichte:
Als Referenzdichte wird die Gasdichte bei Referenz-
druck und Referenztemperatur bezeichnet. Der Refe-
renzdruck und die Referenztemperatur können durch
den Anwender eingegeben werden (MB Register 218,
220, 222, 226). Auf Basis des eigegebenen Referenz-
drucks, der eingegebenen Referenztemperatur und der
gemessenen Gasdichte wird die Referenzdichte (MB:
2015) berechnet und ausgegeben.
```
Dichtesensor einschalten

```
‣ Spannungsversorgung einschalten. Nach Einschal-
ten der Spannungsversorgung startet der Dichte-
sensor	nach	 einer	 kurzen	Aufstartzeit	(<1 Sekunde)	
automatisch.
```
Dichtesensor ausbauen

```
WARNUNG
Gefährdung von Personal und Umwelt durch ge-
sundheitsgefährdende Messstoffe
‣ Sicherstellen,	dass 	beim 	Lösen 	der	fluidischen	Ver-
bindung keine gesundheits- oder umweltgefähr-
denden	Messstoffe	austreten	können.
```
**1.** Steckerverbindung des elektrischen Anschlusses
    vom Dichtesensor trennen.
**2.** Fluidische Verbindung lösen.

## Reinigung und Reparatur

Reinigung des Gehäuses durchführen

### HINWEIS

```
Beschädigung des Gehäuses und des Sensors durch
Reinigungsmittel möglich
‣ Keinen Hochdruckdampf verwenden.
‣ Nur zulässige Reinigungsmittel verwenden.
‣ Reinigung nur bei Raumtemperatur.
‣ Sicherstellen, dass kein Reinigungsmittel in den
Sensor-Innenraum eindringt.
```
```
‣ Gehäuse mit zulässigem Reinigungsmittel reinigen.
Zulässige Reinigungsmittel:
•	Milde Seifenlösungen
•	Isopropylalkohol
```

## Entsorgung 10

Filterreinigung durchführen

Um Verstopfungen zu vermeiden, den im Gerät instal-

lierten Filter regelmässig auf Verschmutzung prüfen

und je nach Verschmutzungsgrad reinigen oder aus-

tauschen. Detaillierte Informationen zum Filter siehe

„Integrierter	Filter“	auf	Seite 11.

**1.** Sicherungsring mit Sicherungsringzange entnehmen.
**2.** Filter und Federring entnehmen.
**3.** Federring wieder einsetzen.
**4.** Neuen Filter einsetzen.
**5.** Sicherrungsring wieder einsetzen.
**6.** Gegebenenfalls Dichtungsring austauschen.

## Entsorgung

Dichtesensor entsorgen

```
WARNUNG
```
Gefährdung von Personal und Umwelt durch ge-

sundheitsgefährdende Messstoffe

‣ Sicherstellen, dass Dichtesensor und alle Hohlräu-

```
me frei von gesundheits- oder umweltgefährdenden
Messstoffresten	sind.
```
```
‣ Dichtesensorkomponenten der Wiederverwertung
zuführen.	Dabei	die	 national	gültigen	Vorschriften	
beachten.
```
## Produktspezifikation

```
Allgemein
```
```
Messgrösse •	Dichte in kg/m^3
•	Temperatur in °C
•	Druck in bar absolut
```
```
Abgeleitete Messgrössen (kunden-
spezifische	Konfiguration):
•	Konzentration von binären Gas-
gemischen als ideale Volumen-
anteile (Mol anteile) in %
•	Referenzdichte (Normdichte)
•	Mittlere Molmasse
•	 Kundenspezifische	Messgrössen
```
```
Zulässige Messstoffe WARNUNG
```
```
Lebensgefahr bei Betreiben mit
zündfähigen Messstoffen.
Der Dichtesensor besitzt keine Zu-
lassung	für	 die	 Verwendung	in	 ex-
plosionsgefährdeten Bereichen.
‣ Nicht für zündfähige Gase oder
Gasgemische verwenden.
‣ Nicht 	für 	Kohlenwasserstoff	gase
verwenden.
```
```
Zulässige Messstoffe
(Fortsetzung)
```
### HINWEIS

```
Beschädigung des Dichtesensors.
‣ Nur zulässige Gase oder deren
Gemische mit geringer Feuch-
tigkeitskonzentration (<0,1%)
verwenden.
```
```
•	 Wasserstoff	(H 2 )
•	Helium (He)
•	 Stickstoff	(N 2 )
•	 Sauerstoff	(O 2 )
•	 Luft
•	 Kohlenstoffdioxid	(CO 2 )
•	Argon (Ar)
Medien, die von zuvor aufgeführ-
ten 	Messstoffen	abweichen,	kön-
nen ggf. nach Einzelabklärung
verwendet werden. Zum Beispiel
Neon (Ne) und Krypton (Kr).
```
```
Zulässige Gemische, siehe Modbus
Registerinformationen «Selected
Mixtures	Matrix»	.
```
```
Messperformance
```
```
Max.
Messabweichung
```
```
•	Dichte: ±0,1 kg/m^3
•	Temperatur: ±0,8 °C
•	Druck: ±0,04 bar
•	Mit Feldabgleich
Dichte ±0,05 kg/m^3
```
```
Wiederholbarkeit •	Dichte: ±0,015 kg/m³
•	Temperatur: ±0,06 °C
•	Druck: ±0,005 bar
```
```
Messrate 10 Hz
```

## Produktspezifikation 11

Einsatzbereich

Zulässiger
Dichtemessbereich

```
0,2...19 kg/m^3
Max.	Messbereich:	
```
```
0...10 bar (abs)
HINWEIS
Gasgemische mit Argon (Ar) nur
bis	max	9	bar	(abs)	verwenden.
```
```
Berstdruck:
30 bar
```
Ansprechzeit 0,1...120 s
(abhängig von der Installation)

Zulässige
Partikelgrösse

```
Min.	50	μm
```
```
Ein- und
Auslaufstrecken
```
```
Ein- und Auslaufstrecken haben
keinen	 Einfluss	auf	 die	 Mess-
genauigkeit.
```
```
Temperaturbedingungen
```
```
Zulässige Mediums-
temperatur
```
### -20...+60 °C

```
Zulässige Umge-
bungstemperatur
```
### -20...+60 °C

```
Zulässige Lagerungs-
temperatur
```
### -20...+60 °C

```
Umgebungsbedingungen
```
```
Klimaklasse Noch	nicht	definiert
```
```
Elektromagnetische
Verträglichkeit
```
### EMV 2014/30/EU (EN 61326-1)

```
Schwingungs - und
Stossfestigkeit
```
```
Noch	nicht	definiert
```
```
Schutzart
(eingebauter Zustand)
```
### IP67 (IEC 60529)

```
Werkstoffe
```
```
Gehäuse •	Rostfreier Stahl: 1.4404 (316L)
```
```
Medienberührend •	Rostfreier Stahl: 1.4404 (316L)
•	Elektronikplatine
```
```
0.
0.
0.
0.
0.
0
-0.
-0.
-0.
-0.
-0.
0 50 100 150 200 250 300 350 400
```
```
Maximaler Fehler (kg/m
```
```
3 )
```
```
Dichte · Viskosität (kg/m^3 · μPa s)
```
```
Maximale Messabweichung
```
```
C u t- o ff
```
```
Viskosität (μPa s)
```
```
p (bar):
```
```
Dichte (kg/m^3 )
```
```
Arbeitsbereich DGF-I
```
```
CO 2
```
```
N 2
```
```
Air
```
```
He
```
```
Ar
```
```
O 2
```
```
H 2
```
```
0 5 10 15 20
```
```
5
```
```
10
```
```
15
```
```
20
```
```
1 2 3 4 5 6 7 8 9 10
```
```
1 2 3 4 5 6 7 8 9 10
```
```
1 2 3 4 5 6 7 8 9 10
```
```
1 2 3 4 5 6 7 8 9 10
```
```
1 2 3 4 5 6 7 8 9 10
```
```
1 5 10
```
```
1510
```
```
Cut-off	
```
_Grafik: Maximale Messabweichung Grafik: Arbeitsbereich DGF-I_


## Produktspezifikation 12

_Bauform, Abmessungen in mm_

Dimensionen

Abmessungen 63 	x 	27 	x 	33.5 	mm^3 (mit M8-Stecker)

Gewicht <150 g

Fluidische Schnittstelle

Fluidische Schnittstellen _• G½“-Gewinde_

Elektrische Schnittstelle

Kommunikation •	Auf dem Hardware-Standard

```
RS485. (Protokoll)
•	Modbus RTU-
Kommunikations protokoll,
siehe „Modbus RTU Register-
informationen“	ab	Seite 6.
```
```
Anschluss M8-Anschluss, 4-polig,
gemäss	IEC 61076-2-
```
```
Energieversorgung DC 4,5...12 V	(max. 200 mW)	
```
```
Anschlusskabel und Stecker
sind nicht im Lieferumfang ent-
halten. Anforderungen an An-
schlusskabel und Stecker:
```
```
•	Netzteil mit Sicherheits-
Kleinspannung (SELV) oder
Schutz-Kleinspannung (PELV).
•	M8-Stecker, 4-polig
•	 Max.	zulässige	Kabellänge:	30 m
•	Überstromschutz durch
externe	Beschaltung	mittels	
einer	Sicherung	(max.	2	A	)	
sicherstellen
•	Kabelempfehlung: Lumberg
Automation M8 Standard
Sensor / Actuator Connec-
tors RKMWV 4-07.
```
```
RS485-Schnittstelle •	 Überstromschutz	durch	externe	
Beschaltung mittels einer Siche-
rung	(max.	2	A	)	sicherstellen
•	Kabelempfehlung: Lumberg
Automation M8 Standard Sensor
/ Actuator Connectors RKMWV
4-07.
•	Gemäss Standard EIA/TIA-485-A
•	 Maximal	zulässige	Spannung:
―	A	und	B:	-11 V...+15 V
― (A-B) oder (B-A) mit aktiver
Terminierung: 6 V
•	Zuschaltbare
120 Ω-Terminierung:	Standard-
mässig deaktiviert (Unit Load 1/8)
```
```
Kabelbelegung
```
## M8-Anschluss 4

## 3

## 2

## 1

```
PinBelegung
```
```
1 V+ Versorgungsspannung
```
```
2 A RS485 Modbus RTU
```
```
3 GND Signalmasse
```
```
4 B RS485 Modbus RTU
```
```
Integrierter Filter
```
```
Material Sinterbronze
```
```
Theoretische
Porengrösse
```
```
50 μm
```
```
63
```
```
14
```
```
34.
```
```
5
```
```
G½"
```
```
27.
```
```
Ø 33
```

## Produktspezifikation 13

Zertifikate und Zulassungen

CE-Kennzeichnung Der Dichtesensor erfüllt die ge-
setzlichen Anforderungen der EG-
Richtlinien. Die TrueDyne Sensors
AG bestätigt die erfolgreiche Prü-
fung des Dichtesensors mit der An-
bringung des CE-Zeichens.

RoHS Alle verbauten Komponenten er-
füllen die Anforderungen der RoHS
III-Richt linie.

Elektromagnetische
Verträglichkeit

### EMV 2014/30/EU (EN 61326-1)

Zubehör und Ersatzteile

Adapter
G½"-Gewinde

```
Adapter	G½"-Gewinde	für	 die	 fluidi-
sche Schnittstelle.
```
Dichtungsring Dichtungsring für den Austausch
eines beschädigten Dichtungsrings.

Filter Set bestehend aus Filter, Federring
und Sicherungsring für den Aus-
tausch eines verschmutzten Filters.

Elektronik-Adapter USB-RS485 inkl. M8-Stecker


© TrueDyne Sensors AG • Christoph-Merian-Ring 20 • CH-4153 Reinach

T	+41 61 715 89 00	• info@truedyne.com • [http://www.truedyne.com](http://www.truedyne.com)

Download-Bereich


