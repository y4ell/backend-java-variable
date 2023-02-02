# Backend Java: Variables

## Inleiding

Deze repository bevat oefeningen voor het declareren en assignen van variabelen in Java.
Neem eerst het hoofdstuk over variabelen door.

Je gaat oefenen met het declareren van variabelen. In tegenstelling tot eerdere oefeningen compiled de code bij deze opdracht niet.
Je ziet src/main/java een class `Main`.

In deze class staan een hoop `System.out.println` statements, maar de `variabele` zijn rood gekleurd.

Dit komt omdat de variabele nog niet gedeclareerd en geassigned zijn.

Als je deze code probeert uit te voeren krijg je foutmeldingen van de compiler.

## Voor je begint

Voorwaarden voor deze opdracht:
1. Java Development Kit, versie 17
2. IntelliJ IDEA

### Uitvoeren met Maven

Voer de opdracht code uit met:

```shell
./mvnw clean compile exec:java
```

of

```shell
mvnw.cmd clean compile exec:java
```

### Uitvoeren vanuit Intellij

Groene play-knop voor de `main` method klikken en 'Run...' kiezen.

### Testen uitvoeren vanuit Intellij

Groene play-knop voor de `MainTest` class in src/test/java klikken en 'Run 'MainTest'' kiezen.

## Opdracht

Zorg dat de code compiled en de testen slagen. Je mag de regels die starten met System.out.println niet aanpassen.
Achter de regels die beginnen met System.out.println staat in commentaar welk type de variable heeft, en welke waarde.

Om te valideren of je klaar bent kun je de testen draaien. In `src/test/java` vind je een class MainTest. Links naast `public class MainTest {` staat een groen pijltje dat je kunt gebruiken om te compilen en te testen. Onder in het scherm komt het resultaat te staan.

### Stappenplan

_Let op_ het is uitdagender om jouw eigen stappenplan te maken. Als je niet zo goed weet waar je moet beginnen, kun je onderstaand stappenplan gebruiken

* Kijk goed naar het voorbeeld, hier zie je dat er een variabele wordt gedeclareerd van type `String` met naam `string_voorbeeld`. Daarna volgt een `=` waardoor we direct een waarde toewijzen, namelijk de string `"Dit is een voorbeeld"`. Je sluit het statement af met `;`
* Declareer onder het voorbeeld een nieuwe variabele van type  `String` met de naam `string_hello_world`
* Zet na de declaratie een `=` om direct een waarde toe te wijzen.
* Wijs de String `"hello world"` toe, en sluit af met een `;`
* De regel `System.out.println(string_hello_world);` bevat nu geen foutmelding meer,
* Declareer op een nieuwe regel een nieuwe variabele van type  `boolean` met de naam `boolean_true`
* Zet na de declaratie een `=` om direct een waarde toe te wijzen.
* Wijs de boolean `true` toe, en sluit af met een `;`

## Bonusopdracht

Het onderste `System.out.println` statement vraagt je om een variable opnieuw toe te wijzen. Op welke plek in de code doe je dit?
Hoe ziet alleen toewijzen er uit? (Hint: de variabele bestaat al, dus we hoeven hem niet te declareren.)
