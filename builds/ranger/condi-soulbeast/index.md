---
title: Condi Soulbeast
hidden: false
archive: false
hasBeginner: true
rating: Meta
role: Condi Damage
profession: Ranger
specialization: Soulbeast
conditions:
  - name: Vulnerability
    uptime: 10 stacks
  - name: Bleeding
  - name: Poisoned
  - name: Burning
code: '[&DQQeLSE3Ny55AAAAAAAAAL8AAADpFgAALhYAADQlAAAAAAAAAAAAAAAAAAA=]'
cmGuide: pug
classification:
  - 5
  - 4
  - 3
  - 2
  - 3
date: 2022-07-31T11:40:09.644Z
---

<Warning>

This build is strong in full condi groups ([team comps](/guides/effective-comp)), especially on Ensolyss, 100CM and some T4 bosses. In power groups and other bosses this build will fall massively behind <BuildLink specialization="Soulbeast" build="Power Soulbeast"/> - the power damage counterpart. 

</Warning>

Condi <Specialization name="Soulbeast"/> is a DPS build with high sustained damage that also provides strong party buffs with <Skill name="Sun Spirit"/>, <Skill name="One Wolf Pack"/>, and crowd control (CC) skills. This build is mostly used for 100CM, for most other fractals, especially if your group is playing power builds, you will be better off playing the power variant found [here](/builds/ranger/power-soulbeast/).

This build is rather self sufficient due to:

- Boon extension by <Trait name="Essence of speed"/>, <Skill name="We heal as one"/>
- Good CC with <Skill id="46432"/> and <Skill name="Concussion Shot"/>
- High mobility via <Skill name="Instinctive Engage"/> and <Skill name="Quick Shot"/>

Overall this is a very well-rounded build that is rewarding to play in both PuGs and organized teams alike.

<Beginner>

This guide will focus on the Shortbow + Dagger/Torch variant of the build with <Trait name="Light on your Feet"/> which is frequently played in fractals. There are some alternatives for specific situations with slightly varying rotations. Once you can execute the step-by-step rotation provided below without spending too much thought on it and are confident with the utility options, check out the advanced page for extra information. Feel free to swap to the advanced page early if you feel like you are missing some information on additional (less common) utility skills, trait swaps, or other weapon variants.

</Beginner>

<Divider text="Equipment"/>

<Beginner>

<CharacterWithAr>
<Character title="Krait Runes" gear={{
  "profession": "Ranger",
  "weight": "Medium",
  "gear": [
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper"
  ],
  "attributes": {
    "Health": 21902,
    "Armor": 2361,
    "Power": 2923,
    "Precision": 1733,
    "Toughness": 1243,
    "Vitality": 1598,
    "Ferocity": 0,
    "Condition Damage": 2642,
    "Expertise": 797,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0.5313333333333333,
    "Boon Duration": 0.162,
    "Critical Chance": 0.7490476190476191,
    "Critical Damage": 1.5,
    "Power Coefficient": 2165.1,
    "Power2 Coefficient": 0,
    "Burning Coefficient": 2.42,
    "Bleeding Coefficient": 28.0878619047619,
    "Poison Coefficient": 16.42,
    "Torment Coefficient": 0.16,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Bleeding Duration": 0.5,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 7768.035831324402,
    "Power DPS": 6476.154939699832,
    "Power2 DPS": 0,
    "Siphon DPS": 139.75,
    "Bleeding Damage": 373.6425524999999,
    "Bleeding Stacks": 56.1757238095238,
    "Bleeding DPS": 20989.640832725494,
    "Burning Damage": 841.1686874999999,
    "Burning Stacks": 3.705826666666667,
    "Burning DPS": 3117.2253533025,
    "Confusion Damage": 331.6337625,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 373.53890624999997,
    "Poison Stacks": 25.144493333333337,
    "Poison DPS": 9392.44653794375,
    "Torment Damage": 419.53387499999997,
    "Torment Stacks": 0.24501333333333336,
    "Torment DPS": 102.79139316,
    "Damage": 40218.00905683157,
    "Effective Health": 102906710.44776121,
    "Survivability": 52316.57877364576,
    "Effective Healing": 390,
    "Healing": 390
  },
  "runeId": 24762,
  "runeName": "Krait",
  "infusions": [
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432
  ],
  "weapons": {
    "weapon1MainType": "Dagger",
    "weapon1MainSigil1Id": 44944,
    "weapon1OffType": "Torch",
    "weapon1OffSigilId": 24560,
    "weapon2MainType": "Short Bow",
    "weapon2MainSigil1Id": 44944,
    "weapon2MainSigil2Id": 24560
  },
  "consumables": {
    "foodId": 91878,
    "utilityId": 48917
  },
  "skills": {
    "healId": 31914,
    "utility1Id": "",
    "utility2Id": 12537,
    "utility3Id": 40498,
    "eliteId": 45717
  },
  "assumedBuffs": [
    {
      "id": "might",
      "type": "Boon"
    },
    {
      "id": "fury",
      "type": "Boon"
    },
    {
      "id": "protection",
      "type": "Boon"
    },
    {
      "id": "vulnerability",
      "type": "Condition"
    },
    {
      "id": "jade-bot",
      "gw2id": 96613,
      "type": "Item"
    },
    {
      "id": "omnipotion",
      "gw2id": 79722,
      "type": "Item"
    }
  ]
}}>

If you do not have a Jade Bot Core: Tier 10, you will have a slightly lower duration on your non-bleeding conditions but the build does not change!

</Character>
</CharacterWithAr>

</Beginner>

<Advanced>

<CharacterWithAr>
<Character advanced title="Afflicted Runes" gear={{
  "profession": "Ranger",
  "weight": "Medium",
  "gear": [
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper"
  ],
  "attributes": {
    "Health": 21902,
    "Armor": 2361,
    "Power": 2923,
    "Precision": 1733,
    "Toughness": 1243,
    "Vitality": 1598,
    "Ferocity": 0,
    "Condition Damage": 2632,
    "Expertise": 897,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0.798,
    "Boon Duration": 0.162,
    "Critical Chance": 0.7490476190476191,
    "Critical Damage": 1.5,
    "Power Coefficient": 2165.1,
    "Power2 Coefficient": 0,
    "Burning Coefficient": 2.42,
    "Bleeding Coefficient": 27.9278619047619,
    "Poison Coefficient": 16.26,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Bleeding Duration": 0.2,
    "Poison Duration": 0.1,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 7768.035831324402,
    "Power DPS": 6476.154939699832,
    "Power2 DPS": 0,
    "Siphon DPS": 139.75,
    "Bleeding Damage": 357.44481499999995,
    "Bleeding Stacks": 55.79986808571428,
    "Bleeding DPS": 19945.373524922543,
    "Burning Damage": 805.0715,
    "Burning Stacks": 4.35116,
    "Burning DPS": 3502.9949079400003,
    "Confusion Damage": 317.28445,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 357.41703125,
    "Poison Stacks": 30.861480000000004,
    "Poison DPS": 11030.418561581251,
    "Torment Damage": 401.34075,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 41094.69193414362,
    "Effective Health": 102906710.44776121,
    "Survivability": 52316.57877364576,
    "Effective Healing": 390,
    "Healing": 390
  },
  "runeId": 24687,
  "runeName": "Afflicted",
  "infusions": [
    37130,
    37130,
    37130,
    37130,
    86113,
    86113,
    86113,
    86113,
    86113,
    86113,
    86113,
    86113,
    86113,
    86113,
    86113,
    86113,
    86113,
    86113
  ],
  "weapons": {
    "weapon1MainType": "Dagger",
    "weapon1MainSigil1Id": 44950,
    "weapon1OffType": "Torch",
    "weapon1OffSigilId": 24560,
    "weapon2MainType": "Short Bow",
    "weapon2MainSigil1Id": 44950,
    "weapon2MainSigil2Id": 24560
  },
  "consumables": {
    "foodId": 91876,
    "utilityId": 48917,
    "infusionId": 86113
  },
  "skills": {
    "healId": 31914,
    "utility1Id": "",
    "utility2Id": 12537,
    "utility3Id": 40498,
    "eliteId": 45717
  },
  "assumedBuffs": [
    {
      "id": "might",
      "type": "Boon"
    },
    {
      "id": "fury",
      "type": "Boon"
    },
    {
      "id": "protection",
      "type": "Boon"
    },
    {
      "id": "vulnerability",
      "type": "Condition"
    },
    {
      "id": "jade-bot",
      "gw2id": 96613,
      "type": "Item"
    },
    {
      "id": "omnipotion",
      "gw2id": 79722,
      "type": "Item"
    }
  ]
}}>

This builds damage depends on the <Skill name="Vulture Stance"/> uptime you and your party have. The higher the uptime, the better it will preform. In general it is around the same damage as the Krait rune build with higher potential damage, depending on boss and comp. Choose the build you are more comfortable with, they are both good choices.

This build uses the Jade Bot Core: Tier 10 in combination with 14 <Item name="Spiteful +9 Agony Infusion"/> to cap Bleeding duration. If you do not have the Jade Core, run all 18 <Item name="Spiteful +9 Agony Infusion"/>.

</Character>
<Character title="Krait Runes" gear={{
  "profession": "Ranger",
  "weight": "Medium",
  "gear": [
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper"
  ],
  "attributes": {
    "Health": 21902,
    "Armor": 2361,
    "Power": 2923,
    "Precision": 1733,
    "Toughness": 1243,
    "Vitality": 1598,
    "Ferocity": 0,
    "Condition Damage": 2732,
    "Expertise": 797,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0.5313333333333333,
    "Boon Duration": 0.162,
    "Critical Chance": 0.7490476190476191,
    "Critical Damage": 1.5,
    "Power Coefficient": 2165.1,
    "Power2 Coefficient": 0,
    "Burning Coefficient": 2.42,
    "Bleeding Coefficient": 28.0878619047619,
    "Poison Coefficient": 16.42,
    "Torment Coefficient": 0.16,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Bleeding Duration": 0.5,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 7768.035831324402,
    "Power DPS": 6476.154939699832,
    "Power2 DPS": 0,
    "Siphon DPS": 139.75,
    "Bleeding Damage": 384.81953999999996,
    "Bleeding Stacks": 56.1757238095238,
    "Bleeding DPS": 21617.516195547996,
    "Burning Damage": 862.878375,
    "Burning Stacks": 3.705826666666667,
    "Burning DPS": 3197.6776921650003,
    "Confusion Damage": 341.298075,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 384.04359374999996,
    "Poison Stacks": 25.144493333333337,
    "Poison DPS": 9656.581582756251,
    "Torment Damage": 432.1395,
    "Torment Stacks": 0.24501333333333336,
    "Torment DPS": 105.87993936000001,
    "Damage": 41193.56034952908,
    "Effective Health": 102906710.44776121,
    "Survivability": 52316.57877364576,
    "Effective Healing": 390,
    "Healing": 390
  },
  "runeId": 24762,
  "runeName": "Krait",
  "infusions": [
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130
  ],
  "weapons": {
    "weapon1MainType": "Dagger",
    "weapon1MainSigil1Id": 44944,
    "weapon1OffType": "Torch",
    "weapon1OffSigilId": 24560,
    "weapon2MainType": "Short Bow",
    "weapon2MainSigil1Id": 44944,
    "weapon2MainSigil2Id": 24560
  },
  "consumables": {
    "foodId": 91878,
    "utilityId": 48917,
    "infusionId": 37130
  },
  "skills": {
    "healId": 31914,
    "utility1Id": "",
    "utility2Id": 12537,
    "utility3Id": 40498,
    "eliteId": 45717
  },
  "assumedBuffs": [
    {
      "id": "might",
      "type": "Boon"
    },
    {
      "id": "fury",
      "type": "Boon"
    },
    {
      "id": "protection",
      "type": "Boon"
    },
    {
      "id": "vulnerability",
      "type": "Condition"
    },
    {
      "id": "jade-bot",
      "gw2id": 96613,
      "type": "Item"
    },
    {
      "id": "omnipotion",
      "gw2id": 79722,
      "type": "Item"
    }
  ]
}}>

If you do not have a Jade Bot Core: Tier 10, you will have a slightly lower duration on your non-bleeding conditions but the build does not change!

</Character>
<Character advanced title="Hybrid Soulbeast" gear={{
  "profession": "Ranger",
  "weight": "Medium",
  "gear": [
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper"
  ],
  "attributes": {
    "Health": 22202,
    "Armor": 2511,
    "Power": 3073,
    "Precision": 1883,
    "Toughness": 1393,
    "Vitality": 1628,
    "Ferocity": 910,
    "Condition Damage": 2657,
    "Expertise": 748,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0.49866666666666665,
    "Boon Duration": 0.162,
    "Critical Chance": 0.9704761904761905,
    "Critical Damage": 2.1066666666666665,
    "Power Coefficient": 2246,
    "Power2 Coefficient": 0,
    "Burning Coefficient": 1.8,
    "Bleeding Coefficient": 23.105333333333334,
    "Poison Coefficient": 5.34,
    "Torment Coefficient": 0.19,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Bleeding Duration": 0.5,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 13927.673085687777,
    "Power DPS": 12045.265210032632,
    "Power2 DPS": 0,
    "Siphon DPS": 139.75,
    "Bleeding Damage": 386.6649815,
    "Bleeding Stacks": 46.17985955555555,
    "Bleeding DPS": 17856.134540721487,
    "Burning Damage": 869.8930875000001,
    "Burning Stacks": 2.6976,
    "Burning DPS": 2346.62359284,
    "Confusion Damage": 343.14813250000003,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 309.1543,
    "Poison Stacks": 8.00288,
    "Poison DPS": 2474.1247643839997,
    "Torment Damage": 434.165325,
    "Torment Stacks": 0.28474666666666665,
    "Torment DPS": 123.62712907599999,
    "Damage": 34985.52523705412,
    "Effective Health": 110943725.37313434,
    "Survivability": 56402.50400261024,
    "Effective Healing": 390,
    "Healing": 390
  },
  "runeId": 24762,
  "runeName": "Krait",
  "infusions": [
    86113,
    86113,
    86113,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130,
    37130
  ],
  "weapons": {
    "weapon1MainType": "Axe",
    "weapon1MainSigil1Id": 44944,
    "weapon1OffType": "Torch",
    "weapon1OffSigilId": 24560,
    "weapon2MainType": "Dagger",
    "weapon2MainSigil1Id": 44944,
    "weapon2OffType": "Axe",
    "weapon2OffSigilId": 24560
  },
  "consumables": {
    "foodId": 91876,
    "utilityId": 48917,
    "infusionId": 37130
  },
  "skills": {
    "healId": 31914,
    "utility1Id": 12633,
    "utility2Id": 12537,
    "utility3Id": 40498,
    "eliteId": 45717
  },
  "assumedBuffs": [
    {
      "id": "might",
      "type": "Boon"
    },
    {
      "id": "fury",
      "type": "Boon"
    },
    {
      "id": "protection",
      "type": "Boon"
    },
    {
      "id": "vulnerability",
      "type": "Condition"
    },
    {
      "id": "jade-bot",
      "gw2id": 96613,
      "type": "Item"
    },
    {
      "id": "omnipotion",
      "gw2id": 79722,
      "type": "Item"
    }
  ]
}}>

This build uses the Jade Bot Core: Tier 10 in combination with 15 <Item name="Malign +9 Agony Infusion"/> and 3 <Item name="Spiteful +9 Agony Infusion"/>. However running 18 <Item name="Malign +9 Agony Infusion"/> is a minimal DPS loss.

This build is mainly used on 100CM, although can preform well on other fights as well. On 100CM it can preform slightly better than <Specialization name="Soulbeast" text="Condi Soulbeast"/> with a more engaging rotation, however mistakes will tank your damage and can be very punishing, especially in less experienced groups.

If you need to drop a utiltiy skill <Skill name="Sic Em"/> should be replaced and you will want to use either [Warthog](https://wiki.guildwars2.com/wiki/Juvenile_Warthog) or [Bristleback](https://wiki.guildwars2.com/wiki/Juvenile_Bristleback) as your pet.

</Character>
</CharacterWithAr>

</Advanced>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Card title="Traits">
<Tabs>
<Tab title="Condi Soulbeast">
<Traits traits1Id="33" traits1="Wilderness Survival" traits1SelectedIds="1099,1101,1701" traits2Id="30" traits2="Skirmishing" traits2SelectedIds="1069,1846,1912" traits3Id="55" traits3="Soulbeast" traits3SelectedIds="2071,2161,2128" unembossed/>
</Tab>
<Tab title="Hybrid Soulbeast">
<Traits traits1Id="32" traits1="Beastmastery" traits1SelectedIds="1606,970,1066" traits2Id="30" traits2="Skirmishing" traits2SelectedIds="1069,1846,1888" traits3Id="55" traits3="Soulbeast" traits3SelectedIds="2071,2161,2128" unembossed/>
</Tab>
</Tabs>
</Card>

<Beginner>

<Card title="Defiance Bar Damage">

|                                            |                                                                                   |
| ------------------------------------------ | --------------------------------------------------------------------------------- |
| <Skill id="46432" size="big" disableText/> | 300 damage (F2 in <Skill id="42944"/>)                                            |
| <Skill id="12508" size="big" disableText/> | 200 damage (Shortbow 5)                                                           |
| <Skill id="12507" size="big" disableText/> | 50/s <Condition name="Immobile"/>, 15/s <Condition name="Crippled"/> (Shortbow 4) |
| <Skill id="12490" size="big" disableText/> | 33/s <Condition name="Chilled"/>, 20/s <Condition name="Weakness"/> (Axe 3)       |

</Card>

</Beginner>

</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">

|                                                       |                                                                                                                                                                                                                                                                                         |
| ----------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill name="Moa Stance" size="big" disableText/>     | A replacement for <Skill name="Vipers Nest"/>, this allows your <Specialization name="Renegade"/> to lower their boon duration and deal substantially more DPS! Alternatively if you have more than one <Specialization name="Soulbeast"/>, one can drop <Skill name="Sun Spirit"/>. |
| <Skill name="Vipers Nest" size="big" disableText/>    | Your standard 3rd utility. Only taken if you do not need to use a more supportive skill.                                                                                                                                        |
| <Skill name="Dolyak Stance" size="big" disableText/>    | Can be used to share <Boon name="Stability"/>.                                                                                                                                        |
| <Skill name="Spike Trap" size="big" disableText/>    | Can be taken to for extra CC, while being used in rotation for <Condition name="Bleeding"/> stacks.                                                                                                                                        |
| <Skill name="Bear stance" size="big" disableText/>    | A party-wide condi cleanse through <Trait name="leaderofthepack"/>.                                                                                                                                                                                                                     |
| <Skill name="Healing Spring" size="big" disableText/> | Area condi cleanse, taken if your party needs a long lasting condi cleanse. Very useful on 100CM!                                                                                                                                                                                       |

</Card>
<Card title="Pets">

[Warthog](https://wiki.guildwars2.com/wiki/Juvenile_Warthog) - Best CDPS pet that also brings CC, also this is the pet you use in <Skill id="42944"/>.

<Advanced>

[Bristleback](https://wiki.guildwars2.com/wiki/Juvenile_Bristleback) - Used to precast some extra Bleeding. Is also the best CDPS pet for when there are multiple targets. Only take Bristleback if you can consistently get 5+ hits from <Skill name="Rain of Spikes"/> without delaying the skill too much.

</Advanced>

[Lynx](https://wiki.guildwars2.com/wiki/Juvenile_Lynx) - Best single target CDPS pet. Taken if you don't need the CC from Warthog

</Card>
</GridItem>
</Grid>

<Advanced>

<Divider text="Further information"/>

<Grid>
<GridItem sm="7">
<Card title="Situational Traits">

|                                                         |                                                                                                                                |
| ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| <Trait name="Essence of Speed" size="big" disableText/> | Take this instead of <Trait name="Predators Cunning"/> if boon uptime in your party is bad and you want some extra generation. |

</Card>

<Card title="Off-hand Dagger">

Running an off-hand Dagger is similar DPS to Torch providing you can flank permanently and your group can't make use of the fire field from <Skill name="Bonfire"/>. It also has the benefit of having an evade through using <Skill id="12478"/>.

</Card>
<Card title="Swap Weapons">

- A <Item id="75325"/> (selected attribute does not matter!) to blast might when prestacking boons.
- A weapon set to precast <Item id="24609"/> and <Item id="24599"/> before getting into fight.

</Card>
</GridItem>

<GridItem sm="5">

<Card title="Defiance Bar Damage">

|                                            |                                                                                   |
| ------------------------------------------ | --------------------------------------------------------------------------------- |
| <Skill id="46432" size="big" disableText/> | 300 damage (F2 in <Skill id="42944"/>)                                            |
| <Skill id="12508" size="big" disableText/> | 200 damage (Shortbow 5)                                                           |
| <Skill name="Spike Trap" size="big" disableText/> | 232 damage       |
| <Skill id="12507" size="big" disableText/> | 50/s <Condition name="Immobile"/>, 15/s <Condition name="Crippled"/> (Shortbow 4) |
| <Skill id="12490" size="big" disableText/> | 33/s <Condition name="Chilled"/>, 20/s <Condition name="Weakness"/> (Axe 3)       |


</Card>
</GridItem>
</Grid>

</Advanced>

<Divider text="Rotation / Skill usage"/>

<Advanced>
<Grid>
<GridItem sm="6">
<Card title="Information">

When playing <Specialization name="Soulbeast" text="Condi Soulbeast"/> in 100CM, <Trait name="Light on your Feet"/> is much more attractive choice than <Trait name="Quickdraw"/> which is used in raids. The reason is that Ai moves around far too much for you to be able to benefit from using skills like <Skill name="Bonfire"/> twice in most cases. Also with some strategic dodging during movement and downtime you can keep a very high <Trait name="Light on your Feet"/> uptime, especially during your bursts which leads to very high DPS.

The rotation in general is very simple, just keep rotating between your Shortbow and Dagger/Torch set using your utility skills as often as you can. When you get to the point of auto-attacking use your <Skill id="42944"/> skills to fill.
</Card>
<Card title="Shortbow Golem Rotation">

1.  <Skill name="Vipers Nest"/>
2.  <Skill name="One Wolf Pack"/>
3.  <Skill name="Poison Volley"/>
4.  <Skill name="Crippling Shot"/>
5.  <Skill name="Concussion Shot"/>
6.  `Weapon Swap`
7.  <Skill name="Vulture Stance"/> + <Skill name="Sharpening Stone"/>
8.  <Skill name="Double Arc"/>
9.  <Skill name="Throw Torch"/>
10. <Skill name="Bonfire"/>
11. <Skill id="44514"/>
12. <Skill name="Primal Cry"/>
13. `Autoattack chain x2`
14. <Skill name="Double Arc"/>
15. `Autoattack chain x3`
16. <Skill name="Double Arc"/>
17. <Skill name="Throw Torch"/>
18. `Weapon Swap`
19. <Skill name="Poison Volley"/>
20. <Skill name="Crippling Shot"/>
21. `Autoattack`
22. <Skill id="44514"/>
23. `Autoattack`
24. <Skill name="Concussion Shot"/>
25. <Skill name="Poison Volley"/>
26. `Autoattack`
27. <Skill name="Primal Cry"/>
28. `Autoattack`
29. <Skill name="Poison Volley"/>
30. `Autoattack`
31. <Skill name="Crippling Shot"/>
32. Repeat from `Step 5`

</Card>
</GridItem>

<GridItem sm="6">
<Card title="Shortbow Golem Rotation">

<Video youtube="iKKWM4F3ayg" caption="by Eren"/>
</Card>
<Card title="Precasting">

When precasting in fractals we want to stack as many useful boons with as much duration as possible, these being <Boon name="Might"/>, <Boon name="Fury"/>, <Boon name="Quickness"/>, <Boon name="Alacrity"/> and <Boon name="Swiftness"/>. We can also cast useful unique effects, for a <Specialization name="Soulbeast" text="Condi Soulbeast"/> this means your stances such as <Skill name="Vulture Stance"/>, <Skill name="Moa Stance"/> and <Skill name="One Wolf Pack"/>.

As a <Specialization name="Soulbeast" text="Condi Soulbeast"/> there are also multiple skills and traits that can be quickly pre-stacked for extra condis and damage at the start of fights. These aren't necessary to do and depending on the encounter, not all are possible, but if you have the time and can make use of them they are worth using.

### **Stances**

As a <Specialization name="Soulbeast" text="Condi Soulbeast"/> we have three important stances to share with <Trait name="Leader of the Pack"/> when precasting.

**<Skill name="Moa Stance"/> -** This will increase your party members' boon duration by 66%, which when added to the conversion from <Item id="74185"/> means your party will have close to 100% boon duration without even swapping gear. This means any boons your party stacks duration will be close to double.

**<Skill name="Vulture Stance"/> -** This will help your party stack some initial condis and some initial <Boon name="Might"/> at the start of the fight and should be the last thing you cast before taking the _Mistlock Singularity_.

### **Boons**

**<Boon name="Might"/> -** Before starting fights we want to have 25 stacks of <Boon name="Might"/>, the standard way of this in fractals is by blasting a fire field. If no one else in your party will provide one you can use <Skill name="Bonfire"/> on a torch. In the fire field, we want to use blast finishers which each one will give 3 stacks of <Boon name="Might"/> for 20 seconds (not accounting for boon duration). Our main blast is from <Skill name="Call of the Wild"/> which can be used twice and also gives 6 stacks of might for 10 seconds along with the blast (again not accounting for boon duration).

**<Boon name="Fury"/> and <Boon name="Swiftness"/> -** We can provide these boons again by using <Skill name="Call of the Wild"/>. These boons stack up to 30 seconds, so by blasting twice with Warhorn and under the effect of <Skill name="Moa Stance"/>, we can provide the maximum duration for our party.

### **Traits**

**<Trait name="Poison Master"/> -** If you can get into combat before precasting you can use <Skill id="40588"/> (Merged F3) to proc <Trait name="Poison Master"/> for some extra <Condition name="poisoned" text ="Poison"/> stacks on your opener

**<Trait name="Light on your Feet"/> -** Stacks in duration by dodging and using <Skill name="Quick Shot"/>. This will increase your condi duration which means if you are playing with <Item id="24687"/> means your <Condition name="Poisoned"/> duration will be capped. It will also increase your strike damage (power) for a bit of extra damage.

### **Skills**

**<Skill name="Sharpening Stone"/> -** Used for some additional <Condition name="Bleeding"/> at the start of the fight. If you use a second time while you still have charges left, the original charges will be overwritten.

**<Skill name="Sharpen Spines"/> -** Can be precasted by merging with Bristleback for extra bleeding at the start of the fight. This stacks in intensity so you can use the skill after taking the mistlock giving you 10 stacks of <Condition name="Bleeding"/>.

**<Skill name="Crippling Shot"/> -** Can be precasted giving you the effect _Blood Thirst_ lasting for 11 seconds. When you have this effect and are merged your next 3 attacks will inflict 1 stack of <Condition name="Bleeding"/> lasting for 12 seconds.

**<Skill name="Double Arc"/> -** Can be precasted giving you the effect _Poisonous Strike_ lasting for 7 seconds. When you have this effect and are merged your next 2 attacks will inflict 1 stack of <Condition name="poisoned" text ="Poison"/> lasting for 6 seconds. This skill can be used twice giving you 3 charges.
</Card>

</GridItem>
</Grid>
</Advanced>

<Beginner>

<Grid>
<GridItem xs="12" sm="7">
<Card title="Step-by-Step Rotation">

**Step 1: Weapon Rotation**

The highest priority skills are your weapon skills, namely skills 2,4, and 5 on both sets. The weapon skill rotation will be the backbone of your rotation and you will not want to interrupt it for any other skill. Any further steps will introduce more skills to fill the gaps between your weapon skills, so it is a good idea to spend some time practicing this step.

The weapon rotation is:

1. Start on Shortbow and use <Skill name="Poison Volley"/>, <Skill name="Crippling Shot"/> and <Skill name="Concussion Shot"/>.
2. Swap to Dagger/Torch and use <Skill name="Double Arc"/>, <Skill name="Throw Torch"/> and <Skill name="Bonfire"/>.
3. Keep using these skills off-cooldown. Your 3rd <Skill name="Double Arc"/> and 2nd <Skill name="Throw Torch"/> should come back at the same time. Use them and swap back to Shortbow.
4. Use <Skill name="Poison Volley"/>, <Skill name="Crippling Shot"/> and <Skill name="Concussion Shot"/> off-cooldown (with this priority) until you used <Skill name="Poison Volley"/> 3 times.
5. Repeat step 2.

**Step 2: Beastmode Skills**

Your <Skill name="Beastmode"/> skills will fill some gaps in your weapon rotation. Use them off-cooldown but do not interrupt or delay your weapon rotation for them. The priority depends on the Pet you are using.

For Lynx, the priority is:

1. <Skill id="44514"/>
2. <Skill id="40588"/>

For Warthog, the priority is:

1. <Skill id="46432"/>
2. <Skill id="41406"/>
3. <Skill id="40588"/>

Keep in mind that <Skill id="46432"/> is also a CC skill, so delay it for break bars if necessary but try not to delay it for too long if possible.

**Step 3: Utility Skills**

Next up, we want to incorporate our Utility Skills. These will generally also be used off-cooldown with a higher priority than the <Skill name="Beastmode"/> skills.

- When running with <Skill name="Sun Spirit"/>, make sure to keep in on the group as best as possible. If you know the boss will not move within the next 15 seconds, you can use <Skill name="Solar Flare"/> as an extra filler skill to inflict some <Condition name="Burning"/>.
- <Skill name="One Wolf Pack"/> is your highest priority utility skill. Use it off-cooldown but don't waste it in split phases. Make sure everyone is in your range and can attack the boss when you cast it.
- When running <Skill name="Vipers Nest"/>, use it off-cooldown but make sure to not use it right before the boss moves.
- <Skill name="Sharpening Stone"/> and <Skill name="Vulture Stance"/> are instant-cast so you can use them off-cooldown, even while casting other skills. Make sure to be in the range of your allies when using <Skill name="Vulture Stance"/>.

**Step 4: Easy Precasts**

Lastly, we will look at some easy precasts you can (almost) always do with low effort but a good reward:

1. <Skill name="Double Arc"/>, <Skill name="Crippling Shot"/> and <Skill name="Sharpening Stone"/> all provide a boost to your next attacks after being used. You can use these before the fight if you do not get into combat by doing so (no other enemies around). This becomes even more efficient if a Mistlock Singularity is present to reset the skill cooldowns.
2. If a Mistlock Singularity is present, you can cast your Stances as well, namely <Skill name="One Wolf Pack"/> and <Skill name="Vulture Stance"/>.

</Card>

<Card title="Improving Further">

Once you are comfortable with the above steps, you are doing the full rotation and will be able to deal great damage.

There will be a few additional things on the advanced page to improve further but if you got here, you already know the most important things and these will have a smaller impact than what you learned so far.

Most of the additional steps will be extra precasts to have a higher damage spike or help with providing boons for your party at the Mistlock Singularity.

</Card>

</GridItem>
<GridItem xs="12" sm="5">

<Beginner>
<Card title="Step-by-Step Video">

This video shows the step-by-step approach to the rotation listed on the left.

<Video youtube="jfMwOw722Z0" caption="by Ascers"/>

</Card>
</Beginner>

<Card title="Shortbow Golem Rotation">

This video shows the full rotation on the golem.

<Video youtube="iKKWM4F3ayg" caption="by Eren"/>

</Card>
</GridItem>
</Grid>
</Beginner>
