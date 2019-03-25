# Jinx: Simple Storytelling Role Playing Game Mechanics

## Traits, Abilities and Talents

### Traits
Every character has 3 traits, ranked on a scale between 1 and 20. They are:

- **Body** identifies everything related to strength, agility, health.
- **Mind** defines the intellectual capabilities.
- **Spirit** is used for the characters self esteem, confidence and presence.

### Abilities

Every character has a list of abilities. Each ability is linked to a trait. The initial value of a new ability is the value of the trait itself.

The abilities defines the character, as Jinx does not have the notion of class. The list of abilities is era-dependent. Future expansions will include a list of abilities for various type of games (Fantasy, Contemporary, Science Fiction).

### Talents

Some abilities, when mastered over 50 points, offers some unique talents. Differently from traits and abilities, talents do not have any value, they are just capabilities that expands the abilities themselves. For example, a character whose melee ability of 50 or more can chose to master a double attack.

The list of talents is available with the list of attributes.

## Life Points
Every playing character has 50 life points plus the value of their **Body**. When lost, the life points can be recovered by sleeping or meditating (1 every 6 hours) or through medical treatment.

`life points = 40 + Body`

### Effects of damages on character
When a character has suffered physical damages, they won't be able to perform as well as they would when in optimal conditions. The more the character is hurt, the more challenging their action become.

damages|action modifier
---|---:
0-20|0
21-25|-5
26-30|-10
31-35|-15
36+|-20

### Unconsciousness

When a character reaches between 0 and -30 life points, they are rendered unconscious. To regain consciousness they can only be revived with medicine, potions or spells. Every round unconscious, every player character should roll a body trait check against a challenge of 25, or lose 10 life points.

### Death

A character dies when one of the following condition happens:
- they reach -31 points or less
- when they are unconscious, an attacker announces a *coup de grace* on them

## Character creation
At the beginning of a game, the user defines:

- Traits values
- Initial abilities and values
- OCEAN personality traits
- Background story

### Traits values
Every player has 30 points to divide in the three traits of their character. The limit helps create a character that can have strength and weaknesses alike.

### Initial abilities and values
At the beginning of the game, each character possesses five abilities of their choice. The player has 60 points to distribute in the five abilities, with a limit of 20 points in each ability.

Every ability will start from the value of the trait they refer to.

### OCEAN personality traits

### Background story
Every character's initial ability should be explained by a back story. The player should explain why their character know how to do certain things and how they leaned those abilities.

## Actions outcome
Every time a character need to perform an action which is not trivial or impossible, they will have to check if they succeed. There are two type of actions: challenged (*stealth VS awareness*) and unchallenged (*jumping over a fence*).

In both cases, the rules refers to an ability, but the challenge can be done on a trait.

### Open ended rolls
Every d20 roll is open ended. Every time a 1 is roll, the player should re-roll the dice and subtract the result. Every time a natural 20 is roll, the player should re-roll the dice and add the result.

The open ended roll applies only to the first roll, and not on the re-rolls.

### Challenged actions
When the action of a character can be challenged by a counter action of another character, then the result of the action is defined by a simple comparison between the action plus 1d20 of the first character and the counter action plus 1d20 of the second character.

The **level of success or failure** is the difference between the two action results.

`success = (ability + 1d20) - (ability + 1d20)`

### Unchallenged actions
Unchallenged actions are those actions which are not opposed by another character. The storyteller should define a threshold that the character should overcome. This threshold define (in percentage value) the complexity of the action.

The action result is calculated by adding the ability or trait of the action plus 1d20.

The **level of success or failure** is the difference between the threshold and the action result.

`success = (ability + 1d20) - threshold`

## Fighting
Similarly to every action, the result of an attack depends if the attack is challenged (*punching VS dodging*) or unchallenged (*shooting another character*).

In Jinx, fighting is dangerous. The game itself is designed to make combat a serious action with dire consequences. By no means we want to avoid combat situations, on the contrary we believe they balance a well though-through campaign. Yet, Jinx is a role-playing game which focuses on storytelling and abilities. Combat is no more important than any other skill.

### Challenged Attacks
When two characters are fighting and the defending character has an ability which can challenge the attacker, then the attack result is defined by a simple comparison between the attack ability plus 1d20 and the defending ability plus 1d20.

The **level of success or failure** is the difference between the two results.

`success = (attacking ability + 1d20) - (defending ability + 1d20)`

### Unchallenged Attacks
When the attack of a character cannot be actively defended by the other character, the difficulty is derived by a base challenge factor of **25**. This can receive a positive or negative modifier depending on the opponent apparent size and speed. The *apparent size* is how big the target looks from the attacker perspective. This can be because of the real size of the opponent, its distance form the attacker or due to the opponent being hidden from view.

### Attack modifiers
The attack success can be modified by a series of factors. Some of them make it easy to hit or deliver damages, while others can make it more challenging to attack.

size of target|modifier
---|---:
Tiny|+10
Small|+5
Medium|0
Big|-5
Huge|+10

speed of target|modifier
---|---:
Still|+5
Walking|0
Trotting|-5
Running|-10
Moving erratically|-5

### Damages
Every weapon has a fixed amount of damages it inflicts. The damage receives a modifier depending on the success of the attack.

success|damage modifier
---|---:
1-10|1/2
11-20|1
21-30|1.5
31-40|2
41-50|2.5
51+|3


### Ablative armour
Jinx uses the idea of ablative armours, which are protections that absorb the damages in lieu of the character wearing it. The armours have a fixed amount of protection, which is lost every time a damage is absorbed.

The ablative armour can absorb only a maximum of damage in a single attack. Each armour should specify this value.

Each character can try and repair a damaged armour using the Armoury skill.

### Weapons and Armours
Future expansions will include a list of weapons and armours for various type of games (Fantasy, Contemporary, Science Fiction).

## Character progression
Jinx is based on the character progression based on its abilities, not on levels. Every time a character succeed in an ability test, the player should mark that action as successfully trained.
At the end of every adventure, which should last a few session, the storyteller should allow the players to increase their character's ability scores.

## Magic
In world where magic can be used, Jinx supports the idea of Vancian Magic. Every spellcaster must learn their spells every day, and they dissolve from their memories after being cast. Hence, magic users must learn the spell before being able to cast it again. Magic users can learn a single spell for longer, which means they are able to cast it more than once.

Each spell has a complexity level. Spellcasters have the ability to learn and cast spells of complexity lower than their ability. Each day, spellcasters can memorise a set maximum amount of spells per complexity;


Magic ability VS spell complexity|Spell per complexity level
---:|:---
0/+4|1
+5/+9|2
+10/+15|3
+15|4


Magic Ability|10|20|30|40|50|60|70|80|90
---|---:|---:|---:|---:|---:|---:|---:|---:|---:
10-14|1|-|-|-|-|-|-|-|-
15-19|2|-|-|-|-|-|-|-|-
20-24|3|1|-|-|-|-|-|-|-
25-29|4|2|-|-|-|-|-|-|-
30-34|4|3|1|-|-|-|-|-|-
35-39|4|4|2|-|-|-|-|-|-
40-44|4|4|3|1|-|-|-|-|-
45-49|4|4|4|2|-|-|-|-|-
50-54|4|4|4|3|1|-|-|-|-
55-59|4|4|4|4|2|-|-|-|-
60-64|4|4|4|4|3|1|-|-|-
65-69|4|4|4|4|4|2|-|-|-
70-74|4|4|4|4|4|3|1|-|-
75-79|4|4|4|4|4|4|2|-|-
80-84|4|4|4|4|4|4|3|1|-
85-89|4|4|4|4|4|4|4|2|-
90-94|4|4|4|4|4|4|4|3|1
95-99|4|4|4|4|4|4|4|4|2
100|4|4|4|4|4|4|4|4|3

Which means that a character with a magical ability of 33 will be able to memorise 4 spells of complexity level 10, 3 spells of level 20 and 1 spell of level 30
