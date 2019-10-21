HEADER:
I denna sektionen har jag lagt loggan och menyn, både för stor och liten skärm. Jag har gjort två olika klasser,
en class "hide-desktop" där hamburgaren är i och som bara ska visas när skärmen är mindre. Och en klass som heter "show-desktop och
hide-mobile" där menyn som ska visas för större skärmar finns. 
Gjordes eftersom att då kan jag använda "display: block" när de inte ska visas. 

VÄLKOMMEN:
Här har jag använt mig av bootstrap. 

TJÄNSTER:
Här har jag använt mig av flex-box för att få bilderna på rätt plats och även en "hover"-effekt för extra tydlighet att 
det är länkar. 
Vid större skärmar än 650px har jag lagt bilderna bredvid varandra och även ändrat storleken på bilderna något. 

OM OSS:
Även här har jag avvänt mig av flexbox och "listan" blir bredvid varandra när skärmen blir bredare än 1024px. 

KONTAKT: 
Här har jag använt mig av bootstrap. 

FOOTER:
Här har jag inte ändrat speciellt mycket beroende på skärmstorlek. 

JS: 


BREAKING POINTS: 
Anpassade först min hemsida efter en mobilanpassad skärm storlek. Sedan använde jag mediaquerys för att anpassa sidan successivt 
efter större skärmar. Huvudsakliga ändringarna skriver jag som punkter här under:

- 650px och större
    * Tjänster-listan hamnar i rad istället, med hjälp av flex box. 
- 767px och större 
    * Här gjorde jag om "Kontakt sektionen" till flexbox. 
- 1024px 
    * Här minskade jag "width:en" på hela min sida så den endast tar opp 80% av sidan och all text alltså trycks lite innåt. 
    * Här la jag även "Om oss- listan" bredvid varandra istället, med hjälp av flexbox. 
- 1600px
    * Här har jag endast ändrat bildstorlek en aning på bildera i tjänster-listan