# Nodaly-cursussjabloon

Een kleine voorbeeldcursus in het [Nodaly](https://nodaly.be)-formaat om je eigen cursus mee te beginnen. Ze toont
alles wat het formaat kan: theorie met afbeeldingen, wiskunde en kaders; `function`- en `io`-oefeningen met tips,
verborgen tests, `setup` en een test op de code zelf; meerkeuzevragen; puzzels met codeblokken; en spel-levels met elke
soort doel. Neem wat je nodig hebt en verwijder de rest.

## Gebruiken

1. Klik op **Use this template** om een eigen repository te maken (openbaar of privé).
2. Pas `course.json` en de lessen in `lessons/` aan.
3. Importeer de repository in Nodaly via **Cursussen → Importeren uit GitHub**. Voor een privé-repository koppel je eerst
   GitHub en geef je de Nodaly-app toegang.
4. Na elke wijziging: **Synchroniseren** in Nodaly maakt een nieuwe versie.

## Structuur

```
course.json                         titel, hoofdstukken en lessen van de cursus
chapters/                           de inleiding van elk hoofdstuk
lessons/lussen/exercises.json       de onderdelen van een les, in volgorde
lessons/lussen/tellen/              opdracht, startcode en oplossing van één oefening
lessons/02-functies/                een les in een eigen map ("path" in course.json), met een afbeelding in media/
lessons/spel/, lessons/grotten/     spel-levels
```

Wat elk onderdeel toont, staat in de handleiding voor leerkrachten in Nodaly, onder *Handleiding → Voorbeelden*.
Het volledige formaat (soorten oefeningen, tests, teksten, afbeeldingen) staat in de handleiding voor leerkrachten in
Nodaly, onder *Handleiding → Het cursusformaat*.

> Voorbeeldoplossingen (`solution`/`solutionFile`) krijgen leerlingen in Nodaly nooit te zien, maar in een **openbare**
> repository zijn ze voor iedereen leesbaar.

## Licentie

Dit sjabloon staat onder [CC0 1.0](LICENSE) (publiek domein): je mag het zonder voorwaarden kopiëren, aanpassen en
gebruiken, ook zonder bronvermelding. Voor je eigen cursus kies je zelf een licentie: vervang dan `LICENSE` en het veld
`license` in `course.json` (bv. `CC BY-SA 4.0`).
