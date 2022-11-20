# Meteor Kaizo Ironmon
Meteor Kaizo is a variant of Kaizo Ironmon created by Something_Smart, with the intention of improving the
watchability of the challenge and adding more meaningful decisions. Original Ironmon rules can be found [here](ironmon.gg) (scroll down for Kaizo).

This challenge uses a modified version of the [Pokémon Randomizer](https://github.com/Ajarmar/universal-Pokemon-randomizer-zx/releases), which is included in the project here.

# Differences from regular Kaizo

## Randomizer settings

* Boss trainers + important trainers have sensible held items
* Catch rate slider set to 5 (guaranteed catches)
* Full TM compatibility
* Guarantee 2 abilities
* Use all misc. tweaks that apply: Revert Resist Berries, Remove Banned Mons From Lab, HM Moves by Levelup, Ban Unown From Wild, Ban Perish Song, Ban Imposter, Fix Mythical Pokemon Experience.

## Rule changes

The main rule change is a change to what held items are usable. Instead of having a strict list of which items can and can't be held, legal items depend on the BST of your current pokemon:
(categories are additive, so each row includes all the rows above it)
| BST   | Legal items                                                                                               |
|-------|----------------------------------------------------------------                                           |
|521+   | Standard Kaizo allowed items (consumable other than Focus Sash)                                           |
|520-   | Life Orb, choice items                                                                                    |
|490-   | Items that do not heal or directly boost damage of moves (Scope Lens etc. is allowed, but not Muscle Band)|
|460-   | Focus Sash, items that boost damage                                                                       |
|430-   | All items                                                                                                 |
|400-   | You may also buy one healing item after each gym                                                          |

In addition, the first TM that is obtainable from a non-gym NPC may be taught; however, if you do, you must permanently move one row up on the chart, losing access to one tier of items.
(If you were already in the top row, nothing changes.)

I'm not sure where this first gift TM is in all games, but here are the ones I do know:
* RSE: TM09 from the kid near the flower shop
* DP: TM10 from the students in the Trainer's School
* Pt: TM27 from Rowan
* HGSS: TM70 from the Sprout Tower Elder
* B2W2: TM21 from the grunt in the ranch
* ORAS: TM49 from the kid near the flower shop

## Settings strings

I'll add some more settings strings later, but here are the ones for the games I've played:
* HGSS: 321WRIEEgKYAJsAngCRAAKeBhsEiAEAFAACCQAuEgAAAABbzBCI5ATkQYYICTIGBQIyUwUgW8wQiAAAAAEVUG9rZW1vbiBIZWFydEdvbGQgKFUpsjeSL+PDOIo=
* B2W2: 321WRIEEgLvAfIB9QGRAAKeBhsEiAEACQACCSAuEgAAAAB7xHCI5ATkwYYICTIGBgIyUwUge8RwiAAAAAATUG9rZW1vbiBCbGFjayAyIChVKQbA+2vjwziK

If you have any questions/suggestions about the challenge, or suggestions for changes to the randomizer, hit me up at Something_Smart#8109 in the Ironmon discord.
