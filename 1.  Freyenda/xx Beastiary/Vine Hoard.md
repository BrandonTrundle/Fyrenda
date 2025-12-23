```statblock
# ===== BASIC INFO =====
name: Vine Horde
image: Utility/Images/BeastiaryImages/VineHoard.jpeg
layout: 5e-wide
width: 1100
image_height: 300

size: Large
type: Plant
alignment: Unaligned

ac: 14 (natural armor)
hp: 150
hit_dice: 20d10+40

speed: 20 ft., burrow 10 ft.

# ===== ABILITY SCORES =====
stats:
  - 20
  - 10
  - 14
  - 2
  - 12
  - 5

# ===== SAVES =====
saves:
  strength: 7
  dexterity: 0
  constitution: 4
  intelligence: 0
  wisdom: 3
  charisma: 0

# ===== SKILLS =====
skillsaves:
  perception: 3
  stealth: -2
  insight: 1

damage_resistances: bludgeoning, piercing, necrotic, cold
damage_immunities: poison
condition_immunities: blinded, deafened, charmed, frightened, poisoned, prone

senses: blindsight 60 ft. (blind beyond this radius)
languages: —
cr: "5"

# ===== TRAITS =====
traits:
  - name: Swarm Body
    desc: |
      The Vine Horde occupies its space and can move through openings large enough for a Medium creature. It can share its space with other creatures, and other creatures can move through its space.

  - name: Burning Weakness
    desc: |
      When the Vine Horde takes fire damage, it has disadvantage on all attack rolls and Dexterity saving throws until the end of its next turn.

# ===== ACTIONS =====
actions:
  - name: Multiattack
    desc: |
      The Vine Horde makes two Tendril Lash attacks.

  - name: Tendril Lash
    desc: |
      Melee Weapon Attack: +7 to hit, reach 10 ft., one target.
    attack_bonus: 7
    damage:
      - dice: 2d8
        bonus: 5
        type: bludgeoning

  - name: Root Burst
    desc: |
      The Vine Horde erupts from the earth in all directions. Each creature within 10 feet must make a DC 15 Dexterity saving throw or take 3d6 bludgeoning damage and be knocked prone. On a success, the creature takes half damage and does not fall prone.
    save_dc: 15
    save_ability: dexterity

  - name: Constricting Mass (Recharge 5–6)
    desc: |
      The swarm expands and attempts to crush everything in its space. Each creature in the Vine Horde’s space must make a DC 15 Strength saving throw or take 4d6 bludgeoning damage and become restrained for 1 minute. A restrained creature may repeat the saving throw at the end of its turn, ending the effect on a success.
    save_dc: 15
    save_ability: strength
    damage:
      - dice: 4d6
        type: bludgeoning

  - name: Grasping Crawl
    desc: |
      The Vine Horde moves up to 10 feet without provoking opportunity attacks.
    attack_bonus: 0

# ===== LEGENDARY ACTIONS =====
legendary_actions:
  - name: Shift Mass
    desc: |
      The horde shifts its weight. Until the start of its next turn, creatures in its space have disadvantage on Strength saving throws.
    roll:
      - skill: athletics

  - name: Tendril Snap
    desc: |
      The horde lashes out violently.
    attack:
      bonus: 7
      damage_dice: 1d10
      damage_bonus: 5
      damage_type: bludgeoning

  - name: Crushing Surge
    desc: |
      The horde compresses inward. Each creature in its space must succeed on a DC 15 Strength saving throw or take 2d6 bludgeoning damage.
    save_dc: 15
    save_ability: strength
    damage:
      - dice: 2d6
        bonus: 0
        type: bludgeoning
```

### **Visual Description 

A writhing mass of roots, vines, and thorned tendrils pulses like a single organism. Each movement ripples through hundreds of strands that coil, flex, and lash with unsettling coordination. Dirt and shredded bark drip from its twisting body as if the forest itself were dragging its nerves into the open. It moves with the weight of something choking the life out of the earth.