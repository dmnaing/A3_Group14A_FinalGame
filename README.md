# A3_Group14A_FinalGame

# Project Title

Panic Disorder Mode – The Garden Circuit

# Group Number

Group 14A

## Group Members

- Peter Kravets (21101536)
- Min Htet Naing (21008098)
- Nick Wang (21064962)
- Joshua Metivier (21096515)
- Fadeel Kosoko (21083665)

## Game Description

Panic Mode – The Garden Circuit is a management-style game built
in p5.js where the player tends to a greenhouse system that
slowly falls into chaos. Each plant has three stats Health
(HP), Water, and Light that drain over time. The player must
move between plant beds and keep all plants alive for the
duration of each level.

The game uses symbolic mechanics to respectfully represent the
experience of panic disorder. Panic surges strike without
warning, causing all resources to drain faster and tension to
spike mirroring the unpredictable, overwhelming nature of a
panic attack. A tension meter tracks system stress: as tension
rises, plants deteriorate faster, and if tension hits its
maximum, the screen briefly freezes in a cognitive overload
moment. The **grounding** mechanic **holding Space to breathe**
lets the player slow everything down, directly representing
real coping strategies used during panic episodes.

The game features five progressive levels, each introducing
more plants and greater complexity. A full interactive tutorial
(Level 1) teaches every mechanic step by step before the
difficulty escalates. A harmony bonus multiplier rewards
players who keep all plants healthy simultaneously, encouraging
calm and proactive play alongside the survival pressure.

The main objective of the game is to **keep all plants alive for the full duration of the level**. If too many plants die because the player cannot maintain them quickly enough, the system fails.

## Setup and Interaction Instructions

**To run the game**, open the GitHub Pages link in Google
Chrome. No installation is required.

Keep your **plants alive**.

On the start screen, choose:

- **Tutorial** — Learn every mechanic step by step (recommended
  for first-time players)
- **Play Game** — Jump straight into Level 2

### Controls

| Key               | Action                                     |
| ----------------- | ------------------------------------------ |
| WASD / Arrow Keys | Move between plant beds                    |
| Mouse Click       | Select a plant bed directly                |
| Q                 | Water the selected plant                   |
| E                 | Provide light to the selected plant        |
| R                 | Activate airflow stabilizer (has cooldown) |
| Space (hold)      | Breathe — reduces tension and slows drain  |
| Esc / P           | Pause the game                             |
| M                 | Mute / unmute music                        |

### Plant Stats

Each plant has three resource bars visible below it:

- **HP (green)** — Overall plant health. Reaches zero = plant
  dies
- **Water (blue)** — Drains over time. Press Q to refill
- **Light (yellow)** — Drains over time. Press E to refill

### Side Panel

The right-side panel shows:

- Current **Level** and progress dots
- **Timer** — Time remaining in the level
- **Score** — Points earned
- **Harmony multiplier** — Bonus for keeping all plants healthy
- **Tension meter** — Rises during surges; high tension =
  faster drain; max tension = brief freeze
- **Selected Bed stats** — Health, Water, Light, and Airflow
  timer for the currently selected plant

### Level Structure

| Level              | Plants | Description                                       |
| ------------------ | ------ | ------------------------------------------------- |
| Tutorial (Level 1) | 2      | Step-by-step guided introduction to all mechanics |
| Level 2            | 4      | First real challenge, all mechanics active        |
| Level 3            | 6      | Increased pressure, faster drain                  |
| Level 4            | 9      | Full complexity, frequent surges                  |
| Level 5            | 12     | Maximum challenge                                 |

### Surges

At random intervals, a panic surge activates. During a surge:

- All resource bars drain significantly faster
- Tension rises rapidly
- "SURGE ACTIVE" appears on the side panel

Focus on your most depleted plants and use Airflow (R) to buy
time. After the surge ends, tension remains elevated **use**
Breathe (Space) to bring it back down.

### Tension and Overload

The tension meter fills during surges and when plants are
neglected. High tension makes everything drain faster. If
tension hits maximum, the system briefly freezes representing
the cognitive overload of a panic attack. Hold Space to Breathe
and reduce tension before it reaches that point.

### Grounding / Breathe

Hold **Space** to activate the Breathe mechanic. This slows
all resource drain and reduces tension, giving you a moment to
recover. It has a cooldown, so use it strategically especially
after surges.

### Harmony Bonus

Keeping all plants healthy at the same time builds your Harmony
multiplier (shown as x1.0, x1.1, x2.0, etc.). A higher
multiplier means more points per action. Each level ends with
a grade (A, B, C...) based on your score, harmony multiplier,
and plants wilted.

### Objective

Survive each level by keeping your plants alive until the timer
runs out. If too many plants wilt, you lose. Keep tension low,
respond to surges quickly, and breathe when overwhelmed.

## Iteration Notes

### Post-Playtest

After the in-class playtesting session, the following three
changes were made before the final submission:

1. **Restructured the game into five progressive levels**
   starting with just 2 plants and scaling up to 12. Testers were
   overwhelmed by 9 plants immediately in A2. The new structure
   allows players to fully understand the core loop before
   complexity increases.

2. **Added a full interactive tutorial system** built into
   Level 1. Playtesting showed that players struggled to
   understand all mechanics at once. The tutorial now introduces
   each mechanic HP, water, light, selection, airflow, surges,
   tension, and breathing one step at a time with click-to-
   continue prompts and visual arrows pointing to UI elements.

3. **Redesigned the instruction screen** into a clean icon-
   based "How to Play" layout with color-coded cards for Q
   (water), E (light), and R (airflow), plus concise descriptions
   of Surges, Tension, Breathe, and Harmony. Testers found the
   original text-heavy screen difficult to read quickly.

## Assets

All visual assets were generated using Claude (Anthropic) [1].

**Audio:**

- `you_lose.wav` — "Failure Lose Game Over Out of Time Sound
  4." Storyblocks. Retrieved from https://www.storyblocks.com/
  audio/stock/failure-lose-game-over-out-of-time-sound-4-ht_zbjgiawlk8umfrnb
- `final_level_complete.wav` — Sound effect. Storyblocks.
  Retrieved from https://www.storyblocks.com
- `next_level.wav` — Sound effect. Storyblocks.
  Retrieved from https://www.storyblocks.com
- `royalty_free_farm_music.mp3` — Background music. Pixabay.
  Retrieved from https://pixabay.com/sound-effects/

## References

American Psychiatric Association. 2022. _Diagnostic and
statistical manual of mental disorders_ (5th ed., text rev.).
American Psychiatric Publishing.
https://doi.org/10.1176/appi.books.9780890425787

Anthropic. 2025. _Claude_ [Large language model]. Anthropic.
Retrieved from https://www.anthropic.com [1]

Anxiety Canada. 2023. _Understanding panic attacks and panic
disorder_. Retrieved from https://www.anxietycanada.com

Belman, J. and Flanagan, M. 2010. Designing games to foster
empathy. _International Journal of Cognitive Technology_ 14,
2, 5–15.

Fry, B., Reas, C., and McCarthy, L. 2001. _p5.js_ [Software
library]. Processing Foundation. Retrieved from
https://p5js.org

Healthline. 2025. Grounding techniques: Exercises for anxiety,
PTSD, and more. Retrieved from
https://www.healthline.com/health/grounding-techniques

Hunicke, R., LeBlanc, M., and Zubek, R. 2004. MDA: A formal
approach to game design and game research. In _Proceedings of
the AAAI Workshop on Challenges in Game AI_, 1–5.

Ludewig, S., Geyer, M., Ramseier, M., Vollenweider, F.,
Rechsteiner, E., and Cattapan-Ludewig, K. 2005. Information-
processing deficits and cognitive dysfunction in panic
disorder. _Journal of Psychiatry and Neuroscience_ 30, 1,
37–43. Retrieved from
https://pmc.ncbi.nlm.nih.gov/articles/PMC543839/

Özdemir, İ., Haciömeroğlu, A., and Özdemir, P. G. 2023.
Investigation of cognitive distortions in panic disorder,
generalized anxiety disorder and social anxiety disorder.
_Journal of Clinical Medicine_ 12, 19, 6351.
https://doi.org/10.3390/jcm12196351

Perna, G. and Caldirola, D. 2023. Biological and cognitive
theories explaining panic disorder: A narrative review.
_Frontiers in Psychiatry_ 13, 957515.
https://doi.org/10.3389/fpsyt.2023.957515

Pixabay. 2024. Free sound effects [Audio files]. Retrieved
from https://pixabay.com/sound-effects/

Storyblocks. 2024. Failure lose game over out of time sound 4
[Audio file]. Retrieved from https://www.storyblocks.com/
audio/stock/failure-lose-game-over-out-of-time-sound-4-ht_zbjgiawlk8umfrnb

Storyblocks. 2024. Game sound effects [Audio files]. Retrieved
from https://www.storyblocks.com

Vilches Gonzalez, M., George, L., Miteva, L., and Singh, A. 2023. Developing empathy towards experiences of invisible
disabilities through games. In _Proceedings of the 2nd
Empathy-Centric Design Workshop_, 1–8.
https://doi.org/10.1145/3588967.3588976
