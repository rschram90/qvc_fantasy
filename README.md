# QVC Manager Android starter

Jetpack Compose + Room + MVVM + Hilt starter-codebase voor een voetbalmanager-game rond QVC.

## Inbegrepen
- Dashboard met budget, teamrating, seizoen/ronde en record
- QVC spelers in Room seed data
- Tegenstanders + simpele competitie
- Transfermarkt met koop/verkooplogica
- Training met leeftijd/potential groei
- Match simulatie met teamrating, random factor en thuisvoordeel
- Challenge systeem met coins en ICON unlocks
- Bottom navigation naar dashboard, selectie, transfermarkt, competitie en challenges

## Structuur
- `data/` Room entities, dao's, repository implementatie
- `domain/` modellen, repository contract, use cases
- `ui/` navigation, screens, viewmodel, theme
- `di/` Hilt modules

## Opmerkingen
- Dit is een echte starter-codebase en bedoeld als basis om verder uit te bouwen.
- De league table en match engine zijn bewust simpel gehouden.
- ICON rewards worden direct owned gezet zodra challenge compleet is.
