# NAA Checker Brief: change report, 26 November 2026

Draft file: `drafts/content_DRAFT_2026-11-26.json` (version 2026-11-26b). **Not live.** The live `content.json` has only the new date stamp (2026-11-26a).

## 1. Italy: address for initial examiner assessment of competence applications

| | Wording |
|---|---|
| App now (attributed to EASA EDD 2026/Q4, section 3.16) | "Request individual Designation to istruttoriesaminatori@enac.gov.it (at least 15 days for  the designation)" |
| ENAC web page, dated 01/09/2025, retrieved 26 Nov 2026 | "At least 15 days before the intended exam, an application for an Individual Authorisation … to personale.volo@enac.gov.it" |

Source: <https://www.enac.gov.it/en/safety-security/personnel-certification/edd-examiner-differences-document/>

- The 15-day period agrees. Only the address differs. istruttoriesaminatori@enac.gov.it does not appear on that ENAC page.
- This is a conflict between two sources, not a proven new change: the ENAC page date is older than the EDD issue (01.10.2026).
- The ENAC wording came through the automated fetch tool. Open the page and confirm it before approval.
- Draft change: the quotation and a NOT CHECKED line are added under Italy, "What to send before" and "Can you conduct it?". Existing EDD quotations are kept.

To approve: publish the draft as `content.json` (raise `contentVersion` if the live version is by then newer than 2026-11-26b, and keep the latest check date).

## 2. Seen but not drafted (unconfirmed)

- Italy: the ENAC page links to `.../personnel-licencing/examiners-forms/`; the app link ends `examiners-form`. Neither was opened successfully today.
- Italy: a search also found RPT 01 at `/uploads/2025/07/RPT-01-ATPL-MPL-TR-CR.pdf` (Ed. 2025.01, Rev 00.00). The app links a 2025/12 file with the same edition label; that link was not opened.
- Bulgaria: a form "CAA LST/LPC (A) FORM 003 / Issue 3" is on caa.bg. It refers to EDD version 01-2014, so it appears older than the held Issue 05 form.

## 3. Core sources

| Source | Result |
|---|---|
| EASA Examiner Differences Document | Unchanged: [EASA page](https://www.easa.europa.eu/en/examiner-differences-document) shows 2026Q4. PDF itself not opened. |
| UK CAA Standards Document 24(A) | **NOT CHECKED** (fetch permission unanswered). Held: Version 6. |
| FAA ATP ACS | Listing page not checked. [FAA file](https://www.faa.gov/sites/faa.gov/files/training_testing/testing/acs/atp_acs.pdf) at an older address is the 2019 edition; [current-series file](https://www.faa.gov/training_testing/testing/acs/atp_airplane_acs_11.pdf) is FAA-S-ACS-11A, November 2023. No newer version seen. |
| 14 CFR 61.43 | Section page not checked. Rules [2026-18776](https://www.federalregister.gov/documents/2026/09/14/2026-18776/sport-pilot-practical-test-standards-alignment) and 2026-23786 ([govinfo](https://www.govinfo.gov/content/pkg/FR-2026-11-23/pdf/FR-2026-11-23.pdf)) do not amend its text. |
| 14 CFR 121.424/.427/.433/.440/.441, Part 142 | Consolidated text blocked. Rule 2026-23786 does not amend Parts 121 or 142. |
| EASA Part-FCL, AMC/GM, FEM compare | Not due (Mondays). |

## 4. Authorities in today's rotation

| Authority | Result |
|---|---|
| Ireland | Partial. Pages load; PLAM 004 PDF unreadable, so periods, addresses and forms not confirmed. |
| Italy | Difference above. Portal, fallback email, 1, 7 and 15 day periods and RPT 01 edition agree. |
| Denmark | Not checked. |
| Austria | Not checked. |
| Belgium | Blocked (CAPTCHA) or not checked. |
| Bulgaria | Partial. Examiners Handbook Issue 2 Rev 1 unchanged; web pages and forms not checked. |

No authority was fully re-checked. All other authorities were not in today's rotation.

## 5. Language scan

Today's changes add no foreign-language wording (ENAC and email addresses aside). The scan did find non-English text already in the live content, left unchanged for your decision:

- Czech Republic: Czech handbook title in references and one form title.
- France: French guide title in references, the French name of a registration form inside quotations, and one French system name.
- Poland: a short Polish phrase quoted in one line.
- Authority names and a postal address with accented letters (Iceland, Malta) and a Slovak form code.
