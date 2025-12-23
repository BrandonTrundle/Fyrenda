```statblock
# ===== BASIC INFO =====
name: Father Thorne
image: Utility/Images/Bad Guys/Cultist.jpeg
layout: 5e-wide
width: 1100
image_height: 300

size: Medium
type: Humanoid (cultist)
alignment: Lawful Evil

ac: 16
hp: 110
hit_dice: 13d8+52

speed: 30 ft.

# ===== ABILITY SCORES =====
# STR, DEX, CON, INT, WIS, CHA
stats:
  - 10
  - 14
  - 18
  - 14
  - 16
  - 18

# ===== SAVES =====
# Set only bonuses that differ from ability mod
saves:
  constitution: +8
  wisdom: +7
  charisma: +8

# ===== SKILLS =====
skillsaves:
  perception: +7
  insight: +7
  religion: +6

damage_resistances: psychic, necrotic
damage_immunities: —
condition_immunities: frightened

senses: darkvision 60 ft., passive Perception 17
languages: Common, Deep Speech
cr: "9"

# ===== TRAITS =====
traits:
  - name: Voice of the Sleeper
    desc: |
      Father Thorne has advantage on Constitution saving throws to maintain concentration. When he succeeds on a concentration saving throw, he gains 10 temporary hit points.

  - name: Ritual Conduit
    desc: |
      While within 30 feet of an allied Dreambound creature, Father Thorne adds +2 to his spell save DC.

  - name: Spellcasting
    desc: |
      Father Thorne is a 9th-level spellcaster. His spellcasting ability is Charisma (spell save DC 16, +8 to hit with spell attacks).

  - name: Spells
    desc: |
      Cantrips (at will): thaumaturgy, minor illusion, mind sliver  
      1st level (4 slots): bane, command, dissonant whispers  
      2nd level (3 slots): hold person, mind spike  
      3rd level (3 slots): Somnurex's Magic Missle, hypnotic pattern  
      4th level (3 slots): blight, blight  
      5th level (1 slot): dominate person

# ===== ACTIONS =====
actions:
  - name: Multiattack
    desc: |
      Father Thorne casts one spell or makes one Ritual Dagger attack.

  - name: Ritual Dagger
    desc: |
      Melee Weapon Attack: +6 to hit, reach 5 ft., one target.
    attack_bonus: 6
    damage:
      - dice: 1d6
        bonus: 3
        type: piercing

  - name: Somnurex’s Edict
    desc: |
      Father Thorne speaks a command infused with Somnurex’s will. One creature he can see within 60 feet must succeed on a DC 16 Wisdom saving throw or be paralyzed until the end of its next turn.
    save_dc: 16
    save_ability: Wisdom

  - name: Veilbound Step
    desc: |
      Father Thorne magically teleports up to 30 feet to an unoccupied space he can see. Until the start of his next turn, he has advantage on saving throws.
    attack_bonus: 0
