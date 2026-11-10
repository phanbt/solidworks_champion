# Who is the SOLIDWORKS Champion?

A quiz-show style game to help engineers learn SOLIDWORKS and 3DEXPERIENCE.

- 50 questions in the bank (17 easy, 17 medium, 16 hard). Each game draws 20: 7 easy, 7 medium, then 6 hard.
- Enter your name to start. A **Restart game** button (click twice to confirm) starts a fresh round at any time.
- Four answers per question, shuffled every game. A correct answer earns the points on that step of the ladder; a wrong answer earns 0 and the game continues.
- Two lifelines, each usable once per game: **50:50** removes two wrong answers, **Call the expert** suggests an answer (usually, but not always, right).
- Each answer shows a short explanation.
- The end screen summarizes the player's points by level (easy, medium, hard) against the 187,350 points available. Reaching **80% of the total points (149,880)** earns the title **SOLIDWORKS Champion**; otherwise the player gets a rank and a review list of missed questions.
- Keyboard: A–D to pick an answer, Enter to confirm or continue.

## Run it

Open `index.html` in any modern web browser. No installation needed.

## Editing questions

Questions live in the `BANK` array at the top of the `<script>` section in `index.html`. Each entry has `d` (difficulty 1–3), `q` (question), `a` (answers, the first one is correct) and `x` (explanation).

© PHAN Bá Thông aka Grandpa
