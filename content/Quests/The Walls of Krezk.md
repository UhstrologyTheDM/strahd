---
tags:
  - Category/Quest
MyContainer: [[Village of Krezk]]
MyCategory:
questObtained:
questStatus: Not Started
questGiver:
questLocationObtained:
questSessionObtained:
questLootAvail:
questLootEarned:
draft: false
---
# Quest Info

Provide a summary of the quest here. 

- [x] Obtain the quest
- [ ] Travel to the ruins of Berez and have Baba Lysaga perform a scrying spell.
- [ ] Give Dmitri the location of his son.

# Quest Details


Date Obtained: Neyavr 9th
Status: 
Quest Giver: [[Dmitri Krezkov]]
Quest Location: [[Village of Krezk]]

# Backstory
Baron Krezkov asks the players to journey to the hut of the witch Baba Lysaga in the ruins of Berez to the southeast. There, he tells them, they must beseech Baba Lysaga to perform a _scrying_ spell to discern the location and condition of a particular person.

If the players accept Baron Krezkov’s task, he provides them with a few strands of dark hair for Baba Lysaga to use in her scrying, as well as a large gold bracelet inset with intricate carvings of wolves and ravens as a gift to purchase her favor.

Baron Krezkov confessed that the missing person is his son, Ilya Krezkov, who disappeared several days ago.

# Planning

Plan your quest out here. 

# People
The following people are associated with this quest:
```base
filters:
  and:
    - file.hasProperty("status")
    - status == "healthy"
views:
  - type: table
    name: Table
    order:
      - file.name
```