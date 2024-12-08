---
Title: Utvärdera webbplatsers laddningstid och användbarhet 
Description: En analys av laddningstid och användbarhet för tre utvalda webbplatser.
Template: analysis
---

=======================

I denna analys utvärderas laddningstide och förbättringsmöjligheter för tre webbplatser med hjälp av mätverktyg som Google PageSpeed och DevTool och allt resultat är sammanställt i en rapport med visualiseringar från ett kalkylark.

## 1. Urval

För analysen valde jag tre webbplatser med olika målgrupper och syften för att få en bred jämförelse av laddningstid och användbarhet.

Kalmar HC - https://www.kalmarhockey.com/: En sportklubbs webbplats som representerar en lokal hockeyklubb och mitt favorit lag. Webbplatsen riktar sig till supportrar och lokala invånare med fokus på information, nyheter och matcher.

D&D Beyond - https://www.dndbeyond.com/:
En internationell webbplats som fungerar som en resurs och verktyg för spelare av rollspelet Dungeons & Dragons. Den innehåller tunga interaktiva element och mycket information.

Aktiespararna - https://www.aktiespararna.se/:
En svensk webbplats som riktar sig till aktiesparare och investerare med nyheter, analyser och verktyg för ekonomiska beslut.

Med dessa tre sidorså får man olika typer av webbplatser, för olika målgrupper och innehållsstrukturer, hanterar laddningstid och optimering på olika sätt. Kalmar HC är en mindre lokal sida, D&D Beyond en större internationell plattform, och Aktiespararna en nationell webbplats med fokus på affärsinformation.

## 2. Verktyg och metod
#### Verktyg:
Använd följande verktyg för denna analys:

Google Pagespeed Insights: För att mäta betyg på Mobile och Desktop.
DevTools (Network-fliken): För att mäta laddningstid, antal resurser och sidans storlek.
Google Sheets eller Excel: För att spara dina mätvärden och räkna ut snittet.

#### Metod:
Öppna varje webbplats och välj tre sidor på varje webbplats för att analysera.

För varje sida:
Mät Google Pagespeed-betyg för både Mobile och Desktop.
Använd Shift + Ctrl + R i DevTools för att rensa cachen och mäta laddningstid, antalet resurser och sidans totala storlek. 
Detta upprepas tre gånger för varje sida och sedan tas snittet som läggs in i excel ark för enkel visualisering.

## Resultat
<div class="spreadsheet-container">
    <iframe 
        src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTTxDyH7DFd4cKGoM_YZ7-Sao5rZ-J8itBWQM46JWRquAbHW3wXQzovP4PhTWbjRR5PkLx5B2Rmr3Cs/pubhtml?widget=true&amp;headers=false" 
        width="100%" 
        height="300" 
        style="border: 1px solid #ccc; margin: auto; display: block;">
    </iframe>
</div>

### Webbplats A - Kalmar HC
<img src="../assets/img/load2_hc.png" alt="Kalmar Hockey" class="analysis-image">
#### Sida 1 - spelshcema: https://www.kalmarhockey.com/game-schedule
#### Sida 2 - nyheter: https://www.kalmarhockey.com/article/archive
#### Sida 2 - Trupp: https://www.kalmarhockey.com/team/4b7a-cd81IIiWF/khc1_khc/squad
#### Förbättringar:
Webbplatsen kan förbättras genom att optimera bildstorlekar och använda moderna format som WebP för att minska sidstorlek och laddningstider. Dessutom kan tunga JavaScript-filer och externa resurser anpassas eller tars bort för att skapa en bättre prestanda för denna websidda när det kommer till både mobil och desktop.

### Webbplats B - D&D beyond
<img src="../assets/img/D&D.png" alt="Kalmar Hockey" class="analysis-image">
#### Sida 1 - https://www.dndbeyond.com/how-to-play-dnd?srsltid=AfmBOorbnijM-_Dg-QviCL5tMdT95xnQ1fmkyByMwSMgGMcOniy4_zrs
#### Sida 2 - https://www.dndbeyond.com/sources#Sourcebooks
#### Sida 3 - https://marketplace.dndbeyond.com/
#### Förbättringar: 
Webbplatsen kan förbättra sina laddningstider genom att konvertera bilder till WebP-format för att minska filstorleken, och använda lazy loading för bilder som inte är synliga direkt, eftersom att vissa av dens sidor har väldigt mycket bilder.

### Webbplats C - Aktiespararna
<img src="../assets/img/aktie.png" alt="Kalmar Hockey" class="analysis-image">
#### Sida 1 -https://www.aktiespararna.se/nyheter
#### Sida 2 - https://www.aktiespararna.se/om-oss
#### Sida 3 - https://www.aktiespararna.se/analyser
#### Förbättringar: 
Aktiespararna skulle nog kunna optimeras ytterligare genom reducera antalet bilder och storleken på JavaScript-filer, även med lazy loading för att minska laddningstider.

### Analys
De vanligaste förbättringsåtgärderna som kunde identifierades är bildoptimering speciellt på sidor med mycket bilder, men även minimering av JavaScript och CSS, samt implementering av lazy loading hade hjälp i sådana situationer. Att implemenmtera dessa åtgärder kan webbplatser minska sina laddningstider, förbättra användarupplevelsen och se till att de får en snabbare och smidigare upplevelse för sina besökare.

Rangordning och Vinnare
Efter att ha analyserat laddningstid, antal resurser och sidstorlek för varje webbplats, är rangordningen som följer:

1. Aktiespararna
Motivering: Aktiespararna var bäst i flesta kategorier. som låg laddningstid (0,3–0,36 s), relativt få resurser (140–173) och små sidstorlekar (7,2–8,3 MB), erbjuder denna webbplats en snabb och smidig användarupplevelse. Desktop- och mobilpoängen på Google Pagespeed är också höga speciellt när man jämför med de andra webbplatserna, vilket tyder på en bättre optimerad webbplats.

2.  D&D Beyond
Motivering: D&D Beyond lider av högre laddningstider (1,31–3,39 s) och stor sidstorlek (14,3–41,2 MB), vilket påverkar användarupplevelsen negativt. Trots det är deras Google Pagespeed-poäng på desktop relativt bra (27–62). Webbplatsen har potential föbättre vissa sidor som drar ner webplattsen överlagg på grund av dess många resures och stor data mängd, genom att förbättras genom optimering av bilder och script.

3. Kalmar HC
Motivering: Kalmar HC presterar sämst i analysen. Med höga laddningstider (0,94–1,89 s), många resurser (115–192) och relativt stora sidstorlekar (9,1–11,26 MB), har denna webbplats den största förbättringspotentialen. Låga Google Pagespeed-poäng (11–45) visar att det finns betydande arbete att göra för att optimera användarupplevelsen.

Aktiespararna sticker ut som den bäst presterande webbplatsen genom effektiv hantering av resurser och inte överfyllda sidor heller. D&D Beyond presterar som näst bäst, men dras ner av mängder med tunga resurser och långsamma laddningstider på vissa sidor. Kalmar HC är den sämsta sida och skulle behöva förbättras genom möjligen att minska antalet resurser och bättre metoder. Generellt visar analysen att optimering av bilder, minimering av script och implementation av lazy loading är avgörande för att förbättra prestandan på alla tre webbplatser.
#### Gräns tid
Snabb webbplats:
En webbplats med en laddningstid under 1 sekund uppfattas som snabb. Detta gör att användaren får innehållet presenterat omedelbart utan att behöva vänta.

Mitt urval av webbplatser visar att Aktiespararna klarar gränsvärdet för snabb laddningstid med god marginal och upplevs som mycket snabb, medan D&D Beyond ligger däeremot ofta över gränsen på 1 sekund och kan därför upplevas som långsam/seg på vissa sidor, och Kalmar HC ligger närmare gränsen och även under den på vissa sidor, men med tanke på dess storlek och några uppdatering kunna hman under gränsen oavsätt.

## övrigt
Av Oscar Sandberg, ossn17