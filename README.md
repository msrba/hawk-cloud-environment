# Enwicklungsumgebung mit Vagrant 

Diese Umgebung startet eine Virtuelle Maschine mit Ubuntu 14.04 Desktop und führt das Script "assets/setup/setup_environment.sh" aus.

In diesem Script können alle Installation gescriptet werden die dazu notwendig sind um die Umgebung einzurichten. Auch die Eclipse notwendigen Einstellungen können über Shell gemacht werden -> GOOGLE

## Befehle:

vagrant up : Started die Umgebung und Installiert alles notwendige

vagrant destroy: Löscht die Virtuelle Maschine wieder

vagrant suspend: Versetzt die Virtuelle Maschine in einen Ruhezustand und kann mit vagrant up wieder aus dem Ruhe Zustand geholt werden.

## Verzeichnisse: 

dev/setup/files/ : alle für die Umgebung notwendige Dateien 

dev/setup/ : alle Setup Scripte

Alle Anderen notwendigen Datein und Verzeichnisstrukture des Projektes sollten in der Ebene des Vagrantsfiles angesiedelt werden

Alle Verzeichnise ab der Ebene des Vagrantsfiles werde in die Virtuelle Maschine unter /vagrant/. gemountet alle Änderungen im Host und Gast System werden synchronisiert. 
