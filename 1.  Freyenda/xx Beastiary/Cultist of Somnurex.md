```statblock
# ===== BASIC INFO =====
name: Dreambound Cultist
image: Utility/Images/Bad Guys/Cultist.jpeg
layout: 5e-wide
width: 1100
image_height: 300

size: Medium
type: Humanoid (cultist)
alignment: Chaotic Evil

ac: 15
hp: 66
hit_dice: 12d8+12

speed: 30 ft.

# ===== ABILITY SCORES =====
# STR, DEX, CON, INT, WIS, CHA
stats:
  - 10
  - 14
  - 12
  - 13
  - 15
  - 16

# ===== SAVES =====
# Set only bonuses that differ from ability mod
saves:
  wisdom: +5
  charisma: +6

# ===== SKILLS =====
skillsaves:
  perception: +5
  stealth: +4
  insight: +5

damage_resistances: psychic
damage_immunities: —
condition_immunities: frightened

senses: darkvision 60 ft., passive Perception 15
languages: Common, Deep Speech
cr: "5"

# ===== TRAITS =====
traits:
  - name: Fanatical Devotion
    desc: |
      The Dreambound Cultist has advantage on saving throws against being charmed or frightened. If the cultist is concentrating on a spell and takes damage, it has advantage on the Constitution saving throw to maintain concentration.

  - name: Somnurex’s Whisper
    desc: |
      When the Dreambound Cultist casts a spell that forces a Wisdom saving throw, it can impose disadvantage on one creature’s first saving throw against that spell once per turn.

  - name: Spellcasting
    desc: |
      The Dreambound Cultist is a 7th-level spellcaster.
      
  - name: Spells
    desc: |

      Cantrips (at will): thaumaturgy, minor illusion, mind sliver  
      1st level (4 slots): bane, command, dissonant whispers  
      2nd level (3 slots): hold person, mind spike, darkness  
      3rd level (3 slots): hypnotic pattern, fear  
      4th level (1 slot): blight

# ===== ACTIONS =====
actions:
  - name: Multiattack
    desc: |
      The Dreambound Cultist makes one Ritual Dagger attack or casts one spell.

  - name: Ritual Dagger
    desc: |
      Melee Weapon Attack: +5 to hit, reach 5 ft., one target.
    attack_bonus: 5
    damage:
      - dice: 1d6
        bonus: 3
        type: piercing

  - name: Mind-Severing Chant
    desc: |
      The cultist utters a fragment of Somnurex’s litany. One creature the cultist can see within 60 feet must succeed on a DC 14 Wisdom saving throw or be stunned until the end of its next turn.

  - name: Dreamstatic Pulse (Recharge 5–6)
    desc: |
      Psychic energy erupts in a 20-foot-radius sphere centered on the cultist. Each creature in the area must make a DC 14 Wisdom saving throw, taking 6d8 psychic damage on a failed save, or half as much damage on a successful one. Creatures that fail are also restrained until the end of their next turn.
    save_dc: 14
    save_ability: Wisdom
    damage:
      - dice: 6d8
        type: psychic

  - name: Veil Slip
    desc: |
      The Dreambound Cultist magically teleports up to 30 feet to an unoccupied space it can see. Until the start of its next turn, attack rolls against it are made with disadvantage.
    attack_bonus: 0
