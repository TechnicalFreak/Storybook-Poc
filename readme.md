# POC Storybook für Css-Doku
## Wichtige Punkte
- Package.json-Script "start-live-convertion-scss-to-css" -> Sorgt bei Änderungen einer scss-Datei dafür, dass die Ziel-Css-Datei ständig aktualisiert wird
- .storybook/preview.js -> import "../public/css/main.css"; bewirkt, einen regelmäßigen Refresh der gestarteten Storybook-Homepage bei Änderungen am css
- Ordner /public/css muss angelegt werden, damit die main.css-Datei in diesen Ordner geschrieben werden kann. In .storybook/preview.js wird auf diesen Speicherort verwiesen
- Ordner /scss ist der Ordner in dem die Styles bearbeitet werden

## Ziel
Es soll geprüft werden, ob Storybook geeignet ist, eine reine css-Doku bereitzustellen.

## GetStarted
npm run start
