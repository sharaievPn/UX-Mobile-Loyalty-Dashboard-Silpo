# UX Architecture of a Mobile Grocery Loyalty Dashboard: A Customer-Centered Approach

This repository accompanies a bachelor's thesis investigating how a user-centered UX architecture for a mobile grocery loyalty dashboard can improve usability, comprehension, and engagement with loyalty features, based on Silpo's app as the case study

---

## Author

**Vitalii Sharaiev**
Ukrainian Catholic University, Faculty of Applied Sciences
Department of Computer Sciences and Information Technologies

**Supervisor:** Dmytro Trotsko
**Submission:** 2026

---

## About the Project

Loyalty dashboards in modern grocery apps often combine bonuses, subscriptions, partner offers, recipes, and personalised promotions on a single screen. Despite the volume of value packed into these dashboards, users frequently struggle to find, understand, or act on loyalty mechanics. This thesis applies a user-centered design (UCD) process — grounded in the Design Thinking framework — to diagnose those friction points on Silpo's mobile app and propose an information-architecture redesign of its loyalty dashboard.

The work combines:

- **Quantitative methods** — eye-tracking attention analysis (RealEye), System Usability Scale (SUS) scoring
- **Qualitative methods** — semi-structured interviews, moderated usability testing, heuristic evaluation (Nielsen's 10 heuristics)
- **Synthesis tools** — affinity diagramming, Customer Profile (Value Proposition Canvas)
- **Ideation tools** — SCAMPER, design briefs
- **Iterative prototyping** — three Figma prototype rounds with two test iterations

---

## Repository Structure

This repo follows the **Design Thinking** 5-steps approach, with an additional preliminary-study phase that audits the existing Silpo experience before any new design work begins.

```
.
├── Preliminary study/    Audit of the current Silpo loyalty dashboard
│   ├── Heuristics Audit/   Nielsen's 10 heuristics applied to the live app
│   ├── Eye Tracking/       RealEye attention maps (heatmaps + view maps)
│   └── IA Audit/           Information-architecture review of current navigation
│
├── Empathy/              Direct research with real users
│   ├── Semi-structured interview/    Recruitment artefacts, raw transcripts (11 participants)
│   └── Usability testing for existing application/   Moderated sessions with 6 participants
│
├── Define/               Synthesis of research findings
│   └── Customer Profile + Affinity Diagraming.pdf    Jobs / pains / gains synthesis
│
├── Ideate/               Concept generation
│   ├── SCAMPER.pdf                   Ideation board
│   └── Design Briefs.pdf             Concept briefs for prototype rounds
│
├── Prototype/            Three Figma prototype iterations
│   ├── Prototype v1.pdf
│   ├── Prototype v2.pdf
│   ├── Prototype v3.pdf
│   └── Власний Рахунок (I–III).fig   Source Figma files
│
└── Test/                 Usability validation of the redesign
    ├── Iteration 1/      Test plan, sessions, and findings — round 1
    └── Iteration 2/      Test plan, sessions, and findings — round 2
```

---

## Research Highlights

A summary of headline findings produced by the research phases (full data and analysis live inside the corresponding folders):

**Empathy** — 17 interview participants generated 277 job statements, 305 pain statements, and 278 gain statements. The most-frequent jobs were QR scanning at checkout, delivery, and checking receipts; the most-frequent pains were technical failures (especially QR-code freezes), navigational complexity, and unclear loyalty value.

**Preliminary study** — Eye-tracking on 8 dashboard screens revealed attention concentrating on the top hero block while critical loyalty mechanics below the fold went unfixated. The heuristic audit surfaced violations across all 10 of Nielsen's heuristics, with "match between system and the real world" and "consistency and standards" the most affected.

**Test** — Moderated usability sessions with the redesigned dashboard exposed remaining navigation failures, confusion between bonus points and paid subscriptions, misinterpretation of offer-validity timers, and visual noise on the home screen — driving the second iteration of the prototype.

---

## How to Read This Repository

The recommended reading order mirrors the design process: start with `Preliminary study/` to understand the existing problem space, move through `Empathy/` and `Define/` for the user research, then `Ideate/` and `Prototype/` for the design response, and finish with `Test/` for the validation evidence. Each folder is intended to stand on its own — supporting artefacts (raw transcripts, Figma sources, eye-tracking CSVs) accompany the higher-level reports.

---

## License

See the `LICENSE` file in the root of this repository.
