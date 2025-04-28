# Ihr wollt euren Roboter hinzufügen?

How TO:
Ihr müsst zu aller erst das Repository runterladen, dazu braucht Ihr GIT.
GIT könnt ihr einfach im Internet [runterladen](https://git-scm.com/downloads).

Mit folgendem command "cloned" ihr das Repository.
Geht dazu in das Terminal und geht mit folgendem Command in eure Dokumente:
```bash
# In die Dokumente
cd .\Documents

# Herunterladen
git clone https://github.com/Technulgy-LGNU/OpenSource-Mechanics.git
```

Erstelle nun einen Ordner mit eurem Team und dann einen Ordner von dem Jahr. 
Dort fügt Ihr dann eure CAD Daten hinzu, ein guter Anhaltspunkt wie man das sortiert,
sind die Ordner von Team Faabs.

Nachdem Ihr alle Ordner hinzugefügt habt, müsst Ihr folgende Commands eingeben.
```bash
# Davor mit dem Terminal in den OpenSource Mechanics Ordner wechseln
cd .\OpenSource-Mechanics\

# Alle Dateien hinzufügen
git add .

# Dokumente einem commit hinzufügen
git commit -m "Team <NAME> <JAHR> mechanics'"

# Hochladen
git push -u origin main
```

Gegebenfalls müsst Ihr euch beim letzten Schritt über ein PopUp bei GitHub anmelden.  
