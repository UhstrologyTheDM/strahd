---
tags:
  - Category/Quest
MyContainer: 
MyCategory:
questObtained:
questStatus: Not Started
questGiver:
questLocationObtained:
questSessionObtained:
questLootAvail:
questLootEarned:
---
# Quest Info

Provide a summary of the quest here. 

- [ ] Obtain the quest
- [ ] Embark on an epic journey
- [ ] Complete the quest
- [ ] Roll in epic loot

# Quest Details


Date Obtained: 
Status: 
Quest Giver: 
Quest Location: 
Session Obtained: 
Available Loot: 
Acquired Loot: 

# Backstory

Describe the backstory of the quest here. Why is it important for the party to complete?

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