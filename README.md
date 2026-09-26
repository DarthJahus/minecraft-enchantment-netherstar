# Nether Star Enchantments

Portable beacon effects on your gear, …

… a **selfish beacon**.

In PvP / PvE, classic beacons are often underused: the range is limited and moving a full pyramid is tedious.
These enchantments bring beacon-like powers directly onto your equipment.
No structure required. Just wear or hold the right item, keep enough XP levels and the effect applies to **you**.

- [Crafting](#crafting)
- [Speed](#speed)
- [Jump Boost](#jump-boost)
- [Haste](#haste)
- [Strength](#strength)
- [Resistance](#resistance)
- [Regeneration](#regeneration)
- [Conduit](#conduit)
- [Turtle](#turtle)

---

## Concept

Each enchantment mimics a beacon primary effect, with two important twists:

1. **Personal only** — the effect applies to the wearer / holder, not to nearby players.
2. **XP gate** — most effects require a minimum player XP level (typically **30**, or **40** for Conduit), similar in spirit to the cost of powering a real beacon.

Some also carry a small **drawback** (reduced interaction range) so they stay balanced for late-game / PvP use.

Anvil cost is high (**40**) for most of them — they are end-game upgrades.

---

## Crafting

All "of the Nether" items are made on a **smithing table**:

| Result | Base | Template | Addition | Enchantment |
|--------|------|----------|----------|-------------|
| Bottes of the Nether | Netherite Boots | Nether Star | Beacon payment block* | Speed I |
| Jambières of the Nether | Netherite Leggings | Nether Star | Beacon payment block* | Jump Boost I |
| Plastron of the Nether | Netherite Chestplate | Nether Star | Beacon payment block* | Resistance I |
| Casque of the Nether | Netherite Helmet | Nether Star | Beacon payment block* | Regeneration I |
| Épée of the Nether | Netherite Sword | Nether Star | Beacon payment block* | Strength I |
| Pioche / Hache / Pelle / Houe of the Nether | Matching netherite tool | Nether Star | Beacon payment block* | Haste I |
| Carapace of the Deep | Turtle Helmet | Conduit | Sea Lantern | Conduit I + Turtle I |

\* Beacon payment blocks: Iron, Gold, Emerald, Diamond or Netherite block.

Crafted items are marked **epic** rarity and come with a short lore line.

### Smithing with a Nether Star

The smithing recipe **resets the item**: previous enchantments are removed and only the Nether Star enchantment remains.

Unlike a Netherite upgrade (which copies everything from the base item), this is a full re-infusion.

To combine with other enchantments, either:
- Run a second item through the smithing table, then **merge the two on an anvil**;
- Apply the Nether Star enchantment first on a clean item, then add the other enchantments on an anvil as usual.

---

## Speed

Grants Speed while you are not in water or lava.

- Supported: Boots
- Max level: 3
- XP required: **30**
- Trigger: continuous (tick)

| Level | Amplifier |
|-------|-----------|
| 1     | Speed I   |
| 2     | Speed II  |
| 3     | Speed III |

## Jump Boost

Grants Jump Boost.

- Supported: Leggings
- Max level: 3
- XP required: **30**
- Trigger: continuous (tick)

| Level | Amplifier     |
|-------|---------------|
| 1     | Jump Boost I  |
| 2     | Jump Boost II |
| 3     | Jump Boost III|

## Haste

Grants Haste when you mine a block.

- Supported: Tools (`#minecraft:enchantable/mining_loot`)
- Max level: 3
- XP required: **30**
- Trigger: on block hit
- Drawback: reduced block interaction range (−0.5 per level, up to −1.5)
- Incompatible with: damage exclusive set (Sharpness, etc.)

| Level | Amplifier | Duration |
|-------|-----------|----------|
| 1     | Haste I   | ~15 s    |
| 2     | Haste II  | ~15 s    |
| 3     | Haste III | ~15 s    |

## Strength

Grants Strength when you attack.

- Supported: Weapons
- Max level: 3
- XP required: **30**
- Trigger: on attack
- Drawback: reduced entity interaction range (−0.5 per level, up to −1.5)
- Incompatible with: damage exclusive set

| Level | Amplifier   | Duration |
|-------|-------------|----------|
| 1     | Strength I  | ~15 s    |
| 2     | Strength II | ~15 s    |
| 3     | Strength III| ~15 s    |

## Resistance

Grants Resistance when you are attacked.

- Supported: Chestplate
- Max level: 3
- XP required: **30**
- Trigger: when hit

| Level | Amplifier      | Duration |
|-------|----------------|----------|
| 1     | Resistance I   | short    |
| 2     | Resistance II  | short    |
| 3     | Resistance III | short    |

## Regeneration

Grants Regeneration when you are attacked.

- Supported: Helmet
- Max level: 3
- XP required: **30**
- Trigger: when hit

| Level | Amplifier        | Duration |
|-------|------------------|----------|
| 1     | Regeneration I   | short    |
| 2     | Regeneration II  | short    |
| 3     | Regeneration III | short    |

## Conduit

Grants Conduit Power while you are in water.

- Supported: Helmets
- Max level: 1
- XP required: **40**
- Trigger: continuous while submerged

## Turtle

Applies Slowness II when you stand still **out of water** (turtle-shell behaviour on land).

- Supported: Turtle Helmet only
- Max level: 1
- Usually paired with Conduit via the *Carapace of the Deep* recipe

---

## Notes

- Effects only apply to the player wearing / holding the item (true selfish beacon).
- Keep your XP level high enough or the effects stop.
- High anvil cost makes them expensive to transfer or upgrade.
- Designed for late-game survival, adventure maps and PvP/PvE where a full beacon pyramid is impractical.
