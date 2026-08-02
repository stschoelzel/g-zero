# QUICK REFERENCE

*Everything below is derived from the rules above. Where they disagree, the rules above are correct.*

## SETUP

All Null-Frames start at **V1**, **Altitude Mid**, **Nerve 4**, 0 G-Force. Standard race: **3 laps**.

## ROUND SEQUENCE

Vector Phases 1 to 6 in order. In each Phase: secret Altitude declaration, then activation in initiative order.
Qualified = current Vector equal to or higher than the Phase number. A frame activates once per round, in the Phase matching its Vector.
**Initiative order** = current race standing, leader first. Ties broken by distance to next Gate, then by roll-off.
**Leading Position** passes to the current race leader at the end of each round.
**End of round:** remove temporary Burst Templates.

## ACTIVATION SEQUENCE

| Step | Action |
|:---:|:---|
| 1 | Declarations (Redout, Red Mist, Slipstream) |
| 2 | Reveal Altitude, resolve transition |
| 3 | Select and place template (pay High-G) |
| 4 | Roll Nerve Dice |
| 5 | Spend Energy |
| 6 | Move and resolve collisions |
| 7 | Lose unspent Energy; G-Load Check at 6+ G |

## NERVE DICE

Roll up to your current Nerve. Rolling is optional.

| Roll | Result |
|:---:|:---|
| 1 - 2 | +1 G-Force |
| 3 - 4 | Nothing |
| 5 - 6 | +1 Energy |

## SPENDING ENERGY

| Cost | Action |
|:---:|:---|
| 1 | Remove 1 G-Force (Inertial Dampener) |
| 1 | Shift Vector 1 step (+1 G per extra step) |
| 1 + 1 G | Drift: exit at the template's Drift point |
| 1 + 1 G | Spin: pivot up to 90 degrees at final position |

Vector range V1 to V6. Unspent Energy is lost at end of activation.

## ALTITUDE TRANSITIONS

| From | To Low | To Mid | To High |
|:---|:---|:---|:---|
| **Low** | +Short Straight, free | +2 Energy | 2 G first step, 1 G each further |
| **Mid** | +Medium Straight, 1 G | +1 Energy | 1 G first step, 1 G each further |
| **High** | +Long Straight, 2 G | +2 Energy | free first step, 1 G each further |

Going High lowers your Vector **for template selection only**.

## COLLISIONS

Collision Dice: **4, 5, 6 = success**. Aggressor = the frame that caused contact. Objects are always the Aggressor.

**Different Altitudes = Graze.** Winner rolls 3 dice, loser rolls 1.
High beats Mid. Mid beats Low. Low beats High.

**Same Altitude = Full Collision.** Both roll the same pool:

| Orientation | Pool |
|:---|:---|
| Head-On (front edge/corner) | Sum of both Vectors, min 3 |
| Broadside (side edge) | Higher Vector, min 2 |
| Tailgate (rear edge/corner) | Difference of Vectors, min 1 |

**Reactions:**

| Reaction | Who | Per success |
|:---|:---|:---|
| Brace | Anyone | +1 G on the other party, pivot them 30 degrees |
| Evade | Defender only | Cancel 1 G inflicted on you |

**Objects:** always Brace; all dice auto-succeed; the frame is Defender and may Evade; orientation does not apply.

| Object | Dice | Burst | After |
|:---|:---:|:---|:---|
| Soft | 1 | Small | Destroyed; movement continues |
| Medium Solid | Your Vector | Large | Destroyed; -1 Vector |
| Heavy Solid | 2x your Vector | Extra-Large | Unaffected; movement stops |

## SONIC BOOM

First activation after switching to V6: place a Large Burst Template directly behind the frame, at start or end of movement (your choice). Removed at end of the Vector Phase.
Any other frame activating while overlapping it, or ending its activation overlapping it, rolls extra Nerve Dice equal to its current Nerve.

## G-LOAD CHECK

Triggered at **6+ G-Force at end of activation**. At Nerve 1, roll the Emergency Dampener Check first.

Roll dice equal to Nerve, minus 1 die per G beyond the sixth. Each die **equal to or above your current Vector** is a success.

| Successes | Result |
|:---:|:---|
| 3+ | **NERVES HOLD.** Nothing happens. |
| 2 | **NERVES FRAY.** Tumble; -1 Nerve. Vector kept. |
| 1 | **GREYOUT.** Override. Vector to V1, Altitude to Mid. |
| 0 | **BLACKOUT.** Tumble and Override; -1 Nerve. Vector to V1, Altitude to Mid. |

Discard all G-Force in every case.

## TUMBLE

1. **Direction:** away from the point of contact (collision) or the template centre (burst). No directional cause: 1D6 in six 60-degree wedges - 1 forward, 2 forward right, 3 back right, 4 back, 5 back left, 6 forward left.
2. **Distance:** Short (V1-V2), Medium (V3-V4), Long (V5-V6).
3. Frames in the path gain G equal to length: 1 / 2 / 3. No reactions, no Altitude check.
4. Nearest rival pivots the tumbling frame to any facing.
5. -1 Nerve, permanent (min 1).

## OVERRIDE AND RECOVERY

Override triggers on GREYOUT or BLACKOUT; the frame enters **Recovery** and skips its next qualifying activation. Does not stack.

## EMERGENCY DAMPENER CHECK

At Nerve 1 only, before any G-Load Check:

| Check | Survive on |
|:---:|:---:|
| 1st | 2+ |
| 2nd | 4+ |
| 3rd | 6 |
| 4th | Death, no roll |

Success: resolve the G-Load Check normally; a Tumble costs no further Nerve.
Failure: pilot dies; frame becomes a Dead Stick.

## DEAD STICK

Activates automatically in the Vector Phase matching its last Vector. Moves one Long Straight forward. No dice, no Altitude, no consequences. Gates do not count.
On hitting a wall or Heavy Solid: **1** stop and remove; **2-5** bounce, nearest rival pivots it; **6** removed, Large Burst at impact.
Leaving the track boundary removes it.

## PILOT ACTIONS

**Redout** - Start of activation. -1 Nerve permanently. Ignore all Vector restrictions on template selection this activation. Stackable. Not available at Nerve 1.

**Red Mist** - Once per race, start of activation, V5 or V6 only. Add two Long Straight templates in any order. No Nerve Dice, no self-inflicted G-Force. Pilot dies at end of activation; frame permanently lost. Recorded as a Finisher if the Finish Gate was crossed on the final lap. Not available at Nerve 1.