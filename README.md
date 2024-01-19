# asom (arbetsgruppen för samordning kring mjukvara)

## Mål

Asoms primära mål är att underlätta praktisk digital samverkan kring utveckling och förvaltning av öppen källods-projekt mellan myndigheter. [Se exempel praktisk samverkan](#appendix)

## Strategi

- Att erbjuda en gemensam plats för myndighetsgemensam utveckling, där projekten följer bästa praxis för öppen källkod, med syftet att tillgängliggöra produkter av hög kvalitet, säkerhet och med korrekta licenser.

- Att i första hand bidra till befintliga projekt om möjligt istället för att ta fram egna lösningar, i syfte att minimera förvaltning och dubbelarbete.

- Att vidareutveckla de riktlinjer och ramar för utveckling och öppen förvaltning,[Mer om ramar, öppen förvaltning](#appendix) att vara aktuella och uppdaterade enligt gällande standarder, bästa praxis, regler och lagar.

- Att utgå från konkreta projekt för utveckling av ramar och riktlinjer, då det är ett effektivt sätt att identifiera frågor, hinder och möjligheter.

## Projektkrav

- Krav på i första hand eftersträva dialog med projekt uppströms om önskade funktioner i de fall det finns ett sådant.[Vad betyder uppströms-projekt](#appendix)

- Krav på att det måste finnas ett gemensamt myndighetsintresse för att implementera den utveckling som önskas genomföras inom asom:s ram.

- Krav på en förvaltningsplan.

- Krav på att uppfylla WCAG 2.1 när det är tillämpligt.

- Krav på finansiering av utvecklingsprojekt för tillgängliggörande.

- Krav på att vilja uppfylla de kvalitetsramar och praxis som asom och Digg har utformat.

(Kraven är inte skrivna i sten och ska ses som en första målsättning)

## Beslutsrätt och rådgivande funktion

Deltagande myndigheter inom asom har vardera en röst:

För närvarande är följande myndigheter deltagande:

- Trafikverket
- Försäkringskassan
- Digg
- Arbetsförmedlingen
- Länsstyrelsen
- Havs- och vattenmyndigheten
- Skatteverket
- Boverket

Övriga deltagare har en rådgivande funktion. För närvarande inkluderar detta:

- Intunio (Medverkar som leverantör åt Havs- och vattenmyndigheten)
- Foundation for Public Code
- Nosad
- Rise

## Roadmap

- Formalisera asom (pågående)
- Utforma krav för att inkludera projekt under asom (pågående
- Ha flera pågående utvecklingsprojekt och kunna demonstrera arbetsflödet för både utveckling och publicering (pågående)
- Initiera arbetet med att hitta en lösning för samfinansiering av förvaltning och utveckling av myndighetsgemensamma projekt (ej påbörjat)
- Följa upp att Försäkringskassan sätter upp GitLab-repositories som DIGG beställt (pågående)
- Följa upp att Jitsi-pluginet följer Foundation for Public Code's kriterier (efter nyår)
- Följa upp Försäkringskassan involveras i önskad vidareutveckling av Jitsi-pluginet. (Klar)

## Appendix

### Exempel på hur praktisk samverkan kan gå till

Havs- och vattenmyndigheten hade ett behov av en Jitsi-plugin med anledning av att myndigheten skall inför ny videomötestjänst.
Man kunde i dialog med andra myndigheter som redan använde Jitsi, konstatera att även de efterfrågade ett bra plugin till Outlook.
HaV utvecklade därför pluginen på ett generellt sätt, och lade ut det som öppen källkod på Digg's GitHub.
Det gjorde det möjligt för alla som önskar att både använda det och bidra i fortsatt utveckling av pluginet.
Därmed undvek vi dubbelarbete, och sparade utvecklingstid/skattepengar.

### Vilka ramar, vad är öppen förvaltning

Ramar som tagits fram asom, som till exempel [mallprojektet](https://github.com/diggsweden/open-source-project-template)
Med öppen förvaltning avses lösningar som är öppna att använda sig av (öppen källkod), men även förvaltas öppet, ibland med flera myndigheter för delat ansvar (och finansiering).

### Vad menas med uppströms

Uppströms (upstreams) är ett begrepp inom Öppen Källkod-världen, där man säger att basprojektet är uppströms, medan en modifierad kopia är en egen gren.
Det är därför nästan alltid bättre att i första hand få in lösningar i originalprojektet.
Detta för att undvika dubbelarbete och förvaltning.
Exempel: _Man behöver en funktion eller rätta ett kodfel i Jitsi. Man lägger ett ärende och diskuterar med projektet är intresserad innan vi gör ett modifierat tillägg som en Pull Request till projektet. Detta skedde exempelvis med moderatorpanelen för Jitsi där man ej var intresserad, och man gjorde därför en egen lösning_
