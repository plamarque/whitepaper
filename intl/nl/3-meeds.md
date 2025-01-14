# 3. Meeds token - de Work Metaverse valuta

De Work Metaverse wordt aangedreven door haar valuta - de Meeds (MEED) token. Meeds worden gebruikt om gebruikers te belonen (via engagement programma's), in winkels te kopen, Deeds te krijgen, financieel rendement op investeringen te krijgen etc.

## 3.1. Tokenomics

De **maximale voorraad Meeds is beperkt tot 100 miljoen tokens**, die geleidelijk worden geslagen. **Meeds worden geslagen met een snelheid van 10 MEED per minuut**. Daarom is de volledige munthorizon bijna 20 jaar (aangezien ongeveer $10*60*24*365 = 5M$ Meeds per jaar worden geslagen).

Tot op heden zijn 5 miljoen Meeds (5% van de totale voorraad) voorgemunt. Daarvan zijn 4,5 miljoen vastgezet in een kluiscontract met een lineaire vesting over 4 jaar. Het voorgemunt bedrag werd hoofdzakelijk gebruikt om software-IP te verwerven, de juridische kosten van de tokenemissie en hostingdiensten te betalen.

De rest is onderdeel van de __Meeds DAO-fondsen__ en zal worden gebruikt om diensten te betalen, evenals enkele lanceringsprikkels zoals airdrops en verwijzingscampagnes.


## 3.2. Minting allocatie

Gemunte Meeds worden toegewezen om de betrokkenheid van de drie categorieën belanghebbenden aan te moedigen - de gebruikers, de bouwers en de investeerders:

- De gebruikers (gebruikers en aktehouders/huurders) krijgen Meeds via engagementbeloningen (mintium model).
- Bouwers (leden van de vereniging en de gemeenschap) krijgen Meeds via de verenigingsfondsen om de WoM te bouwen, te exploiteren en te verbeteren.
- Investeerders krijgen Meeds door het huren en kopen van liquiditeitspools en het inzetten van Meeds.

In het begin krijgen de bouwers 30% van de toewijzing. De 70% wordt verdeeld tussen de gebruikers en de investeerders. Dit toewijzingsaandeel zal regelmatig worden herzien door middel van de stemming over de Vereniging Meeds DAO.

## 3.3. Gebruikers - minten door engagement

Een deel van de continu geslagen Meeds wordt toegewezen aan het engagement muntkanaal. De verdeling vindt wekelijks plaats. An het eind van een willekeurige week wordt de engagementindex berekend en kunnen Deeds de volgende week hun beloning opeisen en hun Meeds krijgen. Niet opgeëiste Meeds blijven in het fonds en worden toegevoegd aan de verdeling van de volgende week. Het model is in detail beschreven in het vorige hoofdstuk (deel 2.6).

## 3.4. Bouwers - Meeds associatie DAO en gemeenschap van bouwers

De WoM en het Meeds token worden beheerd door de non-profit Meeds Association DAO, die hierboven is geïntroduceerd. Een multisig contract genaamd de _MMeeds DAO Funds_ wordt gebruikt om de exploitatiekosten van de vereniging te beheren.

Tijdens de mint periode, **30% van de geslagen Meeds worden toegewezen aan de Meeds vereniging**.

Leden van de vereniging kunnen diensten verlenen aan de vereniging op basis van een ondertekende dienstenovereenkomst waarin het mandagen tarief wordt vastgesteld. Diensten worden maandelijks betaald in Meeds, op basis van de marktprijs. Oorbeelden van diensten zijn - verrijking van de Meeds-software, ontwikkeling van de WoM-app, ontwikkeling van nieuwe connectoren, exploitatie van de cloud-dienst, verlenen van financiële en juridische diensten, enz.

Zonder lid te zijn, kan elke Deed deelnemen aan de creatie van een nieuwe connector en daarvoor beloond worden - eerst doordat de Meeds associatie de connector verwerft en vervolgens door munten via deze connector.

De vereniging beheert een bouwersgemeenschap die WoM-liefhebbers verwelkomt, die willen bijdragen aan de creatie van de WoM. De vereniging zal de gemeenschap sponsoren uit haar budget, ter compensatie van het engagement van de leden van de gemeenschap.

Zo zal de gemeenschap functioneren als een voorbeeld van een Deed, die een standaard set van diensten aanbiedt die door de vereniging worden geleverd. De vereniging zet Meeds in om een Deed voor de gemeenschap in te wisselen. De gemeenschap zal dan ook deelnemen aan de inzet van de Deed zoals elke andere Deed.

Nadat de periode van het slaan voorbij is, wordt de vereniging in stand gehouden door :

- het belasten van passief inkomen (3% op de huur van Deeds)
- belasting op verkoopinkomsten (2,5% op Deeds verkoop)
- het waarnemen van transactiekosten over het gebruik van de perks stores
- handelen als een liquiditeitspool provider
- transactiekosten in rekening brengen wanneer een Deed niet-Meeds tokens distribueert via WoM-diensten.
- door de exploitatie van de Deeds die de vereniging in de loop der tijd heeft geslagen.


## 3.5. Investeerders

Investeerders helpen de WoM te creëren door liquiditeit te verschaffen en door Meeds te slaan en zo het prijsniveau tijdens de bouwperiode te stabiliseren. Beide worden aangemoedigd door het slaan van munten.

**Liquiditeitsverschaffers** Liquiditeitsbeheer is de sleutel tot het succes van het project en er zullen verschillende DeFi strategieën worden gebruikt om de kapitaalefficiëntie te optimaliseren. We beginnen met stimulansen voor het inzetten van MeedS/ETH LP pool tokens en zullen geleidelijk obligaties introduceren om te komen tot een protocol-eigen liquiditeit. Dit laatste zou bijdragen tot de duurzaamheid van de vereniging op lange termijn - zoals hierboven vermeld zullen de transactiekosten de werkingskosten van de vereniging, zoals cloud hosting, financieren.

Elk lid heeft ook het recht om rechtstreeks een grote hoeveelheid Meeds te kopen met korting. Het bedrag dat naar de verenigingsrekening wordt overgemaakt, wordt omgezet in ETH en samen met de equivalente waarde van Meeds toegevoegd aan de Liquidity Pool.

**Inzet / langetermijninvestering** Om langetermijninvesteringen aan te moedigen, worden gestoken Meeds beloond. Wanneer Meeds worden ingezet, krijgt de staker een aantal xMeeds tokens. Nieuw geslagen Meeds worden verdeeld onder stakers in verhouding tot hun xMeeds-bezit. In de praktijk worden geslagen Meeds effectief toegevoegd aan de holdings van het xMeeds smart contract en uitgedeeld aan de xMeeds-houder wanneer zij unstake.

Door Meeds in te zetten, kunnen beleggers ook Deeds inwisselen (en dan deelnemen aan het slaan van de munt door middel van betrokkenheid), waardoor de vraag naar tokens toeneemt. Elke ingezette Meeds (xMeeds) geeft zijn eigenaar een aantal punten per dag. Hoe langer de vastgelegde periode, hoe hoger het aantal punten per xMeeds. Elke Deed wordt dan ingewisseld in ruil voor een aantal punten.

Punten worden berekend met de onderstaande formule:

 $$ P = xMeeds / (xMeeds + 12000) * T / 240 $$

 waar :

- $xMeeds$ : xMeeds saldo zonder decimalen
- $T$ : Tijd verstreken in milliseconden

De formule vermijdt het bevoordelen van grote houders om de Deeds efficiënter en billijker te verdelen. De formule geeft bijvoorbeeld de volgende percentages :

| **Houder Grootte** | **Houderschap** | **Opbouwpercentage** |
| ------------------ | --------------- | -------------------- |
| Klein              | 1 000 xMeeds    | 28 punten/dag        |
| Middelgroot        | 10 000 xMeeds   | 164 punten/dag       |
| Groot              | 100 000 xMeeds  | 321 punten/dag       |


wat leidt tot de volgende houderstijd voor elke houderklasse :

| **Soort Kaart** | **Kosten**  | **Grote houder** | **Middelgrote houder** | **Kleine houder** |
| --------------- | ----------- | ---------------- | ---------------------- | ----------------- |
| Algemeen        | 8 000 ptn   | 25 dagen         | 49 dagen               | 9 maanden         |
| Ongewoon        | 32 000 ptn  | 100 dagen        | 6 maanden              | 3 jaar            |
| Zeldzaam        | 50.000 ptn  | 156 dagen        | 10 maanden             | 5 jaar            |
| Legendarisch    | 100.000 ptn | 311 dagen        | 20 maanden             | 10 jaar           |

## 3.6. Meeds DAO bestuur

Houders van Meeds tokens moeten tokens inzetten om te kunnen stemmen over de beslissingen van de Meeds DAO, zoals het beheer van het muntbudget of het kiezen van DAO-bestuursleden (jaarlijks mandaat).

## 3.7. Gedecentraliseerde financiële (DeFi) gebruikersdiensten

De Work Metaverse zal de blockchainwereld introduceren bij veel mensen die er vandaag geen gebruik van maken.

Elk werk (al dan niet digitaal) kan immers worden gegamificeerd en elk engagement - beloond met Meeds. Meeds worden beschikbaar gesteld aan gebruikers via een gebruiksvriendelijke, op blockchain gebaseerde portefeuille die elke complexiteit van de cryptowereld "abstraheert" voor de gemiddelde gebruiker.

Naast de portemonnee en een winkel waar ze extraatjes voor Meeds kunnen kopen, zijn we van plan elke gebruiker kennis te laten maken met verschillende eindgebruikersproducten die aangedreven worden door de Decentrale Financiële Protocollen, zoals:

- De mogelijkheid om Meeds tokens in te zetten en opbrengsten te krijgen (inkomsten genereren)
- De mogelijkheid om Meeds Tokens te gebruiken als onderpand om stabiele munten zoals USDC te lenen (maak eerst een [zekerpoel](https://app.rari.capital/fuse) en registreer de Meeds token tot [AAVE](https://aave.com/).
- Een digitale kaart die kan worden toegevoegd en gebruikt via Apple Pay, Google pay of elke geldautomaat. Deze laatste kan worden verstrekt via een partnerschap met VISA en zal gebruikmaken van een kredietlijn in USDC, die wordt beveiligd door ingezette Meeds. Deze kaart zou ook kunnen worden gebruikt door organisaties om portemonnees van werknemers te financieren voor het beheer van personeelsvoordelen zoals restaurants, vervoer en alle soorten uitgaven.

Zo zullen niet alleen veel nieuwe gebruikers de blockchainwereld ontdekken, maar ook een bankloze wereld.

 
