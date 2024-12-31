# Breaches

Each System of a starship can sustain a number of Breaches **equal to its Scale**. For each System, a Breach has an immediate impact, a short-term penalty such as being unable to use that System for a Turn. Then, if a System has suffered a number of Breaches equal to or greater than half the ship’s Scale, then it is *damaged*. If a System has suffered a number of Breaches equal to the ship’s Scale, then it is *disabled*. If a System has suffered more Breaches than the ship’s Scale, then it is *destroyed*.

| **Type**      | **Number of Breaches** | **Effect**                                                                                                                               |
| ------------- | ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| **Impact**    | 0; < 1/2 ship's scale  | Disrupt functions temporarily. Do *restore* [Ship Actions - Minor](craft-importer-internal-link://Ship Actions - Minor)                  |
| **Damaged**   | \#ERROR!               | Difficulty of tasks related increases by 2; complication range 19-20                                                                     |
| **Disabled**  | \#ERROR!               | System cannot be used unless do [Ship Actions - Internal Systems](craft-importer-internal-link://Ship Actions - Internal Systems) Repair |
| **Destroyed** | ship's scale           | Cannot be repaired. If engines, warp core breach                                                                                         |

| **System**         | **Impact**                 | **Damaged**   | **Disabled**                                                                       | **Destroyed**                                                                                          |
| ------------------ | -------------------------- | ------------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| **Communications** | Cannot hail                | Difficulty +2 | Must [Repairing](craft-importer-internal-link://Breaches#Repairing) (difficulty 4) | Can't repair                                                                                           |
| **Engines**        | Lose 2 power               | Difficulty +2 | Must repair                                                                        | Can't repair;<br>Possible Warp Core Brea[ch](craft-importer-internal-link://Breaches#Warp Core Breach) |
| **Weapons**        | Can't fire                 | Difficulty +2 | Must repair                                                                        | Can't repair                                                                                           |
| **Structure**      | Roll 1D; if effect: injury | Difficulty +2 | Must repair                                                                        | Can't repair                                                                                           |
| **Computers**      | No assist from ship        | Difficulty +2 | Must repair                                                                        | Can't repair                                                                                           |

- **Impact:** Whenever a System suffers a Breach, it disrupts functions temporarily. Until a character in a relevant role for the System performs the *Restore* Minor Action, that System cannot be used to perform or assist any Tasks.
   - Communications can’t hail
   - Engines lose 2 Power
   - Weapons cannot fire
   - If Structure is hit then roll 1 ; if an Effect is rolled, a random Player Character suffers an Injury.
- **Damaged:** If the total number of Breaches is equal to half the ship’s Scale, the Difficulty of all Tasks using that System increase by 2, and a Complication occurs on the result of a 19-20. The Difficulty to repair this damage is 3.
- **Disabled:** If the total number of Breaches is equal to ship’s Scale, the System is disabled. The System cannot be used to perform or assist with any related Task. If this is the Engines System, the ship cannot generate more Power and loses 1 Power every Round. The Difficulty to repair this damage is 4, and a Complication occurs on an 18-20.
- **Destroyed:** If the total number of Breaches exceeds the ship’s Scale, the System is destroyed. The System cannot be used to perform or assist with any related Task, and cannot be repaired. If this is the Engines System, the ship can suffer warp core breach, as described below.

!Pasted image 20240218140328.png

# Repairing

The *Damage Control* Task listed on the Internal Systems and the Communications reference pages sends a repair team to handle the repairs. However, characters can use the *Change Position* Minor Action to move elsewhere in the ship, a character can head to the site of the damage, and attempt to perform the repairs personally. This will take a **Daring** or **Control + Engineering** **Task** with the Difficulty for repairs set by the damage suffered above.

## Warp Core Breach

If the ship suffers a loss of containment, then the reactors may explode at any moment; roll one or more at the end of each Round, starting with 1 at the end of the Round in which the containment loss began, and increasing by 1 for each successiveRound (so, 2 for the second round, 3 for the third, and so forth).If one or more Effects are rolled, the reactors explode, destroying the ship immediately, killing all aboard, and inflicting 3 + ship’sScale Piercing 2 damage to all other ships within Close range.

This can, however, be avoided. Characters in main engineering may attempt to stabilize the reactor, or they may try to eject the reactor entirely (though not all ships have the capability to eject their reactors, so their crews may wish to abandon ship):

- **Stabilize the Reactor:** This is an Extended Task, with Work 8, Magnitude 3, Resistance 2, and a Base Difficulty of 3. Succeeding at this Extended Task prevents the reactor from exploding. Common combinations for this will be Daring or Control + Engineering.
- **Eject the Reactor**: This is a Daring + Engineering Task, with a Difficulty of 2. Success means that the reactor is successfully ejected. If ejected, continue to roll to see if it explodes; when it does, it will not destroy the ship (as it’s been ejected and is no longer within the ship), but all ships, including the one that ejected it, within Close range will still suffer damage when it detonates.

