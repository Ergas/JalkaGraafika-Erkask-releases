# Versiooniuuenduste ajalugu

## [2.7.2] 09.10.2026
### Lisatud
- Uuenduste lehel saab nüüd vaadata kõigi rakenduse versioonide muudatusi.

## [2.7.1] 09.10.2026
### Lisatud
- Lisatud otseülekande lehele nupud kolme rakendusele reserveeritud vMix overlay sulgemiseks vMix-is seadistatud üleminekuefektiga.
### Muudetud
- Uuenduste menüülink on nüüd menüü viimane valik.
- Muudatuste logi kuvatakse uuenduste lehel vormindatult.
### Parandatud
- Määramata värava aega ei kuvata suure skoori väravalööjate loendis.
- Uuendatud Nuxti, XML-i parsija ja Electron Builderi sõltuvused.
- Määratud projektile toetatud Node.js-i versiooninõue.

## [2.7.0] 09.10.2026
### Lisatud
- Lisatud rakenduse uuenduste leht, kus kuvatakse uuenduse olek, allalaadimise edenemine ja GitHubi väljalaske muudatused.
- Rakenduse käivitamisel kuvatakse uue versiooni korral uuenduse teavitus.
- Uuenduse saab edasi lükata ja hiljem uuenduste lehelt paigaldada.
- Laiendatud testikomplekti ärikriitiliste otseülekande API-de, mängu oleku, vahetuste, vMix-i käskude, litsentsi oleku, allikate ja allalaadimiste katet.
- Lisatud testid vMix-i piiratud käskude autoriseerimisele ja käsupakettide järjekorra säilitamisele.
### Muudetud
- Uuendus laaditakse ja paigaldatakse rakenduse töötamise ajal; paigaldamine ei sõltu rakenduse või Windowsi sulgemisest.
- Aktiivse otseülekande ajal on uuenduste kontroll ja allalaadimine peatatud.
- Testikomplektis on nüüd 49 testi 12 testifailis ning litsentsiserveri päringud on jätkuvalt täielikult mock'itud.

## [2.6.0] 09.10.2026
### Lisatud
- Lisatud Vitest-il põhinev ühik-, integratsiooni- ja komponenditestide komplekt.
- Lisatud `npm test` ja `npm run test:watch` käsud testide käivitamiseks.
### Parandatud
- XML-ist puuduva kohtuniku ID väärtus säilitatakse `null`-ina, mitte väärtusena `0`.
- Kohandatud vMix-i sisendite nimed lahendatakse käskude töötlemisel õigesti.

## [2.5.4] 08.10.2026
### Lisatud
- Salvestatud mängudes ja avatud mängu vaates kuvatakse võistluse nimi.

## [2.5.3] 08.10.2026
### Lisatud
- Mängu mõlemale treenerile saab eraldi kaarte määrata ning nende kaardigraafikat vMix-is kuvada.
### Parandatud
- Mängu ja tiimi info saatmisel edastatakse vMix-i ainult esimese peatreeneri nimi.
- Mänguinfo mängijate ja treenerite nimede suurtähed ühtlustati üksikute mängija- ja treenerigraafikatega.
- Suure skoori lisainfo saadetakse teistes võistlustes nii `HALFTIME.Text` kui ka `INFO-TXT.Text` väljale.

## [2.5.2] 08.10.2026
### Muudetud
- vMix-i käsupakettide saatmine on piiratud 100 käsuni ja maksimaalselt kaheksa samaaegse päringuni, et vältida juhuslikke koormuspiike.
- Otseülekande kasutus- ja vMix-i päringute töökindlust parandatud.
### Parandatud
- Välditud kattuvate otseülekande südamelöökide saatmine.
- Mänguandmete allikapäringutele lisatud 15-sekundiline ajalõpp.

## [2.5.1] 08.10.2026
### Muudetud
- Aktiivse otseülekandega mängu ei saa kustutada; mängude hulgikustutamisel säilitatakse aktiivsed mängud.
- Väravat saab tühistada ainult tegevuste loendist, mitte skoori „-1” nupuga.
### Parandatud
- Neljanda kohtuniku nimi saadetakse Premium liiga vMix-i graafikas õigele väljale.
- Salvestatud mängu avamisel kuvatakse nähtav laadimisolek navigeerimise ajal.

## [2.5.0] 07.10.2026
### Lisatud
- Lisatud eraldi leht Premium Liiga ja teiste võistluste vMix-i sisendite nimede muutmiseks ning profiilipõhiseks lähtestamiseks.
- Mängu avamisel kuvatakse laadimisindikaator.
### Muudetud
- Tegevuste ja väravalööjate aeg kuvab nüüd aktiivset mänguminutit.
### Parandatud
- vMix-i päringud kasutavad sisendite nimesid ilma `.gtzip` laiendita ning arvestavad muudetud nimedega.
- Parandatud alternatiivse vMix-i profiili sisendite ja intro-graafika nimede kasutamine.

## [2.4.6] 07.10.2026
### Lisatud
- Salvestatud mängudes ja avatud mängu vaates kuvatakse mängu kuupäev ja kellaaeg.
- Mänguinfo saatmisel saadetakse vMix-i mõlema meeskonna treeneri nimi ja info.
### Parandatud
- Mänguinfo osalise saatmise tõrge ei takista enam teiste vMix-i graafikaväljade uuendamist.
- Alternatiivse vMix-i profiili suure skoori vaates kuvatakse nüüd ka meeskondade logod.

## [2.4.5] 04.10.2026
### Lisatud
- Vahetuse vormis saab nüüd lisada ja korraga kinnitada mitu mängijate vahetust.

## [2.4.4] 04.10.2026
### Parandatud
- Premium liiga algkoosseisu mängijad saadetakse nüüd õigete vMix-i väljadega.

## [2.4.3] 04.10.2026
### Muudetud
- Uue litsentsi aktiveerimisel deaktiveeritakse seadme varasem litsents.

## [2.4.2] 04.10.2026
### Muudetud
- Windowsi installer kuvab litsentsitingimused ja lisab LICENSE-faili installitud programmi kausta.
- Rakendus paigaldatakse nüüd kõigile kasutajatele Program Files-kausta.

## [2.4.1] 04.10.2026
### Lisatud
- Lisatud võimalus määrata meeskonnale käsitsi peatreener, kui allikas treeneri nime ei anna.
### Muudetud
- Mängude allikate päringuväljad kuvatakse ainult siis, kui valitud allikas neid vajab; implementeerimata allikad 5 ja 6 on peidetud.
- Lisatud vMix-i overlay-sisendite 1 kuni 8 tugi, sh algkoosseisu live-kuvamine overlayga 3.

## [2.4.0] 20.09.2026
### Lisatud
- Lisatud võistlusepõhised vMix-i profiilid premium liiga ja teiste võistluste jaoks.
- Lisatud algkoosseisude eelvaate ja live-nupud mõlemale meeskonnale.
### Muudetud
- Alternatiivse vMix-i profiili mänguinfo, meeskondade, kohtunike, värvide ja intro-graafika tugi.
- Tegevuste loend kuvab viimased sündmused esimesena.
- Kohtunike väljad kohanduvad kolme ja nelja ametniku korral.

## [2.3.3] 20.09.2026
### Parandatud
- Litsentsi andmete tuvastamine

## [2.3.2] 20.09.2026
### Lisatud
- Lisatud aktiivse litsentsi nime kuvamine litsentsi seadetes.

## [2.3.1] 20.09.2026
### Parandatud
- Parandatud Windowsi allalaadimise Save As dialoogi avamine.
- Parandatud allalaaditavate failide algse nime ja laiendi säilitamine.
- Lisatud edenemisriba ka Windowsi ja brauseri allalaadimise töövoogudele.

## [2.3.0] 20.09.2026
### Lisatud
- Lisatud litsentsiga seotud failide loend ja allalaadimise leht.
- Lisatud faili salvestuskoha valimine Save As dialoogi või brauseri failivalija kaudu.
- Lisatud allalaadimise edenemise protsent ja visuaalne edenemisriba, kui faili suurus on teada.
- Failid laaditakse voona alla ja salvestatakse kasutaja valitud asukohta, säilitades algse failinime ja laiendi.
- Allalaadimisnupp kuvab laadimise ajal animeeritud laadimisikooni.
### Muudetud
- Rakenduse jalus paikneb lühikestel lehtedel alati akna allservas.

## [2.2.5] 18.09.2026
### Muudetud
- Litsentsi valideerimisel saadetakse litsentsiserverile rakenduse praegune versioon.

## [2.2.4] 18.09.2026
### Muudetud
- Ühtlustatud Windowsi väljalaske installeri ja uuendusefailide nimed.

## [2.2.3] - 18.09.2026
### Lisatud
- Lisatud kasutajale nähtavad teavitused uuenduse saadavuse, allalaadimise edenemise ja lõpetamise kohta.

## [2.2.2] - 18.09.2026
### Lisatud
- Lisatud rakenduse jalusesse versiooninumber ja väljalaske kuupäev.

## [2.2.1] - 18.09.2026
### Lisatud
- Automaatsed uuendused rakendusele

## [2.2.0] - 18.09.2026
### Lisatud
- Lisatud dünaamiline pordivalik: rakendus alustab eelistatud pordist ja leiab vajadusel vaba pordi kuni pordini 4000.
- Lisatud suure skoori eelvaate ja live-režiimi juhtimine vMix-i `OverlayInput1` kaudu.
- Lisatud väravalööjate andmete saatmine ja kuvamine suure skoori `Page1` üleminekuga.
- Lisatud suure skoori `LISAINFO` presetid `VAHEAEG`, `LÕPPSEIS`, tühi väärtus ja kohandatud tekst.
- Lisatud mängijate ja treeneri tegevusmodaal vMix-i eelvaateks, live-kuvamiseks ja kaartide määramiseks.
- Lisatud muu klubi personali salvestamine, korduv valimine ning kaartide määramine nime ja tiitli alusel.
- Lisatud tegevuste nimekirja sisemine kerimine ja kogu lehe laadimise overlay-spinner.
### Muudetud
- Kaartide määramine mängijale või treenerile toimub tegevusmodaalist otse ilma eraldi kaardimodaalita.
- Suure skoori juhtimine paikneb mänguinfo tegevuste juures ning muu personali kaardid ei mõjuta mängijate punase kaardi tähiseid.
- Rakenduse põhikonteinerit laiendati suurematel ekraanidel.
### Parandatud
- Punase kaardi saanud mängijatele, treeneritele ja muule personalile ei saa uut kaarti määrata; kaardi tühistamisel muutuvad nad uuesti valitavaks.

## [2.1.3] - 16.09.2026
### Lisatud
- Kohtunike graafika otse vMix-i kuvamine

## [2.1.2] - 16.09.2026
### Lisatud
- Lisatud otseülekande alustamise ja lõpetamise seansid koos kasutusstatistika ja maksete arvestuseks vajaliku aruandlusega.
- Lisatud piiratud testrežiim koos eestikeelse hoiatuse, piirangute modali ja serveripoolse piirangute jõustamisega.
- Lisatud ühe aktiivse otseülekande piirang litsentsi kohta ning salvestatud mängude aktiivse otseülekande tähis.
### Muudetud
- Litsentsi aktiveeritud kasutaja saab otseülekande alustamisel täielikud funktsioonid ilma täiendava kasutajapoolse litsentsikontrollita.
- Piiratud režiimis peatatakse kümne minuti täitumisel rakenduse ja vMix-i mängukell ning vMix-i sünkroonitakse rakenduse skooriga.
- Aktiivse otseülekande konfliktiteated kuvatakse korrektselt eestikeelsete täpitähtedega.

## [2.1.1] - 16.09.2026
### Muudetud
- Eemaldatud kohalik sisselogimise süsteem ja kasutajate rollid.
- Eemaldatud administraatori kasutajate API; administraatori funktsioonid on piiratud kohaliku litsentsi kasutajaliidesega.

## [2.1.0] - 13.09.2026
### Lisatud
- Lisatud litsentsi aktiveerimine, kontrollimine, deaktiveerimine ja võrguühenduseta seitsmepäevane armuaeg.
- Lisatud litsentsi leht, kus kuvatakse litsentsi olek, pakett, kehtivusaeg ja viimase veebikontrolli aeg.
- Lisatud võimalus litsentsi vahetada ning selle arvuti aktiveering deaktiveerida.
- Lisatud arvuti ühekordse instantsi kontroll; teise käivitamise korral avatakse juba töötav rakendus.
- Lisatud rakenduse favicon, brauseri pealkiri ja Windowsi rakenduse ühtne nimi „JalkaGraafika ErKask“.
- Lisatud korrektne mitme suurusega Windowsi ICO-fail installerile ja rakendusele.
### Muudetud
- Litsentsita kasutajal on võimalik avada ainult litsentsi aktiveerimise vaade; rakenduse põhimenüü ja töövood avanevad pärast edukat aktiveerimist.
- Rakenduse avaleht kujundati ümber selgemaks töövoo, vMix-i sisendite ja programmiinfo ülevaateks.

## [2.0.1] - 13.09.2026
### Lisatud
- Lisatud kapteni määramine mängu ajal; kapteniks saab valida ainult väljakul oleva mängija.
- Lisatud väravate määramine mängijatele või määramata väravana.
- Lisatud penalti- ja omavärava tähised (`PEN`, `OV`).
- Lisatud väravalööjate saatmine vMix-i suurde skoorigraafikasse koos värava minutitega.
- Lisatud väravalööjate muutmine ning väravate, kaartide ja vahetuste mänguaja muutmine.
- Lisatud kohtunike info parserisse, kohtunike modal ja info saatmine vMix-i.
- Lisatud esimese ja teise väljakul saadud punase kaardi tähised väikese skoori graafikasse.
- Lisatud mängijate ja treenerite piltide kuvamine ning mängijate eelvaate- ja live-nupud.
- Lisatud mänguaja, lisaminutite ja lisaminutite graafika juhtimine.
- Lisatud meeskondade särgi- ja püksivärvide muutmine koos HEX-väärtustega.
- Lisatud vMix-i seadete leht IP-aadressi ja pordi salvestamiseks.
### Muudetud
- Mängusündmused kuvatakse nüüd mänguaja järgi ja aja muutmisel järjestatakse need automaatselt ümber.
- Mängijate juures kuvatakse väravate arv, väravaikoon, väravavahi (`VV`) ja kapteni (`K`) tähised.
- vMix-i saadetavates mängijanimedes kuvatakse `VV` ja `K` ning saatmisel antakse kasutajale tagasiside.
- Lisatud nuppude hover-, fookus- ja klõpsamisolekud ning vMix-i tegevuste tagasiside lehe ülaossa.
- Punase kaardi saanud mängijad eemaldatakse kaardi valikust; kaardi tühistamisel muutuvad nad uuesti valitavaks.
- Lühikesed meeskonnanimed jäävad tühjaks, kui väärtust ei ole; pikka meeskonnanime ei kasutata automaatselt asendusena.
### Parandatud
- Parandatud punaste kaartide graafika sünkroniseerimine esimese, teise ja tühistatud punase kaardi korral.
- Parandatud viga, mille tõttu vMix-i suurde skoorigraafikasse ei saadetud väravalööjate infot.

## [2.0.0] - 11.09.2026
---

## [1.0.3] - 02.06.2026
### Lisatud
- Skoori ja kella kontrollimise võimalus, mis võimaldab kasutajatel kontrollida mängu kulgu ja skoori reaalajas.
### Parandatud
- Parandatud viga, mille tõttu mängu info uuendamisel ei uuendatud kollaste ja punaste kaartide sisendite meeskondade nimesid ja logosid.
- Parandatud viga, mille tõttu sai olla korraga vaid üks salvestatud mäng.
- Parandatud viga, mis kuvas kohtunike graafikas valesid rolle.

## [1.0.2] - 01.06.2026
### Lisatud
- Versiooniuuenduste ajaloo lehekülg

## [1.0.1] - 31.05.2026
### Lisatud
- Lisatud süsteemi ikoon tegumireale, kui rakendus töötab, võimaldab rakendust avada ja sulgeda kiiresti.
- Lisatud Windowsi installi tugi, mis võimaldab kasutajatel hõlpsasti rakendust oma arvutisse installida ja kasutada.
- API integratsioon vMix API-ga, mis võimaldab sisestatud andmeid automaatselt vMix-i sisendite mallidesse sisestada.

## [1.0.0] - 24.05.2026
### Lisatud
- Esialgne versioon, mis võimaldab kasutajatel sisestada mängijate andmeid ja kuvada neid tabelina.