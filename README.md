t-Test
============

Diese Animation stellt eine aktualisierte Version dar. Die ursprüngliche Programmierung erfolgte durch Andranik Stepanyan. Die dazugehörigen R-Codes finden Sie [hier.](https://github.com/andronikoss/t-Test)

Um die Animation auf Ihrem Rechner auszuführen (_Localhost_), brauchen Sie das R Packet `shiny`. 

```
# Notwendiges Packet wird installiert
install.packages("shiny")
library(shiny)
runGitHub("t-Test", "Oekonometrie-Lernen")
```

Erfolgreiches Ausführen dieser Schritte wird Ihnen ermöglichen die Animation Local auf Ihrem eigenen Rechner laufen lassen.   
Für ausführliche Informationen wie man eine Anwendung mithilfe RStudio Shiny Packet schreibt, finden Sie unter folgendem [Tutorium.](http://shiny.rstudio.com/tutorial/)

Bei jeder wiederholten Stichprobe berechnet der Intervallschätzer für den Steigungsparameter β ein neues Intervall. In der Animation können Sie den Einfluss des Signifikanzniveaus, der Störgrößenvarianz und des Beobachtungsumfangs auf die Gestalt der erzeugten Intervalle studieren.
Der t-Test ist ein Standardverfahren zur Überprüfung von Hypothesen. Wenn der aus der beobachteten Stichprobe ermittelte t-Wert außerhalb des berechneten Akzeptanzintervalls des t-Tests liegt, wird die Hypothese verworfen.
