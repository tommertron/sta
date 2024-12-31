+++
date = '2024-12-31'
draft = false
title = 'Combat - Ships'
summary = 'Everything you need to know about ships, including combat.'
showReadingTime = false
+++

## Ship Combat Overview

Starship combat is a dynamic and tactical experience where each Player takes control of a specific station on the ship. Unlike personal combat, a ship does not take a single unified turn; instead, each Player contributes by performing actions based on their assigned role. Moving between stations is possible but takes time and resources, as it requires using a Minor Action. For NPC ships, the number of actions they can take per round equals their **Scale**.

When damage occurs, systems can suffer **Breaches**, which disable or degrade their functionality. Repairs can be conducted from the bridge or on-site if the system is damaged or disabled. Systems beyond repair require more drastic measures, such as abandoning the ship or ejecting the warp core.

---

## Movement and Terrain

The helmsman controls ship movement in combat. Moving the ship generally requires a **Task**, though under normal conditions, this has a Difficulty of 0, meaning no dice roll is required. Environmental traits, such as hazardous terrain, can increase the Difficulty. Maneuverability and range also play crucial roles in ship positioning during combat.

---

## Combat Tasks and Minor Actions

Each bridge station has specific Tasks and Minor Actions associated with the character's role. During their turn, a character can attempt **one Combat Task** and perform **one free Minor Action**. Additional Minor Actions may be purchased by spending **Momentum** (Immediate) or adding to **Threat**.

**Key Points**:
- Players should align their actions with their station's functionality.
- Non-assigned roles can still issue commands, but they may lack the bonuses provided by specialized training or station assists.

### Ship Actions - Helm

| **Action**         | **Description**                                                                                                    | **Power Cost**                   | **Additional Notes**                                                                                   |
|---------------------|--------------------------------------------------------------------------------------------------------------------|-----------------------------------|-------------------------------------------------------------------------------------------------------|
| **Maneuver**       | The flight controller uses the ship's thrusters for precise adjustments, moving anywhere within Medium range.      | None                              |                                                                                                       |
| **Impulse**        | The flight controller utilizes the ship's impulse engines for swift movement, reaching any location within Long range. | 1 Power                          |                                                                                                       |
| **Warp**           | The flight controller engages the ship's warp drive for short jumps across multiple zones.                         | Equal to the number of zones traversed |                                              |
| **Evasive Action** | The flight controller performs a series of swift, unpredictable maneuvers to throw off enemy targeting.            | None                              | **Action**: Daring + Conn Task, Difficulty 1.<br><br> **Bonus**: Assisted by the ship's Structure + Conn.<br><br>**Effect**: If successful, until the flight controller's next turn, all attacks against the ship and attacks made by the ship gain a bonus. |


---

## Making an Attack

Attacks using a starship’s weapons follow a structured process. The attacker selects a weapon system and target, then resolves the attack using an appropriate Task. 

1. **Choose Weapon**: Decide between energy weapons or torpedoes.
2. **Select Target**: The target must be within the weapon’s effective range. Specify if the attack is lethal (adds 1 Threat).
3. **Roll Attack Task**:
   - Use **Control + Security**, assisted by the ship’s **Weapons + Security**.
   - The Difficulty depends on the weapon:
     - Energy weapons: Difficulty 2.
     - Torpedoes: Difficulty 3.
   - Increase Difficulty for targeting a specific system or attacking outside the weapon’s optimal range.
4. **Resolve Damage**: Roll damage dice per the weapon's profile. If no specific system was targeted, roll to determine which system is hit.

---

## Damage and Breaches

When a ship suffers damage, it first reduces the damage by its **Resistance**, then subtracts the remaining damage from its **Shields**. A ship may suffer one or more **Breaches** under these conditions:
- **Five or more damage** from a single attack (after Resistance).
- **Shields reduced to 0** by the attack.
- **Damage inflicted while shields are already at 0**.

Breaches affect the system hit, potentially disabling or destroying it. The severity of the effect depends on the number of Breaches relative to the ship’s **Scale**.

### Breach Effects
- **Impact**: Temporary disruption; the system can be restored using a Minor Action.
- **Damaged**: Tasks involving the system have increased Difficulty (+2) and higher complication range.
- **Disabled**: The system cannot function until repaired.
- **Destroyed**: The system is permanently unusable and cannot be repaired.

---

## Repairs and Damage Control

Repairs are essential for maintaining ship functionality during combat. Characters can attempt repairs by either sending a repair team or moving to the damaged system. Repairs involve a **Daring** or **Control + Engineering** Task, with the Difficulty depending on the damage level.

- **Minor Damage**: Requires a Difficulty 1 Task.
- **Disabled Systems**: Repairs are Difficulty 4 and require dedicated effort.
- **Warp Core Breach**: Stabilizing or ejecting the core is an extreme measure requiring a specialized Extended Task.

---

## Power Management

Starships rely on Power to operate advanced systems like shields, weapons, and propulsion. At the start of each scene, the ship regenerates its full Power capacity (equal to its **Engines** rating). Actions like going to warp or boosting shields consume Power, while certain effects or complications can cause power loss. 

If Power is depleted, the ship may suffer a **Complication** affecting a random system, reflecting the strain on its functionality.

---

## Ship-Specific Mechanics

### Shields
Shields absorb damage before it affects the ship’s structure. A ship’s Shield value equals its **Structure + Security**. Shields can be restored during combat using the appropriate Task.

### Resistance
Ships have a base **Resistance** equal to their **Scale**, which reduces incoming damage. Resistance can be bypassed by effects such as the **Penetration** Momentum spend.

### Crew Support
Crew Support represents the availability of additional personnel for tasks. Each ship’s Crew Support pool equals its **Scale** and refreshes only at the start of a new mission.

---

## NPC Ships

For NPC-controlled vessels, each ship takes a number of actions per round equal to its Scale. Crew quality determines their effectiveness:
- Basic: Attribute 8, Discipline 1.
- Proficient: Attribute 9, Discipline 2.
- Talented: Attribute 10, Discipline 3.
- Exceptional: Attribute 11, Discipline 4.

Simplified damage rules can be used for large-scale encounters, reducing tracking complexity while maintaining combat flow.

---

## Momentum Spends (Ships)

| **Action**         | **Effect**                                                                           | **Cost** |
| ------------------ | ------------------------------------------------------------------------------------ | -------- |
| Bonus Damage (R)   | Increase attack damage by +1 per Momentum spent.                                     | 1        |
| Penetration (R)    | Ignore 2 Resistance per Momentum spent on attack.                                    | 1        |
| Re-Roll Damage     | Re-roll any number of dice from the current attack.                                  | 1        |
| Devastating Attack | Roll an additional system; it suffers half the primary attack's damage (rounded up). | 2        |
| Swift Task         | Attempt an additional Task with +1 Difficulty.                                       | 2        |
| Power Loss (R)     | Attack removes one point of target's Power.                                          | 1        |

