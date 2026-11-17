# SortSage rule templates

Copy-first JSON packs for [SortSage for Windows](https://enlightpixel.com/products/sortsage?utm_source=github&utm_medium=referral&utm_campaign=sortsage-rules) by EnlightPixel. Use the packs to preview a small cleanup or as a starting point for your own rules. The SortSage application is sold separately.

| Pack | Matches | Copies to |
| --- | --- | --- |
| [Downloads](packs/downloads.json) | PDF and ZIP files | Separate PDFs and Archives folders |
| [Screenshots](packs/screenshots.json) | PNG names beginning with Screenshot | Screenshots folder |
| [Invoices](packs/invoices.json) | PDF names containing invoice | Invoices folder |

1. Download one JSON pack and open it in a text editor. Replace every example destination with an absolute path you own and can write to. Put it outside any monitored source tree.
2. In SortSage, select a scratch folder containing copies of a few representative files and import the JSON in the rules interface.
3. Review the imported rules. Enable only the rules under test, keep automatic triggering off, and inspect Dry Run before executing. Check unmatched files too.
4. Run the rule on the samples and check the new copies. Every pack starts disabled, uses Copy, and requests SmartRename on a collision. Change to a move only after testing and making a backup.

These examples match filenames and extensions. The invoice pack does not read a PDF's contents and the screenshot pack will miss images with a different naming convention. See the [SortSage documentation](https://enlightpixel.com/products/sortsage/docs) and [official downloads](https://enlightpixel.com/products/sortsage/download). The JSON examples are available under MIT.
