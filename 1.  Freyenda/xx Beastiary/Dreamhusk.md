```statblock
# ===== BASIC INFO =====
name: Dreamhusk
image: Utility/Images/BeastiaryImages/Dreamhusk.jpeg
layout: 5e-wide
width: 1100
image_height: 300

size: Medium
type: Aberration
alignment: Chaotic Evil

ac: 17 (chitinous hide)
hp: 142
hit_dice: 15d8+75

speed: 30 ft.

# ===== ABILITY SCORES =====
stats:
  - 18
  - 16
  - 20
  - 7
  - 14
  - 9

# ===== SAVES =====
saves:
  strength: 8
  dexterity: 6
  constitution: 9
  intelligence: 0
  wisdom: 5
  charisma: 1

# ===== SKILLS =====
skillsaves:
  perception: 5
  stealth: 6
  insight: 3

damage_resistances: psychic, necrotic, cold; bludgeoning from nonmagical attacks
damage_immunities: —
condition_immunities: frightened, charmed

senses: darkvision 120 ft., passive Perception 15
languages: understands Deep Speech but cannot speak
cr: "8"

# ===== TRAITS =====
traits:
  - name: Nightmare Aura
    desc: |
      Creatures that start their turn within 10 feet of the Dreamhusk must succeed on a DC 16 Wisdom saving throw or take 2d6 psychic damage and have disadvantage on their next attack roll.

  - name: Sleepwalker Form
    desc: |
      The Dreamhusk can move through a space as narrow as 6 inches wide without squeezing.

# ===== ACTIONS =====
actions:
  - name: Multiattack
    desc: |
      The Dreamhusk makes two Claw attacks and one Mindrend attack.

  - name: Claw
    desc: |
      Melee Weapon Attack: +8 to hit, reach 5 ft., one target.
    attack_bonus: 8
    damage:
      - dice: 2d8
        bonus: 4
        type: slashing

  - name: Mindrend
    desc: |
      Melee Weapon Attack: +8 to hit, reach 5 ft., one creature.
    attack_bonus: 8
    damage:
      - dice: 2d10
        bonus: 4
        type: psychic

  - name: Dreamlash
    desc: |
      The Dreamhusk targets a creature it can see within 30 feet. The target must succeed on a DC 16 Wisdom saving throw or take 4d6 psychic damage and be stunned until the end of its next turn.
    save_dc: 16
    save_ability: wisdom

  - name: Void Screech (Recharge 5–6)
    desc: |
      The Dreamhusk emits a warped, dissonant shriek. Each creature within 20 feet must succeed on a DC 16 Constitution saving throw or take 5d6 thunder damage and be pushed 10 feet away.
    save_dc: 16
    save_ability: constitution
    damage:
      - dice: 5d6
        type: thunder

  - name: Nightmare Step
    desc: |
      The Dreamhusk teleports up to 20 feet to an unoccupied space it can see.
    attack_bonus: 0

# ===== LEGENDARY ACTIONS =====
legendary_actions:
  - name: Flicker
    desc: |
      The Dreamhusk teleports 10 feet to an unoccupied space it can see.
    roll:
      - skill: stealth

  - name: Rending Claw
    desc: |
      The Dreamhusk makes one Claw attack.
    attack:
      bonus: 8
      damage_dice: 1d8
      damage_bonus: 4
      damage_type: slashing

  - name: Psychic Pulse
    desc: |
      One creature within 10 feet must succeed on a DC 16 Wisdom saving throw or take 2d6 psychic damage.
    save_dc: 16
    save_ability: wisdom
    damage:
      - dice: 2d6
        bonus: 0
        type: 
```

### ⭐ **Visual Description**

Its emaciated body twists with dreamlike distortions, as if parts of it exist half a second behind the rest. Its limbs are too long, joints bending with sickening elasticity. A veil of drifting motes surrounds it like fragments of broken dreams. Its face is featureless except for a gaping maw that widens silently, as though screaming in a nightmare no one else can hear.