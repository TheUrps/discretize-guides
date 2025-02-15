---
title: Condi (Alac) Specter
hidden: false
archive: false
hasBeginner: true
rating: Good
role: Condi Damage
profession: Thief
specialization: Specter
conditions:
  - name: Vulnerability
    uptime: 20 stacks
  - name: Poisoned
  - name: Bleeding
  - name: Torment
boons:
  - name: Fury
    uptime: 75%
    variant: party
  - name: Might
    uptime: 5 stacks
    variant: party
  - name: Swiftness
    uptime: 75%
    variant: party
code: "[&DQUcGywfRxcMAQAACwEAAC8BAAA+AQAADgEAAAAAAAAAAAAAAAAAAAAAAAA=]"
classification:
  - 5
  - 4
  - 3
  - 2
  - 3
compositions: null
date: 2022-07-31T13:25:08.948Z
cmGuide: ""
---

<Advanced>
<Warning>
<Specialization text="Condi Specter" name="Specter"/> is a very strong build, especially in fractal CMs. However, like all condi thief builds it does suffer from a lack of cleave damage, which is important in T4s. We suggest that you also consider gearing <BuildLink build="Power Daredevil" specialization="Daredevil"/> to swap to on certain sections of T4 fractals where cleave is important and power damage is more suited to the boss. By swapping between both builds and also learning skips, you can carry your party and vastly speed up a fractal clear.
</Warning>
</Advanced>

The **<Specialization text="Condi Specter" name="Specter"/>** is a high DPS condition build with great team support options. It offers large amounts of <Effect name="Barrier"/> for your party, some healing and a small amount of <Boon name="Might"/> and <Boon name="Swiftness"/> by targeting allied players.

<Advanced>

The value of this build comes from the pure damage that it will bring, which is inflated by the **<Specialization text="Condi Soulbeast" name="Soulbeast"/>**'s <Skill id="40498"/>, on top of Venom Skills which can be precast on the _Mistlock Singularity_, and cast again as soon as your allies have consumed them by attacking the target.

</Advanced>

<Beginner>

The beginner version of this guide will focus on the most important utility options and try to teach a slightly simplified rotation step-by-step while giving some notes on what you can do to optimize in the future.

The advanced page provides a more complete overview of the utilities the <Specialization name="Thief"/> has to offer. Once you can execute the step-by-step rotation provided below without spending too much thought on it and are confident with the utility options provided here, head over and check out the advanced page for some extra information. Feel free to swap to the advanced page early if you feel like you are missing some information on additional (less common) utility skills or trait swaps.

<Information>

Although this build lists 162 <Attribute name="Agony Resistance"/>, it is not a strict requirement! We recommend getting started with this build anyway - even if it might be suboptimal while being in Tier 1 or 2 fractals. Keep upgrading your <Attribute name="Agony Resistance"/> until you reach the suggested variant. In the beginning, it is much more important to learn about fractal mechanics and your skills rather than equipping optimal gear.

</Information>
</Beginner>

<Divider text="Equipment"/>
<Beginner>
<CharacterWithAr>  
<Character title="DPS Specter" gear={{
  "profession": "Thief",
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
    "Health": 16425,
    "Armor": 2361,
    "Power": 2923,
    "Precision": 1633,
    "Toughness": 1243,
    "Vitality": 1478,
    "Ferocity": 0,
    "Condition Damage": 2435,
    "Expertise": 1014,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0.6759999999999999,
    "Boon Duration": 0.162,
    "Critical Chance": 0.6014285714285714,
    "Critical Damage": 1.5,
    "Power Coefficient": 2131,
    "Power2 Coefficient": 0,
    "Burning Coefficient": 0.52,
    "Bleeding Coefficient": 2.59,
    "Poison Coefficient": 19.782,
    "Torment Coefficient": 20.25,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Poison Duration": 0.33,
    "Outgoing Healing": 0.2,
    "Torment Duration": 0.5,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 7334.034576428571,
    "Power DPS": 6018.0314525873255,
    "Power2 DPS": 0,
    "Siphon DPS": 158.75600000000003,
    "Bleeding Damage": 280.72700000000003,
    "Bleeding Stacks": 4.34084,
    "Bleeding DPS": 1218.5909906800002,
    "Burning Damage": 849.0697500000001,
    "Burning Stacks": 0.87152,
    "Burning DPS": 739.9812685200001,
    "Confusion Damage": 332.02105000000006,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 398.90956000000006,
    "Poison Stacks": 39.564,
    "Poison DPS": 15782.457831840002,
    "Torment Damage": 460.99515000000014,
    "Torment Stacks": 40.5,
    "Torment DPS": 18670.303575000005,
    "Damage": 42588.121118627336,
    "Effective Health": 96466231.34328361,
    "Survivability": 49042.3138501696,
    "Effective Healing": 468,
    "Healing": 468
  },
  "runeId": 44956,
  "runeName": "Tormenting",
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
      "weapon1MainType": "Scepter",
      "weapon1MainSigil1": "Doom",
      "weapon1OffType": "Dagger",
      "weapon1OffSigil": "Bursting",
      "weapon2MainType": "Scepter",
      "weapon2MainSigil1": "Doom",
      "weapon2OffType": "Pistol",
      "weapon2OffSigil": "Paralyzation"
    },
    "consumables": {
      "foodId": 91878,
      "utilityId": 77567
    },
    "skills": {
      "heal": "Hide in Shadows",
      "utility1": "Thousand Needles",
      "utility2": "Skale Venom",
      "utility3": "Spider Venom",
      "elite": "Basilisk Venom"
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
The <Skill name="skelkvenom"/> is a great option to support your party as it brings a tremendous amount of party healing.

If you do not need the extra CC you can remove the Pistol so your Dagger counts for both sets. This allows you to swap freely for <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/>.

</Character>  
</CharacterWithAr>
</Beginner>
<Advanced>
<CharacterWithAr>  
<Character title="DPS / Alac Share" gear={{
  "profession": "Thief",
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
    "Health": 16425,
    "Armor": 2361,
    "Power": 2923,
    "Precision": 1633,
    "Toughness": 1243,
    "Vitality": 1478,
    "Ferocity": 0,
    "Condition Damage": 2525,
    "Expertise": 1014,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0.6759999999999999,
    "Boon Duration": 0.162,
    "Critical Chance": 0.6014285714285714,
    "Critical Damage": 1.5,
    "Power Coefficient": 2131,
    "Power2 Coefficient": 0,
    "Burning Coefficient": 0.52,
    "Bleeding Coefficient": 2.59,
    "Poison Coefficient": 19.782,
    "Torment Coefficient": 20.25,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Poison Duration": 0.33,
    "Outgoing Healing": 0.2,
    "Torment Duration": 0.5,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 7334.034576428571,
    "Power DPS": 6018.0314525873255,
    "Power2 DPS": 0,
    "Siphon DPS": 158.75600000000003,
    "Bleeding Damage": 289.745,
    "Bleeding Stacks": 4.34084,
    "Bleeding DPS": 1257.7366858,
    "Burning Damage": 872.36625,
    "Burning Stacks": 0.87152,
    "Burning DPS": 760.2846342,
    "Confusion Damage": 342.39175,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 410.90350000000007,
    "Poison Stacks": 39.564,
    "Poison DPS": 16256.986074000002,
    "Torment Damage": 475.87485000000015,
    "Torment Stacks": 40.5,
    "Torment DPS": 19272.931425000006,
    "Damage": 43724.72627158734,
    "Effective Health": 96466231.34328361,
    "Survivability": 49042.3138501696,
    "Effective Healing": 468,
    "Healing": 468
  },
  "runeId": 44956,
  "runeName": "Tormenting",
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
      "weapon1MainType": "Scepter",
      "weapon1MainSigil1": "Doom",
      "weapon1OffType": "Dagger",
      "weapon1OffSigil": "Bursting",
      "weapon2MainType": "Scepter",
      "weapon2MainSigil1": "Doom",
      "weapon2OffType": "Pistol",
      "weapon2OffSigil": "Paralyzation"
    },
    "consumables": {
      "foodId": 91878,
      "utilityId": 77567,
      "infusionId": 37130
      
    },
    "skills": {
      "heal": "Hide in Shadows",
      "utility1": "Thousand Needles",
      "utility2": "Skale Venom",
      "utility3": "Spider Venom",
      "elite": "Basilisk Venom"
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
The <Skill name="skelkvenom"/> is a great option to support your party as it brings a tremendous amount of party healing.

If you do not need the extra CC you can remove the Pistol so your Dagger counts for both sets. This allows you to swap freely for <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/>.

If healing isn't an issue, this is the perfect build to use <Item name="writofmasterfulmalice"/> over <Item name="tuningicicle"/> ! <Skill name="signetofmalice"/> is also the strongest personal-healing ability you can bring to maintain your health over 90%, if you feel you don't need <Skill name="hideinshadows"/>.

It's recommended to have a short bow for additional movement during downtime and <Boon name="might"/> blasts on the _Mistlock Singularity_.
</Character>
<Character title="Alac Specter" gear={{
  "profession": "Thief",
  "weight": "Medium",
  "gear": [
    "Viper",
    "Ritualist",
    "Ritualist",
    "Viper",
    "Ritualist",
    "Viper",
    "Ritualist",
    "Ritualist",
    "Viper",
    "Viper",
    "Viper",
    "Ritualist",
    "Ritualist",
    "Ritualist"
  ],
  "attributes": {
    "Health": 23915,
    "Armor": 2361,
    "Power": 2174,
    "Precision": 1228,
    "Toughness": 1243,
    "Vitality": 2227,
    "Ferocity": 100,
    "Condition Damage": 2498,
    "Expertise": 1111,
    "Concentration": 648,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0.7406666666666666,
    "Boon Duration": 0.43200000000000005,
    "Critical Chance": 0.4085714285714286,
    "Critical Damage": 1.5666666666666667,
    "Power Coefficient": 1878,
    "Power2 Coefficient": 0,
    "Burning Coefficient": 0.57,
    "Bleeding Coefficient": 0,
    "Poison Coefficient": 17.102,
    "Torment Coefficient": 18.34,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Poison Duration": 0.33,
    "Outgoing Healing": 0.2,
    "Torment Duration": 0.2,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 5164.574897714285,
    "Power DPS": 3734.721470122228,
    "Power2 DPS": 0,
    "Siphon DPS": 158.75600000000003,
    "Bleeding Damage": 291.3366,
    "Bleeding Stacks": 0,
    "Bleeding DPS": 0,
    "Burning Damage": 878.3320500000001,
    "Burning Stacks": 0.9921799999999998,
    "Burning DPS": 871.4634933689999,
    "Confusion Damage": 344.35959,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 413.40270300000003,
    "Poison Stacks": 34.204,
    "Poison DPS": 14140.026053412,
    "Torment Damage": 434.97090000000003,
    "Torment Stacks": 35.59182666666666,
    "Torment DPS": 15481.408877844,
    "Damage": 34386.37589474723,
    "Effective Health": 140456007.4626866,
    "Survivability": 71406.20613253005,
    "Effective Healing": 468,
    "Healing": 468
  },
  "runeId": 83502,
  "runeName": "Renegade",
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
    "weapon1MainType": "Scepter",
    "weapon1MainSigil1Id": 24583,
    "weapon1OffType": "Dagger",
    "weapon1OffSigilId": 24609,
    "weapon2MainType": "Scepter",
    "weapon2MainSigil1Id": 24583,
    "weapon2OffType": "Pistol",
    "weapon2OffSigilId": 24639
  },
  "consumables": {
    "foodId": 91878,
    "utilityId": 81079,
    "infusionId": 37130
  },
  "skills": {
    "healId": 63292,
    "utility1Id": 63323,
    "utility2Id": 63276,
    "utility3Id": 13037,
    "eliteId": 13132
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
      "id": "jade-bot-base",
      "type": "Text"
    },
    {
      "id": "jade-bot-per-tier",
      "type": "Text"
    },
    {
      "id": "omnipotion",
      "gw2id": 79722,
      "type": "Item"
    }
  ]
}}>
This build runns <Attribute name="Boon Duration" text="43% Boon Duration"/>. If you are struggling to maintain <Boon name="Alacrity"/> use the [gear optimizer](https://optimizer.discretize.eu/) to adjust your gear. Additionally, when it is <Instability name="Boon Overload"/>, you can also adjust your gear to play a much more offensive variation.

If you do not need the extra CC you can remove the Pistol so your Dagger counts for both sets. This allows you to swap freely for <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/>.

It's recommended to have a short bow for additional movement during downtime and <Boon name="might"/> blasts on the _Mistlock Singularity_.
</Character>  
</CharacterWithAr>
</Advanced>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Card title="Traits">
<Traits unembossed traits1="Trickery" traits1Selected="Thrill of the Crime,Pressure Striking,Quick Pockets" traits2="Deadly Arts" traits2Selected="Deadly Ambition,Panic Strike,Potent Poison" traits3="Specter" traits3Selected="Consume Shadows,Larcenous Torment,Strength of Shadows"/>

### No Pain, No Gain Variant

<Trait id="1277"/> over <Trait id="1190"/> on <Instability name="No Pain, No Gain"/> days, or when boonstrip is needed.
<Traits traits1="Trickery" traits1Selected="Thrill of the Crime,Bountiful Theft,Quick Pockets" unembossed/>

<Advanced>
### Alacrity Variants

Situationally <Specialization name="Specter"/> can be used as a <Boon name="Alacrity"/> source. Either on its own or sharing generation with another class.

#### Alac Share

Alac share specter is a very strong build to play, especially on Ensolyss and 100CM. It uses the same gear as <Specialization text="Condi DPS Specter" name="Specter"/>. 

The DPS loss for the specter is well worth the DPS gain of taking a <Specialization text="Condi DPS Renegade" name="Renegade"/>, a <Specialization text="Staxe Mirage" name="Mirage"/> or another <Specialization text="Alac Share Specter" name="Specter"/> over a dedicated <Boon name="Alacrity"/> source!

<Traits traits1="Specter" traits1Selected="Consume Shadows,Traversing Dusk,Strength of Shadows" unembossed/>
<Skills heal="Well of Gloom" utility1="Well of Sorrow" utility2="Devourer Venom" utility3="Spider Venom" elite="Basilisk Venom" unembossed/>

#### Alacrity Specter

This build can maintain <Boon name="Alacrity"/> solo. You will need to adjust your gear using the [gear optimizer](https://optimizer.discretize.eu/) to gain at least 43% <Attribute name="Boon Duration"/> if you want to upkeep it permanantly.

<Traits traits1="Specter" traits1Selected="Consume Shadows,Traversing Dusk,Strength of Shadows" unembossed/>
<Skills heal="Well of Gloom" utility1="Well of Bounty" utility2="Well of Sorrow" utility3="Spider Venom" elite="Basilisk Venom" unembossed/>
</Advanced>

</Card>
</GridItem>
<GridItem sm="5">

<Card title="Situational Skills">

|                                                       |                                                                                                                                              |
| ----------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill id="13093" size="big" disableText/>            | A situational damage ability; take this over <Skill name="Thousand Needles"/> on moving targets.                                               |
| <Skill name="signetofmalice" size="big" disableText/> | Highest sustained healing.                                                                                                                   |
| <Skill name="skelkvenom" size="big" disableText/>     | Best party healing.                                                                                                                          |
| <Skill id="13020" size="big" disableText/>            | Taken over <Skill name="Prepare Thousand Needles"/> when extra CC is needed (particularly useful on MAMA).                                   |
| <Skill id="13082" size="big" disableText/>            | Taken for extra personal DPS, when CC isn't needed. Can also be precasted on the mistlock before swapping to <Skill name="Basilisk Venom"/>, |

</Card>

<Advanced>
<Card title="Useful skills for skips">

|                                            |                                                                                                           |
| ------------------------------------------ | --------------------------------------------------------------------------------------------------------- |
| <Skill id="13117" size="big" disableText/> | Group stealth. Keep in mind, if you leave the AoE before it ends, you will be revealed for a long period. |
| <Skill id="13065" size="big" disableText/> | Used for a smoke field to blast <Effect name="Stealth"/> for skips.                                       |
| <Skill id="13044" size="big" disableText/> | 3 seconds AoE <Effect name="Stealth"/> (also another blast).                                              |
| <Skill id="13064" size="big" disableText/> | 1200 range shadowstep, useful for some skips.                                                             |
| <Skill id="13002" size="big" disableText/> | 1200 range teleport, use it again to teleport back.                                                       |
| <Skill id="13038" size="big" disableText/> | One way portal, useful if you don't have <Item id="78978"/>.                                              |
| <Skill id="13025" size="big" disableText/> | 900 range shadowstep, useful for some skips.                                                              |
| <Skill id="13041" size="big" disableText/> | Used as a blast finisher to stack <Effect name="Stealth"/>.                                               |

</Card>
</Advanced>

<Card title="CC Skills">

|                                            |                                                        |
| ------------------------------------------ | ------------------------------------------------------ |
| <Skill id="13132" size="big" disableText/> | 150 Defiance bar damage per ally (up to 750 CC).       |
| <Skill id="63275" size="big" disableText/> | 450 Defiance bar damage.        |
| <Skill id="63155" size="big" disableText/> | Mind Shock (skill 5) does 150 Defiance bar damage.     |
| <Skill id="13020" size="big" disableText/> | 150 Defiance bar damage.                               |
| <Skill id="13012" size="big" disableText/> | 200 Defiance bar damage (260 with <Item id="24639"/>). |
| <Skill id="13019" size="big" disableText/> | <Condition name="Crippled"/> 15/s Defiance bar damage. |
| <Skill id="13093" size="big" disableText/> | <Condition name="Immobile"/> 50/s Defiance bar damage. |

</Card>

</GridItem>
</Grid>

<Divider text="Rotation / Skill usage"/>

<Grid>
<GridItem sm="7">

<Beginner>

<Card title="Step-by-Step Rotation">

**Step 1: Scepter 3 and F1**

In the first step, we will focus on spending our Initiative and gaining some of it back.
- The main skill we want to spend it on is <Skill name="Twilight Combo"/>.
- Besides that, we will just auto-attack on Scepter. Finishing auto-attack chains is not necessary.
- When low on Initiative, use <Skill name="Siphon"/> to gain back some through <Trait name="Kleptomaniac"/>. Be careful as this skill can cancel other skills you are currently casting.

**Step 2: Shadow Shroud**

Next up, we want to incorporate <Skill name="Enter Shadow Shroud"/>. This will be useful for gaining back Initiative instead of auto-attacking on Scepter for too long.
- When at low Initiative, use <Skill name="Enter Shadow Shroud"/> as soon as possible.
- This will trigger <Trait name="Quick Pockets"/> and give you back some Initiative (unless you recently weapon swapped before).
- Use Skills 2,4 and 5 off-cooldown in Shroud.
There are 2 options to track how long you want to stay in Shroud:
1. Leave Shroud when your Initiative is almost full.
2. Leave Shroud after the 3rd time casting skill 2 (if you entered at 0-1 Initiative) or after casting 2 additional auto-attacks after the 2nd time (if you entered at 3-4 initiative).

The 2nd way is more future-proof due to being independent of <Trait name="Quick Pockets"/> timings if you have to swap to Pistol during the fight or when you move on to using the 2nd Dagger to trigger <Trait name="Quick Pockets"/> at different times.

**Step 3: Venoms**

The first utility skills we will incorporate will be the venoms, namely <Skill name="Spider Venom"/> and <Skill name="Skale Venom"/>.
- Venoms give a buff to ourselves and 4 allies that will make the next attacks inflict various conditions. It will count towards your damage and scale with your stats.
- This also means they will be a lot more effective in a real fight "with allies" compared to the golem.
- Use these skills off-cooldown. They are instant-casts and can therefore be used while casting other skills.
- Use <Skill name="Basilisk Venom"/> whenever its CC is needed. This one does have a cast-time though.
- If a Mistlock Singularity is present, you can even precast them there before taking the singularity to reset your skills and use them again once the first ones are used up. This will ensure massive burst damage at the start of the fight.

**Step 4: Thousand Needles**

Lastly, you have <Skill name="Prepare Thousand Needles"/>.
- Using this skill will place a trap on the ground that will take 3 seconds until you can use it again to trigger the trap dealing damage and inflicting conditions in the area.
- Use it off-cooldown unless you know the boss will move soon. You can place it on the boss's location before the boss becomes attackable. The cooldown will start when you first place it, not when you trigger it.
- Due to its stationary nature, this skill can easily get wasted on bosses that move around a lot. You can consider <Skill name="Devourer Venom"/> as an alternative to enemies that move around a lot. In that case, use it like the other 2 venoms in step 3.

</Card>

<Card title="Improving Further">

Once you are comfortable with the above steps, you are already doing most of the full rotation and will be able to deal great damage.

There will be a few additional things on the advanced page to improve further but if you got here, you already know the most important things and these will have a smaller impact than what you learned so far.

The additional steps are:
- Using weapon swap more actively when not running a Pistol off-hand in order to maximize the efficiency of <Trait name="Quick Pockets"/> and <Item type="Sigil" name="Doom"/>.
- You can slightly shift the priority of certain skills to maximize their usage like casting <Skill name="Siphon"/> as soon as you go below 9 Initiative instead of when you run out of it.

</Card>

</Beginner>

<Advanced>
<Card title="Rotation">

There is no set rotation for <Specialization name="Specter" text="Condi Specter"/>, your rotation comes from skill priority. Your main aim when playing <Specialization name="Specter" text="Condi Specter"/> is to never have full Initiative, cast utility skills of cooldown and proc <Trait name="Quick Pockets"/> and <Item id="24609"/> as often as possible.

You should be casting your <Skill name="Skale Venom"/>, <Skill name="Spider Venom"/> and <Skill name="Thousand Needles"/> off cooldown (unless a phase is about to end).

On Scepter/Dagger you want to use:

- <Skill name="Twilight Combo"/>
- <Skill name="Shadow Bolt"/>, <Skill name="Double Bolt"/>, <Skill name="Triple Bolt"/>

You should also be weapon swapping off cooldown if you are not playing Pistol to make the best use of <Trait name="Quick Pockets"/> and <Item id="24609"/>

In <Skill name="Enter Shadow Shroud" text="Shadow Shorud"/> you want to use:

- Mind Shock (Skill 5)
- Eternal Night (Skill 4)
- Grasping Shadows (Skill 2)
- Haunt Shot (Skill 1)

</Card>
</Advanced>


</GridItem>

<GridItem sm="5">

<Beginner>
<Card title="Step-by-Step Video">

This video shows the step-by-step approach to the rotation listed on the left.

<Video youtube="HPwciFIKlAA" caption="by Ascers"/>

</Card>
</Beginner>

<Card title="Golem rotation">

<Beginner>

This video shows the full golem rotation. It optimizes the use of <Item type="Sigil" name="Doom"/> and <Trait name="Quick Pockets"/>.

</Beginner>

<Video youtube="7ZjQJmms_Dw" caption="by Incera"/>
</Card>

<Advanced>
<Card title="Precasting">

All Damaging Venom Skills should be casted on the _Mistlock Singularity_: <Skill name="Skale Venom"/>, <Skill name="Spider Venom"/> and <Skill name="Devourer Venom"/>. On stationary bosses which can be manually activated, instead of precasting <Skill name="Devourer Venom"/>, you can instead go to the spawn location and precast <Skill name="preparethousandneedles"/>. All you have to do then is to activate the Preparation when the boss becomes vulnerable, and cast it again as it will be off cooldown. This is possible on Skorvald, Artsariiv, Arkk, MAMA, and Ensolyss with the use of a <Item name="White Mantle Portal Device"/>, or on Siax without. It is also possible on the Sorrowful Spellcaster (Light & Dark Ai), but with a 1/4 chance of success.

- On 100CM, make sure to precast venoms on your <Skill id="13082"/> minions, as every boon and special ability effect currently on you will be stripped upon starting the encounter.
- Spam <Skill name="clusterbomb"/> for <Boon name="might"/> blasts on the _Mistlock Singularity_.

</Card>
</Advanced>
</GridItem>
</Grid>
