# Kom i gang med micro:bit

##Steg 0 YEAH @showdialog
Før vi begynner, må vi koble sammen PCen og micro:biten.

![Bilde av en micro:bit koblet til](https://d14xnrffmhx4ml.cloudfront.net/1661434482/smarthus-veiledning-microbit-for-seg-selv.png)

Hent micro:bit og USB-ledning og plugg ting sammen.

##Steg 1 prokkprik @showdialog
Og så må vi koble nettleseren til micro:biten, så vi kan laste ned programmene direkte

![Bilde av USB-connect device](https://d14xnrffmhx4ml.cloudfront.net/1661434772/smarthus-veiledning-usbconnect.png)

##Steg 000 

Trykk på det tre prikkene ved siden av "Last ned" og så "Connect Device". Følg informasjonen på skjermen for å koble til.

Hvis ikonet på "Last ned" ser ut som et micro:bit-ansikt i stedet for et papir-ark med en pil, har dere gjort det riktig.

Trykk på "Neste" for å fortsette.

##Steg 0 YEAH

Lag et lite program med blokker fra Basis og Inndata.

Trykk på "Last ned"-knappen i venstre hjørne for å teste.


##Steg 2232 WOO
Godt jobbet! Trykk på Slutt/Finish for å avslutte veiledningen og få tilgang til resten av blokkene i MakeCode.

Vent på klarsignal fra formidleren før dere går for å hente utstyr.

```ghost
input.onButtonPressed(Button.A, function () {
    basic.pause(100)
})
input.onGesture(Gesture.Shake, function () {
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
    basic.showIcon(IconNames.Heart)
})
input.onSound(DetectedSound.Loud, function () {
    basic.showString("Hello!")
})
basic.forever(function () {
	
})

```


> Åpne denne siden på [https://broccolisurprise.github.io/microbit---kom-i-gang/](https://broccolisurprise.github.io/microbit---kom-i-gang/)

## Bruk som utvidelse

Dette kodeområdet kan bli lagt til som en **utvidelse** i MakeCode.

* åpne [https://makecode.microbit.org/](https://makecode.microbit.org/)
* klikk på **Nytt prosjekt**
* klikk på **Utvidelser** i menyen under tannhjulet
* søk etter **https://github.com/broccolisurprise/microbit---kom-i-gang** og importér

## Rediger dette prosjektet ![Bygg statusmerke](https://github.com/broccolisurprise/microbit---kom-i-gang/workflows/MakeCode/badge.svg)

For å redigere dette kodeområdet i MakeCode.

* åpne [https://makecode.microbit.org/](https://makecode.microbit.org/)
* klikk på **Importer** og så på **Importér URL**
* lim inn **https://github.com/broccolisurprise/microbit---kom-i-gang** og klikk på importér

## Forhåndsvisning av blokker

Dette bildet viser blokk-koden fra den siste oppdateringen i hovedgrenen.
Dette bildet kan ta noen minutter å oppdatere.

![En opptegnet visning av blokkene](https://github.com/broccolisurprise/microbit---kom-i-gang/raw/master/.github/makecode/blocks.png)

#### Metadata (brukes for søk, visualisering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
