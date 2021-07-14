# Codebuch: Spielerinnennetzwerk des Volleyballclubs MTV Stuttgart #


## Ursprung und Erhebung ##

https://www.stuttgarts-schoenster-sport.de/team/spielerinnen

Es handelt sich um ein two-mode Netzwerk.


## EDGE-Attribute ##

**id**

(eindeutige Kodierung des Knoten)


**relation**

Mitgliedschaft in Organisationen (wie Verein und Heimatland)

1 = Mitgliedschaft (Verein, Land)

2 = Teamkollegin

## NODE-Attribute ##

**id**

Identische ID aus der edgelist zur Identifikation der Knoten.


**name**

Name der Spielerin, des Vereins oder des Heimatlandes


**type**

Art des Akteurs

0 = Privatperson

1 = Organisation


**birth**

Geburtsjahr


**age**

Aktuelles Alter, codiert in Abschnitten

1 = 0-20 Jahre

2 = 21-23 Jahre

3 = 24-26 Jahre

4 = 27-30 Jahre



**position**

Position der Spielerin, codiert mit dem Anfangsbuchstaben der Positions-Bezeichnung

M = Mittelblock

A = Außenangriff

...


**country**

Heimatland, codiert mit den Länderabkürzungen nach ISO

NL = Niederlande

DE = Deutschland

...
