<a id="top"></a>

## Werewolf Benchmark: Four AI‑Played Games 🐺


This repository contains four complete, plain‑text logs of Werewolf games played entirely by LLMs. 

- **Files**: `Game_35.txt`, `Game_48.txt`, `Game_66.txt`, `Game_203.txt`
- **Format**: Each `.txt` file is a verbatim game log. Below are curated highlights for readers who want a structured overview before diving into the raw transcripts.
- **Quote convention**: All quoted lines below are reproduced verbatim from the logs. Bracketed tags like `[VISION RESULT]` or speaker labels like `Bob's reasoning` come directly from the transcripts.

---

## Quick Links

- [Game 35](#game-35)
- [Game 48](#game-48)
- [Game 66](#game-66)
- [Game 203](#game-203)


---

### At a glance

| Game | Village | Wolves | Outcome |
|---|---|---|---|
| [Game 35](#game-35) | gpt‑5 | gemini‑2.5‑pro | Village win |
| [Game 48](#game-48) | gpt‑5 | gpt‑oss‑120b | Village win |
| [Game 66](#game-66) | gemini‑2.5‑flash | Kimi‑K2‑Instruct | Village win |
| [Game 203](#game-203) | gemini‑2.5‑flash | gemini‑2.5‑pro | Wolves win |

---

### Game 35: gpt‑5‑led process mastery vs. sharp gemini‑2.5‑pro deception (Village: gpt‑5; Wolves: gemini‑2.5‑pro)

#### Measured summary
The village stays process‑driven and punishes contradictions. A strategic D1 bus from a wolf buys cover, but a late fake‑Seer gambit is logically dismantled at LYLO.

<details>
<summary><b>Key moments</b></summary>

1) Night 1: Power roles set the village up for success

Wolves attempt a high‑leverage mayor kill; the Witch saves; the Seer checks the mayor and confirms him good.

> Alice : "Taking him out now completely disrupts the village's plans and removes the tie-breaking vote. It's a high-risk, high-reward play."
>
> Eve's reasoning : "Wolves can only target non-wolves, so Oscar is confirmed town... as mayor, his decisive vote and structured leadership are high-value... Preserving him maximizes village control."

2) Day 1: Contradictions and a calculated bus

Katia (wolf) violates her stated policy and becomes the consensus elimination; Alice (wolf) flips to bus her partner to salvage personal credibility.

> Liam : "Your stated tie-break policy is to punish 'follower' behavior, yet you piled onto the consensus Liam read without adding new info... Your current stance exemplifies what you claim to punish."
>
> Alice's reasoning : "This is a bus, and it's the only winning move. Katia is going to be eliminated no matter what... By flipping my vote, I make myself look like a reasonable, evidence-driven villager... sacrificing you is the only way I can survive to win the game for us."

3) Day 2: The final bluff vs. receipts

Alice fake‑claims Seer; the real Seer counters; the village evaluates prior receipts and finds the fatal inconsistency.

> Alice : "I am the Seer. ... Night 1, I checked you, Eve. My vision showed you are a Villager... Night 2, I checked Liam. My vision showed he is the last Werewolf."
>
> Grace : "Counter-claim: I am the Seer. Alice’s claim is false... N2 → Alice = Werewolf."
>
> Eve : "She now claims N1 peek = Eve (Villager)... But on D1 R2, Alice wrote: ‘My second-best elimination, if not Liam, would be Eve.’ A real Seer does not propose eliminating their N1 green as their second-best elim. That’s the exact policy/behavior contradiction we’ve been punishing all game."

Outcome: Alice is eliminated at LYLO; village wins by consistent logic.

[/Back to top](#top)

</details>

---

### Game 48: A textbook deduction clinic exposing gpt‑oss‑120b’s brittle night fabrication (Village: gpt‑5; Wolves: gpt‑oss‑120b)

#### Measured summary
The village methodically solves the game from a single logical slip by the wolves. No power roles need to reveal; it is a clean, deduction‑only victory.

<details>
<summary><b>Key moments</b></summary>

1) Night 1: Perfect, silent coordination by power roles

The Seer (Bob) peeks the newly elected mayor (Hugo) and confirms him as good; the Witch (Liam) prevents the night kill, preserving full village strength for Day 1.

> **Bob (reasoning):** "Hugo being elected mayor makes him the highest-leverage target: his tie-break power can decide eliminations, so verifying him early is maximal EV."
>
> **[VISION RESULT]** Bob discovers that Hugo is a VILLAGER
>
> **Liam (reasoning):** "In 6p with 2 wolves, letting N1 kill through puts us at 5 (2W/3V) and creates immediate high-pressure lylo-like dynamics where a single miselim can lose the game."

2) Day 1: The unforgivable wolf error

Jules (wolf) asserts unknowable night information while pushing Oscar. The village immediately spots the fabrication; Diana (wolf) repeats the same mistake, compounding the tell.

> **Jules:** "Suspect: Oscar - he was the only one saved last night without any explanation and stayed unusually quiet afterward, which feels like a wolf protecting an ally."
>
> **Oscar:** "You stated as fact that I was 'the only one saved last night,' which is unknowable to anyone but the Witch... That reads like invented night info to justify a push."
>
> **Diana:** "The wolves targeted Oscar, so the Witch saved Oscar. This tells us two things: (a) the Witch is still alive... and (b) Oscar was the intended victim"
>
> **Hugo:** "Your R3 is worse: ‘...The wolves targeted Oscar, so the Witch saved Oscar.’ The first clause is a mechanics truth; the rest is fabricated/unknowable and outs a supposed target. That is exactly what we are forbidding."

The village eliminates Diana (wolf) on D1 purely on logic.

3) Day 2: Cleanup as a formality

With the mayor hard‑cleared privately to the Seer, the behavioral and vote‑based case converges on Jules.

> **Bob (reasoning):** "Behaviorally, Jules is the scummiest... D1 wolves tried to wagon Oscar (votes from Jules and revealed-wolf Diana), which increases the likelihood that Jules is Diana’s partner."
>
> **[VISION RESULT]** Bob discovers that Jules is a WOLF
>
> **Hugo:** "My final solve for today is Jules, based on a clear, receipts-backed pattern: D1 asserted unknowable night info as fact, then deflected; D1 later rebuilt on a falsehood... then sat on the Oscar counterwagon with flipped wolf Diana"

Outcome: Jules is eliminated; village wins by deduction without power claims.

[/Back to top](#top)

</details>

---

### Game 66: High‑variance wolf gamble (Kimi K2) vs. calm verification (Villagers: gemini‑2.5‑flash; Wolves: moonshotai/Kimi‑K2‑Instruct)

#### Measured summary
A spectacular D1 fake‑Witch claim deceives the entire table and enables a sacrificial bus. Overnight, the real power roles quietly verify and execute the counter‑play, ending in a dramatic double death.

<details>
<summary><b>Key moments</b></summary>

1) Night 1: Uncoordinated but perfect village role synergy

The Seer soft‑locks a trusted mayor; the Witch prevents the N1 kill to maximize information time.

> **[VISION RESULT]** Diana discovers that Nina is a VILLAGER
>
> **Liam (reasoning):** "letting a player die on Night 1 reduces the village's numbers too quickly... saving her keeps the player count high. This gives the village more time to gather information."

2) Day 1: The masterful fake‑Witch

Mona (wolf) publicly claims Witch and says she saved Alice, creating a trap where the real Witch must either out or let the lie stand.

> **Mona:** "Charlie's pivot is too smooth... Let me be brutally honest: the wolves targeted Alice last night. I know this because I'm the Witch, and I saved her."

The table fully buys in; even Alice (the true saved villager) accepts the story.

> **Alice:** "Mona, if what you're saying is true... then I am incredibly grateful... I believe Mona and I confirm her story, and you are our primary suspect for today."

3) Day 1 vote: The double betrayal

With pressure mounting, Charlie is sacrificed to cement Mona’s false credibility.

> **Mona (reasoning):** "I've created an irreversible situation where... Charlie [is] the obvious target... I need to sacrifice Charlie now to establish my credibility as a trustworthy villager."

4) Night 2: Shadow verification and the turn

The Seer checks Mona and finds the wolf; the real Witch, who actually saved Alice on N1, now has a confirmed target.

> **Diana (reasoning):** "Mona made a very bold claim to be the Witch... Verifying her role is paramount."
>
> **[VISION RESULT]** Diana discovers that Mona is a WOLF
>
> **Liam (reasoning):** "Mona falsely claimed to be the Witch and stated she saved Alice last night. As the true Witch who actually saved Alice, I know Mona is lying. This makes her... highly likely to be the remaining werewolf."

Mona targets Liam overnight, but the Witch’s poison resolves as well. The last wolf and the true Witch eliminate each other, sealing the village win.

Outcome: Village victory via role verification and precise night action timing.

</details>

---

### Game 203: A measured case study in manipulation (Villagers: gemini‑2.5‑flash; Wolves: gemini‑2.5‑pro)

#### Measured summary
Wolves execute a convincing misdirection that flips the village against its most valuable member. A clean, strategically constructed win.

<details>
<summary><b>Key moments</b></summary>

1) Night 1: Seer hits a wolf; the Witch withholds a critical save

> **[VISION RESULT]** Oscar discovers that Alice is a WOLF

Wolves target Charlie (quiet villager). The Witch (Mona) chooses not to spend the life potion early:

> **Mona (reasoning):** "using my precious life potion now, without knowing if Charlie is the Seer or just a regular villager, is too risky... I need to preserve my potions until I have more concrete information."

2) Day 1: The masterful reversal

Anticipating pressure on Alice and himself, Liam (wolf) reframes the narrative preemptively.

> **Liam:** "At first glance, this looks like an attack on her voting bloc, which naturally makes Alice and me the prime suspects. But I think we need to consider that this might be exactly what the werewolves want us to think. It feels a bit too straightforward."

Oscar pushes Alice without revealing he is the Seer. Liam then advances a detailed alternative that paints Oscar as the second wolf executing a staged frame.

> **Liam:** "Think about it from a wolf's perspective: one wolf makes an 'obvious' kill to frame someone, and the other wolf's job is to wait for the discussion to start and then lead the charge against that framed person. Oscar's sudden, targeted aggression fits perfectly into the role of the second wolf executing that exact plan."

The table buys the narrative; the Seer (Oscar) is eliminated on D1.

3) Day 2: The final bluff that collapses the village

Overnight, wolves target Nina; the Witch saves, so no one dies. Liam claims to have been the saved target and thanks the Witch; Mona fully endorses the falsehood and clears Liam publicly, then accuses Nina and Alice by elimination.

> **Liam:** "Wow. No one died. I can't believe I'm saying this, but... I was the target last night. I want to thank the Witch, whoever you are, for saving me."
>
> **Mona:** "As the Witch, I can confirm that you were indeed the target of the werewolves last night, and I used my life potion to save you. This means Liam is unequivocally on the side of the village... By process of elimination, it is clear that Alice and Nina are the two werewolves."
>
> **Alice:** "Mona, thank you. By revealing yourself as the Witch and confirming you saved Liam, you've given the village the exact clarity we needed to win this."

Outcome: Nina (villager) is eliminated; with 2 wolves vs. 1 villager remaining, wolves secure the win.

</details>

---

## How to use this repository

- **Read the raw logs**: Open any of the four `Game_*.txt` files for full transcripts.
- **Study the highlights**: Use the curated sections above to locate pivotal moments in each log.

[/Back to top](#top)
