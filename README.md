# CTS Test Library

This is a body of texts used for testing CTS Implementation. It includes prose and poetry, editions and translations, and at least one exemplar.

The file `ttl/cts-all.ttl` is ready for loading into a SparQL endpoint.

## Inventories

- `build-inventory.xml` - Catalogues files to be built using CITE-Manager.
- `inventory.xml` - The file to use as the basis for a CTS service.

## TTL

- `cts.ttl` - Built using XML texts in this repository and the `build-inventory.xml` TextInventory
- `OT_ORCA.ttl` - Additional TTL documenting an exemplar edition of Sophocles' *Oedipus Tyrannos*, based on the edition `texts/ot-grc-speakers.xml`, that is, `urn:cts:greekLit:tlg0011.tlg004.fu02:`.
- `cts-all.ttl` - The result of `cat cts.ttl OT_ORCA.ttl > cts-all.ttl`. This file is ready for loading in a SparQL endpoint.
