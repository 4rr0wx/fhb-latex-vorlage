

FH-Burgenland Vorlage V2

Dieses Repository enthält eine LaTeX-Vorlage für Dokumente der FH Burgenland, entwickelt von Martin Scheifinger. Diese Vorlage ist strukturiert und formatiert, um die Anforderungen an akademische Dokumente zu erfüllen und bietet benutzerdefinierte Anpassungen für Kopf- und Fußzeilen, Inhaltsverzeichnis, Seitenlayout und Verzeichnisse.

Features

	- Modularer Aufbau: Die Vorlage nutzt mehrere externe Dateien, wie _Packages, _Variables, und Kapitel/Kapitel_1, um Code sauber und übersichtlich zu halten.
	- Anpassbare Kopf- und Fußzeilen: Definiert mit dem fancyhdr-Paket, einschließlich Logos der FH Burgenland.
	- Inhaltsverzeichnis: Bis zu 4 Ebenen tief, anpassbare Nummerierung.
	- Formatierte Anhangsverzeichnisse: Optionales Abbildungs- und Tabellenverzeichnis.
	- Acronyme und Glossar: Verwaltet über makeglossaries.

Verwendung

	1.	Klonen des Repositories:

git clone https://github.com/dein-benutzername/dein-repository.git


	2.	Bearbeiten der Datei main.tex:
	- Passe die Metadaten (title, author, etc.) an deine Anforderungen an.
	- Ersetze Platzhalter in den Dateien Deckblatt und Kapitel/Kapitel_1.
	3.	Kompilieren des Dokuments:

pdflatex main.tex
makeglossaries main
pdflatex main.tex
pdflatex main.tex



Abhängigkeiten

	- LaTeX Distribution (MikTeX oder TeX Live empfohlen)
	- Pakete: fancyhdr, makeglossaries, inputenc, und weitere, in _Packages definiert.

Anpassungen

Metadaten und Dokumenteninformationen befinden sich in der main.tex Datei. Achte darauf, dass Fachkürzel und Titel in den Dateien _Variables und Deckblatt aktualisiert werden.
