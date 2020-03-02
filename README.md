# mask-map

日本マスクマップ Japan Mask Map
https://www.japanmaskmap.com

Forked from https://github.com/kiang/pharmacies

## What
Japan mask map silimar to Taiwan mask map.
Unfortunately Japanese government doesn't have API for mask.

I tried to use Twitter API for integration instead.
However, API application was rejected.
According to them, this use case is the violation of their terms.

## Doc
`/static` is the directory root for host.
Currently Netlify is used for integration.

OpenLayers is used for map visualization.
No backened is required. It simply displays `/json/points.json`

## TODO

Add batch script to update `/json/points.json`

## LICENSE
MIT
