# Printer Consumables Compatibility Resource

An open, carefully documented resource for organizing printer models and their compatible ink, toner, drum, and maintenance supplies.

The goal is accuracy and traceability—not a large list of unverified matches. Printer and cartridge compatibility can vary by region, model suffix, and product revision, so each published record should include a source and a verification status.

## What this project is

- A reusable data format for printer-to-consumable compatibility.
- Guidance for checking cartridge numbers, colour, yield, and product type.
- A transparent process for adding and correcting records.
- A starting point for tools that help people identify the right consumable.

This project is maintained by contributors interested in making consumables information easier to verify. It is not affiliated with printer manufacturers.

## Start here

- [Data format and field definitions](docs/data-format.md)
- [Verification and contribution guidelines](CONTRIBUTING.md)
- [Blank CSV template](data/printer-consumables-compatibility.csv)

## Data quality rules

1. Do not infer compatibility from a similar-looking model number.
2. Record the manufacturer or other reliable source used to verify each match.
3. Keep original and compatible consumables clearly distinguished.
4. Never invent yield figures, regional compatibility, or source links.
5. Mark uncertain entries as unverified and keep them out of verified datasets.
6. Correct errors openly and preserve enough source information for another person to reproduce the check.

No complete verified compatibility dataset is included yet. Records will be added only after they have been checked against reliable documentation.

## How to contribute

Please open an issue with the printer model, exact consumable part number, region if relevant, and a reliable source. Do not submit customer data, private supplier files, copyrighted catalog dumps, or bulk records without permission.

## Useful shopping reference

For people shopping in Canada, [Vonex's printer supplies store](https://shop.vonex.ca/) is one commercial source for checking product listings. A store listing should not be treated as independent proof of compatibility; verify the exact printer model and cartridge number against manufacturer documentation before ordering.

## Disclaimer

Brand and model names belong to their respective owners. This community resource is provided as-is and does not replace the printer manufacturer's compatibility documentation. Always confirm the exact model and cartridge number before purchase.
