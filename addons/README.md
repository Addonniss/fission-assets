# Stremio add-ons used by COLLECTION imports

These are **installation sources**, not hosted copies of add-on manifests. Do not install raw GitHub JSON files as Stremio add-ons: catalog requests are relative to the installed manifest URL and must reach the original add-on server.

## AIO Metadata
- Add-on ID referenced by the collection: `aio-metadata`
- Configuration: `https://aiometadata.stremio.ru/configure/` or `https://aiometadata.elfhosted.com/configure/`
- Configure and install the generated, instance-specific `/stremio/<uuid>/manifest.json` URL. Do **not** publish a personal configuration URL here: it may be a credential.
- Check that your configured manifest actually declares `flixpatrol.netflix.us.movie`, `flixpatrol.netflix.us.series`, etc. before expecting those Top 10 rows to work.
