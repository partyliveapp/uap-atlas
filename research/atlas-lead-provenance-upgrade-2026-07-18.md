# Atlas lead-provenance upgrade tranche — 2026-07-18

## Scope

This tranche follows the completed 125-case carousel migration. It does not add UI. It replaces only leads that can be improved through stronger custody, first-generation records, higher-resolution official scans, or more accurate provenance language.

## Weak-lead ranking

The first pass prioritized:

1. Modern reconstructions presented as the only recognizable opener.
2. Public thumbnails where a source-derived frame could be recovered.
3. Low-resolution document previews with a higher-resolution official archive copy.
4. Disputed photographs whose attribution or custody wording was too broad.
5. Context and summary cards for which no stronger local or public primary visual was yet verified.

Highest-priority cases included Foo Fighters, Kenneth Arnold, CEFAA, Kaikoura, Colares, Gulf Breeze, Calvine, Maury Island, Kecksburg, Varginha, and sparse institutional releases.

## Adopted upgrades

### BF-1947-KA-01 — Kenneth Arnold

- Replaced the modern reconstruction with the June 26, 1947 **Chicago Sun** report.
- Repository chain: Chicago Sun microfilm at Chicago Public Library; UPI copy; public-domain reproduction via Wikimedia Commons.
- Boundary: contemporary reporting of Arnold's account, not event photography or independent confirmation.

### BF-1978-KK-01 — Kaikoura

- Replaced the reduced preview with the full-resolution Archives New Zealand scan.
- Archive reference: `ABHS 6958 W5579 Box 227, NYP 3/58/13 Part 1`.
- Boundary: official investigation record, not encounter film imagery.
- The publicly mirrored documentary footage was reviewed but not promoted because it does not improve custody over the official record.

### BF-2014-CH-01 — CEFAA

- Replaced a generic public-upload thumbnail with a timestamped frame extracted from the complete 9:22 UAP Archive mirror.
- Selected timestamp: approximately `00:08:10`.
- Lead uses a disclosed target/trail crop; the uncropped full frame remains in Files / Sources.
- Boundary: public mirror, not a native CEFAA master. The image does not resolve object identity or competing aircraft/plume analysis.

### BF-1990-CV-01 — Calvine

- Retained the known surviving-print reproduction.
- Corrected attribution using embedded metadata: permission of Craig Lindsay / Sheffield Hallam University; scan credit Andrew Robinson; CC BY-NC-SA 4.0.
- Clarified that this is not an original negative and that the other reported images remain unavailable.

### BF-1977-CL-01 — Colares / Operation Prato

- Retained the secondary photo-reproduction page.
- Corrected provenance language so the selected page is not laundered as a direct Brazilian Air Force original.
- Preserved the Brazilian National Archives packet as the official linked record.

## Rejected or deferred replacements

### Foo Fighters

A higher-resolution Commons image exists with public-domain metadata, but its chain runs through a modern article and visual authenticity is not sufficiently established. The explicitly labeled reconstruction remains safer than promoting it as an event-era photograph.

### Gulf Breeze

The current comparison card foregrounds the disputed photo/model controversy. No demonstrably stronger authenticated event photograph has been established in this tranche; replacing it with a famous but disputed image would weaken the provenance framing.

### Kaikoura film frame

Public documentary mirrors contain footage presented as the encounter film, but no first-generation TV1/Fogarty master or complete custody record was recovered. The official Archives New Zealand cable remains the lead.

## Missing records still controlling confidence

- Native CEFAA/Chilean Navy media master and agency workpapers.
- First-generation TV1/Fogarty and Crockett Kaikoura film.
- Original Calvine negative and remaining reported prints.
- Original Operation Prato negatives with complete custody.
- Authenticated Gulf Breeze negatives and complete photographic chain.
- Original wartime Foo Fighter mission reports and authenticated imagery, if any.

## Late delegated-source reconciliation

The completed three-agent research batch was compared against the implemented selections before deployment:

- **CEFAA:** two additional public YouTube/news mirrors were found, but neither established stronger agency custody than the selected UAP Archive mirror. No lead change.
- **Kaikoura:** a public copy of the December 31, 1978 television report was found. It is visually stronger than a cable page, but its current public custody remains YouTube rather than a verified broadcaster/archive master. The Archives New Zealand record remains the lead; the broadcast copy remains a research lead.
- **Colares:** the delegated report correctly identified the Arquivo Nacional/SIAN PDF as the strongest official public record. Visual inspection of the locally archived official pages showed text-only case records, including explicit discussion of photographs; they do not contain the recognizable alleged photograph shown on the secondary page. The secondary page remains the lead with corrected custody language, while the official PDF remains the primary linked document.
- **Gulf Breeze:** no authenticated original Polaroid, negative, or first-generation public archive was recovered. No change.
- **Calvine:** the batch corroborated the surviving-print/Sheffield Hallam trail but recovered no stronger public asset URL. The retained print reproduction and embedded attribution remain appropriate.
- **Foo Fighters:** no specific wartime mission-report page or contemporaneous clipping was recovered. The reconstruction remains explicitly labeled rather than being replaced by a weak-custody purported photograph.
- **Kenneth Arnold:** the batch recommended a contemporary clipping. That recommendation had already been implemented with the June 26, 1947 Chicago Sun record.

## Verification status

Canonical regeneration and data audit passed. Focused Playwright review checked all 125 carousel-first leads with zero failures, failed URLs, console errors, or page errors. Final deployment-preview and live verification are recorded separately during publication.
