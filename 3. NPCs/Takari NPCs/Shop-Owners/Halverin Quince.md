```statblock
# ===== BASIC INFO =====
name: Halverin Quince
image: Utility/Images/NPC Images/Halverin Quince.jpeg
layout: 5e-wide
width: 1100
image_height: 250

size: Medium
type: humanoid
race: Half-Elf
class: Shopkeeper (General Goods Merchant)
alignment: Neutral

ac: 12
hp: 27
hit_dice: 5d8

speed: 30 ft.

# ===== ABILITY SCORES =====
stats:
  - 10
  - 12
  - 11
  - 14
  - 13
  - 16

# ===== SAVES =====
saves:
  wisdom: +3
  charisma: +5

# ===== SKILLS =====
skillsaves:
  persuasion: +7
  deception: +5
  insight: +5
  intimidation: +3
  perception: +5
  stealth: +2
  athletics: +2
  arcana: +4
  history: +4
  religion: +2
  investigation: +4

# ===== ROLEPLAY INFO =====
personality_traits: |
  Speaks quickly and confidently, with a merchant’s practiced rhythm. Laughs easily, especially at their own jokes, and fills silence with commentary about prices, trends, or rumors. Constantly appraises people the way others appraise goods.

ideals: |
  Trade is the lifeblood of civilization. Fair deals keep cities alive, but clever deals keep merchants alive.

bonds: |
  Deeply loyal to their shop, viewing it as both legacy and shield. Maintains quiet relationships with caravans, dockhands, and informants who feed them information.

flaws: |
  Greedy for opportunity and easily tempted by rare or exotic items. Has difficulty refusing a deal, even when it might be dangerous.

goals: |
  Short-term: Acquire unique merchandise that no rival shop can match.  
  Long-term: Retire wealthy enough to open a second store in a major trade city.

background: |
  Born to a traveling trader and an elven archivist, this merchant learned numbers before letters and negotiation before etiquette. After years on the road, they settled down, turning a modest storefront into a respected hub for goods, gossip, and quiet deals.

# ===== SOCIAL ABILITIES =====
social_abilities:
  - name: Merchant’s Read
    desc: |
      After speaking with a creature for at least 1 minute, this NPC has advantage on Insight checks to determine that creature’s intentions regarding trade, deception, or negotiation.

  - name: Favor Economy
    desc: |
      Can call in small favors from local merchants, guards, or travelers, granting advantage on one Charisma-based check related to commerce, information, or logistics per day.

# ===== ACTIONS (OPTIONAL COMBAT) =====
actions:
  - name: Dagger
    desc: |
      Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target.
    attack_bonus: 4
    damage:
      - dice: 1d4
        bonus: 2
        type: piercing

# ===== REACTIONS =====
reactions:
  - name: Silver Tongue Deflection
    desc: |
      When targeted by a hostile creature, the NPC can impose disadvantage on the first attack roll against them as they distract, bargain, or verbally stall.

# ===== LEGENDARY ACTIONS (OPTIONAL) =====
legendary_actions: []

# ===== PASSIVE STATS =====
passive_senses:
  perception: 15
  insight: 15

languages: Common, Elvish, Dwarvish
cr: ""

```