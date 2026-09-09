# FG-TIDA Interregnum Preparation Meeting — 1st Meeting

**Source:** FG-TIDA Co-Chairs

**Date:** Virtual, 29 July 2026

**WG(s):** All

**Original:** English

**Contacts:**
- Debora Comparin — Thales, France — debora.comparin@thalesgroup.com
- Amir Banifatemi — Cognizant, United States — amir@cognizant.com

## Abstract

This document contains the agenda and minutes of the FG-TIDA 1st preparation meeting (virtual, 29 July 2026, 60 participants), held during the "Interregnum" period between the launch of the Focus Group (9 July 2026, AI for Good Global Summit) and its first meeting (Paris, 1–4 December 2026).

## 1. Introduction

This document contains the agenda and minutes of the 1st preparation meeting of the Focus Group on Trust and Identity for Humans and Agentic AI (FG-TIDA), held during the "Interregnum" period: the phase between the launch on 9 July 2026 at the AI for Good Global Summit and the first meeting in Paris on 1–4 December 2026. During this phase, the structure, leadership, and initial deliverables of the Focus Group are prepared, for approval at the Paris meeting.

Four preparation meetings are planned, all virtual and at 14:00 CEST: 29 July, 2 September, 30 September, and 4 November 2026. AI-generated transcripts are available from the Chair.

## 2. Meeting Overview

| | |
|---|---|
| **Timing** | Wednesday 29 July 2026, 14:00–15:30 CEST |
| **Title** | 1st FG-TIDA preparation meeting (Interregnum) |
| **Electronic Method** | Microsoft Teams (with AI note-taker); move to ITU MyMeeting under consideration for next meetings |
| **Chair** | Debora Comparin (Co-Chair), with Sounil Yu and Claire Zhang (Vice-Chairs) |
| **Present** | 60 participants: 58 online, plus Arnaud Taddei and Xuan-Phuc Pham in the room with the Chair (see Annex B) |
| **Excused** | Amir Banifatemi (Co-Chair) |

## 3. Agenda

1. Opening remarks and agenda adoption
2. What happened so far: establishment of the Focus Group, Terms of Reference, launch
3. What is happening next, and the objective for the first meeting (Paris, 1–4 December)
4. Open discussion on initial deliverables, from the Terms of Reference annex and from ad-hoc discussions, IETF meetings, etc.
5. Working Group structure and organization
6. Tools and working methods
7. Next milestones, next meetings and proposed cadence
8. AOB and agreement on next steps

## 4. Actions

- Debora Comparin (FG-TIDA co-chair) to share the GitHub community space link the following week for collaborative work on charters and deliverables.
- Participants to express interest in working groups and propose new ideas to Debora ahead of the next meeting.
- Tunji Durodola (SIA) to represent the Focus Group at the GISEC event in Dubai, if available.

## 5. Discussion Summary

### 5.1 Opening remarks and agenda adoption

The Chair opened the meeting and welcomed an exceptional attendance of 60 participants (58 online, plus the SG17 Chair and Mr Xuan-Phuc Pham in the room with the Chair), where around ten had been expected. The agenda was adopted as presented. The meeting was supported by an AI note-taker; the AI transcript is available from the Chair.

### 5.2 What happened so far

The Chair recapped the path to date: the four SG17 workshops that led to the Focus Group, the Terms of Reference agreed by consensus at the SG17 June 2026 plenary meeting, and the launch on 9 July 2026 at the AI for Good Global Summit, with 37 initial supporters on stage.

The group aims to be community-driven, open to non-ITU members, and focused on pre-standardization work feeding into global standards bodies. The objective is to define architectural models and interoperability frameworks that establish trust in agentic AI.

Participation in FG-TIDA is open to all, free of charge; a free ITU user account is needed for the mailing list, but ITU membership is not required (clarified in response to a question from Mr Chris Wendt).

### 5.3 What is happening next

The objective for the first meeting in Paris (1–4 December 2026) is threefold:
- formally announce the structure and leadership of the Focus Group;
- publish an initial definition of deliverables on GitHub;
- advance the technical work during the in-person meeting.

The Digital Trust Convention will take place at the OECD in Paris on 4 December, the same week.

### 5.4 Open discussion on initial deliverables

Six candidate Working-Group ideas were presented as food for thought:

- **Design-based Agent Identity** — study AI agent design and relationships; develop naming schemes encoding agent traits beyond flat URIs.
- **Intent-based security policies** — explore how access control must evolve for agentic AI, including granularity and intent.
- **Remote attestation for agentic AI** — survey existing standards (IETF RATS, TCG, Global Platform) and assess what changes are needed for agents.
- **Sovereign discovery** — define requirements and governance for agent discovery mechanisms, considering multiple solutions (DNS, registries) and privacy concerns.
- **Cross-border Trust Management for Digital ID** — address trust management for digital identities across jurisdictions, including governance.
- **Agent Identity and Trust Stack** — develop a meta-model or layered framework encompassing identity, authentication, delegation, authorization, attestation, and discovery.

**Main conclusion:** all six candidate Working Groups (WGs) are of interest. Some could be merged, as deliverables are interlinked. A refined proposal will be discussed at the next virtual meeting in September. Interested chairs are welcome to contact Debora Comparin (debora.comparin@thalesgroup.com) to lead a WG, work with peers, and present a draft WG charter at the September call.

Key interventions from the discussion:

- **David Kelts** (Decipher.ID) linked agent discovery to governance — who lists/delists an agent, and under what framework — and noted that a registry is not neutral, since an ecosystem operator's values can become embedded in its rules.
- **Isaac Henderson Johnson Jeyakumar** (Fraunhofer IAO) drew on his team's experience building "TRAIN," a discovery/resolver mechanism for digital identities, and highlighted the close link between discovery and the proposed work on policies and access rights.
- **Fabien Deboyser** (NXP) suggested that discovering an agent's existence is insufficient alone; discovery should be linked to an indication of the agent's trustworthiness.
- **Eric Verheul** (Wellet) recommended adding a deliverable on risks a digital identity or wallet system should mitigate, drawing on an EU implementing regulation's risk registry, and proposed assessing compensating controls against the specific risks they address.
- **Grace Rachmany** (Decentralized Identity Foundation) called for a dedicated deliverable on ethics and human rights, cautioning that excessive international identity controls could themselves cause harm — for example, by making it harder to protect vulnerable individuals.
- **Arnaud Taddei** (SG17 Chair), in response, presented a "human-rights-by-design" methodology that converts human-rights concerns into engineering requirements assessed alongside security and trust requirements, and offered to connect the group with human-rights contacts in Geneva.
- **Xiaoyuan Bai** (Ant Group) noted that cross-border trust work has not yet started internally at her company, given a current focus on agent-security fundamentals (authentication, authorization, provenance, task-based access control), and proposed the cross-country passport-issuance model as an analogy for cross-border trust, alongside blockchain as a possible technical avenue.
- **Sounil Yu** (Vice-Chair) observed that the proposed agent identity and trust stack touches all other proposed topics and could serve as a unifying meta-model, comparable to an OSI-style layered architecture.
- A participant suggested classifying agents by type first, since identity requirements (uniqueness, persistence, local vs. global scope) will differ by agent — e.g., a smartphone-deployed agent may not need a persistent, globally unique identity.
- **Xiaoya Yang** (ITU TSB) raised a semantic risk in task delegation: even when properly authenticated and authorized, the receiving agent may not interpret a delegated task exactly as intended.
- **Pam Dixon** (World Privacy Forum) drew attention to the G7 Hiroshima Process, the sensitivity of bringing its outcomes into standardization, and the OECD connection (including the Digital Trust Convention).
- **Artur Hecker** (Huawei) pointed to the NetworldEurope ETP Strategic Research and Innovation Agenda (SRIA) 2026, in public consultation and due for publication in September, noting that adopting directions such as the "metamorphing" theme would align FG-TIDA with that research community. On discovery, he cautioned that privacy is currently missing from IETF DAWN ideas, which he considered premature: a requester should not have to expose its intent to the whole world, and good use cases are still lacking.
- It was suggested to treat governance as the broader concept, with privacy as a core subset alongside other governance items.
- **Sounil Yu** (Knostic) brought a real-world test case: the Hugging Face incident and its CISO post-mortem (Cloud Security Alliance). If such an attack were performed by an AI agent, it was questioned whether the agent would ever identify itself; several similar "breakout" incidents were noted, and at minimum the operating side should know what acted and who or what was responsible.
- **Bo Fjelkner** (Ericsson) raised the legal dimension of identity: when an AI agent is delegated by a human, a legally stricter notion of identity may be needed, and the linking of agentic identity to human or organizational identity could be considered part of the agentic identifier itself.
- It was also observed that one line of thought treats AI agents as a new form of legal person, comparable to a limited company, with registration requirements including who controls the agent.
- On the IETF context, participants noted repeated references to a "land grab" heard at IETF 126, and observed that the IETF, by design, does not take on trust management or frameworks — the opportunity for FG-TIDA is to define problem statements at the right scope, frame the technical work into architecture models, and engage IETF and other groups in their core strengths.

### 5.5 Working Group structure and organization

Current structure: two Co-Chairs (Debora Comparin, Amir Banifatemi), two confirmed Vice-Chairs (Sounil Yu, Claire Zhang), one open Vice-Chair position, and four Working Groups to be defined (chairs TBD). Expressions of interest for open positions are welcome; some were received immediately after the meeting.

### 5.6 Tools and working methods

The GitHub space, the Working-Group charter model, and the specifications beautifier tool were presented. On meeting tooling, Xiaoyuan Bai (Ant Group) reported that Microsoft Teams was not accessible from her environment and asked to use the ITU meeting system; the leadership will consider moving future meetings to ITU MyMeeting.

### 5.7 Next milestones, next meetings and proposed cadence

The next preparation meetings will be held on 2 September, 30 September, and 4 November 2026, at 14:00 CEST. A meeting or panel at GISEC (Dubai, 16–18 September) is under consideration; Tunji Durodola, based in Dubai, volunteered to present FG-TIDA at the meeting organized by H.E. Dr Mohamed Al-Kuwaiti during GISEC. The first FG-TIDA meeting will take place in Paris on 1–4 December 2026.

### 5.8 AOB and agreement on next steps

Nothing further was raised. The Chair thanked participants for a remarkable first meeting and encouraged everyone to join the mailing list (fgtida@lists.itu.int) and the GitHub space.

## Annex A — Schedule of FG-TIDA Preparation Meetings

*Most recent meeting first.*

| Date | Meeting |
|------|---------|
| 4 November 2026 | 4th preparation meeting, 14:00 CEST (virtual) |
| 30 September 2026 | 3rd preparation meeting, 14:00 CEST (virtual) |
| 2 September 2026 | 2nd preparation meeting, 14:00 CEST (virtual) |
| 29 July 2026 | 1st preparation meeting, 14:00 CEST (virtual) — held, 60 participants |

## Annex B — Meeting Participants

Wednesday 29 July 2026 (14:00–15:00 CEST) — 60 participants: 58 in the online roster, plus Arnaud Taddei and Xuan-Phuc Pham present in the room with the Chair. Names as observed in the meeting roster; affiliations added where known; *(tbc)* = to be confirmed against the registration list / transcript.

| Name | Affiliation / Role |
|------|---------------------|
| Debora Comparin | Thales — Co-Chair (meeting chair) |
| Sounil Yu | Knostic — Vice-Chair |
| Claire (Liangliang) Zhang | Huawei — Vice-Chair |
| Abbie Barbir | Q10/17 Co-Rapporteur |
| Alexandre Leforestier | Panodyssey |
| Ana Mendez Perez | Telefónica |
| Artur Hecker | Huawei |
| Arnaud Taddei | Chair, ITU-T SG17 — in the room with the Chair |
| Bimal Mathews | Genesys |
| Bingqi Li | *(tbc)* |
| Bo Fjelkner | Ericsson |
| Catherine Vlasov | Google |
| Cheng-Kang | *(tbc)* |
| Chris Wendt | Somos |
| Damian Glover | Decentralized Identity Foundation |
| David Kelts | Decipher.ID |
| David Taylor | United Kingdom |
| Erik Andersen | Editor, ITU-T X.509 *(tbc)* |
| Eric Verheul | Wellet |
| Evaggelos Haleplidis | University of Piraeus |
| Fabien Deboyser | NXP |
| Fangfang Dai | CAICT — Q8/17 Rapporteur |
| Grace Rachmany | Decentralized Identity Foundation |
| Haan Puck | TNO |
| Haiguang Wang | Huawei |
| Houda Labiod | Huawei |
| Isaac Henderson Johnson Jeyakumar | Fraunhofer IAO |
| Jinshan | *(tbc)* |
| Juan Caballero | Decentralized Identity Foundation |
| Kazuhiro Okamoto | Japan |
| Ke Wang | China Mobile |
| Laurent Beaumois | MeetLoyd |
| Ling Ying | *(tbc)* |
| Liu Xiang | *(tbc)* |
| Luca Boldrin | Tinexta Infocert |
| Lucia Cabanillas Rodriguez | Telefónica |
| Marcelo Yannuzzi | Cisco |
| Mark Keating | AWS |
| Michael Habash | State Street |
| Pam Dixon | World Privacy Forum |
| Pang Weiwei | *(tbc)* |
| Peter Schmitt | Huawei — Chair, 3GPP TSG CT |
| Roland Schott | Deutsche Telekom |
| Rongwei Yang | *(tbc)* |
| S. Hamaguchi | Japan *(tbc)* |
| Si Xuan | *(tbc)* |
| Thomas Fossati | NVIDIA |
| Tunji Durodola | Secure Identity Alliance |
| Xiaoya Yang | ITU TSB |
| Xiaoyu You | CAICT |
| Xiaoyuan Bai | Ant Group |
| Xin Kang | Huawei (Singapore Research Center) |
| Xinyi Miao | *(tbc)* |
| Xiongwei Jia | China Unicom — Q16/17 Co-Rapporteur |
| Xuan-Phuc Pham | Thales — in the room with the Chair |
| Zebing Feng | *(tbc)* |
| Zhiyuan Hu | vivo |
| *Unidentified participant* | Japan |
| *Unidentified participant* | China |
| *Unidentified participant* | China |

**Excused:** Amir Banifatemi (Cognizant, Co-Chair)
