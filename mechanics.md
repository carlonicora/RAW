# Jinx: Simple Storytelling Role Playing Game Mechanics

## Traits and Abilities

### Traits
Every character has 3 traits, ranked on a scale between 1 and 20. They are:

- __Body__ identifies everything related to strength, agility, health.
- __Mind__ defines the intellectual capabilities.
- __Spirit__ is used for the characters self esteem, confidence and presence.

### Abilities
Every character has a list of abilities. Each ability is linked to a trait. The initial value of a new ability is the value of the trait itself.

The abilities defines the character, as Jinx does not have the notion of class. The list of abilities is era-dependent. Future expansions will include a list of abilities for various type of games (Fantasy, Contemporary, Science Fiction).


### Life points
Every playing character has 50 life points plus the value of their __Body__. When lost, the life points can be recovered by sleeping or meditating (1 every 6 hours) or through medical treatment.

`life points = 50 + Body`

### Effects of damages on character
When a character has suffered physical damages, they won't be able to perform as well as they would when in optimal conditions. The more the character is hurt, the more challenging their action become.

damages|action modifier
---|---:
0-10|0
11-20|-5
21-30|-10
31-40|-15
41-49|-20

## Character creation
At the beginning of a game, the user defines:

- Traits values
- Initial abilities and values
- HEXACO personality
- Background story

### Traits values
Every player has 30 points to divide in the three traits of their character. The limit helps create a character that can have strength and weaknesses alike.

### Initial abilities and values
At the beginning of the game, each character possesses five abilities of their choice. The player has 60 points to distribute in the five abilities, with a limit of 20 points in each ability.

Every ability will start from the value of the trait they refer to.

### HEXACO personality
Each player should define the personality of a character based on the [HEXACO model of personality structure](https://en.m.wikipedia.org/wiki/HEXACO_model_of_personality_structure). The structure identifies six traits of the personality and assigns them a value between 1 and 5:

- __H__ onesty
- __E__ motionality
- e __X__ traversion
- __A__ greeableness
- __C__ onscientiousness
- __O__ penness to Experience

Available online there is a [HEXACO personality test](http://hexaco.org/hexaco-online) which the players can take while seeing the world through their character's eyes.

### Background story
Every character's initial ability should be explained by a back story. The player should explain why their character know how to do certain things and how they leaned those abilities.

## Actions outcome
Every time a character need to perform an action which is not trivial or impossible, they will have to check if they succeed. There are two type of actions: challenged (_stealth VS awareness_) and unchallenged (_jumping over a fence_).

In both cases, the rules refers to an ability, but the challenge can be done on a trait.

### Open ended rolls
Every d20 roll is open ended. Every time a 1 is roll, the player should re-roll the dice and subtract the result. Every time a natural 20 is roll, the player should re-roll the dice and add the result.

The open ended roll applies only to the first roll, and not on the re-rolls.

### Challenged actions
When the action of a character can be challenged by a counter action of another character, then the result of the action is defined by a simple comparison between the action plus 1d20 of the first character and the counter action plus 1d20 of the second character.

The __level of success or failure__ is the difference between the two action results.

`success = (ability + 1d20) - (ability + 1d20)`

### Unchallenged actions
Unchallenged actions are those actions which are not opposed by another character. The storyteller should define a threshold that the character should overcome. This threshold define (in percentage value) the complexity of the action.

The action result is calculated by adding the ability or trait of the action plus 1d20.

The __level of success or failure__ is the difference between the threshold and the action result.

`success = (ability + 1d20) - threshold`

## Fighting
Similarly to every action, the result of an attack depends if the attack is challenged (_punching VS dodging_) or unchallenged (_shooting another character_).

### Challenged Attacks
When two characters are fighting and the defending character has an ability which can challenge the attacker, then the attack result is defined by a simple comparison between the attack ability plus 1d20 and the defending ability plus 1d20.

The __level of success or failure__ is the difference between the two results.

`success = (attacking ability + 1d20) - (defending ability + 1d20)`

### Unchallenged Attacks
When the attack of a character cannot be actively defended by the other character, the difficulty is derived by a base challenge factor of __25__. This can receive a positive or negative modifier depending on the opponent apparent size and speed. The _apparent size_ is how big the target looks from the attacker perspective. This can be because of the real size of the opponent, its distance form the attacker or due to the opponent being hidden from view.

### Attack modifiers
The attack success can be modified by a series of factors. Some of them make it easy to hit or deliver damages, while others can make it more challenging to attack.

apparent size of target|modifier
---|---:
Bigger than equal size at 5m|+5
Equal size at 5m|0
1/2 the size at 5m|-10
1/4 the size at 5m|-20
Smaller than 1/4 size at 5m|-40

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
1-10|-50%
11-30|0
31-40|+50%
41+|+100%


### Ablative armour
Jinx uses the idea of ablative armours, which are protections that absorb the damages in lieu of the character wearing it. The armours have a fixed amount of protection, which is lost every time a damage is absorbed.

The ablative armour can absorb only 50% of its protection in a single attack. The rest of the damage is passed to the character.

### Weapons and Armours
Future expansions will include a list of weapons and armours for various type of games (Fantasy, Contemporary, Science Fiction).

## Character progression
Jinx is based on the character progression based on its abilities, not on levels. Every time a character succeed in an ability test, the player should mark that action as successfully trained.
At the end of every adventure, which should last a few session, the storyteller should allow the players to try and increase their character's ability scores.

To increase the score of a trained ability, the player should score higher than the ability value on a d100 roll. In case of success, the ability is increased by 1 point.

The storyteller may allow the value to be tested a second time at the end of the same adventure should the player had demonstrated particular qualities in handling that specific ability.
