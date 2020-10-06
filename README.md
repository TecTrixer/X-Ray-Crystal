# Röntgen Kristall Experiment - digitale Auswertung

## Art der Auswertung

Um die durch das Experiment gewonnenen Daten auszuwerten, werden sie als Textdatei importiert und mithilfe eines Jupyter Notebooks, welches auf Python basiert ausgewertet und graphisch dargestellt.

## Einrichten des Jupyter Notebooks

Zum Arbeiten mit dem Jupyter Notebook am besten das kostenlose Programm Visual Studio Code benutzen, es ist für alle Betriebssysteme frei verfügbar und unterstützt fast jede Programmiersprache.

Anschließend Git, eine Version Control Software installieren, mit dieser können diese Dateien auch einfach heruntergeladen werden. Dazu einfach im Zielverzeichnis folgenden Code im Befehlsfenster ausführen:

`git clone https://github.com/tectrixer/X-Ray-Crystal.git`

Nun muss auch Python installiert werden, hierzu am besten im Internet nach der Installationsanleitung für das jeweilige Betriebssystem gucken und nach Möglichkeit die modernste Version (momentan 3.8) installieren. Hier kann auch Software zum erstellen einer virtuellen Pythonumgebung installiert werden. (pipenv oder venv)

Jetzt mit Hilfe von pip, Pythons "Pluginmanager" die verschiedenen benötigten Zusatzmodule installieren:

`pip install -r requirements.txt`

oder wenn pipenv verwendet wird:

`pipenv install`

Anschließend kann das Jupyter Notebook "Auswertung.ipynb" einfach mit Visual Studio Code geöffnet werden. Daraufhin sollte Visual Studio Code unten rechts das entsprechend benötigte Plugin vorschlagen. Nachdem dieses installiert wurde, startet VS Code beim öffnen des Jupyter Notebooks automatisch die entsprechenden Programme, die im Hintergrund laufen müssen.
