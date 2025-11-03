## Dichtemessung Grundlagen

### Schulungsunterlage (MEMS-CHIP)


## Grundlagen der Dichtemessung

```
Auf einen Blick
In diesem Abschnitt erhalten Sie einen ersten Einblick in die Grundlagen der Dichtemessung. Sie erfahren,
dass es sich bei der Dichte um eine temperatur- und druckabhängige Stoffeigenschaft handelt, die häufig
mit der Einheit kg/m^3 bzw. lb/ft^3 angegeben wird. Der Dichtewert wird für die Bestimmung von Konzen-
tration, mittlerer Molmasse und Gehalt benötigt. Wird die Dichte von Gasen ermittelt, muss beachtet
werden, dass sie vom jeweiligen Druck abhängig ist. Die Dichte von Flüssigkeiten ist abhängig von der
Temperatur
```
Inhalte
•	Was ist Dichte?
•	Wofür werden Dichteangaben benötigt?
•	Welche Messmethoden gibt es für die Bestim-
mung der Dichte?

Was ist Dichte?
Die Dichte ist eine physikalische Stoffeigenschaft,
die temperatur- und druckabhängig ist. Sie gibt Auf-
schluss darüber, wie schwer ein Stoff ist. Wird die
Masse von zwei Stoffen derselben Menge verglichen,
hat der Stoff mit dem höheren Gewicht die höhere
Dichte.

Die Dichte _ρ_ (Rho) wird als Masse _m_ pro Volumenein-
heit _V_ definiert.

```
Dichteformel
```
Stoffe können als Reinstoffe, Gemische oder Verbin-
dungen vorkommen. Werden die Massen der einzel-
nen Stoffe pro Volumeneinheit addiert, erhält man
die Dichte eines Stoffgemisches:

```
Dichteformel von Stoffgemischen
```
```
̨ Umrechnung SI-Einheiten:
1 kg/m^3 = 1000 g/m^3 = 0,001 g/cm^3
= 0,000001 kg/cm^3
Die SI-Einheit der Dichte lautet Kilogramm pro Kubik-
meter (kg/m^3 ).
```
```
Die US-Einheit der Dichte wird in Pfund pro
Kubikfuss(lb/ft^3 ) angegeben.
```
```
Zudem gibt es produkt- oder branchenspezifische
Einheiten. So z.B. das Grad Oechsle (°Oe) oder das
Grad Brix (°Bx). Die Einheiten geben die Dichte bzw.
den Zuckergehalt von Most oder von Zucker/Wasser-
Lösungen an.
```
```
̨ Die Dichte ist druck- und temperaturabhängig.
Aufgrund der thermischen Ausdehnung und der
Kompressibilität wird die Dichte eines Stoffes von der
vorherrschenden Temperatur und dem Druck beein-
flusst. Abhängig davon, ob es sich um einen Feststoff
oder um ein Fluid handelt, wirken diese Einflussgrös-
sen stärker oder weniger stark auf die Dichte ein.
```
```
Die Temperatur- und Druckabhängigkeit ist bei Flu-
iden sehr viel höher als bei Feststoffen. Um eine
präzise Dichteangabe zu erhalten, müssen daher ins-
besondere bei Fluiden die zugehörige Temperatur
sowie der Druck bekannt sein.
```
```
̨ Das Volumen und die Dichte verändern sich mit
einer Temperatur- und/oder Druckänderung. Die
Masse bleibt dabei immer gleich.
Während sich die Dichte und das Volumen eines
Stoffes durch Temperatur- und Druckeinfluss verän-
dern, bleibt die Masse immer konstant. Wird das Vo-
lumen bei gleichbleibender Masse durch Druck- und/
oder Temperatureinfluss verringert, erhöht sich die
Dichte.
```
##### ρ =

###### m

###### V

##### ρ =

###### 1

# V ∑

##### mi

```
i
```

```
Temperatur- und Druckeinfluss auf die Dichte einiger Fluide bei t ref = 20 °C und p ref = 10 bar
```
```
Stoff
Dichte ρ
( t ref , p ref)
(kg/m^3 )
```
```
Dichte ρ
( t ref +1 °C, p ref)
(kg/m^3 )
```
```
Δρ
(Δ T = 1 K)
(kg/m^3 )
```
```
Dichte ρ
( t ref , p ref +1 bar)
(kg/m^3 )
```
```
Δρ
( Δp = 1 bar)
(kg/m^3 )
Gase
Helium 1,634 1,629 -0,006 1,80 0,
Luft 11,92 11,88 -0,04 13,12 1,
CO 2 19,10 19,02 -0,08 21,14 2,
Methan 6,70 6,68 -0,02 7, 3 9 0,
Flüssigkeiten
Propan 500,52 498,95 -1 , 57 500,80 0,
Wasser 998,62 998 ,41 -0,21 998,66 0,
Ethanol 790,22 789,36 -0,86 790,30 0,
Pentan 626,86 625,89 -0,97 626,99 0,
```
```
Quelle: NIST Reference Fluid Thermodynamic and Transport Properties Database
```
In der Tabelle ist zu erkennen, dass sich die Dichte von
Gasen bei einer Temperaturveränderung von einem
Kelvin kaum verringert. So sinkt sie bei Luft lediglich
um ca. 0,04 kg/m^3. Mit dem MEMS-Chip könnte eine
solche Veränderung nicht eindeutig festgestellt wer-
den. Wird der Druck jedoch um 1 bar erhöht, erhöht
sich die Gasdichte im Beispiel von Luft um 1,2 kg/m^3.
Die Dichte einer Flüssigkeit verändert sich bei einer
Druckänderung von 1 bar hingegen kaum.

̨ Um	Stoffe	untereinander	besser	vergleichen	zu	
können,	kann	die	Dichte	eines	Stoffes	in	eine	
sogenannte	Normdichte	oder	in	eine	spezifische	
Dichte umgerechnet werden.

Die Normdichte (auch „Reference Density“ genannt)
gibt die Dichte eines Stoffes oder Stoffgemisches bei
einer bestimmten Temperatur und einem bestimmten
Druck an. Sie ermöglicht eine bessere Vergleichbar-
keit von verschiedenen Dichtewerten untereinander.
Die folgenden Standardbedingungen für Tempera-
tur _t_ n und Druck _p_ n werden in den aufgeführten Bran-
chen häufig verwendet:

```
Standardbedingungen von Normdichten
verschiedener Branchen
```
```
Branche Temperatur t n Druck p n
Physik 0 °C 1,01325 bar
Chemie 0 °C 1,000 bar
Öl & Gas 15 °C/60 °F 1,013 bar
Medizin 37 °C Luftdruck
Labor 20 °C 1013 mbar
```
```
Quelle: in Anlehnung an https://de.wikipedia.org/wiki/Standard-
bedingungen
```
```
Die Normdichte	 von Stoffen	 bzw. Stoffgemischen
kann sogenannten Dichtetabellen entnommen
werden.	Beispiele	für 	Dichtetabellen	finden	sich 	u.a.
hier:
•	Alkohol: Standard OIML R 22
„International Alcoholmetric Tables“ von 1973
(http://www.oiml.org/en)
•	Zucker: Standard ICUMSA
„Densimetry	and	Tables:	Sucrose	-Official;	Gluco-
se,	Fructose	and	Invert	Sugar	-	Official	ICUMSA	
Method SPS-4“ von 1998
(http://www.icumsa.org)
```

•	Wasser: PTB-Mitteilungen
Wagenbreth,	H.;	Blanke,	W.:	„Die	Dichte	des	Was-
sers im Internationalen Einheitensystem und in
der Internationalen Praktischen Temperaturskala“
von 1968
sowie
Bettin	H.;	Blanke	W.:	„Die	Dichte	des	Wassers	als	
Funktion der Temperatur nach Einführung der
Internationalen Temperaturskala“ von 1990
•	Gase: Datenbank von NIST
„NIST Reference Fluid Thermodynamic and Trans-
port Properties Database“
(http://www.nist.gov)

Die spezifische Dichte _d_ , auch als relative Dichte be-
kannt, beschreibt das Verhältnis von zwei Dichtewer-
ten. Dabei wird die Dichte eines Stoffes mit der jewei-
ligen Normdichte oder einer anderen Bezugsgrösse
(z.B. Luft) ins Verhältnis gesetzt. Die spezifische Dich-
te ist eine dimensionslose Grösse ohne Einheit.

```
Berechnung der spezifischen Dichte d
```
Wofür werden Dichteangaben benötigt?
Die Dichte ist ein Standardwert für die Charakterisie-
rung von Stoffen und Stoffgemischen und wird da-
her häufig in der Analytik und bei der Synthese von
Stoffen eingesetzt.

Der Dichtewert ermöglicht die Ableitung verschie-
dener Kenngrössen, die Rückschlüsse auf die Zusam-
mensetzung eines Gemisches oder einer Verbindung
zulassen.

Sehr häufig wird mithilfe der Dichte die Konzentrati-
on eines Stoffes in einer wässrigen Lösung bestimmt.
Dabei kann die mengenmässige Grösse eines (Rein)-
Stoffes in einem Gemisch in Volumenprozent, Mas-
senanteil oder als Stoffmengenkonzentration ange-
geben werden.

Zudem wird die Qualität eines Stoffgemisches oder
einer Stoffverbindung häufig mit der mittleren Mol-
masse (mittlere molare Masse) beurteilt. Die mittlere

```
Molmasse kann ebenfalls mithilfe der Dichte ermit-
telt werden und ermöglicht z.B. eine Charakterisie-
rung von Erdgas.
```
```
Welche Messmethoden gibt es für die Bestim-
mung der Dichte?
Es gibt zahlreiche Vorrichtungen und Messmetho-
den, mit denen die Dichte eines Stoffes bestimmt
werden kann. Beim dem MEMS-Chip kommt mit der
Schwinger-Dichtemessung ein relativ junges Prinzip
zum Einsatz. Typischerweise werden aber auch heute
noch ältere Messmethoden wie Aräometer, Pykno-
meter und Auftriebswägungen verwendet.
```
#### d =

##### ρ

##### ρ

```
Luft
```

Messmethoden für die Bestimmung der Dichte

```
1
```
```
2
```
```
3
```
```
Für die Dichtemessung von Flüssigkeiten werden
häufig Aräometer eingesetzt. Diese gläsernen
Schwimmkörper werden in der Flüssigkeit platzi-
ert	 und	 sinken	so	 lange	ein,	 bis	 die	 Auftriebs kräfte	
der 	Prüfflüssigkeit	ein 	Gleichgewicht	zum 	Aräom-
etergewicht bilden. Die Dichte der Flüssigkeit
kann anhand der Eintauchtiefe des Schwimm-
körpers abgeleitet werden.
```
```
Quelle: Flüssigkeit-Dichtemessung Übersichtsartikel 2002
Prof. Dr. G. Hradetzky (Hochschule Merseburg)
Prof. Dr. K.-D. Sommer (PTB Braunschweig)
```
```
1
```
```
2
```
```
3
```
```
Pyknometer sind Wägegefässe, die zuerst leer
und dann mit der zu messenden Flüssigkeit oder
dem zu messenden	 Feststoff	 gewogen	 werden.
Anhand der beiden Werte kann die Dichte be-
rechnet werden.
```
```
Quelle: http://www.physik.uni-halle.de/Lehre/Grundprak-
tikum/anleitungen/Pharma-Heft-11.pdf,	Martin-Luther-
Universität Halle-Wittenberg
```
```
Mithilfe	des	 Auftriebsprinzips	ist	 die	 Messung	der	
Dichte auch mit Auftriebswägung möglich. In
die zu messende Flüssigkeit wird ein Senkkörper
getaucht,	dessen	Auftrieb	mithilfe	einer 	Waage
gemessen	wird. 	Der 	Quotient	des 	Auftriebs	und
des Senkkörpervolumens ermöglicht die Berech-
nung der Dichte der Flüssigkeit.
```
```
Quelle: Artikel „Neues Messverfahren für Aräometer durch
direkte	Auftriebskraftmessung“	in	WägeRaum	(Ausgabe	
10, 2004), Christian Buchner und Dietmar Steidl, Bundes-
amt für Eich- und Vermessungwesen (BEV)
```

Messmethoden für die Bestimmung der Dichte (Fortsetzung)

```
Der Omega-Chip zählt zu den Schwinger-Dich-
temessgeräten. Bei dieser Methode bewegt sich
ein Schwinger während er Kontakt zu dem jew-
eiligen Fluid hält. Dabei wird die Schwingfrequenz
gemessen, die von der Dichte des Fluids abhängig
ist.
```
```
Quelle: Technische Information “DLO-M1”, TrueDyne
Sensors AG
```
Dichtemessmethoden im Vergleich

```
Aräometer Pyknometer Auftriebswägung Schwinger-
Dichtemesser
Stoffart Flüssigkeiten Festkörper und Flüs-
sigkeiten (niedrig-
viskose)
```
```
Festkörper und Flüs-
sigkeiten
```
```
Gase und Flüssigkeiten
```
```
Einsatzgebiet Labor, Prozess Labor Labor, z.T. Prozess Labor, Prozess
Messunsicher-
heiten
```
```
0,02 bis 5 kg/m³ 0,02 bis 0,5 kg/m³ 0,001 bis 0,5 kg/m³ 0,005 bis 10 kg/m³
```
```
Rückführung ˳ direkte Messung ˳ direkte Messung,
Rückführbarkeit
über Ausliterung
von Volumen
```
```
˳ direkte Messung ˴ keine direkte Rück-
führbarkeit
```
```
Durchführung ˳ relativ einfache
Durchführung
˴ unflexible	Mess-
methode
```
```
˴ aufwendige
Messmethode
```
```
˳ relativ einfache
Durchführung
```
```
˳ sehr einfache
Durchführung
```
```
Temperaturan-
forderung
```
```
˴ homogene Temper-
atur erforderlich
```
```
˴ sorgfältige
Temperaturkontrol-
len notwendig
```
```
˴ exakte Temperatur
problematisch
```
```
˳ einfache
Temperierung
```
```
Messergebnis ˳ kein	Drift ˳ genaue Ergebnisse,
kein	Drift
```
```
˳ sehr genaue
Ergebnisse
```
```
˳ hochpräzise
Ergebnisse
˳ schnelle Ergebnisse
˳ kontinuierliche
Messung
Einfluss-
faktoren
```
```
˴ Messprobleme
durch Verdampfung
˴ Entmischung
˴ Ablesefehler
˴ grosse Probemenge
notwendig
```
```
˴ Messprobleme bei
hoher Viskosität
˴ Messung unter
Druck schwierig
```
```
˳ Messung unter
Druck möglich
˴ Messprobleme bei
hoher Viskosität,
Blasenbildung,
Verunreinigungen
˴ eingeschränkter
Messbereich
```

**Notizen:**


## Die Schwinger-Dichtemessung

```
Auf einen Blick
Im vorherigen Abschnitt haben wir die Grundlagen der Dichtemessung sowie die Definition von Dichte
kennengelernt. Der vorliegende Abschnitt widmet sich der Schwingungsmethode, die auch Dichtesen-
soren für die Dichtemessung verwendet. Aus dieser Methode ergeben sich einige Vor- und Nachteile, die
ausführlich beleuchtet werden.
```
Inhalte
•	Wie funktioniert die Schwinger-Dichtemessung?
•	Welche Vorteile ergeben sich?
•	 Was	sind	kritische	Einflussfaktoren	(Nachteile)?
•	Wo wird die Schwinger-Dichtemessung angewen-
det?
•	Ermittlung der Methanzahl in Gasmotoren zur
Effizienzsteigerung.

Wie funktioniert die Schwinger-Dichtemessung?
Bei der Schwinger-Dichtemessmethode wird die Dich-
te indirekt durch eine Frequenzbestimmung ge-
messen. Das zu messende Fluid wird dazu in ein Rohr
(Schwinger) gefüllt, das in Resonanzschwingung ver-
setzt wird. Die daraus resultierende Schwingungsfre-
quenz, die von der Dichte des Fluids sowie der Steifig-
keit des Schwingers abhängig ist, gibt nun Aufschluss
über die Dichte. Je grösser die Schwingungsfrequenz
ist, desto kleiner ist die Dichte des Fluids.

```
Abhängigkeit Fluiddichte/Schwingungsfrequenz
```
```
Oscillation frequency: Tube with water
```
```
Oscillation frequency: Tube with honey
```
```
u(t)
```
```
u(t)
```
```
t
```
```
t
```
```
Quelle: TrueDyne Sensors AG, Animation Biegeschwinger
```
Die Eigenschaften des Schwingers (u.a. Steifigkeit)
sind temperatur- und druckabhängig. Diese Abhän-
gigkeiten werden anhand von Kalibriermessungen
ermittelt und durch das Messgerät kompensiert.

```
Übrig bleibt als beeinflussbare Grösse somit nur die
Dichte des Fluids.
```
```
Die folgende Gleichung verdeutlicht den Zusammen-
hang zwischen der Dichte ρ des Fluids, den Eigen-
schaften des Schwingers (Konstanten A und B) sowie
der Schwingungsfrequenz f :
```
```
Zusammenhang zwischen Mediumsdichte ρ und
Schwingungsfrequenz f
```
```
Funktionsweise des Schwinger-Messgeräts:
•	Schwinger ist an beiden Enden fest eingespannt.
•	Erreger versetzt das Rohr in Schwingung.
•	Schwingungssensoren erfassen die Schwingungs-
frequenz.
```
```
Aufbau eines Schwinger-Messgeräts
```
```
Exciter
```
```
Vibration sensors
```
```
Firmly clamped resonator
```
```
Quelle: TrueDyne Sensors AG, Animation Biegeschwinger
```
```
Form und Materialien des Schwingers sind dabei nicht
fest vorgegeben. So kann es sich bei dem Schwinger
sowohl um ein Rundrohr als auch um ein Vierkant-
rohr handeln.
```
##### ρ = A +

B

```
⨍
2
```

Welche Vorteile ergeben sich?
Die einfache Handhabung, die mit einem geringen
prüftechnischen Aufwand einhergeht, ist einer der
grössten Vorteile der Schwinger-Dichtemessung. Die
Dichte wird nach Zugeben des Mediums gemessen,
ohne dass weitere Einstellungen vorgenommen wer-
den müssen. Ablesefehler können ausgeschlossen
werden, da die Ausgabe des Dichtwerts über eine di-
gitale Anzeige erfolgt. Eine Temperierung des Medi-
ums ist nicht notwendig, stattdessen erfolgt die Tem-
peraturmessung an Ort und Stelle. Zudem muss keine
exakte Volumenmenge entnommen werden.

Die mögliche Miniaturisierung der Technologie er-
fordert nur geringe Probemengen zur zuverlässigen
Dichtebestimmung. Diese Eigenschaft ist besonders
für kostspielige Medien relevant. Die Verwendung
geringer Probemengen erleichtert zudem die Bestim-
mung der Mediumstemperatur bei der Dichtemes-
sung.

Die Messung kann in einem geschlossenen System
und somit unter Druck erfolgen. Dies ist vor allem
für bestimmte Medien wie Alkohol-Wassergemische
oder Gase relevant. Ohne einen entsprechenden
Druck verflüchtigen sich solche Medien, was zu fal-
schen Messenwerten führen würde.

Schliesslich stehen die Messergebnisse bereits in kür-
zester Messzeit zur Verfügung.

Schwinger-Messgeräte können zudem für eine konti-
nuierliche Messung mit Durchfluss direkt im Prozess
eingesetzt werden.

Was sind kritische Einflussfaktoren (Nachteile)?
Die Methode ermöglicht keine direkte Rückführbar-
keit, d.h. der Dichtemesswert kann nicht mit den na-
tionalen Normalen (kg und m^3 ) für diese Messgrösse
verglichen werden. Grund dafür ist, dass die Dichte
über eine gemessene Frequenz berechnet wird. Für
die Berechnung sind mindestens zwei Referenzmedi-
en mit bekannter Dichte notwendig. Eine Rückführ-
barkeit ist daher nur über diese beiden Referenzme-
dien möglich.

Die Messempfindlichkeit wird durch die Beschaffen-
heit des Messrohrs beeinflusst. Je kleiner das Eigen-
gewicht des Messrohrs ist, desto geringer ist sein
Einfluss auf die Frequenz und umso höher ist die

```
Messempfindlichkeit. Die Bestimmung von geringen
Mediumsmassen bei gleichzeitig hohem Eigenge-
wicht des Messrohrs ist hingegen problematisch.
```
```
Die mechanischen Eigenschaften des Schwingers
werden durch Druck- und Temperatureinflüsse ver-
ändert. Infolgedessen verändert sich auch die Fre-
quenz. Durch Kalibrierungen mit verschiedenen
Druck- und Temperaturpunkten können diese Ab-
hängigkeiten kompensiert werden.
```
```
Darüber hinaus ist die Frequenz auch von der Visko-
sität der Messfluiden abhängig. Dies kann weitere
Messunsicherheiten zur Folge haben.
```
```
Luftblasen in der Messflüssigkeit können zudem zu
Messfehlern führen. Dies ist nicht der Fall, wenn vor
der Messung eine Entgasung vorgenommen wird.
```
```
Das Messergebnis kann durch Verunreinigungen des
Schwingers verfälscht werden. Ein sauberer Schwin-
ger ist an der korrekten Luftdichte im leeren Zustand
zu erkennen.
```
```
Wo wird die Schwinger-Dichtemessung ange-
wendet?
Die Bestimmung der Dichte von Fluiden mithilfe der
Schwinger-Dichtemessmethoden eignet sich be-
sonders in Branchen mit verschiedenen Genauigkeit-
sanforderungen in Labor und Prozess:
•	In der Öl- und Gasbranche z.B. zur Bestimmung
von Heizwert, Energiegehalt oder zur Ermittlung
der Zusammensetzung.
•	In Tankstellen zur Abrechnung des korrekten
Werts und bestimmen von Fremdpartikeln.
```
```
•	Im Transport zur Abrechnung des korrekten Wer-
tes und zur Kontrolle des Mediums.
```
```
•	Bei Flugzeugbetankungen zur Optimierung der
Füllmenge auf Distanz.
```
```
•	Bei Motorenprüfständen zur Prüfung der kons-
tanten	Treibstoffqualität.
```
```
•	Etc.
```

Welche Ausführungen von Schwinger-Dichtemessgeräten gibt es?

```
Beispiele: Schwinger-Dichtemessgeräte
```
```
Dichtemessgerät Baureihe DIMF 2.1: Dichtemes-
sung für Prozessmessungen von Bopp & Reuther
```
```
Gerätedimension: ca. 650 x 450 x 150 mm
Quelle: http://www.bopp-reuther.de/
```
```
Dichtemessgerät DMA 5000: Labor-Dichtemess-
gerät von Anton Paar. Universalgerät mit höch-
ster Präzision (0,000005 g/cm^3 ).
```
```
Gerätedimension: 482 x 340 x 231 mm
Quelle: http://www.anton-paar.com
```
```
UGC-Densitometer: Dichtemessgerät für Prozess-
messungen von AMETEK
```
```
Gerätedimension: ca. 450 x 200 x 100 mm
Quelle: http://www.ametekpi.com
```
```
MEMS-Dichtemodul: Dichtemessgerät für die In-
tegration in Systemen von TrueDyne Sensors AG
```
```
Gerätedimension: 80 x 30 x 15 mm
Quelle: http://www.truedyne.com
```

**Notizen:**


## Die MEMS-Technologie

```
Auf einen Blick
Im vorherigen Abschnitt haben wir die Schwingungsmessungsmethode kennengelernt. Der vorliegende
Abschnitt behandelt die Entstehung der MEMS-Technologie bei TrueDyne Sensors AG. Die Technologie
hat den MEMS-Sensor hervorgebracht, dessen Herzstück ein schwingender Silizium-Messkanal ist. Im
Vergleich zur konventionellen Schwinger-Technologie vereint er zahlreiche Vorteile. Diese reichen von
seiner geringen Grösse und einem breiten Anwendungsbereich über die exakte Dichtebestimmung von
Gasen, auch bei geringem Druck, bis hin zu einer überaus schnellen Reaktionszeit.
```
Inhalte
•	 Was ist die MEMS-Technologie?
•	 Wo werden MEMS-Technologien eingesetzt?
•	 Wie ist der TrueDyne Sensors AG MEMS-Chip
aufgebaut?
•	 Welche Chancen bietet die MEMS-Technologie?

Was ist die MEMS-Technologie?
MEMS steht für Micro-Electro-Mechanical Systems.
Die Technologie vereint mikroelektronische und mi-
kromechanische Komponenten in einem komplexen
Mikrosystem, das auf einer Silizium-Halbleitertech-
nologie basiert.

Bei der Halbleitertechnologie werden anhand ver-
schiedener Verfahrenstechniken, z.B. mit Fotolitho-
grafie und Dünnschichttechnik, mehrere elektro-
nische Komponenten auf einem Halbleiter-Substrat
(häufig aus Silizium) strukturiert und zu einem Chip
aufgebaut. Da die Einzelschritte für die Herstellung
eines Chips sehr aufwendig sind, vervielfältigt man
diese Arbeitsschritte und stellt mehrere Chips gleich-
zeitig her. Dies geschieht mit einem kreisrunden oder
quadratischen, scheibenförmigen Wafer, der aus
dem Material des benötigten Substrats besteht.

Mit der Halbleitertechnologie lassen sich elektro-
nische Schaltungen, die in der klassischen Elektronik
aus mechanisch angefertigten Komponenten be-
stehen, miniaturisieren. Ein TrueDyne Sensors AG
MEMS-Chip beinhaltet nicht nur elektronische, son-
dern auch mechanische und fluidische Funktionen.

Aufgrund der hohen Anforderungen an die einzelnen
Bauteile beschränkt sich ein TrueDyne Sensors AG
MEMS-Chip meist nicht nur auf ein Silizium-Substrat.
Stattdessen werden für die verschiedenen Kompo-
nenten unterschiedliche Materialien verwendet, die

```
mithilfe diverser Aufbau- und Verbindungstechniken
zusammengeführt werden.^1
```
```
Kreisrunde Wafer
```
```
Quelle: https://de.wikipedia.org/wiki/Wafer
```
```
Wo werden MEMS-Technologien eingesetzt?
MEMS-Technologien gewinnen immer mehr an
Bedeutung. Sie werden in den unterschiedlichs-
ten Gebieten eingesetzt und sind in unserem Alltag
allgegenwärtig. MEMS-Systeme finden vermehrt
in der Automobilindustrie Verwendung, z.B. zur
Diebstahlsicherung, für die Airbag-Kontrolle oder in
Fahrzeugüberschlag-Erkennungssystemen. Darüber
hinaus kommen sie im Mobilfunkbereich bei der Na-
vigation, zur Displayausrichtung oder beim mobilen
Gaming zum Einsatz. Grosses Anwendungspotenzial
von mikrofluidischen Systemen gibt es auch in der
Medizintechnik, insbesondere in der biomolekularen
Analytik. Stichwörter hier sind Lab-on-a-Chip oder
BioMEMS.
```
```
1 Quelle: Praxiswissen Mikrosystemtechnik, F. Völklein und T. Zetterer,
2006, Vieweg+Teubner Verlag
```

Wie hat sich die MEMS-Technologie bei TrueDy-
ne Sensors AG entwickelt?
TrueDyne Sensors AG arbeitet bereits seit eini-
gen Jahren an der Entwicklung und Umsetzung des
Coriolis-Messprinzips als fluidisches Mikrosystem
bzw. als MEMS-Chip. Dabei wird der für das Coriolis-
Mess-prinzip notwendige fluidische Kanal aus einem
Silizium-Substrat geformt und in einen MEMS-Chip
integriert.

Für die Messung von Durchfluss hat sich dieses Sys-
tem für TrueDyne Sensors AG nicht bewährt. Jedoch
hat sich gezeigt, dass der vibrierende Siliziumkanal
sehr gut als Schwinger-Dichtemesser eingesetzt
werden kann.

Wie ist der TrueDyne Sensors AG MEMS-Chip
aufgebaut?
Ein TrueDyne Sensors AG MEMS-Chip ist heute ge-
rade einmal 6,9 x 6,9 x 1,5 mm gross. Er beinhaltet
elektronische Komponenten, einen fluidischen Mess-
kanal sowie einen Temperatursensor.

```
TrueDyne Sensors AG MEMS-Chip
```
```
Quelle: Launch-Unterlagen DLO-M
```
Der TrueDyne Sensors AG MEMS-Chip wird mithilfe
von insgesamt vier Wafern hergestellt:

•	 Zwei Siliziumwafer bilden den Messkanal. Der
Messkanal wird mithilfe von Plasmaätztechnik
geformt.	Dazu	wird	je	eine	Hälfte	des	Kanals	in	
einen Siliziumwafer geätzt. Der Kanal entsteht
durch	die	Verbindung	der	beiden	Hälften	(Bon-
dingverfahren).
•	 Ein Glaswafer enthält metallische Elektroden,
fluidische	Öffnungen	sowie	den	Temperatursen-
sor.

```
•	 Ein weiterer Siliziumwafer dient dazu, den Mess-
kanal in Vakuum zu verpacken. Dadurch kann der
Messkanal	ohne	Luftdämpfung	schwingen.
```
```
Welche Chancen bietet die MEMS-Technologie?
Aufgrund der Miniaturisierung (Messkanal	=	 0,5 μl	
Volumen) und der Materialeigenschaften (Silizium)
des Kanals ergeben sich zahlreiche Vorteile und neue
Anwendungsbereiche.
```
```
Die Miniaturisierung gewinnt vor allem in Anwen-
dungen, bei denen geringe Probemengen und eine
kompakte Bauform wichtig sind, an grosser Bedeu-
tung.
```
```
Durch die thermischen und mechanischen Eigen-
schaften von Silizium steht zudem ein leistungsfähi-
ger Sensor zur Verfügung.
```
```
Silizium ist ein guter Wärmeleiter. Der Kanal ist
daher keinen grossen Temperaturunterschieden
ausgesetzt. Die für die Dichtemessung erforderliche
Temperaturinformation kann somit exakt und ein-
fach ermittelt werden.
```
```
Auch die mechanischen Eigenschaften von Silizium
sind bei der Dichtemessung von Vorteil. Durch die
geringe Eigenmasse und die geringe Steifigkeit des
Siliziumkanals wird eine sehr hohe Messempfind-
lichkeit erzielt. Diese Eigenschaft ist insbesondere
bei leichten Fluiden bzw. bei Gasen von Bedeutung.
So bleibt bei einer Gasmessung mit niedrigem Druck
(der derzeit spezifizierte Druckbereich liegt zwischen
1 und 20 bar) eine hohe Messempfindlichkeit erhal-
ten.
```
```
Der Siliziumkanal kann mit einer sehr hohen Fre-
quenz schwingen. Dies führt zu einer kurzen Mess-
zeit und zur Unabhängigkeit des Messsignals von
äusseren, mechanischen Störvibrationen.
```

**Notizen:**



