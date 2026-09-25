# No Man's Sky - Enhanced First Person Camera Mod
<p align="center"><img src="https://raw.githubusercontent.com/Legandy/EnhancedFirstPersonCamera/main/.site/icon.png" width="512" height="288">


## DOWNLOADS
[NexusMods](nm)


## BESCHREIBUNG
Dieser Mod passt die FOV-Werte (Fuß/Schiff) und die Multitool-Position so an, dass sie eher einer Standard-FPS-Ansicht entsprechen.

Ich wollte das gesamte First-Person-Erlebnis verbessern, um mehr Immersion zu schaffen, beispielsweise bei der Ansicht und beim Schussverhalten.
Da ich jedoch mit der Anpassung der Werte für das Schussverhalten (Rückstoß, Verwacklung) nicht zufrieden war, habe ich diese beiden Aspekte voneinander getrennt.
Das Sichtfeld des Spielers scheint nicht zu funktionieren, das des Schiffes hingegen schon. (Manuell in der Datei „TKGRAPHICSSETTINGS.MXML“ einstellen).


## Die verbesserte First-Person-Kamera (EXML & .lua):
Ich empfehle dringend, die .lua-Datei zu nutzen, um den Mod an eure Vorlieben anzupassen, aber bei Bedarf kann ich auch eine weitere Variante erstellen.


### ÄNDERUNGEN IN:
### GCCAMERAGLOBALS.GLOBAL.MBIN:
- FOV-Einstellungen für Charakter und Schiff
- Keine Glättung der freien Blickrichtung in Mechs und Schiffen
- Ich habe Exocraft ausgeschlossen, da es durch viele Overhaul-Mods ersetzt wird, aber die Einstellungen sind in der .lua enthalten

### GCGAMEPLAYGLOBALS.GLOBAL.MBIN:
- Multitool- und Stabposition
- Ich habe die Stabposition nicht angepasst, da ich keinen Stab besitze, aber die Einstellungen sind in der .lua-Datei enthalten


## Verbessertes Gunplay (nur .lua):
- Ich glaube, ich habe die richtigen Eigenschaften gefunden, habe aber nicht alles getestet.
- Ich habe viele Werte ausprobiert, war aber nicht zufrieden, daher habe ich die Idee vorerst aufgegeben.
- Falls ihr selbst an den Einstellungen herumprobieren wollt, habe ich die .lua-Datei beigefügt. Wenn ihr gute Einstellungen findet, teilt sie bitte mit mir.

### ÄNDERUNGEN IN:
### GCCAMERAGLOBALS.GLOBAL.MBIN:
- Intensität des Multitools/der Waffenvibration
- GCPLAYERGLOBALS.GLOBAL.MBIN:
- Stärkerer Zoom des Zielfernrohrs


## KONFLIKTE:
- ✅ Patch-Mod – Funktioniert wahrscheinlich gut mit anderen Patch- und Ersatz-Mods

## FEHLER:
- Das Sichtfeld des Spielers scheint nicht zu greifen, das Sichtfeld des Raumschiffs funktioniert jedoch. Stellt es manuell in der Datei „TKGRAPHICSSETTINGS.MXML“ ein, die sich in „No Man’s Sky\Binaries\SETTINGS\“ befindet

## INSTALLATION:
- Vortex sollte funktionieren
- Für die manuelle Installation entpacke den Inhalt der Datei „EnhancedFirstpersonCamera.zip“ in deinen Ordner „No Man's Sky\GAMEDATA\MODS“
- [Weitere Details hier][mg]

## BESONDERER DANK AN:
- [AMUMSS][amuss-ref] dafür, dass er das Modding ziemlich einfach gemacht hat


[nm]: https://www.nexusmods.com/nomanssky/mods/3901
[mg]: https://docs.google.com/document/d/18k5VfvzLXbpBrAGGO7LK30c2Ta_lWQ5F5YgEpuwKZ6M/edit?tab=t.0#heading=h.vm4bcr5uj28i
[amuss-ref]: https://www.nexusmods.com/nomanssky/mods/957