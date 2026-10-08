---
title: TRACK 25 of 25
type: tracker
date: 2026-10-07
sources: ["https://paretotalent.com", "NotesAndSlides/Pareto_Bootcamp_Day10 - Transcript.txt"]
status: active
related: ["LINK_INDEX.md", "MOC.md"]
---

Title: TRACK 25 of 25. Owner Demian Ducardt. Date 2026-10-07.
Target: 25 of 25. Threshold: 20 of 25 passes. Rubric quoted once from brief: Webinar Topic, Agenda, and Deck.
Deadline: EOD Oct 7 Montevideo time. Results by Oct 16. Submit at bootcamp.paretotalent.com/finalproject.
Contact: demian.ducardt@gmail.com. Sources: https://paretotalent.com plus Day 10 transcript with Ivan Bunin.

Map:
Task A Webinar pack lives in 05_LeadMagnet/webinar_deck.md plus 05_LeadMagnet/quiz.html.
Task B Landing page lives in 06_Funnel/index.html plus thank-you-qualified.html plus thank-you-unqualified.html.
Task C Automations live in 07_Workflows/optin_blueprint.json plus pipeline.md plus pipeline_log.csv plus nurture_qualified_3.md plus nurture_other_1.md plus booking_confirmation.md.
Task D Ads live in 08_Ads/ads_pack.md plus 5 PNGs.
Task E Loom plus PDF live in 09_Loom_PDF/loom_script.md plus FP_Demian_Ducardt_ParetoBootcamp.pdf plus FP_build.html.
Bonus lives in Pareto_Right_Hand_Handbook.pdf at repo root plus 02_Research/target_older_companies.md plus 03_BusinessMap/business_map.html PNG plus owner extra idea TBD.
Strategy base lives in 01_SecondBrain/01_pareto_offer.md plus 02_proof.md plus 03_voice.md plus MOC.md plus 02_Research/competitor_teardowns.md.
PM base lives in 00_Meta/LINK_INDEX.md plus 04_ClickUp_SOP/clickup_board.csv plus sop_lead_magnet_launch.md.

Step 1. Webinar pack for Score 5.
1.1 Lock topic and promise. Topic: Pareto Delegation Score. Find your bottleneck in 2 minutes. Audience: established local companies at 300k plus revenue with inbox overload and random AI use. Promise: 7 question quiz plus tiers plus 10 tasks to hand off first plus SOP template. File: 05_LeadMagnet/webinar_deck.md lines 1 to 40. Keep Kasim Aslam verbatim: You don't have a people problem. You have a delegation problem. Source https://paretotalent.com. Keep triple verbatim: Find the right people. Give them ownership. Get out of the way.
1.2 Write agenda with times. 0 to 3 min hook with 12.5 hours lost weekly. 3 to 8 min live quiz scoring 0 to 21. 8 to 14 min 3 tiers Starter plus Bottleneck plus AI Behind with handoff list. 14 to 18 min Pareto Right Hand with 100 plus founders served plus 93 percent retention at 12 months plus 250 plus pros plus 4.9 of 5 across 84 reviews plus 3 matches in 24 hours. 18 to 20 min email CTA to demian.ducardt@gmail.com. Verify each number against https://paretotalent.com. Drop any number without a live source line.
1.3 Build deck 10 slides in 05_LeadMagnet/webinar_deck.md. Slide 1 title plus owner. Slide 2 hook. Slide 3 quiz. Slide 4 tiers. Slide 5 handoff list of inbox triage plus calendar blocks plus follow ups plus vendor mail plus invoices plus CRM notes plus meeting recaps plus hiring inbox plus content repurpose plus weekly report. Slide 6 offer. Slide 7 proof wall. Slide 8 qualifier math 39,000 divided by 175 equals 223 hours per year. Slide 9 fork. Slide 10 CTA. Export to PDF. Use Pareto dark plus blue. Use Inter 28pt titles. Test PDF opens view only.
1.4 Link quiz to deck. quiz.html must show See my result button plus tier text plus link to ../06_Funnel/index.html. Serve locally for test: python3 -m http.server 8000 --directory "/home/user/Documents/ParetoTalent/Final Project". Open http://localhost:8000/05_LeadMagnet/quiz.html incognito. Complete 7 answers. Confirm result block appears.

Step 2. Landing page for Score 5.
2.1 Keep hero in 06_Funnel/index.html. H1 stays verbatim from https://paretotalent.com. Sub states 2 min quiz plus pack plus email route for companies behind on AI. Proof row shows 100 plus founders served plus 93 percent retention plus 250 plus pros plus 4.9 of 5 across 84 reviews plus 3 matches in 24 hours.
2.2 Keep form fields first name plus last name plus work email plus company URL plus revenue band plus AI use plus need. Revenue options: under 100k plus 100k to 300k plus 300k plus. Need options: Exploring AI help now plus Need help in 30 days plus Just researching.
2.3 Fix fork JS in index.html lines 45 to 50. Route to thank-you-qualified.html only when rev equals high and need equals Exploring AI help now. Route all other combos to thank-you-unqualified.html. Test 6 combos incognito. Log each result.
2.4 Style CTA plus mobile. Button text: Send my result pack. Button color #2a7bff on white form. Confirm single column under 700px. Confirm footer reads Built by Demian Ducardt.
2.5 Publish Pages links. Push 06_Funnel folder to the public repo with Pages on. Paste full https into 00_Meta/LINK_INDEX.md L7 plus L8 plus L9 plus L10. Test each https incognito. Use dash for any missing asset. Never use bitly.

Step 3. Automations for Score 5.
3.1 Confirm pipeline stages in 07_Workflows/pipeline.md. Stages: opt in plus qualified plus call via email plus client plus other. Log file 07_Workflows/pipeline_log.csv columns email plus revenue_band plus route plus date. Add 3 test rows covering high plus mid plus low bands with dates 2026-10-06 to 2026-10-07.
3.2 Confirm opt in blueprint in 07_Workflows/optin_blueprint.json. Trigger: form_submit_06_Funnel_index. Steps: tag by revenue band plus create opportunity row plus send resource email at once plus notify demian.ducardt@gmail.com. Mode: off_by_default in live use.
3.3 Expand 07_Workflows/nurture_qualified_3.md to full bodies. Email 1 Day 0 subject Your Delegation Score pack with quiz link plus tier recap plus CTA reply with revenue band. Email 2 Day 2 subject AI Behind map with inbox agent plus calendar guard plus SOP writer plus proof plus CTA reply with bottleneck tier. Email 3 Day 4 subject 10 tasks to hand off first with full 10 item list plus CTA email to start matching. Each body 90 to 140 words. Each ends with one CTA. From demian.ducardt@gmail.com.
3.4 Expand 07_Workflows/nurture_other_1.md to full body 80 to 120 words. Include quiz pack link plus one tip clear inbox to zero once plus threshold 300k plus for call route plus link to thank-you-unqualified.html.
3.5 Expand 07_Workflows/booking_confirmation.md to 2 mails. Mail 1 confirmation subject Pack received, next step by email with reply template asking 2 times plus timezone plus company URL plus bottleneck tier plus reply within 1 business day. Mail 2 reminder Day 1 subject Quick reminder with same CTA. State clearly: email CTA only. Calendar embed absent by owner setting.
3.6 Test delivery chain. Submit form with test@example.com high band plus Exploring AI help now. Confirm redirect to thank-you-qualified.html. Confirm pipeline_log.csv gains row. Confirm notify to demian.ducardt@gmail.com drafted. Submit second test mid band. Confirm redirect to thank-you-unqualified.html. Screenshot both inboxes. Save PNGs to 07_Workflows/proof_inbox_day0.png plus proof_inbox_day2.png.

Step 4. Ads for Score 5.
4.1 Produce 5 PNGs in 08_Ads plus update 08_Ads/ads_pack.md with file names. Keep one palette Pareto dark plus blue across quiz plus funnel plus emails plus ads. Use real founder photo style. Export at 1080 by 1080. Names: ad1_inbox.png plus ad2_ai_behind.png plus ad3_burned_hirer.png plus ad4_company_pack.png plus ad5_extra_tbd.png. Each ad carries hook plus offer plus qualifier plus proof plus mechanism plus CTA. Each visual ends with Built by Demian Ducardt. Ad copy stays short and direct with client words. Proof chips max 2 per ad from verified pool.

Step 5. Loom plus PDF for Score 5.
Build FP_build.html Section 1 with name Demian Ducardt plus application email demian.ducardt@gmail.com plus lead magnet title Pareto Delegation Score plus funnel tool opencode static HTML plus JS fork. Build Section 2 L1 to L20 with full https links from the public repo. Use dash where asset is pending. Export PDF as FP_Demian_Ducardt_ParetoBootcamp.pdf with clickable links. Record Loom 2 min with face on at 1080p following 09_Loom_PDF/loom_script.md. Timeline covers 0 to 20s magnet plus 20 to 50s landing plus 50 to 80s quiz fork plus 80 to 110s delivery plus 110 to 120s ads plus contact. Upload Loom. Paste https into L20. Re-export PDF. Test PDF links incognito.

Bonus. Problem solving for borderline boost.
Ship Pareto Right Hand Handbook as the extra asset: 17 page A4 beginner book, Day 1 to Day 10, diagrams plus templates plus cited sources, at repo root. File the target shift memo in 02_Research/target_older_companies.md: older companies over digital entrepreneurs, with 4 cited reasons covering behind on average plus value per hour plus willing spend plus saturation gap. Add qualifier math sheet in 02_Research/icp_personas_qualifier_math.md showing annual plan 36,000 plus 3,000 fee equals 39,000 Year 1 with break even 4.3 hours per week against 12.5 saved. Add business map PNG export from 03_BusinessMap/business_map.html with green for built plus red for blueprint. Add ClickUp CSV with all rows Done plus deadlines Oct 6 to Oct 7.

QA gate before submit.
Serve full folder locally. Click every repo https incognito. Click every link inside PDF. Confirm no login wall. Confirm filename reads FP_Demian_Ducardt_ParetoBootcamp.pdf. Confirm 00_Meta/LINK_INDEX.md matches PDF Section 2 line for line.

Built by Demian Ducardt.
