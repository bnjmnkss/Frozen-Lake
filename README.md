# Frozen-Lake
Code und Modelle für das Frozen Lake Problem 

Während meines Studiums war das ein Projekt zur Übung von Reinforcement Learning im Sommer 2025. Das Ziel war, den Elfen auf zufälligen 8x8 Lakes konstant zum Ziel zu bringen, ohne dass er in ein Loch fällt. 

Ich bin dabei folgendermaßen vorgegangen:

1. Normales Q-Learning auf konstanten 4x4 Lakes
2. Normales Q-Learning auf konstanten 8x8 Lakes
3. Deep Q-Learning auf konstanten 4x4 Lakes
4. Deep Q-Learning auf konstanten 8x8 Lakes
5. Deep Q-Learning auf random 4x4 Lakes
6. Deep Q-Learning auf random 8x8 Lakes

Dabei gab es bei Deep Q-Learning auf random 8x8 Lakes mit dem bisherigen Ansatz Probleme, weshalb ich verschiedene Optimierungen testete, die zu verschiedenen interessanten Verhaltensweisen des Elfen führten, jedoch nicht zu konstantem Zielerreichen. 
Eine Lösung war die Verwendung eines CNNs als Modell.

Die PowerPoint war meine Abschlusspräsentation des Projekts. (In den Foliennotizen stehen manchmal weitere Erklärungen zu den einzelnen Folien)

Falls du auch dieses Projekt bearbeiten musst/willst, dann empfehle ich dringendst nicht 1 zu 1 meinen Code zu kopieren, sondern ihn lediglich als Vergleich/Leitlinie zu benutzen, genauso wie die Präsentation. 
