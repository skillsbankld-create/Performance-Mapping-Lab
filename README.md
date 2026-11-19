# Performance Mapping Lab (Activity 4): a card game for groups

One HTML file, English and Arabic (RTL), official Skills Bank palette and logo. Your 10 scenarios (text verbatim) become a hand of real cards: **pick a card, stamp the risk (Q or P), place it on the Efficiency × Effectiveness matrix**. Q = Quality Risk, P = Productivity Risk.

## How a group plays
1. Players type a name, enter the session code and pick a **group** (1 to 6; 3-5 people per group). All members of a group share one live board from their own devices (or one person drives while the group talks). Groups never see each other.
2. The trainer chooses a time and presses **START ROUND**: every group sees 3-2-1 at the same moment and the face-down deck turns over. A timer counts down; the boards lock when the time is up.
3. For each card: read the scenario card, **stamp** it (**Q** quality risk, **P** productivity risk, **Q+P** both, or **No risk**), then **place** it in its quadrant (tap "Place card here" or drag the card). The stamp comes first. The group can **lock its board** when all ten are done.
4. The trainer presses **REVEAL RESULTS**: each group gets its score (150 max), a title, the leaderboard, and the model answer for every card. Then each group writes the leadership principles that achieve and sustain High Effectiveness and High Efficiency.
Scoring: 10 points for the right quadrant, up to 5 for the right stamp (2 if partly right). Titles: Rising Analyst, Sharp Analyst, Efficiency Expert (90+), Performance Architect (120+). Card 2 accepts one quadrant; card 8 accepts two (your debate note). Without a session code a single device plays alone and can check its own answers.

## Trainer dashboard (code 2026)
Round control (time, start, end), live groups (members, cards done, lock, mini-matrix with stamps), **Model answers for every card** (best quadrant, best stamp, why, how to move it, and your facilitator note), leaderboard, consensus table (how many groups chose each quadrant, "groups differ" flag), the groups' principles, projector view (group matrices, where groups differ, scenario + model answer, leaderboard, principles) and CSV export.

## Model answers (quadrant, best stamp)
| Card | Quadrant | Stamp |
| --- | --- | --- |
| 1 Monthly Management Report | Inefficient & Effective | P |
| 2 Rapid Customer Response Team (debate) | Efficient & Ineffective | Q+P |
| 3 Weekly Coordination Meeting | Efficient & Ineffective | Q |
| 4 Quality Review Process | Inefficient & Effective | P |
| 5 Automated Invoice Process | Efficient & Effective | No risk |
| 6 Executive Dashboard | Efficient & Ineffective | Q |
| 7 Client Proposal Team | Inefficient & Effective | P |
| 8 Process Improvement Initiative (debate) | Efficient & Ineffective (or Inefficient & Ineffective) | Q |
| 9 Order Fulfilment Team | Inefficient & Ineffective | Q+P |
| 10 High-Performing Service Desk | Efficient & Effective | No risk |

## Please check
1. The **quadrants and the facilitator notes** come from your scenario file. The **best stamps, the "why" and "move it" lines, the icons, the scoring and the titles** were written for this tool: please review them (the stamp answers especially, cards 2, 3, 6, 8 and 9).
2. The Arabic text of the cards and the model answers is my translation: please have it reviewed.
3. Tested with simulated devices and a test relay (two groups, several devices per group), not on real phones or the live ntfy.sh relay. The public relay is not confidential: fictional scenarios only.

## Publish (GitHub Pages)
Upload `index.html` and `.nojekyll` to the repo root; Settings > Pages > Deploy from branch. Open the published address, not a preview viewer.
