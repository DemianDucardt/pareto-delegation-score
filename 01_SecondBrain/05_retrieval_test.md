---
title: FP Second Brain Retrieval Test
type: retrieval-test
date: 2026-10-07
sources: ["vault-internal"]
status: local-pass
related: ["MOC.md", "01_pareto_offer.md", "02_proof.md", "03_voice.md"]
---

Retrieval test. Owner Demian Ducardt. Date 2026-10-07. Method MOC first, one file open, link follow only if needed.

Q1: exact Pareto headline.
Expected file: 01_pareto_offer.md.
Local proof: string "delegation problem" hits 01_pareto_offer.md plus 03_voice.md. Command grep minus ril "delegation problem" 01_SecondBrain.
Answer: "You don't have a people problem. You have a delegation problem." Source https://paretotalent.com.
Result: pass.

Q2: Year 1 all in annual cost.
Expected file: 01_pareto_offer.md.
Local proof: string "39,000" hits 01_pareto_offer.md in brain core, excluding test file. Command grep minus ril "39,000" 01_SecondBrain minus exclude 05_retrieval_test.md.
Answer: 39,000. 36,000 per year plus 3,000 placement fee. Source https://paretotalent.com pricing block.
Result: pass.

Q3: Justin Donald exact Wall of Love line.
Expected file: 02_proof.md.
Local proof: string "world-beater" hits 02_proof.md in brain core, excluding test file. Command grep minus ril "world-beater" 01_SecondBrain minus exclude 05_retrieval_test.md.
Answer: "My executive assistant Marina came from Pareto Talent and is just a world-beater. The best EA I have ever had." Source https://paretotalent.com/wall-of-love.
Result: pass.

Q4: Kasim triple verbatim.
Expected file: 03_voice.md.
Local proof: string "Give them ownership" hits 03_voice.md in brain core, excluding test file. Command grep minus ril "Give them ownership" 01_SecondBrain minus exclude 05_retrieval_test.md.
Answer: "Find the right people. Give them ownership. Get out of the way." Source Kasim Aslam triple per AGENTS.md.
Result: pass.

Negative test, 2 lines:
- Asked monthly retainer USD standalone. Brain returns Year 1 all in only. Offer file marks standalone unknown.
- Correct behavior is say so or drop the line. No invention.

Built by Demian Ducardt.
