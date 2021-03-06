# Glossar :closed_book:

**Erläuterung und Verknüpfung von Begriffen rund um Softwaretechnologie**

Es ist für Anfänger nicht immer leicht den Überblick über all die relevanten (Fach-)begriffe zur Softwaretechnologie zu behalten. Genau das ist aber sehr wichtig für das Verständnis von Lehrveranstaltungen, Büchern, Dokumentationen etc.! Im Folgenden sind die wichtigsten (nicht Java-spezifischen!) Begriffe alphabetisch sortiert aufgelistet, kurz erläutert und miteinander verknüpft.

> :construction: :snail:
> Dieses Verzeichnis wird wohl für immer **_work in progress_** sein!

> :warning:
> **Achtung:** Hier sind die Java-spezifischen Themen aus dem eigentlichen [Java-Wegweiser](https://dh-cologne.github.io/java-wegweiser) **nicht noch einmal aufgeführt**. Es geht hier um **allgemeine** Software-Terminologie!

> :speech_balloon:
> In diesem Stichwort-Verzeichnis geht es außerdem **nicht** um [ulkige Bezeichnungen für Dinge aus der Welt des Programmierens](https://blog.codinghorror.com/new-programming-jargon/) (schade!), sondern um allgemeine Begriffe, die zur Kommunikation über das Programmieren und Quelltext genutzt werden.

> :milky_way:
> **TODO:** `Design Pattern`, `Entwurfsmuster`, `Listener`, `Kommandozeile`, `Konsole`, `Terminal` ...



## Legende
:point_right: Verweis auf einen anderen Begriff in diesem Verzeichnis  
:telescope: Verweis auf einen Artikel / Abschnitt im [Java-Wegweiser](https://dh-cologne.github.io/java-wegweiser)  
:link: Verweis auf eine externe Ressource (meist Wikipedia)




## A

### Abstraktion
Trennung von Konzept und Umsetzung (:point_right: [Implementation](#implementation)). 

### Algorithmus
Abfolge von aufeinanderfolgenden Einzelschritten zur Lösung eines Problems; siehe auch :link: [Algorithmus](https://de.wikipedia.org/wiki/Algorithmus).

### Anweisung
Siehe :point_right: [Statement](#statement) (eng.) oder Instruktion (unüblich)

### API
Kurz für _**A**pplication **P**rogramming **I**nterface_ (deu.: _Anwendungs­programmier­schnittstelle_). Eine Schnittstelle zur Anbindung an Anwendungen auf Quelltext-Ebene (nicht Binärcode). Siehe auch :link: [Programmierschnittstelle](https://de.wikipedia.org/wiki/Programmierschnittstelle).

### Arbeitsspeicher

Der Speicher eines Computers, der die gerade laufenden Programme und verwendeten Daten enthält. Auch: _Hauptspeicher_ bzw. eng. _(main) memory_ oder _RAM (Random Access Memory)_.

### Argument
Siehe :point_right: [Parameter](#parameter)

### Attribut
Ein einem Objekt zugeordnetes Merkmal bzw. Eigenschaft. Wird oft als anderes Wort für :point_right: [Instanszvariable](#instanzvariable) genutzt.

### Ausdruck
Eine Kombination aus Variablen, Literals, Konstanten, Operatoren und Rückgabewerten von Methoden. Ein Ausdruck ergibt als ganzes einen Wert. Z.B. hat der Ausdruck `2 < 9` den Wert `true` und der Ausdruck `(4 - Math.max(15, 46)) * ( 1 + 1 == 1 ? 1 : -1)` den Wert `42`.

### Aussage
:point_right: [Ausdruck](#ausdruck) mit einem :point_right: [Wahrheitswert](#wahrheitswert), etwa `2 == 7` (hat üblicherweise den Wert `false`). Auch: Englisch für :point_right: [Statement](#statement) (aber als deutsche Entsprechung dafür eher unüblich im Programmier-Kontext).


## B

### Bezeichner
Von dem/der Programmierer*in frei (aber gut) gewählter Name für eine :telescope: [Klasse](articles/Klassen-und-Objekte.md), eine :telescope: [Methode](articles/Methoden.md) oder eine :telescope: [Variable](articles/Variablen.md).

### Bug
Fehler in einem Computerprogramm.


## C

### Code
Englisch für :point_right: [Quelltext](#quelltext); auch: Ein System zum Umwandeln von Informationen.

### Compiler
Computerprogramm, das den Quelltext einer Programmiersprache in Maschinencode übersetzt, der von einem Computer ausgeführt werden kann. Im Falle von Java ist das :telescope: [Bytecode](articles/Die-Programmiersprache-Java.md), der von der :telescope: [JVM](articles/Die-Programmiersprache-Java.md) ausgeführt werden kann. Siehe auch: :link: [Compiler](https://de.wikipedia.org/wiki/Compiler).

### Control flow
Englisch für :point_right: [Kontrollfluss](#kontrollfluss).

### CPU
**C**entral **P**rocessing **U**nit. Siehe auch :link: [Prozessor](https://de.wikipedia.org/wiki/Prozessor)


## D

### Datenklasse
Eine Klasse ohne eigene Logik / Funktionalität. Für gewöhnlich umfasst eine Datenklasse nur :point_right: [Instanzvariablen](#instanzvariable) und ggf. :telescope: [Getter und Setter](articles/Objekte-I-Initialisierung-Members-Zugriff.md). Auch: _POJO_.

### Datentyp
Siehe :telescope: [Datentypen](articles/Datentypen.md).

### Debugger
Eine Software (oft eine Komponente einer :point_right: [IDE](#ide)), die als Werkzeug für das :point_right: [Debugging](#debugging) verwendet wird.

### Debugging
Das Auffinden und Beheben von :point_right: [Bugs](#bug). Dazu _kann_ ein :point_right: [Debugger](#debugger) genutzt werden, muss aber nicht.

### Deklaration
Die _Deklaration_ einer :telescope: [articles/Variable](Variablen.md) besteht aus der Angabe ihres :telescope: [Datentyps](articles/Datentypen.md) und ihres Namens (_Variablenname_), etwa `int thisIsAnInteger`.

### Deployment
Der Vorgang des Installierens einer Software auf dem Zielsystem. Auch: _Auslieferung_ oder :link: [_Softwareverteilung_](https://de.wikipedia.org/wiki/Softwareverteilung).


## E

### Endlosschleife
:telescope: [Schleife](articles/Schleifen.md) oder :telescope: [Rekursion](articles/Rekursion.md), die durch fehlende oder nicht erreichbare Abbruchbedingung (oder immer wahre Ausführungsbedingung) nie beendet wird und letztendlich zu einem Programmabsturz führt. Siehe auch :link: [Endlosschleife](https://de.wikipedia.org/wiki/Endlosschleife).

### Exit-Code
Auch: _Exit-Status_, _Return Code_ oder _Rückgabestatus_. Ein numerischer Wert, den ein Programm zurückgibt, wenn es sich beendet (oder beendet wird). Dabei steht `0` üblicherweise für ein reguläres (fehlerfreies) Programm-Ende, andere Werte für unterschiedliche Programm-Abbrüche durch Fehler. Siehe auch :link: [Return Code](https://de.wikipedia.org/wiki/Return_Code)

### Expression
Englisch für :point_right: [Ausdruck](#ausdruck).


## F

### Funktion
Ein :point_right: [Code](#code)-Block, der über einen Namen (:point_right: [Bezeichner](#bezeichner)) angesprochen und ausgeführt werden kann. Es ist ggf. möglich/nötig, der Funktion :point_right: [Parameter](#parameter) zu übergeben. Außerdem _können_ Funktionen am Ende ihrer Ausführung Daten :link: [zurückgeben](https://de.wikipedia.org/wiki/Funktion_(Programmierung)#Direktes_Verwenden_des_Ergebnisses). Siehe auch: :telescope: [Methode](articles/Methoden.md).


## G

### Getter
Siehe :telescope: [Getter und Setter](articles/Objekte-I-Initialisierung-Members-Zugriff.md).

### GUI
**G**raphical **U**ser **I**nterface (_deu.: grafische Benutzeroberfläche_); eine grafische, nicht :point_right: [Kommandozeilen](#kommandozeile)-basierte Benutzerschnittstelle eines Programmes.

### Gültigkeitsbereich
Der Gültigkeitsbereich eines :point_right: [Bezeichners](#bezeichner) (Methodenname, Variablenname, etc.) ist der Bereich im :point_right: [Quelltext](#quelltext), von dem aus der Zugriff auf diesen Bezeichner möglich ist; auch: :point_right: [Scope](#scope).


## H

### Hard Coding
Das Verwenden von expliziten Werten (mittels :point_right: [Literals](#literal)) direkt im Quelltext. Von Hard Coding (auch: etwas ist _hard-coded_) sprcht man etwa, wenn der Pfad zu einer Datei, die Zugangsdaten zu einer Datenbank o.ä. direkt in den Quelltext geschrieben werden statt sie z.B: aus einer Konfigurationsdatei zu laden, sie von User abzufragen oder aus einer sonstigen externen Quelle abzuleiten. Siehe auch: :link: [Hard Coding](https://en.wikipedia.org/wiki/Hard_coding). 

### Hauptspeicher
Siehe :point_right: [Arbeitsspeicher](#arbeitsspeicher).

### high-level
Sich auf einer hohen (:point_right: [Abstraktions](#abstraktion)-)Ebene befindend. Beschreibt z.B. Code, der durch die Verwendung einer entsprechenden :point_right: [Programmbibliothek](#programmbibliothek), die technische Details :point_right: [kapselt](#kapselung), sehr einfach lesbar und semantisch verständlich ist. Gegenteil von :point_right: [low-level](#low-level).

## I

### IDE
**I**ntegrated **D**evelopment **E**nvironment (dt.: _Integrierte Entwicklungsumgebung_). Siehe auch :telescope: [Eclipse IDE](articles/Eclipse-IDE.md).

### Implementierung
Das Umsetzen (oder "Einbauen") eines geplanten Konzeptes oder einer Spezifikation als Software (also in Quellcode). Beispiel: Implementieren eines :point_right: [Interfaces](#interface) oder eines neuen Programm-Features. Siehe auch :link: [Implementierung](https://de.wikipedia.org/wiki/Implementierung#Softwaretechnik).

### Index
Ein :telescope: [Integer](articles/Datentypen.md) größer oder gleich `0`, der auf ein Element in einem :telescope: [Array](articles/Arrays.md) oder einer ähnlichen linearen :telescope: [Datenstruktur](articles/DIY-Datenstrukturen.md) verweist; auch: Eine :link: [spezielle Datenstruktur zur Nutzung in einer Suchmaschine](https://de.wikipedia.org/wiki/Suchmaschine).

### Instanz
Siehe :telescope: [OOP-Einführung](articles/OOP-Einfuehrung.md) bzw. :telescope: [Klassen und Objekte](articles/Klassen-und-Objekte.md).

### Instanzvariable
Siehe :telescope: [Arten von Variablen](articles/Variablen.md#arten-von-variablen).

### Instruktion
:point_right: [Statement](#statement) oder Anweisung; englisch.: _instruction_.

### Interface
Englisch für :point_right: [Schnittstelle](#schnittstelle). Im Kontext von OOP siehe auch :telescope: [Interfaces](articles/Vererbung-III-Interfaces.md).


## J

...


## K

### Kapselung
Verbergen von Daten, Informationen oder Programmlogik vor (ungeregeltem) Zugriff von "außen". Auch wichtiges Mittel zur Erstellung von aufgeräumtem, wartbarem Quellcode. Siehe auch :link: [Datenkapselung (Programmierung)](https://de.wikipedia.org/wiki/Datenkapselung_(Programmierung)#Herleitung) und (speziell mit Bezug auf :telescope: [OOP](articles/OOP-Klassen-und-Objekte.md)) :link: [Datenkapselung im objektorientierten Paradigma](https://de.wikipedia.org/wiki/Datenkapselung_(Programmierung)#Datenkapselung_im_objektorientierten_Paradigma).

### Klasse
Siehe :telescope: [OOP-Einführung](articles/OOP-Einfuehrung.md) bzw. :telescope: [Klassen und Objekte](articles/Klassen-und-Objekte.md).

### Klassenvariable
Siehe :telescope: [Arten von Variablen](articles/Variablen.md#arten-von-variablen).

### Komplexität
> Konzept zur Abschätzung des Ressourcenaufwandes zur :point_right: [algorithmischen](#algorithmus) Behandlung bestimmter Probleme. — :link: [Wikipedia](https://de.wikipedia.org/wiki/Komplexit%C3%A4t#Informatik)

### Kontrollfluss
Die Steuerung des Ablaufs eine Programmes. Für den Kontrollfluss werden :telescope: [Konditionale](articles/Konditionale.md) und :telescope: [Schleifen](articles/Schleifen.md) genutzt, die das Programm abhängig von festgelegten :point_right: [Bedingungen](#bedingung) steuern.


## L

### Laufzeit
(1.) Zeitraum, in dem ein Programm läuft bzw. ausgeführt wird; (2.) :point_right: [Performanz](#performanz) eines :point_right: [Algorithmus](#algorithmus) oder sonstigen Programmteils. Siehe auch :link: [Laufzeit (Informatik)](https://de.wikipedia.org/wiki/Laufzeit_(Informatik)).

### Library
Kurz und Englisch für :point_right: [Programmbibliothek](#programmbibliothek).

### Literal
Ausdruck, der zur direkten Darstellung eines Wertes (numerischer Wert, String, Array, ...) genutzt wird. Mit Literals werden Werte :point_right: "[hard coded](#hard-coding)" in den Quelltext geschrieben. Siehe auch: :link: [Literal](https://de.wikipedia.org/wiki/Literal).

### Lokale Variable
Siehe :telescope: [Arten von Variablen](articles/Variablen.md#arten-von-variablen).

### low-level
Sich auf einer niedrigen (:point_right: [Abstraktions](#abstraktion)-) Ebene befindend. Beschreibt z.B. Code, der ohne den Einsatz von Frameworks o.ä. arbeitet oder maschinennahe Programme wie Treiber. Gegenteil von :point_right: [high-level](#high-level).


## M

### Member
Englisch für _Mitglied_; Überbegriff für :point_right: [Attribute](#attribut) und :point_right: [Methoden](#methode) einer :point_right: [Klasse](#klasse).

### Memory
Meist kurz für _main memory_ (Englisch für :point_right: [Arbeitsspeicher](#arbeitsspeicher)).

### Methode
Eine :point_right: [Funktion](#funktion), die ein :point_right: [Member](#member) einer :point_right: [Klasse](#klasse) ist. Siehe auch: :telescope: [Methoden](articles/Methoden.md).

### Multiprocessing
:point_right: [Multitasking](#multitasking) auf mehreren :link: [CPUs](https://de.wikipedia.org/wiki/Prozessor).

### Multitasking
Die Fähigkeit einer einzelnen :link: [CPU](https://de.wikipedia.org/wiki/Prozessor), mehr als eine Aufgabe gleichzeitig zu bearbeiten. Dies funktioniert, indem das Betriebssystem verschiedenen Tasks nach und nach Rechenzeit zuteilt.

### Multithreading
Das Ausführen mehrerer :point_right: [Threads](#thread) in einem :point_right: [Prozess](#prozess).

## N

### Nullwert
Auch **NULL** oder **NIL**. Ein Zustandswert, der die Abwesenheit eines Wertes kennzeichnet. Es wird mit diesem Wert also ausgedrückt, dass kein Wert vorhanden ist. In Java: `null`.


## O

### Objekt
Eine :point_right: [Instanz](#instanz) einer :telescope: [Klasse](articles/OOP-Einfuehrung.md); siehe auch :telescope: [Klassen und Objekte](articles/Klassen-und-Objekte.md).

### Objekt-Gleichheit
Die _Gleichheit_ (eng. _equality_) zweier :point_right: [Objekte](#objekt) ist gegeben, wenn diese sich in Hinsicht auf alle (oder bestimmte festgelegte) :point_right: [Eigenschaften](#attribut) gleichen.

### Objekt-Identität
Die _Identität_ (eng. _identity_) zweier :point_right: [Objekte](#objekt) ist gegeben, wenn diese überhaupt nicht zwei Objekte sind, sondern nur eines. Und zwar _das selbe_ (an der selben Stelle im :point_right: [Arbeitsspeicher](#arbeitsspeicher)).

### Operation
Verarbeitungsschritt in einem Software-Programm. Siehe auch :link:[Operation](https://de.wikipedia.org/wiki/Operation_(Informatik)).


## P

### Parameter
Bei der Ausführung an ein Programm oder eine :telescope: [Methode](articles/Methoden.md) übergebene Daten; auch: :point_right: [Argument](#argument).

### Performance
Englisch für :point_right: [Performanz](#performanz).

### Performanz
Eigenschaft eines Programmes oder Programmteils, viel oder wenig Rechenzeit in Anspruch zu nehmen (seltener benutzt im Kontext von Speicherbedarf). Siehe auch :point_right: [teuer](#teuer).

### POJO
**P**lain **O**ld **J**ava **O**bject - oft umgangssprachlich für eine :point_right: [Datenklasse](#datenklasse) in Java.

### Polymorphie
Konzept in der objektorientierten Programmierung: Ein :point_right: [Bezeichner](#bezeichner) (:telescope: [Variable](articles/Variablen.md)) kann Objekte unterschiedlichen :point_right: [Datentyps](#datentyp) referenzieren. Dabei hat der Bezeichner einen gleichen oder höherwertigen Datentyp, als das referenzierte Objekt. Beispiel: `SpecialUser su = new SpecialUser(); User u = su;` Siehe auch :link: [Polymorphie](https://de.wikipedia.org/wiki/Polymorphie_(Programmierung)).

### Programmbibliothek
Sammlung von Programmbestandteilen, die in anderen Programmen verwendet werden können. Dies geschieht über die Benutzung der :point_right: [API](#api) der entsprechenden Bibliothek. Siehe auch :link: [Programmbibliothek](https://de.wikipedia.org/wiki/Programmbibliothek).

### Prozess
Ein laufendes Programm im Kontext eines Computersystems. Siehe auch: :point_right: [Thread](#thread).


## Q

### Quelltext
Das, was ein/e Programmierer\*in schreibt, um eine Software zu programmieren; auch: :point_right: [Code](#code).


## R

### Race Condition
Ursache für sehr schwer auffindbare :point_right: [Bugs](#bug). Entsteht, wenn das Ergebnis einer :point_right: [Operation](#operation) vom zeitlichen Ablauf zweier einzelner anderer Operationen abhängt (z.B. zwei :telescope: [Threads](articles/Multithreading.md), die auf die selbe Variable zugreifen). Siehe auch :link: [Wettlaufsituation](https://de.wikipedia.org/wiki/Wettlaufsituation).

### Refactoring
Verbesserung der Struktur des :point_right: [Quelltextes](#quelltext) eines Programms, ohne dessen Verhalten zu verändern.

### Referenz
Verweis auf einen Wert (:telescope: [primitiver Wert](articles/Datentypen.md) oder :telescope: [Pointer](articles/Methoden.md#java-ist-immer--pass-by-value) auf ein :telescope: [Objekt](articles/OOP-Einfuehrung.md)), etwa eine :telescope: [Variable](articles/Variablen.md), oder ein :point_right: [Index](#index) eines :telescope: [Arrays](articles/Arrays.md).

### Runtime
Englisch für :point_right: [Laufzeit](#laufzeit).


## S

### Schnittstelle
Genormte oder mindestens genau beschriebene logische Berührungspunkte von (Software-) Systemen. Siehe auch :telescope: [Interfaces](articles/Vererbung-III-Interfaces.md).

### Scope
Englisch für :point_right: [Gültigkeitsbereich](#gültigkeitsbereich).

### Setter
Siehe :telescope: [Getter und Setter](articles/Objekte-I-Initialisierung-Members-Zugriff.md).

### Standard-Datenströme
Drei Datenströme (:point_right: [Stdout](#stdout), :point_right: [Stdin](#stdin) und :point_right: [Stderr](#stderr)) zur Daten Ein-/Ausgabe zwischen einem Programm und dem Betriebssystem bzw. der Umgebung, in der das Programm ausgeführt wird. Siehe auch :link: [Standard-Datenströme]([Standard-Datenströme](https://de.wikipedia.org/wiki/Standard-Datenstr%C3%B6me)).

### Statement
Eigentlich englisch für "Aussage", im Programmier-Kontext sind aber unterschiedliche Dinge damit gemeint. In Java gibt es **drei verschiedene** Arten von Statements: _Expression Statements_ (siehe :point_right: [Ausdruck](#ausdruck)), _Declaration Statements_ (siehe :point_right: [Deklaration](#deklaration)) und _Control-flow statements_ (siehe :point_right: [Kontrollfluss](#kontrollfluss)).

### Stderr
Error-Datenstrom der :point_right: [Standard-Datenströme](#standard-datenströme). Kurz für _Standard Error_.

### Stdin
Eingabe-Datenstrom der :point_right: [Standard-Datenströme](#standard-datenströme). Kurz für _Standard Input_.

### Stdout
Ausgabe-Datenstrom der :point_right: [Standard-Datenströme](#standard-datenströme). Kurz für _Standard Output_.

### Syntactic sugar
:point_right: [Syntax](#syntax)-Feature einer Programmierprache, mit dem eine bestimmte Anweisung (ö.ä.) einfacher oder leichter lesbar formuliert werden kann. Siehe auch :link: [Syntactic sugar](http://en.wikipedia.org/wiki/Syntactic_sugar).

### Syntax
System zur Formung gültiger ([Quell-](#quelltext))Texte aus dem Zeichenvorrat einer Sprache. Siehe auch :link: [Syntax](https://de.wikipedia.org/wiki/Syntax#Syntax_formaler_Sprachen).

## T

### Test
Im Kontext der Softwaretechnologie: Testet eine Software auf Funktionalität und Qualität. Niedrigste Stufe sind :point_right: [Unit Tests](#unit-test) (oder: _Komponententests_), die einzelne Komponenten / Einheiten der Software testen. Für Erläuterungen zu weiteren Arten von Tests auf höheren Ebenen siehe auch :link: [Softwaretest](https://de.wikipedia.org/wiki/Softwaretest).

### teuer
Als "teuer" wird umgangssprachlich eine Operation bezeichnet, die vergleichsweise viel Rechenleistung und/oder Speicher kostet. Siehe auch :point_right: [Laufzeit](#laufzeit) und :point_right: [Performanz](#performanz).

### Thread
Ein _Ausführungsstrang_ in einem Computerprogramm. Threads sind Teil eines :point_right: [Prozesses](#prozess). Auch: _Leichtgewichtiger Prozess_; siehe auch: :link: [Thread](https://de.wikipedia.org/wiki/Thread_(Informatik)).


## U

### Unit Test
:point_right: Software-[Test](#test) zum testen einzelner Programm-Komponenten.


## Ü

### Überladen
Siehe :telescope: [Methoden &rArr; Überladen von Methoden](articles/Methoden.md#%C3%BCberladen-von-methoden).

### Überschreiben
Siehe :telescope: [Vererbung-I-Grundlagen &rArr; Überschreiben von Methoden](articles/Vererbung-I-Grundlagen.md#%C3%BCberschreiben-von-methoden).


## V

...


## W

### Wahrheitswert
Wert einer :point_right:[Aussage](#aussage). Kann (im Programmier-Kontext) `true` oder `false` sein und ist somit vom :telescope: [Datentyp](articles/Datentypen.md) `boolean` (bzw. `Boolean`).

### Wrapper
Programm-Einheit (z.B. eine Klasse oder eine ganze Library), die als :point_right: [abstrahierende](#abstraktion) Zwischenschicht um eine komplexere Logik (:point_right: [low-level](#low-level)) gebaut ist. In Java auch: Die Klassen `Boolean`, `Integer`, `Double`, [...], die als komplexe "Verpackung" um die primitiven Datentypen fungieren.


## X

...


## Y

...


## Z

### Zuweisung
:point_right: [Operation](#operation), bei der einer :telescope: [Variable](articles/Variablen.md) (oder einer Speicherstelle eines :telescope: [Arrays](articles/Arrays.md)) ein Wert zugewiesen wird (mittels des _Zuweisungsoperators_ `=`).







<!-- Dieses HTML-Snippet sollte am Ende jeder Seite stehen! -->
<div class="top-link">
    <a href="#" title="Zum Anfang scrollen!">Top :balloon:</a>
    <br/>
    <a href="https://dh-cologne.github.io/java-wegweiser#inhalt-book" title="Zurück zur Übersicht!">Inhalt :book:</a>
</div>