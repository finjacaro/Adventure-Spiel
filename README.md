# Adventure-Spiel

Nachdem wir uns in unserem ersten Halbjahr gut in das Programm Star Logo TNG eingearbeitet hatten, entschlossen wir uns auch bei unserem  nächsten Projekt dieses Programm zu verwenden. 
Unser Ziel ist es ein Adventure Spiel mit verschiedenen Levels zu programmieren, in denen der Agent verschiedene Aufgaben, die mit der Höhe des Levels immer schwerer werden, bewältigen muss.

[Zweite Stunde](#zwei)

[Erste Stunde](#eins)

## Zweite Stunde<a name="zwei"></a>

Unser heutiger Plan war, das zweite Level zu bearbeiten. 

## Erste Informatikstunde<a name="eins"></a>

In der ersten Stunde haben wir die Basis für unser Spiel geschaffen, indem wir einen Agenten programmierten und das Terrain bearbeiteten. Wir erschufen Bäume und ein Auto, zu welchem der Agent gelangen muss um in das nächste Level (Level 2) aufzusteigen.  
Damit man die verschiedenen Gegenstände auf der Karte besser erkennen kann, haben wir die Bäume grün und das Auto blau eingefärbt. Allerdings verfärben sich nur die Punkte auf der Karte und nicht die Objekte selber, da sie eine "Haut" tragen. Als unseren Agenten wählten wir Mario, dessen Haut wir entfernten und ihn darauf rot einfärbten, um ihn in dem Spaceland besser erkennen zu können. Dies konnten wir mit Hilfe eines "model skin off"-Blockes verwirklichen.

![screenshot1](Bilder/Screenshot01.png "1")

Um unseren Arbeitsplatz bei Star Logo TNG übersichtlich und organisiert aufzubauen, programmierten wir die Steuerung von Mario in einem Block. Dazu verwendeten wir den "procedure"-Block und nannten ihn Bewegung. An diesen hängten wir mehrer "if"-Blöcke um die Bedingungen für die Steuerung festzulegen. Es muss also zum Beispiel die Pfeiltaste nach oben gedrückt werden, um Mario vorwärts laufen zu lassen. 

![screenshot3](Bilder/Screenshot03.png "3")
 
Das Ziel des ersten Levels ist es die "Tür" in das zweite Level zu finden. Die "Tür" ist in unserem Fall das Auto, wenn Mario mit diesem kollidiert, gelangt er automatisch in das zweite Level. Dafür benutzten wir "change level"- und "set level"-Blöcke. Der "change level"-Block sorgt dafür, dass der Spieler das zweite Level sieht, sich also das Terrain verändert, während der "set level"-Block sicherstellt, dass der Agent weiß, dass er sich in dem zweiten Level befindet.
 
![screenshot2](Bilder/Screenshot02.png "2")
