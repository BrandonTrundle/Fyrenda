```statblock
name: Mawcoil Devourer
image: Utility/Images/BeastiaryImages/MawcoilDevourer.jpeg
layout: 5e-wide
width: 1100
image_height: 300

size: Large
type: Monstrosity
alignment: Neutral Evil

ac: 17
hp: 190
hit_dice: 20d10+80

speed: 30 ft., burrow 20 ft., climb 20 ft.

# ===== ABILITY SCORES =====
# STR, DEX, CON, INT, WIS, CHA
stats:
  - 22
  - 12
  - 18
  - 6
  - 14
  - 9

# ===== SAVES =====
# Set only bonuses that differ from ability mod
saves:
  strength: +10
  dexterity: +5
  constitution: +9
  intelligence: +0
  wisdom: +6
  charisma: +0

# ===== SKILLS =====
skillsaves:
  perception: +8
  stealth: +6
  insight: +6

damage_resistances: bludgeoning, piercing, and slashing from nonmagical attacks
damage_immunities: poison
condition_immunities: poisoned, frightened

senses: darkvision 120 ft., tremorsense 30 ft., passive Perception 18
languages: understands Undercommon but can’t speak
cr: "10"

# ===== TRAITS =====
traits:
  - name: Horrid Form
    desc: |
      Any creature that starts its turn within 10 feet of the Mawcoil Devourer must succeed on a DC 16 Wisdom saving throw or be frightened until the start of its next turn.

  - name: Rotting Bite
    desc: |
      A creature hit by the Mawcoil Devourer’s bite must succeed on a DC 17 Constitution saving throw or be diseased. While diseased, it takes 7 (2d6) necrotic damage at the start of each of its turns. The disease lasts until cured.

# ===== ACTIONS =====
actions:
  - name: Multiattack
    desc: |
      The Mawcoil Devourer makes two attacks: one Bite and one Constrict.

  - name: Bite
    desc: |
      Melee Weapon Attack: +10 to hit, reach 10 ft., one target.
    attack_bonus: 10
    damage:
      - dice: 3d10
        bonus: 6
        type: piercing

  - name: Constrict
    desc: |
      Melee Weapon Attack: +10 to hit, reach 10 ft., one target.
    attack_bonus: 10
    damage:
      - dice: 2d8
        bonus: 6
        type: bludgeoning

  - name: Venomous Pulse
    desc: |
      Each creature grappled by the Mawcoil Devourer must make a Constitution saving throw, taking poison damage on a failed save or half as much on a success.
    save_dc: 16
    save_ability: constitution

  - name: Toxic Breath (Recharge 5–6)
    desc: |
      The Mawcoil Devourer exhales poisonous gas in a 30-foot cone. Each creature in the area must make a Constitution saving throw. On a failed save, a creature takes poison damage and is poisoned for 1 minute. A creature can repeat the save at the end of its turn.
    save_dc: 17
    save_ability: constitution
    damage:
      - dice: 8d8
        type: poison

  - name: Burrow Hide
    desc: |
      The Mawcoil Devourer burrows into loose earth or soft stone, becoming heavily obscured until it emerges. While hidden, it has advantage on Stealth checks.
    attack_bonus: 0

# ===== LEGENDARY ACTIONS =====
legendary_actions:
  - name: Tunnel Shift
    desc: |
      The Mawcoil Devourer moves up to half its burrow speed without provoking opportunity attacks.
    roll:
      - skill: stealth

  - name: Rending Bite
    desc: |
      The Mawcoil Devourer makes one Bite attack.
    attack:
      bonus: 10
      damage_dice: 3d10
      damage_bonus: 6
      damage_type: piercing

  - name: Dreadful Aura
    desc: |
      Each creature of the Mawcoil Devourer’s choice within 10 feet must succeed on a Wisdom saving throw or be frightened for 1 minute.
    save_dc: 16
    save_ability: wisdom
    damage:
      - dice: 2d6
        bonus: 0
        type: psychic
```

### Physical Description
It drags its swollen bulk across the stone with a wet, dragging sound, its body an obscene fusion of rat-like corpulence and serpentine length. Its pale, sagging flesh splits in places, revealing scales that glisten with a sickly sheen, as though something beneath is still trying to force its way to the surface. Each movement ripples through layers of fat and muscle, creating a grotesque undulation that makes the ground seem to pulse with it.

The head is rodent in shape but stretched unnaturally long, the jaw unhinging with a slack, rubbery grotesqueness that exposes rows of teeth that have grown too many, too crooked, and too sharp. Thin tendrils of drool stretch between them, swaying as it breathes—each exhalation a shallow, labored rasp. Wisps of fur cling in patchy tufts along its upper body, thinning to nothing as the form transitions into a scaled abdomen that coils and twists with unnatural flexibility.

Its eyes are small, sunken, and bead-like, reflecting torchlight with a dull, wet glimmer. They don’t blink. They don’t track. They simply stare, as though seeing without understanding. Its limbs are short, almost vestigial, ending in twisted claws that curl inward as if shaped for holding prey close while the rest of the body crushes it.

On its underside, patches of darkened skin sag as if swollen with rot, issuing a faint, constant drip of some viscous, reddish fluid. The smell that accompanies it is impossible to ignore—stale, coppery, and deeply biological, the scent of a predator whose diet is raw and recent.

Its movements are deceptively fast for something so bloated. It surges forward with sudden violent thrusts, its mass sliding across the stone with fluid force, the sound of flesh scraping rock echoing through the tunnels long after it has passed.