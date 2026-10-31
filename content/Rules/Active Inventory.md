---
title: Active Inventory
tags: Category/Rules
aliases:
draft: false
---
# Active Inventory
The right gear at the right time can make all the difference between life and death. But how do you keep track of what you're carrying?
#### Slots & Bulk

An active inventory manages items using inventory slots (storage capacity) and object bulk (carrying effort).

##### Inventory Slots

Inventory slots describe _storage_ capacity—how much can a thing carry without being overwhelmed? One slot holds one small object—a potion bottle, a dagger, a loaf of bread, etc.

Anything that can hold, carry, or contain objects can make use of inventory slots—for example:

- **Creatures** use slots to describe how much they can carry before they're encumbered.
- **Containers** use slots to describe how much they can store before they're full.
- **Buildings** use slots to describe how much free space they have in their rooms.
- **Vehicles** use slots to describe how much they can transport before they can't move.

##### Bulk

Objects use _bulk_ to describe how many inventory slots they fill—the bulkier the object, the more slots occupied.

Bulk represents the _effort_ needed by a medium-sized creature to carry an object based on its size, weight, and shape—the more awkward or uncomfortable it is to hold an object, the higher its bulk.

## Your Inventory

Your inventory capacity depends on your _creature size_ and _strength modifier_—the bigger and stronger you are, the more inventory slots you have.

As your size increases, so too does your bulk—a larger creature takes more effort to carry. Your bulk equals the larger of either a) your _minimum bulk_ or b) the total bulk of everything in your inventory.

#### Creature Inventory

|Creature Size|Inventory Slots|Minimum Bulk|
|---|---|---|
|Tiny|6 + STR|5|
|Small|14 + STR|10|
|Medium|18 + STR|20|
|Large|22 + [ STR x 2 ]|40|
|Huge|30 + [ STR x 4 ]|80|
|Gargantuan|46 + [ STR x 8 ]|160|

Here we see three characters calculate their inventory:

- Valiant, a human cleric, is a medium-sized creature (18 slots) with +2 STR (+2 slots). He has a total of 20 inventory slots, and occupies a minimum of 20 slots when carried.
- Crackle, a kobold wizard, is a small creature (14 slots) with −1 STR (−1 slot). She has 13 inventory slots and occupies a minimum of 10 slots.
- Brakken, a goliath barbarian, is a medium-sized creature with _Powerful Build_ (22 slots) and +3 STR (+6 slots). She has 28 inventory slots and occupies a minimum of 20 slots when carried.

### Basic Supplies

In addition to inventory slots, you can freely carry a limited number of basic supplies—one ration box, one waterskin, and one purse.

- **Ration box:** Stores up to five basic food rations.
- **Waterskin:** Holds enough liquid for five drink rations.
- **Purse:** Holds up to 100 assorted coins.

These three basic supply containers don't occupy any inventory slots, but they can still be affected by NPCs and monsters in some fashion—stolen, damaged, destroyed, etc—so keep an eye on them.

**Additional Supplies:** You can carry additional supplies (more rations, waterskins, purses, etc) by adding them into your inventory space as normal.

## Carrying Objects

When you hold or carry an object, you add it to your inventory. Fill a number of _inventory slots_ according to the object's _bulk_—the bulkier the object, the more inventory slots you must fill.

Valiant buys some hempen rope (2 bulk) and a torch (1 bulk) and puts them in his backpack, filling 3 slots.

Later, when Crackle is knocked unconscious by a rock trap, Valiant carries her to safety. As a small creature (10 bulk), she occupies 10 inventory slots.

#### Estimating Bulk

To choose a bulk rating for an object, consider its general size, weight, and shape—the more uncomfortable an item is to hold, the higher the bulk rating. Check the _Bulk_ table below for some example guidelines.

**Extremely Small Objects:** Some items are _especially_ small and easy to pack together—pins, coins, paperclips, etc. It takes 100 of these items to fill one inventory slot.

**Extremely Large Objects:** If you need to assign a bulk rating to an extremely large object, use a multiple of 18 for your bulk rating—18/36/54/72, etc.

#### Bulk Ratings

Bulk ratings assume the perspective of a medium-sized creature by default. Use larger bulk ratings to reflect larger-than-normal items (giant-forged swords, ogre armor, etc), and smaller ratings for smaller-than-normal equipment (gnome rock-hammers, pixie armor, etc).

### Encumbrance

If you find yourself carrying more than your inventory capacity allows, you are _encumbered_. While you are encumbered, you gain the following condition:

#### Encumbered

- Condition

- Your speed is halved
- You have disadvantage on ability checks, attack rolls, and saving throws that use Strength, Dexterity, or Constitution.

#### Maximum Capacity

You can't exceed your inventory capacity by more than half your maximum inventory slots (rounded down).

Valiant has an inventory capacity of 20 slots. He is encumbered from 21 slots, and can't carry more than 30 bulk in total.

#### Bulk

|Category|Bulk|Size|Weight|
|---|---|---|---|
|Tiny|0.2|**Tiny:** Smaller than the palm of your hand. You can hold many of these in one hand.|**Negligible:** A negligible or trivial weight.|
|Small|1|**Short:** Up to a handspan / 9 inches. Can be held comfortably with one hand.|**Light:** Up to 2 lbs. The weight of a loaf of bread or a bag of sugar.|
|Medium|2|**Medium:** Up to an arms-length / 2 feet long. Can be held with one hand.|**Medium:** Up to 5 lbs. About as heavy as a few big bags of sugar.|
|Large|3|**Long:** Longer than an arm. Usually can be held with one hand, but us most comfortable with two.|**Heavy:** Up to 10 lbs. About as heavy as a cat or a sack of potatoes.|
|X-Large|6|**Extra-long:** Longer than the height of an average person. Requires two hands to hold.|**Extra-heavy:** Up to 35 lbs. About a quarter of the weight of an average person.|
|XX-Large|9|**Extensive:** Longer than the height of two people. Requires two hands to hold.|**Leaden:** Up to 70 lbs. About half as heavy as an average person.|


## Dragging Objects

When you drag or pull an object, that object can still affect your inventory. Halve the bulk value of any object that you are dragging or pulling (rounding down).

**Heaped Objects:** If you're pulling a _pile_ of objects, halve the _total_ amount of bulk—not the individual items.

**Rolling Transport:** If you're pulling an object that is designed to travel easily (a cart, a wagon, a sled), you may quarter that object's bulk value.

Krazak finds a rotting chest that holds 1,900 assorted copper coins (19 bulk carried, 9 bulk when dragged). He drags the chest back up to the surface and loads it onto a hand cart (20 bulk carried, 5 bulk when pulled).

## Wearables

Wearable items—clothes, gloves, boots, hats, necklaces, etc—can be categorized into two groups: _attire_ and _armor_.

- **Attire:** Clothing and finery (necklaces, rings, bracelets, etc) don't occupy any inventory slots while worn—unless that attire is _awkward_ for you.
    
- **Armor:** Armor—and other _awkward_ wearables—continue to occupy inventory slots while worn.
    

Valiant can carry 20 slots-worth of equipment. Before heading out into adventure, he dons a set of common clothes (attire, 1 bulk) and some chainmail (armor, 9 bulk)—he has 11 slots left for other equipment.

Crackle, meanwhile, is trying to infiltrate a draconic cult. She has fashioned a dragon costume (attire, 2 bulk) that is awkward to move around in—it continues to fill 2 inventory slots even when worn.

### Armor Expertise

Armor is big and bulky, but there's a trade-off—you become more resistant to harm.

If you're wearing medium or heavy armor (and you're appropriately proficient) you gain one of the following perks. These doesn't stack with any additional armor feats or bonuses you might gain—use the highest value.

#### Armor Expertise

**Medium Armor:** Reduce any bludgeoning, piercing, and slashing damage that you take from non-magical weapons by half your proficiency bonus (rounded down), to a minimum of 1.

**Heavy Armor:** Reduce any bludgeoning, piercing, and slashing damage that you take from non-magical weapons by your proficiency bonus, to a minimum of 1.

## Transporting Goods

On your travels, you may need to transport goods in large quantities—carting gold from a dragon's lair, shipping ore across the sea, moving grain from one village to another. For this, you'll need transport vehicles and containers.

### Vehicles

Vehicles—carts, carriages, ships, trains, etc—store items in the same way as characters: with _inventory slots_.

Vehicle capacity is measured in six scales of _spacing_—this describes the number of inventory slots available to carry creatures and cargo.

#### Vehicle Capacity

|Spacing|Examples|Slots|
|---|---|---|
|Cramped|Cart (Hand), Sled (Hand)|20|
|Snug|Cart (Horse), Chariot, Rowboat|60|
|Compact|Wagon, Carriage (Horse), Keelboat|180|
|Spacious|Carriage (Train)|540|
|Capacious|Longship, Sailing Ship|1,620|
|Vast|Galley, Warship|4,860|

Valiant, Crackle, and Krazak need to cross the Brindle River. Together, they occupy a total of 50 bulk—they hire a snug rowboat, safe in the knowledge that it can carry all three of them and (probably) won't sink.

#### Transport Animals

Creatures can also carry items for you—pack mules, horses, elephants, etc. The carrying capacity of these creatures depends on their size category and strength modifier—the same as any character.

### Storage Containers

You may need to transport goods within storage containers—chests, crates, barrels, etc—for security or convenience. A storage container has a number of inventory slots equal to its bulk rating:

- A _small_ chest (1 bulk) has 1 inventory slot.
- A _large_ crate (3 bulk) has 3 inventory slots.
- An _extra-large_ barrel (6 bulk) has 6 inventory slots.

#### Nested Containers

You can store containers within containers—but a nested container must be at least one size category smaller than its parent.

Crackle has three containers—two small (1 bulk) chests and one large (3 bulk) crate.

She can't fit a 1 bulk chest inside another 1 bulk chest, but she can put both chests inside the crate.

#### Fiction First

Use the vehicle capacities listed here as a guide, but be mindful of the fiction—a galley may have 4,860 inventory slots, but that doesn't necessarily mean it can support the weight of 30 gargantuan dragons at once.

If you think a vehicle is being put _under duress_ by cargo or passengers, apply an appropriate penalty to its inventory capacity—or put the vehicle at harm's risk.

## Magical Containers

On your adventures, you may find magical containers that can change their storage capacity far beyond the normal. For example:

- **Bag of Holding:** This magical bag (1 bulk) can hold many more items than its size would suggest. A _Bag of Holding_ has 6 inventory slots.
- **Portable Hole:** This magical object (1 bulk) can be folded out into a container with 9 inventory slots.
- **Handy Haversack:** This magical haversack (2 bulk) has 12 inventory slots.

These containers can be very valuable to adventurers with limited access to transport vehicles or animals.

In the ruins of the Arcane Sanctum, Valiant finds a Bag of Holding—still intact after all these years. He places the bag (1 bulk) inside his leather backpack, increasing his total inventory space by 5 slots.

## Inventory Interactions

Once you have an object stowed away in your inventory, you must draw it out before you can use it. During your turn, you may use one free object interaction (PHB p190) with your inventory to:

- **Add/sheathe** one item (or collection of tiny items).
- **Remove/draw** one item (or collection of tiny items).

To make a second change to your inventory during the same turn—or to interact with another character's inventory—you must take the _Use an Object_ action.

Krazak wants to draw out his axe and charge forward, bashing open a door in his way. To do this, he must use his free _object interaction_ to grab the axe from his inventory, his movement to rush forward, and the _Use an Object_ action to bash open the door.

Viridian, meanwhile, wants to draw both a sword and a healing potion from his bag on his turn. He draws the sword as his free _object interaction_, and uses his full action to take out the potion.

#### Armor

|Name|Armor Class (AC)|Cost|Bulk|
|---|---|---|---|
|Light, Padded|11 + DEX|5 gp|_L_, 3|
|Light, Leather|11 + DEX|10 gp|_L_, 3|
|Light, Studded Leather|12 + DEX|45 gp|_L_, 3|
|Medium, Hide|12 + DEX (Max 2)|10 gp|_XL_, 6|
|Medium, Chain Shirt|13 + DEX (Max 2)|50 gp|_XL_, 6|
|Medium, Scale Mail|14 + DEX (Max 2)|50 gp|_XL_, 6|
|Medium, Breastplate|14 + DEX (Max 2)|400 gp|_XL_, 6|
|Medium, Half Plate|15 + DEX (Max 2)|750 gp|_XL_, 6|
|Heavy, Ring Mail|14|30 gp|_XXL_, 9|
|Heavy, Chain Mail|16|75 gp|_XXL_, 9|
|Heavy, Splint Mail|17|200 gp|_XXL_, 9|
|Heavy, Plate Mail|18|1,500 gp|_XXL_, 9|
|Shield|+2|10 gp|_M_, 2|

#### Weapons

|Name|Damage|Cost|Bulk|
|---|---|---|---|
|Battleaxe|1d8 slashing|10 gp|_L_, 3|
|Blowgun|1 piercing|10 gp|_S_, 1|
|Club|1d4 bludgeoning|1 sp|_M_, 2|
|Crossbow, Hand|1d6 piercing|75 gp|_S_, 1|
|Crossbow, Light|1d8 piercing|25 gp|_M_, 2|
|Crossbow, Heavy|1d10 piercing|50 gp|_L_, 3|
|Dagger|1d4 piercing|2 gp|_S_, 1|
|Dart|1d4 piercing|5 cp|_T_, 0.2|
|Flail|1d8 bludgeoning|10 gp|_M_, 2|
|Glaive|1d10 slashing|20 gp|_L_, 3|
|Greataxe|1d12 slashing|30 gp|_L_, 3|
|Greatclub|1d8 bludgeoning|2 sp|_L_, 3|
|Greatsword|2d6 slashing|50 gp|_L_, 3|
|Halberd|1d10 slashing|20 gp|_L_, 3|
|Handaxe|1d6 slashing|5 gp|_M_, 2|
|Javelin (5)|1d6 piercing|5 sp|_L_, 3|
|Lance|1d12 piercing|10 gp|_L_, 3|
|Light Hammer|1d4 bludgeoning|2 gp|_S_, 1|
|Longbow|1d8 piercing|50 gp|_L_, 3|
|Longsword|1d8 slashing|15 gp|_L_, 3|
|Mace|1d6 bludgeoning|5 gp|_M_, 2|
|Maul|2d6 bludgeoning|10 gp|_L_, 3|
|Morningstar|1d8 piercing|15 gp|_M_, 2|
|Net|—|1 gp|_S_, 1|
|Pike|1d10 piercing|5 gp|_L_, 3|
|Quarterstaff|1d6 bludgeoning|2 sp|_L_, 3|
|Rapier|1d8 piercing|25 gp|_M_, 2|
|Scimitar|1d6 slashing|25 gp|_M_, 2|
|Shortbow|1d6 piercing|25 gp|_M_, 2|
|Shortsword|1d6 piercing|10 gp|_M_, 2|
|Sickle|1d4 slashing|1 gp|_S_, 1|
|Sling|1d4 bludgeoning|1 sp|_S_, 1|
|Spear|1d6 piercing|1 gp|_L_, 3|
|Trident|1d6 piercing|5 gp|_L_, 3|
|War Pick|1d8 piercing|5 gp|_M_, 2|
|Warhammer|1d8 bludgeoning|15 gp|_L_, 3|
|Whip|1d4 slashing|2 gp|_S_, 1|

#### Transportation

|Type|Transportation|Size|Speed|Cost|Slots|Bulk|
|---|---|---|---|---|---|---|
|Animal|Camel|Large|50 ft|50 gp|28|40|
||Donkey or Mule|Medium|40 ft|8 gp|26|20|
||Elephant|Huge|40 ft|200 gp|54|80|
||Horse, Draft|Large|50 ft|50 gp|26|40|
||Horse, Riding|Large|60 ft|75 gp|25|40|
||Mastiff|Medium|40 ft|25 gp|19|20|
||Pony|Medium|40 ft|30 gp|20|20|
||Warhorse|Large|60 ft|400 gp|26|40|
|Vehicle (Land)|Carriage, Horse|Huge|—|100 gp|180|180|
||Cart (Hand)|Medium|—|5 gp|20|20|
||Cart (Horse)|Large|—|15 gp|60|60|
||Chariot|Large|—|250 gp|60|60|
||Sled (Hand)|Medium|—|5 gp|20|20|
||Sled (Horse)|Huge|—|20 gp|180|180|
||Wagon|Huge|—|35 gp|180|180|
|Vehicle (Water)|Galley|Gargantuan|4 mph|30,000 gp|4,860|4,860|
||Keelboat|Gargantuan|3 mph|3,000 gp|180|180|
||Longship|Gargantuan|5 mph|10,000 gp|1,620|1,620|
||Rowboat|Large|3 mph|50 gp|60|60|
||Sailing Ship|Gargantuan|5 mph|10,000 gp|1,620|1,620|
||Warship|Gargantuan|4 mph|25,000 gp|4,860|4,860|

#### Adventuring Gear

|Name|Cost|Bulk|
|---|---|---|
|Abacus|2 gp|_S_, 1|
|Acid (vial)|25 gp|_T_, 0.2|
|Alchemist’s Fire (flask)|50 gp|_S_, 1|
|Ammo, Arrows (20)|1 gp|_S_, 1|
|Ammo, Bolts (20)|1 gp|_S_, 1|
|Ammo, Bullets (20)|4 cp|_S_, 1|
|Ammo, Needles (50)|1 gp|_S_, 1|
|Antitoxin (vial)|50 gp|_T_, 0.2|
|Arcane Focus, Crystal|10 gp|_S_, 1|
|Arcane Focus, Orb|20 gp|_S_, 1|
|Arcane Focus, Rod|10 gp|_S_, 1|
|Arcane Focus, Staff|5 gp|_L_, 3|
|Arcane Focus, Wand|10 gp|_S_, 1|
|Ball Bearings (1,000)|1 gp|_S_, 1|
|Barrel|2 gp|_XXL_, 9|
|Bedroll|1 gp|_M_, 2|
|Bell|1 gp|_S_, 1|
|Blanket|5 sp|_S_, 1|
|Block & Tackle|1 gp|_S_, 1|
|Book|25 gp|_S_, 1|
|Bottle, Glass|2 gp|_S_, 1|
|Bucket|5 cp|_M_, 2|
|Caltrops (20)|1 gp|_S_, 1|
|Candle|1 cp|_T_, 0.2|
|Case|1 gp|_S_, 1|
|Chain (10 ft)|5 gp|_S_, 1|
|Chalk (1 piece)|1 cp|_T_, 0.2|
|Chest|5 gp|_XL_, 6|
|Clothes, Common|5 sp|_S_, 1|
|Clothes, Costume|5 gp|_M_, 2|
|Clothes, Fine|15 gp|_M_, 2|
|Clothes, Traveler’s|2 gp|_S_, 1|
|Component Pouch|25 gp|_S_, 1|
|Crowbar|2 gp|_M_, 2|
|Druid Focus, Mistletoe|1 gp|_S_, 1|
|Druid Focus, Staff|5 gp|_L_, 3|
|Druid Focus, Totem|1 gp|_S_, 1|
|Druid Focus, Wand|10 gp|_S_, 1|
|Fishing Tackle|1 gp|_S_, 1|
|Flask or Tankard|2 cp|_S_, 1|
|Game, Cards|5 sp|_S_, 1|
|Game, Dice|1 sp|_S_, 1|
|Game, Dragonchess|1 gp|_S_, 1|
|Game, 3 Dragon Ante|1 gp|_S_, 1|
|Grappling Hook|2 gp|_S_, 1|
|Hammer|1 gp|_S_, 1|
|Hammer, Sledge|2 gp|_L_, 3|
|Holy Symbol, Amulet|5 gp|_S_, 1|
|Holy Symbol, Emblem|5 gp|_S_, 1|
|Holy Symbol, Reliquary|5 gp|_S_, 1|
|Holy Water (flask)|25 gp|_S_, 1|
|Hourglass|25 gp|_S_, 1|
|Hunting Trap|5 gp|_S_, 1|
|Ink|10 gp|_T_, 0.2|
|Ink Pen|2 cp|_T_, 0.2|
|Instrument, Bagpipes|30 gp|_L_, 3|
|Instrument, Drum|6 gp|_M_, 2|
|Instrument, Dulcimer|25 gp|_L_, 3|
|Instrument, Flute|2 gp|_S_, 1|
|Instrument, Horn|3 gp|_M_, 2|
|Instrument, Lute|35 gp|_M_, 2|
|Instrument, Lyre|30 gp|_M_, 2|
|Instrument, Pan Flute|12 gp|_S_, 1|
|Instrument, Shawm|2 gp|_M_, 2|
|Instrument, Viol|30 gp|_M_, 2|
|Jug or Pitcher|2 cp|_S_, 1|
|Kit, Climbers|25 gp|_S_, 1|
|Kit, Disguise|25 gp|_S_, 1|
|Kit, Forgery|15 gp|_S_, 1|
|Kit, Healer’s|5 gp|_S_, 1|
|Kit, Herbalism|5 gp|_S_, 1|
|Kit, Mess|2 sp|_S_, 1|
|Kit, Poisoner’s|50 gp|_S_, 1|
|Ladder (10 ft)|1 sp|_L_, 3|
|Lamp|5 sp|_S_, 1|
|Lantern, Bullseye|10 gp|_S_, 1|
|Lantern, Hooded|5 gp|_S_, 1|
|Lock|10 gp|_S_, 1|
|Magnifying Glass|100 gp|_S_, 1|
|Manacles|2 gp|_S_, 1|
|Mirror, Steel|5 gp|_S_, 1|
|Oil (flask)|1 sp|_S_, 1|
|Paper (1 sheet)|2 sp|_T_, 0.2|
|Parchment (1 sheet)|1 sp|_T_, 0.2|
|Perfume (vial)|5 gp|_T_, 0.2|
|Pick, Miner’s|2 gp|_L_, 3|
|Piton|5 cp|_T_, 0.2|
|Poison, Basic (vial)|100 gp|_T_, 0.2|
|Pole (10 ft)|5 cp|_L_, 3|
|Pot, Iron|2 gp|_S_, 1|
|Potion of Healing|50 gp|_S_, 1|
|Ram, Portable|4 gp|_XL_, 6|
|Ration (1)|1 sp|_T_, 0.2|
|Ration Box|5 sp|_S_, 1|
|Rope, Hempen (50 ft)|1 gp|_M_, 2|
|Rope, Silk (50 ft)|10 gp|_S_, 1|
|Scale, Merchant’s|5 gp|_S_, 1|
|Sealing Wax|5 sp|_T_, 0.2|
|Shovel|2 gp|_L_, 3|
|Signal Whistle|5 cp|_T_, 0.2|
|Signet Ring|5 gp|_T_, 0.2|
|Soap|2 cp|_T_, 0.2|
|Spellbook|50 gp|_S_, 1|
|Spikes, Iron (10)|1 gp|_S_, 1|
|Spyglass|1,000 gp|_S_, 1|
|Tent, Two-person|2 gp|_L_, 3|
|Tinderbox|5 sp|_S_, 1|
|Tools, Alchemist|50 gp|_M_, 2|
|Tools, Brewer|20 gp|_M_, 2|
|Tools, Calligrapher|10 gp|_S_, 1|
|Tools, Carpenter|8 gp|_S_, 1|
|Tools, Cartographer|15 gp|_S_, 1|
|Tools, Cobbler|5 gp|_S_, 1|
|Tools, Cook|1 gp|_M_, 2|
|Tools, Glassblower|30 gp|_M_, 2|
|Tools, Jeweler|25 gp|_S_, 1|
|Tools, Leatherworker|5 gp|_M_, 2|
|Tools, Mason|10 gp|_M_, 2|
|Tools, Navigator|25 gp|_S_, 1|
|Tools, Painter|10 gp|_M_, 2|
|Tools, Potter|10 gp|_M_, 2|
|Tools, Smith|20 gp|_M_, 2|
|Tools, Thieves|25 gp|_S_, 1|
|Tools, Tinker|50 gp|_S_, 1|
|Tools, Weaver|1 gp|_M_, 2|
|Tools, Woodcarver|1 gp|_S_, 1|
|Torch|1 cp|_S_, 1|
|Vial|1 gp|_T_, 0.2|
|Waterskin|2 sp|_S_, 1|
|Whetstone|1 cp|_S_, 1|
|—|—|—|
|—|—|—|

#### Equipment Packs

|Pack|Cost|Total Bulk|
|---|---|---|
|Burglar's Pack|16 gp|17|
|Diplomat's Pack|39 gp|9|
|Dungeoneer's Pack|12 gp|22|
|Entertainer's Pack|40 gp|11|
|Explorer's Pack|10 gp|20|
|Priest's Pack|19 gp|11|
|Scholar's Pack|40 gp|5|
|**Note:** 1 days-worth of rations = 2 rations|   |   |

## Variant Dials

If you want to customize the _Active Inventory_ for your game, consider the following variant dials.

### A. Containers

Use _containers_ to introduce a _granular_ system of inventory management that focuses on item placement.

Characters divide their inventory slots into distinct containers—bags, belts, sheathes, etc—that they name, categorize, and place about their person.

Valiant has 11 free inventory slots (with 9 slots already occupied by his chain mail). He divides these into:

- a 4-slot weapon sheath (for his war pick and shield)
- a 3-slot belt (for his healer's kit and torch)
- a 4-slot bag (for his prayer book and bedroll).

#### Container Categories

Containers can be broadly separated into 5 categories. When you create your inventory containers, assign a category to each—you can mix and match categories however you like, or even rename them to something more fitting (purse, bandolier, backpack, etc).

Some containers can only hold items of a particular size, or require more time to retrieve an item—so pick the right containers to suit your needs.

- **Bag:** A bag holds items of any size. You can draw an item from a bag with a full action.
- **Belt:** A belt can hold only small and tiny items. You can draw an item from a belt with a free action.
- **Sheath:** A sheath holds weapons and shields. You can draw an item from a sheath with a free action.
- **Quiver:** A quiver stores bows, crossbows, arrows, quarrels, and javelins. You can draw an item from a quiver with a free action.
- **Worn:** Space reserved for significant wearables, such as armor and awkward attire.

Krazak wants rapid access to his weapons—he puts them in a sheath so he can draw them as a free action.

His downtime equipment—cooking tools, gaming sets, whetstones, etc—is unlikely to be needed at sudden notice, and can be stashed away in a bag.

#### Changing Containers

Characters can change their containers for free during a long rest, providing they have access to basic supplies and commodities via a village, town, or city.

While in town, Valiant swaps out a 6-slot bag for a 4-slot bag and 2-slot belt to hold his healing potions.

#### Equipping Characters

To demonstrate how containers work, here we see two characters divide their inventory slots into containers.

##### Chansi, Halfling Ranger

Chansi, a halfing ranger with −1 STR, can have only 13 inventory slots due to her small size and strength—humans have it so _easy_. Rolling 12, she starts with 120 gp.

Some decent leather armor is a must when ranging through the wild forests—animals have sharp claws. Chansi favors the trap and shortbow, but carries a sword and dagger for times when her prey gets too close.

The armor was costly, but it's saved Chansi's life on more than one occasion—well worth the price, and there's plenty of work for a talented ranger nowadays anyway.

#### Chansi's Inventory

|Type|Contents|
|---|---|
|Quiver (3/3)|- Shortbow (25 gp, 2 slot)<br>- Arrows (1 gp, 1 slot)|
|Sheath (3/3)|- Shortsword (10 gp, 2 bulk)<br>- Dagger (2 gp, 1 bulk)|
|Bag (4/4)|- Hunting Trap (5 gp, 2 bulk)<br>- Rope (1 gp, 2 bulk)|
|Worn (3)|- Studded Leather (45 gp, 3 bulk)|
|Ration Box|- Basic Ration (5)|
|Waterskin|- Clean Water (5)|
|Purse|- 31 gp (31 coins)|

##### Vikan, Goliath Sorcerer

Vikan, a goliath sorcerer with +2 STR, can have up to 26 inventory slots thanks to his _Powerful Build_—he might smash his head on a few ceilings, but being big does have its advantages. He has 60 gp.

As a sorcerer, Vikan eschews armor—it gets in the way of his raw arcane energies. He carries a quarterstaff for some basic defense and a crossbow for hunting.

A keen painter, Vikan carries painting supplies with him to capture inspirational scenes out in the wild. His art isn't going to win any awards, but Vikan paints for the love of the craft and not the reward.

#### Vikan's Inventory

|Type|Contents|
|---|---|
|Sheath (3/3)|- Quarterstaff (2 sp, 3 bulk)|
|Quiver (3/3)|- Light Crossbow (25 gp, 2 bulk)<br>- Bolts (1 gp, 1 slot)|
|Belt (4/6)|- Focus, Orb (20 gp, 1 bulk)<br>- Gaming Set, Cards (5 sp, 1 bulk)<br>- Lamp (5 sp, 1 bulk)<br>- Oil (1 sp, 1 bulk)|
|Bag (5/14)|- Painter's Supplies (10 gp, 2 bulk)<br>- Blanket (5 sp, 1 bulk)<br>- Bedroll (1 gp, 2 bulk)<br>- Rope, Hempen (1 gp, 2 bulk)|
|Ration Box|- Basic Ration (5)|
|Waterskin|- Clean Water (5)|
|Purse|- 8 sp (8 coins)|

#### Vehicles and Buildings

You can also use containers to divide up other forms of inventory—such as vehicle and building storage. Use these to control where items are placed. For example:

The _Amber Jewel_, sailing ship of Port Rondel, has a total of 1,620 inventory slots. These are divided into:

- Crew and Passengers: 810 slots
- Cargo (secure): 405 slots
- Cargo (unsecured): 405 slots

The spacious _Landril Warehouse_ on the Port's eastern docks can hold up to 540 inventory slots. These are divided into four regions:

- General Cargo: 220 slots
- Frozen Goods: 135 slots
- Secured Cargo: 135 slots
- Vaulted Goods: 50 slots

### B. Quickdraw

If you want to make inventory access a little more restricting for your players, use _Quickdraw_ items.

Characters nominate any 3 items in their inventory as _quickdraw_ items. Quickdraw items can be draw/removed from the inventory using a free _object interaction_ as normal. However, non-quickdraw items can only be accessed using a full action.

Krazak nominates his greataxe, handaxe, and shield as his 3 _quickdraw_ items—he can take out these 3 items using a free _object interaction_ as normal.

During a descent into the _Shadowed Maw_, the dwarf tries to take out a torch to light the way. This isn't a quickdraw item, and so it takes Krazak a full action to dig out the torch from his bag.

#### Changing Items

A character may rearrange their inventory and change their quickdraw items during a short or long rest.

Viridian has a shortsword, dagger, and rope as his 3 quickdraw items. Because hit points are running low across the party, Viridian swaps his quickdraw rope for a healing potion in the next short rest—just in case someone should need a quick restorative to hand.

### C. Pack Endurance

if you want to make a slight increase to the amount of inventory space, use _Pack Endurance_.

A creature may use either a) their Strength modifier or b) their Constitution modifier to calculate their inventory slots—whichever is highest.

Chansi is a halfling ranger with -1 STR and +2 CON. With _Pack Endurance_ and her Constitution modifier, Chansi has 16 inventory slots.

### D. Object Scaling

The bulk ratings listed in the equipment tables assume the perspective of a medium-sized character for simplicity.

But if you want to scale object sizes up or down, apply the following bulk category modifiers when appropriate.

**Creature Sizing:** A creature can't use an object that's inappropriate for their size (either too small or too large).

#### Scaling Modifiers

|Scale|Description|Bulk Category|
|---|---|---|
|Tiny|Much smaller than normal.|−2|
|Small|Smaller than normal.|−1|
|Large|Larger than normal.|+1|
|Huge|Much larger than normal.|+2|
|Gargantuan|Much, much larger than normal.|+3|

Krazak encounters an ogre with a greatclub. Normally, a greatclub is a 3 bulk weapon—but this one is _larger_ than normal and so is 6 bulk (+1 bulk category).

#### Armor Sizes

To scale armor with creature size ratings, use these alternate bulk ratings instead.

#### Armor Sizes

|Size|Armor Bulk|   |   |   |
|---|---|---|---|---|
||Light|Medium|Heavy|Shield|
|---|---|---|---|---|
|Tiny|1|2|3|1|
|Small|2|5|7|1|
|Medium|3|6|9|2|
|Large|4|7|11|3|
|Huge|5|10|15|4|
|Gargantuan|8|15|23|5|

Chansi wants to buy some light armor. Because she is a halfling, her _small-sized_ light armor is only 2 bulk.

Viridian also buys some light armor. As a tiefling, his _medium-sized_ light armor is 3 bulk.

##### Mismatched Armor Sizes

A creature can't use or wear armor that's not of their size category—it simply doesn't fit.

**Armor Alterations:** A skilled armorer may (with appropriate tools) permanently change the size of a piece of armor by one step (smaller or larger) from its natural size—for a negotiable fee (25% of the armor's base cost).