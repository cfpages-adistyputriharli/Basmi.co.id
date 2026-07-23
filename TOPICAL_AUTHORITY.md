# Topical Authority — basmi.co.id

## Role and boundary

Basmi.co.id should become an Indonesian reference and commercial decision-support hub for integrated pest management (IPM), public-health vectors, nuisance animals, termite protection, building hygiene, sanitation, and the moisture/exclusion defects that let infestations recur. The primary readers are homeowners, tenants, building owners, facility and food-safety teams, procurement staff, and people preparing to engage a competent pest-management provider.

Neutral education belongs under `/artikel/<slug>/`. Existing pest and service routes remain commercial landing pages where the offer is verified. The catalog deliberately contains no city, province, or region briefs: a place name alone does not change pest biology, survey logic, treatment safety, or procurement intent.

Health and chemical boundary: the site may explain risks and professional decision processes, but it must not diagnose disease, prescribe treatment for bites or poisoning, provide do-it-yourself poison recipes, give pesticide mixing/dose instructions, or promise eradication, sterilization, zero risk, or disease prevention without suitable evidence. Pesticide, biocide, disinfection, vector-health, poisoning, food-site, pregnancy/child/pet, and fumigation content requires current Indonesian primary sources plus review by the relevant qualified pest-management, environmental-health, medical, veterinary, food-safety, chemical-safety, or legal professional.

## Evidence audited

Audit date: 2026-07-23.

| Evidence | Finding |
|---|---|
| Ownership and canonical source | Portfolio registry marks `basmi.co.id` as owned; repository is `cfpages-adistyputriharli/Basmi.co.id`, branch `main`, remote `origin`; working tree was clean before documentation work |
| Framework | 950,967,204-byte static WordPress export with 6,986 non-git files; no editable CMS/content collection is present |
| HTML inventory | 6,454 HTML files: 5,373 at root and 1,081 nested |
| Sitemap index | `sitemap_index.xml`/`sitemap.xml` point to 27 post sitemaps plus one page sitemap; those children declare 5,394 URL records and 5,392 unique raw URLs |
| Post sitemaps | 5,379 records, 5,377 unique URLs; two URLs are duplicated across the post sitemap set |
| Page sitemap | 15 URLs: homepage, 12 pest/hygiene service pages, contact, and about |
| Complete sitemap | `sitemap-complete.xml` lists 6,454 unique URLs: homepage, 5,386 top-level routes, 539 category-archive routes, and 528 author-archive routes |
| Partial sitemaps | `500-sitemap.xml` and `video-sitemap.xml` each contain only 500 ordinary page URLs; the latter incorrectly references a `genset.co.id` XSL URL |
| Location template set | 5,366 unique pest/service posts are place-name variants across 11 patterns; each family has about 488–490 sitemap entries including its empty-location base page |
| Archive set | 11 category archives have 49 pages each (539 total); the single author archive has 528 pages; these mostly paginate the location templates and are not independent editorial coverage |
| Broken/inconsistent routes | Nine Rank Math post URLs are absent from the complete export; complete sitemap adds malformed empty-suffix routes and several routes absent from the Rank Math set; `.html` and extensionless/canonical forms are inconsistent |
| Existing offer | Homepage names pest/rodent control, termite control, fumigation, monitoring equipment, and pre/post-construction consulting; service pages cover termites, rodents, cockroaches, ants, bed bugs, flies, mosquitoes/fogging, wasps, geckos, generic insects, and disinfection |
| Existing claim risk | Pages contain broad “safe,” “environmentally friendly,” “sterile,” “kills larvae,” “total eradication,” guarantee, health, and efficacy language without visible product registration, label, SDS, dose, test, licensing, monitoring, or reviewer evidence |
| Current editorial depth | No verified neutral knowledge-article collection exists; the 5,377 post URLs are commercial location templates rather than substantive editorial coverage |

Representative route families:

- `/jasa-pembasmi-rayap-<place>.html`
- `/jasa-pembasmi-tikus-<place>.html`
- `/jasa-pembasmi-kecoa-<place>.html`
- `/jasa-pembasmi-semut-<place>.html`
- `/jasa-kutu-kasur-<place>.html`
- `/jasa-pembasmi-lalat-<place>.html`
- `/jasa-fogging-nyamuk-<place>.html`
- `/jasa-pembasmi-tawon-<place>.html`
- `/jasa-pembasmi-cicak-<place>.html`
- `/jasa-pembasmi-serangga-<place>.html`
- `/disinfektan-<place>.html`

Primary planning sources checked on 2026-07-23:

- [Permenkes No. 11 Tahun 2025](https://peraturan.bpk.go.id/Details/335213), the current risk-based business-licensing standard for the health subsector; it supersedes covered provisions of Permenkes 14/2021, 8/2022, and 17/2024.
- [OSS KBLI 81290](https://oss.go.id/id/kbli/detail/fc704812-e15e-475b-8842-2969a286d4fc), which identifies pest extermination and the relevant vector, disease-carrying animal, and settlement-pest service scopes.
- [Permenkes No. 3 Tahun 2026](https://jdih.kemkes.go.id/documents/peraturan-menteri-kesehatan-nomor-3-tahun-2026), the current disease-control regulation. Its revocation schedule leaves only specified provisions and the appendix of Permenkes 2/2023 in force; writers must not cite Permenkes 2/2023 as wholly current.
- [Permenkes No. 2 Tahun 2023](https://jdih.kemkes.go.id/documents/peraturan-menteri-kesehatan-nomor-2-tahun-2023), retained only to the extent stated by Permenkes 3/2026; its retained technical appendix is a source candidate for vector surveillance, resistance, efficacy, and integrated methods after legal review.
- [Permentan No. 43 Tahun 2019](https://peraturan.bpk.go.id/Details/201255/permentan-no-43-tahun-%202019), currently listed as in force for pesticide registration.
- [Kemenkes Regalkes PKRT portal](https://regalkes.kemkes.go.id/) and its [official marketing-authorization guide](https://regalkes.kemkes.go.id/informasi_alkes/014.%20Pedoman%20Pelayanan%20Izin%20Edar%20PKRT%20Bilingual.pdf), which require supporting product data and specific testing for disinfectant products; product status and permitted claims still need case-by-case verification.
- [PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021), covering environmental protection and B3/non-B3 waste management; applicability to each product and waste stream requires specialist review.
- [Kemenkes guidance prioritizing PSN 3M Plus over fogging for dengue prevention](https://kemkes.go.id/id/%2014156-2); use this as public-health context, not as a substitute for current local health-authority direction or an outbreak assessment.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | Commercial overview with broad pest-control claims | expand | National commercial overview linked to BAS-00, BAS-01, and pest hubs | Verify legal entity, credentials, real service area, staff claims, evidence, contacts, and current offer |
| `/serangga/` | Generic insect service page overlaps every insect-specific page | expand | Commercial triage page that routes identified pests to species/service pages | Remove duplicated species guidance and unsupported universal claims |
| `/rayap/` and `/anti-rayap/` | Heavy overlap between active-infestation and prevention/pre-construction intent | manual review | Prefer `/rayap/` for active infestation and `/anti-rayap/` for prevention/pre-construction only if search/history and service evidence support both; otherwise merge | Check GSC, backlinks, leads, canonical behavior, treatment capability, and warranties before redirecting |
| `/tikus/`, `/kecoa/`, `/semut/`, `/kutu-kasur/`, `/lalat/`, `/fogging-nyamuk/`, `/tawon/`, `/cicak/` | Pest-specific commercial landing pages with useful offer signals but unsafe/unsupported claims | expand | Respective commercial routes; neutral biology and decision content belongs to BAS-03 through BAS-10 | Verify identification, products, methods, label uses, competency, safety process, monitoring, and proof |
| `/disinfektan/` | Commercial disinfection page conflates cleaning, disinfection, sterilization, organisms, and guaranteed safety | expand | Commercial disinfection route supported by BAS-11 | Verify PKRT/product authorization, label claims, surface compatibility, contact-time evidence, reviewer, and whether service remains offered |
| `/disinfektan.html` | Post and page collapse onto the same canonical intent | merge | `/disinfektan/` | Confirm traffic/backlinks, then one canonical 301 and remove duplicate sitemap entry |
| Eleven empty-location base posts such as `/jasa-pembasmi-rayap.html` | Template placeholders render phrases such as “di ” and duplicate service hubs | merge | Respective pest/service commercial route | Check history before redirect; do not retain empty-location pages |
| 5,366 place-swapped service posts | Near-identical commercial doorway pattern with no verified local office, staff, case, regulation, ecology, or substantive local evidence | manual review | Consolidate by service family into national service routes; retain a local page only where unique operations and evidence satisfy a strict local-page gate | Export GSC/backlinks/leads; verify each real staffed service area and local proof before bulk redirects |
| `/category/<family>/` plus 528 pagination pages | Archive pages paginate location templates and compete with service hubs | noindex | `/artikel/` knowledge index and pest hubs | Verify live indexation/backlinks; consider redirecting only category roots with a clear equivalent |
| `/author/syamsul-alam/` plus 527 pagination pages | Single-author archive reproduces template excerpts with no independent search intent | noindex | About page for authorship; `/artikel/` for discovery | Verify backlinks and whether author expertise can be substantiated |
| Nine sitemap post URLs absent from static export | Sitemap-to-file mismatch | manual review | Existing equivalent route or a clean 404/410 after evidence review | Check deployed response, GSC, backlinks, and why export omitted them |
| `/jasa-pembasmi-cicak-`, `/jasa-pembasmi-tawon-`, and other sitemap-only anomalies | Malformed or inconsistent suffix routes | remove | Clean service hub or correct historical route | Confirm no traffic/backlinks and implement exact redirects where warranted |
| `500-sitemap.xml`, `video-sitemap.xml`, `sitemap-complete.xml`, Rank Math sitemaps | Conflicting sitemap sets; `video-sitemap.xml` is not a video sitemap and points to a foreign-domain XSL | remove | One canonical sitemap index containing only indexable canonical URLs | Validate production routing and search-engine submissions before deletion |
| `/tentang-kami/` and `/kontak-kami/` | Entity/contact pages with claims that need substantiation | keep | Entity trust and conversion routes | Add legal identity, service boundaries, credentials, privacy/contact handling, and evidence |

The local-page gate requires all of the following: a real service operation or accountable partner in that area; unique address/service-area and contact evidence; locally specific availability, building/ecology/regulatory or case evidence; original photos or records where claimed; and non-templated content. City names alone are insufficient.

## Coverage matrix

| Completeness lens | Topic owners | Status/notes |
|---|---|---|
| Definitions, vocabulary, taxonomy, biology | BAS-00 through BAS-11 | Covered by IPM and pest-specific owners |
| Need recognition and no-action thresholds | BAS-00, BAS-01, BAS-03 through BAS-10 | Covered; nuisance alone is not automatically a chemical-treatment trigger |
| Survey, identification, measurement, risk | BAS-01, BAS-17 | Covered with evidence and uncertainty |
| Requirements and treatment selection | BAS-02 through BAS-16 | Covered; site-specific decisions stay professional |
| Procurement, cost components, contracts, warranty | BAS-17, BAS-18 | Covered without fabricated prices |
| Preparation, occupied-space controls, handover | BAS-14 through BAS-17 | Covered |
| Monitoring, maintenance, recurrence, replacement | BAS-00, BAS-12, BAS-17 | Covered |
| Termites | BAS-02 | Covered across biology, building, survey, options, monitoring, and contract |
| Rodents | BAS-03 | Covered with exclusion and food-site boundaries |
| Cockroaches | BAS-04 | Covered separately from ants and generic insects |
| Ants | BAS-05 | Covered separately by colony behavior and identification |
| Bed bugs | BAS-06 | Covered separately; not conflated with mites/fleas or hygiene |
| Flies | BAS-07 | Covered by source, sanitation, species, monitoring, and control |
| Mosquitoes | BAS-08 | Covered across breeding-source reduction, surveillance, barriers, and professional chemical methods |
| Wasps/stinging insects | BAS-09 | Covered with emergency and relocation boundaries |
| Geckos/other nuisance animals | BAS-10 | Covered with humane, legal, and structural controls |
| Sanitation and disinfection | BAS-11 | Covered; cleaning, sanitizing, disinfecting, and sterilizing remain distinct |
| Moisture, building defects, exclusion | BAS-12 | Covered as recurrence drivers, not generic construction advice |
| Physical, biological, chemical, heat, fumigation alternatives | BAS-13 | Covered as comparison and escalation, never recipes |
| Pesticide/biocide safety and exposure | BAS-14 | Covered with label/SDS, re-entry, storage, spill, and incident gates |
| Children, pregnancy, older people, asthma, pets, aquaria | BAS-15 | Covered without medical/veterinary diagnosis |
| Food businesses and sensitive facilities | BAS-16 | Covered with HACCP-like evidence and contamination boundaries |
| Monitoring, service records, bids, contracts, evidence | BAS-17 | Covered |
| Regulation, licensing, competence, claims | BAS-18 | Covered with dated legal review |
| Environmental effects, resistance, non-target species, waste | BAS-19 | Covered |
| Indonesia climate and geography | BAS-08, BAS-12, BAS-19 | Covered substantively; no place-swapped briefs |
| History | BAS-00-A06 | Covered in one article; separate parent topic is unnecessary |
| News/trends | N/A | Not a stable parent topic; material regulatory/product changes update BAS-18/BAS-19 |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| BAS-00 | Dasar IPM dan siklus pengendalian | Understand how prevention, thresholds, intervention, monitoring, and review form one system | definitions; pest versus vector; tolerance/action thresholds; lifecycle; hierarchy of controls; recurrence; seasonality; roles; myths; history | lifecycle diagram; glossary; decision tree; qualified review | Does not identify a specimen or prescribe a treatment; BAS-01 owns diagnosis and BAS-13 owns method comparison | 6 |
| BAS-01 | Survei, identifikasi, dan penilaian risiko | Turn signs and observations into an evidence-based problem statement | interview; inspection zones; specimen/photo limits; droppings/tracks/damage; monitoring tools; infestation extent; exposure pathways; uncertainty; risk register; stop conditions | survey checklist; photo atlas; sample report; entomology/environmental-health review | Does not diagnose illness or select pesticide; pest owners BAS-02–BAS-10 own biology and BAS-14 owns chemical safety | 6 |
| BAS-02 | Rayap dan perlindungan bangunan | Distinguish termite evidence and choose a survey/treatment pathway | soil versus drywood concepts; swarmers; mud tubes; timber damage; moisture; pre/post-construction; bait/barrier/local treatment; monitoring; warranties; structural escalation | anatomy and damage photos; survey map; decision table; termite specialist review | Structural adequacy belongs to an engineer; product rates and application stay on label and with licensed professionals | 6 |
| BAS-03 | Tikus dan rodent management | Control rodents by proofing, sanitation, trapping, monitoring, and accountable escalation | species/signs; entry paths; food/water/harborage; exclusion; traps; rodenticide limits; carcasses; contamination; food sites; trends | sign atlas; exclusion diagram; trap/monitoring map; pest and health review | No bait formulation, placement recipe, disease diagnosis, or wildlife-law conclusion; BAS-14/BAS-16/BAS-18 own those gates | 6 |
| BAS-04 | Kecoa | Match cockroach ecology and infestation evidence to sanitation, exclusion, monitoring, and treatment | German/American and lookalikes; harborages; moisture/food; egg cases; inspection; monitors; vacuum/heat/bait concepts; resistance; recurrence | identification photos; kitchen map; trend chart; entomology review | Ants remain BAS-05; pesticide selection/rates remain BAS-13/BAS-14 | 6 |
| BAS-05 | Semut | Identify colony behavior and solve entry/source conditions without confusing ant species | trails; nesting; winged ants versus termites; food/water; species uncertainty; exclusion; bait/spray trade-offs; colony response; monitoring | comparison photos; trail map; decision tree; entomology review | Termite identification is BAS-02 and universal poison advice is excluded under BAS-14 | 6 |
| BAS-06 | Kutu kasur | Recognize and manage bed bugs without stigma, unsafe spraying, or false certainty | signs and lookalikes; inspection; travel/luggage; apartments; laundering/heat concepts; encasements; professional treatment; follow-up; bites boundary | photo atlas; room inspection map; preparation checklist; pest and medical review | Does not diagnose bites, recommend skin treatment, or give insecticide/heat recipes; BAS-14 owns exposure safety | 6 |
| BAS-07 | Lalat | Trace adult flies to breeding/source conditions and verify improvement | major indoor/food-site groups; larvae/source; drains/waste/manure; entry; sanitation; physical controls; traps; monitoring indices; chemical limits | identification chart; source map; sanitation audit; trend chart | Mosquitoes belong to BAS-08 and food-process compliance to BAS-16 | 6 |
| BAS-08 | Nyamuk dan pengendalian vektor | Prioritize breeding-source reduction and surveillance while understanding professional chemical interventions | Aedes/Anopheles/Culex concepts; containers/drains; lifecycle; PSN 3M Plus; larval/adult surveillance; barriers; larviciding; fogging limits; resistance; local health coordination | lifecycle diagram; container survey; primary Kemenkes sources; entomology/public-health review | No disease diagnosis, outbreak declaration, fogging dose, or promise that fogging prevents dengue; authorities and professionals own interventions | 6 |
| BAS-09 | Tawon dan serangga penyengat | Assess immediate sting risk and choose isolation, observation, relocation, or professional removal | wasp/bee lookalikes; nest location; defensive behavior; vulnerable people; temporary isolation; building entry; night-work myths; pollinator considerations; incident boundary | identification guide; risk decision tree; pest/medical/ecology review | No nest-removal instructions, allergy diagnosis, or emergency-medication advice; emergency care follows official medical channels | 6 |
| BAS-10 | Cicak dan hewan pengganggu lain | Solve nuisance-animal access and food-chain causes with humane, proportionate controls | geckos; spiders; fleas/mites distinctions; birds/bats/small wildlife boundaries; insects as food; lighting; gaps; droppings; legal/welfare questions; professional referral | identification limits; exclusion details; humane-control matrix; wildlife/veterinary review | No wildlife poisoning, trapping recipes, protected-species claim, or disease diagnosis; regulations require case-specific review | 6 |
| BAS-11 | Sanitasi dan disinfeksi | Choose cleaning, sanitation, or disinfection based on the actual contamination task | terminology; soil removal; target organism and label claim; contact time; dilution only per label; compatibility; ventilation; verification; routine versus incident use; food-contact surfaces | process flow; label anatomy; PKRT check; environmental-health/chemical review | Does not promise sterility or replace outbreak/medical guidance; BAS-14 owns exposure and BAS-16 food-site protocols | 6 |
| BAS-12 | Kelembapan, kerusakan bangunan, dan eksklusi | Find and repair building conditions that sustain pests | leaks; condensation; drainage; roof/wall/plumbing defects; gaps; doors/screens; penetrations; drains; clutter/voids; renovation; verification | moisture/exclusion survey; annotated details; field measurement; building specialist review | Does not replace leak, structural, electrical, or envelope design; pest treatment remains in species topics | 6 |
| BAS-13 | Alternatif dan pemilihan metode pengendalian | Compare non-chemical and chemical approaches by target, evidence, exposure, and follow-up | sanitation; exclusion; traps; vacuum; heat/cold concepts; steam; baits; residual/contact methods; growth regulators; biological methods; fumigation boundaries; resistance | multi-criteria decision table; evidence hierarchy; manufacturer/label comparison; specialist review | No recipes, rates, mixtures, application instructions, or DIY fumigation; BAS-14 owns handling safety | 6 |
| BAS-14 | Keselamatan pestisida, biosida, dan paparan | Read product evidence and plan safe professional use, re-entry, storage, transport, spill, and incident response | registration; label; SDS; hazard versus risk; PPE limits; occupants; ventilation; food/water; re-entry; storage; containers; waste; exposure documentation | label/SDS anatomy; pre-job checklist; primary regulation; toxicology/chemical-safety review | No first-aid invention, antidote, dose, mixing, or off-label use; the product label and emergency/medical professionals control immediate response | 6 |
| BAS-15 | Penghuni sensitif, hewan peliharaan, dan komunikasi risiko | Ask the right questions before work in occupied spaces | children; pregnancy; older people; asthma/allergy; disability; pets; aquaria; plants; neighbors; consent/access; relocation; re-entry; communication | occupant questionnaire; pre/post notice; medical/veterinary and chemical review | Does not declare a product safe for an individual or give medical/veterinary advice; BAS-14 owns product controls | 6 |
| BAS-16 | Pangan, bisnis, dan fasilitas berisiko tinggi | Integrate pest control with hygiene, operations, and audit evidence | restaurants; kitchens; food plants; warehouses; hotels; schools; healthcare; offices; transport; zoning; contamination protection; downtime; contractor access; corrective action | site matrices; monitoring map; food-safety/environmental-health review; audit checklist | Does not claim universal HACCP, hospital, or school compliance; BAS-18 and the facility authority own exact obligations | 6 |
| BAS-17 | Monitoring, laporan, pengadaan, dan kontrak | Buy and manage measurable service rather than vague extermination promises | baseline; device map; thresholds; trend data; service report; corrective actions; scope; exclusions; visits; warranty; product disclosure; bid comparison; case evidence | dashboards; report/contract templates; procurement checklist; anonymized real evidence | No fabricated prices, reviews, case studies, efficacy, or warranty; technical method remains in BAS-13/BAS-14 | 6 |
| BAS-18 | Regulasi, kompetensi, dan klaim layanan | Verify the legal and competence basis for a provider, product, method, and public claim | KBLI/PBBR; national/local roles; pesticide registration; PKRT; retained/revoked rules; staff training; equipment; subcontractors; records; advertising claims; update dates | official-link register; compliance flow; credential checklist; legal/professional review | Not legal advice and never assumes a permit applies everywhere; exact current requirements require official/local confirmation | 6 |
| BAS-19 | Dampak lingkungan, resistensi, dan limbah | Reduce non-target harm and avoid control strategies that undermine future efficacy | resistance mechanisms; rotation versus evidence; pollinators; aquatic life; pets/wildlife; drift/runoff; indoor air; packaging; carcasses; B3/non-B3 classification; climate/season change | pathway diagram; waste decision tree; resistance plan; ecology/chemical review | No disposal shortcut or environmental-safety claim without product and waste-stream evidence; BAS-14 owns immediate exposure | 6 |

## Related-domain opportunities

Different owned domains may cover the same query independently; they are not same-domain cannibalization. Useful perspectives include:

- `safety.co.id`: worker PPE, chemical-risk assessment, incident reporting, confined spaces, and contractor safety.
- building/trade domains such as `tukang.co.id`, `atap.id`, `plafond.id`, `kayu.co.id`, and `fasad.co.id`: repair of leaks, penetrations, rotten timber, envelopes, ceilings, and other entry/moisture defects.
- `katering.co.id`: food-production hygiene and pest-prevention practices from the operator viewpoint.
- `taman.co.id` and `kolam.co.id`: drainage, vegetation, standing water, pollinators, aquatic non-target organisms, and outdoor habitat.

Cross-links are optional and contextual. They do not replace complete coverage on Basmi.co.id.

## Consolidation plan

1. Export GSC, backlinks, analytics, qualified leads, and call/WhatsApp attribution for all 5,366 place variants before any bulk URL action.
2. Freeze new location-template generation immediately. A future local route must pass the evidence gate in this document.
3. Keep and rewrite the verified national commercial hubs. Separate neutral knowledge pages under `/artikel/`.
4. Resolve `/rayap/` versus `/anti-rayap/` using history and a real service boundary; do not keep two pages with the same active-infestation intent.
5. Merge the 11 empty-location template pages into their service hubs and fix the `/disinfektan` route/canonical collision.
6. Group place variants by service family and evidence outcome: retain only substantiated local operations; redirect valuable overlapping URLs to the closest national service owner; use 404/410 for unsupported URLs with no useful history. Never redirect every URL blindly to the homepage.
7. Noindex author and paginated category archives first; redirect a category root only when it has a clear equivalent and useful history.
8. Replace all sitemap variants with one canonical sitemap index after URL decisions. Include only canonical, indexable, successful routes and remove malformed, missing, archive, and duplicate entries.
9. Remove or qualify unsupported health, safety, “green,” efficacy, guarantee, sterilization, price, staff-count, and geographic-availability claims until evidence is attached.
10. Preserve an implementation ledger mapping old URL, evidence, decision, destination, HTTP status, canonical, internal links, sitemap status, and post-launch verification.

## Internal-link architecture

- `/artikel/` is the national knowledge index; BAS-00-A01 is the central IPM foundation.
- Each BAS topic becomes a hub linked to all six children. Every child links upward to its topic hub.
- BAS-01 is the diagnostic gateway. It sends a confirmed or tentative pest identification to BAS-02–BAS-10, building-condition findings to BAS-12, and chemical questions to BAS-13/BAS-14.
- Each pest topic links from signs and identification to prevention/exclusion, method comparison, monitoring, and its relevant commercial service route.
- BAS-11 links to BAS-14 for product/exposure safety and BAS-16 for food/sensitive facilities.
- BAS-12 is the recurrence-prevention layer linked from every pest page where moisture, access, food, or harborage applies.
- BAS-13 explains treatment alternatives; BAS-14 is the mandatory safety gate; neither should copy a pest-specific biology outline.
- BAS-15/BAS-16 modify work planning for people, animals, food, and facility context without duplicating product safety or pest biology.
- BAS-17 receives contextual links from monitoring, procurement, quote, warranty, and service pages. Commercial pages link back to the applicable survey and safety education.
- BAS-18/BAS-19 provide dated compliance and environmental evidence and link to any page making a regulated or environmental claim.

No planned article is orphaned. Related IDs in the catalog are minimum editorial edges, not a generic widget.

## Evidence and editorial standards

- Put the target organism, site, evidence, and decision question before a method or product.
- Verify regulation status on the publication date in the official JDIH/BPK/OSS source. Explicitly distinguish current, partly retained, revoked, and local rules.
- Verify every pesticide/biocide/PKRT product, label use, target, formulation, registration/authorization, expiry, SDS, manufacturer instruction, and claim for the specific product. Never extrapolate one product's evidence to a category.
- High-stakes drafts require named reviewer role and review date: pest-management/entomology for biology and efficacy; environmental health/public health for vectors and disinfection; toxicology/chemical safety for exposure; medical/veterinary for health/pet boundaries; food-safety for food sites; building professional for moisture/structural defects; legal/compliance for regulations.
- Never publish pesticide mixtures, food-bait recipes, fumigant instructions, rates, dilution, injection/drilling patterns, off-label uses, unverified re-entry times, or “natural means safe” claims.
- Emergency content must direct readers to the product label and appropriate emergency/medical authority; do not invent universal first aid. Date-stamp and clinically review it.
- Fogging content must explain source reduction, surveillance, professional/local-health coordination, resistance, exposure, and the limited target/stage of the chosen method. Never market fogging as a standalone dengue guarantee.
- Disinfection content must separate cleaning, sanitizing, disinfecting, and sterilizing; name the target and surface; verify label claim/contact conditions; and avoid “100%,” “sterile,” and unsupported disease-prevention language.
- Use original, labelled photographs only when identification confidence is appropriate. Record specimen uncertainty and refer ambiguous cases.
- Case studies require real, consented, anonymized baseline, method, product evidence, monitoring, limitations, follow-up, and outcome. Absence of sightings is not automatically eradication.
- Cost content describes components and quote comparison until dated local invoices support a range.
- Environmental claims require exposure-pathway and non-target evidence; disposal follows the label and applicable waste classification, not a generic shortcut.

## First bounded publication cluster

Publish 12 assets in Wave W1:

1. BAS-00-A01 — IPM foundation.
2. BAS-00-A02 — lifecycle from survey to review.
3. BAS-01-A01 — pre-service survey checklist.
4. BAS-01-A02 — identification evidence and uncertainty.
5. BAS-01-A04 — pest/site risk matrix.
6. BAS-02-A01 — termite signs and professional escalation.
7. BAS-03-A01 — rodent signs and entry-path mapping.
8. BAS-04-A01 — cockroach identification and harborages.
9. BAS-08-A02 — source reduction versus fogging.
10. BAS-12-A01 — moisture and entry-point map.
11. BAS-14-A01 — pesticide label, registration, and SDS.
12. BAS-17-A04 — provider/quote evaluation.

This cluster creates a coherent path from IPM and evidence gathering to common pest diagnosis, building-source correction, chemical safety, and accountable procurement. It does not depend on city pages.

Monitor indexation; impressions and clicks by distinct intent; checklist downloads/completions; internal path from survey to pest/safety/service pages; qualified survey requests; lead response and conversion; product/evidence questions raised by users; and same-domain query overlap. Compare against a pre-publication baseline and do not expand publication volume until reviewed assets show useful task completion and no new cannibalization.

## Definition of done

- All 20 parent topics have six distinct briefs in `ARTICLE_CATALOG.md`.
- IDs, titles, and slugs are unique; proposed slugs do not collide with audited existing routes.
- Each brief has one primary intent, concrete reader outcome, named exclusion, evidence format, and valid related IDs.
- Every pest, lifecycle stage, safety gate, sensitive setting, monitoring/procurement question, regulatory layer, and environmental pathway has an owner.
- No city/province/region brief or synonym-swapped page is planned.
- Same-domain overlaps are resolved in the register and existing URL actions remain conditional on traffic/backlink/lead evidence.
- High-stakes drafts cite current primary sources and record qualified review.
- The catalog validator passes; counts in the topical map and coverage ledger match.
- Before implementation, production responses, canonicals, robots directives, GSC, backlinks, and redirect destinations are rechecked.
