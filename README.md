# Übung 6 - Main & Static


## 1. Aufgabe

Folgendes Klassendiagramm soll umgesetzt werden:

<p align="center">
  <img src="/assets/images/UML1.png" alt="Bildbeschreibung" />
</p>

**Folgende Bedingungen gelten für die Eigenschaften:**
- `preis` muss größer 0 sein.
- `menge` muss größer-gleich 0 sein.

**Folgende Bedingungen gelten für die Methoden:**
- Im Konstruktor müssen statt der Zuweisung die `set`-Methoden aufgerufen werden.
- Die Parameternamen des Konstruktors müssen gleich den Eigenschaftsnamen sein.
- `verfuegbar()`: Überprüfen Sie, ob das Produkt verfügbar ist oder nicht. Wenn ja, geben Sie eine Meldung aus, in welcher angegeben wird wie viele Stück verfügbar sind. Wenn nein, geben Sie eine Meldung aus, welche besagt, dass das Produkt nicht verfügbar ist.
- `berechneGesamtwert()`: Es soll der Gesamtwert des Produkts berechnet und zurückgegeben werden. Geben Sie das Ergebnis zusätzlich mittels Ausgabe auf der Konsole aus.

Um Ihr Programm zu testen, erstellen Sie eine `Main`-Klasse, welche die `main`-Methode beinhaltet:
- `main(String[] args)`: Erstellen Sie zwei Instanzen der Produktklasse. Einmal mittels Standardkonstruktor und einmal mittels Konstruktor mit Parametern. Rufen Sie die Methoden `verfuegbar` und `berechneGesamtwert` auf. Verändern Sie mittels `set`-Methoden die Werte und rufen Sie die beiden Methoden erneut auf. Ist es möglich den Gesamtwert von beiden Produkten zu berechnen? Wenn ja, wie?

## 2. Aufgabe

Folgendes Klassendiagramm soll umgesetzt werden:

<p align="center">
  <img src="/assets/images/UML2.png" alt="Bildbeschreibung" />
</p>

Es werden drei Zahlen im Konstruktor, in beliebiger Reihenfolge, übergeben – d.h. `a1` ist nicht immer die größte Zahl.
**Achtung:** Die Parameter heißen diesmal nicht wie die Eigenschaften!
Danach wird jedoch die größte Zahl (aus `a1`, `b1`, `c1`) im Attribut `a` gespeichert, die Zweitgrößte im Attribut `b` und die Kleinste im Attribut `c`. Die `print`-Methode gibt die drei Zahlen aus.

Um Ihr Programm zu testen, erstellen Sie eine `Main`-Klasse, welche die `main`-Methode beinhaltet:
- `main(String[] args)`: Erstellen Sie drei Instanzen der `Sortiert3`-Klasse und wählen Sie dabei verschiedene Zahlen. Geben Sie die Zahlen mittels `print`-Methode aus.

## 3. Aufgabe


Folgendes Klassendiagramm soll umgesetzt werden:

<p align="center">
  <img src="/assets/images/UML3.png" alt="Bildbeschreibung" />
</p>

**Beschreibung der Methoden:**
- Im Konstruktor müssen statt der Zuweisung die set-Methoden aufgerufen werden.
- Die Parameternamen des Konstruktors müssen gleich den Eigenschaftsnamen sein.
- `rechne()`: Überprüfen Sie den `operator` mittels `switch`-Anweisung. Der `operator` darf die Werte `+`, `-`, `*`, `/` annehmen. Sollte der `operator` einen anderen Wert annehmen, geben Sie eine Fehlermeldung aus. Hat der `operator` einen gültigen Wert, führen Sie die jeweiligen Rechenoperationen aus und geben Sie das Ergebnis in der Konsole aus.

**Hinweis:** Worauf müssen Sie bei der Division achten?

Um Ihr Programm zu testen, erstellen Sie eine `Main`-Klasse, welche die `main`-Methode beinhaltet:
- `main(String[] args)`: Erstellen Sie zwei Instanzen der Taschenrechnerklasse. Einmal mittels Standardkonstruktor und einmal mittels Konstruktor mit Parametern. Rufen Sie die `rechne`-Methode auf und probieren Sie alle Werte für den `operator` aus der Taschenrechnerklasse aus.

