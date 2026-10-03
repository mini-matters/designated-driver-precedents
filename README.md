# Making a New Behavior Feel Normal

Data, sources, and slides for a study of 35 deliberate attempts to make a new behavior feel normal, from 1929 to 2022. The reference case is the 1988 Designated Driver campaign. By Tim Miano.

Read the essay and see the full deck on Estate of Bits: https://estateofbits.substack.com/p/making-a-new-behavior-feel-normal

## What is here

| Path | Contents |
|---|---|
| `data/fact-check-ledger.csv` | All 432 claims on the slides, one row each: case, slide, field, verdict, slide text, original text, supporting quote, source URL, page or locator, checker note |
| `data/factcheck.json` | The source of truth for every case: claims with verdicts and final wording, campaign/execution/outcome sources, and image records |
| `data/sources.csv` | Every source link by case and role (campaign, execution, outcome, additional) |
| `data/image-credits.csv` | Every image on the slides: item, date, owner, rights status, caption, page URL, file URL |
| `deck/making-a-new-behavior-feel-normal.pdf` | The 62-slide deck |
| `deck/making-a-new-behavior-feel-normal.pptx` | The editable deck; speaker notes carry each case's source links, image credit, and a ledger line for every claim |

## How the claims were checked

Every visible claim on the slides was split out (year, place, type, summary, shift lines, steps, finding, basis, note, and closer-look lines) and traced to a passage in a source that was opened and read. Verdicts: 310 verified as written, 83 corrected, 35 softened, 4 removed and replaced with supported text. Quoted passages were matched by script against the fetched source text; the rest were confirmed by hand or through an alternate copy (PubMed E-utilities, archive.org, OAPEN). A second audit re-checked every changed claim.

## Known limits

- Some sources block automated requests (historians.org, NHTSA, CDC PCD, the Smithsonian, the NYT archive, Fast Company, data.unicef.org, the AJPH DOI). They were read through a browser or an archive.org copy.
- The Twende na Wakati finding comes from Harvard's Gender Action Portal summary; the full paper is paywalled and was not read.
- The Following ER start year (1996) rests on one source.
- The Ven conmigo source contradicts itself on the size of the enrollment rise, so the slide gives no multiplier.
- Many campaigns measured recognition, not behavior. The conclusions keep the two apart.

## Rights

The text, data, and slide design are by Tim Miano and are released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

The campaign images in the deck (posters, print ads, frames from TV spots, and similar material) belong to their owners and are not covered by that license. They are reproduced for commentary, criticism, and research. `data/image-credits.csv` and the deck's credit slides list each image's owner and rights status. To request a correction or removal, open an issue.

## Corrections

Open an issue with the case number, the claim, and the source that contradicts it.

## Cite

Tim Miano, *Making a New Behavior Feel Normal: 35 Campaigns, 1929–2022* (Estate of Bits, 2026), https://github.com/mini-matters/designated-driver-precedents.
