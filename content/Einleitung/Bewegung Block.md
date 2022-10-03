---
weight: 5000
title: "Bewegungsblock"
description: "How to manage the import of external libraries or thirdparties code?"
titleIcon: "fa-solid fa-right-to-bracket fa-rotate-90"
categories: ["Einleitung"]
tags: ["Configuration"]
---

![Please Work](https://ams03pap001files.storage.live.com/y4mwpvJkB3FWLiBi7BScKmSlYJ01UxDDTyyFmwygv8-eJnbs8Jixz8SPtCmN75mmEbRAsm8fHjRKIoiHvd5hcCoW8IaL6060yMLxqA7rmU5x8P6E3WBwP7FWBuPTXnlls4EQ0MxeDDeQFcRSUqrDUnw6mPcMBq5AkXo089wJR2XYkTVFeBndktmTmRbvtxFDVzc-RQejFT8JAuTAiWFDAKBg4Cd3bsMMNaGy6NKSFWh-1Y?encodeFailures=1&width=541&height=121)


# Beschreibung
---

Der Bewegungsblock ist einer der wichtigsten und meist verwendeten Blöcke. Er macht genau das, was der Name impliziert, er Bewegt den Roboter.

Der Roboter hat zur Bewegung bis zu 3 Motoren die durch A, B und C gegenzeichnet werden. Standartmäßig sind Motoren B und C für die Bewegung zuständig und der Motor A für etwas Besonderes macht z.B einen Greifarm bewegen.

# Funktionen
---

## Port:

![Port.png](/static/head.png)

Der Port gibt an welcher der Motoren angesteuert wird. Ihr könnt also alle Motoren gleichzeitig ansteuern oder einen individuell. Die Motoren mit einem Häkchen sind die, die angesteuert werden.

## Richtung:

![Richtung.png](https://files.nuclino.com/files/bcffcfff-4745-48ff-9c4c-a8375124fdf6/Richtung.png)

Richtung macht genau, was man vermuten würde.

**Pfeil nach oben:** lässt den Roboter **geradeaus** fahren.

**Pfeil nach unten:** lässt den Roboter **rückwärts**fahren.

**Stoppschild:** lässt den Roboter **stoppen**, bis er steht.

## Lenkung:

![Lenkung.png](https://files.nuclino.com/files/4e02c603-390f-4a44-a4e5-ff44386c9281/Lenkung.png)

Mit der Lenkung könnt ihr die Richtung angeben, in die der Roboter fahren soll. Die Verschiebung des Reglers nach links und rechts gibt an wie stark der Roboter sich drehen soll. Komplett nach links oder rechts verschoben dreht sich der Roboter im Kreis.

## Leistung:

![Leistung.png](https://files.nuclino.com/files/1ce013ba-683b-4e4e-be8e-d50d3b2eabfa/Leistung.png)

Die Leistung gibt Prozentual an wie schnell sich die Motoren drehen. Ihr könnt die Geschwindigkeit zwischen **0-100%** einstellen. Es braucht allerdings eine Mindestleistung, damit sich der Roboter bewegen kann.

## Dauer:

![Dauer.png](https://files.nuclino.com/files/9cc1be48-a460-4bd0-92a2-f9e5488eb872/Dauer.png)

Die Dauer gibt an wie lange der Roboter den Bewegungs-Block ausführt. Dafür gibt es verschiedene Optionen.

### Unbegrenzt:&#x20;

Die Motoren drehen sich bis ein Bewegungsblock mit der Richtung: "**Stopp"** abgespielt wird.

### Gradzahl:&#x20;

Die Motoren drehen sich um die angegebene Gradanzahl. (Eine Umdrehung sind 360°).

### Umdrehungen:&#x20;

Die Motoren drehen sich so oft um **360°** wie angegeben.

### Sekunden:&#x20;

Die Motoren drehen sich für die Anzahl der angegebenen Sekunden.

## Nächste Aktion:

![Nächste_Aktion.png](https://files.nuclino.com/files/761c4243-a859-4a35-aa64-a8605eea2a30/Nächste_Aktion.png)

Nächste Aktion gibt an was nach dem die Dauer abgelaufen ist passieren soll.

### Bremsen:&#x20;

Der Roboter bremst bis er zum Stehen kommt.

### Auslaufen:&#x20;

Der Roboter macht nichts.