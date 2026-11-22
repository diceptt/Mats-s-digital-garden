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

<details>
<summary><h2>16 nov - Kickoff Sprint 1</h2></summary>

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

<!-- 17 Nov Sprint 1-->
<!-- 17 Nov Sprint 1-->
<!-- 17 Nov Sprint 1-->
<!-- 17 Nov Sprint 1-->
<!-- 17 Nov Sprint 1-->
<!-- 17 Nov Sprint 1-->
<!-- 17 Nov Sprint 1-->
<!-- 17 Nov Sprint 1-->
<!-- 17 Nov Sprint 1-->

<details>
<summary>17 nov - sprint 1</summary>

### Wat heb ik vandaag gedaan:

Vandaag heb ik zelfstandig het practicum over light/dark mode gevolgd. Verder heb ik gewerkt aan mijn presentatie over het onderwerp van de digital garden voor woensdag in de les, die is hieronder te zien (de code in ieder geval).

### Practicum

In het practicum heb ik verschillende dingen geleerd. Een van de eerste, die ook in veel andere gevallen erg handig is zijn custom properties (bijvoorbeeld --hoofdkleur: rood;). Hiermee kun je waardes instellen die je overal door je code heen kunt gebruiken. Verder moet je eerste de regel "color-scheme: light-dark;" in de html plaatsen om de browser te vertellen dat beide aanwezig zijn. Vervolgens kun je in "light-dark()" 2 kleuren opgeven, waar de browser automatisch tussen wisselt. Als je de gebruiker dit handmatig wil kunnen laten veranderen moet je een knop maken met de :has() selector (bijvoorbeeld: html:has([value="licht"]:checked)). Ook heb ik geleerd over het picture element, waarmee je op basis van de schermgrootte en dark/light mode kan instellen welk plaatje wordt laten zien, zoday dit overal binnen past. Ik vind dit nog best ingewikkeld, dus moet hier nog wat verder mee spelen. Kortom, een hoop dingen die ik terug kan laten komen in mijn project.

### Presentatie

</details>

<!-- 18 Nov Sprint 1 lesdag 2-->
<!-- 18 Nov Sprint 1 lesdag 2-->
<!-- 18 Nov Sprint 1 lesdag 2-->
<!-- 18 Nov Sprint 1 lesdag 2-->
<!-- 18 Nov Sprint 1 lesdag 2-->
<!-- 18 Nov Sprint 1 lesdag 2-->
<!-- 18 Nov Sprint 1 lesdag 2-->
<!-- 18 Nov Sprint 1 lesdag 2-->
<!-- 18 Nov Sprint 1 lesdag 2-->
<!-- 18 Nov Sprint 1 lesdag 2-->
<!-- 18 Nov Sprint 1 lesdag 2-->
<!-- 18 Nov Sprint 1 lesdag 2-->

<details>
<summary>18 nov - Sprint 1 lesdag 2</summary>

### Wat heb ik vandaag gedaan:

We zijn begonnen met visual research. Hierbij moesten we als eerste een sfeerwoord vastellen. Ik denk dat dit bij mij warm/cozy/relaxed is. Vervolgens hebben we hier directe, en abstracte afbeeldingen bij gezocht en deze vervolgens gebruikt als basis voor een crazy 8 waar wat eerste ontwerpen uit zijn voortgekomen.

### Vragenlijst na presentatie:

_Wat is voor jou de essentie van wat je hebt gepresenteerd qua onderwerp en geschreven/beeldende content?_

> Dat muziek een belangrijke rol kan spelen in het leven van de gebruiker, en hun gemoedstoestand kan verbeteren en connecties in het brein kunnne versterken

_Heeft 'de ander' een aanvulling op je onderwerp?​_

> Hoe gaat er precies uitzien? Niet teveel op een soort spotify / muziekapp laten zien. Iets unieks om mensen over muziek te vertellen.

_Wat is het karakter/ de uitstraling/ het gevoel dat bij het onderwerp past? (bijv. stoer, hip, vrolijk, dynamisch, eenvoudig, enz.)​_

> Warm, fijn, cozy, chill

_Welke inspiratie kun je uit je 25 afbeeldingen halen. Stijl, een gevoel, vorm, enz.​_

> Qua stijl/gevoel: vintage, warm, huiskamer sfeer. vorm is digital, maar ook analoog (platen, cds etc.)

_Wat zou je willen vertellen over het onderwerp aan een ander? en hoe zou je dat voor je kunnen zien? middels welke beeld, tekst, animatie, inhoudelijke content? (bijv. Ik wil voornamelijk afbeeldingen tonen, als een soort Pinterest, of ik wil muziek fragmenten laten horen, of ik gebruik korte teksten met eigen foto's)._ ​

> Ik wil vooral een visueel verhaal vertellen, aan de hand van muziekfragmenten, achtergrondinformatie en aanraders. Het maakt niet uit waar de gebruiker begint, het is een vrije invulling.

_Vul deze zin aan:_

> Ik wil mijn Digital Garden laten gaan over muziek en de impact ervan op gemoedstoestand. en wil dat laten zien door een visueel verhaal, met veel visuals/muziekfragmenten en interactie aan content te tonen. Ik begin met een stukje eigen content over dat muziek overal is, en wat voor invloed het heeft op je brein bijvoorbeeld. ​Als het begin is gemaakt kan ik mijn Garden verder uitbreiden door genres, muziekfragmenten, aanraders en achtergrondinformatie toe te voegen.

### Visual research:

###### _Directe visuele beelden_

<img src="images/stap1visueelonderzoek.png" alt="foto als basis voor kleurpalet" width="300">

###### _Abstracte visuele vertaling_

<img src="images/stap2visueelonderzoek.png" alt="foto als basis voor kleurpalet" width="300">

###### _Uitgangspunten_

<img src="images/stap3visueelonderzoek.png" alt="foto als basis voor kleurpalet" width="300">

###### _Crazy 8 + inzichten_

<img src="images/crazy8visueelonderzoek.png" alt="foto als basis voor kleurpalet" width="300">

beste ideeen: iets met een platenspeler, misschien combineren met albums (als je erop klikt dat je meer te zien krijgt). Combinatie van platenspeler, album, afspeelidee. De uitgangspunten zijn duidelijk. Sommige zijn een beetje te simpel / saai in hun eentje maar kunnen in combinatie echt goed werken. Het idee is uitdagend omdat er een hoop interactie in zit en dit zijn voor mij nieuwe technieken, dus moet ik er ook nog wat voor leren.

###### _Color palette light and dark mode + typografie_

<img src="images/basiskleurpalet.png" alt="foto als basis voor kleurpalet" height="300">
<img src="images/eerstekleurpalet.png" alt="eerste kleurpalet" width="300">
<img src="images/kleurpaletten.jpg" alt="eerste kleurpalet" width="300">

Typografie

Ik heb gekozen voor Fraunces en Outfit (zie hieronder), Fraunces omdat dit zachte vormen en rondingen heeft, net als we zagen bij de verschillende afbeeldingen in het visuele onderzoek. Daarnaast Outfit, ook omdat dit ronde vormen heeft, omdat het vriendelijk oogt en omdat dit heel goed leesbaar is. Ze creeren samen een rustige, creatieve en toegankelijke sfeer.

<img src="images/lettertypefraunces.png" alt="lettertype Fraunces" width="300">
<img src="images/lettertypeoutfit.png" alt="lettertype Outfit" width="300">

### Practicum

### Checkout vragen:

#### _Leg uit waar het Visual Research in 3 stappen naartoe werkt_

> Het visual research werkt naar een "identiteit" toe, net als bij een merk moet je door de vorm, typografie en kleur meteen kunnen zien dat dit van "jou" is. Je creeert eigenlijk een soort gevoel.

#### _Vertel in 2 zinnen waar jouw Garden over gaat, en met welke content je dat gaat doen (beeld, tekst, sound, animatie enz)._

> Mijn garden gaat over muziek en de invloed daarvan op je gemoedstoestand, dit wil ik laten zien door een visueel verhaal, met veel visuals/muziekfragmenten en interactie. Ik begin met een stukje eigen content over dat muziek overal is, en een basis over de invloed op je brein. ​Als het begin is gemaakt kan ik mijn Garden verder uitbreiden door genres, muziekfragmenten, aanraders en achtergrondinformatie toe te voegen.

#### _Vertel kort welk idee van de Crazy 8 je het liefst zou willen uitvoeren/ verder zou willen onderzoeken._

> Ik denk in ieder geval dat het een combinatie wordt van verschillende ideeen, maar als basis zou ik graag iets doen met het idee van de platenspeler (zie kopje crazy 8). Hier zit veel potentie voor interactie in en ook kunnen hier verschillende animaties mee gemaakt worden.

</details>

<!-- 19 Nov Sprint 1 -->
<!-- 19 Nov Sprint 1 -->
<!-- 19 Nov Sprint 1 -->
<!-- 19 Nov Sprint 1 -->
<!-- 19 Nov Sprint 1 -->
<!-- 19 Nov Sprint 1 -->
<!-- 19 Nov Sprint 1 -->
<!-- 19 Nov Sprint 1 -->
<!-- 19 Nov Sprint 1 -->
<!-- 19 Nov Sprint 1 -->
<!-- 19 Nov Sprint 1 -->
<!-- 19 Nov Sprint 1 -->
<!-- 19 Nov Sprint 1 -->
<!-- 19 Nov Sprint 1 -->

<details>
<summary>19 nov - Sprint 1</summary>

### Wat heb ik vandaag gedaan:

Ik heb vandaag zelfstandig het practicum over mooie kleuren, patronen en gradients gevolgd. Daarnaast ben ik aan de slag gegaan met het verder uitwerken van de crazy 8 en heb ik hier een simpele html opzet van gemaakt in mijn index.html bestand.

### Practicum:

In dit practicum ging het vooral over kleur / gradients. Allereerst heb ik geleerd over een nieuwe kleurmethode. Waar we eerst altijd rgb, hex etc gebruikten is er nu ook oklch() waarmee je super levendige kleuren kan creeeren (nog feller geloof ik). Ook kun je met color-mix() verschillende kleuren mengen, wat bijvoorbeeld bij een hover goed van pas komt. Vervolgens ging het over gradients, waar verschillende varianten van zijn. De varianten vershcillende eigenlijk vooral van beginpunt. Waar een normale gradient bijvoorbeeld van links naar rechts of boven naar onder verloopt, begint een radialgradient eigenlijk vanuit 1 punt. Door color stops te gebruiken (waardoor het eigenlijk geen gradient meer is maar meer een soort kleurvak met een harde grens) kun je verschillende patronen maken. Dit was ook 1 van de dingen waar ik tegenaan liep met het eerste css practicum, waar ik had geprobeerd om de messi achtergrond te maken. Ook was er een stukje over @property. Ik vind dit nog best lastig, maar dit is eigenlijk een manier om een gradient (bijvoorbeeld de angle / kleur) vloeiend te animeren.

### Schetsen o.b.v crazy 8:

<img src="images/schetsen1.png" alt="Schetsen obv crazy8" width="300">
<img src="images/schetsen2.png" alt="Schetsen obv crazy8" width="300">
<img src="images/schetsen3.png" alt="Schetsen obv crazy8" width="300">

### Index.html bestand:

Ik ben begonnen met de html opzet voor de laatste schets (de planken met platen erop + een platenkast). De cactus / het plantje gaat dienen als een light/dark mode, en de kast met platen als navigatie. De platen op de planken gaan waarschijnlijk als popups / popovers werken, althans, dat is nu het plan.

```html
<main>
  <!--Plank 1-->
  <section>
    <ul>
      <li><a href="index.html">Plaat 1 gradient background</a></li>
      <li>
        <a href="https://github.com/account/repo"
          >Plaat 2 gradient background</a
        >
      </li>
      <li>
        <a href="https://github.com/account/repo"
          >Plaat 3 gradient background</a
        >
      </li>
    </ul>
  </section>

  <!--Plank 2-->
  <section>
    <ul>
      <li><a href="index.html">Plaat 4</a></li>
      <li><a href="https://github.com/account/repo">Plaat 5</a></li>
      <li><a href="https://github.com/account/repo">Plaat 6</a></li>
    </ul>
  </section>

  <!--Kast-->
  <section>
    <!--In kast/nav-->
    <nav>
      <ul>
        <li>link</li>
        <li>link</li>
        <li>link</li>
        <li>link</li>
        <li>link</li>
      </ul>
    </nav>
  </section>

  <!--Cactus-->
  <button type="button">cactus dark/light mode</button>

  <!--Platenspeler-->
  <section>
    <button type="button">platenspeler start</button>
  </section>
</main>
```

Dit ziet er op dit moment als volgt uit:

<img src="images/eerstehtmlopzet.png" alt="resultaat eerste html opzet" width="300">

</details>

<!--20 nov sprint 1 lesdag 3-->
<!--20 nov sprint 1 lesdag 3-->
<!--20 nov sprint 1 lesdag 3-->
<!--20 nov sprint 1 lesdag 3-->
<!--20 nov sprint 1 lesdag 3-->
<!--20 nov sprint 1 lesdag 3-->
<!--20 nov sprint 1 lesdag 3-->
<!--20 nov sprint 1 lesdag 3-->
<!--20 nov sprint 1 lesdag 3-->
<!--20 nov sprint 1 lesdag 3-->
<!--20 nov sprint 1 lesdag 3-->
<!--20 nov sprint 1 lesdag 3-->
<!--20 nov sprint 1 lesdag 3-->

<details open>
<summary>20 nov - Sprint 1 Lesdag 3</summary>

### Wat heb ik vandaag gedaan:

Vandaag heb ik mijn gekozen schets (verder) uitgewerkt in een html opzet. Ik had dit al als huiswerk gedaan maar heb hier wat verfijning aan toegevoegd en met behulp van feedback de code vernieuwd. Na deze lesdag heb ik een goede basis om mee verder te gaan voor volgende week. In het weekend ga ik alvast wat css toepassen, en werken aan de illustraties voor de achtergrond.

<!-- !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! -->
<img src="images/" alt="schets met html annotaties" width="300">

Na feedback (zie checkout vraag) van diederik heb ik het ontwerp wat aangepast, zodat er wat minder gebeurt en de aandacht op de juiste plek blijft. Zo is de kast nu een boekenkast, zodat er maar op 1 plek (de planken aan de muur) iets met muziek gebeurt (i.c.m. de platenspeler) bij horizontaal scherm is het idee dat alles van de mobiele weergave iets groter wordt, en er meer (niet interactieve) achtergrondelementen in beeld komen die bij het woonkamer idee horen.

### Index.html bestand update:

Eerste schets met html annotaties:

```html
<main>
  <!--Plank 1 met platen-->
  <section>
    <!--wel of niet een section?-->
    <ul>
      <li>
        <a href="">Plaat 1 gradient background</a>
      </li>
      <li>
        <a href="">Plaat 2 gradient background</a>
      </li>
      <li>
        <a href="">Plaat 3 gradient background</a>
      </li>
    </ul>
  </section>

  <!--Plank 2 met platen-->
  <section>
    <ul>
      <li>
        <a href="">Plaat 4</a>
      </li>
      <li>
        <a href="">Plaat 5</a>
      </li>
      <li>
        <a href="">Plaat 6</a>
      </li>
    </ul>
  </section>

  <!--Kast-->
  <section>
    <!--In kast/nav-->
    <nav>
      <ul>
        <li><a>menulink</a></li>
        <li><a>menulink</a></li>
        <li><a>menulink</a></li>
        <li><a>menulink</a></li>
        <li><a>menulink</a></li>
      </ul>
    </nav>
  </section>

  <!--Cactus-->
  <a href=""><img src="" />cactus dark/light mode</a>

  <!--Platenspeler-->
  <a href=""><img src="" />platenspeler</a>
</main>
```

Na feedback van Sanne:

```html
<body>
  <header>
    <h1>De digital garden van Mats</h1>
  </header>

  <main>
    <!--Plank 1 met platen-->
    <section>
      <h2 class="visually-hidden">Een muurplank met platen erop</h2>
      <ul>
        <li>
          <a href="">Plaat 1 gradient background</a>
        </li>
        <li>
          <a href="">Plaat 2 gradient background</a>
        </li>
        <li>
          <a href="">Plaat 3 gradient background</a>
        </li>
      </ul>
    </section>

    <!--Plank 2 met platen-->
    <section>
      <h2 class="visually-hidden">Een muurplank met platen erop</h2>
      <ul>
        <li>
          <a href="">Plaat 4</a>
        </li>
        <li>
          <a href="">Plaat 5</a>
        </li>
        <li>
          <a href="">Plaat 6</a>
        </li>
      </ul>
    </section>

    <!--Kast-->
    <section>
      <h2 class="visually-hidden">Een kast met boeken erin, navigatie</h2>
      <!--In kast/nav-->
      <nav>
        <ul>
          <li><a>menulink</a></li>
          <li><a>menulink</a></li>
          <li><a>menulink</a></li>
          <li><a>menulink</a></li>
          <li><a>menulink</a></li>
        </ul>
      </nav>
    </section>

    <!--Cactus-->
    <button type="button"><img src="" />lamp dark/light mode</button>

    <!-- Platenspeler (waarschijnlijk later bij interactie aanpassen naar ander onderdeel dan <a>) -->
    <a href=""><img src="" />platenspeler</a>
  </main>

  <footer></footer>
</body>
```

Ook ga ik later, na het maken van het ontwerp, svgs toevoegen in de html. Dit is nu nog niet terug te zien.

### Practicum:

Dit practicum ging over grid. Ik vind grid op zich best logisch, maar er zijn heel veel mogelijkheden en dat maakt het vrij lastig. Een belangrijk ding is de unit fr, hiermee kun je de breedte / lengte van de grid eerlijk verdelen. Bij twee kolommen zal een verdeling van 1fr 1fr er bijvoorbeeld zorgen dat allebei de vakken evenveel ruimte opnemen, wat de totale breedte ook mag zijn. Verder kun je met mediaqueries zorgen dat een grid die op telefoon bijvoorbeeld maar 1 kolom heeft op desktop meerdere kolommen heeft. Dat ziet er ongeveer uit als @media (width > 40em) {hier de code}. Dit vind ik ook nog vrij lastig, omdat ik responsiveness een van de moeilijkste onderdelen vind van het maken van een website. Ook is het met de volgende regel: "grid-template-columns: repeat(auto-fit, minmax(16em, 1fr));", mogelijk om de browser automatisch meer kolommen te laten maken als het past. Dit is een superhandig trucje!

### Checkout vraag:

#### _Welke feedback heb je gehad?_

> Visueel: De plankjes trekken nu het meeste aandacht, er gebeurt nu te veel. Zorg dat het logisch blijft. Op 3 plaatsen muziek krijgen, is dat logisch (platen plankjes, platen kast, cds kast)? Diederik vindt het veel. (zelf: Misschien 1 kast over het algemeen? met planken? dan meer een "logisch" geheel) Denk ook na over wat er gebeurt als het een horizontaal scherm wordt? Kleuren; donkere huiskamers kunnen dark mode zijn, speelt meer in op het gevoel. Light mode misschien een veel heldere moderne kamer (research kant) eventueel ook andere lettertypes voor beide, om dit onderscheid nog groter te maken.

> Techniek: Titels hiden (voor screenreader) met a11y methode, buttons for light dark, als svg code in html zodat dit te animeren valt.

</details>

<!--22 nov sprint 1 weekend-->
<!--22 nov sprint 1 weekend-->
<!--22 nov sprint 1 weekend-->
<!--22 nov sprint 1 weekend-->
<!--22 nov sprint 1 weekend-->
<!--22 nov sprint 1 weekend-->
<!--22 nov sprint 1 weekend-->
<!--22 nov sprint 1 weekend-->
<!--22 nov sprint 1 weekend-->
<!--22 nov sprint 1 weekend-->
<!--22 nov sprint 1 weekend-->
<!--22 nov sprint 1 weekend-->

### Wat heb ik vandaag gedaan:

Vandaag heb ik mijn gekozen schets (verder) uitgewerkt in een html opzet. Ik had dit al als huiswerk gedaan maar heb hier wat verfijning aan toegevoegd en met behulp van feedback de code vernieuwd. Na deze lesdag heb ik een goede basis om mee verder te gaan voor volgende week. In het weekend ga ik alvast wat css toepassen, en werken aan de illustraties voor de achtergrond.

<img src="images/" alt="schets met html annotaties" width="300"> !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

Na feedback (zie checkout vraag) van diederik heb ik het ontwerp wat aangepast, zodat er wat minder gebeurt en de aandacht op de juiste plek blijft. Zo is de kast nu een boekenkast, zodat er maar op 1 plek (de planken aan de muur) iets met muziek gebeurt (i.c.m. de platenspeler) bij horizontaal scherm is het idee dat alles van de mobiele weergave iets groter wordt, en er meer (niet interactieve) achtergrondelementen in beeld komen die bij het woonkamer idee horen.

### Index.html bestand update:
