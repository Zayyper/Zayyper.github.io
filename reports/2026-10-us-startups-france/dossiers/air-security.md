## AIR Security at a glance

AIR Security sells an inline "firewall" that finds the AI agents running in a company and vets the skills, plug-ins and MCP servers they load. It left stealth on 1 September 2026 with $50M in seed funding, more than 20 customers and about 40 staff in Israel [1][2][4]. For France, it targets an agent supply-chain risk that NIS2 and DORA make auditable at banks and pharma groups. It has no European presence yet.

| Item | Detail |
|---|---|
| HQ | New York, NY, per company and press [1][4]; R&D in Israel. One database lists Tel Aviv [20] (single source). |
| Founded | February 2026 [2]; "six-month-old" per Calcalist in September 2026 [2] |
| Founders | Yair Saban (CEO) and Niv Hoffman (CTO), both Unit 8200 veterans [1][2] |
| Headcount | About 40, all reported in Israel [2][4]. One database says 26 [20] (single source). |
| Total raised | $50M [1][5] |
| Latest round | Seed in two tranches: $10M led by Sequoia, then $40M led by Greenoaks; announced 1 Sept 2026 [1][2][3][8] |
| Website | www.air.security [11] (missing from data file) |
| France score | 75/100, Tier A. Market demand 23, regulatory fit 14, strategic fit 14, readiness 18, R&D talent 6. |

## Product and business model

AIR sells one platform that governs a company's agents and filters what enters each agent's context [11][12]. These are company claims, repeated by the press:

- **Discovery:** maps agents across endpoints, cloud accounts and SaaS applications [4].
- **Add-on firewall:** vets skills, plug-ins, MCP servers and sub-agents before installation, then re-checks them [11].
- **Response:** traces every workflow that depends on a bad component and revokes it [9].
- **Runtime filter:** screens instructions, untrusted websites and internal data before the agent acts [4][12].
- **Marketplace and scanner:** a source of pre-vetted add-ons [11] and a free "Scan your add-on" page [18].

The company says it blocks about 27% of the add-ons it sees [2][7]. Buyers are enterprise security teams, mostly in finance and pharma [4][7]. Pricing, packaging and deployment model (SaaS or on-premise) are not disclosed. Searches found no SOC 2 or ISO 27001 report, trust page or EU hosting.

AIR stands out through its published research:

- "Circus of Skills": 17,822 skills with 6.7M installations take instructions from unverified outside sources [16].
- "SkillJacking": 925 skills were hijacked from their maintainers, affecting 134,000 agents [14].
- "MCPJacking": 155 MCP servers in the official marketplace could be hijacked [15].
- "Story of Skills": one Instagram ad was used to hijack 26,000 agents [17].
- "Plugin4Shell": a zero-click remote-code-execution flaw, disclosed on 18 September 2026 [13][19].

Calcalist and BankInfoSecurity say AIR plans a research lab on agent behaviour and interpretability [2][6].

## Team

Both founders are Unit 8200 offensive-security veterans who met about a decade ago in the military [2] (single source).

- **Yair Saban, CEO:** co-founder and public voice [5].
- **Niv Hoffman, CTO:** co-founder; co-discovered Plugin4Shell with researchers Or Nevo and Dor Granat [19].
- **Ryan Knisley, Chief Strategy Officer:** former CISO of The Walt Disney Company and of Costco Wholesale [5]. Axonius had appointed him Chief Product Strategist in April 2025 [21].

**Where the team sits:** about 40 staff work in Israel [2][4]. New York is the stated headquarters of AIR Security Inc. [4]. No source describes staff or functions in New York. Startupim lists "Buzz Security Ltd. (Air Security)" [22], possibly the Israeli operating company (single source, unverified). No European staff were found.

## Funding and investors

AIR raised $50M in two seed tranches that closed within weeks of each other [1][2].

| Date | Round | Amount | Lead | Other investors |
|---|---|---|---|---|
| 2026, exact date not disclosed | Seed, tranche 1 | $10M | Sequoia Capital | not disclosed |
| Closed weeks later; announced 1 Sept 2026 | Seed, tranche 2 | $40M | Greenoaks | Swish Ventures, Netz Capital, plus angels [4][5] |

- **Valuation:** not disclosed.
- **Angels:** Zach Frankel (president of Cognition) and Yinon Costica (Wiz co-founder) [7]. Anne Neuberger is also named [10] (single source). Dealroom mentions "executives from Wiz and Clay" [9] (single source).
- **Sequoia:** partner Bogomil Balkansky wants verification "as standard as the network firewall" [10].
- **Swish Ventures:** Omri Casspi's $60M cyber, cloud and AI fund; Sequoia is an anchor investor [23].
- **Netz Capital and Europe:** no Netz profile and no European investor were found.

## Customers, traction and go-to-market

AIR reports more than 20 customers. About a quarter are large enterprises, mainly in finance and pharma [4][7]. No customer is named. ARR, growth and contract size are not disclosed. No reseller, MSSP or technology partner was found.

Research disclosures are AIR's main demand engine. Plugin4Shell hit Claude Code, Codex, GitHub Copilot and Gemini CLI [19]. AIR found it in May 2026 and told vendors in June [19]. Anthropic and OpenAI shipped fixes; Microsoft and Google had not, per the press [19]. The Cloud Security Alliance published a note on it on 19 September 2026 [24].

The funding pays for researchers and for sales in the US and Europe [1][7].

## Market and competition

AIR competes in AI agent security, a fast-funded category where large vendors buy startups. Agents install third-party code on their own; one in four MCP servers opens a code-execution risk [25]. Investors put $435M into agent-security startups across 12 deals in five months [26] (single source). Four AI guardrail vendors were acquired between August and September 2025 [27].

| Company | Position |
|---|---|
| Zenity | Agent security and governance; $125M Series C led by Norwest [28] (single source) |
| Noma Security | AI and agent posture management, red teaming and agent access control [29] (single source) |
| Prompt Security (SentinelOne) | GenAI and agent security; bought for about $250M, announced August 2025 [27][30] |
| Aim Security (Cato Networks) | AI guardrails; bought by Cato Networks in 2025 [27] |
| Check Point (Lakera, Cyata) | Bought Swiss Lakera for an estimated $300M [31]. Cyata can limit agents to approved MCP servers [32]. |
| Palo Alto Networks Prisma AIRS | Agent discovery and an MCP server for agent security [33] |
| CrowdStrike | Agent discovery and shadow-AI control from endpoint to cloud [34] |
| Runlayer (US) | MCP security; launched November 2025 with $11M [35] |
| Giskard (France) | Agent red teaming; launched "sovereign" Giskard Guards in May 2026 [36] |
| Mindgard (UK) | AI security testing; $30M Series A led by Album VC [37] |
| Mithril Security (France) | AI security; acquired by H Company [38] |

AIR is narrower than these rivals, focused on the add-on supply chain. Large platforms already bundle agent discovery. LeMondeInformatique counts 22 French companies specialising in AI protection in 2026, up from 15 in 2025 [39] (single source). No French player with the same add-on firewall focus was found.

## European and French footprint

No European or French footprint was found. The only signal is the stated plan to build sales in the US and Europe [1][7]. Searches found no EU office, EU job posting, EU customer, EU investor, French-language support, EU hosting or EMEA executive. German-language press covered Plugin4Shell [40], which shows awareness, not commercial activity.

## Regulatory fit for France and the EU

EU rules mostly help AIR, but it lacks the compliance evidence French buyers expect.

- **NIS2 / Loi Résilience (tailwind):** France missed the 17 October 2024 transposition deadline [41]. One bill combines NIS2, the CER directive and DORA-related provisions, with ANSSI as supervisor [41]. The National Assembly takes it up from 7 October 2026 [42] (single source). Supply-chain duties make an agent add-on inventory relevant.
- **DORA (tailwind):** banks and insurers must manage ICT third-party risk. Agent add-ons are third-party code.
- **EU AI Act (neutral):** the Omnibus deal of 7 May 2026 delays high-risk duties to 2 December 2027 (Annex III) and 2 August 2028 (Annex I) [43]. Article 50 keeps 2 August 2026 [44].
- **GDPR (headwind until addressed):** runtime screening sees agent context, which may hold personal data. Buyers will want a DPA and EU hosting.
- **ANSSI guidance (tailwind):** ANSSI published 35 security recommendations for generative AI in 2024 [45]. ANSSI and Germany's BSI issued joint advice on AI coding assistants in October 2024 [46], which AIR's research fits. Campus Cyber has an AI security implementation guide [47].

**What AIR would need:** SOC 2 or ISO 27001, EU hosting or on-premise, and a control mapping to NIS2 and DORA.

## France opportunity assessment

The France score is 75/100, Tier A: market demand 23, regulatory fit 14, strategic fit 14, readiness 18, R&D talent 6. The file's rationale cites readiness 21, but the total of 75 uses 18. The opportunity types are market entry and corporate partnership.

| Organisation | Status | Reason |
|---|---|---|
| BNP Paribas | Plausible target | Large bank under DORA; finance is AIR's strongest vertical |
| Société Générale | Plausible target | Same DORA and NIS2 exposure; a second finance reference |
| Sanofi | Plausible target | French pharma group; pharma is AIR's other strong vertical |
| Thales | Plausible target | Defence and cyber group: a possible buyer, or a channel to sovereign deployment |
| Giskard | Plausible target | French agent red-teaming firm; could complement or compete with AIR |

**Recommended pitch:** "NIS2 transposition and DORA make agent supply-chain controls auditable. Your Plugin4Shell research fits ANSSI-BSI coding-assistant guidance. A Paris pilot with a bank anchors your planned European sales."

**Entry points:** Business France for introductions, Campus Cyber for pilots, the Systematic Paris-Region cluster, France 2030 calls. DGA/AID applies only to a sovereign deployment.

## Risks and open questions

- No certifications, EU hosting or on-premise option found; French banks and defence groups may block procurement without them.
- All staff are in Israel. A French R&D site is unlikely.
- Netz Capital is unidentified, and the Buzz Security Ltd. entity is unconfirmed.
- No named customer, so traction cannot be checked independently.
- Large platforms (Check Point, Palo Alto Networks, CrowdStrike, SentinelOne) already bundle agent discovery.
- Sources disagree on headcount (40 or 26) and HQ city (New York or Tel Aviv).

## Recommended next steps

1. Contact Yair Saban or Ryan Knisley about the European sales plan, timing and first target country.
2. Ask for evidence of SOC 2 or ISO 27001, a GDPR DPA and the deployment options.
3. Prepare a one-page map of AIR's controls against NIS2 supply-chain duties and DORA third-party risk.
4. Propose a Campus Cyber session with security teams from BNP Paribas, Société Générale and Sanofi.
5. Check the Loi Résilience vote after 7 October 2026, and update the regulatory argument.
6. Check Giskard's view of AIR as a partner or a competitor before any joint introduction.

## Sources

1. https://techcrunch.com/2026/09/01/air-raises-50m-to-help-companies-vet-the-skills-and-add-ons-ai-agents-use/ (TechCrunch launch article, 1 Sept 2026)
2. https://www.calcalistech.com/ctechnews/article/r13apdnugg (Calcalist: tranches, staff, lab, Sept 2026)
3. https://www.securityweek.com/ai-agent-firewall-startup-air-security-emerges-from-stealth-with-50-million/ (SecurityWeek launch coverage, Sept 2026)
4. https://siliconangle.com/?p=840154 (SiliconANGLE: product, customers, New York and Israel)
5. https://www.newswire.com/news/air-emerges-from-stealth-with-50m-to-build-a-firewall-for-agents-22853509 (company press release, Sept 2026)
6. https://www.bankinfosecurity.com/air-launches-50m-to-keep-enterprise-ai-agents-safe-a-32733 (BankInfoSecurity: CEO interview, Sept 2026)
7. https://www.pymnts.com/news/investment-tracker/2026/ai-agent-security-startup-air-raises-50-million-to-guard-enterprise-supply-chains/ (PYMNTS: customers, angels, blocked share)
8. https://runtimewire.com/article/air-security-raises-50m-ai-agent-firewall (RuntimeWire funding article, from data file)
9. https://dealroom.co/news/148163-air-raises-50m-seed-to-build-a-firewall-for-ai-agents/ (Dealroom: round structure and angel investors)
10. https://aiweekly.co/alerts/air-emerges-from-stealth-with-50m-from-sequoia-and-greenoaks-to-build-a (AI Weekly: angels, Sequoia quote)
11. https://www.air.security/ (company website: platform and marketplace)
12. https://www.air.security/blog-posts/out-of-stealth (company blog: stealth launch post)
13. https://www.air.security/blog-posts/plugin4shell (company blog: Plugin4Shell disclosure, Sept 2026)
14. https://www.air.security/blog-posts/skilljacking (company blog: 925 skills hijacked)
15. https://www.air.security/blog-posts/mcpjacking (company blog: 155 hijackable MCP servers)
16. https://www.air.security/blog-posts/the-circus-of-skills (company blog: 17,822 vulnerable skills)
17. https://www.air.security/blog-posts/the-story-of-skills (company blog: 26,000 agents hijacked)
18. https://scan.air.security/scan/addon (company's free public add-on scanner)
19. https://thenextweb.com/news/plugin4shell-ai-coding-agents-zero-click-rce-sha-pinning (TNW: Plugin4Shell details and patches, Sept 2026)
20. https://fundediq.co/air-security-air-security-funding/ (database profile: Tel Aviv, 26 employees)
21. https://www.globenewswire.com/news-release/2025/04/15/3061550/0/en/Axonius-Appoints-Former-Disney-CISO-Ryan-Knisley-as-Chief-Product-Strategist.html (Axonius appoints Ryan Knisley, 15 Apr 2025)
22. https://startupim.com/company/buzz-security-ltd-air-security (Startupim entity listing, Buzz Security Ltd.)
23. https://techcrunch.com/2024/12/02/omri-casppi-launches-60m-fund-for-cyber-cloud-and-ai-startups (Swish Ventures $60M fund, Dec 2024)
24. https://labs.cloudsecurityalliance.org/wp-content/uploads/2026/09/CSA_research_note_plugin4shell_ai_coding_agent_supply_chain_20260919-csa-styled.pdf (CSA Plugin4Shell research note, 19 Sept 2026)
25. https://helpnetsecurity.com/2026/05/05/ai-agent-security-skills-blind-spots (Help Net Security: MCP server risk, May 2026)
26. https://finance.yahoo.com/technology/ai/articles/air-security-50m-seed-signals-001228353.html (Yahoo Finance: $435M into agent security)
27. https://www.decryptiondigest.com/blog/ai-guardrail-vendors-after-acquisition-lakera-prompt-security-aim-calypsoai (AI guardrail acquisitions wave, 2025)
28. https://ai2.work/blog/zenity-lands-125m-series-c-to-police-enterprise-ai-agent-actions (Zenity raises $125M Series C)
29. https://www.nightfall.ai/blog/zenity-reviews (vendor comparison covering Zenity and Noma)
30. https://www.businesswire.com/news/home/20250805913926/en/SentinelOne-to-Acquire-Prompt-Security-to-Advance-GenAI-Security-and-Agent-Security-Strategy (SentinelOne to acquire Prompt Security, 5 Aug 2025)
31. https://www.venturelab.swiss/Lakera-acquired-by-Checkpoint-in-USD-300-million-deal (Check Point acquires Lakera, estimated $300M)
32. https://siliconangle.com/2026/02/12/check-point-announces-three-startup-acquisitions-mixed-quarter (Check Point buys Cyata and others, 12 Feb 2026)
33. https://docs.paloaltonetworks.com/ai-runtime-security/administration/agent-discovery (Palo Alto Prisma AIRS agent discovery docs)
34. https://www.crowdstrike.com/en-us/blog/new-crowdstrike-innovations-secure-ai-agents-govern-shadow-ai/ (CrowdStrike agent and shadow-AI features)
35. https://techcrunch.com/2025/11/17/mcp-ai-agent-security-startup-runlayer-launches-with-8-unicorns-11m-from-khoslas-keith-rabois-and-felicis (Runlayer launch with $11M, Nov 2025)
36. https://tech.eu/2026/05/07/meet-the-french-startup-fixing-the-guardrail-gap-holding-enterprise-ai-back/ (Tech.eu: Giskard Guards launch, 7 May 2026)
37. https://techfundingnews.com/mindgard-raises-30m-ai-security-cursor-chatgpt-google/ (Mindgard raises $30M Series A)
38. https://sifted.eu/articles/h-company-acquires-mithril-security (Sifted: H Company acquires Mithril Security)
39. https://www.lemondeinformatique.fr/actualites/lire-la-dynamique-des-start-ups-en-cybersecurite-s-accelere-en-france-en-2026-100555.html (French cyber startup dynamics in 2026)
40. https://borncity.com/news/plugin4shell-kritische-luecke-in-ki-programmierassistenten-entdeckt/ (German-language Plugin4Shell coverage, Sept 2026)
41. https://copla.com/blog/compliance-regulations/nis2-directive-regulations-and-implementation-in-france/ (NIS2 in France: status and timeline)
42. https://next.ink/brief-article/alleluia-la-transposition-de-nis2-est-enfin-a-lordre-du-jour-de-lassemblee-nationale/ (Next: NIS2 bill on Assembly agenda, Sept 2026)
43. https://datamatters.sidley.com/2026/06/22/eu-lawmakers-reach-provisional-agreement-to-delay-key-eu-ai-act-obligations/ (Sidley: AI Act Omnibus delay, 22 Jun 2026)
44. https://www.gibsondunn.com/eu-ai-act-omnibus-agreement-postponed-high-risk-deadlines-and-other-key-changes/ (Gibson Dunn: Omnibus changes, Article 50)
45. https://cyber.gouv.fr/sites/default/files/document/security_recommandations_for_a_generative_ai_system.pdf (ANSSI generative AI security recommendations, 2024)
46. https://cyber.gouv.fr/actualites/lanssi-et-le-bsi-publient-leurs-recommandations-de-securite-concernant-les-assistants-de-programmation-bases-sur-lia/ (ANSSI-BSI advice on AI coding assistants)
47. https://wiki.campuscyber.fr/images/6/65/Guide_impl%C3%A9mentation_S%C3%A9curit%C3%A9_IA.pdf (Campus Cyber AI security implementation guide)
