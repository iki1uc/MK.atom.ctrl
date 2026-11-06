# muss.weg

**Wagnisschale – ROOT zuerst – 3 → 9**

Brain ist weg. Nur noch Root + core + hdf + stage.

## ROOT – 3 – muss laufen
- `index.html` – Stage – Einstieg
- `404.html` – Fallback + recall `?node=`
- `README.md` – das hier

## CORE – Motor – 8 Dateien
- `core/NC_figur.js`
- `core/NC_kraft.js`
- `core/NC_space.js`
- `core/NC_time.js`
- `core/OS_CORE.js`
- `core/axiom.map.js`
- `core/coord.js`
- `core/vec.js`

## HDF / MODULES – Inhalt
- `hdf/modules/dreieck/dreieck.js`
- `hdf/modules/respo/respo.js`

## STAGE – Bühne
- `stage/index.html` – Master Kopie
- `stage/router.js`
- `stage/resolver.js`

## BEILÄUFER
- `bei.lauefer.js` – läuft mit, lädt alles, checkt alles
- `m.md` – Notizen
- `muss.ready` – Ready Marker

## Start
1. `index.html` aufmachen
2. `bei.lauefer.js` läuft mit
3. 404 testen – muss recall machen

## Regel
- Kein brain/ mehr
- Kein 404.html/ Ordner mehr – nur 1 Datei
- Keine Kopie – jede Datei nur 1x
- Was stört → schmelzen / verdampfen
