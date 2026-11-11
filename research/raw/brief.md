You are a skeptical venture partner and a senior ML engineer reviewing an idea for a student startup MVP in Kazakhstan. Answer in Russian. Do not edit any files. Be concrete and critical; no flattery, no filler. If you use facts you are not sure about, say so explicitly.

## Context and hard constraints

National program "AI-SANA", Stage III (Program 2: "Digital solutions for industry problems with AI and team leadership", Stanford GSE / Paul Kim). Final project:
- Team of 5 students. Working MVP for a REAL industry problem in Kazakhstan where AI is the core component, not a side feature.
- Deliverables: Google Slides in a mandatory 12-stage pitch format + YouTube video pitch (min 3 minutes, English subtitles, all team members on camera).
- Scored by an AI grader on the SMILE platform: 120 points normalized to 100, pass = 70, unlimited resubmissions. The 12 stages: 1 Problem definition; 2 Target market (TAM/SAM, segmentation); 3 Solution/MVP (highest weight, 15/120: clarity, logical justification, innovation, meaningfulness); 4 Value proposition; 5 Business model (monetization, unit economics); 6 Competitive analysis (positioning, moat); 7 GTM; 8 Financial projections (reduced weight); 9 Team; 10 Traction/milestones (reduced weight); 11 Funding ask; 12 Vision/impact.
- The course teaches a six-criteria idea filter: urgency for the payer; measurable ROI; time-to-value; end-user adoption; dissatisfaction with the status quo; feasibility through AI. It also asks: "Where in this process can AI contribute not by automating what already happens, but by enabling what was previously impossible?" and warns against thin wrappers over a foundation model; moats = domain expertise, data access, workflow integration, niche focus, switching costs.
- Priority industries: mining, agriculture, healthcare, education, fintech, construction, telecom, energy. Extra: cybersecurity, operations automation, robotics, entertainment/media.
- Team capabilities (software only, no hardware, no proprietary corporate data): web apps (Next.js/FastAPI), RAG with citations over regulatory/clinical documents, LLM agents and chatbots in Russian and Kazakh (Telegram/WhatsApp), object detection on phone photos incl. on-device ONNX. Realistic build time: 2-4 weeks.

## What research found (Nov 2026; many numbers are from search snippets and still need verification)

- Construction: 1,463 violations found on sites in Astana and Almaty in 2025; developers fined 1.59 bn tenge, 3,000+ unscheduled inspections; construction output 2025 ~10.8 trn tenge. The ministry pilots computer vision that cuts detection of discrepancies between as-built and design from 3 days to 4 hours; a sector digitalization plan for 2026-2027 is approved; state platform E-Qurylys. Existing players: Armeta (AI review of design/estimate documentation, multi-year contract with the State Expertise), AI Qurylys platform with 6 modules incl. "AI Baqylau" (camera video analytics for PPE and danger zones, incident registry).
- Agriculture: goal to digitize 50% of arable land by 2028; no quantified pest-loss figure found; state "AI farmer assistant" program.
- Fintech: 26.3k internet fraud cases in 2025 (+86%); national anti-fraud center and banks active.
- Telecom: ~2.6k complaints to the regulator in 2025, fines 314.6 mn tenge - small relative to revenue.
- Healthcare: doctor shortage in rural areas; regional AI screening exists; medical software needs registration; patient data is personal data.
- Energy and mining: data closed, vendors present.
- Education: AI tutors for UNT/SAT exam prep are crowded and free.
- Crowded: Kazakh foundation LLMs (AlemLLM, KazLLM).
- Lessons from local startups (Higgsfield, Cerebra, Parqour, CodiPlay, 1Fit, Citix, TrustMe): narrow B2B wedge with measurable ROI; a private payer that can buy within 1-2 quarters; a data loop; local regulatory/language advantage; dependence on a single government channel is dangerous.

## Candidate idea A (current front-runner)

"Pre-inspection of a construction site from a phone". A technical-supervision engineer, HSE specialist or foreman at a small/mid contractor photographs an area and sends it to a bot. AI (1) detects visible violations (missing helmet/vest/harness at height, unguarded openings and edges, scaffolding condition, storage), (2) links each to the exact clause of the applicable Kazakhstan building/safety norm with a verbatim quote in Russian and Kazakh (RAG), (3) drafts the remark/prescription document with photo, deadline and responsible person, and keeps a registry showing site readiness before a state inspection. Out of scope for MVP: hidden/structural defects, comparison with design/BIM. A human signs the document. Positioning: phone instead of cameras, for contractors who cannot afford camera analytics; contractor-side self-check before the state's AI inspection. Moat hypothesis: locally labeled violation photos from engineer accept/reject feedback, clause-level bilingual norms corpus, registry/history switching costs.

Fallback idea B: an AI "virtual patient" simulator for medical students grounded in Kazakhstan clinical protocols (a hackathon prototype already exists). Buyer: medical universities.

## Your tasks

1. BEFORE judging idea A: propose your own top 3 MVP ideas for this team under these constraints (may be in any priority industry). For each: the buyer, the quantified pain you would look for, why AI is essential, the moat, the main risk, and what a 3-week MVP would demonstrate.
2. Attack idea A: the 5 strongest reasons it could fail (market, technical, legal, competitive, grading). For each, say what evidence would confirm or refute it.
3. Technical reality check for idea A: what accuracy is realistic for detecting such violations on arbitrary phone photos with open detectors and vision-language models; which violation types are feasible vs not; how to structure the norms RAG to avoid wrong clause citations; how to evaluate it honestly on a small test set.
4. Score A, B and your own top idea on the six-criteria filter (1-5 each) and say which one you would pick and why.
5. For the idea you pick: which of the 12 pitch stages will be weakest and what evidence the team should collect first.

Keep the answer under 1,200 words.
