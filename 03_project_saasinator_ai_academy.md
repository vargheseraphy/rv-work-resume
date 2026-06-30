# Project Summary — saasinator & YALLO AI Academy (Claude project report)

Here's the detailed picture that emerges from the saasinator and YALLO AI Academy work across this project, Raphy.

**Your role on this project**

You're the Head of Marketing & Growth at YALLO Group and co-founder/product owner of saasinator — meaning you sit across both GTM strategy and product ownership rather than being purely a marketing executor. You run the strategic synthesis work (the final "Prompt 10" master briefs go through you before reaching Sumeet), and you're the one who decides what gets ratified versus what stays a recommendation. In the chatbot work specifically, you framed your own way of using Claude explicitly: "see me as a founder and I need the council to analyse and take decisions for me" — that's a distinct working style worth naming on a resume: you use AI tooling as a decision-support council, not just a content generator.

**Projects you're driving**

*1. saasinator v2 — the core platform and its conversion chatbot*
You owned the full lifecycle of the AI sales chat agent: architecture decisions (Claude Haiku 4.5 + Groq fallback, Neon Postgres, pgvector RAG, six-state conversion machine), the migration into the saasinator-v2 monorepo as a portable package, and — critically — the QA discipline around it. You ran structured persona-based testing in two full rounds (8 personas, then 7), using yourself, Rohit, and Anil to simulate Gulf enterprise CIO/CTO/CDO/COO buyers against the live agent. Round 1 surfaced zero clean conversions and five lost warm buyers; you drove the fix cycle (15 commits across two rounds) and the re-test that confirmed two full converts and zero P0 bugs. You also made the infrastructure call to standardize on Neon and remove Supabase across all YALLO products, and you handled a live credential exposure incident by rotating all three affected keys without letting it stall the work.

*2. saasinator brand and content system*
You hold the line on the hard content rules — no pricing, no unverified stats, lowercase "saasinator," no overclaiming as a SaaS product — and you push back on the team when those get violated. That's a governance/brand-integrity skill, not just a marketing one.

*3. YALLO AI Academy competitive intelligence program*
You set up and run the structured, repeatable research framework across competitors (Emeritus, AI CERTs) that Rohit and Anil feed into. You're the checkpoint before any pricing model, positioning statement, or accreditation decision (like the AI CERTs partnership question) gets acted on — you and Sumeet are explicitly the ratification gate. This surfaced real strategic findings under your process, like the MBZUAI-vs-Emeritus government contract signal that validated a "local relevance over global brand" positioning bet.

**What this shows about how you operate**

*Leadership and decision-making* — You centralize ratification on irreversible or strategic decisions (pricing, positioning, accreditation, brand commitments) while delegating execution freely to Rohit (engineering), Anil (research), and others. You don't bottleneck day-to-day work, but you don't let strategic calls get made by committee either.

*Thinking style* — You're evidence-gated: claims need a proof point (YALLO Hub, MARS) or they don't ship. You think in frameworks — the IRL service categories, the 70-20-10 model, persona-based QA — and you reuse them deliberately rather than improvising fresh structure each time. You're comfortable holding nuance (e.g., respecting Emeritus's brand strength while still finding the GCC relevance gap) rather than defaulting to simple competitor bashing.

*Execution pattern* — You run things in measurable rounds: test, fix, re-test, confirm. You ask for compressed outputs when you need them ("in short, for a slide") and you're precise about what should and shouldn't appear in a given output (e.g., explicitly stripping dates when reusing a summary). You move fast on infrastructure decisions (Supabase removal, credential rotation) without letting them become extended debates.

*Communication/output style* — Concise, structured, deliverable-oriented. You want markdown/docx outputs that are reusable artifacts (QA transcript packages, competitive SWOTs), not just chat answers. You're direct about scope — correcting when research should stay competitor-scoped rather than blended.

A few resume-ready framings this supports: "Owns end-to-end GTM and product strategy for an AI systems integrator launch, including infrastructure decisions and brand governance," "Designed and ran persona-based QA program for an AI conversion agent, reducing zero-conversion failure rate to zero P0 defects across two test cycles," "Built and govern a repeatable competitive-intelligence framework feeding board-level strategic synthesis."

If it'd help, I can turn this into an actual Word doc resume draft, or just a bullet bank you can drop into whatever format you're building — which would you rather have?
