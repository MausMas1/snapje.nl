# Snap je website

Deze website is bewust gebouwd met eenvoudige, statische HTML, CSS en JavaScript. Daardoor kan de inhoud zonder buildstappen of frameworkkennis worden aangepast en is de site ook goed door AI-tools te onderhouden.

## Waar staat wat?

- `index.html` bevat alle teksten en secties van de homepage.
- `privacy.html` bevat het privacyreglement.
- `styles.css` bevat kleuren, typografie, responsive layout en animaties.
- `script.js` bevat alleen het mobiele menu en de scrollanimaties.
- `assets/photos/` bevat de originele foto's en het logo.
- `assets/generated/` bevat gegenereerde afbeeldingen.

## Veilig aanpassen met AI

Geef bij een volgende opdracht aan dat bestaande teksten, telefoonnummers en adressen niet zonder expliciete opdracht mogen worden gewijzigd. Laat na iedere wijziging minimaal controleren op 390 px (telefoon), 768 px (tablet), 1024 px (laptop) en 1440 px (desktop).

Nieuwe kaarten kunnen dezelfde classes gebruiken als bestaande kaarten. De scrollanimatie wordt automatisch toegepast op `.card`, `.feature`, `.section-head`, `.split-content` en relevante afbeeldingen. Er hoeft daarvoor geen extra JavaScript te worden toegevoegd.

## Publiceren

GitHub Pages publiceert de bestanden rechtstreeks uit deze repository. Commit en push wijzigingen naar de ingestelde Pages-branch om ze online te zetten.
