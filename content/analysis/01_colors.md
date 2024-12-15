---
Title: Färgval och känsla
Description: I den här rapporten analyseras tre webbplatser i hur de använder färger och typografi för att locka besökare och skapa en viss känsla för dem. Utvärderingen kommer bestå av analys av färgscheman, typografi och helhetsintryck för att få en ide av designstrategier och ifall de har lyckats.
Template: analysis
---

<hr>

En analys av hur färger och typografi används på tre webbplatser för att skapa en viss känsla eller signalera ett budskap.

## 1. Urval
<hr>
För att genomföra analysen valde jag att fokusera på tre webbplatser inom samma kategori: ishockey. Jag gjorde detta val för att jämföra hur olika klubbar inom samma område/liga använder sig av färger och typografi för att vissa sin identitet.
1. Webbplats A - [https://www.kalmarhockey.com/]
2. Webbplats B - [https://www.difhockey.se/]
A och B valdes eftersom de är två klubbar i samma liga, så då kan en analys göras hur två olika kulubbar anpassar sina sidor för att skapa en känsla och kommunicera med sina supportar.
3. Webbplats C - [https://www.hockeyallsvenskan.se/]
C är ju för hela liggan som alla klubbar spelare i så denna sidan ska ju vara mer allämen och neutral. Helt enklet vara vara ämnad för alla supportar oavsätt vilken klubb man heja på, ås ingen favotisering ska ju vissas. 


## 2. Metod
<hr>
För att analysera färger och typografi använde jag:
- Verktyg: Främst använt mig av devtools för att inspektera element på sidorn och där igenom ta fram deras färgpalett och typografi. Genom att gå in on kolla element så får man tillgång till nörvänding information som stilar, inklusive color, background-color, font-family, och andra egenskaper.
- Geonom jag använder DevTools för denna info så blir det enklare att:
Granska kontraster: Se hur läsbarheten och hur färger harmoniserar eller inte.
Färgschema: Identifiera vilka färger som används och kategorisera dem enligt grundläggande färgteori.
Typografi: Dokumentera rubrik- och texttypsnitt för H1-H3 och brödtext.

## 3. Resultat
<hr>

### 3.1 Webbplats A - Kalmar Hockey
<hr>
Här är en snapshot av webbplatsen Kalmar Hockey:

<img src="../assets/img/kalmarHC.png" alt="Kalmar Hockey" class="analysis-image">

<div class="color-palette">
    3.2 Här är färgpaletten för Kalmar HC baserad på deras webbdesign:
    <table style="border-spacing: 10px; border-collapse: separate; margin-top: 1rem;">
        <tr>
            <td style="height: 50px; width: 50px; background-color: rgba(140, 20, 18, 1)"></td>
            <td style="height: 50px; width: 50px; background-color: rgba(176, 25, 23, 1)"></td>
            <td style="height: 50px; width: 50px; background-color: #ffffff; border: 1px solid #ccc;"></td>
        </tr>
        <tr>
            <td style="text-align: center;">Navbar-färg</td>
            <td style="text-align: center;">Meny & footer-färg</td>
            <td style="text-align: center;">Textfärg & boardercolor</td>
        </tr>
    </table>
</div>
3.3 Kalmar HC:s färgval, är ett monokromatiskt färgschema, eftersom det använder olika nyanser av rött och kompletterar med vitt för kontrast. 

3.4 På Kalmar HC:s webbplats används olika typsnitt beroende på vilken del av sidan man befinner sig på. För rubriker och brödtext används Roboto eller Roboto Condensed.

 - Roboto används som standard för större delen av texten, inklusive brödtext och vissa rubriker.
 - Roboto Condensed används på andra sidor på kalmar HC  sidan som rubriker och vissa specifika textavsnitt där en smalare och mer kompakt textstil är önskad.
Webbplatsen är inställd så att om det primära typsnittet inte kan laddas korrekt, faller den tillbaka på den andra familjen Roboto, arial, helvetica, sans-serif.

3.5 Kalmar HC:s färgval och typografi speglar klubbens profil väl, där de röda nyanserna som spelgar deras logo, match tröjor, m.m, medan de moderna typsnitten, Roboto med  vitt, gör det tydligt och en känsla som passar en hockeyklubb.

### 3.1 Webbplats B - Djurgården Hockey
<hr>
Snapshot från Djurgården Hockeys webbplats:
<img src="../assets/img/djurgårdenIF.png" alt="Kalmar Hockey" class="analysis-image">

<div class="color-palette">
    3.2 Här är färgpaletten för Djurgården IF baserad på deras webbdesign:
    <table style="border-spacing: 10px; border-collapse: separate; margin-top: 1rem;">
        <tr>
            <td style="height: 50px; width: 50px; background-color: rgba(15, 34, 60, 1)"></td>
            <td style="height: 50px; width: 50px; background-color: rgba(20, 46, 80, 1)"></td>
            <td style="height: 50px; width: 50px; background-color: #ffffff; border: 1px solid #ccc;"></td>
        </tr>
        <tr>
            <td style="text-align: center;">Navbar-färg</td>
            <td style="text-align: center;">Meny & footer-färg</td>
            <td style="text-align: center;">Textfärg & boardercolor</td>
        </tr>
    </table>
</div>
3.3 Djurgården IF:s färgval, är också monokromatiskt färgschema, eftersom det använder olika nyanser av blått men ljusare än hockey sidan och kompletterar med vitt för kontrast. Deras logo innehåller rött och gult som inte direkt reflekteras på deras sida, bortsätt från i bilderna, så det kan ses lite som en borttappad möjlighet att få sidan att sticka ut.

3.4 Typografi - Djurgården Hockey
Djurgården-sidan använder Arial och Helvetica som standardteckensnitt, definierat på html-nivå i CSS. Det innebär att:

 - Alla rubriker (h1, h2, h3, osv.) och brödtext (p, span) ärver detta teckensnitt.
 - Teckensnittet ger sidan en enkel och funktionell design, utan att använda mer dekorativa eller avancerade typsnitt.

3.5 Djurgården Hockeys färgval och typografi förmedlar en traditionell och funktionell profil, med ljusare blå nyanser som kompletteras av vitt för kontrast och tydlighet. Det enkla valet av Arial och Helvetica som ger sidan en praktisk och lättläst utformning.

### 3.1 Webbplats C - HockeyAllsvenskan
<hr>
Snapshot från HockeyAllsvenskans webbplats:
<img src="../assets/img/hockyallsvenskan.png" alt="Kalmar Hockey" class="analysis-image">

<div class="color-palette">
    3.2 Här är färgpaletten för Hockeyallsvenskan baserad på deras webbdesign:
    <table style="border-spacing: 10px; border-collapse: separate; margin-top: 1rem;">
        <tr>
            <td style="height: 50px; width: 50px; background-color: rgba(3, 22, 35, 1)"></td>
            <td style="height: 50px; width: 50px; background-color: rgba(4, 28, 44, 1)"></td>
            <td style="height: 50px; width: 50px; background-color: rgba(24, 58, 75, 1)"></td>
            <td style="height: 50px; width: 50px; background-color: #ffffff; border: 1px solid #ccc;"></td>
        </tr>
        <tr>
            <td style="text-align: center;">Överst</td>
            <td style="text-align: center;">Header/navbar & footer-färg</td>
            <td style="text-align: center;">Hidden menu</td>
            <td style="text-align: center;">Textfärg & boardercolor</td>
        </tr>
    </table>
</div>
3.3 Hockeyallsvenskans färgval, är också monokromatiskt färgschema, eftersom denna använder olika nyanser av blått och kompletterar med vitt för kontrast när det kommer till text. 

3.4 På HockeyAllsvenskans webbplats används Barlow som primärt typsnitt för både rubriker och brödtext.

 - Barlow används för att ge webbplatsen en modern och stilren känsla. Det är ett sans-serif-typsnitt som är lättläst och lämpar sig väl här.
 - Typsnittet används konsekvent över hela webbplatsen, vilket bidrar till en enhetlig visuell identitet och förbättrar användarupplevelsen.

3.5 HockeyAllsvenskans ska ju vara en allmän sida för hela hockyligan, så dess färgval och typografi ska vara professionellt, modern profil och neutral, de blå nyanserna passar för hockey och signalerar stabilitet, medans de konsekvent använder det stilrena typsnittet Barlow för tydlighet, men kunde valt annat färgschema för att inte likna andra lag i ligans sidor. 

## 4 Analys
<hr>
Kalmar HC: monokromatiska färgschema med röda nyanser speglar klubbens varumärke väl och blir ändå läsbar genom kombination med vitt för god kontrast och passande. HockeyAllsvenskan: Som en allmän plattform för hela ligan bör HockeyAllsvenskan vara mer neutral, dess blå färgschema och yypografi med Barlow bidrar till en stilren och modern känsla, men färgschemat riskerar att likna vissa lag i ligan, vilket kan minska webbplatsens unika identitet. Djurgården Hockey: Webbplatsen för Djurgården Hockey använder ljusare blå nyanser, vilket skiljer något HockeyAllsvenskans mörkare palett och är tydligt genom att kompletteras med vitt, men hade kunnats göra mer unikt genom att unytja lagets alla färger med rött och gult ytterligare för att sticka ut. En viktig observation från denna studie är hur valet av färger och typsnitt påverkar intrycket av en webbplats och dess förmåga att kommunicera sin profil/ståndpunkt. fått tyligt ide hur olika färgshcmean funkar speciellt monokromatiska färgscheman och hur de är effektiva för att skapa en sammanhängande design.Typografi spelar också en avgörande roll i att förstärka varumärket och i detta fall hade man aknske kunnat slapa ännumer invidulaitet genom att använda mer unika eller skiljande typsnitt.Genom att jämföra dessa tre webbplatser framgår det att färg och typografi inte bara är estetiska val, utan också strategiska verktyg för att kommunicera identitet, skapa en viss känsla, och engagera användare.

## 5: Övrigt
<hr>
Av Oscar Sandberg, Ossn17



