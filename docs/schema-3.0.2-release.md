# GLC schema 3.0.2

GLC schema 3.0.2 is a patch release derived from 3.0.1.

## Change from 3.0.1

- `device_datasheet.schema.json`: `datasheet_channel` now requires at least one
  channel item when the field is present. The field was already required, but
  schema 3.0.1 unintentionally accepted an empty array.

Schema 3.0.1 remains unchanged and supported for reproducibility. New packages
should use schema 3.0.2.
