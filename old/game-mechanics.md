# Game Mechanics

Atlantis is based on simple game mechanics which revolve around a series of abilities each character has. The abilities define the characters' skillset and allow them to grow as complex entities. The abilities are based on the fact that we all have some basic traits, and that the more we perform an action, the more skilled we become at it.

In Atlantis, every ability is scored in values that range from 0 to 100. The higher the score, the better the character is at that particular ability.

Atlantis keeps into account a random opportunity of failure and success in the form of a dice which can be rolled and added to the total value of an ability. This signifies the chance and the fortunate or unfortunate conditions. The luck variance can add up to 20 points, which in extreme cases can expand the variance from removing 20 points to adding 40 points to an action.

The goal is to create a realistic approach to how a real person is, with unique skillsets each character has abilities which grows organically, making the characters progress.

## Open ended rolls

In Atlantis, every d20 roll is open-ended. Every time a 1 is rolled, the player should re-roll the dice and subtract the result from their ability. Every time a natural 20 is rolled, the player should re-roll the dice and add the result of both dice.

The open-ended roll applies only to the first roll, and not on the re-rolls.

## Performing Actions

Every time a character needs to perform an action which is neither trivial nor impossible, they will have to check if they succeed.

An action value is the sum of the ability and 1d20.

`result = ability + 1d20`

### Threshold

Atlantis is based on a percentile complexity level. Every time an action is performed, the total result identifies the degree of success on a scale between 0 and 100. It is therefore simple to identify threshold values the storyteller should use to challenge a character's action.

Threshold|Difficulty level
---:|---
10|Mundane difficulty, almost everyone can do it
25|Normal challenge, with a bit of effort you can do it
50|Difficult, you need to know your ability in order to succeed
75|Exceptional, only those who master the ability can do it

The threshold is set by the game master and indicates the ability result required in order to succeed.

### Type of Actions

There are two types of actions:
- **Challenged** actions (*stealth VS awareness*)
- **Unchallenged** actions (*jumping over a fence*).

#### Challenged actions

When the action of a character can be challenged by the counteraction of another character, then both character should check their ability result and compare the two. The higher wins.

The **level of success or failure** is the difference between the two action results.

`success = result 1 - result 2`

#### Unchallenged actions

Unchallenged actions are those actions which are not opposed by another character. The storyteller should define a threshold that the character should overcome. This threshold defines (in a percentage value) the complexity of the action.

The **level of success or failure** is the difference between the threshold and the action result.

`success = (ability + 1d20) - threshold`

## Learning new abilities

Every time a character wants to perform an ability they are not skilled in, they can use the trait on which the ability is based. **Athletics**, for example, is based on the trait **Body**. When a character tries to perform an **Athletics** check for the first time, they will roll the dice using the trait. If the character succeeds, they have the possibility to learn the ability as any other ability, as described in the character progression chapter.

## Combat

Similarly to every action, the result of an attack depends if the attack is challenged (*punching VS dodging*) or unchallenged (*shooting another character*).

In Atlantis, fighting is dangerous. The game itself is designed to make combat a serious action with dire consequences. By no means we want to avoid combat situations, on the contrary, we believe they balance a well thought-through campaign. Yet, Atlantis is a role-playing game which focuses on storytelling and abilities. Combat is no more important than any other skill.

### Challenged Attacks

When two characters are fighting and the defending character has an ability which can challenge the attacker, then the attack result is defined by a simple comparison between the attack ability plus 1d20 and the defending ability plus 1d20.

The **level of success or failure** is the difference between the two results.

`success = (attacking ability + 1d20) - (defending ability + 1d20)`

An example of a challenged attack is when the defending character spends their turn to perform a defending action. The attacking character may try to punch another, who may try to dodge the punch. In that case, the attacking character will use 1d20+brawl, and to succeed will have to score higher than the defending 1d20+dodge. In this case, the defending character will invest their action for their turn, and won't be able to do an attack themselves.

### Unchallenged Attacks

When the attack of a character cannot be actively defended by the other character, the difficulty is derived by a base challenge factor of **25**. This can receive a positive or negative modifier depending on the opponent apparent size and speed.

`success = (attacking ability + 1d20) - 25`

### Passive resistance

The difficulty to hit is, by default, 25. However, if the defendant has a skill which identifies an ability to oppose the attack (both attacker and defender have melee ability) then the default value may be replaced by the defender's ability. This is considered a passive resistance and does not require the defending character to spend their action turn. It is automatic.

> After spotting *Okado*, the guard raises his sword and attacks her. The guard has a melee ability of 36, and with a roll of 13, he would have scored a success of 24 (ability+1d20-25). However, *Okado* is extremely skilled with her sword and she naturally knows how to defend an attack. Her melee ability is 53, which is enough to parry the guard's attack (which totalled 49).

Please note that every additional passive action performed in the same round receives a -5 penalty.

> The second guard, galvanised but his colleague, decides to attack *Okado* as well. This time, because *Okado* has already parried an attack in the same round, the passive resistance will receive a penalty of -5. The second guard has a melee ability of 34 and rolls a 17, which totals 51. While *Okado* has a melee ability of 53, with a penalty of -5, she can only offer a passive resistance of 48. The second guard will hit but causing only minimal damage to her.
>
> It is now *Okado*'s time to attack. She focuses on her first guard first, hitting him (the ability of 53 plus a 1d20 roll of 15 minus a passive resistance of 36 gives her a 32 points success) and causing a massive damage. She also uses her melee talent of two attacks per round on the second guard, which is killed instantaneously, as *Okado* rolls a critical hit (ability 53 - second attack talent penalty -5 + 1d20 roll of 20 + bonus 1d20 roll of 18 - passive resistance of 34 for a success of 52) delivering three times the normal damage of her sword.

### Attack modifiers

The attack success can be modified by a series of factors. Some of them make it easy to hit or deliver damages, while others can make it more challenging to attack.

Please note that these modifiers are optional, and should never slow down the game. It is down to the storyteller to decide how much to involve the modifiers. Our approach is simple: if it makes the game more interesting, use them, otherwise drop them.

size of target|modifier
---|---:
Tiny|-10
Small|-5
Medium|0
Big|+5
Huge|+10

Remember that a positive modifier makes it easier for the character to hit.

To balance the game in terms of challenging the hand to hand combat, the melee combat and the ranged combat, the following modifiers should be applied to ranged combat. Please keep in mind that every ranged weapon has a maximum range, over which the attack fails automatically.

Distance to target|modifier
---|---:
0-15m|0
16m-30m|-5
31m-45m|-10
46m-100m|-15
101m+|-25

Last, but not least, you should consider the challenge of hitting a subject who is partially covered

Coverage|modifier
---|---:
Part (25%)|-5
Half(50%)|-10
Sensible(75%+)|-15

### Damages
Every weapon has a fixed amount of damages it inflicts. The damage receives a modifier depending on the success of the attack.

success|damage modifier
---|---:
1-10|1
11-25|2
26-50|3
51-75|4
76+|5

### Ablative armours
Jinx uses the idea of ablative armours, which are protections that absorb the damages in lieu of the character wearing it. The armours have a fixed amount of protection, which is lost every time damage is absorbed.

The ablative armour can absorb only a maximum of damage in a single attack. Each armour should specify this value.

Every time the damage caused by a single attack is bigger than the number of damages the armour can sustain in a single attack, the rest of the damages are passed to the character.

Each character can try and repair a damaged armour using the Armoury skill.

## Damages and Death

A character life points are indicative of their psycho-physical health. Every time a character is injured, debilitated or psychologically damaged, their life points are lowered to reflect the character status.

### Effects of damages on character

When a character has suffered damages, they won't be able to perform as well as they would when in optimal conditions. The more the character is hurt, the more challenging their action becomes.

The table below indicates how the amount of psychophysical damages affects the character's ability to perform any action.

damages|action modifier
---|---:
0-10|0
11-25|-5
25-50|-10
51-75|-15
76+|-20

### Unconsciousness

When a character reaches between 0 and -30 life points, they are rendered unconscious. They can only be revived with medicine, potions or spells. Every round unconscious, every player character should roll a body trait check against a threshold of **25**, or lose 10 life points.

### Death

A character dies when one of the following condition happens:
- they reach -31 points or less
- when they are unconscious, an attacker announces a *coup de grace* on them
