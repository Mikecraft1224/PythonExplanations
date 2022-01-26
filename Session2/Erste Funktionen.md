# Erste Funktionen

## print(...)
---
Print ist eine sehr wichtige Funktion, mit der du `strings` oder andere Variablen in der Konsole ausgeben kannst.
```python
variable = 5
print(variable)
```
Wir können aber auch direkt einen `string` oder andere Dinge printen, indem wir dies in die geöffneten Klammern schreiben.
```
print("Hello World")
```
Damit können wir das standardmäßige "Hello World"-Programm schreiben.  
<br>

## Bedingungen
---
Wir können auch Bedingungen in unseren Code einbauen.  
Das geht mit einem sogenanten if-else-Block oder einem if-statement.  
```python
variable = 5

if variable == 5:
    print("Wurde ausgeführt") #Funktioniert
if variable != 5:
    print("Wurde ausgeführt") #Funktioniert nicht
if variable > 5:
    print("Wurde ausgeführt") #Funktioniert nicht
if variable < 5:
    print("Wurde ausgeführt") #Funktioniert nicht
if variable >= 5:
    print("Wurde ausgeführt") #Funktioniert
if variable <= 5:
    print("Wurde ausgeführt") #Funktioniert
if variable > 0 and variable < 10:
    print("Wurde ausgeführt") #Funktioniert
if variable < 0 or variable == 5:
    print("Wurde ausgeführt") #Funktioniert
```
Dabei können wir verschiedene Logikoperatoren verwenden. Es gibt folgende:  
"==":  ist gleich  
"!=":  ist ungleich  
">":   ist größer  
"<":   ist kleiner  
">=":  ist größer gleich  
"<=":  ist kleiner gleich  
"and": True wenn beide True sind  
"or":  True wenn eines True ist  
Stichwort [Boolesche Algebra](https://de.wikipedia.org/wiki/Boolesche_Algebra)  
<br>
Nach einer if-Abfrage gibt es noch zwei weitere Dinge, die damit verknüpft sind; `elif` und `else`.
```python
variable = 5

if variable < 0 or variable == 5:
    print("If Wurde ausgeführt") #Funktioniert
elif variable == 10:
    print("Elif wurde ausgeführt") #Funktioniert nicht
else:
    print("Else wurde ausgeführt") #Funktioniert auch nicht
```
Was machen diese jetzt?  
Ein `elif` ist eine weitere Abfrage, die aber nur ausgeführt wird, wenn die Abfrage des vorherigen ifs oder elifs False lieferte.  
Das bedeutet, dass in jedem if-else-Block nur ein einziges Statement ausgeführt wird.  
Das `else` deckt alle Fälle ab, die bisher noch nicht in einem if oder elif abgedeckt wurden.
```python
variable = 5

if variable == 10:
    ...
elif variable == 5:
    ...
else:
    ...

#entspricht:

if variable == 10:
    ...
else:
    if variable == 5:
        ...
    else:
        ...
```
Man kann auch mehrere elifs haben.
```python
variable = 5

if variable == 10
    print("Die Zahl war 10")
elif variable == 7:
    print("Die Zahl war 7")
elif variable == 2:
    print("Die Zahl war 2")
elif variable == 5:
    print("Die Zahl war 5")
else:
    print("Die Zahl war nicht 10, 7, 2 oder 5")
```