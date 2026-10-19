---
name: school-imrad-research-writer
description: Draft, revise, and audit research manuscripts using the user's school-style IMRAD format, especially the Introduction and Methods. Follow a general-to-specific discussion, bulleted specific objectives, numbered superscript source notes with APA-style bibliographic details when requested, explained development stages, diagram/table insertion points, and appendix cross-references. Tailor every statement to the actual study rather than copying the Hourly example.
---

# School-Style IMRAD Research Writer

## Purpose and boundaries
Produce thesis-ready *Introduction* and *Methods* sections modeled on the supplied school manuscript examples and the Hourly development workflow. Keep the writing readable, formal, and grounded. This skill is a reusable **structure and editing process**, not a source of factual claims about a new study. It does not automatically prepare Results and Discussion when the adviser currently requires only Introduction and Methods.

Read `references/style-guide.md` before drafting; use `templates/introduction-and-methods.md` to place section content and visual markers. Run `references/quality-checklist.md` before presenting a final version. The Hourly-specific mapping in `references/hourly-example.md` illustrates the format but must not be copied into another system's manuscript.

## Source and instruction hierarchy
1. Follow the user's latest adviser instructions, provided sample pages, required school format, and explicitly requested scope.
2. Use study facts, images, existing drafts, approved system requirements, diagrams, and references supplied by the user. Inspect attachments rather than assuming their content.
3. Use external research only when requested or needed to substantiate factual claims; verify authors, years, exact titles, journal/publisher details, URLs/DOIs, and what sources actually support.
4. Treat previous example content as layout guidance, **not** as findings that apply to the current research.
5. If essential details are missing, ask a short targeted question, or mark a transparent placeholder. Never invent research participants, methodology results, interviews, evaluation scores, hardware requirements, software versions, citations, or completed activities.

## Intake: capture only details relevant to the user's requested section
- Approved research title, proposed product/system, type (mobile, web, desktop, game, etc.), intended users, site/setting if applicable.
- Problem and supporting evidence: provided studies and verified local/international context; direct observation/interview only if actually conducted.
- Main features, intended process, scope and limitations, purpose/beneficiaries, related work, any required SDG linkage.
- Adviser-required methodology (RAD, Agile, etc.), actual stages and tasks, development status and tense.
- User-supplied hardware/software tables or specifications; source activity diagram and intended appendix location.
- Evaluation framework (ISO 9126 only when specified), respondents, instrument, procedure, scale, and statistical treatment if known.
- Citation arrangement (school preference: numbered superscripts linked to full APA-style entries at the foot of the page; do not imply it is standard APA 7 in-text author–date format).
Do not make a long questionnaire by default. Draft what is supported and flag only the information needed to finish.

## INTRODUCTION: write general to specific
Arrange connected academic paragraphs in this progression, combining or moving paragraphs when that improves the supplied reference's flow:
1. Explain the broad discipline or activity, its importance, and the conceptual context without inflated, generic claims.
2. Narrow to the practical educational/workplace/social context, supported by credible sources where factual claims require them.
3. Present relevant international and Philippine/local research or institutional evidence as applicable. Do not force a fixed number, or label a source 'local' simply because it is on a Philippine website if it does not address the claimed setting.
4. Describe the specific observed problem or stakeholder need; distinguish firsthand observation, literature evidence, and proposed assumptions.
5. Discuss similar systems/studies and identify a **carefully bounded gap**. Do not assert that every existing system lacks a feature without comparative evidence.
6. Introduce the proposed system and explain its functions, intended beneficiaries, target environment, and what distinguishes its approach. Explain calculations and roles accurately (e.g., do not claim AI performs deterministic salary calculations if it does not).
7. Where truly applicable, explain the requested SDGs and/or software quality model; connect the claims narrowly to what the system actually does.
8. State one general objective, then introduce separate **bulleted specific objectives**. Start each bullet with 'To ...'; make it measurable and tied to a real function or evaluation task. Use simple wording and the user's preferred 'Feature' or 'Module' without replacing other text when only a one-word edit was requested.
9. Cover scope, limitations, and likely beneficiaries, in an order matching the user's example. Separate **expected** benefits from measured outcomes; avoid repetition.
10. Close with a focused purpose statement if helpful to the manuscript flow.

Avoid unsupported numerical estimates, exaggerated claims, unexplained jargon, broad promises, or switching between independent teacher-side estimated compensation and official institutional payroll.

## Citation rules
- Follow the research paper's requested footnote appearance: superscript numeric markers ¹ ² ³ ... in order of **first citation**, pointing to full APA-style bibliographic details. Reuse a source's assigned number if cited again rather than duplicating an entry, unless the adviser explicitly requires a different convention.
- Every factual sourced claim should be directly supported by the referenced source. Prefer one apt source per claim instead of stacking several superscripts after one sentence.
- In the bibliography/footnote itself, provide **only the actual citation**: author/organization, date, title, publication, and verified DOI or clean URL as appropriate. Do not append explanatory summaries, annotations, `utm_source` query strings, or invented publication metadata.
- A thesis using superscript-numbered notes with APA-style entries is a **school-specific hybrid**; orthodox APA 7 normally uses author–date in-text citations and a reference list. State this only when clarification is relevant.
- The Word workflow, if requested: place the superscript using References > Insert Footnote so the matching source appears at the foot of the relevant page. Check bibliography entries for duplicates and renumber as needed.
- Do not use a citation merely because a source's title appears related. Check its precise support before writing a claim.

## METHODS: write general to specific
Use continuous, formal paragraphs, not a disconnected inventory of tools. Adapt the headings to the adviser's exact scheme.
1. Begin with `METHODS`. In the first paragraph define the **actual selected development/research approach** broadly. Then justify its relevance to this system's users, scope, development constraints, and feedback process.
2. Introduce the selected stages in one sentence. **Insert a paragraph break immediately after that sentence** and place `[INSERT DEVELOPMENT METHODOLOGY DIAGRAM HERE]`, followed by an italic caption such as `Figure 1.0. Rapid Application Development (RAD) Model`. Figure numbering is a configurable example, not a universal rule.
3. Explain **each stage in its own substantive paragraph**, named at the beginning, describing what the researchers actually did or plan to do and the project-specific functions associated with it. Keep tense consistent with status. For Hourly-style four-stage RAD, use Requirements Planning, User Design, Construction, and Cutover; recognize iteration between design and construction. Do not silently swap them for an unrelated RAD variant.
4. Transition to equipment/resources, state what the table covers, then put `[INSERT HARDWARE REQUIREMENTS TABLE HERE]` and its caption on separate lines. Follow with prose for **each supplied category** and the role of each device/specification. Do not fabricate minimums or present 'recommended' as 'tested'.
5. Introduce development/runtime software, put `[INSERT SOFTWARE REQUIREMENTS TABLE HERE]` and its caption, then explain each supplied group (operating system, development tools, language/framework/storage, website/hosting when relevant). Distinguish optional components, development-only connectivity, and core runtime requirements.
6. If an Activity Diagram is supplied or planned, summarize its **actual** workflow in the Methods prose and point to the figure in the appendix: `Appendix A (Figure A.1)` when Appendix A is available. **The figure itself goes at the back of the paper**, not in the Methods body, when that is the adviser's chosen arrangement. Never invent unseen branches, screens, actors, or outputs.
7. Explain the actual evaluation standard, if one is established. If ISO 9126 is selected, its six characteristics are functionality, reliability, usability, efficiency, maintainability, and portability. Distinguish software quality evaluation from the development methodology.
8. Only when grounded, finish with research design, sampling/respondents, data collection, instrument, procedure, rating scale, ethical considerations, and statistical treatment. Mark absent study-specific items as `[TO CONFIRM: ...]` instead of making up them or reporting future tests as completed.
9. Do not add Results/Discussion or imply evaluation results before data exist.

### Methodology adaptation
- **RAD**: follow the user's chosen RAD diagram/stage labels. In the Hourly example, four main stages are Requirements Planning → User Design → Construction → Cutover, with cycles for design/build/feedback/testing. Explain stage boundaries coherently: preliminary/iterative testing may take place during Construction and final acceptance testing in Cutover.
- **Agile** or other development models: use the exact stages shown in the new study's approved diagram. Never call Agile phases 'RAD' or automatically reuse the reading-app example's Define, Design, Develop, Demo, Release phases.
- Research that is not a software-development study may need a different Methods architecture. Keep the general-to-specific structure but adapt content rather than forcing development tables.

## Figure, table, and appendix layout
- Keep an explicit, standalone insertion marker exactly where Word's paragraph break should occur. Follow each marker with an italic caption. Do not describe a non-existent figure as completed.
- Recommended **Hourly example** labels: `Figure 1.0. Rapid Application Development (RAD) Model`; `Table 2.0. Hardware Requirements for [System]`; `Table 2.1. Software Requirements for [System]`; `Appendix A`, `Figure A.1. Activity Diagram of [System]`. Reconcile the actual manuscript sequence and school numbering before final output.
- A two-column, justified research-paper style appears in the school examples; follow the actual supplied institutional template for typeface, margins, column setup, indent, caption position, and pagination. Do not invent exact measurement settings.
- Caption/marker placement: lead-in paragraph → blank paragraph / visual/table marker → caption → narrative explanation. Activity Diagram: narrative and appendix cross-reference in Methods → full diagram/caption in appendix.

## Editing contract
- Preserve all untouched words when the user requests a narrow edit (e.g., 'replace only Module').
- If the user asks for 'simpler words', preserve technical meaning and the six objectives unless instructed otherwise.
- When the user asks for only APA entries, output only entries; remove discussion and annotation.
- Use expected/future tense for planned work and past tense only for demonstrated completed work. Do not write completed evaluation claims in a proposal.
- When details conflict (e.g., stated Android minimum versus final framework support), flag for verification; do not silently amend original tables.
- Before delivery, audit claims, technical fidelity, transitions, citations, objective alignment, diagram references, figure/table numbering, and whether placeholders are conspicuous.

## Standard deliverable
Provide only the requested scope, usually:
1. A coherent, copy-ready manuscript draft in the school format.
2. Explicit figure/table insertion markers and captions, if applicable.
3. The footnotes/reference entries (without annotations), when requested.
4. A very short outstanding-items note naming only real unknowns, e.g. respondent count, actual diagram, unverified specifications.

For a new study, begin with the minimal prompt in `templates/starter-prompt.md` and adapt the main template.