# BHT Softwaretechnik Kurs

Dieses Repository wurde erstellt für die Einsendeaufgabe zum Thema Versionierung mit Git.

## Aufgabe 1  
Erstellen Sie sich ein Repository in Github oder GitLab.

### Vorgehen
**Schritt 1**  
Auf GitHub ein neues Repository erstellt (https://github.com/BooleanBill/BHT-SWT-ESA-DVC).
**Schritt 2**  
Repo lokal geklont:  
```bash
git clone git@github.com:BooleanBill/BHT-SWT-ESA-DVC.git
```

## Aufgabe 6
Erstellen Sie in GitHub einen Pull-Request bezugnehmend auf https://github.com/edlich/education! Bitte referenzieren Sie auf den Pull-Request mit Link oder der Pull-Request Nummer! Kryptische GitHub Namen kann ich kaum zuordnen. Die Aufgabenteile vor dem Pull-Request bitte nicht in den Pull-Request einbauen, sondern extra abgeben!


### Vorgehen
**Schritt 1**  
Fork vom Repository erstellt (https://github.com/BooleanBill/education). 

**Schritt 2**  
```bash
git clone git@github.com:BooleanBill/education.git # Repository geklont
cd education # in das Verzeichnis wechseln
git checkout -b klejewski-esa-dvc # Branch erstellt
cp ~/Pictures/Nero.png ~/Projects/BHT/SWT/education/Pet-Folder # Bild kopiert
git add Pet-Folder/Nero.png # Bild hinzugefügt
git commit -m "Added picture of my dog Nero (Nero.png)" # Commit erstellt
git push origin klejewski-esa-dvc # Branch gepusht
```

**Schritt 3**  
Pull-Request erstellt (https://github.com/edlich/education/pull/489)