# Gallery Asset Approval Workflow

**Status:** Proposed curation standard  
**Core rule:** A file being present in a repository does not make it approved.

## 1. Asset classes
- MASTER: original source or canonical vector, preserved unchanged.
- APPROVED: reviewed for a specific intended use.
- DERIVATIVE: export or crop made from a verified master.
- REFERENCE: comparative material, not an owned brand asset.
- DRAFT: work in progress, not approved for public use.
- RETIRED: retained for provenance but no longer current.

## 2. Required provenance
Record asset title, file path, creator/author, source, creation or acquisition date when known, rights holder, licence/permission, intended use, relevant brand, approval status, reviewer, restrictions and checksum where useful. Unknown facts must be labelled UNKNOWN; never infer permission from public availability.

## 3. WARENA Flying-Wolf
The Flying-Wolf is intended to represent the WARENA system, not only one product. The design direction is wolf-first, integrated upward wings, one negative-space eye, compact geometry and strong small-size legibility. Treat this as a design brief until the original master artwork is located and verified.

Workflow:
1. Search existing repository history and asset collections.
2. Identify the original source and record provenance.
3. Compare the source against the current design brief.
4. Preserve the master unchanged.
5. Create separate, labelled positive/negative exports from the verified source.
6. Test at 64, 40 and 24 pixels against light and dark backgrounds.
7. Record reviewer, decision, date, export settings and checksums.
8. Do not label generated references as the canonical original.

## 4. Whole-ecosystem crest and signature
The full signed crest may contain more information than a GitHub avatar can display. Preserve a full master for documentation and a simplified, geometry-consistent avatar derivative for small contexts. Do not force every brand name, motto and signature into a tiny circle if legibility suffers.

## 5. Website restriction
The public website policy prohibits embedding graphics. The website may link to this repository as a text destination; do not add inline images, SVG, CSS image backgrounds, video or graphic favicons to the webpage. A curated Gallery does not override this restriction.

## 6. Approval checklist
- [ ] Provenance and rights documented.
- [ ] Intended use and relevant brand stated.
- [ ] Source/master distinguished from derivative.
- [ ] Consent and privacy requirements checked.
- [ ] Canonical status explicitly approved, not inferred.
- [ ] Small-size and background tests recorded for emblem exports.
- [ ] No asset is embedded in the public website contrary to policy.
- [ ] Manifest updated only after review.
