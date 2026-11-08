# MyBible moduliai

Lietuviškų Biblijų, lietuviškų ir angliškų komentarų bei kitų „MyBible“ modulių saugykla.

## Įdiegimas per papildomą registrą

„MyBible“, skirtoje „Android“ (5.5.0 ar naujesnėje), atidarykite **Modules → Extra module registries** ir pridėkite šią nuorodą:

```text
https://raw.githubusercontent.com/kiritoshiro/mybible-lt-modules/main/mybible-lt.registry.json
```

Grįžkite į modulių sąrašą, pasirinkite lietuvių kalbą ir atsisiųskite norimus modulius. Nustatymuose galite įjungti automatinį modulių atnaujinimą.

## Kvanto Biblija (1908)

Atsisiųskite **abu** modulius:

- **Kvanto Biblija (1908)** – Biblijos tekstas ir skyrių antraštės.
- **Kvanto Biblija (1908) – išnašos** – su tekstu susietos išnašos ir kryžminės nuorodos.

Abiejų modulių pagrindinis pavadinimas turi likti `Kvanto`, kad veiktų išnašų sąsaja. Tai išnašų modulis, o ne savarankiškas aiškinamasis komentaras.

1908 m., Berlynas — devintasis spausdinimas. Modulio informacija pateikiama dabartine lietuvių kalba. Abiejų modulių „Apie“ pirmiausia pateiktos leidimo datos, antroje vietoje — vertimo šaltiniai ir rankraščiai. Tai 1735 m. kolektyvinio vertimo tradicijos vėlesnis leidimas; pradinio vertimo šaltiniai — Liuterio vokiškoji Biblija ir Bretkūno lietuviškas rankraštis. Bibliografijoje 1908 m. redaktoriumi nurodomas Vilius Gaigalaitis. Išlaikyta istorinio leidimo kalba ir senoji rašyba; eilučių numeracija kai kur skiriasi nuo kitų vertimų. Perkėlimo patikros saugomos vietinėse ataskaitose.

## Algirdo Jurėno vertimas (2000)

Atsisiųskite **abu** modulius:

- **Algirdo Jurėno vertimas (2000)** – Biblijos tekstas ir antraštės.
- **Algirdo Jurėno vertimas (2000) – išnašos** – su tekstu susietos išnašos.

Abiejų modulių pagrindinis pavadinimas turi likti `Jurenas`, kad veiktų išnašų sąsaja. Eilučių numeracija kai kur skiriasi nuo kitų vertimų. Moduliuose išsaugota pirminė naudojimo teisių informacija.

2000 m. — pirmasis visos Biblijos vertimo leidimas (Duncanville: World Wide Printing). Modulio skiltis „Apie“ pradedama šia leidimo data, antroje vietoje pateikiami vertimo šaltiniai ir rankraščiai. Nurodyta, kad Senąjį Testamentą prof. dr. Algirdas Jurėnas vertė iš hebrajų ir aramėjų, Naująjį — iš graikų kalbos, ir pateikta ankstesnių leidimų istorija.

## Juozapo Skvirecko vertimas (1947, 1955–1958)

- **Juozapo Skvirecko vertimas (1947, 1955–1958)** (`Skvireckas`) — visa Biblija, 73 knygos, įskaitant deuterokanonines knygas. [Biblijos archyvas](modules/bibles/Skvireckas.zip).
- **Juozapo Skvirecko komentarai (1947, 1955–1958)** (`Skvireckas-K`) — 12 651 įrašas. Ši versija pakeičia ankstesnį tik NT komentarų modulį. [Komentarų archyvas](modules/commentaries/Skvireckas-K.commentaries.zip).

1947 m. — NT IV laida, Stuttgart: Lux; 1955 ir 1958 m. — ST II laidos I ir II tomai, Roma. Abiejų modulių „Apie“ pradedamas šiomis leidimų datomis, antroje vietoje pateikiami vertimo šaltiniai ir rankraščiai. Vertė ir komentarus parašė Kauno arkivyskupas metropolitas Juozapas Jonas Skvireckas. Vertimo pagrindas — lotyniškoji Vulgata.

2026-11-08 abu moduliai patikrinti pagal skenuotą leidinį: ištaisytos teksto atpažinimo klaidos, paraščių nuorodų ir eilučių numerių likučiai, eilučių ribos ir antraštės (taip pat psalmių antraštės), komentarų pastabos priskirtos tinkamoms eilutėms. Senoviniai žodžių variantai palikti taip, kaip išspausdinti leidinyje. Tuščios eilutės paliktos ten, kur leidinys eilutės numerio nespausdina. Komentarų lange pasirinkite **Skvireckas-K**.

## Brolio Teofilio vertimas: Naujasis Testamentas (2023)

- **Brolio Teofilio vertimas: Naujasis Testamentas (2023)** (`Teofilis`) — Naujasis Testamentas, 27 knygos, 7 957 eilutės. Modulio įvade pateiktas vertėjo žodis skaitytojui. [Biblijos archyvas](modules/bibles/Teofilis.zip).

2023 m. — trečiasis, pataisytas leidimas, išleido Liutauras Leščinskas (ISBN 978-609-8322-08-8). Modulio „Apie“ pradedamas šia leidimo data, antroje vietoje nurodytas vertimo šaltinis — graikiškasis *Textus Receptus*, 1550 m. Stephanus leidimas. Eilučių numeracija atitinka šį tekstą (pvz., 3 Jn turi 14 eilučių), todėl kai kur skiriasi nuo kitų vertimų. Leidinys platinamas nemokamai.

## Rankinis įdiegimas

Iš [Biblijos archyvo](modules/bibles/Kvanto.zip) ir [išnašų archyvo](modules/commentaries/Kvanto.commentaries.zip) išskleiskite abu `.SQLite3` failus į „MyBible“ duomenų aplanką telefone. Iš naujo paleiskite programėlę.

Jurėno vertimui naudokite [Jurėno Biblijos archyvą](modules/bibles/Jurenas.zip) ir [Jurėno išnašų archyvą](modules/commentaries/Jurenas.commentaries.zip).

## Savarankiški komentarai

| Modulis | Kalba | Apimtis | Atsisiuntimas |
| --- | --- | --- | --- |
| ABC | Anglų | Andrews Bible Commentary: Senasis ir Naujasis Testamentas, 66 knygos | [ABC.commentaries.zip](modules/commentaries/ABC.commentaries.zip) |
| SDABC | Anglų | SDA Bible Commentary, red. F. D. Nichol: 66 knygos | [SDABC.commentaries.zip](modules/commentaries/SDABC.commentaries.zip) |
| SDAIBC | Anglų | SDA International Bible Commentary: Pradžios knyga, J. Doukhan | [SDAIBC.commentaries.zip](modules/commentaries/SDAIBC.commentaries.zip) |
| Skvireckas-K | Lietuvių | J. Skvirecko Senojo ir Naujojo Testamento komentarai | [Skvireckas-K.commentaries.zip](modules/commentaries/Skvireckas-K.commentaries.zip) |

Tai savarankiški komentarų moduliai, kuriuos galima pasirinkti komentarų lange su skirtingais Biblijos vertimais. ABC, SDABC ir SDAIBC ieškokite **angliškų komentarų**, o Skvireckas-K – **lietuviškų komentarų** sąraše. Jei anglų kalba paslėpta, pasirinkite visų kalbų rodymą ir išvalykite paieškos bei modulių būsenos filtrus.

Archyvuose pateikti naudotojo perduoti moduliai, jų tekstas nekeistas. SQLite vientisumas ir archyvų atitikimas originalams patikrinti; tai nėra viso turinio ar kiekvienos nuorodos teisingumo patvirtinimas. OCR tekstuose gali būti atpažinimo klaidų; vietinėje SDAIBC turinio patikroje taip pat pažymėti priskyrimo ir teksto atskyrimo neatitikimai. Naudojimo teisių pastabos išsaugotos pačiuose moduliuose.

SDABC yra atskiras Nichol komentaras; SDAIBC – J. Doukhan Pradžios knygos komentaras. Įkeltas SDABC failas skiriasi nuo ankstesnės vietinės patikros tikrintos versijos, todėl senasis auditas nepatvirtina šio failo turinio teisingumo.

Rankiniam įdiegimui iš komentarų archyvo išskleiskite `.commentaries.SQLite3` failą į „MyBible“ duomenų aplanką telefone ir iš naujo paleiskite programėlę. „Android“ taip pat galima naudoti failų programos **Open with → MyBible** veiksmą ZIP archyvui importuoti.

## Kitų modulių pridėjimas ir atnaujinimas

1. Į atitinkamą `modules/` aplanką įkelkite ZIP archyvą, kurio šaknyje yra modulio `.SQLite3` failas.
2. Į `mybible-lt.registry.json` sąrašą `modules` pridėkite modulio aprašą ir tiesioginį atsisiuntimo adresą.
3. Atnaujindami esamą modulį pakeiskite jo archyvą ir padidinkite `update_date` datą; pakeitimus aprašykite `update_info` lauke.

Registro nuoroda išlieka ta pati, todėl naudotojams jos pridėti iš naujo nereikia.

Formato šaltinis: [oficiali MyBible papildomų registrų instrukcija](https://mybible.zone/android/extra-registries/).
