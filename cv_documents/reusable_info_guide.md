# Reusable Information Guide

This file centralizes recurring profile and contact information used across CVs, letters, applications, and site pages.

## Core Personal Information

| Field | Value | Source |
| --- | --- | --- |
| Full name | Cayetano Soneira Landín | `docs/cv.md` |
| Preferred citation name | C. Soneira-Landín | `docs/trajectory/publications.md` |
| Date of birth | 18 January 1999 | `docs/cv.md` |
| Email | csoneira@ucm.es | `docs/contact.md` |
| ORCID (current CV/docs value) | 0009-0002-0760-4985 | `docs/cv.md`, `docs/contact.md` |
| Website | https://csoneira.github.io/csoneira/ | `docs/contact.md` |
| LinkedIn slug | cayetano-soneira-906a241b5 | `docs/contact.md` |
| Current position | Predoctoral researcher, Nuclear Physics Group (GFN), UCM | `docs/cv.md` |

## Name and Signature Variants

- Full: `Cayetano Soneira Landín`
- Bibliography short: `C. Soneira-Landín`
- Signature block short:
  - `Cayetano Soneira Landín`
  - `PhD student, Universidad Complutense de Madrid (UCM)`
  - `Nuclear Physics Group (GFN)`

## Recurrent Contacts

| Name | Role | Contact | Notes | Source |
| --- | --- | --- | --- | --- |
| Luis Mario Fraile Prieto | Physics Director, ISOLDE (CERN); Catedratico UCM | Luis.Fraile@cern.ch | Recommender / supervisor context | `calls/ESA-FAIR/drafts/LoR_Draft_Luis_Mario_Fraile_ESA_FAIR_2026.md` |
| José Manuel Udías Moinelo | Catedrático UCM | jmudiasm@ucm.es | Recommender / project PI context | `calls/ESA-FAIR/drafts/LoR_Draft_Jose_Manuel_Udias_ESA_FAIR_2026.md` |
| Alberto Blanco | LIP collaborator | (email not stored in repo) | Speaker in NMDB 2025 contribution where Cayetano is co-author | `calls/ESA-FAIR/drafts/Publications_Cayetano_Soneira_ESA_FAIR_2026.md` |

## Application Contacts (ESA-FAIR 2026 call)

Use these as copied in the call text (verify before external use):

- Maria Didonna, Biophysics Secretariat (GSI): `bio-sekretariat(at)gsi.de`
- Marcia Bennet, ESOC Darmstadt: `Marcia.Bennet(at)esa.int`
- Piers Jiggens (ESA): email shown in call text; verify on official ESA channels before use.
- Anna Fogtmann (ESA ext): email shown in call text; verify spelling/domain before use.
- Charlot Vandevoorde (GSI/FAIR): `C.Vandevoorde(at)gsi.de`

Source: `calls/ESA-FAIR/The ESA-FAIR Space Radiation School 2026.docx`

## Recurrent Institutions and Projects

| Type | Canonical wording |
| --- | --- |
| University | Universidad Complutense de Madrid (UCM) |
| Group | Nuclear Physics Group (GFN) |
| Project | Nueva Generacion de Dispositivos de Imagen Molecular en Mama (NeWMBI) |
| Detector project | miniTRASGO |
| School | DRD1 Gaseous Detectors School (CERN) |

## Reusable Research Summary (Short)

Predoctoral researcher in Nuclear and Particle Physics focused on radiation detector instrumentation, cosmic-ray monitoring, and medical imaging applications (including RPC/MRPC systems and in-beam PET workflows).

## Master Data File

Structured master log for future reuse is stored at:

- `cv_documents/master_academic_activity.csv`

This CSV is designed to be the single table for publications, conference outputs, teaching, outreach, projects, scholarships, and related activities.

## Data Hygiene Notes

- Prefer ISO-like `date_sort` (`YYYY-MM-DD`) in CSV rows. Use first day of month/year when only partial date is known.
- Keep `status` values consistent: `published`, `accepted`, `presented`, `completed`, `ongoing`, `pending`.
- For entries backed by files, update `evidence` with local path in `cv_documents/PUBLIC/`.
- Use ORCID `0009-0002-0760-4985` consistently across public-facing files.
