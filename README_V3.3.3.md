# PR Explorer Madeira · V3.3.3

Stage 1 Patch: synchronisiertes PR-Karussell-Bottom-Sheet.

## Geändert

- Karussell-Reihenfolge bleibt stabil; aktive PR wird nicht mehr nach vorne sortiert.
- `scrollIntoView()` läuft nur noch bei externer Auswahl aus Pin/Journal, nicht mehr bei jedem PR-Wechsel.
- Aktive PR wird automatisch durch die horizontal zentrierte Karussell-Kachel bestimmt.
- Kein zusätzlicher Tap auf die Kachel erforderlich.
- Kachel-Tap selbst löst keinen ungewollten PR-Wechsel und kein Springen mehr aus.
- Bottom-Sheet-Zustände für Karussell: `peek`, `card`, `half`, `full`.
- Peek-Leiste zeigt aktive PR-Kurzinfo.
- Sheet-Höhe bleibt global erhalten, wenn horizontal zum nächsten PR gewechselt wird.
- iPhone-Safe-Area unten für Karussell und Detail-Sheet nachgezogen.

## Nicht Bestandteil dieses Patches

- Transparenzregler
- GPX/KML-Farb- und Kontureinstellungen
- nachgezeichneter Hiking-Layer
- Pin-Symbolauswahl
- POI-Clustering
