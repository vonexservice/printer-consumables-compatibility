# Compatibility data format

The CSV template in `data/printer-consumables-compatibility.csv` defines one row per specific printer-to-consumable relationship.

## Fields

| Field | Required | Meaning |
|---|---|---|
| manufacturer | Yes | Printer or consumable manufacturer, as applicable |
| printer_model | Yes | Exact model designation; include suffixes that affect compatibility |
| region | When relevant | Market/region the compatibility claim applies to (for example, Canada) |
| consumable_type | Yes | Toner, ink, drum, waste container, maintenance kit, etc. |
| consumable_part_number | Yes | Exact manufacturer part number or clearly identified compatible SKU |
| colour | When applicable | Black, cyan, magenta, yellow, multi-colour, or not applicable |
| formulation | Yes | Original/OEM, compatible, remanufactured, or other clearly described type |
| yield_pages | If published | Published page yield; leave blank if not reliably documented |
| yield_standard | If published | Standard or method stated by the source, if available |
| verification_status | Yes | `verified`, `unverified`, or `needs_review` |
| source_url | Yes for verified rows | Direct link to manufacturer documentation or another reliable primary source |
| source_title | Yes for verified rows | Title of the source used |
| checked_on | Yes for verified rows | Date checked in ISO format: YYYY-MM-DD |
| notes | Optional | Caveats such as regional differences or model suffix details |

## Example structure

The CSV is intentionally a blank template rather than a list of guessed matches. Do not add an example compatibility claim unless you can verify it from a reliable source.

## Verification status

- **verified** — exact printer model and exact consumable part number were checked against a reliable source.
- **unverified** — a claim has been submitted but has not been independently checked.
- **needs_review** — sources conflict, the source is unclear, or a regional/model distinction needs confirmation.

A row should not be described as verified merely because a retailer lists it. Prefer manufacturer compatibility tools, manuals, product data sheets, or official cartridge guides.
