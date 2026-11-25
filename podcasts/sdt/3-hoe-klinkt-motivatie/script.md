# Zelfdeterminatietheorie · aflevering 3: Hoe klinkt motivatie? · script v1 (25 nov 2026)

Persoonlijke studiepodcast voor Kamiel, op basis van het literatuuronderzoek *Motivatie in leerlingentaal (SDT × taal × AI)*, secties 3, 4 en 6 (https://claude.ai/artifact/VFBrPvjxSvbojdtV3mp3kj).

Stem: Remko (`vjeU1L5RIGPyrwuboFwz`), eleven_v4, één take per segment.

Beweringen en bronnen:
- Codeersysteem motiverende gespreksvoering (MISC) codeert gedrag van de hulpverlener en verandertaal/behoudtaal van de cliënt (MISC-handleiding; Apodaca e.a. 2016).
- 92 studenten: bevestigen was het enige gedrag dat verandertaal verhoogde én behoudtaal verlaagde (Apodaca e.a.).
- 129 opgenomen groepssessies met jongeren gecodeerd (PMC4300532). Motiverende gespreksvoering gaat uit van verandering via intrinsieke motivatie in de zin van SDT (PMC6415657).
- Functiewoorden en voornaamwoorden zeggen iets over psychologische toestand (Chung & Pennebaker; Tausczik & Pennebaker 2010). Modale werkwoorden als marker is een idee uit het literatuuronderzoek, geen onderzoeksuitkomst.
- Benchmark automatisch herkennen drie behoeften in korte Engelse posts (Stajner e.a. 2021); NLP gebruikt SDT nog nauwelijks (Wemmer & Röcker 2025).
- Kappa: mens–mens vaak 0,40–0,60 (Jain e.a. 2025); GPT-4 8 van 9 codes boven 0,6, GPT-3.5 gemiddeld 0,34 (Dunivin 2024); Discord inductief 0,57, deductief 0,46 (Zhang e.a.); acht modellen samen 0,89 waar mensen 0,67 haalden (ensemble 2025); SDT-leraartaal: LLM iets anders, niet tegenstrijdig (PMC12427170).
- Codeboek herschrijven, model laten onderbouwen (Dunivin). Open brief en debat over reflexiviteit (De Paoli 2025).

---

## 0 · Opening (± 35 s)

'Ik moet dit nog doen.' 'Ik wil dit snappen.' Twee korte zinnen. Hoor je het verschil in motivatie?

Waarschijnlijk wel. De vraag is of je dat verschil ook betrouwbaar kunt meten. En of een taalmodel het kan. In deze aflevering drie stappen. Eén: hoe hulpverleners al jaren motivatie in gesprekken coderen. Twee: wat kleine woorden verraden. Drie: een taalmodel als tweede codeur. En aan het eind: waar jouw onderzoek past.

## 1 · Verandertaal (± 3 min)

Deel één. Verandertaal.

Het best uitgewerkte voorbeeld komt uit de hulpverlening. Daar bestaat een gespreksstijl voor mensen die twijfelen of ze iets willen veranderen, bijvoorbeeld hun drankgebruik. Die stijl heet motiverende gespreksvoering. Anders gezegd: de hulpverlener duwt niet, maar helpt iemand zijn eigen redenen voor verandering te verwoorden.

Onderzoekers ontwikkelden er een codeersysteem voor. Het codeert twee kanten van het gesprek. Wat de hulpverlener doet, zoals een open vraag stellen, iets samenvatten of iemand bevestigen. En wat de cliënt zegt. Zegt die iets in de richting van verandering, zoals 'Misschien moet ik minder drinken'? Dat heet verandertaal. Zegt die iets tegen verandering, zoals 'Ik heb geen probleem'? Dat heet behoudtaal.

Wat is 'Misschien moet ik eens anders gaan plannen': verandertaal of behoudtaal?

[STILTE 3]

Verandertaal.

Met dit systeem kun je per uiting van de hulpverlener nagaan wat de cliënt daarna zegt. Bij tweeënnegentig studenten bleek bevestigen het enige gedrag dat verandertaal verhoogde én behoudtaal verlaagde. Het werkt ook bij jongeren: honderdnegenentwintig opgenomen groepssessies met adolescenten zijn zo gecodeerd. En motiverende gespreksvoering gaat er zelf van uit dat verandering verloopt via het versterken van intrinsieke motivatie. Het sluit dus direct aan op de zelfdeterminatietheorie.

Kort gezegd: motivatie in gesprekken is te coderen, aan beide kanten van het gesprek. En dat principe, uiting gevolgd door reactie, is precies wat jij nodig hebt.

## 2 · Kleine woorden (± 2,5 min)

Deel twee. Kleine woorden.

Psychologen ontdekten iets onverwachts. Niet de grote, inhoudelijke woorden zeggen het meest over je psychologische toestand, maar de kleine. 'Ik', 'wij', 'niet', 'maar'. Die kleine woorden heten functiewoorden. Anders gezegd: functiewoorden zijn het cement tussen de stenen van een zin, en juist dat cement verraadt hoe iemand denkt.

Er bestaat software die zulke woorden telt in psychologische categorieën. Voornaamwoorden, emotiewoorden, woorden over anderen.

Wat zou meer zeggen over verbondenheid: hoe vaak iemand 'wij' zegt, of hoe vaak iemand 'school' zegt?

[STILTE 3]

'Wij'. Het gaat om de relatie, niet om het onderwerp.

Voor jouw onderzoek kun je zo een paar kandidaten bedenken. 'Wij' als teken van verbondenheid. 'Moeten', 'willen' en 'mogen' als tekens van autonomie of controle. Let wel: dat zijn ideeën om te toetsen, nog geen bewezen markers.

Is dit al eens automatisch gedaan? Een beetje. In het jaar 2021 zette een team als eerste een test op om de drie behoeften automatisch te herkennen in korte Engelse berichten van internet. En in het jaar 2025 schreven onderzoekers dat taaltechnologie deze theorie nog nauwelijks gebruikt.

Kort gezegd: kleine woorden verraden veel. Maar bijna al het werk gaat over geschreven Engelse tekst van internet, niet over gesproken Nederlands.

## 3 · Een taalmodel als tweede codeur (± 3 min)

Deel drie. Een taalmodel als tweede codeur.

In kwalitatief onderzoek laat je gesprekken vaak door twee mensen coderen. Daarna kijk je hoe vaak ze het eens zijn, gecorrigeerd voor toeval. Die maat heet kappa. Anders gezegd: kappa is nul als twee codeurs het alleen bij toeval eens zijn, en één als ze het altijd eens zijn.

Het verrassende is dat twee getrainde mensen vaak maar rond de helft van die schaal uitkomen.

Kan een taalmodel de tweede codeur zijn? De resultaten lopen uiteen. Bij goed omschreven codes haalt een sterk model vaak hetzelfde niveau als mensen onderling. Een ouder, zwakker model bleef in een van die studies steken rond een derde. En acht modellen samen, met een meerderheidsstem, haalden in één studie zelfs bijna negen tiende, op taken waar mensen onderling lager uitkwamen.

En de zelfdeterminatietheorie? Er is een studie die uitspraken van leraren in de klas codeerde volgens deze theorie, door mensen én door een taalmodel. Het model gaf iets andere uitkomsten, maar sprak de menselijke codering niet tegen.

Hier is het belangrijke punt. Niet alleen het model bepaalt hoe goed het werkt. Het codeboek bepaalt het. Een codeboek dat voor mensen geschreven is, moet je herschrijven voor een model. En als je het model laat uitleggen waarom het een code kiest, gaat de kwaliteit duidelijk omhoog.

Denk even na. Waarom zou je een taalmodel als tweede codeur gebruiken, en niet als enige?

[STILTE 4]

Omdat interpretatie mensenwerk blijft. Er is zelfs een open brief van onderzoekers die vinden dat kwalitatief onderzoek helemaal menselijk moet blijven, omdat een model niet kan reflecteren op zijn eigen rol. Je hoeft het daar niet mee eens te zijn. Maar het pleit voor een opzet waarin jij codeert, en het model controleert en opschaalt.

Kort gezegd: een taalmodel kan een goede tweede codeur zijn, mits het codeboek scherp is en jij de eindbeslissing houdt.

## 4 · Afsluiting: jouw plek (± 1 min)

Terug naar de twee zinnen van het begin. 'Ik moet dit nog doen.' 'Ik wil dit snappen.' Het verschil is hoorbaar, en het is in principe te meten.

Hier ligt het gat in de literatuur. Er is onderzoek naar de taal van leraren, naar online tekst en naar hulpverleners. Maar er is bijna niets over hoe leerlingen praten in een coachgesprek, in het Nederlands, in onderwijs met veel vrijheid. Precies die gesprekken voer jij elke week.

Drie dingen om te onthouden. Eén: verandertaal laat zien dat je motivatie in gesprekken kunt coderen, aan beide kanten. Twee: kleine woorden als 'wij' en 'moeten' zijn veelbelovende markers, maar nog niet bewezen. Drie: een taalmodel werkt als tweede codeur, als het codeboek scherp is.

Leg nu in één zin hardop uit welke onderzoeksvraag jij zou willen stellen over je eigen coachgesprekken.
