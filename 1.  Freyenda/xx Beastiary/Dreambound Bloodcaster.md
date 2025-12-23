```statblock
# ===== BASIC INFO =====
name: Dreambound Bloodcaster
image: Utility/Images/Bad Guys/Cultist.jpeg
layout: 5e-wide
width: 1100
image_height: 300

size: Medium
type: Humanoid (cultist)
alignment: Chaotic Evil

ac: 14
hp: 72
hit_dice: 12d8+18

speed: 30 ft.

# ===== ABILITY SCORES =====
# STR, DEX, CON, INT, WIS, CHA
stats:
  - 9
  - 14
  - 14
  - 12
  - 13
  - 17

# ===== SAVES =====
# Set only bonuses that differ from ability mod
saves:
  constitution: +5
  charisma: +7

# ===== SKILLS =====
skillsaves:
  perception: +4
  stealth: +4
  insight: +4

damage_resistances: psychic
damage_immunities: —
condition_immunities: frightened

senses: darkvision 60 ft., passive Perception 14
languages: Common, Deep Speech
cr: "5"

# ===== TRAITS =====
traits:
  - name: Blood for the Dream
    desc: |
      When the Dreambound Bloodcaster deals damage with a spell of 1st level or higher, it gains temporary hit points equal to the spell’s level × 3.

  - name: Somnurex’s Hunger
    desc: |
      Once per turn, when the Bloodcaster deals psychic or necrotic damage, it can add an extra 1d8 damage of the same type to one target of the spell.

  - name: Spellcasting
    desc: |
      The Dreambound Bloodcaster is a 7th-level spellcaster.

  - name: Spells
    desc: |
      Cantrips (at will): mind sliver, toll the dead, thaumaturgy  
      1st level (4 slots): inflict wounds, dissonant whispers  
      2nd level (3 slots): mind spike, scorching ray  
      3rd level (3 slots): vampiric touch, hunger of hadar  
      4th level (1 slot): blight

# ===== ACTIONS =====
actions:
  - name: Multiattack
    desc: |
      The Dreambound Bloodcaster casts one spell or makes one Ritual Dagger attack.

  - name: Ritual Dagger
    desc: |
      Melee Weapon Attack: +5 to hit, reach 5 ft., one target.
    attack_bonus: 5
    damage:
      - dice: 1d6
        bonus: 3
        type: piercing

  - name: Dream Rend
    desc: |
      Psychic energy lashes out at a creature the Bloodcaster can see within 60 feet. The target must succeed on a DC 15 Wisdom saving throw or take psychic damage and be knocked prone.
    save_dc: 15
    save_ability: Wisdom
    damage:
      - dice: 4d10
        type: psychic

  - name: Soul-Flare (Recharge 5–6)
    desc: |
      Necrotic energy erupts in a 15-foot-radius sphere centered on a point the Bloodcaster can see within 60 feet. Creatures in the area must make a DC 15 Constitution saving throw, taking necrotic damage on a failed save, or half as much damage on a successful one.
    save_dc: 15
    save_ability: Constitution
    damage:
      - dice: 6d10
        type: necrotic

  - name: Veil Slip
    desc: |
      The Dreambound Bloodcaster magically teleports up to 30 feet to an unoccupied space it can see.
    attack_bonus: 0
