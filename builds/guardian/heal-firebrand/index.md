﻿---
title: 'Heal Firebrand'
date: '2020-07-25'
rating: 'T4'
role: 'Support'
profession: 'Guardian'
specialization: 'Firebrand'
skills: [9093, 9153, 9251]
boons: ['Quickness', 'Fury', 'Might', 'Stability', 'Retaliation', 'Aegis']
conditions: ['Vulnerability', 'Blinded', 'Crippled']
code: '[&DQEQLjElPjZLF0sXehZ6FksBNgH+AP4AiRKJEgAAAAAAAAAAAAAAAAAAAAA=]'
---

<Message>
Despite being very common in pugs, this build is not **the** meta! It is part of a composition called PuG meta, you can read more about it [here](/guides/meta-explained). We **recommend** to play [Heal Renegade](/builds/revenant/heal-renegade) for PuGs who are more organized and know the mechanics (after around 150-250+ <Item id="81743"/>), also a <Specialization name="firebrand"/> can deal way more damage than <Specialization name="renegade"/>. However if you fail mechanics <Specialization name="Firebrand" text="Heal Firebrand"/> is a way to success.
</Message>

<Tabs>
<Tab title="Build">
If you play this build we highly recommend learning the <Skill name="Bane Signet"/> share variant. If you want a good and smooth run, take a look at the [Fractal Pages](/fractals). This class will not be doing much damage but understanding how the class works best and when to do <Skill name="Bane Signet"/> sharing is important!

<Divider text="Equipment"/>

Note that this build variant is optimized for 150 agony resistance.  
If you have more AR, feel free to swap out harrier pieces for cleric, as long as you are maintaining 100% boon duration. Please take in mind, that this is not _THE_ gear setup you have to play, many variants work. It is all about maximizing boon duration and healing power.  
Yes, you can play full harrier - however, you will lose some healing power.

Check the [gear optimizer](http://old.discretize.eu) for more gear variants!

<Grid>
<GridItem sm="4">
<Armor weight="Heavy" helmAffix="Harrier" helmRune="Monk" shouldersAffix="Harrier" shouldersRune="Monk" coatAffix="Harrier" coatRune="Monk" glovesAffix="Harrier" glovesRune="Monk" leggingsAffix="Harrier" leggingsRune="Monk" bootsAffix="Harrier" bootsRune="Monk"/>
</GridItem>
 
<GridItem sm="4">
<Weapons weapon1MainType="Staff" weapon1MainAffix="Harrier" weapon1MainSigil1="Transference" weapon1MainSigil2="Concentration" weapon2MainType="Axe" weapon2MainAffix="Harrier" weapon2MainSigil1="Transference" weapon2OffType="Shield" weapon2OffAffix="Harrier" weapon2OffSigil="Concentration"/>
<Card title="Swap Weapons">
* Greatsword for pulling adds in 99 CM
* A hammer for <Boon name="might"/> pre-stacking
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Cleric" accessory1Affix="Cleric" accessory2Affix="Cleric" amuletAffix="Harrier" ring1Affix="Cleric" ring2Affix="Harrier"/>
<Consumables food="Delicious Rice Ball" utilityId="67528" infusion="Healing +9 Agony Infusion"/>
</GridItem>

</Grid>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Radiance" traits1Selected="Right Hand Strength, Wrath of justice, Perfect Inscriptions" traits2="Honor" traits2Selected="Invigorated Bulwark, Honorable Staff, Writ of Persistence" traits3="Firebrand" traits3Selected="Liberators Vow, Weighty Terms, Loremaster"/>
 
<Card title="Situational Traits">
| | |
| -- | -- |
| <Trait name="Pure of heart" size="big" disableText/> | In some T4s with a lot of attacking enemies it can be beneficial to bring this trait. This trait trades <Boon name="Might"/> for more heals. |
## Wheelchair
In case your team downs frequently and is unable to handle mechanics correctly, you can swap radiance for virtues. This however is **not** the default build and should only be played under extreme circumstances, like very bad instability combos or beginner groups.
<UnembossedTraits traits1Id="46" traits1="Virtues"  traits1SelectedIds="625, 610, 554"/>

</Card>
</GridItem>

<GridItem sm="5">
<Skills heal="Mantra of Solace" utility1="Mantra of Potence" utility3="Bane Signet" elite="Mantra of Liberation"/>

<Card title="Situational Skills">
| | |
| -- | -- |
| <Skill id="45460" size="big" disableText/> | A strong condition cleanse to counterplay <Instability name="Afflicted"/>. |
| <Skill name="Feel my wrath" size="big" disableText/> | When there is absolutely no need for <Boon name="Stability"/>. |
| <Skill id="9246" size="big" disableText/> | A 1,200 range teleport to an ally. Can be used to blink to a <Skill id="9168"/>.|
| <Skill id="9247" size="big" disableText/> | A 1,200 range teleport to an enemy. Very handy for some skips. |
| <Skill name="Hallowed Ground" size="big" disableText/> | Can be used where <Boon name="stability"/> or stun break is needed. Preferred over <Skill id="9153"/>. |
| <Skill id="9153" size="big" disableText/> | Can be used where <Boon name="stability"/> or stun break is needed. |
| <Skill id="9175" size="big" disableText/> | A strong heal. |
| <Skill id="9125" size="big" disableText/> | Deals additional 200 defiance bar damage. |
| <Skill id="9251" size="big" disableText/> | A stationary reflect lasting for 10 seconds. Can be used to counterplay <Instability name="We bleed fire"/>.|
| <Skill name="Sanctuary" size="big" disableText/> | A slow but strong CC skill. Also destroys projectiles inside. |
</Card>
</GridItem>
</Grid>
</Tab>

<Tab title="Guide">
<Divider text="Details"/>

It provides permanent <Boon name="Quickness"/>, <Boon name="Regeneration"/>, <Boon name="Fury"/> and a decent amount of might. Exactly like the meta-counterpart it provides good offensive support via <Skill name="Bane Signet"/>, it is important to understand that the signet share is essential to faster runs and sharing extra power during <Effect name="exposed"/> (broken Defiance bar). The main source of <Boon name="Quickness"/> is <Skill name="Restoring Reprieve"/> and <Skill name="Potent Haste"/>; <Skill name="Feel My Wrath"/> is optional.

The <Specialization name="Firebrand" text="Heal Firebrand"/> heals with any symbols, dodges, <Boon name="Regeneration"/>, <Skill name="Restoring Reprieve"/>, and if necessary <Skill name="Bow of Truth"/>. If your group is unable to stay alive, you can swap out your offensive support (<Skill name="Bane Signet"/> and radiance) to virtues for more heals, _but_ it should not be needed.

When <Instability name="Afflicted"/> is present or enemies are applying conditions, you can use <Skill name="Symbol of Swiftness"/> (Staff3) and blast it with <Skill name="Holy Strike"/> (Staff2) for area condition cleanse.

<Grid>
<GridItem sm="12">
<Card title="Skill Usage">
Prestacking:
- Press <Skill name="Empower"/>
- Press <Skill name="Restoring Reprieve"/> and <Skill name="Potent Haste"/> each twice; press <Skill name="Feel My Wrath"/>
- Take mistlock 
- Press <Skill name="Empower"/> again

To keep up <Boon name="Quickness"/>:

- Use <Skill name="Restoring Reprieve"/> and <Skill name="Potent Haste"/> but leave one charge left (unless the fight is close to being over)
- Only use these skills close to your allies - try to "puke" on them with the mantras

To keep up <Boon name="Might"/> and <Boon name="Fury"/>:

- Always prestack <Boon name="Might"/> on the mistlock!
- You can press <Skill name="Symbol of Vengeance"/> (Axe2) two times before your <Skill name="Empower"/> (Staff 4) if off cooldown again.
- You wanna maximize the uptime of <Skill name="Symbol of Vengeance"/> while pressing <Skill name="Empower"/> off cooldown.

CCing:

- Always use <Skill name="Bane Signet"/>! This is one of the most important things you have to do!
- Use <Skill name="Blazing Edge"/> (Axe3)
- Use <Skill name="Shield of Absorption"/> (Shield5)
- Using consumables such as <Item name="Metal Rod"/>, <Item name="sentinelrifle"/> and <Item name="termiteshovel"/> is highly encouraged, since you having nothing to do anyway.

Tomes are very useful when no other skills are ready. <Skill name="Tome of Justice"/> also gets refreshed every time an enemy dies (works with anomalies at Artsariiv/Arkk, knights at MAMA and hallucinations at Siax).

<Skill name="Tome of Courage"/> and <Skill name="Tome of Resolve"/> are great for high incoming damage scenarios.

- <Skill name="Tome of Justice"/> (F1):
  - Skill 4 is a ticking AoE, good for single target and great for AoE DPS
  - Skill 5 makes your surrounding allies inflict <Condition name="Burning"/> - worth using as precast
  - Skill 3 is an AoE pull (150 defiance bar damage)
  - Often these skills are used as an opener
- <Skill name="Tome of Resolve"/> (F2):
  - Skill 2 is a party condition cleanse
  - Skill 3 grants <Boon name="Vigor"/>, <Boon name="Regeneration"/> and <Boon name="Swiftness"/>
  - Skill 4 is a good party heal
  - Skill 5 increases healing on allies for 8s by 33% and converts up to 5 conditions to boons
- <Skill name="Tome of Courage"/> (F3):
  - Skill 1 grants <Boon name="Stability"/> and <Boon name="Swiftness"/>
  - Skill 3 is a 5s reflect
  - Skill 4 grants <Boon name="resistance"/> and breaks stun
  - Skill 5 grants <Boon name="Aegis"/>, <Boon name="Protection"/>, <Boon name="Stability"/> and 300 toughness for 5 seconds

</Card>

</GridItem>

<GridItem>
<Card title="CC skills">
| | |
| -- | -- |
| <Skill name="Blazing Edge"/> | 150 damage |
| <Skill name="Shield of Absorption"/> | 150 damage |
| <Skill name="Bane Signet"/> | 300 damage |
</Card>
</GridItem>
<GridItem>
<Message>
This guide is good for people who want to start fractals with heal firebrand. We still highly recommend running the Radiance/Honor build variant from our Build section so you start playing with the proper build!
</Message>
<Video youtube="oigZbGyQvbQ" title="In-depth build guide by Rheyo"/>
</GridItem>
</Grid>

</Tab>
