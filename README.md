# Yhdistyksen logo

Logo on jatkokehitelmä European Bitcoiners logosta, josta lisää credits.md tiedostossa.

Tämän virallisen logon lisäksi epävirallisemmissa yhteyksissä voi alla olevien 
värien, fonttien yms. puitteissa käyttää muitakin tekstejä, kuten yhdistyksen 
nimi pelkästään suomeksi, pelkästään englanniksi tai ilman perustamislohkoa.

Myös latinankielistä tekstiä on ehdotettu: 
 "Societas Bitcoin Finniae. Vires in numeris. Codex 783065".

## Värit

| Väri      | RGB     |RGB desimaali| Selite                                      |
|-----------|---------|-------------|---------------------------------------------|
| Sininen   | #002f6c |    0,47,108 | Suomen lipun sininen                        |
| Oranssi   | #f7931a |  247,147,26 | Bitcoin-logo                                |
| Valkoinen | #fafafa | 250,250,250 | Ei täysin valkoinen. Helpottaa painatuksia. |

Sinisen ympyrän ulkopuoli on läpinäkyvä.

## Mittasuhteet

Ympyröiden halkaisijat ja mitat 125 mm avatarille.
- blead             125mm
- sininen ympyrä   	100mm
- tekstin ulkoreuna  91mm 
- tekstin sisäreuna  82mm
- valkoinen ympyrä   73mm

SVG-master on 125 mm x 125 mm, jossa piirros on 100mm x 100mm.

## Fontti

Ubuntu, bold - lähde: https://github.com/daltonmaag/ubuntu/releases/tag/v0.83

## Tekstin muotoilu

Tekstien fonttik koko on 18px

"Suomen Bitcoin-yhdistys ry  •  Finnish Bitcoin association" -tekstin 
char spacing 1,75px ja word spacing 0,00px

"•  Est. 783065  •"-tekstin 
char spacing 2,00px ja word spacing 0,50px

Tekstin erottimet ovat 2x space ja "Bullet"-merkki (U+2022), joka kirjoitetaan Alt+0149.

## Bitcoin-logo

Otettu käyttöön Bitcoin Design Communityn B-kirjain (bitcoin-symbol.svg), sivulta
https://bitcoin.design/guide/getting-started/visual-language/

Permalink:

https://github.com/bitcoin-yhdistys/Bitcoin-and-Lightning-Network-logos-and-icons/blob/a171f054702408b4e4018304ee5729339d6172f0/icon/bitcoin-btc-icon_inverted.svg

# ./source kansio

Kansiossa on Inkscape -ohjelmalla tehty sby-fba-master.svg.
Alikansiosta work löytyy eri tasoiset master-versiot tulevaisuuden tarpeisiin.

Tiedostot work kansiossa ovat
-fonts          fontteja käyttävä versio, tulevaisuuden muokkauksien source, joka ei näy oikein selaimissa as of 20240329
-paths          fontit muutettu paths-vektorimuotoon
-paths-plain    fontit muutettu paths-vektorimuotoon, ja talletettu muodossa Inkscape-plain.svg joka on MASTER-VERSIO

## SVG- ja PDF-tiedostot sekä JPG- ja PNG-tiedostojen luonti

Alikansioissa pdf ja svg ovat käyttövalmiit SVG- ja PDF-vektoritiedostot. 

/svg kansion svg-tiedosto on kopio source-alikansion alla olevasta master-tiedostosta.

/pdf ja /png kansioiden tiedostot on luotu svg-tiedostosta Inkscape sovelluksella.

Kun haluat luoda muita formaatteja, se esimerkiksi onnistuu avaamalla master SVG-tiedosto 
SVG-editorilla muokattavaksi. Sitten käytä editorin export-toimintoa muiden tiedostoformaattien 
luomiseen.

## Historia 

2024 @tlindi
Luotu uudelleen tyhjästä Inkscape -ohjelmistolla.
Muutoksena alkuperäiseen on vain kirjainten välien tasaukset.
2023 @ottomagic
Alkuperäinen logo tehty Libre Office Draw -ohjelmistolla