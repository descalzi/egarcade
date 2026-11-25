# Grinstead Arcade

## Design plan for review

**Grinstead Arcade** is a series of original, browser-based 16-bit arcade brawlers set in East Grinstead, West Sussex. The hook is a recognisable High Street and stories built around real local events. The first complete episode is **East Grinstead: The Big Reveal**. A future episode could take the same two heroes to the Dunnings music festival.

Launch the first episode straight from its title screen into character selection. Add a Choose a Story screen once a second episode exists. Share movement, combat, characters and reusable scenery across episodes, with separate stage layouts, objectives, music, bosses and endings. A possible address is `grinsteadarcade.co.uk/big-reveal`. Domain availability is open.

## The Big Reveal

On the evening of the Christmas lights and shop-window reveal, the Disco King, a silver-suited mannequin come to life, takes the fuse from the event's lighting control box. The Christmas lights go out. An event volunteer at Benchy Cafe hands the chosen hero a spare fuse. Get it to the control box by the finale shop and bring the reveal back on.

| Stage | Route and encounters | Boss |
| --- | --- | --- |
| **1. The Blackout** | Start at Benchy Cafe, between Farthing & Co. and The Book Nook. An easy pavement present, a ledge present and a breakable crate introduce the controls. Meet one Christmas-shopping zombie, then two approaching from opposite sides. | **The Nutcracker**, a wooden window decoration. A visible wind-up precedes its straight-line charge. Step across the pavement, then counter while it recovers. |
| **2. Window Shopping** | Continue past the Tudor façades. Larger groups of the same shuffling zombies emerge from doorways and passages. The Dorset Oak's real carriage passage fits an encounter. | **The Last-Minute Shopper**, an oversized zombie with an overloaded trolley. Sidestep the rush and counter while it turns the trolley around. |
| **3. One Last Number** | A short zombie encounter on the approach to The Treetop Frog. The crowd waits outside and the shop's three display bays stay completely covered. | **The Disco King** uses repeated dance sequences with a visible recovery pose. Beat him, fit the spare fuse and use the reveal switch. |

The countdown frames the story and finale. Players can take their time with the fights. On zero, the player's switch cue brings the lights on and lifts the window cover on the first beat of an original '70s disco track. The DJ appears in the middle bay with one dancer on either side. The crowd dances in the street, the Disco King slips into the front row, and the score appears after the scene has had time to play.

## Controls and scoring

- **Move** along the street and across the depth of the pavement. Side-stepping is the basic dodge.
- **Attack** on the ground for a short punch sequence ending in a kick. Use the same button to break crates and bins.
- **Jump** to reach high presents. Attack once in the air for a forward kick that knocks a zombie back. Ground attacks are enough to clear every encounter.
- Choose between a woman in a rust shearling jacket, tan boots and ponytail and a man in a teal winter jacket and red scarf. Both share identical speed, jump, attack reach, timing, health and story.
- Start with **five hearts**. A landed hit takes one heart, followed by a brief invulnerability window. Hearts carry across stages. At zero, restart the current stage on five hearts with its entry score.
- Wrapped presents are worth **100 points**. Place them on the pavement, on reachable ledges and in breakables. One optional gold present per stage is worth **300 points**.
- Mince pies restore **one heart**. Place them at fixed spots and leave them available at full health. Show hearts and score in a compact HUD.

## Art and locations

Use original pixel art with crisp silhouettes, blue winter dusk and warm shop windows. Preserve the relative shop widths, roof silhouettes, window positions and distinctive timber patterns from the reference photos. Straighten the view for side-scrolling, give the walkable pavement clear depth, and keep bright background detail away from attack silhouettes. Use concept poses to establish proportions, then draw aligned game sprites with matching timing and grounded shadows.

| Real landmark | Working in-game sign | Details to carry forward |
| --- | --- | --- |
| Bench RH19 | **Benchy Cafe** | Gabled dormer, projecting bay, curved timber braces, cream fascia and red chairs. |
| The Bookshop | **The Book Nook** | Immediately right of Benchy, with a broad low tiled roof and long book-filled display windows. |
| Penny Farthing Jewellers | **Farthing & Co. Jewellers** | Immediately left of Benchy, with a small penny-farthing emblem as a sign idea. |
| Heath Botanicals | **Heath & Bloom** | Plants in the window and a planter that could double as a pickup ledge. |
| Flint Owl Bakery | **Flint & Feather Bakery** | Owl motif and a natural place for a mince-pie pickup. |
| The Dorset Arms | **The Dorset Oak** | Long pale frontage, four dormers, left carriage passage and the photo's low entrance canopy. |
| Tree Frog | **The Treetop Frog** | Three arched display panes, scalloped awning, recessed side entrance, brick steps and column. |
| Tudor stretch near 61 High Street | **Tudor High Street** | Broad tiled roof, irregular beams, projecting windows and recessed wooden gateway. |

The four street references are Google Street View captures supplied for architectural review. The four generated images are concept studies. The production art should use original façades and dedicated animation frames. The Dorset concept has a pitched canopy to correct, and the combat mock-up should be tested with slightly smaller sprites on the playable pavement.

| Street references | Concept studies |
| --- | --- |
| [22 High Street](art/references/22-high-street.webp) | [Benchy opening](art/concepts/benchy-opening.png) |
| [61 High Street](art/references/61-high-street.webp) | [Pub and finale](art/concepts/pub-and-finale.png) |
| [The Dorset Arms](art/references/dorset-arms.webp) | [Winter duo and poses](art/concepts/winter-duo.png) |
| [Tree Frog](art/references/tree-frog.webp) | [Combat at street scale](art/concepts/combat-scale.png) |

## Build order after review

1. **First playable slice.** Build a short browser level outside Benchy Cafe. Include both selectable heroes, depth movement, ground combo, jump kick, the first zombie encounter, a breakable crate, a raised present and a mince pie. Playtest timing, hit feedback, jump readability and sprite scale.
2. **Complete episode.** Finish the three connected stages, three bosses, restarts, score screen and the timed window reveal. Produce final sprites, landmark frontage art, sound effects and original music.
3. **Browser playtest.** Check keyboard play, small-screen readability and the feasibility of touch controls. Verify both heroes can reach every pickup and complete every encounter. Set hosting and domain after review.
4. **Future stories.** Add an episode menu when the second story is ready. The Dunnings music festival is a candidate, with its own objective and finale and familiar locations redressed for a different event.

## Feedback for reviewers

- Does the route feel like East Grinstead? Which shopfronts or details would locals miss?
- Does the Christmas blackout give the heroes a clear reason to cross the town?
- Do the three bosses feel distinct, and does the Tree Frog moment feel like the right payoff?
- Are the two characters and the jump kick easy to recognise at gameplay size?
