Modest Mod v0.42.06-1
An indispensable mod for Dwarf Fortress v0.42

By Igfig
With Thanks to CryptoCactus
Updated for 0.40+ by Button

The Modest Mod is a collection of vital bugfixes and tweaks that everyone should be able to use comfortably and without reservation. This mod doesn't add anything new. It doesn't do anything controversial. It's just like vanilla DF, but a little better. French vanilla.

Please direct all questions, suggestions, and comments to the (NEW) Modest Mod thread at http://www.bay12forums.com/smf/index.php?topic=148265

The original Modest Mod thread can be found at
http://www.bay12forums.com/smf/index.php?topic=105871.0

INSTALLATION

1. Back up your existing 'raw' folder.
2. Unzip this archive into your Dwarf Fortress directory.
3. Say yes when it asks if you want to replace files.

COMPATIBILITY

Modest Mod should be compatible with many mods and some texture packs. 

Even for mods which are incompatible, it's pretty easy to merge things manually. All of my changes are clearly marked in the raw files with the phrase "Modest Mod". We recommend using WinMerge (http://winmerge.org)

In addition, there exist alternate versions of the Modest Mod intended specifically for use with specific tilesets. Be sure to install Modest Mod AFTER installing the graphics pack of your choice.

MODULES

Modest Modules involve changes that, while popular, are a little too ambitious for the core mod. 

Modules included in release 0.42.06-1 are:
	* Accelerated - Significantly reduces the number of materials present in the game, increasing performance.
	* Everything Is Tameable - With the exception of the civilized races, you can tame anything. Not compatible with Pedestals.
	* Everything Is Tameable for Accelerated - A version of the Everything Is Tameable module which is compatible with the Accelerated module. Install AFTER Accelerated. Not compatible with Pedestals.
	* Modest Bodies - Modifies body definitions to add joints between "upper" and "lower" limbs, and renames some body parts - e.g. "upper leg" to "thigh."
	* Pedestals - Allows you to mount & display crafts, particularly artifacts. Not compatible with Everything Is Tameable.
	* Pedestals for Accelerated - A version of the Pedestals module which is compatible with the Accelerated module. Install AFTER Accelerated. Not compatible with Everything Is Tameable.
	* Tooltips - Provides descriptions & important information for most Fortress Mode reactions. Likely to be helpful for newbies.
	* Tooltips for Accelerated - A version of the Tooltips module which is compatible with the Accelerated module. Install AFTER Accelerated.
	
Unless otherwise noted, Modest Modules are compatible with each other and can be installed in any order.

MODULE INSTALLATION

1. Install the Modest Mod as directed above.
2. Check your Dwarf Fortress directory for the folder named "Modest Modules." Open this folder.
3. Unzip the modules you want to install into your Dwarf Fortress directory, as you did with the Modest Mod.
4. Say yes when it asks if you want to replace files.

CHANGELOG

v.42.06-1
	* Reverted plump helmets to a plant instead of a growth again, as bags are no longer auto-emptied.
	* Fixed the MM grate creation reactions to use masonry instead of mechanics
	* Brought the new reptiles in line with other creatures (giant maxages, child names, biting with teeth, etc.)
	* Fixed long yams being named lesser yams
	* Removed SPECIFIC_FOOD from panda men and red panda men.
	* Adjusted the names on giant one-humped camel and giant two-humped camel milk and cheese
	* Fixed bug #9621 (the plural of "left foot" is no longer "right feet" for certain bipedal creatures)
	* Fixed bug #9620 (kobolds have an invalid agility range)
	* Renamed baby toad-variants to "toadlets" instead of "tadpoles"
	* Fixed new creatures with teeth, and creatures with new teeth, so that they use their teeth to bite
	* Brought giant foxes & giant wolverines in line with other large carnivorans (large predator, trainable)

v.42.04-1a
	* Fixed the specific mill to paste reactions, which were consuming seeds without producing paste
	* Made talc usable in magma-safe reactions
	* Added more reactions for non-magma-safe stone items
	* Added "rock" to the names of the non-/magma-safe item reactions, for clarity from the manager interface
	* Added mass-brewing reaction for mead

v.42.04-1
	* Merged the Modest Mod onto the 0.42.04 raws
	Creatures
		New in 0.42.04
			* Adjusted the max ages for the new giant variations of short-lived creatures, so that they live at least 10 years.
			* Gave giant & animal person variations of non-biting vermin the ability to bite, with the exception of flies, butterflies and moths.
			* Made male mosquito variations able to bite, but not to suck blood.
		Attacks
			* Made animal men without teeth prefer not to bite, in line with animal people with teeth. Exception: animal people with venomous bites.
			* Made hooved animal men prefer not to kick, in line with animal people without hooves.
			* Made animal men with goring, headbutt, or tail slap attacks prefer not to use them, in line with other animal people's non-venomous natural attacks.
			* Removed the "snatch" attack from the animal person variations of various flying birds, and added their talons to their kicks instead.
			* Removed kick attacks from penguin men entirely, because their legs are stubby (and adorable).
			* Made ostriches', cassowaries', and emus' kicks edged attacks.
			* Made giant variations of legged vermin capable of kicking.
			* Gave grey parrots & their variations talons and the appropriate attacks.
			* Made swans', ducks' and geese's bites no longer edged attacks.
			* Replaced domestic sheep rams' gore attack with a headbutt attack.
			* Gave domestic goats, mountain goats, gazelles, muskoxen, ibexes, male impalas & their variations a headbutt attack.
			* Gave mountain goats, gazelles, muskoxen, male elk, ibexes, male impalas & their variations a horn gore attack.
			* Gave desert tortoises & their variations the ability to kick.
			* Gave gila monsters, lizards & their variations the ability to scratch
			* Made sea lampreys prefer not to tail slap.
			* Made hippo & giant hippo bites able to latch
			* Made hippos, elephants, rhinos & their variations prefer not to kick
			* Gave stag men the ability to attack with their antlers
			* Gave rhinos, giraffes & their variations the ability to bite
			* Made giant tortoises' & their variations' bites sharp
		Other:
			* Removed leather & parchment from mussels and oysters.
			* Made toads, lice, green tree frogs & their variations carnivores.
			* Made worms & worm men appear underground as well as aboveground.
			* Made vermin birds that are shy in real life PET_EXOTICs rather than PETs.
			* Gave crows and foxes their proper adjectives, in line with the changes to creature_domestic in 0.42.04.
			* Restored flight to non-giant mantises.
			* Gave gazelles, male impalas & their variations horns.
			* Stopped flies from spawning in pools & their variations from spawning in lakes, as they are not water vermin.
			* Restored Giant Desert Scorpions
			* Reverted all scorpions & variations to giving live birth.
			* Added eggs to lizards, toads, a number of insects, & their variations.
	Plants
		* Added oat beer
		* Reverted tree nuts to vanilla now that the seed-picking bug has been fixed.
		* Converted plump helmets to fruit for adventure mode picking again, now that the bagged growth bug has been fixed.
	Reactions
		* Fixed hull seeds reaction to use PROCESSPLANTS skill
		* Created specific reactions for brewing and milling
		* Created magma-safety-conscious reactions for common masonry, mechanics & stonecrafting tasks
		* Modified parchment reaction to work with the skin glob format
	Other
		* Made helms a shaped item again

v.40.24-2a
	* Changed fortress mode seed hulling to require plant processing labor
	* Removed eggs from sea serpents
	* Gave olm men their legs back

v.40.24-2
	* Added edible (cooked) baggable growths to taro, lesser yam, purple yam, and white yam, as they had unobtainable seeds.
	* Changed plump helmets back to plants, to keep them accessible to new players. They are no longer pickable in adventure mode.
	* Doubled the metal reagents and yield of the pig iron and steel smelting reactions, effectively halving the flux and fuel requirements.
	* Re-enabled purring maggots (and thus "dwarven" milk and cheese) for dwarven and goblin civilizations.
	* Adjusted cavern populations to a uniform double of the vanilla amounts, to compensate for forgotten beasts slaughtering them.

FEATURES
	Announcements
		* Births do not cause the game to pause and recenter.
		* Babies born in combat will be noted in the combat log.
		* Citizen deaths cause the game to pause and recenter.
	Creatures (General)
		* Fear of commitment no longer causes non-sapient creatures to be sterile. (They can still be asexual or gay.)
		* Butchered creatures produce skin - and thus leather - in proportion to their size.
		* Scales are tannable into leather.
		* Chitin is usable as though it were shell.
		* All creatures with real life counterparts, and their giant variations, are tamable in fortress mode. 
		* All tameable creatures have CHILDhoods, and so can be fully tamed.
		* Giant variations of carnivorous creatures have remembered that they are LARGE_PREDATORs. So have blind cave bears.
		* Giant variations on vermin that can only bite have learned to use other attacks. Most notably, giant spiders can kick.
		* Giant creatures with short-lived base creatures live for a minimum of 10 years.
		* Animal people become adults at age 12, and live for 60-80 years total.
		* Animal people are not milkable.
		* Animal person variations of grazers no longer need to graze.
		* Creatures without legs use the legless animal person variation.
		* Giant and animal person variations on vermin that spawn in ponds will spawn in lake biomes.
		* Aquatic and amphibious creatures cannot be used as mounts.
		* Aquatic creatures all give live birth, as they cannot claim nest boxes.
		* Unless they're aquatic, insects, gastropods, arachnids, amphibians, most reptiles, and all of their respective variations lay eggs. Also voracious cave crawlers, giant desert scorpions, and hydras.
		* A number of creatures which eat vermin in real life now hunt (or dive hunt) vermin.
		* Giant and animal person variations of vermin hunters no longer hunt vermin.
		* All non-sapient, dog-sized or larger canines and felines can be trained for war or hunting. Also hyenas.
		* Canines and felines smaller than a dog cannot be trained for war, only hunting.
		* Very slow creatures, and creatures that curl up when threatened, can no longer be used as mounts.
		* Elves can use most ruminants as PACK_ANIMALs.
		* Creatures made of inorganic materials will produce a boulder, bar, or wood block when butchered.
		* Animate organic materials will melt or boil in sufficient heat, so undead are not immune to magma.
		* Pain in bones is reduced by 4/5.
		* Feathers heal fairly quickly, up from not healing at all.
		* Horn, hoof, cartilage, hair, facial hair, nails, claws, talons, and ivory have slow healing rates, up from not healing at all.
		* Nerves, brains, and spines heal extremely slowly, up from not healing at all.
	Creatures (Specific)
		* Mantises and their variants can no longer fly.
		* Goblins can ride cave dragons.
		* Elves can ride giant desert scorpions.
		* Reindeer can pull wagons and carry loads.
		* Llamas and elk birds can carry loads.
		* Wild boars have learned how to gore enemies with their tusks.
		* Elephants are tamable in worldgen by non-elves, and can pull wagons and carry loads.
		* Grizzly bears, black bears, panda bears and capybaras are no longer tamable in worldgen by non-elves.
		* Warthogs, chimpanzees, gorillas, muskoxen, orcas, sperm whales, and elephant seals aren't very friendly.
		* Hippos aren't benign either - in fact, they're prone to rage.
		* Giraffes cannot be trained for war or hunting.
		* There are twice as many jabberers in cavern biomes, they live twice as long, and they lay half again as many eggs. This is to compensate for their populations getting wrecked by Forgotten Beasts.
		* There are ten times as many giant cave spiders in cavern biomes. This is to compensate for their populations getting wrecked by Forgotten Beasts.
		* Hedgehogs live for 6-16 years. (I'm friends with the proud daddy of two hedgehogs, and he insists.)
		* Humans, elves and goblins style their hair.
		* Dragons become adults at age 23.
		* Dragons cannot be trained for hunting, because they'll just melt the target and set everything on fire.
		* Hydras become adults at age 10, and can be trained for war or hunting.
		* Sea serpent populations range from 10-20 in biomes they're native to, but still travel alone.
		* Black bears, dingos, and anacondas are not LARGE_PREDATORs.
		* Hungry heads have switched to an all-vermin diet, in accordance with their small size.
		* Giant mantises, giant ticks, giant moon snails, alligators, saltwater crocodiles, giant snapping turtles, giant leeches, giant axolotls, cave crocodiles, giant adders, giant anacondas, and giant pythons are AMBUSHPREDATORs.
		* Magma crabs are tamable.
		* Snowy owls are diurnal.
		* Corrected the grammar & spelling of the peach-faced lovebird and brown recluse spider descriptions, and the magpie, giant magpie, and donkey PREFSTRINGs.
		* Water buffalos can be ridden.
		* Brown recluse spider men & giant brown recluse spiders have webs thick enough to hold non-vermin prey.
		* Giant grasshoppers need to graze.
		* The venoms of bark scorpion men, giant bark scorpions, platypus men, and giant platypuses are properly labeled, and their respective species are properly immune to their own venoms.
		* Giant kangaroo and giant tapir milk are properly labeled.
		* Bark scorpions and platypuses are no longer immune to their variations' venoms.
		* Guineafowl occur naturally in a number of tropical environments.
		* Rabbits don't hibernate in winter.
		* Oysters and mussels produce pearls when cleaned.
		* Pandas, red pandas, and their giant variants have reduced food requirements.
		* Unicorns become adults at 3 years old, but aren't tamable.
		* Moon snails and their variants have fully-defined bodies, allowing moon snail men to not be vegetables.
	Plants (General)
		* Seeds which grow on trees have hulls, and so can be gathered by an herbalist.
		* Nuts and legumes can be hulled to obtain their usable, tasty seeds in both Fortress and Adventure mode.
		* Shrubs with unobtainable seeds (e.g. onions) can be picked whole and processed to bag, like a quarry bush.
		* The process to bag reaction produces 2 seeds per shrub instead of 1, as farmers and herbalists are as likely to pick the growth as they are the whole shrub.
		* Inedible tree seeds disintegrate, reducing clutter and freeing up bags.
		* Separate reactions for milling flour, dye, and sugar from plants.
		* Grains are referred to by their proper names, not as "seeds."
	Plants (Specific)
		* Feather tree eggs are gatherable and edible (cooked).
		* In adventure mode, feather tree eggs are no longer drinkable.
		* Plump helmets can be picked in adventure mode. To accommodate this, they are brewed as fruit in fortress mode.
		* Dwarves will no longer pick strawberry plants whole, nor try to eat them whole.
		* "Flaxseed," "hempseed" and "cottonseed," used as descriptors of derived products, are correctly shortened to a single word each. The exception is for oil-based products made from flaxseed, which is described as "linseed."
		* "Hazelnut" is one word.
		* Cashews, coffee beans, and paradise nuts are edible.
	Miscellaneous
		* A reaction at the kitchen to empty a bucket of water.
		* Three empty reactions, which can be filled in to add new reactions after a world has already been generated.
		* Hair can no longer be used to make hard items. You will no longer find huts made out of hair in adventure mode.
		* Vital administrators can be assigned on an AS_NEEDED basis, instead of being limited to one per fort.

FEATURES REMOVED SINCE 0.34.11

Some fixes from the old Modest Mod were incorporated directly into 0.40.x; they are not listed here. These are features that were not incorporated into 0.40.x, but have been removed from the Modest Mod for other reasons.

	Because they addressed bugs that have been fixed in the vanilla game:
		* Ranged weapon balance changes (the Broken Arrow mod) have been removed.
		* Specific GRAZER values for most creatures have been removed.
		* MOUNT_EXOTIC has been returned to flying creatures.
		* Skill increase modifiers for combat-related skills have been removed.
		* Elves no longer have LOCAL_BANDITRY
		* Goblins and dwarves no longer build human-like fortresses during world generation.
	Because of version differences:
		* Melee weapon balance changes have been removed. It won't be clear what fixes will be appropriate here until more SCIENCE has been done.
		* All binary patch-based fixes have been removed, because they are not available for the new version (AFAIK).
	For inclusion in Modest Modules:
		* Egg-layers once again lay their default numbers of eggs. 
		* Adventure mode crafting has been removed. 
		* Feathers are not usable for decoration.
		* Purring maggots are not present in the first cavern layer/not available to dwarven civilizations.
	Because of bugs in the fix itself:
		* Giant creature age changes have been moved from the GIANT template into the individual creatures, because CV_REPLACE_TAG does not work correctly for numbers.

FOR MOD AUTHORS

The Modest Mod belongs to the Dwarf Fortress community. You are free to remix, build upon, pull from, and otherwise use these raws for any purpose. Attribution is nice, but you don't even have to do that.
		
SPECIAL THANKS

Vintermann, for starting the thread that inspired this mod
Igfig, for doing the majority of the work
Meph, for identifying and addressing a lot of issues
RavingManiac, for the Seasonal Crops mod
Joben, for the Broken Arrow mod
Quietust, for creating a whole bunch of binary patches
Elvang, for compiling them into a single .exe
Ag, for a bunch more binary patches
Urist Da Vinci, Vattic, Kaos, Taverius, Quarterblue, and others I may have forgotten, for good suggestions
Everyone else who's contributed to the thread
MASSIVE THANKS to CryptoCactus for maintaining the Modest Mod during Igfig's absence.
Zarathustra30, for the Tooltips module
And Toady One, of course.