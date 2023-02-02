# Template - Opdrachtbeschrijving ???

## Inleiding

Dit project is gemaakt om als basis te dienen voor opdracht-projecten in GitHub, die uitgecheckt kunnen worden door studenten.

## Voor je begint

### Java installeren

Intellij kan Java voor je installeren:
1. Om dit te doen kan je het volgende scherm openen: `File -> Project Structure -> Project Settings -> Project`.
2. Bij SDK kan je in de dropdown `download JDK` selecteren.
3. Kies hier voor versie 17 en laat deze downloaden en installeren.

### Uitvoeren met Maven

We maken hier ook gebruik maken van de build tool maven.
Dit kunnen we zien aan het bestand `pom.xml`.
Deze file bevat de configuratie voor ons project.
Voor een klein project als dit is deze configuratie nog erg klein.
We zien hier dat we voor nu even Java versie 8 gebruiken, dit doen we nog even om te voorkomen dat Intellij je teveel gaat helpen terwijl je nog concepten aan het leren bent.
Later in deze cursus gaan we java 17 gebruiken.
We kunnen ook kijken of het programma via Maven te draaien is.
Hiervoor kun je helemaal onderin het scherm op het tabblad `terminal` klikken.
Hier kun je het volgende commando uitvoeren:

```shell
./mvnw clean compile exec:java
```

of 

```shell
mvnw.cmd clean compile exec:java
```

Als het goed is komt er nu een boel tekst hier te staan waaronder de tekst "BUILD SUCCESS" en hierboven de tekst "Hello world".
Als dit werkt weet je dat maven correct werkt.

### Uitvoeren vanuit Intellij

Dit is een project dat gebruik maakt van Maven en Intellij kan hier mee omgaan.
Er is een kans dat Intellij dit al voor je gedaan heeft, maar dit kunnen we controleren door helemaal aan de rechterkant het tabblad `Maven` te openen.
Als dit tabblad leeg is moet er op het `+` icoon gedrukt worden en de `pom.xml` van dit project geselecteerd worden.
Nu zie je als het goed is het project `Helloworld` in dit tabblad staan. 

Als alles goed is gegaan zie je nu in de map `src/main/java` de classe `Main` staan.
Hier zie je een groen play knopje voor de methode `main` staan.
Als je hier op klikt krijg je de mogelijkheid om `run Main.main()` te doen.
Als je hiervoor kiest gaat het programma draaien en zal je onderin in het `run` scherm de tekst:
"Hello world" te zien moeten krijgen (met daaronder de tekst "Process finished with exit code 0").
Als je dit ziet betekend dat Java goed is geinstalleerd.


## Opdracht

Beschrijving van de opdracht: je gaat dit en dat maken en dit moet het doen.

### Randvoorwaarden

De opdrach moet voldoen aan de volgende voorwaarden:

* Voorwaarde
* Nog een voorwaarde
* etc...

### Stappenplan

_Let op_ het is uitdagender om jouw eigen stappenplan te maken. Als je niet zo goed weet waar je moet beginnen, kun je onderstaand stappenplan gebruiken

* Doe eerst dit
* Doe dan dat
* etc...

## Bonusopdracht

Optioneel.
