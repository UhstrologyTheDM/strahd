---
title: Master Homebrew Rules
draft: false
aliases: House Rules
tags: Category/Rules
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

# Ammunition Dice

Some items require ammunition—arrows, bolts, bullets, charges, etc. But in the heat of battle, it's not always clear how much ammo you have left in your quiver.

This chapter introduces _ammunition dice_ as a means of tracking your ammunition supplies.

## The Ammunition Die

Instead of tracking each individual shot, take a d12—this is your _Ammunition die_. Roll it whenever you take a shot: if you roll a 1 or 2, the die gets one size smaller.

If you're down to one piece of ammunition and you use it, that's it—it's all gone! Remove it from your inventory.

#### Ammunition Die

d12 → d10 → d8 → d6 → d4 → 1

- GM: The ghoul grabs hold of you tight, Viridian, moaning as it prepares to bite. What do you do?
- Viridian: Uh Chansi, need a little help here!
- Chansi: Yea see the thing is, I'm kinda running low on arrows. Ammunition die is down to a d4—
- Viridian: TAKE THE DAMN SHOT, CHANSI!
- Chansi: _Fine_. That's... (rolls 15) ...15 to hit, and... (rolls 1) ...damn, a 1 for ammunition. Last arrow.

#### Special Ammo

If your ammunition is rare or has limited uses—fire arrows, magic bolts, lighting bullets, etc—don't use an ammunition die. Track each individual shot as you use them.

#### Average Uses per Die Size

|Die Size|Remaining  <br>Uses (Average)|
|---|---|
|d20|30|
|d12|20|
|d10|14|
|d8|9|
|d6|5|
|d4|2|

### Ammunition Stacks

Most ammunition types will start with (and have a maximum size of) a d12 _ammunition die_—this represents a full stack of arrows/bolts/bullets/etc. Some special items, however, may have their own unique limitations—such as a wand with d8 maximum charges.

**Multiple Stacks:** If you're carrying multiple stacks of any one type of ammunition, prioritize the smallest stack. Always roll the smallest ammunition die per ammo type.

### Replenishing Ammunition

To increase your _ammunition die_ you can recover ammo from the environment, buy a new stack, or pay a small percentage of the total cost to increase your die by one step based on the _maximum_ die size for that ammo type

To replenish a stack of arrows (max size d12) from d8 to d10 would cost 20 cp (20% of 1 gp).

#### Replenishing Ammunition

| Maximum Die | Cost per Size Increase |
| ----------- | ---------------------- |
| d20         | 16%                    |
| d12         | 20%                    |
| d10         | 25%                    |
| d8          | 33%                    |
| d6          | 50%                    |
| d4          | 100%                   | 

# Degrees of Success

Sometimes, despite our best efforts, we don't always win. But not all failures are equal—sometimes we mess up a little, sometimes we mess up catastrophically. Sometimes, we even have a chance to prevent failure—at a small, extra cost.

This chapter introduces _degrees of success_, allowing you to judge the scale of success and failure accordingly.

## Success & Failure

When you attempt an action that has a chance of failure, compare your result to the DC and check the list below to see just how well you did.

- **Critical Success:** You succeeded by 10 or more on a skill check, or rolled a natural 20 on an attack. Things have gone perfectly. You achieve your goal and something else happens in your favor.
- **Success:** You achieve your goal.
- **Minor Failure** or **Success at a Cost:** You failed by 1, 2, or 3. You can choose to succeed, but something bad also happens as a consequence.
- **Failure:** You failed by 4 or more. Something bad happens—you take damage, gain Stress, lose a hit die, a Condition worsens, etc.
- **Critical Failure:** You failed by 10 or more on a skill check, or rolled a natural 1 on an attack. It's all gone badly for you and you suffer a second consequence in addition to the normal failure effects—you take extra damage, lose a hit die, drop an item, etc.

Krazak is critically hit by an enemy. He takes damage for failing to dodge, then _additional_ damage (the crit damage) for critically failing—two consequences.

### Boons

When a character succeeds with an ability check or attack roll, something good happens and they get what they wanted. The type of this reward is often clear from the context of the character's action—you hit the monster, you unlock the chest, you identify the potion, etc.

But if the reward _isn't_ clear—or you want to give a character an _extra_ boon for a critical success—consider some of the examples below.

#### Boons

|d20|Boon|
|---|---|
|1|You restore some hit points|
|2|You gain a hit die|
|3|You find some extra gold|
|4|You gain a favor from an ally|
|5|You regain a spell slot|
|6|You deal extra damage|
|7|You heal some mental stress|
|8|You may spend a hit die to recover some hit points|
|9|You may switch places with a nearby ally|
|10|You can move to an advantageous position|
|11|You learn a piece of rare information|
|12|You (temporarily) lose one level of exhaustion|
|13|A magic item regains one charge|
|14|The locals hear about your achievement|
|15|You apply a condition to your enemy|
|16|A god notices your achievement|
|17|A condition improves|
|18|You gain advantage to your next roll|
|19|Your enemies are intimidated by you|
|20|You move your enemy|

### Consequences

When a character fails an action, something bad happens. The type of this consequence is often clear from the context of the character's action—you take damage from an attack, you anger the guards, you fall into the pit, etc.

But if the consequence _isn't_ clear—or you want to give a character an _extra_ consequence for a critical failure—consider some of the examples below.

#### Consequences

|d20|Consequence|
|---|---|
|1|You or an ally take damage|
|2|An enemy reacts and takes an action|
|3|You gain some mental stress|
|4|Take a notch on your weapon/armor/item|
|5|You lose an item|
|6|One of your conditions worsens|
|7|Your torch goes out|
|8|An NPC becomes hostile to you|
|9|You lose some gold|
|10|You learn some misinformation|
|11|Your enemy becomes enraged|
|12|You gain the attention of the local guards|
|13|You drop your weapon|
|14|You stop and fall prone|
|15|You are poisoned or diseased|
|16|You are imprisoned|
|17|A crowd turns against you|
|18|A higher authority learns of your misdoings|
|19|A god punishes you|
|20|You lose some ammunition or hit dice|

### Success at a Cost

When you fail by a narrow margin, you may choose to _succeed at a cost_ instead—you get what you want, but something bad happens to you as a consequence.

This may require some negotiation with the GM—if you can't both agree on the cost, you can't succeed. Check the _Offerings_ table below for some inspiration.

#### Offerings

|d10|Offering|
|---|---|
|1|25% or 50% of your total hit points|
|2|You lose one or more hit dice|
|3|You lose one or more spell slots|
|4|An item gains a notch|
|5|You gain a condition|
|6|You gain the attention of the enemy|
|7|You are moved into a disadvantageous position|
|8|You lose an item|
|9|You gain a level of exhaustion|
|10|You lose some gold|
|11|An NPC is put in a perilous situation|
|12|You lose renown with a person or faction|

# Making a Journey

The wilds are a dangerous place and travel is rarely straightforward outside city walls. Many adventurers have lost their way in dark forests. Many more have died from lack of food, or water, or protection from bandits and monsters—the world is not forgiving to the unprepared traveler.

This chapter introduces the journey phase to make travel a more integral part of the adventure.

## The Journey Phase

If you wish to make a long journey, there are three basic steps to follow: plan your route and gather supplies, travel the distance, and arrive at your destination.

### 1Plan

The first step in making a long journey is planning—you need to decide where you're going, how you're getting there, and who you're travelling with.

1. **Pick the destination:** First, pick your destination. This could be a dungeon, city, or other landmark.
2. **Choose your route:** Next, you need to decide which route you'll take. The length of your route is measured not in miles but in _days_ (assuming an average walking speed of 15 miles per day).
3. **Gather supplies:** Finally, gather any supplies, vehicles, and equipment needed for the journey.

Valiant, Chansi, and Clanda are trying to reach Westwall Tower. It's about 45 miles away, so the journey should take 3 days at a normal walking pace—assuming fair weather and no surprises.

#### Travelling at Night

This chapter assumes you will be making a standard journey during the day. On rare occasions, however, you might want to travel in the dead of night.

When travelling at night, use the same process described in this chapter but simply shift the phase of the day accordingly to suit your schedule. Keep in mind that some checks might be much more difficult at night.

### 2Travel

Now it's time to gather everyone and head out on your journey. The average day is broken up into six parts—dawn, morning, noon, afternoon, dusk, and night—so run through these in sequence for each day of travel.

#### Dawn

Sunlight crests the horizon. It's time to wake up, eat some breakfast, and pack up camp.

- **Check the weather:** The weather can have a drastic impact on your travel plans—especially if you're not properly prepared. You may want to avoid travel completely during heavy rains, storms, and snows.
- **Assign roles:** Decide who is going to be today's guide, forager, scout, and lookout. A character can only assume one role at a time, so pick wisely.
- **Set pace:** Decide what pace you'll be travelling at today—slow, medium, or fast. A slower pace makes it easier to succeed at your roles, but also means that the journey takes longer to complete.
- **Eat breakfast:** Eat some food and drink some water to build up your energy for the travel ahead.
- **Pack up camp:** Put out any cooking fires, strap on your gear, and pack up your camp.

#### Morning

The sun rises and the day becomes warmer. Begin the first half of today's travelling.

#### Noon

The sun is at its peak. Take a short break, sit in the shade, and rest your feet.

#### Afternoon

The sun descends and the temperature cools. Press on to finish the second half of today's travel while you still have some natural light.

#### Dusk

The sun sinks beneath the horizon and the sky darkens. It's time to set up camp for the night, eat a good meal, and reflect on today's travel.

- **Make camp:** Take off your gear and set up camp.
- **Lookout duty:** The lookout takes charge of camp defense and security for the night. While on lookout, a character can only eat and sleep—they don't have time to do or join in with anything else.
- **Guide:** The guide makes a guidance check to confirm the adventuring party's location—did you all stay on track, or have you veered off in the wrong direction?
- **Forage:** The forager makes a foraging check to see if they were able to gather any food or water supplies throughout the day's travel.
- **Eat dinner:** Eat some food and drink some water to help recover from the day's travel.

#### Night

The night is dark and full of terrors—an unwelcoming time for travelers out in the wilds. Travel is very difficult and it's _very_ easy to get lost in the dark, so best get some sleep and recover your energy for tomorrow.

Waking on the second day of their journey, Valiant, Chansi, and Clanda assign roles as they eat: Valiant to guide, Chansi to scout, and Clanda to keep lookout at night. They don't appoint a forager, but that's fine—there's enough rations for a couple of days yet.

The morning is uneventful, and at noon they stop for a short rest and a small drink—it's becoming very warm now thanks to a cloudless sky.

During the afternoon, they find an old peddler sitting on the side of the road—he's suffering from some mild heatstroke. Chansi offers him some water, and the peddler gratefully gives them a freshly caught rabbit in exchange. They continue on.

As dusk settles, the adventurers set up camp for the night. Clanda is on lookout, so she casts a few _Alarm_ spells around the camp's perimeter. Chansi cooks the peddler's rabbit meat for everyone to eat, while Valiant checks their progress on his map—everything seems on track, thankfully.

Tomorrow they might have to think about foraging for fresh water to top up their supplies—especially if it's as warm as today was.

### 3Arrive

After enough days of travel have passed—if you didn't lose your way—you'll arrive at your destination.

#### Variant: Stress

If you're using the _Stress_ rules, check the _Journey Arrival_ table below to see how much Stress you heal upon reaching your destination.

#### Journey Arrival

| Travel Time   | Stress       |
| ------------- | ------------ |
| Up to 1 day   | -1           |
| Up to 1 week  | -2 (1d4)     |
| Up to 1 month | -4 (1d6)     |
| Up to 1 year  | -8 (1d6 + 4) |

After 5 days of travel—a sudden and fierce thunderstorm forcing them to lose 2 days progress—Valiant, Chansi, and Clanda finally make it to Westwall Tower. Relieved, they each restore 2 points of Stress.

## Roles

There are four core responsibilities when travelling: guide, forager, scout, and lookout. A person can only lead or assist one role per day if they wish, and any role not taken will automatically fail any related rolls.

A role can have only one leader, but any number of helpers. The leader makes the roll, the first helper grants advantage, and subsequent helpers grant a +1 bonus.

### A. The Guide

The guide makes sure that everyone is heading in the right direction. If the guide fails, you'll become lost and the journey will take longer as you try to retrace your steps.

If you're the guide, roll Intelligence on the _Guidance_ table at the end of the day to see if you were able to keep everyone on track. Cartography tools, maps, and the Survival skill will help you be a better guide.

**Success:** The party is on track. Subtract today's progress from the remaining travel time.

**Failure:** You veered off course and lost your way. Add 0.5 day to the remaining travel time.

#### Guidance

| DC  | Terrain                                                                              |
| --- | ------------------------------------------------------------------------------------ |
| 5   | Wide open plains; Clear landmarks; Obvious pathway.                                  |
| 10  | Tall landmarks; Small hills.                                                         |
| 15  | Light rain or mist; Woods and hills.                                                 |
| 20  | Moonlight night; Heavy rain or mist; Forest with no clear pathway or markings.       |
| 25  | Fog; Thick and obscure forest; Mountains.                                            |
| 30  | Clouded night; Impossibly thick fog; A shifting maze; Magically treacherous terrain. |

### B. The Forager

The forager finds food and water for the travelling party. If the forager fails, you'll run out of essential supplies long before the journey reaches its destination—so make sure to pack plentiful supplies before you embark if you don't have a skilled forager.

If you're the forager, roll Wisdom on the _Foraging_ table at the end of the day to see how much food and water you were able to hunt throughout the day. Hunting equipment and the Survival skill will help you forage.

**Success:** You recover 2d4 rations-worth of food and water—you can divide this however you like.

**Failure:** You were unable to find anything.

#### Foraging

| DC  | Terrain                                                                                  |
| --- | ---------------------------------------------------------------------------------------- |
| 5   | Lush and verdant forest; Food and water are everywhere.                                  |
| 10  | Forest; Coast; Abundant food and clean water.                                            |
| 15  | Thin woodland and greenwood. Food must be actively hunted and water is harder to find.   |
| 20  | Dry, open plains; Very little food or clean water.                                       |
| 25  | Desert and barren or polluted land; Food is extremely rare and water may need treatment. |
| 30  | Toxic or corrupted deadlands; Food is inedible and water sources are poisoned.           |

- GM:Chansi, roll a Foraging check to see if you found anything. You're in thin woodland, so it takes a little effort—DC 15.
- Chansi:Ok... (rolls 18) ...perfect. Today I found... (rolls 4) ...4 supplies. We're a bit low on water right now, so let's say I found 3 water rations and 1 food ration.

### C. The Scout

The scout ranges ahead during the day's travel and keeps an eye out for dangers. If the scout fails, you may be ambushed by enemies and other hazards.

If you're the scout, you're responsible for making any perception checks during the day to spot incoming risks and dangers—the GM will notify you of anything worth rolling for. A spyglass will help you scout better.

**Success:** You noticed the threat and were able to warn the party in time. You have a chance to avoid the threat entirely, or encounter it at your own pace.

**Failure:** You failed to spot the danger in time and the party are surprised.

### D. The Lookout

The lookout protects the camp at night. If the lookout fails, you risk being attacked while you sleep.

If you're the lookout, you're responsible for making perception checks during the night to spot incoming threats—the GM will notify you of anything worth rolling for. The lookout can't join in any camp activities beyond eating and sleeping, so make sure that whoever takes the lookout shift won't be needed for anything else.

You can set traps and alarms around the camp—dry twigs, tripwires, the Alarm ritual—to help you detect intruders a little better.

**Success:** You were able to rouse the party in time to prevent being ambushed.

**Failure:** You failed to spot the danger in time and the party are surprised.

## Travelling Pace

The speed at which you travel can have an significant impact on your role. There are three main paces: slow, normal, and fast. Check the _Travelling Pace_ table to see exactly how you're affected by the pace you choose.

### Walking

The average character has a walking speed of about 3 miles per hour, and can travel—comfortably—around 15 miles per day. This takes into account the many rest breaks, pauses, and distractions a character will need during the day—especially those that carry heavy gear and armor. Walking long-distance is surprisingly hard work, and a long march in full plate armor is a sure way to strain muscles and hurt yourself.

### Horseback

The average horse walks at much the same pace as a character: 3 miles per hour. While they can gallop much faster, they can only do so on flat ground for very short periods—horses overheat _very_ quickly.

On horseback, a character can comfortably travel 20 miles per day without injuring the horse or becoming too saddle-sore. Anything more arduous requires knowledge and experience of _Animal Handling_.

The main benefit of travelling on horseback is the carrying capacity—a horse can carry much more than a character for much longer without complaint. Horses need plenty to eat and drink, however—2 food and water rations a day—so make sure you bring enough supplies to keep your animals in good shape.

#### Travelling Pace

| Travel Pace | Speed    | Distance | Guide        | Forage       | Scout        | Hide Tracks  |
| ----------- | -------- | -------- | ------------ | ------------ | ------------ | ------------ |
| Slow        | 0.6 days | 10 miles | Advantage    | Normal       | Advantage    | Advantage    |
| Medium      | 1 day    | 15 miles | Normal       | Disadvantage | Normal       | Normal       |
| Fast        | 1.4 days | 20 miles | Disadvantage | None         | Disadvantage | Disadvantage |

# Light & Shadow

Danger hides in darkness. A monster, lurking in the night, pounces as you stumble in the dark. A trap, hidden in the gloom of an unlit dungeon, clicks underfoot ominously. A way out of a deadly maze goes unseen in shadow. A seasoned adventurer soon learns not to travel without a set of dry torches—or a precious lantern—close to hand.

This chapter introduces _light levels_ and rules to help you track light more easily in your campaign.

## Using Light

If you want to make players afraid of the dark—but don't want the overhead of tracking distances—use _light levels_ to help determine what your party can and can't see.

To start using lighting and light levels in your games, simply follow these three steps:

1. **Pick a lighting level:** When the players enter a distinct area—such as a room, dungeon, or overworld—describe the initial level of available light. Is it darkest, dark, dim, bright, or brightest?
2. **Add light sources:** Add up any light bonuses from torches, lanterns, and any other equipment or effects that might be creating light in the area.
3. **Apply light conditions:** Once you know the total level of light in the area, apply any lighting conditions to your affected characters.

Valiant and Clanda are travelling through a cramped, _dark_ dungeon. Valiant is carrying a torch (small, +1 light), while Clanda is casting a _Light_ (small, +1 light) spell. With two small light sources, the _dark_ chamber is now bathed in _bright_ light.

### Types of Vision

To help instill a fear of the dark, it's important that characters don't have easy access to _Darkvision_. To that effect, these rules recommend the following changes:

- **Low-light Vision:** If you have the _Darkvision_ racial trait, replace it with _Low-light Vision_.
- **Darkvision:** If you have the _Superior Darkvision_ racial trait, replace it with _Darkvision_.
- **Brightvision:** If you have neither low-light vision nor darkvision, you are assumed to have _Brightvision_.

Darkvision gained from other sources—such as items, spells, effects, etc—remains unchanged.

Clanda, a high elf sorceress, replaces her _Darkvision_ elf racial trait with low-light vision. She can see in twilight, but has trouble in darkness or with overly-bright light.

Truth, a drow elf paladin of Sune, replaces his _Superior Darkvision_ with darkvision. He can see in the dark—unless it is total darkness—but is easily blinded by brightest light. Drow eyes are not fond of the sun.

Valiant, however—a human cleric of Kelemvor—has brightvision and needs bright light to see clearly.

## Lighting Levels

Light can be measured—and described—with five basic categories of increasing intensity: darkest, dark, dim, bright, and brightest.

When your players enter a notable region—such as a room, dungeon, or overworld—describe the level of light in their environment. Don't worry too much about precise distances at this point—simply apply the same level of lighting to the entire area of interest for simplicity.

#### Light Levels

| Level | Light     | Description                                                                                   |
| ----- |:--------- | --------------------------------------------------------------------------------------------- |
| 0     | Darkest   | No light at all—total darkness, a windowless basement, an unlit dungeon.                      |
| 1     | Dark      | Very faint light—moonlight and starlight, outdoors at midnight, a small candelabra in a room. |
| 2     | Dim       | Fading light—thick stormcloud, heavy fog, a room with weak lights.                            |
| 3     | Bright    | Clear and visible—a cloudy or overcast day, a room with many lights.                          |
| 4     | Brightest | Excessive light—clear light all around, a sunny day, a noble's ballroom party.                |

### 0. Darkest Light

In places where there is no light whatsoever, it is _darkest_—total darkness, a sealed and windowless room, an unlit underground dungeon, a zone of magical darkness, etc.

While the lighting is darkest, you gain the _Blinded_ condition as described below—even if you have darkvision (there is no light for your eyes to reflect and magnify).

#### Blinded

- Condition

- You can't see.
- You automatically fail ability checks that require sight.
- Attack rolls against you have advantage _if_ your opponent can see you.
- Your attack rolls have disadvantage.
- You can't cast spells or use effects that require you to see the target.
- You can't actively target creatures that have hidden from you (such as with a _Hide_ action).
- Your speed is halved.

### 1. Dark Light

In places where there is a faint glimmer of light, it is _dark_—a graveyard at midnight, a dungeon with faintly glowing lichen, a room lit by a rusted candelabra.

While the lighting is dark, you are _Blinded_—unless you have darkvision, in which case you are the _Partially Blinded_ condition instead.

### 2. Dim Light

In places where the light is faded or murky, it is _dim_—a misty forest, the twilight after a setting sun, a volcanic lair with glowing lava, a burning fireplace in a room, etc.

While the lighting is dim, you gain the _Partially Blinded_ condition—unless you have darkvision or low-light vision, in which case you can see normally.

#### Partially Blinded

- Condition

You have disadvantage on Wisdom (Perception) checks that rely on sight.

### 3. Bright Light

In places where the light is abundant and visible, it is _bright_—a clear day, a properly-lit room, a sinister tomb with two huge and flaming braziers.

When the lighting is bright, you can see normally.

### 4. Brightest Light

In places where the light is excessive and practically dazzling, it is _brightest_—a clear and sunny day, the solar room of a sun god's temple, a dungeon illuminated by a raging, white-hot fire elemental, etc.

When the lighting is brightest, you can see normally.

#### Lighting Level Conditions

| Lighting Level | Brightvision      | Low-light Vision            | Darkvision        |
| -------------- | ----------------- | --------------------------- | ----------------- |
| Darkest        | Blinded           | Blinded                     | Blinded           |
| Dark           | Blinded           | Blinded                     | Partially Blinded |
| Dim            | Partially Blinded | —                           | —                 |
| Bright         | —                 | —                           | —                 |
| Brightest      | —                 | (Variant) Partially Blinded | (Variant) Blinded |

#### Revising Blinded

These rules introduce minor updates to the "Blinded" condition (such as halving speed) to make it a more significant—and dangerous—threat to characters.

However, you can continue to use the original rules for "Blinded" if you prefer—it might make the darkness a little less threatening, but it won't break _Light & Shadow_.

## Light Sources

Light sources come in many forms—candles, torches, magical spells, fire elementals, etc. Each source has a power category to reflect the amount of light it produces—tiny, small, medium, large, huge, and gargantuan.

Typically, the bigger the source the more light it can put out—though power and intensity are also a factor. Use the _Light Sources_ table below to determine how much light a particular item (or creature) should emit.

**Total Light:** Once you know the strength of each significant light source in an area, add them to the lighting level to find out just how bright it is.

#### Light Sources

| Power      | Light | Examples                           |
| ---------- | ----- | ---------------------------------- |
| Tiny       | +0.2  | Candle.                            |
| Small      | +1    | Torch, Lantern (hood down), Flare. |
| Medium     | +2    | Lantern (hood up), Fireplace.      |
| Large      | +4    | Brazier, Glass chandelier.         |
| Huge       | +8    | Raging fire elemental.             |
| Gargantuan | +16   | Burning building.                  |

### A. Common Equipment

A seasoned adventurer knows that there are three common, everyday ways to create a light in the dark: candles, torches, and lanterns.

Most of the lighting equipment used by adventurers will fall into one of these three categories—for other bespoke items, use the _Light Sources_ table as a guide.

#### Candles

Candles produce very little light on their own, but they are cheap and easy to make. They produce little smoke and so can be used comfortably indoors.

#### Torches

Torches produce a small amount of light. Like candles, torches are cheap and relatively easy to make—but they produce a lot of smoke and ash as they burn. Avoid using a torch in an enclosed space whenever possible.

#### Lantern

Lanterns burn brighter than the average torch, and—with the right fuel—for much longer. They produce little smoke and can be used comfortably indoors, but can be very fragile—take care not to drop a lantern.

#### Candle

- Light (Tiny)

This candle emits a _tiny_ (+0.2) amount of light for up to 1 hour. You can snuff out a burning candle with an object interaction—each time it is snuffed out, deduct 15 minutes from the remaining burn time.

- **Residue** This common candle produces wax and a noticeable smell as it burns.
- **Dropped** If the candle is carelessly dropped, thrown, or knocked over, roll a d6:
    
    - **1-3:** The candle breaks and can't be used again.
    - **4-5:** The candle is snuffed out.
    - **6:** The candle remains lit.

#### Torch

- Light (Small)

This torch emits a _small_ (+1) amount of light for up to 1 hour. You can extinguish a burning torch with a bonus action—each time it is extinguished, deduct 15 minutes from the remaining burn time. You can spend an action to plant a torch in soft ground without extinguishing it.

- **Residue** This common torch produces smoke, ash, and a noticeable smell as it burns.
- **Dropped** If the torch is carelessly dropped, thrown, or knocked over, roll a d6:
    
    - **1:** The torch breaks and can't be used again.
    - **2-3:** The torch is extinguished.
    - **4-6:** The torch remains lit.

#### Lantern

- Light (Medium)

This lantern emits a _medium_ (+2) amount of light for up to 6 hours. You can extinguish a burning lantern with an action—each time it is extinguished, deduct 15 minutes from the remaining burn time.

You can spent an action to place a lantern carefully on the ground without extinguishing it.

- **Hooded** If your lantern has a hood, you can close it to reduce the light emitted to small (+1) or none (+0).
- **Dropped** If the lantern is carelessly dropped, thrown, or knocked over, roll a d6:
    
    - **1-2:** The lantern goes out and loses d3 hours of fuel.
    - **3-4:** The lantern is extinguished.
    - **5-6:** The lantern remains lit.

#### Lighting Spells

|Spell|Level|Source|Power|Light|Other Changes|
|---|---|---|---|---|---|
|Continual Flame|2nd|PHB|Small|+1|Now has a maximum duration of 8 hours.|
|Control Flames|Cantrip|XGtE|—|—|Now requires _Concentration_.|
|Create Bonfire|Cantrip|XGtE|Small|+1|—|
|Dancing Lights|Cantrip|PHB|Small|+1|You can create up to 5 tiny (candle-like) lights or 1 small (torch-like) light.|
|Dawn|5th|XGtE|Large|+4|—|
|Daylight|3rd|PHB|Medium|+2|Now requires _Concentration_.|
|Faerie Fire|1st|PHB|Small|+1|—|
|Flame Blade|2nd|PHB|Small|+1|—|
|Flame Shield|4th|PHB|Medium|+2|—|
|Flaming Sphere|2nd|PHB|Small|+1|—|
|Investiture of Flame|6th|XGtE|Large|+4|—|
|Light|Cantrip|PHB|Small|+1|Now requires _Concentration_.|
|Produce Flame|Cantrip|PHB|Small|+1|Now requires _Concentration_.|
|Wall of Fire|4th|PHB|Medium|+2|—|
|Wall of Light|5th|XGtE|Large|+4|—|

### B. Spells & Effects

Some magical spells and effects are known to create light—whether intentionally or as a side-effect. Use the _Light Sources_ table as a guide to assign light values to these effects as appropriate.

#### Common Spells

The _Lighting Spells_ table (shown above) lists some of the most common spells and their associated lighting effects.

Some spells have also been adjusted for balance purposes—use these changes to help ensure that lighting equipment (candles, torches, and lanterns) remains an important part of adventuring in your games.

### C. Environmental Light

Some environmental features can emit light—lava, glowing crystals, spectral cave moss, etc. You can account for these light sources separately (using the _Light Sources_ table to determine their strength) or fold them into the base lighting level for the area.

- GM:As you step into the _Ashen Crown_, searing heat threatens to overwhelm you. Glowing lava (+2 light) fills the chamber with a warm, _dim_ light.
- Clanda:Dim light? Hmm, so with my _Light_ spell (+1 light) and Valiant's torch (+1 light), that should get us up to _brightest_ light?
- GM:Yes, the chamber is brightly illuminated right now—you can see clearly across the lava pool.
- Clanda:Excellent. I'll stop casting _Light_ then if you're good to keep holding that torch, Valiant?
- Valiant:Actually I—
- Clanda:_Great_, I knew you wouldn't mind.
- Valiant:...

#### Spell Revisions

These rules introduce minor changes to certain spells (such as by adding _Concentration_) so that they require more effort from your spellcasters—if _Light_ has no significant cost then candles/torches/lanterns quickly become redundant.

However, you can continue to use the original spells if you prefer—it will de-emphasize the need for players to carry lighting equipment, but it won't break the game.

### D. Creatures

Some creatures, whether as part of their nature or through ongoing effects, can act as light sources—burning fire elementals, radiant clerics of a sun god, undead skeletons covered in necrotic darkflame.

Assign these particular creatures a light value to track how they affect their surroundings.

The nightdrake roars, scratching angrily at the ground. With a hiss, it's black scales start to absorb daylight (-2 light), turning the bright grove _dark_...

### EItems and Gear

Some equipment, often magical in nature, can act as a light source—a shining sunblade, a suit of gleaming starsprite armor, a gemstone headlamp, etc.

Assign these items a light value as appropriate to track how they affect their surroundings.

You feel the sunblade hum in your hand as it starts to glow, casting a _small_ light around you (+1 light).

## Room Scales

Not all rooms are the same size, and a larger room naturally requires more light to fill it—a single torch won't make a dent in a gargantuan cavern

A _room scale_ changes the amount of light you need to move up one lighting level. In a _medium_ sized room you need +1 light to go from dark to dim light—but in a _huge_ room you need +4 light to make the same change.

#### Room Scales

|Room Scale|Light Needed per Level|Da|D|Di|B|Br|
|---|---|---|---|---|---|---|
|Tiny|x 0.25|0|0.25|0.5|0.75|1|
|Small|x 0.5|0|0.5|1|1.5|2|
|Medium|x 1|0|1|2|3|4|
|Large|x 2|0|2|4|6|8|
|Huge|x 4|0|4|8|12|16|
|Gargantuan|x 8|0|8|16|24|32|

Room scales are a good way to add some variety to your regions and encourage the use of large/huge/gargantuan lights during adventures.

It can be difficult for players to fill huge/gargantuan spaces with enough light using just candles, torches, and lanterns—especially if they are caught off guard—so try to make sure there are some fun, environmental lighting features that players can interact with.

- GM:As you push it, Valiant, the door slowly opens with a grinding creak. Beyond, you notice the walls spreading out into a _large_, dark room.
- Valiant:What can I see in the room?
- GM:Your torch (+1 light) isn't strong enough to fill the large space—you'll need another light source if you want to fill the dark room with dim light.

### The Twilight Reliquary

To demonstrate how you can use light levels and room scales in your adventures, this section will lay out an example dungeon—the _Twilight Reliquary_.

#### Default Rooms

The _Twilight Reliquary_ is an underground dungeon constructed long ago to house the bones of an ancient shadow dragon—Despair. It creates a permanent gloom over the land above. Many adventurers have tried to brave its dark depths, but few—if any—have returned.

By default, the Reliquary is in total darkness (0 light) with medium room sizes (1 light needed per level). Adventurers need to create at least +2 light to get visibility up from darkest to dim light.

#### The Bonewall

In a _small_ room, stone shelves hold rows of human bones. Looking carefully, you can see veins of black necrotic energy running throughout the bones—you think that it might be a bad idea to disturb them.

The Bonewall is a small room (0.5 light needed per level) in darkest light (0 light). Adventurers need only +1 light to get visibility from darkest to dim light.

#### The Seat of Prayer

One _large_ room appears to have been dedicated to prayer of some kind—carvings in the stone walls indicate humans worshipping a gargantuan shadow dragon.

Two candelabra stand either side of a stone lectern, upon which rests a black leather book. Black candles burn with a sinister, purple light (+1 light each) in this large, dark room.

The Seat of Prayer is a large room (2 light needed per level) in dark light (2 light from the candelabra). Adventurers need to create another +2 light to get visibility up from dark to dim light.

#### The Shadow Throne

At the heart of the Reliquary lies the _Shadow Throne_, the final resting place of Despair. This is a _huge_ room. At one end, Despair's gargantuan skeleton lies curled around a huge, darkstone throne.

Two braziers stand on either side of the room's entrance. They are currently unlit, but a perceptive adventurer may deduce that they will each emit a huge amount of light (+4 light each) when set ablaze.

The Shadow Throne is a huge room (4 light needed per level) in total darkness (0 light). Adventurers need to create at least +8 light to get visibility up from darkest to dim light.

#### Darklight Brazier

- Light (Huge)

This black metal brazier is filled with some kind of dark wood. When set ablaze, it burns with a large purple flame (+4 light) that is cold to touch.

#### Keep Things Simple

It can be tempting to use room scales often in your dungeons, but try not to overcomplicate things for your players—or yourself.

Establish a baseline lighting condition for your region, and reserve room modifiers for your major centerpieces and named rooms.

## Items & Consumables

Across your adventures, you may be able to buy, craft, or loot special items that can help control how your character reacts to certain lighting levels—special lanterns, tinted glasses to diminish light, potions to see in the dark, etc.

When delving into the dark places of the world, make sure equip to yourself with adequate lighting supplies for your journey—to be stuck underground with no light and darksighted monsters all around is a surefire recipe for death and disaster.

#### Flare

- Light (Medium)

This flare emits a _medium_ (+2) amount of light for up to 1 hour. Once lit, a flare can't be extinguished unless it is doused in water—at which point, the flare is ruined and can't be lit again.

#### Darksight Goggles

- Wearable
- Rare

These magical goggles—set with delicate crystal lenses and arcane sigils—amplify light and help you to see in the dark.

- **Sight Beyond Sight** When you wear these goggles, you gain darkvision.
- **Fragile** These goggles are fragile and easily cracked, so be careful not to drop or injure them.

#### Darkstone Shard

- Rare

A shard of darkstone taken from the Shadowfell. This small, bloodthirsty stone absorbs light from the surroundings and creates pockets of darkness. Thieves and rogues are known to prize these shards.

- **Light Devourer** Once per long rest, you can spend a bonus action to activate the darkstone with a drop of blood. For 1 hour, the stone absorbs light and darkens the surrounding area (-1 light).
- **Overheat** If left exposed to bright light for longer than 1 hour, the darkstone cracks and turns to dust.

#### Hellfire Torch

- Light (medium)
- Uncommon

This specially-treated torch burns twice as bright and twice as hot as normal, producing a _medium_ (+2) amount of light for 30 minutes before it turns to ash.

#### Lesser Sunblade

- Weapon (Longsword)
- Rare

This magical sword, crafted by the elves of Sindoril, hums with radiant energy. A favored weapon of dungeon delvers—when commanded, it glows with radiant light.

- **Radiant Power** This blade has 6 charges of power, and it regains 1d3 expended charges at dawn.
- **Radiant Strike** When you hit a creature with an attack using this sword, you can spend 1 charge to deal an extra 1d4 radiant damage.
- **A Light in the Dark** If you are holding the sword, you can spend a bonus action and one charge to speak a command word and emit a glowing white light (+1 light) from the blade.
    
    The glow persists until a) it is dismissed as a bonus action, b) you let go of the sword, or c) 1 hour passes.
    

#### Potion of Cats Eye

- Potion
- Consumable

This white potion turns clear for a few seconds when you shake it. It tastes of smoke and lemons.

You gain darkvision when you drink this potion—the better the quality, the longer this ability lasts for.

|Type|Rarity|Duration|Cost|
|---|---|---|---|
|Lesser|Common|1 hour|50 gp|
|Greater|Uncommon|2 hours|150 gp|
|Superior|Rare|4 hours|450 gp|
|Supreme|Very rare|8 hours|1,350 gp|

#### Solar Lantern

- Light (large)
- Rare

Crafted by the dwarves of Kadrun Volk for use in the undermines, solar lanterns burn with blue fire.

This solar lantern burns through oil three times as fast as normal, but produces a _large_ (+4) amount of light.

#### Tinted Glasses

- Wearable
- Uncommon

These tinted glasses of gnomish design make everything look a little less bright—perfect if you have darkvision and need some protection against the glare of intense daylight.

- **Looking Good** You gain the _Partially Blinded_ condition and can reduce your effective light level by 1.
- **Fragile** These glasses are fragile and easily cracked, so be careful not to drop or injure them.

# Wounds & Injuries

An adventurer without a scar is either very good, very lucky, or very _new_ to the profession—trap-ridden dungeons, rabid monsters, and sharp weapons are notoriously bad for your health. Some adventurers are fortunate enough to retire with just a few injuries to show for their career. Many, however, die from injury long before retirement.

This chapter sets out options for character health, lingering wounds, permanent injuries, and prosthetics.

## Bloodied

Your health is your most precious resource and—as an adventurer—keeping hold of it is not an easy task. A character is considered _bloodied_ when they have lost half of their hit points—when bloodied, they have taken a small cut or bruise.

Some monsters may react differently to you when you are bloodied—becoming frenzied or blood-thirsty—while others may have an easier time detecting you by scent.

- GM:The wolf bites you fiercely, Sarien, causing 7 points of damage.
- Sarien:Gah, I'm _bloodied_ now.
- GM:With the scent of fresh blood in the air, all three wolves turn and look at Sarien hungrily...

### Healing when Bloodied

If you are bloodied, it's a little harder to recover your stamina. While bloodied, you must use a bandage or other first-aid material in order to spend any hit dice and recover hit points when resting. Make sure to keep an eye on your medical supplies.

## Lingering Wounds

When you fall to 0 hit points, you've taken significant damage and gain an open, lingering wound somewhere on your body.

Roll on the _Lingering Wounds_ table below to see which part of you was wounded—or pick one based on the type of damage you suffered.

#### Lingering Wounds

|d10|Area|
|---|---|
|1|An arm|
|2|A leg|
|3|A hand|
|4|A foot|
|5|Your stomach|
|6|Your back|
|7|Your head|
|8|Your face|
|9|Your chest|
|10|Your buttocks|

- GM:The orc's axe slashes you, Viridian, and you take 9 points of damage.
- Viridian:Urk, that's not good—I'm at 0 hit points. Before I black out, I notice... (rolls 9) ...blood dripping from a wound to my chest. Great.
- Clanda:At least it wasn't your butt this time.
- Viridian:Yea. _Lucky me_.

### Exhaustion

Each time you gain an open wound, you also gain a level of _exhaustion_. This exhaustion is permanent for as long as your wound is open and untreated.

You gain exhaustion for each open wound, so watch out—exhaustion effects stack up fast.

#### Exhaustion Effects

|Level|Effect|
|---|---|
|1|Disadvantage on Ability Checks|
|2|Speed halved|
|3|Disadvantage on Attack rolls and Saving Throws|
|4|Hit point maximum halved|
|5|Speed reduced to 0|
|6|Death|

When Viridian gains his new chest wound, he also gains a level of exhaustion. After the battle, Chansi patches him up and treats the wound to remove the exhaustion penalty.

### Treating Wounds

A wound hinders you while it's untreated, making your life difficult with exhaustion. You can spend one hour to treat a wound using first-aid knowledge and supplies—make an Intelligence (Medicine) or Wisdom (Medicine) check (DC 10) to patch up the wound.

A treated wound remains on your character—though it no longer causes exhaustion. A wound will only heal properly during a long rest or with magical healing.

### Healing Wounds

Wounds heal naturally over time. At the end of a long rest, roll to see if your wounds have healed—make a Constitution (Medicine) check (DC 15) for each wound.

Some downtime activities, such as resting, may allow you to roll the check with advantage.

#### Magical Healing

You may use magical effects to heal a wound. You do not gain any hit points from the magic in doing this, however—all of the spell's power is used on your wound.

### Reopened Wounds

If you are critically hit during combat, your treated wounds may reopen. When you take critical damage, roll a d20 for each treated wound you have:

#### Reopened Wounds

|d20|Effect|
|---|---|
|1|The wound reopens and you lose a hit die|
|2-8|The wound reopens|
|9-20|The wound remains closed|

When a wound reopens, it starts applying exhaustion again—you'll need to treat the wound to remove this.

**Untreated wounds:** Any _untreated_ wound you have fails this check automatically (as if you had rolled a 1), causing you to lose a hit die—so try to keep your wounds bandaged at all times.

- GM:The werewolf's razor sharp claws slash wildly at you, Viridian. It's a critical hit—you take 14 points of damage.
- Viridian:Ouch. Better check if my treated chest wound is ok... (rolls 1) ...damn it, it reopens _and_ I lose a hit die. This hurts...
- GM:Those claws have ripped open your bandages, Viridian, and blood pours from your chest wound. You start to feel exhausted again from the wound.
- Viridian:Great. Can this day get any worse?
- GM:The werewolf slashes at you again. It's another critical hit.
- Viridian:Son of a...

### Variant: Simple Wounds

If you want a quick way to make falling to 0 hit points more significant, then use this _Simple Wounds_ variant.

When you fall to 0 hit points, gain a level of exhaustion. This exhaustion can be removed through the normal means (rest/spells/etc).

## Permanent Injuries

Some monsters are especially deadly, destructive, and vicious—when they hit, they hit hard enough to break bones and sever limbs. Dragons, giants, ogres—if it's huge, its attacks are usually extremely violent.

If you are reduced to 0 hit points by a _violent_ attack, you suffer a debilitating _Permanent Injury_. Roll to see which injury you suffer—reroll any nonsensical result.

#### Permanent Injuries

|d10|Injury|Treatment|
|---|---|---|
|1|Lose an arm|Prosthesis (arm)|
|2|Lose a leg|Prosthesis (leg)|
|3|Lose a hand|Prosthesis (hand)|
|4|Lose a foot|Prosthesis (foot)|
|5|Lose an eye|Prosthesis (eye)|
|6|Lose a toe|Medical aid (DC 15)|
|7|Lose a finger|Medical aid (DC 15)|
|8|Gain a horrific, scarring wound|Medical aid (DC 20)|
|9|Gain an internal injury|Medical aid (DC 20)|
|10|Lose half your teeth|Medical aid (DC 20)|

When you gain an injury, you also gain a level of exhaustion. As with lingering wounds, this exhaustion is permanent until you treat the injury in some fashion.

#### Injury Effects

The exact consequences of an injury may vary wildly from game to game and character to character.

If a character gains an injury, make sure to have a brief discussion between player and GM to establish any notable in-game effects beyond the exhaustion increase.

- GM:The _violent_ dragon shows you no mercy, Sarien, as it bites down. Sharp teeth spear into you painfully for 19 points of damage.
- Sarien:Damn it, I'm at 0 hit points. That means a violent injury on my... (rolls 1) ...arm.
- GM:You hear a sickening snap as the dragon's teeth bite into your shoulder, scraping bone. The pain is overwhelming. As its huge head snaps back, you feel a sharp pull and a hear a loud, wet tearing sound. Through the pain, you realize you can't move your left arm. You can't even _see_ your left arm. It's gone.
- Sarien:What. The Hell.
- GM:The last thing you see before you black out, Sarien, is the dragon throw your arm up into the air and—with a snap—swallow it. "Deliciousssss..."

### Violent Monsters & Attacks

When you add the _vicious_ keyword to a monster or attack, make sure to telegraph this to your players clearly in advance—they should know they risk _serious_ injury before they charge in.

- GM:You see the orc warlord ahead, yelling orders to the goblin soldiers. He hasn't seen you yet, but he looks extremely _vicious_.
- Krazak:Vicious? Sounds like a challenge. I charge—
- Valiant:NO YOU DON'T. Plan first, charge later—I'm not paying to put _another_ leg on you.

### Treating Injuries

Once you gain an injury, it remains active on your character and causes exhaustion until it is treated. There are three common ways to treat an injury:

- **Prosthetics:** Wear a prosthetic device to replace a missing body part.
- **Medical Aid:** Receive medical attention—even surgery—to close up major damage and internal bleeding. This can only be done during a long rest when you are in a safe place—a village, town, or city.
- **Magic:** Injuries can be reversed with the _Greater Restoration_ spell (or something of equivalent power).

Once an injury has been treated, the exhaustion is lifted and your character can act normally again.

#### Gameplay over Realism

Injuries should be important events, but they shouldn't make a character unplayable forever. Use them to create short bursts of drama in your game, but avoid penalizing a character for too long.

Once an injury is treated—whether by prosthesis, surgery, or magic—don't apply any more penalties unless it's especially relevant to the story.

## Prosthetics

A prosthesis is an artificial device that can replace or augment a missing (or injured) body part—such as an arm, leg, or eye. You may find prosthetics on your adventures or buy them from artificers, crafters, and healers.

#### False Leg

- Prosthesis (Leg)
- Common

A wooden leg with a secret compartment that can hold a small item. Wearing this treats a _missing leg_ injury.

#### Glass Eye

- Prosthesis (Eye)
- Common

A glass orb made to look like a tabaxi eye. Wearing this treats a _missing eye_ injury.

### Magical Prosthetics

Some prosthetics have been augmented with magic, granting them extra properties. These are much rarer in the world—and far, far more expensive.

#### Arm of Living Bark

- Prosthesis (Arm)
- Rare

A prosthetic arm crafted from living wood. Wearing this treats a _missing arm_ injury.

- **Nature's Grasp** Once per short rest, you may use a free action to stretch out the vines in your arm and extend your reach by 5ft until the end of your turn.

#### Foot of Cloud Walking

- Prosthesis (Foot)
- Rare

A prosthetic foot inscribed with an air enchantment. Wearing this treats a _missing foot_ injury.

- **Cloudwalk** Once per short rest, you may jump twice as far or twice as high as you normally would.

#### Hand of Static

- Prosthesis (Hand)
- Rare

A metal prosthetic hand inscribed with arcane glyphs and sigils. Wearing this treats a _missing hand_ injury.

- **Static Shock** Once per short rest, when you make a successful melee attack, you may use a free action to add 2d6 lightning damage to your damage.

## Lycanthropy

**_[Lycanthropy](https://www.scabard.com/pbs/campaign/4777087/note/5626064)._** Player Characters infected with lycanthropy may continue to be played. These PCs must take precautions to restrain themselves on the night of the full moon, and must actively seek a cure. Any lycanthropic PC who kills and devours an innocent humanoid (even through no fault of their own) becomes a villainous [NPC](https://www.scabard.com/pbs/campaign/4777087/ccategory/4793990) under the control of the DM. You do not use the stats from the Player's Handbook, use the following modifications instead.

### Heightened Senses

At 3rd level, you gain the improved senses of a natural predator. You have advantage on Wisdom ([Perception](https://www.dndbeyond.com/sources/dnd/free-rules/playing-the-game#Skills)) checks that rely on hearing or smell.

### Hybrid Transformation

Also at 3rd level, you learn to control the lycanthropic curse that courses through your veins. As a bonus action, you transform into a special hybrid form for up to 1 hour. You can speak, use equipment, and wear armor while in this form, and can revert to your normal form as a bonus action. You automatically revert to your normal form if you fall [unconscious](https://www.dndbeyond.com/sources/dnd/free-rules/rules-glossary#UnconsciousCondition) or die.

This feature replaces the [rules](https://www.dndbeyond.com/sources/mm/monsters-l#PlayerCharactersasLycanthropes "rules") for lycanthropy in the _[Monster Manual](https://www.dndbeyond.com/sources/mm "Monster Manual")_. Once you use this feature, you must finish a short or long rest before you can use it again.

#### Hybrid Transformation Features

While you are transformed, you gain the following benefits and drawbacks:

_**Feral Might.**_ You have advantage on Strength checks and Strength saving throws, and you have a +1 bonus to melee damage rolls.

_**Resilient Hide.**_ You have resistance to bludgeoning, piercing, and slashing damage from nonmagical attacks not made with silvered weapons. Additionally, while you are not wearing heavy armor, you have a +1 bonus to AC.

_**Predatory Strikes.**_ Your unarmed strikes are treated as a weapon. You can use Dexterity instead of Strength for the attack and damage rolls of your unarmed strikes, which deal 1d6 bludgeoning or slashing damage (your choice). This damage increases to 1d8 at 11th level.

Additionally, when you use the [Attack](https://www.dndbeyond.com/sources/dnd/free-rules/rules-glossary#AttackAction) action to make an unarmed strike, you can make one additional unarmed strike as a bonus action.

_**Bloodlust.**_ If you start your turn with fewer hit points than half your hit point maximum, you must succeed on a DC 8 Wisdom saving throw or move directly toward the nearest creature and use the [Attack](https://www.dndbeyond.com/sources/dnd/free-rules/rules-glossary#AttackAction) action against that creature. If you’re concentrating on a spell or are under an effect that prevents you from concentrating (such as the barbarian’s Rage feature), you automatically fail this saving throw.

If you have the Extra Attack feature, you can choose whether to use it for this frenzied attack. If more than one creature is equally near to you, roll randomly to determine your target. Once your attack is resolved, you regain control of yourself.

# Death & Resurrection

There are only two certainties in life: death and taxes. Throughout their career, adventurers face danger and destruction at every turn—and not everyone is lucky enough to make it back to town alive.

This chapter sets out the _Dying_ condition and includes rules for persistent death saves, funerals, character wills, and resurrection magic.

## Dying

When you are reduced to 0 hit points, you gain the _Dying_ condition. You can't move, and your ability to talk is limited. This condition ends if you regain any hit points.

#### Dying

- Condition

- You drop whatever you're holding and fall prone.
- You can't move, take actions, or use reactions.
- You're aware of what's happening 15 ft around you.
- You can speak a maximum of _two_ words per round.
- Attack rolls against you have advantage.
- You automatically fail STR/DEX saving throws.
- You must make a _death saving throw_ at the start of your turn. If you fail three death saving throws, you die.

### Death Saving Throws

While you are dying, you must make a death saving throw at the start of your turn to see how long you can cling onto life—if you fail three death saving throws, you die.

When you make a death saving throw, roll a d20 and check the _Death Saving Throw_ table below to see what happens to you.

#### Death Saving Throw

| d20   | Outcome                                                |
| ----- | ------------------------------------------------------ |
| 1     | You fail two death saving throws.                      |
| 2-9   | You fail one death saving throw.                       |
| 10-19 | You pass one death saving throw.                       |
| 20    | You regain 1 hit point and the _dying_ condition ends. |
### Taking Damage

If you are hit by any damaging attack whilst dying, you automatically fail one death saving throw. Critical damage, likewise, causes you to fail one death saving throw.

#### Limited Awareness

When a character has the _Dying_ condition, their awareness and ability to communicate with other characters is severely restricted—dying is hard work.

Choose your character's two words carefully for each round, and avoid table-talk whenever possible.

## Death

Sometimes, despite your best efforts, your best just isn't good enough—all things come to an end, and your character is unfortunately no exception.

But with any luck, you fought a good fight and left the world a little less dark than when you first joined it.

### Your Funeral

No corpse should be left out in the open to be torn apart by birds and wild dogs—a hero deserves a hero's send-off.

If your adventuring party are able to recover your body, bury it, and throw an appropriately lavish funeral (at least 50 gp for each of your character levels, or appropriate roleplay), they each gain one favor from you from beyond the grave.

### Reading of the Will

You can leave a will behind to confirm who the heirs to your property are. This can be arranged in retrospect with your GM _after_ the character's death if necessary. The reading of the will usually takes place at your funeral, or before the introduction of a new character.

This might be the last opportunity for your character to say any final words, so make the most of it.
### A New Beginning

Once you've added your character's name to the graveyard, it's time to start anew with a fresh character or an elevated NPC/henchman.

There are a variety of ways to determine your starting level and wealth—choose the method that fits your game.

#### Starting Level

- **Same Level:** Start at the same level as your old PC.

#### Starting Wealth

- **Inheritance:** Inherit gold and starting items from your old character—whatever was passed on in your will. Your new character should be known or related to your old character in some fashion.

### Mercer Resurrection Rules 
Character death can often prove to become a minor inconvenience in some campaigns once the adventuring party reaches a certain level, with spells being available to return fallen comrades from the afterlife with temporary setbacks, robbing a small element of danger, and threat to future conflicts and challenges within the story. This rule will elevate the gravity of character death.

If a character is dead, and a resurrection is attempted by a spell or spell effect with longer than a 1 action casting time, a Resurrection Challenge is initiated. Up to three members of the adventuring party can offer to contribute to the ritual via a **Contribution Skill Check.** The DM asks them each to make a skill check based on their form of contribution, with the DC of the check adjusting to how helpful/impactful the DM feels the contribution would be.

For example, praying to the god of the devout, fallen character may require an Intelligence (Religion) check at an easy to medium difficulty, where loudly demanding the soul of the fallen to return from the aether may require a Charisma (Intimidation) check at a very hard or nearly impossible difficulty. Advantage and disadvantage can apply here based on how perfect, or off base, the contribution offered is.

After all contributions are completed, the DM then rolls a single, final Resurrection success check with no modifier. The base DC for the final resurrection check is 10, increasing by 1 for each previous successful resurrection the character has undergone (signifying the slow erosion of the soul’s connection to this world). For each successful contribution skill check, this DC is decreased by 3, whereas each failed contribution skill check increases the DC by 1.

Upon a successful resurrection check, the player’s soul (should it be willing) will be returned to the body, and the ritual succeeded. On a failed check, the soul does not return and the character is lost.

Only the strongest of magical incantations can bypass this resurrection challenge, in the form of the True Resurrection or Wish spells. These spells can also restore a character to life who was lost due to a failed resurrection ritual.

If a spell with a casting time of 1 action is used to attempt to restore life (via the Revivify spell or similar effects), no contribution skill checks are allowed. The character casting the spell makes a Rapid Resurrection check, rolling a d20 and adding their spellcasting ability modifier. The DC is 10, increasing by 1 for each previous successful resurrection the character has undergone. On a failure, the character’s soul is not lost, but the resurrection fails and increases any future Resurrection checks’ DC by 1. No further attempts can be made to restore this character to life until a resurrection spell with a casting time higher than 1 action is attempted.

# Cheating Fate

In the face of certain death, a lucky adventurer might just find a way to cheat fate and live on to fight another day. Today is a good day to survive.

This chapter introduces _fate points_ for player characters and how you can use them in your game.

## Fate Points

If you would suffer a killing blow or fail your last death saving throw, you may spend a _fate point_ to cheat death in some fashion.

Perhaps you were knocked unconscious, or the scorpion's poison wasn't strong enough to finish you off, or it was just a flesh wound? Discuss with your GM exactly how it is you managed to survive your ordeal.

- GM:You lie unconscious and dying, Viridian, but the orc is without mercy—she stabs down with her spear. Lose a death saving throw.
- Viridian:Oh no, that was my last one... I'm dead. Or I _would_ be if I didn't have one last _fate point_ to use. Perhaps the spear _missed_ me...?
- GM:Fate is in your favor. The spear wouldn't miss given its proximity, but let's say it missed your vital organs. Everyone thinks you're dead, and you remain unconscious _but alive_ for the rest of the scene.
- Viridian:Unconscious and alive sounds good to me.

#### Why Use Fate?

When you roll dice, fate can be cruel—even _unfair_—at times. Fate points give players a way to mitigate the meanest twists of fate without neutering the threat entirely.

### Gaining Fate

1st-level characters start with one fate point—a reward for becoming an adventurer in the first place. You can hold up to three fate points at any one time, and fate points can't be exchanged between characters.

Beyond this, fate points are _extremely_ rare. To gain fate, players must face—and defeat—the most dangerous monsters in your world. Dragons, liches, beholders—these _fated_ monsters are significant threats to the party.

Fate smiles on those who brave the darkest of these _optional_ dangers and survive.

**One Monster, One Point:** A fated monster rewards only 1 fate point in total when defeated—the players must decide who among them is lucky enough to take it.

- GM:You hear that the black dragon Kaladax has laid waste to Merrowford and taken residence in the burnt wreckage of the town.
- Clanda:Interesting. Is he a _fated_ dragon?
- GM:Kaladax is a major power, and certainly fated.
- Viridian:Could be worth investigating. I don't like being fate-less now, myself...

### Spending Fate

When you spend a fate point, you (usually) can't act for the rest of the scene—everyone, friend and foe alike, thinks you're dead or otherwise not worth any attention. But you are immune to any further damage during the rest of the scene, regardless of whatever else happens around your unconscious body.

At the end of the scene—or whenever appropriate—you regain consciousness with 1 hit point. You also recover any failed death saving throws.

# Survival Conditions

Characters don't exist in a bubble; they affect and are affected by their surroundings—going without sleep makes you tired, failing to eat makes you hungry, not drinking makes you thirsty. With _survival conditions_, players track the physical state of their character. It's hard, thirsty work being an adventurer—do you have the resources to survive?

This chapter introduces several survival conditions and examples of how to use them in your game.

## Your Conditions

With _survival conditions_, players keep track of three basic physical states that can affect their character's general performance: hunger, thirst, and fatigue.

1. **Hunger:** Few things burn through calories as fast as adventuring, so keep some snacks in your pocket.
2. **Thirst:** Adventure, travel, and combat are thirsty work. Keep a waterskin close by to avoid dehydration.
3. **Fatigue:** It takes a keen mind to watch out for danger, so get regular sleep to stay alert and aware.

These basic conditions worsen naturally throughout the day, becoming more severe and—if left untreated—can eventually lead to increasing levels of exhaustion. Depending on the situation, this can be a real problem for your character:

Viridian has been travelling at speed through the Emerald Rift for two days, chased by the relentless _Witch of Gloamgard_. His supplies are running low, and—due to the chase—hasn't been able to rest easily in the haunted woods.

The bard is ravenous (5 hunger), parched (3 thirst), and barely awake (6 fatigue)—he has +2 exhaustion from his conditions, cutting his speed in half. Unless Viridian can find food fast for some quick energy, the dreaded Witch will be right on his heels.

Keep an eye on your conditions and use your supplies to manage them as best you can—eat food to stave off hunger, drink water to quench your thirst, and get some sleep to remove your fatigue.

#### Survival Conditions

|Stage|Hunger|Thirst|Fatigue|Temperature|Effect|Stamina DC|
|---|---|---|---|---|---|---|
|0|Stuffed|Quenched|Energized|Perfect|−1 Exhaustion|—|
|1|Well-fed|Refreshed|Well-rested|Comfortable|—|5|
|2|Ok|Ok|Ok|Ok|—|10|
|3|Peckish|Parched|Tired|Noticeable|—|15|
|4|Hungry|Thirsty|Sleepy|Uncomfortable|—|20|
|5|Ravenous|Dry|Very sleepy|Overwhelming|+1 Exhaustion|25|
|6|Starving|Dehydrated|Barely awake|Unbearable|+1 Exhaustion|30|

#### Using Survival Conditions

Survival conditions can be a fun, easy way to immerse players in the fiction of your campaign, but they only have an impact if resources—like food and water—are restricted and hard to come by.

If your characters have easy access to food and water—or time is not an issue, or survival is not an important theme in your game—conditions won't have much impact.

### Gaining a Condition

Characters gain hunger, thirst, and fatigue in four primary ways whilst adventuring: through the natural passage of time, by falling to 0 hit points, through failure consequences, and by suffering certain monster attacks.

#### Time of Day

As the day progresses, characters become more hungry, thirsty, and tired. Conditions worsen at dawn, noon, and dusk—the specific effects are listed in the table below.

#### Hunger, Thirst & Fatigue

|Time|Hunger|Thirst|Fatigue|
|---|---|---|---|
|Dawn|+1|+1|—|
|Noon|—|—|+1|
|Dusk|+1|+1|+1|

Across a normal, uneventful day, a character will gain +2 hunger, +2 thirst, and +2 fatigue—this means a character needs 2 rations of food, 2 rations of water, and a good night's sleep each day to stay in good form.

During the adventure, the GM—or whoever else is keeping track of time—announces the changes in character conditions when appropriate.

- GM:It's been a long afternoon, but _dusk_ approaches. Everyone gains +1 hunger, +1 thirst, and +1 fatigue.

#### Falling to 0 HP

Nearing death is an exhausting shock to the body. If you fall to 0 hit points for any reason—including shapeshifted forms such as _Wild Shape_—you gain +1 fatigue.

#### Consequences

You may gain survival conditions as a consequence of failing an action, at your GM's discretion—or, if using the _Degrees of Success_ rules, offer to gain a condition and succeed at a cost.

- GM:To cross the pit requires a simple jump, Clanda—roll a DC 10 Athletics check.
- Clanda:Ok.. (rolls 9) ...augh, so close!
- GM:You clear the jump with a stumble, noticing a rumble in your stomach as you land. Gain +1 hunger.

#### Monster Attacks

Monster and environmental effects can drain characters of their stamina and resources. As GM, add condition modifiers to some of your existing monster attacks and traps—or add brand new condition-causing powers.

- A fire elemental burns the air around you with a blast of searing heat: you gain _+1 thirst_.
- A green ooze wraps around your arm and sucks the nutrients from your flesh: you gain _+1 hunger_.
- An eldritch mage whispers a cacophonous verse and commands you to sleep: you gain _+1 fatigue_.

### Improving Your Condition

Whenever appropriate, your character can attempt to improve their physical condition in a manner that makes sense. Some of the most common actions are:

- **Eat a ration of food:** −1 hunger per ration. Better quality food may relieve more hunger per ration.
- **Drink a ration of water:** −1 thirst per ration. Better quality water may relieve more thirst per ration.
- **Get a good night's sleep:** (undisturbed) −3 fatigue. A disturbed night's sleep grants only −1 fatigue.

- GM:You rise at dawn, Valiant, your stomach growling. Gain +1 hunger and +1 thirst.
- Valiant: I'll eat one of my rations (−1 hunger) and take a swig from my waterskin (−1 thirst)—that should keep me going till nightfall.

## Exhaustion

As your character's condition worsens, they become increasingly more exhausted. Whenever a condition reaches stage 5 or 6, it generates +1 exhaustion—for a maximum of +3 exhaustion across all conditions.

Valiant is ravenous (5 hunger), dry (5 thirst), and barely awake (6 fatigue)—he has +3 exhaustion from his unfortunate conditions.

Unable to find food, he later finds himself starving (6 hunger). His exhaustion remains at +3.

**Persistent:** Once a condition has begun to cause exhaustion, that exhaustion remains on your character until the condition is sufficiently improved (such as by being reduced to stage 4 or lower).

### Relieving Exhaustion

A condition stops causing exhaustion once it has been improved to stage 4 or higher. After the next short rest, update the character's exhaustion counters.

Valiant finds a cache of food supplies. He immediately eats 3 rations-worth, healing 3 hunger and improving his overall condition to _Peckish_.

His _Hunger_ condition continues to add +1 exhaustion until he takes a short rest, at which point his total exhaustion drops from +3 to +2.

## Stamina Check

It's hard work being an adventurer—battles to fight, ropes to climb, rivers to swim—and such activity can be draining to those without the proper constitution.

After a particularly strenuous event, the GM can ask you to make a _Stamina check_ (Constitution saving throw) against the DC of your best condition. A failure means that your stamina was tapped during the event—roll a d6 to see which condition worsens.

#### Stamina Check

|d6|Outcome|
|---|---|
|1-2|+1 Hunger|
|3-4|+1 Thirst|
|5-6|+1 Fatigue|
|—|—|

- GM:The last goblin drops his dagger and flees into the night. Well done, everyone. Now roll a Stamina check.
- Valiant:14. I didn't break a sweat.
- Sarien:9. That's what I get for skipping breakfast... (rolls 6) ...+1 fatigue. Getting _sleepy_ here.
- Clanda:7. Damn, not enough. I gain... (rolls 4) ...+1 thirst. Great, and my waterskin's dry already. Anyone got a drink? I'm feeling pretty _thirsty_ right now.

## Variant: Temperature

If you want to give a mechanical environmental effects, add the _Temperature_ survival condition to your game.

With the _Temperature_ condition, characters must watch out for the weather and keep their body temperature in check to avoid suffering from exhaustion.

#### Using Temperature

The _Temperature_ condition works best in games that feature a lot of exploration in harsh climates with unpredictable or unforgiving weather patterns—a scorching desert, a frozen mountain pass, a temperamental jungle.

### Gaining Temperature

Your body temperature is affected primarily by the weather and environment. The GM describes the baseline temperature when appropriate—often when you enter or research a new region, dungeon, or lair:

- GM:It's starting to rain outside and, as you step out, an _uncomfortably_ cold wind blows past. You think it might become _unbearably_ cold outside tonight if the rain continues to pour.

#### Hot or Cold

The temperature conditions apply to both hot and cold climates—it could be _unbearably cold_ in the arctic wastes, or _unbearably hot_ in the arid desert.

#### Time of Day

Temperatures change throughout the day as the sun rises and sets. Check the table below to see how the baseline temperature might be affected by your climate.

#### Climate Temperature Change

|Time|Hot|Moderate|Cold|
|---|---|---|---|
|Morning|+1|—|+1|
|Afternoon|+2|−1|—|
|Evening|+1|—|+1|
|Night|—|+1|+2|

#### Monster Effects

Some monsters can affect the surrounding temperature by their sheer presence, producing scorching heat or chilling winds.

- GM:Frozen winds surround the _King of Frost_—it is unbearably cold around him. If you end your turn adjacent to him, you'll suffer the chill...

### Improving your Temperature

Whenever appropriate, your character can improve their temperature in a manner that makes sense. Some of the most common actions are:

- **Appropriate clothing:** Thick furs and cloaks will help protect you from the cold, while thin fabrics will help cool you in the heat.
- **Find shelter:** Sometimes you have to take a break and rest. Build a shelter to keep warm against a freezing wind, or provide shade against a scoring sun.
- **Cast spells:** Some spells and abilities may provide you with a burst of much-needed warmth or cold.
- **Racial abilities:** Some races are naturally resilient against cold or heat. These innate characteristics will help protect you against certain temperatures.

# Stress & Afflictions

The adventuring life is not an easy one. Moving from town to town, delving into dark dungeons and hunting dangerous monsters for perhaps a few gold coins, is not a safe—or sane—way to make a living.

This chapter introduces mechanics to track a character's stress level and the lasting consequences these lingering, mental afflictions can have on their adventuring career.

## Stress

Stress is a measure of pressure on a character's mental state, representing a build-up of negative emotions such as anger, fear, frustration, and irritation. Too much Stress is bad for your mental health and, if not treated carefully, can lead to detrimental Afflictions—or even death.

Characters can suffer up to 40 points of Stress before they reach breaking point. To prevent this, they'll need to find ways to relax and recover during downtime.

### Gaining Stress

Stress is gained through danger, hardship, and adversity—suffering a critical hit from an enemy, hearing an unearthly moan from a dark room, sleeping rough in the cold rain, watching an ally die. Anything that threatens the mental well-being of your character can inflict Stress.

When choosing how much Stress to inflict, decide how significant the event is to the character—is it minor, moderate, major, or monstrous? The more emotionally significant, the higher the amount of Stress.

The more an event conflicts with the fundamental nature of your character, the greater the amount of Stress you'll suffer—a bard may be more embarrassed to ruin a performance than a wizard, while a lawful paladin is more hurt by a broken oath than a lawless rogue.

#### Gaining Stress

|Category|Stress|Description|
|---|---|---|
|Minor|+1|A small frustration, worry, or irritant: missing an attack, falling down, hearing a noise in the dark.|
|Moderate|+2  <br>(1d4)|You've made a critical error or something is seriously at risk: being caught lying, learning that the villain has escaped, being outnumbered.|
|Major|+4  <br>(1d6)|Something devastating to your character or their beliefs: breaking an oath, falling to 0 hp, finding a heap of fresh corpses.|
|Monstrous|+8  <br>(1d6 + 4)|Something incomprehensible or world-shattering: meeting a god, being betrayed by your closest friend, watching a loved one die.|

#### Consequential Stress

You can gain Stress as a direct consequence of failing an action—missing an attack, breaking a lockpick, being caught in the middle of a lie. The GM will usually notify you that this is a risk _before_ you make your attempt.

Here we see Chansi attempt—and fail—to pick a pick.

- Chansi:Ok, let's see what's in this chest. I want to pick the lock on this thing—what's the DC?
- GM:It's a secure metal chest, so DC 20.
- Chansi:Easy. Lemme just... (rolls 15) ...ugh, fail.
- GM:You hear the pins clicking in the lock, Chansi, but you can't understand why they're not setting. It's a frustrating failure for you—gain 1 point of Stress.

#### Stress as a Consequence

Whether through a consequence or an explicit Stress check, a character should gain Stress _only_ as a consequence for failing a roll of some kind—such as an attack roll, a defense roll, a skill check, or a Stress check.

#### Stress Check

In cases where the environment or situation provokes an emotional response—standing before a dragon, entering a decrepit tomb, hearing a terrifying sound—you may be asked to pass a Stress check (Wisdom saving throw) to avoid gaining some Stress.

### Snapping

Too much Stress can be unhealthy for your character, causing long-term problems. The first time you gain 50% or more Stress after a long rest, you snap and develop a mental Affliction. You can only snap once per long rest, though you still risk hitting your breaking point if you reach 100% Stress.
### Breaking Point

When a character gains 40 points of Stress, they hit breaking point. In this state, your character is reckless, dangerous, and _extremely_ vulnerable.

If you are hit by a damaging attack while at breaking point, your character suffers a fatal heart attack. You fall to 0 hit points, fail any remaining death saving throws, and die immediately.

#### Stressful Situations

These are some example situations that might trigger Stress. Some characters may respond more strongly than others depending on their background—a fighter may be less stressed about being outnumbered in battle, while a necromancer might not react to the sight of a dead body.

- Badly failing an attack or skill check
- Hearing an unearthly roar from the dark
- Embarrassing yourself in front of someone
- Falling over or being knocked down
- Being disarmed or disabled
- Critically failing an attack or skill check
- Seeing a heap of mutilated corpses
- Facing a huge or formidable enemy
- Being caught lying
- Being surrounded, outnumbered, or out-flanked
- Being critically hit by an attack
- Seeing an ally die
- Accidentally hurting a friend
- Seeing a hideous abomination
- Breaking an oath
- Being betrayed by an ally

### Healing Stress

Stress is healed through success and relaxation—disarming a trap, defeating a formidable opponent, carousing in town, sleeping in a warm bed. Anything that helps your character feel better can heal Stress.

The amount healed depends on the significance to your character. The more it aligns with your character's personality, the more you heal (at the GM's discretion)—rogues benefits more than mages from lockpicking, while clerics benefit more than fighters from prayer.

#### Healing Stress

| Category | Stress        | Description                                                                                                                                                               |
| -------- | ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Minor    | −1            | A small success or bit of good news: disarming a trap, playing a song, relaxing with your friends.                                                                        |
| Moderate | −2  (1d4)     | A critical success or special achievement: eating a well-cooked meal, finding a hoard of treasure, repairing something important.                                         |
| Major    | −4  (1d6)     | You've beaten the odds and gained a major victory: defeating a dangerous enemy, saving an ally from death, completing a work of art.                                      |
| Majestic | −8  (1d6 + 4) | You've achieved a long-term goal or done something thought near impossible: bringing a friend back from death, finishing a masterpiece, receiving praise from your deity. |

Here we see Clanda attempt to disarm a magical trap with her arcane training, healing Stress in the process. As a sorceress disarming a _magical_ trap, she heals a moderate amount of Stress instead of a minor amount.

It is much harder to heal Stress than it is to gain it, so you'll need to be proactive in treating your Stress level before it becomes insurmountable. Rest when you can, and try not to over-exert yourself.

#### Downtime

While out travelling, a good time to heal Stress is during downtime and through sleep. Here, Sarien takes advantage of his downtime during a night's rest to meditate and clear his mind.

- GM:Ok, camp's been set up for the night. What do you all do for the next few hours?
- Sarien:I spend a couple of hours meditating.
- GM:Ok—it's been an easy day, so make a DC 10 Wisdom check.
- Sarien:No problem... (rolls 17).
- GM:You're able to calm your mind and organize your thoughts, Sarien. Heal 2 points of Stress.

#### Taking a Long Rest

When you complete a long rest in a sanctuary, such as a village, town, or city, you heal all stress. Reduce your Stress level to 0.

Returning to the town of Darrowmore, Valiant takes a long rest and begins a week of training. Once the week is over, he reduces his Stress to 0.

#### Calm Emotions

When you are affected by the _Calm Emotions_ spell—or other similar magic spells and effects—you heal a moderate amount of Stress.

#### Stress Relief

These are some things a character might do to reduce their stress levels. Not everyone will recover in the same way—an introvert may unwind best on their own with a good book and some hot tea, while an extrovert may want to throw a raucous and extravagant party to blow off steam.

- Disarming a trap
- Defeating a dangerous enemy
- Eating a hot, well-cooked meal
- Making people laugh with a joke
- Listening to a bard perform a song
- Carousing in a rowdy tavern
- Picking a lock
- Sleeping in a warm, comfortable bed
- Praying to your deity
- Finding a chest of treasure
- Arriving somewhere safely after a long journey
- Spending time with family and friends
- Learning a new skill
- Engaging in a hobby
- Playing with a pet
- Rolling dice and playing some games
- Fulfilling an oath or promise
- Protecting an ally from harm
- Meditating and resting
- Making a discovery

## Afflictions

An _Affliction_ is a stress-induced mental issue suffered by a character when they gain too much Stress. Afflictions affect your character's abilities and can only be cured during downtime.

When you gain 50% Stress for the first time after a long rest, roll on the _Afflictions_ table to see which new mental Affliction you develop. If you roll a duplicate, roll again until you get a new result.

#### Afflictions

| d100  | Affliction   | Modifier                           |
| ----- | ------------ | ---------------------------------- |
| 01-06 | Fearful      | Disadvantage on WIS checks & saves |
| 07-12 | Lethargic    | +1 exhaustion until removed        |
| 13-18 | Masochistic  | Disadvantage on CON checks & saves |
| 19-24 | Irrational   | Disadvantage on INT checks & saves |
| 25-30 | Paranoid     | Speed is halved                    |
| 31-36 | Selfish      | Disadvantage on CHA checks & saves |
| 37-42 | Panic        | Disadvantage on DEX checks & saves |
| 43-48 | Hopelessness | Disadvantage on STR checks & saves |
| 49-54 | Mania        | Disadvantage on attack rolls       |
| 55-60 | Anxiety      | Disadvantage on Stress checks      |
| 61-66 | Hypochondria | Hit point maximum is halved        |
| 67-72 | Narcissistic | Disadvantage on ability checks     |
| 73-77 | Powerful     | +2 to all damage rolls             |
| 78-82 | Focused      | +2 to all attack rolls             |
| 83-87 | Stalwart     | +2 AC                              |
| 88-91 | Acute        | Advantage on INT checks & saves    |
| 92-96 | Perceptive   | Advantage on WIS checks & saves    |
| 97-00 | Courageous   | Advantage on CHA checks & saves    |

- GM:Sarien, you hear a sickly moan from the shadows. Make a DC 10 Wisdom saving throw to see if you can keep your composure.
- Sarien:Sure... (rolls 6) ...damn, not enough.
- GM:Gain 1 point of Stress, Sarien.
- Sarien:That pushes me over 20—looks like I'm feeling pretty... (rolls 41) ...panicked. How _appropriate_.

### Curing Afflictions

Afflictions don't go away on their own—your character must dedicate time to treating their mental state. During a long rest, your character can attempt to treat one of their Afflictions in an appropriate fashion—carousing, praying, resting, meditating, etc.

Roll a d20 to make an Affliction Removal attempt. Some downtime activities, such as resting, may allow you to roll with advantage—bear this in mind if your Afflictions are proving hard to clear, before you become overwhelmed by them.

#### Affliction Removal

| d20   | Result                                                                                            |
| ----- | ------------------------------------------------------------------------------------------------- |
| 01    | **Critical Failure:** You fail to cure your Affliction, gaining a new one in the process.         |
| 02-09 | **Failure:** You fail to cure your Affliction.                                                    |
| 10-19 | **Success:** You cured your Affliction.                                                           |
| 20    | **Critical Success:** In a moment of clarity, you cleared yourself of all Afflictions and Stress. |

You can only make one Affliction Removal attempt per in-game week, so make the best of it.

#### Greater Restoration

The _Greater Restoration_ spell may be used to let you make an Affliction Removal attempt outside of a long rest. You can attempt this once outisde your once-per-week attempt.

From levels 1-10, you may roll your _Affliction Removal_ check with advantage when using Greater Restoration. From levels 11-20 however, roll with disadvantage.

### Mental Breakdown

If your character gains more than 3 Afflictions, they suffer a complete mental breakdown.

If you are hit by a damaging attack while at breaking point (100% Stress), you fall unconscious. No amount of jostling or damage can wake you.

After 2d4 hours, you awaken with an indefinite madness—roll on the _Indefinite Madness_ table (DMG p260) to see what you are afflicted with.

#### Recovery

If a character is placed in good care, there is a rare chance they may eventually recover from their breakdown. For each month of proper care, they may roll an _Affliction Removal_ attempt with disadvantage. A month after they have removed all Afflictions, they recover their senses and can be active again.

Each time a character recovers from a breakdown, their minimum Stress increases by 10.

## Items & Consumables

Across your adventures, you may be able to buy, craft, or loot special items that can help you to manage stress—magic gear, soothing teas, precious potions, etc.

#### Soothing Stones

- Item (Small)
- Common

A pair of small, stone balls engraved with dwarven runes. They make a soothing sound when held in one hand.

- **Relaxing Sound** During camp, if you successfully _Relax in Solitude_, you heal an additional +1 Stress.

#### Elixir of Sanity

- Potion
- Consumable

This thick purple elixir looks almost alive. When you stare at it, you get the feeling you're being watched.

- **Iron Soul** When you drink this elixir, you may roll any Stress checks with advantage for one hour.

#### Ring of Clarity

- Item (Small)
- Rare

This fine silver ring, forged by the drow monks of Elgin Orsul, is set with a tiny astral topaz.

- **Clear Mind** When you wear this ring, you can increase your maximum stress by +8.

#### Book of Sermons

- Item (Small)
- Common

A cheap but illustrated book of inspiring sermons.

- **Sermon** During camp, you can attempt to read a sermon from the book. If you successfully _Tell a Story_, you heal an additional +1 Stress.

#### Greenleaf Tea

- Item (Small)
- Common

A packet of halfling tea leaves. One packet contains enough leaves for five separate brews.

- **Delicious Tea** If you successfully _Brew Drinks_ using one charge of tea leaves, each person who takes a drink can heal an additional +1 Stress.

## Variant Dials

_Stress & Afflictions_ is a flexible game mechanic that can be adjusted to suit a variety of settings and gameplay styles. If you want to customize the experience for your game, consider using some of these variant dials.

### A. One Snap

If you want to make afflictions a little rarer in your game—or prevent rapid escalation once a character reaches 50% stress—consider this _One Snap_ variant.

The first time you gain 50% or more Stress after a long rest, you snap and develop a mental Affliction. You can only snap once per long rest, though you still risk hitting your breaking point if you reach 100% Stress.

### B. Insanity Zones

You may want to use _Stress & Afflictions_ for just a short time in your campaign—to add theming to a particular region or adventuring site, for example. You can achieve this with _insanity zones_.

#### Creating an Insanity Zone

Stress is only gained in certain areas—_insanity zones_. Outside of these zones, characters don't gain stress—though they still suffer the effect of any lasting afflictions.

An insanity zone can be anything—a room, a dungeon, a kingdom, etc—so add them to your game as best suits your setting. Use them to add memorable features to your dungeons and adventure hubs.

Chansi and Viridian approach the _Tomb of Eldritch Horror_, an ancient dungeon corrupted by aberrant powers. The tomb is an _insanity zone_—within its walls, players risk gaining stress.

#### Leaving an Insanity Zone

If you leave an insanity zone, your stress and afflictions remain until you complete a long rest (or perform another form of recovery action, such as spending hit dice or acquiring consumables).

### C. Temporary Virtues

Some afflictions—such as Powerful and Focused—can be a benefit to your character. With this _Temporary Virtues_ variant, these effects become short-lived.

If you develop a beneficial affliction, it is automatically cured without cost at the end of your next long rest.

# Short Rest

Adventurers need to rest at some point, if only to catch their breath between action, treat wounds, and prepare for upcoming dangers.

This chapter defines the short rest period, some basic activities you might undertake while resting, and how to set up camp for an overnight rest.

## Taking a Short Rest

A short rest is a period of downtime, at least 1 hour long, in which characters sit down to perform a few basic tasks—such as eating, drinking, and treating wounds.

During a short rest you can spend hit dice, bind your injuries, and consume some essential supplies—but anything more intensive will require you to settle down and set up camp for a longer stay.

- DM:Your blade slices through the dire wolf. With a howl, the other wolves flee into the dark forest.
- Valiant:That was a close one. You ok, Viridian?
- Viridian:Took a few bad hits there. We should take a rest soon so I can heal up before we reach _Blightmere_.
- Clanda:Much as it pains me to say, the bard's right—I need to bandage up this bite wound.
- Valiant:Alright, we still have sunlight to burn. Let's find a safe spot to rest in for an hour.

### Basic Activities

During a short rest, whilst you're catching your breath, you can perform some _basic_ activities—such as the example tasks listed here. Complicated or prolonged tasks may require you to set up camp first.

#### Recover Hit Points

Spend your hit dice to recover some lost hit points. If the _Bloodied_ condition is in effect and you have lost half of your hit points, you will need to use a first-aid kit—or similar medical supplies—to spend any hit dice.

#### Regain Class/Racial Features

Some classes and races regain powers after a short rest is completed—monk ki, warlock spell slots, dragonborn breath weapon, etc. Check your character sheet to see which features you recover.

#### Eat & Drink

If _Survival Conditions_ are in effect, you can use this time to satiate your hunger or thirst.

In addition, if you are suffering from exhaustion caused by one or more of your surival conditions, you can remove it if that condition has sufficiently improved.

#### Change Inventory Quickslots

If the _Quickdraw_ inventory rules are in effect, you can change your three selected quickdraw items.

#### Treat Wounds

If you are suffering from any _lingering wounds_, you can treat them if you have sufficient first-aid resources.

#### Research/Investigate

You spend your time researching, reading, or investigating something within reach—such as an encrypted book, an unfamiliar insect, a strangely carved monolith, or an unidentified magic item.

## Setting Up Camp

If you decide to rest for a prolonged period of time—or need to perform some complicated tasks—it's time to set up camp. Find a secure site, start a campfire, pitch your tents, and secure any animals, vehicles, or cargo.

There are five basic steps to follow when trying to set up camp:

1. **Make Camp:** Make _Camping_ checks to see how well you set up camp—the more successes you have, the nicer your camp site is.
2. **Nominate the Lookout:** The lookout is in charge of camp defense, keeping watch for any threats.
3. **Perform Camp Activities:** Each party member (who is not on lookout duty) can perform one primary camp-related activity in addition to any other basic short rest activities.
4. **Sleep:** Try to get some rest for a few hours.
5. **Pack Up:** Pack up camp and prepare to move on.

### 1. Making Camp

To make camp, each party member must roll a _Camping_ check—a Strength/Intelligence/Wisdom (Survival) ability check—against a target DC (see the _Camping DC_ table) as they each try to help set up the campsite.

The more successes the party has, the more thoroughly they prepare the final campsite—making it easier to defend, rest, and perform other camp activities.

#### Camping Check DC

|DC|Description|
|---|---|
|10|Safe, dry land is easy to find / the weather is clear.|
|15|A campsite requires effort to find / there's bad weather—rain, light snow, heavy fog, etc.|
|20|It's hard to find a safe campsite / the weather is terrible—heavy rain, a fierce storm, a howling wind.|

#### Camping Results

|Failures|Description|
|---|---|
|0|A perfect campsite. Activity checks are DC 5.|
|1|A decent campsite with one glaring flaw. Activity checks are DC 10.|
|2 or more|A shoddy campsite just barely fit for purpose. Activity checks are DC 15.|

#### Camping Equipment

It's hard to set up camp if you're relying on nature alone to provide you with shelter and comfort. If you don't have any appropriate camping equipment—such as a bedroll or tent—roll your _Camping_ check with disadvantage.

Some equipment, such as a two-person tent, may count as camping gear for multiple people—if they're willing to share.

The four adventurers start to set up camp. With clear skies and a sheltered forest, the camping DC is only 10. Between them, they have two bedrolls and a two-person tent—enough camping gear for all four.

Valiant rolls 13, Chansi 17, Viridian 11, and Clanda 7. The camp is prepared with one setback—a weak campfire. Any camp activities will have a base DC 10.

#### Variant: Alternate Skills

If you want to support skills other than _Survival_ when making camp, consider this _Alternate Skills_ variant.

Depending on your character and background, you may use another skill instead of Survival—if appropriate—when making your Camping check. For example:

- **Athletics:** You help by moving something heavy to clear space for the camp.
- **Animal Handling:** You help by checking the site isn't in the territory of any dangerous, wild animals.
- **Nature:** You help by finding good wood—and other natural fuel—for the campfire.
- **Religion:** You help by channeling divine power from your deity to bless the campsite.

At least one _Camping_ check must be made using the Survival skill, and any alternate skills can only be used by one party member—so choose who rolls which skill.

### 2. The Lookout

It's a big risk to set up camp without appointing someone to watch out for any would-be intruders. A lookout is in charge of camp security and keeps an eye out for potential threats.

If you are the lookout, roll an Intelligence (Survival) check to see how well you secure the camp against potential dangers. If you have any tools, equipment, or magic that might help—traps, bells, the _Alarm_ spell—you may roll your check with advantage.

**Success:** You noted some weak spots in the camp's defense and secured them.

**Failure:** You made a bad job of securing the camp. You have disadvantage on perception checks against any would-be intruders while camping.

- Clanda:I'll take lookout tonight—I owe Viridian one.
- DM:You all made a decent camp site, so make a lookout check against DC 10 to set the defenses.
- Clanda:I'll set a few _Alarm_ spells around the perimeter, that should help.
- DM:It does—make your roll with advantage.
- Clanda:Simple... (rolls 8 and 17) ...see—nothing's getting past me tonight.

#### Focus

Being on lookout takes a good deal of focus. If you are on lookout, you can't join in with any camp activities besides eating, drinking, and sleeping.

### 3. Camp Activities

While camping, you can perform one primary activity (in addition to the normal basic activities) before you sleep. Below are listed some example activities—if an activity is not covered here, discuss it with your DM.

- Cook food
- Brew drinks
- Play music
- Tell a story

- Repair an item
- Craft an item
- Play a game
- Relax in solitude

#### Cook Food

If you know how to cook and have the right supplies, you can prepare a meal for the group. This requires use of a campfire and cooking tools. Expend one use of your cooking supplies to attempt one of the following actions:

- **Create rations:** You slow-cook and preserve some fresh ingredients—usually meat or grains—to create 1d4 + 1 new, basic food rations that can be preserved.
- **Stretch rations:** You thin out some basic rations into a simple meal, feeding two people for each ration you cook. If cooked successfully, everyone who eats gains 1d4 + 1 hit points (max. once per day).
- **Cook a hot meal:** You cook a hot meal for everyone, using one ration—or ration substitute—per person. If cooked successfully, everyone who eats the hot meal regains 1 spent hit die (max. once per day).

Before you serve the meal, roll a Wisdom (Survival) check to see how well you prepared everything. Meals spoil after an hour, losing any restorative properties.

**Success:** The meal is well made.

**Failure:** You spoiled the meal and wasted the ingredients—no one can eat your cooking.

#### Brew Drinks

If you know how to brew drinks and have the right supplies, you can prepare some for the group. This requires a campfire and brewer's kit. Expend one use of your brewing supplies to try one of the following actions:

- **Create rations:** You distill some impure water overnight to create 1d4 + 1 new, drinkable rations.
- **Brew a balm:** With a few herbs you turn some basic water rations into a delicious, soothing drink—one ration per two drinks. Everyone who drinks a fresh balm gains 1d4 + 1 hit points (max. once per day).
- **Brew a restorative:** You turn some basic water rations into a tasty, hot drink using one ration per drink. Everyone who drinks a fresh restorative regains 1 spent hit die (max. once per day).

Before you serve the drinks, roll a Wisdom (Survival) check to see how well you prepared everything. Your brews lose their restorative properties after an hour.

**Success:** The drinks are well made.

**Failure:** You spoiled the brew and wasted the ingredients—no one can stomach your drinks.

#### Regaining Hit Dice

Some campsite activities can allow you to regain expended hit dice. These activities stack with each other—if you eat a hot meal, drink a restorative, and get a good nights sleep, you can regain 3 expended hit dice in total.

#### Play Music

If you know how to play an instrument, you can attempt to play some music for the group. Roll a Dexterity (Performance) check to see how well you play.

**Success:** You perform well and inspire one of your allies. Choose a party member other than yourself or the lookout—that character gains a point of inspiration.

**Failure:** You made an embarrassing mistake.

#### Tell a Story

People like to hear a good story. If you are proficient in Arcana, History, or Religion—or are carrying an interesting book—you can attempt to tell a captivating story to the group. Roll a Charisma (Performance) check.

**Success:** Your story is well told and inspires an ally. Choose a party member other than yourself or the lookout—that character gains a point of inspiration.

**Failure:** You made an embarrassing mistake.

#### Repair an Item

If you're proficient with certain tools, you may perform basic repairs on damaged equipment—sharpening a blunt sword, sewing up a torn robe, hammering out some dented armor. You can try to remove one notch from an item with a successful Intelligence (Tool) check.

**Success:** You successfully remove one notch.

**Failure:** You were unable to make the repairs.

#### Craft an Item

You can spend time crafting simple items—bandages, salves, arrows—if you have the right materials and appropriate crafting tools. Roll the appropriate check for your specific craft.

**Success:** You successfully craft your item.

**Failure:** You were unable to craft the item.

#### Play a Game

If you have a gaming set and know the rules, you can play a game to unwind. Anyone can join in—so long as they're not occupied with another activity—but at least one person playing must be proficient in the rules.

Everyone who plays can roll an Intelligence (Game) ability check—the highest roll wins.

**Winner:** You feel inspired—gain a point of inspiration.

**Loser:** You lost the game.

#### Relax in Solitude

If you prefer to spend some time alone—reading a book, meditating, painting—you can do so. Roll a Wisdom ability check to see if you are able to unwind.

**Success:** You feel inspired by your seclusion—gain a point of inspiration.

**Failure:** You couldn't relax as something—or someone—was irritating you too much.

- DM:Your campsite is reasonably prepared (one failure)—activities will be DC 10. What do you each do before sleep?
- Clanda:Looks like I'm on lookout tonight, so I'll start setting few _Alarm_ spells around the perimeter. If you set them off again, Viridian, I'm going to _burn_ you.
- Chansi:I'll cook up a hot meal—we should eat this rabbit meat before it spoils. Should be enough for all four of us, and easy to make a stew (rolls 17).
- DM:Soon you have a bubbling pot of hot stew going, Chansi. It smells delicious, and everyone regains one spent hit die.
- Viridian:Great, I'm starving. I'll get my lute out, play a little background music for us (rolls 11).
- DM:Your songs are a fine accompaniment to the food, Viridian—who do you inspire?
- Viridian:How about Clanda? She could do with some inspiration.
- Clanda:Thanks, but I'm too busy being on lookout to listen to your amateur fumblings.
- Viridian:_Fine_, witch. I play one of Chansi's favorites while she cooks; she gains inspiration.
- Chansi:Play _The Wizard's Staff_, I love that song.
- Valiant:Meanwhile, I'll make a few bandages from that old shirt—we're running low on supplies in the healer's kit (rolls 18).
- DM:You tear the shirt into three usable bandages.

### 4. Getting Some Sleep

Sometimes the best way to clear your mind is to shut it down for a while—rest is often the best medicine.

When you attempt to sleep, make a sleeping check (Constitution saving throw) against the _Camping Activity DC_—if you are sleeping in a bedroll or tent, you can make the roll with advantage.

**Success:** Your sleep was undisturbed. Regain 1 spent hit die (max. once per day).

**Failure:** You couldn't sleep well, waking up tired.

After their activities, the four adventurers make sleeping checks against the camping activity DC (10). As each party member has a bedroll or tent, they make their roll with advantage.

Valiant, Chansi, and Viridian each roll above 10—they sleep undisturbed and, once awake, regain 1 expended hit die.

Clanda, however, rolls only a 7—she has a frustrating, restless night half-awake in the forest.

#### Trance

Some races don't sleep as others do—instead, they fall into a meditative state known as a _Trance_. In this state, your character is semi-conscious and only partially-aware of their surroundings.

While you are in a trance, you have disadvantage on all Perception rolls. You may, however, roll your sleeping checks as normal.

#### Wearing Armor

Armor—while great for defense—does not make for comfortable sleeping attire. If you choose to keep your armor on while you sleep, you must roll your sleeping check with disadvantage.

#### The Lookout

While the lookout is on active guard duty, they can still make a sleeping check—simply assume that they find some time to have a quick nap whilst the other party members are still awake.

The lookout rolls their sleeping check with disadvantage, however—it's hard to feel completely refreshed after a night on watch.

### 5. Packing Up

When you decide to move on, it's time to pack up camp—put out your campfire, strap on your gear, and get back to the adventure. This may take a little time, depending on the size and permanency of your camp.

## Ambushed!

A warm campfire and the smell of delicious, hot food can attract attention out in the dark wilds—from cruel bandits, to hungry bears, to bloodthirsty cultists. If you let your guard down, you might find both your sleep and your life cut surprisingly short.

If an intruder approaches, the lookout rolls a Wisdom (Perception) check against the intruder's Stealth:

**Success:** The lookout is able to detect the intruders and, if they choose to, rouse the party with enough time for people to don light armor.

**Failure:** The lookout—and the rest of the party—are caught off-guard and surprised.

- DM:Valiant, Chansi, and Viridian are asleep. The forest is silent around you, Clanda, as you stand guard for the night. Silent, except...
- Clanda:Except...(rolls 18)?
- DM:Except you hear a deep, low growl and the sound of something large pushing through the woods. A bear, perhaps. And it's coming right for you.
- Clanda:Damn it, Chansi, I knew that stew would attract attention. I shake everyone awake, _fast_.

### False Alerts

Out in the dark, it's easy to worry about every shadowed movement and every distant noise—a cracked twig, a far-off howl, a whisper on the wind.

Occasionally, the DM may ask the lookout to make a Wisdom (Perception) roll to detect a false alarm:

**Success:** The lookout realizes that it's just a false alarm and doesn't rouse the party.

**Failure:** The lookout thinks danger approaches and wakes the party unnecessarily. Their sleep is disturbed for the rest of the night.

- DM:As you stand watch for the night, Viridian, you hear a noise in the distance. For a moment, it sounds like laughter. Roll perception.
- Viridian:Eugh, these spooky woods...(rolls 8).
- DM:The laughter grows louder. What do you do?
- Viridian:Uuuuh I wake everyone up of course—I'm not fighting this thing alone.
- DM:You shake everyone awake in a hurry. After a tense minute, Clanda realizes what the sound is—it's just a northern barred owl calling out in the night, nothing more.
- Clanda:Are you _kidding me_, Viridian.
- Viridian:Uh... whoops. Sorry everyone, false alarm. We don't get many owls in the city, see.

## Useful Magic Spells

Magic can be a great help when travelling, providing valuable light, heat, and supplies when needed most.

Below are some spells that may prove useful during your time in camp and some of their potential benefits:

#### Alarm

This spell grants the lookout advantage on any perception checks made to detect intruders.

#### Create Bonfire

This spell can be used to generate 1 automatic success when setting up camp, assuming there is flammable material around with which to build a long-term fire.

#### Create Food & Water

One use of this spell can heal 3 hunger and 3 thirst from up to 15 creatures. As a magical consumable, a creature gains this benefit only once per day.

#### Create or Destroy Water

One use of this spell can fill up to 5 waterskins (a total of 25 water rations). For each spell slot above 1st-level, you can fill another 5 waterskins.

#### Goodberry

A goodberry heals 1 hit point and 1 hunger when eaten. As a magical consumable, a creature gains this benefit only once per day.

#### Heroes' Feast

One use of this spell can heal 6 hunger and 6 thirst from up to 12 creatures. As a magical consumable, a creature gains this benefit only once per day.

#### Leomund's Tiny Hut

When used to protect the camp, this spell grants the lookout an automatic success on their activity checks in addition to its other benefits.

#### Mordenkainen's Faithful Hound

The hound grants you advantage on any perception checks made to detect intruders.

## Variant: Conditions

If you are using the _Survival Conditions_ rules, some of these camping activities can provide additional benefits and improve certain character conditions:

- **Eating:** If you eat a hot meal, you heal 2 hunger.
- **Drinking:** If you drink a restorative, you heal 2 thirst.
- **Sleeping:** If you sleep undisturbed, you heal 3 fatigue.

Viridian eats a portion of a hot meal cooked by Chansi. He regains one spent hit die _and_ heals 2 hunger.

## Variant: Stress

The adventuring life is a stressful business, but a little downtime around a roaring fire can help you to unwind.

If you are using the _Stress_ rules, camp activities can affect your Stress levels. When you make a camping activity check, the following also applies to your result:

- **Success:** You heal a minor amount of Stress.
- **Failure:** You gain a minor amount of Stress.

Valiant tries to create some bandages from an old shirt. He rolls 18—a success. He gains 3 bandages _and_ heals a minor amount of Stress.

Some camp activities—such as those listed below—also gain additional Stress-related effects.

#### Cook Food / Brew Drinks

If you successfully cook a meal (stretched rations / hot meal) or brew some drinks (balm / restorative), you heal a minor amount of Stress from everyone you serve.

#### Be the Lookout

If you successfully secure the camp, you heal a minor amount of Stress from everyone. If you fail, however, everyone instead gains a minor amount of Stress.

In addition, if an intruder slips past your guard during the night, you gain a moderate amount of Stress.

#### Play Music / Tell a Story

If you perform well, you heal a minor amount of Stress from everyone that is listening to you perform.

#### Play a Game

If you win a game, you heal a moderate amount of Stress. If you lose (or tie), you heal a minor amount.

#### Sleeping

If you get some undisturbed sleep, you heal a major amount of Stress. If your sleep is restless, broken, or interrupted by an intruder, you instead gain a moderate amount of Stress.

# Long Rest

Eventually, everyone wants to come home—home is where the heart is. A place to put your feet up, reflect on your recent adventures, and prepare for adventures yet to come.

## Taking a Long Rest

#### Sanctuary

To begin a long rest, you must be in a sanctuary of some kind—such as a village, town, or city. Sleeping in the wilds isn't safe, comfortable, or restful enough for a full recovery.

Viridian, Valiant, and Clanda finally reach the gates of Darrowmore. They're looking forward to a well-earned rest and plan to stay in town for one week.

Between them, they carry 45 gp of recently-recovered treasure from the Elsewood—this rewards each of them with 150 XP (450 XP total).

They all choose a _comfortable_ lifestyle for the week ahead while pursuing their own activities in town: Valiant does some charity work at his church, Clanda begins training for her next level up, and Viridian tries to sell a sort-of-cursed magic item.

#### Variant: Stress

If you are using the _Stress_ rules, completing a long rest automatically resets your Stress level to 0. You may also pay gold to make an _Affliction Removal_ check if you have not already rolled one this week