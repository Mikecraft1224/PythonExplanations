# Datentypen

## Erste Typen: str, int und float
---

In Python gibt es mehrere Datentypen, wie z.B. `str`(string), `int`(integer) und `float`(floating point numbers).  
Ein String wird IMMER durch `""` umgeben.  
Das Dezimaltrennzeichen bei einem `float` ist ein Punkt, kein Kommata. (internationale Darstellung).
```py
BeispielFürEinenString = "2022"
BeispielFürEinenInteger = 2022
BeispielFürEinFloat = 0.5
```  
<br>

## Weitere Typen: bool
---
Ein `bool`(boolean) ist ein s.g. Wahrheitswert.  
Das bedeutet, der `bool` kann 2 Zustände haben, wahr und falsch oder in der Programmierung `True` und `False`.
```py
BeispielFürEinBool = False
StringRepresentation = "False"
```
<br>

## None-Type
---
Es gibt in Python einen s.g. `None`-Type.  
Dieser wird verwendet um z.B. Variablen zu erstellen, diesen aber keinen Wert zuzuweisen.  
Dieser kann im Nachhinein mit irgendeinem Typ überschrieben werden.
```py
BeispielFürEinNoneType = None
#Überschreiben des NoneTypes
BeispielFürEinNoneType = "Hallo"
```
<br>

## Typabfrage
---
Wir können in Python den Typ einer Variable abfragen.  
Das können wir mithilfe einer s.g. builtin-function machen.  
In diesem Fall verwenden `type(...)`.  
```py
BeispielFürEinenString = "Hallo Welt"
type(BeispielFürEinenString) #Liefert str zurück
```