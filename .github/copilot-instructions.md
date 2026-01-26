# AI Agent Instructions – Sergio Muñoz CV Workspace

## Project Overview

Bilingual (Spanish/English) CV workspace for Sergio Muñoz de Alba Medrano positioning him as **Operations & Program Management Leader / Chief of Staff** across public, nonprofit, and mission-driven private sectors in Yucatán Peninsula.

**Key Positioning:** Primary narrative is operations leadership and executive coordination; conservation and rural development are domain examples, not limiting factors.

## File Architecture

- **segunda ronda/** → Current production CVs (3 pages, optimized)
  - `cv_SMAM_Director_Operations_Programs_ENG.tex/.pdf` → English CV (Operations & Programs Director)
  - `cv_SMAM_Director_de_Operaciones_y_Programas_SPA.tex/.pdf` → Spanish version (parallel structure)
- **NEW_CV_Chief_of_staff/** → Previous iterations; reference archived versions
- **OLD CV/** → Archive; reference only
- **docs profesionales sergio/** → Supporting documents (credentials, official documents)
- **para imprimir/** → Print-ready PDFs

## Core Content Rules

### Tone & Voice
- **English:** Business/managerial (operations, execution, leadership). Standard management terminology.
- **Spanish:** Neutral, professional, appropriate for public/nonprofit/private sectors.
- **Framing:** Position agriculture/conservation as _domain examples_, not identity limits.

### Narrative Framework
Always present Sergio as:
1. **Operations & Program Management Leader** (primary)
2. **Chief of Staff / Executive Partner** to senior leadership
3. **Organizational Development & Execution Expert**

Systematically highlight:
- Team size: **320+ staff, 22 regional offices** (SAGARPA context)
- Budget scale: **250+ million MXN annually, 45,000+ beneficiaries**
- Interinstitutional coordination roles
- Process/system implementation (SOPs, ISO 9000, digital platforms)

### Bilingual Synchronization
- Each meaningful change in Spanish → reflected in English
- Maintain parallel structure and similar level of detail
- Key translation pairs:
  - "Subdelegado de Planeación" → "Deputy Director for Planning and Rural Development (Operations Lead)"
  - "Encargado del Despacho" → "Acting Regional Director / Chief of Staff"

## LaTeX CV Format (moderncv)

**Style:** banking mode, blue color  
**Structure:**
1. Professional Summary (30+ years, operations focus, scale of teams/budgets, Chief of Staff role)
2. Core Management Competencies (7 key areas: operations leadership, program management, chief of staff, organizational development, processes, data systems, stakeholder relations)
3. Professional Experience (reverse chronological, each entry: 1–2 context lines + 3–5 quantified achievements)
4. Education, Languages, Technical Skills

**Compilation:** `pdflatex cv-sergio-munoz-eng-chief_of_staff.tex` or `latexmk`

## Key Competencies (Reference)

| Competency | Evidence |
|---|---|
| Operations Leadership | 320+ staff, 22 offices (SAGARPA) |
| Program Management | 250+ MDP annually, 45,000+ beneficiaries |
| Chief of Staff / Executive Liaison | Deputy Director role, state/federal coordination |
| Organizational Development | Municipal councils, CoPs, cross-institutional teams |
| Processes & Quality | SOPs, ISO 9000, workflow standardization |
| Data & Systems | GOB.mx v3 platforms, traceability, compliance tracking |
| Stakeholder Relations | Secretariats, international orgs, producers, private sector |

## Copilot-Specific Instructions

### English CV (segunda ronda/cv_SMAM_Director_Operations_Programs_ENG.tex)
- **Preserve:** Professional Summary messaging, 7 Core Competencies, Operations & Programs positioning
- **Update entries:** Ensure each position explains role in operations/management terms, includes quantified metrics (people, budget, scope, systems)
- **Maintain consistency:** Any structural change applies to Spanish version in parallel

### Spanish CV (segunda ronda/cv_SMAM_Director_de_Operaciones_y_Programas_SPA.tex)
- Same positioning logic as English version
- Parallel structure and content depth
- Localized terminology (ops/management, not just sector-specific language)

### LinkedIn Profile (future: linkedin-profile.md)
- Headline: "Director of Operations & Programs | Program Management | Chief of Staff"
- About: 30+ years leading operations, budgets, multisector coordination
- Job descriptions: Brief, results-focused, emphasize scale and execution

## Workflow

1. **Edit CV content** in `.tex` files (use moderncv syntax)
2. **Compile to PDF** via `pdflatex` or `latexmk`
3. **Keep EN ↔ SPA in sync** – major edits in one language should flow to the other
4. **Archive old versions** in OLD CV/ folder
5. **Export final PDF** to para imprimir/ for distribution

## Interaction Language

- Internal work and Copilot dialogue: Spanish acceptable
- Final CV output (English): Standard management English
- Documentation: Bilingual or English preferred
