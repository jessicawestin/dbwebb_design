---
Title: SOS…loading
Description: Design / rapport kmom05.
Template: analysis
---
### Design rapport kmom05

SOS…loading
=======================

Denna rapport gör en kvalitativ mätning och undersökning av laddningstid av hemsidor från tre svenska samhällsbärande funktioner.


Urval
-----------------------
Jag valde hemsidorna från tre stycken samhällsbärande funktioner i Sverige, Polisen, 1177 samt Myndigheterna för samhällsskydd och beredskap (händanefter MSB). Detta urval skedde då jag var intresserad av att mäta hur snabbt hemsidor från myndigheter och samhällsbärande funktioner laddas, då användare oftast använder dessa sidor under akut kris, snarare än att de “browsar runt”. 


Metod
-----------------------
I min metod har jag uteslutande använt mig av produkter från Google: webbläsaren Chrome och dess verktyg för webbutvecklare, Google Pagespeed, samt Google Drive (Google Kalkylark). 

Resultat
-----------------------
### Polisen

<div class="img-right">
    <a href="https://www.polisen.se/" target="_blank">
    <img src="%base_url%?image/polisen.png?w=600&h=376" alt="Polisen">
    </a>
</div>

<div style="text-align: center">
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vT1zOFPco-gJGC0O59TGC75eE30JA19JRTBDlI87ptBi15ig67BSVs-yQFyVQnvkA-5NiyRdEneDcqB/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" frameborder="0" width="50%" height="650" scrolling="no" title="Polisen"></iframe>
</div>

Polisens hemsida levererar genomgående bra resultat på mätningarna i Pagespeed samt i utvecklarverktyget. Det som hemsidan skulle kunna förbättra framförallt prestandan på både desktop och mobil, där hastigheten drar ner genomsnittsbetyget. Vissa bildelement saknar width och height, samt bildinläsningen var uppskjuten vid största uppritningen av innehåll. 

### 1177
<div class="img-right">
    <a href="https://www.1177.se/" target="_blank">
    <img src="%base_url%?image/1177.png?w=600&h=376" alt="1177">
    </a>
</div>
<div style="text-align: center">
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vT1zOFPco-gJGC0O59TGC75eE30JA19JRTBDlI87ptBi15ig67BSVs-yQFyVQnvkA-5NiyRdEneDcqB/pubhtml?gid=1132339801&amp;single=true&amp;widget=true&amp;headers=false" frameborder="0" width="50%" height="650" scrolling="no" title="1177"></iframe>
</div>



1177 har framförallt prestandaproblem, med två av samma problem som polisen: bilderna kan läsas in i förväg för största uppritning av innehåll och bilderna saknar width och height. Dessutom så skickas inte statiska tillgångar med en effektiv cachelagringspolicy, och möjligheten att förbättra prestandan kan ske genom att reducera JavaScript som inte används. I övrigt så skulle de två undersidorna som har mätts kunna förbättra sin SEO, som båda ligger på kring 91/100, speciellt då dessa sidor är relevanta ur användarperspektiv. 


### MSB
<div class="img-right">
    <a href="https://www.msb.se/" target="_blank">
    <img src="%base_url%?image/msb.png?w=600&h=376" alt="MSB">
    </a>
</div>
<div style="text-align: center">
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vT1zOFPco-gJGC0O59TGC75eE30JA19JRTBDlI87ptBi15ig67BSVs-yQFyVQnvkA-5NiyRdEneDcqB/pubhtml?gid=1132339801&amp;single=true&amp;widget=true&amp;headers=false" frameborder="0" width="50%" height="650" scrolling="no" title="MSB"></iframe>
</div>

MSB har mycket att förbättra på sin hemsida. Tillgängligheten är det som levererar bäst på mätningen på Google Pagespeed, där den levererar genomgående 98/100 på alla sidor, både på desktop och mobil. Det är prestandan som levererar sämst, så lågt som 28/100 på mobilt på dess landningssida, däribland då de har ett “onödigt stort DOM-träd” med 6717 element. Möjligheterna till förbättring ligger i att bilderna kan uppdateras till ett modernare format bildformat samt att skjuta upp inläsningen av bilder som inte visas på skärmen. Dessutom skulle MSB kunna aktivera textkomprimering samt att texten vara synlig medan webbteckensnitten läses in. 


Analys
-----------------------

Resultatet av min undersökning var lite överraskande, då jag skulle ha chansat på att MSB, som bland annat, är ansvariga för informationssäkerhet, cybersäkerhet och säkra kommunikationer, skulle ha en bättre hemsida som är snabb, optimerad och presterar bra. Deras hemsida levererar de sämsta resultaten, vilket i mitt tycke visar på att de inte tar ansvar för just säkra kommunikationer. För när krisen och kriget har inträffat (som ju har skett de senaste 3 åren), så är känslan att det flesta söker information online, snarare än andra kontaktvägar. 
Den förbättring som skulle kunna ske på alla hemsidor är att sätta width och height på bildelementen, detta för att undvika att layouten skiftas samt förbättrar användarupplevelsen för besökarna på hemsidan då browsern kan direkt avgöra hur mycket storlek som bilderna förväntas ta istället för att inte veta exakt storlek på bilderna och därför inte kan spara lämpligt utrymme för bilderna. 

### Testvinnare 
1. polisen.se
2. 1177.se
3. msb.se


### Laddningstid
En laddningstid under 0.9 millisekunder anser jag vara en snabb webbplats, samt allting över 2.5 sekunder tycker jag är långsam. 

Polisens webbplats klarar mitt gränsvärde för snabb webbplats, och jag upplever den som otrolig lättillgänglig. 1177 ligger strax över gränsvärdet, och msb.se är långt över gränsvärdet (4.5 sekunder i genomsnitt för startsidan), och det gör även att känslan är att webbplatsen är långsam. 

### Avslutande notering
I tillägg vill jag notera att de enda verktyg jag har använt för denna rapport är skapade av Google, ett amerikanskt företag med ett nästintill monopol på internetverktyg. Jag vill lyfta att det kan vara problematiskt att ett företag är styrande på vad som beräknas som “bra” prestanda på internet, då det inte är det allmänna intresset som styr utan det är faktiska reklamintäkter (sökannonser). Att låta ett företag med vinstintressen och deras verktyg styra svenska samhällsbärande funktioners resultat och hur bra de anses vara online, tillsammans med hur besökares upplevelse av svenska myndigheters hemsidor anser jag är högst problematiskt. Dock jag inga förslag på andra lösningar, då det skulle krävas en reform av all internetanvändning på ett globalt plan.  



Övrigt
-----------------------

Författare:
Jessica Westin 
