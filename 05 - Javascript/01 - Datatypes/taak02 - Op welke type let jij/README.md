# FRONTEND-ESSENTIALS

## Javascript

## taak01 - Datatypes

### Introductie

In de code-wereld bestaan allerlei soorten datatypes. Soorten data. Data-typen. Tijdens deze Frontend Module zul je de volgende tegenkomen:

- String
- Number
- Boolean
- Undefined
- Null
- Symbol

#### STRING

Het datatype __String__ is een stukje tekst. Sterker nog dit kan zelfs een lege stuk tekst zijn. Als de tekst (of lege tekst) tussen aanhalingstekens staat dan is het van het type String. Dus bijvoorbeeld zo:

```js
let mijnVoornaam = "Bart"
let mijnAchternaam = 'Simpson'
let beroep = "   ";
let school = '';
```

Je ziet dat __enkele__ en __dubbele__ aanhalingstekens mag gebruiken.

#### Number

Cijfer of cijfers dat is een __Number__ datatype. Voorbeelden van Number datatypen zijn:

```js
/* Integers zijn gehele getallen */
let aantalKinderen = 3;
let aantalKoekjes = 12;
let aantalKoekjesPerKind = 4;

/* Float een niet-geheel getal */
let leeftijd = 42.5;
```

#### Boolean

Een __Boolean__ datatype bestaat uit maar twee waarden: of

- Waar óf
- niet Waar

Of beter in het Engels

- TRUE
- FALSE

```js
let isMinderjarig = false;
let isStudent = true;
```

#### Undefined

Als een variabele bestaat (met `let` gedeclareed), maar geen waarde heeft gekregen) en je roept de variabele wel op dan krijg je __Undefined__

```js
let naamStudent = "Farhad";
let leeftijdStudent;

console.log(naamStudent); /* de naam Farhad verschijnt in de console */
console.log(leeftijdStudent);
```

Dit is dan het resulaat:

![Farhad](images/farhad.png)

De leeftijd was niet 'gevuld' en is dus niet gedefineerd.

#### NULL

NULL is een lege waarde maar niet undefined. Soms kan een variabele dus expres leeg gemaakt zijn. Dit is dus __niet__ een lege string of het getal 0. Dit is NULL.

```js
let eenLegeVariabele = null;
console.log(eenLegeVariabele); /* NULL */
```

### Opdracht

1. Maak een index.html met de gebruikelijke tags en daarbij ook een script tag. (je kunt de index.html van taak01 nemen ;)
2. Maak voor de volgende onderwerpen de volgende variabelen die over jezelf gaan.
   - voornaam
   - achternaam
   - leeftijd
   - ikBenStemGerechtig
   - ikMagLegaalAlcoholKopen
   - ikMagBrommerRijden
   - SoftwareOntwikkeling
3. Geen van de bovenstaande variabele mag _undefined_ zijn als je het zou testen in de console
4. Gebruik de genoemde datatypes
