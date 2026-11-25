# OU Libraries Digital Repository (Islandora) - Postman collection

University of Oklahoma Libraries [digital repository](https://repository.ou.edu): digitised Western History Collections items, including the printed case record *The Chickasaw Nation vs. John P. Holder et al.* (Melven Cornish Collection).

## Import
In Postman: **Import > Link** and paste
`https://raw.githubusercontent.com/mikeyeves/OU-Libraries-Repository-Postman/main/OU_Libraries_Digital_Repository_Islandora.postman_collection.json`

## Requests
| Folder | Requests |
|---|---|
| OAI-PMH | Identify, ListSets, ListRecords, GetRecord |
| Datastreams | object page, MODS, DC, OCR |

## Notes
- OAI-PMH Identify and GetRecord, and the MODS datastream, live-tested 25 Nov 2026.
- The Islandora REST module path (`/islandora/rest/v1`) is not enabled.

Built for family-history research (Genealogy-Vault), November 2026. Status lines say what was live-tested.

## Licence
Collection: CC0. The data and images belong to the source institutions; follow their terms of use.
