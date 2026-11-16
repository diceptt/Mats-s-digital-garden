# Learning Log Mats van Waarden

<!-- 9 Nov Kickoff -->

<details>
<summary>9 nov - Kickoff</summary>

### Wat heb ik vandaag gedaan:

Een fork van de model repository gemaakt en gepubliceerd via mijn eigen Github omgeving (binnen een eigen domein).

### Checkout vragen:

#### 1. _Leg uit wat een source hosting platform is en voor welke jij gekozen hebt._

> Een source hosting platform is een platform waarop developers (samen) code kunnen opslaan, delen en bewerken. Ik heb gekozen voor github, omdat we hier bij wijzer op het web al een klein beetje gebruik van hebben gemaakt, en dit voor zover ik weet de industriestandaard is.

#### 2. _Vertel welke domeinnaam jij gekozen hebt en hoe je die hebt gekoppeld aan jouw pagina._

> Ik heb gekozen voor de domeinnaam: "hettuintjevanmats.nl" ik vond dit een toepasselijke twist op het doel van de opdracht, het maken van een digital garden, en heb zo vrij snel mijn keuze gemaakt. Na het domein op te kopen via Trans-IP, heb ik de DNS records aangepast om het domein aan mijn github repository te linken / ernaar te verwijzen, en heb ik het domein via de instellingen van de repository (om specifiek te zijn; Github Pages) gekoppeld.

#### 3. _Beschrijf hoe je aanpassingen aan jouw pagina kunt maken en hoe je er voor zorgt dat die op het web gepubliceerd worden._

> Ik kan aanpassingen maken door in mijn Visual Studio Code de codebestanden die in de door de docent gemaakte template meegeleverd zijn te bewerken. Voor nu is dat voornamelijk de index.html, waarin simpele html aanpassingen gemaakt kunnen worden door code te schrijven of te bewerken. Na het uitvoeren van wijzigingen, kan ik via source control deze wijzigingen "committen" naar mijn github repository. Vervolgens sync ik deze wijzigingen in hetzelfde scherm en zullen deze in de bestanden in de repository aangepast worden. Dit is ook wat ik ga doen om deze tekst op mijn pagina te krijgen :)

</details>

<!-- 11 Nov practica -->

<details>
<summary>11 nov - practica</summary>

### Wat heb ik vandaag gedaan:

##### In het eerste practicum;

Een herhaling gehad van MMD (Multi Modal Design), microinteracties / animaties en (nieuwe) informatie over forms. Dit was een nuttige geheugensteun, omdat het meeste van vorig jaar toch al wel een beetje was weggezakt.

##### In het tweede practicum;

Schetstechnieken, we hebben onder andere naar schetsen van vorig jaar gekeken om vast te stellen wat een schets "goed" maakt. Ook hebben we zelf geoefend met schetsen maken gebruikmakende van deze technieken. Om er een paar te noemen: Visuele hierarchie (door middel van fineline + dikkere stift), shading (met bijvoorbeeld een grijze stift), annotaties (met een andere kleur) en hoe je interactie / animatie zichtbaar maakt in een schets (met stippellijnen en een andere kleur bijvoorbeeld). Hieronder zijn de oefeningen te zien die we uitgevoerd hebben:
<img width="200" alt="image" src="https://github.com/user-attachments/assets/9bf2bda4-c61c-4800-85d2-382bad4b85be" />
<img width="200" alt="image" src="https://github.com/user-attachments/assets/57793959-0758-4424-89e1-1e030ae7d8fe" />
<img width="200" alt="image" src="https://github.com/user-attachments/assets/dac1c870-48c8-427d-b16b-5d5f2e42a533" />


</details>

<!-- 13 Nov practica -->

<details>
<summary>13 nov - practica</summary>

### Wat heb ik vandaag gedaan:

#### In het eerste practicum (Praktische CSS);

In dit practicum zijn we begonnen met het maken van een "lelijke html" pagina. Deze hebben we vervolgens gebruikt om weer wat css kennis naar boven te halen. Zo zijn we aan de slag gegaan met fonts, plaatjes juist weergeven (met behulp van max-width), buttons en hun interactie, consistente witruimtest en een form / formulier. Het meeste hiervan (behalve de form), was bekende informatie (alhoewel dit wel al een tijd geleden was), maar ik heb ook wat nieuws geleerd. Door het gebruiken van variabelen kun je makkelijk door op 1 plek in de code een regel aan te passen op verschillende plekken de waarde veranderen. Dit scheelt een hoop gedoe, en maakt het een stuk makkelijker om snel grote wijzigingen door te voeren.

###### Plaatje

<img width="200" alt="image" src="https://github.com/user-attachments/assets/617150bf-dc1e-4380-9cda-f6c1885d6408" />
<img width="200" alt="image" src="https://github.com/user-attachments/assets/fd7845f1-dc93-4ac9-aee5-1118eee8c483" />

#### In het tweede practicum (CSS - Fonts met kleur en effecten);

Vervolgens zijn we verder gegaan met fonts, en ook meerdere soorten kleur en effecten. Er waren verschillende (na te maken) ontwerpen waar uit gekozen kon worden. Ik heb, naast de basisopdrachten, gekozen voor een opdracht uit de categorie "goed te doen" (neon), een uit "wellicht lastiger" (PUFF) en een uit "best tricky" (Messi). De eerste twee gingen mij met een beetje pielen redelijk af, maar met de laatste had ik echt moeite. Dit is mij uiteindelijk ook niet helemaal gelukt, maar ik zat wel in de juiste richting. Na een uitleg van Sanne had ik een stuk beter inzicht hoe deze laatste werkte, dus dat was erg fijn. Als laatste hebben we nog wat geleerd over animaties/transitions (transition: .5s; bijvoorbeeld), dit werkt perfect om bijvoorbeeld een knop bij :hover mooi naar een andere kleur te laten faden. Dit is ook erg handing voor in mijn uiteindelijke app. Mijn uitwerking en code is hieronder te zien:

###### Plaatje

<img width="1067" height="452" alt="image" src="https://github.com/user-attachments/assets/dd46815e-5a8f-428d-99fe-bb0dad8671d9" />

###### CSS

```css
/**\*\***\*\***\*\***/
/_ @FONT-FACE _/
/**\*\***\*\***\*\***/
/_ Neon,Puff,Messi _/

/_ alle fonts hier _/
@font-face {
font-family: "Ubuntu";
src: url("../fonts/Ubuntu-Bold.ttf");
font-weight: 700;
}

@font-face {
font-family: "DynaPuff";
src: url("../fonts/DynaPuff-Bold.ttf");
font-weight: 700;
}

@font-face {
font-family: "Aldrich";
src: url("../fonts/Aldrich-Regular.ttf");
font-weight: 400;
}

/**\*\***\*\***\*\***\***\*\***\*\***\*\***/
/_ JOUW CODE VOOR DE BLOKJES _/
/**\*\***\*\***\*\***\***\*\***\*\***\*\***/

/_ met deze selector selecteer je de eerste li _/
li:nth-of-type(1) {
display: grid;
place-items: center;
background: linear-gradient(limegreen, midnightblue);

/_ je kunt css selectors nesten _/
/_ zo kun je makkelijker zien wat bij elkaar hoort _/
/_ met deze selector selecteer je de h2 in de eerste li _/
h2 {
font-size: 3.5rem;
color: rgb(0, 0, 0, 0);
-webkit-text-stroke-color: white;
-webkit-text-stroke-width: 1px;
}
}

/_ met deze selector selecteer je de tweede li _/
li:nth-of-type(2) {
background: radial-gradient(Yellow, Limegreen);
display: grid;
place-items: center;

h2 {
font-size: 4rem;
font-family: DynaPuff;
text-transform: uppercase;
color: white;
-webkit-text-stroke-width: 30px;
-webkit-text-stroke-color: limegreen;
paint-order: stroke fill;
}
}

li:nth-of-type(3) {
background: repeating-linear-gradient(
45deg,
rgb(0 100% 0 / 0.2),
rgb(0 100% 0 / 0.2) 130px,
green 130px,
green 260px
), repeating-linear-gradient(
45deg,
green,
green 130px,
rgb(0 100% 0 / 0.2) 130px,
rgb(0 100% 0 / 0.2) 260px,
)
display: grid;
place-items: top;

h2 {
color: white;
border: solid;
border-color: #fff;
font-size: 2rem;
font-family: Aldrich;
height: 80%;
margin: 2rem;
padding: 1.5rem;
padding-right: 6rem;
}
}
```

</details>

<!-- 16 Nov Kickoff Sprint 1 -->

<details open>
<summary>16 nov - Kickoff Sprint 1</summary>

### Wat heb ik vandaag gedaan:

We zijn over de sprintplanning voor de eerste sprint heengegaan. Hierbij hebben we een lijst gemaakt van het huiswerk en de tussentijdse opdrachten die we afgerond moeten hebben voor de retrospect volgende week vrijdag. Vervolgens hebben we teksten/artikels gelezen over digital gardens, wat ons een goed beeld heeft gegeven over wat een digital garden inhoudt, en dit heeft mij ook enorm geholpen met mijn beeld van de opdracht over de komende weken. Hierna hebben we naar wat webrings gekeken, en deze vergeleken aan de hand van verschillende criteria, om erachter te komen welke het meest "webby" was. Hierna zijn we begonnen met wat onderzoek over ons onderwerp voor de opdracht, en een presentatie om hier woensdag mee verder te gaan. Hier zal ik morgen mee verder gaan.

### Checkout vragen:

#### 1. _Leg uit wat een digital garden is en waarom dat anders is dan een reguliere website._

> Een digital garden is eigenlijk een soort persoonlijk digitale leeromgeving. Het hoeft niet "af" / "compleet" te zijn, wat bij een website wel zo is. Het is een soort moestuin, waarin je dingen die je interesseert plaatst en die af en toe wat bijwerkt. Het is dus ook niet zo dat je dit elke dag moet checken, omdat je dan iets zou missen. Het is echt een "eigen" plekje op het web, waar de maker met van alles aan de slag kan gaan.

#### 2. _Leg uit wat een website 'webby' maakt en welke websites jou het meeste inspireren._

> Wat een website webby maakt zijn verschillende factoren. Een voorbeeld hiervan is of het responsive is (past het in een klein scherm, past de tekst zich aan etc.), het toegankelijk is (goed kleurcontrast, visuele hierarchie, fingerfriendly, alttekst bij plaatjes etc.). Ook is het toch wel belangrijk dat de website expressief is, er moeten ook een beetje interactie, wat animaties en gradients bijvoorbeeld in gebruikt worden. Dit geeft het leven, en een "eigen" identiteit. Een van de websites die mij het meeste inspireert is de apple website. Dit komt omdat het gewoon "werkt". Het is duidelijk dat aan alles is gedacht, en dat het, terwijl het zo "simpel" lijkt, precies werkt zoals het hoort. Het is niet voor niks dat deze website altijd als voorbeeld gebruikt wordt.

#### 3. _Vertel waar jij mee aan de slag wilt gaan bij het maken van jouw eigen digital garden (let op: dit zijn jouw eerste ideeën, dit kan en mag veranderen in de loop van het programma)._

> Wat eerste ideeen die ik heb zijn muziek en vibecoding. Dit zijn dingen die mij interesseren of waar ik zelf mee aan de slag ben. Vibecoding denk ik bijvoorbeeld dat een belangrijk onderdeel wordt van het veld waarin we (gaan) werken, en al is het misschien niet bruikbaar tijdens de opdracht, het kan wel als onderwerp gebruikt worden!

</details>
