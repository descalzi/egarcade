# Grinstead Arcade: review notes

Feedback on `GAME_PLAN.md` and the art in `art/`, 25 November 2026. It includes the decisions Martin has made since the first review.

## Decisions so far

- **Single player.** The two heroes are a choice between a woman and a man. There is no simultaneous co-op.
- **No real people as enemies.** Every enemy is a zombie or a decoration brought to life.
- **Beaten zombies disappear.** They fall, flash and vanish like in a classic arcade game. They do not turn back into shoppers, so anything moving on the pavement is always an enemy.
- **Faithful shopfronts.** Reproduce the local shops as accurately as possible and change only their names slightly.
- **Art style.** Use the richer "HD pixel art" look of the concept images, not a sparse early-1990s look.

## What's working

- Real High Street landmarks behind friendly renamed signs make a strong local hook. The Tree Frog window reveal is a specific and memorable finale.
- The scope is sensible: three stages and three bosses, with a well-chosen first playable slice outside Benchy Cafe.
- Controls and scoring are already concrete: hearts, presents, the gold present, mince pies and the restart rules. Both heroes play identically, which keeps balancing simple.
- Each boss has a readable pattern: it shows a tell, then you punish it.
- The mood in the art works well (blue dusk with warm shop windows), and the heroes' rust and teal colours tell them apart at a glance. The Dorset Oak and Treetop Frog concepts are faithful to the photos.

## Still open

- **The countdown.** It "frames the story", but the plan also says players can take their time. Decide whether it is a real timer or only a cutscene beat, and write that down.
- **Why the shoppers are zombies.** Nothing yet links them to the Disco King. One simple answer is that his disco spell turned them.
- **Target play length** for the episode, and roughly how long each stage should take.
- **Tech choices.** Phaser 3 is a good fit for a browser brawler.
- **Unplaced landmarks.** Heath & Bloom and Flint & Feather are in the landmarks table but have no photos and aren't placed in any stage. Flint & Feather is the natural place for the gingerbread men to appear.
- **Repo housekeeping.** Two pairs of reference files have swapped names. `22-high-street.webp` shows 61 High St and vice versa, and `dorset-arms.webp` shows Tree Frog and vice versa. Also, the repo is public and the references are Google Street View screenshots, so your own photos would be safer long term. You need those photos for tracing anyway (see below).

## Enemies

Every enemy type behaves differently, so the fights stay fresh across three stages.

| Enemy | Stages | Behaviour | What it teaches |
| --- | --- | --- | --- |
| **Shopper zombies** | All | Slow; grab you if you stand still. Knocked down, they flash and disappear. | The basic combo and keeping moving |
| **Gingerbread men** (escaped from Flint & Feather) | 1 onwards | Small and fast, come in groups, crumble in one hit | Crowd control |
| **Toy soldiers** (marching out of shop windows) | 2 | Advance in a line and jab with their bayonets | Sidestepping and flanking |
| **Snowmen** | 2 | Stay back and throw snowballs | Closing the distance while dodging |
| **Mannequin dancers** (the Disco King's crew) | 3 | Block while posing; open to hits as they change pose | Timing, and a preview of the final boss |

Everything is a Christmas decoration or shop dummy come to life, which ties the enemies to the Nutcracker and Disco King bosses. The finale crowd stays as its own scene and isn't made of beaten enemies.

## Art spec

- **Native resolution of 480×270**, scaled up 4× to 1920×1080 with crisp nearest-neighbour scaling. Your combat concept shrunk to 480×270 with 128 colours looks almost identical to the original ([art/mockups/your-concept-at-480x270.png](art/mockups/your-concept-at-480x270.png)), so this resolution keeps the look you want.
- **Heroes about 60px tall.** Enemies are similar, and bosses are larger.
- **About 128 colours per scene**, with a small fixed palette per character so the sprites stay consistent.
- **Pavement depth.** The walkable pavement should fill about the bottom third of the screen so there's room to move up and down. In the current concepts it's a thin strip, which matters more than sprite size.
- **Keep attacks readable.** Keep bright, busy detail (such as lit bookshelves) out of the band where the heroes fight, or darken it a little.
- **Consistency.** Fix one version of each building, the weather (snow or no snow) and each hero's outfit. The concepts currently differ on all three.

## Making the shopfronts accurate

1. Take your own straight-on photos of each shop, ideally at dusk and on the same day.
2. Correct the perspective and scale each photo so one storey is about 90px at native resolution. That fits two storeys above the pavement and keeps the heroes in proportion.
3. Draw the pixel art over the photo. Window counts, arches, awnings, timber patterns, columns and proportions all come from the photo. Only the name on the sign changes.
4. Make each shopfront its own piece, so the street can be put together in a level editor (such as Tiled) and buildings can be reused or redressed for the Dunnings episode.

## Production notes

- **Backgrounds** are cheap in this style: each shopfront is one painted image, so detail and lighting cost little.
- **Sprites** are the expensive part, because the shading has to be redrawn in every frame. A hero needs roughly 40 to 60 frames (idle, walk, punch combo, jump kick, hurt, knockdown, victory) and each enemy 20 to 30. That's about 2 to 3 times the work of a simpler style.
- **AI concept images** are great for mood and as a base to paint backgrounds over. They can't be used directly as sprites, because they have no true pixel grid and won't stay consistent from frame to frame.
- **Recommendation:** keep the full concept style for backgrounds, and give the character sprites slightly fewer shading tones so they stay affordable to animate. Budget for a pixel artist for the sprites, using a tool like Aseprite.

## Suggested next steps

1. Settle the countdown and the zombie premise, and set a target play length.
2. Fix the swapped filenames and take your own reference photos.
3. Make one style-guide frame at 480×270: the Benchy Cafe screen with the correct pavement depth and both heroes at final size.
4. Build the first playable slice as planned, using placeholder sprites, so the combat feel can be tuned early.
