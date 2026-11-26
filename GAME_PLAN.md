# Grinstead Arcade

## Game plan

**Grinstead Arcade** is a series of original, browser-based 16-bit arcade brawlers set in East Grinstead, West Sussex. The hook is a recognisable High Street and stories built around real local events. The first complete episode is **East Grinstead: The Big Reveal**. A future episode could take the same two heroes to the Dunnings music festival. The game is single-player, with a choice of hero at the start.

Launch the first episode straight from its title screen into character selection. Add a Choose a Story screen once a second episode exists. Share movement, combat, characters and reusable scenery across episodes, with separate stage layouts, objectives, music, bosses and endings. A possible address is `grinsteadarcade.co.uk/big-reveal`. Domain availability is open.

## The Big Reveal

On the evening of the Christmas lights and shop-window reveal, the Disco Diva, a disco mannequin come to life, takes the fuse from the event's lighting control box. The Christmas lights go out, and her spell animates the window displays, including zombie figures dressed as Christmas shoppers. An event volunteer at Benchy Cafe hands the chosen hero a spare fuse. Get it to the control box by the finale shop and bring the reveal back on.

| Stage | Route and encounters | Boss |
| --- | --- | --- |
| **1. The Blackout** | Start at Benchy Cafe, between Farthing & Co. and The Book Nook. An easy pavement present, a ledge present and a breakable crate introduce the controls. Meet one Christmas-shopping zombie, then two approaching from opposite sides. | **The Nutcracker**, an oversized wooden window decoration. Its shadow shows where it will land. The leap targets the player’s position at takeoff, leaving time to dodge and counter. |
| **2. Window Shopping** | Continue past the Tudor façades. Larger groups of the same shuffling zombies emerge from doorways and passages. The Dorset Oak's real carriage passage fits an encounter. | **The Last-Minute Shopper**, an oversized zombie with armfuls of shopping bags. Dodge the low swing or overhead slam, then counter while he recovers. On defeat his bags split and he saves one present. |
| **3. One Last Number** | A short zombie encounter on the approach to The Treetop Frog. The crowd waits outside and the shop's three display bays stay completely covered. | **The Disco Diva** rolls two mirror balls before taking a breather. Sidestep or jump each ball. On defeat she slips, spins and takes a seated bow. A giant mirror ball drops in a burst of glitter and stays lodged in the pavement through the reveal. Fit the spare fuse and use the reveal switch. |

Aim for **10–15 minutes** on a first clear. Start with roughly 3–4 minutes at Benchy Cafe, 4–6 minutes on Tudor High Street and 3–5 minutes for the final approach, boss and reveal. Use playtests to tune these ranges.

After the player fits the fuse and hits the switch, the crowd starts a short countdown. On zero, the lights come on, the covers slowly lower across all three window bays and the first beat of an original ’70s disco track lands. The DJ appears in the middle bay with one dancer on either side. The townsfolk dance in the street and the score appears after the scene has had time to play. The countdown is a finale cue with no gameplay time limit.

## Enemies

All enemies are fictional zombies or animated decorations and shop dummies. Beaten zombies fall, flash and vanish. Keep townsfolk in the finale scene, outside combat.

| Enemy | Placement and role |
| --- | --- |
| **Shopper zombies** | All three stages. Slow enemies with a close-range grab. The Benchy Cafe slice uses these to teach the basic combo and lane movement. |
| **Gingerbread figures** | First extra enemy to try, outside Flint & Feather once its route position is confirmed. They rush in groups and crumble in one hit. |
| **Mannequin dancers** | Proposed for Stage 3. They block while posing and leave an opening when changing poses, previewing the Disco Diva’s timing. |
| **Toy soldiers and snowmen** | Revisit after playtesting the slice. Soldiers could march and jab in formation to encourage flanking. Snowmen could throw snowballs to teach closing the distance. |

## Controls and scoring

- **Move** along the street and across the depth of the pavement. Side-stepping is the basic dodge.
- **Attack** on the ground for a short punch sequence ending in a kick. Use the same button to break crates and bins.
- **Jump** to reach high presents. Attack once in the air for a forward kick that knocks a zombie back. Ground attacks are enough to clear every encounter.
- Choose between **Lizzy**, in a rust shearling jacket and tan boots with a ponytail, and **George**, in a teal winter jacket and red scarf. Both share identical speed, jump, attack reach, timing, health and story.
- Start with **five health segments**. A landed hit takes one segment, followed by a brief invulnerability window. Health carries across stages. At zero, Game Over offers a stage restart at full health with its entry score, or an exit to the title screen.
- Wrapped presents are worth **100 points**. Place them on the pavement, on reachable ledges and in breakables. One optional gold present per stage is worth **300 points**. Both heroes squat for presents collected from a standing position. The present gives off sparks and shows its point value at the pickup spot.
- A few solid street props can hide higher-value prizes. Repeated kicks make one collectible drop from a prop, while the prop stays in place. Use subtle hit feedback to reward curiosity without telegraphing the hiding spot.
- Mince pies restore **one health segment**. Place them at fixed spots and leave them available at full health. The hero squats to collect a pie, then gains a brief mint glow. A segmented health bar and amber pixel score sit directly over the play area.

## Art and locations

Use the rich HD pixel-art look of the concepts, with crisp silhouettes, blue winter dusk, warm shop windows and no settled snow. Keep the hero outfits and building designs consistent across scenes.

- Start with a **480×270 native canvas** and nearest-neighbour scaling, including 4× at 1920×1080. Test heroes around **60 pixels tall**, enemies at a comparable scale and larger bosses. Use roughly **128 colours per scene** as a guide, with a small fixed palette per character.
- Give the walkable pavement roughly the **bottom third of the frame**. Use grounded shadows to show depth and soften busy background detail in the combat band.
- Take straight-on reference photos where possible, ideally in consistent dusk light. Correct perspective and try about 90 pixels per storey as a starting scale. Draw each frontage as a reusable piece, preserving windows, arches, awnings, timberwork and relative proportions while making small changes to shop names.
- Use concept images for mood and pose reference. Draw and align dedicated production sprites on a consistent pixel grid, with matching animation timing for both heroes. Budget roughly 40–60 frames per hero and 20–30 per regular enemy as early estimates. Use fewer shading tones for sprites to keep the animation workload manageable. Aseprite is a candidate for sprite production.

| Real landmark | Working in-game sign | Details to carry forward |
| --- | --- | --- |
| Bench RH19 | **Benchy Cafe** | Gabled dormer, projecting bay, curved timber braces, cream fascia and red chairs. |
| The Bookshop | **The Book Nook** | Immediately right of Benchy, with a broad low tiled roof and long book-filled display windows. |
| Penny Farthing Jewellers | **Farthing & Co. Jewellers** | Immediately left of Benchy, with a small penny-farthing emblem as a sign idea. |
| Heath Botanicals | **Heath & Bloom** | Plants in the window and a planter that could double as a pickup ledge. Confirm its route position from new references. |
| Flint Owl Bakery | **Flint & Feather Bakery** | Owl motif and a natural place for a mince-pie pickup and the gingerbread encounter. Confirm its route position from new references. |
| The Dorset Arms | **The Dorset Oak** | Long pale frontage, four dormers, left carriage passage and the photo's low entrance canopy. |
| Emma Louise | **Emma & Lou Interiors** | Lifestyle and interiors shop. Keep the narrow white gable with black trim, small window high in the gable, projecting black bay and recessed entrance between display windows. The red pillar box and pavement steps help place it on the street. |
| Tree Frog | **The Treetop Frog** | Three arched display panes, scalloped awning, recessed side entrance, brick steps and column. |
| Tudor stretch near 61 High Street | **Tudor High Street** | Broad tiled roof, irregular beams, projecting windows and recessed wooden gateway. |
| The Menders | **The Sole Menders** | Shoe-repair shop beside the Tudor row. Keep the black fascia with gold lettering, the broad repair-shop window, the diamond-leaded upper windows and the two low dormers in the slate roof. |
| Brick frontage near 64 High Street | | Red brick, three gabled dormers, white sash windows and a central black door above stone steps. Keep it between the timbered row and the Dorset Oak's carriage passage. |
| East Grinstead war memorial | **War Memorial** | Cross-topped stone column on a stepped base with dark plaques and iron railings. Keep the flagpoles, curved flower beds and brick approach, with the sports shop behind and to the left. |
| Herbert Sports | **Herbie’s Sports** | Black-and-white timbered upper floor under a long tiled roof with small dormers, pale shop signs above wide display windows and a covered passage to the right. |
| Sackville College | **Sackville College** | Long stone frontage set back behind a lawn and low hedge, with tall chimneys, a central arched entrance, a path across the lawn and benches beside the pavement. |

For the street expansion, use the 61 and 64 High Street views together to match the roofline and the transition from timber to brick and then to the pale pub frontage. Treat the latest view of 61 as a second angle on the existing Tudor segment. Use Sackville College as the point where the street opens up, with a wider view across the garden and a bare tree framing the scene.

The current Google Street View captures are temporary architectural references. Replace them with original photos as they become available, starting with Benchy Cafe and its neighbours. Capture Heath Botanicals and Flint Owl Bakery before placing them on the route. Use the Dorset Arms photo’s low canopy for the pub’s production frontage.

| Street references | Concept studies |
| --- | --- |
| [22 High Street](art/references/22-high-street.webp) | [Benchy opening](art/concepts/benchy-opening.png) |
| [61 High Street](art/references/61-high-street.webp) | [Pub and finale](art/concepts/pub-and-finale.png) |
| [The Dorset Arms](art/references/dorset-arms.webp) | [Winter duo and poses](art/concepts/winter-duo.png) |
| [Tree Frog](art/references/tree-frog.webp) | [Combat at street scale](art/concepts/combat-scale.png) |
| | [480×270 palette and scale test](art/mockups/your-concept-at-480x270.png) |

## Episode playtest

[Play The Big Reveal](https://descalzi.github.io/egarcade/play/) or download [the self-contained game](docs/play/index.html) and open it in a browser. The playtest covers all three stages in eight connected screens, from Benchy Cafe past Emma & Lou Interiors and the memorial, through Tudor High Street, Georgian Row and the Dorset Oak, then from Sackville College to the Treetop Frog. Clear each encounter and head right to the next screen.

The Nutcracker jumps to the player’s position at takeoff and telegraphs the landing with its shadow, the Last-Minute Shopper swings shopping bags, and the Disco Diva rolls mirror balls. Each boss has a dedicated fight theme, a defeat sequence, and a stage-clear fanfare. Heal with mince pies along the way. Health and score carry forward. Restarting from Game Over returns you to the current stage entry with five segments and its entry score. The last encounter ends with the fuse, the lighting switch, the countdown and the live window display. The browser synthesizes the music, including an arcade arrangement of Dance of the Sugar Plum Fairy and a separate disco track for the reveal.

The playtest uses Canvas 2D, a fixed camera per screen, and first-pass pixel art for the new street sections, bosses and performers. The [Benchy Cafe style frame](art/mockups/benchy-cafe-style-frame.png) remains the art target for the episode. Check scene readability and landmark resemblance before refining the new artwork. On touch devices, the game uses the landscape view and overlaid joystick and buttons. The game uses CC0 impact and smoke effects from the [external assets](ExternalAssets/) under the [supplied licence notice](ExternalAssets/public-license.pdf).

## Build order

1. **Benchy Cafe style frame and first playable slice.** Develop them alongside each other. The style frame shows the faithful fronts, both heroes for comparison and the wider playable pavement at 480×270. The browser slice now includes both selectable heroes, depth movement, ground combo, jump kick, two shopper waves, a breakable crate, a raised present and a mince pie. Tune hit feedback, lane dodging and pickup reach before producing full animation sets. Phaser 3 is the proposed engine for the prototype, and Tiled is a candidate if an editor helps assemble reusable shopfronts.
2. **Complete episode playtest.** The three stages, bosses, stage restarts, score screen and timed window reveal are playable. Refine the route, landmark frontage art, boss animation, effects and music after feedback.
3. **Browser playtest.** Check keyboard play, small-screen readability and the feasibility of touch controls. Verify both heroes can reach every pickup and complete every encounter. Set hosting and domain after review.
4. **Future stories.** Add an episode menu when the second story is ready. The Dunnings music festival is a candidate, with its own objective and finale and familiar locations redressed for a different event.

## Feedback for reviewers

- Does the route feel like East Grinstead? Which shopfronts or details would locals miss?
- Does the Christmas blackout give the heroes a clear reason to cross the town?
- Do the three bosses feel distinct, and does the Tree Frog moment feel like the right payoff?
- Are the two characters and the jump kick easy to recognise at gameplay size?
