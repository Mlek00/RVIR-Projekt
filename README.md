# Where’s the fish

Where’s the fish je načrtovana mobilna aplikacija za podvodne ribiče. Omogočala bo beleženje ribolovov na posameznih mestih in pregled, kako uspešno je bilo mesto v različnih letnih časih. Projekt je trenutno v fazi zasnove; izvorna koda aplikacije še ni dodana.

## Kaj bo omogočala prva različica

- Prijavo in registracijo z e-pošto ter geslom.
- Dodajanje mesta z lokacijo, imenom, opisom in fotografijami.
- Beleženje ribolova z datumom, vrstami rib, ulovom, fotografijami ter podatki o času v vodi, potopih in terenu.
- Pregled lastnih mest v mreži in na zemljevidu ter podrobnosti posameznega mesta.
- Filtriranje po območju, letnem času in oceni ter navigacijo do izbranega mesta.
- Samodejni izračun statistike in ocene mesta iz zabeleženih ribolovov.
- Pregled, urejanje in brisanje lastnih zapisov.

Prva različica je **osebni ribiški dnevnik**: lokacije so zasebne in jih vidi njihov avtor. Deljenje mest z drugimi ribiči je predvideno za poznejšo različico.

## Predvidene tehnologije

Mobilni odjemalec bo zasnovan z **React Native, Expo in TypeScript**. Načrtovani so Expo Router, zemljevid v aplikaciji, lokacijske storitve telefona ter **Firebase Authentication, Cloud Firestore, Cloud Storage in Cloud Functions**. Izbiro Firebase SDK-ja je treba potrditi s kratkim preizkusom na napravi, ker sta delo brez povezave in nalaganje fotografij bistveni zahtevi. Podrobnosti so v [projektni specifikaciji](dokumentacija/projektna-specifikacija.docx).

## Dokumentacija

- [Pregled dokumentacije](dokumentacija/README.md)
- [Projektna specifikacija](dokumentacija/projektna-specifikacija.docx)

Načrt dela in naloge so v GitHubovem Kanbanu.

## Stanje repozitorija

V repozitoriju sta trenutno README in mapa `dokumentacija/`; aplikacija še ni implementirana. Predvidena struktura po začetku razvoja je `app/`, `components/`, `services/`, `hooks/`, `lib/` in `functions/`. Navodila za namestitev in zagon bodo dodana, ko bo ustvarjen Expo projekt.
