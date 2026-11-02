# Lietuviški MyBible moduliai

Lietuviškų Biblijų, komentarų ir kitų „MyBible“ modulių saugykla.

## Įdiegimas per papildomą registrą

„MyBible“, skirtoje „Android“ (5.5.0 ar naujesnėje), atidarykite **Modules → Extra module registries** ir pridėkite šią nuorodą:

```text
https://raw.githubusercontent.com/kiritoshiro/mybible-lt-modules/main/mybible-lt.registry.json
```

Grįžkite į modulių sąrašą, pasirinkite lietuvių kalbą ir atsisiųskite norimus modulius. Nustatymuose galite įjungti automatinį modulių atnaujinimą.

## Kvanto Biblija

Atsisiųskite **abu** modulius:

- **Kvanto Biblija (ST ir NT)** – Biblijos tekstas ir skyrių antraštės.
- **Kvanto Biblija – išnašos ir kryžminės nuorodos** – su tekstu susietos išnašos.

Abiejų modulių pagrindinis pavadinimas turi likti `Kvanto`, kad veiktų išnašų sąsaja. Tai išnašų modulis, o ne savarankiškas aiškinamasis komentaras.

Tekstas perkeltas iš „Kvanto ST.pdf“ ir „Kvanto NT.pdf“, išlaikant senąją rašybą. Eilučių numeracija kai kur skiriasi nuo kitų vertimų. Šaltinio ypatumai ir perkėlimo pataisos aprašyti pačiame Biblijos modulyje.

## A. Jurėno vertimas

Atsisiųskite **abu** modulius:

- **A. Jurėno vertimas (ST ir NT)** – Biblijos tekstas ir antraštės.
- **A. Jurėno vertimas – išnašos** – su tekstu susietos išnašos.

Abiejų modulių pagrindinis pavadinimas turi likti `Jurenas`, kad veiktų išnašų sąsaja. Eilučių numeracija kai kur skiriasi nuo kitų vertimų. Moduliuose išsaugota pirminė naudojimo teisių informacija.

## Rankinis įdiegimas

Iš [Biblijos archyvo](modules/bibles/Kvanto.zip) ir [išnašų archyvo](modules/commentaries/Kvanto.commentaries.zip) išskleiskite abu `.SQLite3` failus į „MyBible“ duomenų aplanką telefone. Iš naujo paleiskite programėlę.

Jurėno vertimui naudokite [Jurėno Biblijos archyvą](modules/bibles/Jurenas.zip) ir [Jurėno išnašų archyvą](modules/commentaries/Jurenas.commentaries.zip).

## Kitų modulių pridėjimas ir atnaujinimas

1. Į atitinkamą `modules/` aplanką įkelkite ZIP archyvą, kurio šaknyje yra modulio `.SQLite3` failas.
2. Į `mybible-lt.registry.json` sąrašą `modules` pridėkite modulio aprašą ir tiesioginį atsisiuntimo adresą.
3. Atnaujindami esamą modulį pakeiskite jo archyvą ir padidinkite `update_date` datą; pakeitimus aprašykite `update_info` lauke.

Registro nuoroda išlieka ta pati, todėl naudotojams jos pridėti iš naujo nereikia.

Formato šaltinis: [oficiali MyBible papildomų registrų instrukcija](https://mybible.zone/android/extra-registries/).
