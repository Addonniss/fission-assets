# Stremio add-ons used by collection imports

These are **installation sources**, not hosted copies of add-on manifests. Do not install raw GitHub JSON files as Stremio add-ons: catalog requests are relative to the installed manifest URL and must reach the original add-on server.

## Streaming Catalogs
- Add-on ID: `pw.ers.netflix-catalog`
- Live manifest URL (check reachability before installing): `https://7a82163c306e-stremio-netflix-catalog-addon.baby-beamup.club/manifest.json`
- Configure: `https://7a82163c306e-stremio-netflix-catalog-addon.baby-beamup.club/`
- This add-on **does not** satisfy the `aio-metadata` FlixPatrol Top 10 catalog references in the November 4 Kaptain collection.

## AIO Metadata
- Add-on ID referenced by the collection: `aio-metadata`
- Configuration: `https://aiometadata.stremio.ru/configure/`
- Configure and install the generated, instance-specific `/stremio/<uuid>/manifest.json` URL. Do **not** publish a personal configuration URL here: it may be a credential.
- Check that your configured manifest actually declares `flixpatrol.netflix.us.movie`, `flixpatrol.netflix.us.series`, etc. before expecting those Top 10 rows to work.

A manifest snapshot copied into this repository is **not an operational proxy** for the original catalog server. Store verified public installation URLs here, or build/host an actual Stremio-compatible proxy if you need a fixed manifest URL.
