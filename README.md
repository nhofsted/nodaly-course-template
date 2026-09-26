# Nodaly-cursussjabloon

Een kleine voorbeeldcursus in het [Nodaly](https://nodaly.be)-formaat om je eigen cursus mee te beginnen:
één les met een theorie-item, een `function`-oefening en een `io`-oefening.

## Gebruiken

1. Klik op **Use this template** om een eigen repository te maken (openbaar of privé).
2. Pas `course.json` en de lessen in `lessons/` aan.
3. Importeer de repository in Nodaly via **Cursussen → Importeren uit GitHub**. Voor een privé-repository koppel je eerst
   GitHub en geef je de Nodaly-app toegang.
4. Na elke wijziging: **Synchroniseren** in Nodaly maakt een nieuwe versie.

## Structuur

```
course.json                      titel en lessen van de cursus
lessons/lussen/exercises.json    de onderdelen van de les, in volgorde
lessons/lussen/tellen/           opdracht, startcode en oplossing van één oefening
```

Het volledige formaat (soorten oefeningen, tests, teksten, afbeeldingen) staat in de handleiding voor leerkrachten in
Nodaly, onder *Handleiding → Het cursusformaat*.

> Voorbeeldoplossingen (`solution`/`solutionFile`) krijgen leerlingen in Nodaly nooit te zien, maar in een **openbare**
> repository zijn ze voor iedereen leesbaar.
