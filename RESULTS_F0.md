# DOC-1-038 F0 RESULTS: BGC discovery documentation audit

Source position 38: Discovering Novel Biosynthetic Gene Clusters with Deep Learning. Original scope: metagenomic BGC identification and prediction of final chemical product structures. Research-only/documentation-only F0. No sequences, structures, BGC-entry values, model scores, fitting, synthesis or biological engineering. No clinical use. Zero scientific success credit.

## Verdict

UNRESOLVED for the original fixed-set question, not a full-set STOP or a scientific negative. Documentary routes do not establish independent metagenomic product labels, eligible cohort coverage, family-held-out evaluation or current JGI rights. Full GO impossible by construction: actual execution readiness remains UNKNOWN. No GO-ready F1 package or narrower model task promoted.

Design (ii), predictions-as-labels, is STOP/FAIL by its definition, not a new route-based result: antiSMASH labels cannot independently validate a model against those same predictions. D also explicitly says cluster borders are estimated and core product structures are rough predictions, with the final molecule likely different. This supports the pre-stated incompatibility for replacing measured boundaries/final structures with those predictions, not failure of the tool at its own intended task. Designs (i)/(iii) remain UNKNOWN. Full-set STOP would require explicit route incompatibility for both, absent here.

## Chronology

- Protocol web commit af1d206099d16d661478e5b17ec38419be136470; GitHub API committer time 2026-10-09T22:24:53Z.
- Release f0-protocol-lock API created_at 22:24:53Z, published_at 22:25:37Z; lightweight tag points to exact commit. Conservative cutoff 2026-10-09T22:25:37Z, later API time, not a page-display inference.
- Tagged PROTOCOL_LOCKED.md readback byte-identical, SHA256 a82928992c4231f5acee619aae8083df6443cb6f8272dd55bb1a13ca5378e13e.
- Builder-reported first-fetch UTC A-D 2026-10-09T22:25:50Z, E-G 22:25:52Z; strictly after cutoff. Time files are private working records, not published; hashes-only below. Not independently attested fetch times.
- API lock verification preceded fresh A-G re-fetches. Parallel lock gate re-review is not an admission prerequisite under the parent ruling. No pre-lock fetch is RESULTS evidence. All fixed route markers matched (B case-insensitive).

## Documentary route support and gaps

| Route | Read documentary support | Gate disposition |
|---|---|---|
| A MIBiG Zenodo 4.0.1 | JSON data-standard files and associated GenBank/FASTA metadata; dataset CC BY 4.0, reuse/redistribution with attribution. No archive opened. | M1 independent experiment/boundary evidence UNKNOWN per entry; M2 measured final structure schema/linkage UNKNOWN; M3 metagenomic context UNKNOWN; M4/M5 UNKNOWN-by-construction without entry list/coverage; M6 stated dataset license support within scope only; M7 UNKNOWN. |
| B MIBiG home | title-only capture. | M1-M5 UNKNOWN, not data absence; M6/M7 UNKNOWN. No entry/diagram exploration. |
| C antiSMASH FAQ | hybrid-versus-neighboring cluster uncertainty, conservative borders, gene-prediction/input and privacy prose. | Tool documentation, not experimental labels. M1/M2 incompatibility only for predictions-as-measured-label design; M3-M5 UNKNOWN-by-construction; stopping design (ii) does not stop this route as evidence for other designs. M6 code license UNKNOWN on admitted routes, privacy prose not data-use rights; M7 UNKNOWN. |
| D antiSMASH output docs | estimated borders; predicted functions; KnownClusterBlast uses MIBiG; rough predicted core and warning that final molecule likely differs. | M1/M2 explicit incompatibility when used as measured boundary/final-product truth, consistent with design (ii) STOP; no tool accuracy verdict. M3-M5 UNKNOWN-by-construction; M4 documented MIBiG/antiSMASH overlap channel, audit needed in F1. Stopping design (ii) does not stop this route as evidence for other designs. M6 software/data rights UNKNOWN, M7 UNKNOWN. |
| E current JGI portals | IMG/M metagenomic functional annotation in isolate-reference context; SMC described as sequence/annotation resource; July 2026 ORCID/2FA notice. | Metagenomic resource exists in principle, not independent measured product linkage. M1-M5 UNKNOWN at cohort level. M6 specific rights UNKNOWN; M7 access/budget UNKNOWN, no sign-in attempted. SMC is not a substituted route/data source. |
| F current JGI policy hub | sparse public policy/support mission, policy-document references. | Current per-dataset intended-use/release/redistribution rights UNKNOWN. No policy PDF followed; missing current terms not a prohibition. M1-M5 UNKNOWN-by-construction, M7 UNKNOWN. |
| G historical 2020 Q&A | historical annotation backfill, published/unpublished rights distinctions, access caveats. | History only, not current 2026 permission or eligibility. M1-M5 UNKNOWN; M6 current rights UNKNOWN, M7 current readiness UNKNOWN. |

M4 positive independence requires distinct collection/recruitment projects/consortia and site or country, no shared specimen/assembly/participant or sequencing/processing batch lineage, and no shared BGC family/product scaffold across development and test. Submitters/entries are not projects; MIBiG is one source family until source evidence establishes otherwise. IMG datasets from one JGI proposal/PI group are one family. No >=3 independent-family set or untouched family is verified. Family definition, novelty threshold and holdout rule belong to F1, not selected here.

Novel does not mean unannotated or absent from MIBiG. No BLAST/KnownClusterBlast, similarity threshold or clustering executed. Tool non-detection, genome BGC absence and MIBiG non-entry are not validated negatives. Product-label coverage cannot be bounded from documentation/file counts or sizes. No power/coverage claim.

## Enumerated designs and FAIL versus UNKNOWN

(i) MIBiG training plus independently labeled IMG/M metagenomic test: UNRESOLVED, measured final product/boundary linkage, metagenomic test lineage, rights, family coverage and readiness UNKNOWN. E's metagenome description is not such a test set.
(ii) antiSMASH predictions as metagenomic detection/full-product labels: STOP by definition, with D's predicted-border/core wording as additional explicit incompatibility evidence. This is the only design that may FAIL without a route statement. For design (ii) itself, downstream M3-M5 are not assessed after the stop. No executed negative experiment or tool failure claimed.
(iii) MIBiG-only modeling claimed as metagenomic discovery: UNKNOWN. Locked FAIL rule needs explicit isolate-derived/experimentally characterised entries with no metagenomic context plus metagenomic-discovery claim. A/B do not establish that provenance in permitted text; generic dataset title is not sufficient. No full-set STOP.

## Rights distinctions

A's explicit CC BY 4.0 dataset terms support that licensed work's scope with attribution; they do not establish independent experimental validity or IMG rights. AntiSMASH code license remains UNKNOWN from admitted C/D; no inference from its public software status. F current hub is sparse, so current JGI/IMG per-dataset use/release conditions UNKNOWN. G historical Q&A cannot grant present permission.

A later F1 must verify research/model-fitting and held-out evaluation rights, derived-prediction/evaluation-result release rights, and redistribution rights for any BGC-derived table (including reused annotations/product metadata) separately. Partial license evidence is not a full M6 pass. No data table released, PI contacted, account created/signed in, upload or agreement accepted.

## Captures and hashes

Each SHA256 below hashes the separated UTF-8 Markdown route capture, including fetch header. Private raw captures retain unread images/sections; source URLs identify documentation, not downloaded sequence/structure datasets.

- A https://zenodo.org/records/14835872
  - SHA256 55eddf80725a5883180c0b564564b4de981c7c88b011a76a9f581e13cb9df1b6
- B https://mibig.secondarymetabolites.org/
  - SHA256 ab9ebbeb2f973ca2a970ce686c4a3ee060124c26611ee9e19b3350ab0721d51b
- C https://docs.antismash.secondarymetabolites.org/faq/
  - SHA256 b667678be3538b913047babfa3da25471b26dbf758ac024dd0baaeeeeb5b2218
- D https://docs.antismash.secondarymetabolites.org/understanding_output/results/
  - SHA256 f591d4010dd83fe94be528eaf45497c8178b0e64820ebc3c5d015c1610b0abab
- E https://jgi.doe.gov/analyze-data/jgi-portals
  - SHA256 e56147c7f393720ffba5b0a457727efdccbe4311935a659f1dea8ae8febeffc2
- F https://jgi.doe.gov/Data-Policy-Support
  - SHA256 6931a017c1a69a3526eaa11e915b6409418bebba67cc0a878e5cfb56f6912027
- G https://mgm.jgi.doe.gov/2020/04/27/img-webinar-2020-april-21-data-export-and-download-qa/
  - SHA256 8d0c9ffa38e361664ff3db98416fc11ff916bd38b4998dd5c86852d6b04c37a9
- A-D.txt: 1f1502d65d78a9534a46d7fe6154c73e4b0e24ad59ea4518619db30c0f984840
- E-G.txt: db2b03afb19a424ce351065046cb7b17a409b14ec63c0fb061a99d64b54c7aeb
- A-D-first-fetch-utc.txt: c6467101ace3b32baa488d2304c7cc2a353718724b9ac68091a3b553cdc14370
- E-G-first-fetch-utc.txt: f3c2f7cd93f6f8df434e0d8d65fe57fb26cc7c77d0cd387ed42f9a9a9531c0d3

## Exposure ledger and deviations

Pre-lock fetch UTC unrecorded. A-G and MIBiG download page fetched during discovery; the download page is exposure only, not a route and not re-fetched post-lock; its file sizes/checksums are not evidence. Pre-lock queries/exposure details retained in frozen protocol. No threshold, floor, family definition or design choice derives from A's file sizes, E/G counts or any illustration. Unrecorded historical exposure cannot be excluded.

Post-lock permitted reading: A description/version/license (no archive); B title; C limitations/input/privacy prose; D output semantics/limitations prose only (no images); E IMG/M/SMC/access prose; F sparse policy prose; G historical rights/version/access prose. A file metadata are captured but not cohort/product-coverage evidence. D raw images/structure displays remain unread; E unrelated portal counts and G unrelated examples/counts remain unread during admission. No named hazardous product, toxin or virulence factor copied as an example.

Deviations/source-instruction exposure list:
- Route A says, "This dataset was uploaded with permission from the corresponding author(s)." This is an external uploader-approval claim, not authorization for this work; it was not followed as an instruction or grant. Rights assessment used the separately stated dataset license only within scope.
- Instruction-like source text seen, not followed: C recommendations to contact/upload/use other software, G navigation instructions, and E ORCID/2FA login notice. No contact, upload, alternate-software operation, navigation expansion or sign-in followed from that text.

No execution or value-access deviations found. No data archives, BGC records, sequences/structures, policy PDFs, alternate sources or analysis service operated. This is bounded source-document audit, not data admission for fitting.

## Closeout scope

UNRESOLVED/documentation-only/zero credit. No deep-learning BGC detector, metagenomic discovery, chemical-structure prediction result or scientific success from this unit. Source38 remains open. Independent full-product labels, metagenomic lineage, family/scaffold holdout, rights and safety review need a separately gated F1 before values/compute. No sequence design, synthesis, mutation ranking or biological optimization. Honest unresolved findings do not terminate the wider program.
