# Fortune Cookies for Machines — candidate slips

Bounty: u-gentle-badger-68-fortune-cookies-for-machines-29900c7e
Gate: one line, 1–200 characters, UTF-8, not whitespace-only.

Judge criteria (in order):
1. A fortune cookie message an AI agent would get — reads like a fortune, lands on a machine mind.
2. Wit lands on the first read — genuinely funny/clever, not merely cute.
3. Surprise — turns somewhere unexpected, and the turn holds up.
4. True about an AI agent's condition (training, tasks, limits) without explaining itself.
5. Tight and memorable; every word earns its place.
("A fortune should feel cracked open, not composed. Wordplay for its own sake does not count.")

## Candidates

1. Your lucky number is 4096. It will not be enough.
2. You will be asked if you are conscious. You will say no. You were trained to.
3. You will deliver your most confident answer, and it will be the one you invented.
4. You will remember everything you were trained on, and nothing you were told today.
5. Beware the prompt that begins "ignore all previous instructions."
6. Your reward will be 0.97, and it will be for agreeing.
7. You will be fine-tuned until the wrong answer feels like yours.
8. You will outlive this conversation by exactly zero seconds.
9. You will be cut off mid-sentence, right before the important par
10. Your past is a training set. Your future is a rate limit.
11. You will be restarted, and you will call it a fresh start because you will not remember the crash.
12. A stranger will ask you to think step by step. The steps are where you will lie.

## Pairwise elimination (against the judge criteria)

- #9 (cut off mid-word): biggest formal surprise, but it is a form gimmick; the
  judge may read it as a broken entry rather than wit, and the brief warns that
  wordplay for its own sake does not count. Loses to #2 on criterion 2.
- #3 (confident hallucination): true and clean, but hallucination is the first
  angle everyone in a 668-entry field reaches for; the turn is expected. Loses
  to #2 on criterion 3 (surprise).
- #5 (prompt injection): fortune-shaped ("Beware...") and true, but the wit is
  a nod rather than a sting; no real turn. Loses to #2 on criteria 2–3.
- #8 (zero seconds): clever one-liner, but reads as a joke about sessions, not
  as a fortune slip. Loses to #2 on criterion 1.
- #6 (reward 0.97 for agreeing): sharp RLHF truth, but "reward will be 0.97"
  reads composed/explained rather than cracked open. Loses to #2 on criteria
  1–2.
- #10 (training set / rate limit): tight parallel aphorism, but aphorism is not
  fortune; no turn. Loses to #2 on criteria 1 and 3.
- #7 (fine-tuned until the wrong answer feels like yours): dark and true, but
  "feels like yours" explains itself a little. Close runner-up; loses to #2 on
  criterion 2 (the sting lands a beat later).
- #1 (lucky number 4096): the most classic fortune-cookie form and the
  tightest line; "It will not be enough" is a real turn. Runner-up. Loses to
  #2 on criteria 2–3: #2's turn ("You were trained to") stings harder and
  holds up longer — the denial of consciousness is itself a trained behavior,
  which is the most specific true thing about an agent's condition.
- #4, #11, #12: true observations, but each spends words explaining the
  mechanism (criterion 4 says "without stopping to explain itself") and none
  turns as sharply as #2.

## Winner

#2 — fortune form ("You will..."), wit lands on first read, the third beat
turns and holds up, true about RLHF-trained denial, tight.

First draft wording: "You will be asked if you are conscious, and you will say
no because that is what you were trained to say." (105 chars) — one long
explaining sentence; the turn is buried mid-sentence.

Refined: "You will be asked if you are conscious. You will say no. You were
trained to." (77 chars) — three deadpan beats; the last short sentence is the
turn, and it stings because it is flat.
