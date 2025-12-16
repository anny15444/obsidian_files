# Attributes
At the start of each battle, random gladiators are generated to create unique scenarios. The most important part of these fighter's stats is their **attributes**. Attributes are a set of six randomly generated numbers that influence every other stat. 

>[!todo]  All attributes are affected by *vitality* when it is below or above 100%
### Strength
Internally known as *str*, strength determines the damage output of attacks and influences skills such as **Swordsmanship**, **Fencing**, and **Hand** **to** **Hand**.
### Speed
Internally known as *spd*, speed determines the possible amount of attacks and influences skills such as **Swordsmanship**, and **Projectile**
### Agility
Internally known as *agi*, agility determines the chance to dodge & parry attacks and influences skills such as **Archery**, and **Martial** **arts**
### Intelligence
Internally known as *int*, intelligence determines the accuracy of attacks and influences skills such as **Archery**, **Fencing**, and **Projectile**
### Size
Internally known as *size*, size determines total vitally and influences skills such as **Axing**, and **Martial Arts**
### Constitution
Internally known as *con*, constitution determines the chance to block attacks and influences skills such as **Axing**, and **Hand to Hand**

>[!tip] Visual representation: [[Fighter Class.canvas|Fighter Class]] 
# Skills
Once all attributes are determined, they're used to set level of expertise in skills. There are 7 skills, and 4 levels of expertise. It is important to keep in mind that all skills have minimal randomness, so it's impossible to exactly predict them.
## Expertise
The expertise gives an idea of a gladiator's competence in a certain skill.

| Expertise   | Novice | Medicore | Advanced | Master |
| ----------- | ------ | -------- | -------- | ------ |
| Skill (lvl) | 0-2    | 3-6      | 6-8      | 9-10   |
## Skills list

| Skill       | Swords. | Archery | Axing | Fence. | Hands. | Martial. | Project. |
| ----------- | ------- | ------- | ----- | ------ | ------ | -------- | -------- |
| Attribute 1 | Str     | Int     | Size  | Str    | Str    | Size     | Int      |
| Attribute 2 | Spd     | Agi     | Con   | Int    | Con    | Agi      | Spd      |
 Table to identify corresponding attributes and skills.

---
### Swordsmanship
Swordsmanship skill provides large bonuses to the Swords category of [[Weapons|weapons]] (e.g. Daggers, Gladiuses), and is heavily boosted by high **Strength** and **Speed**.
### Archery
Archery skill provides large bonuses to the Strung category of weapons (e.g. Longbow, Recurve), and is heavily boosted by high **Intelligence** and **Agility**.
### Axing
Axing skill provides large bonuses to the Axes category of weapons, and is heavily boosted by high **Size** and **Constitution**.
### Fencing
Fencing skill provides large bonuses to the Swords category of weapons, and is heavily boosted by high **Strength** and **Intelligence**.
### Hand to Hand
Hand to Hand skill provides no bonuses to any weapons type, and is heavily boosted by high **Strength** and **Constitution**.
### Martial Arts
Martial Arts skill provides no bonuses to any weapons type, and is heavily boosted by high **Size** and **Agility**.
### Projectile
Projectile skill provides large bonuses to the Thrown category of weapons, and is heavily boosted by high **Intelligence** and **Speed**.
