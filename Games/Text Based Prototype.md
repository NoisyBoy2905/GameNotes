
## [Repo](https://github.com/NoisyBoy2905/severance-text)

Will be exactly like the 2.5D version but without visuals or with them appearing rarely like showing a enemy/boss or special item or chest

# Goal

Just a simple texted based game with branching paths, will follow the dungeon, have saving features and allow for multiple classes

# In Scope

- Start with 1 class (probably paladin due to being simple)
- Start with first dungeon (dungeon 1 on dungeon & enemies note)
- Turned based combat 
- Enemies with set classes and a boss at the end of each dungeon
- Multiple dungeons (Rainforest River and Derelict Spaceship built, Cave planned)
- Multiple classes (Paladin done, Sorcerer in progress)

# Out of Scope

- Many different bosses and enemy types with multiple classes/roles they fill
# Tech

Written in python, gonna use colorama, JSON and random again, with classes to save player, enemy and dungeon data and stats 

# Build Order

1. Player Class: health, attack, stats and abilities 
2. Enemy Class: health, attacks and stats
3. Combat loop: player acts ,enemy acts repeats until one dies
4. Abilities: add cooldowns
5. First Dungeon: Rooms and multiple fights in a row
6. A Boss: a boss fight which will be placed at the end of the dungeon
7. Rewards: XP and gear dropped by boss
8. Save/Load: save and load via files with JSON
9. Polish: add colours, ASCII art for enemies and gear and special parts of the room

Status: In progress - steps 1-6 done (Paladin, 2 dungeons with bosses, levelling and XP). Working on the Sorcerer next

Link to [[Dungeons & Enemies]]
Link to [[Lore & World]]
Back to [[Game Ladder]]

#game 
