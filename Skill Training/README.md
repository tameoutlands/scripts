#### Skills
* [Animal Taming](#animal-taming)
* [Tailoring](#tailoring)

#### Animal Taming
General information: This script is designed to be 100% afk, from 50-120.  For more information about what to tame, please see https://www.tameoutlands.com/.

Things you require for this to work

1) A dagger
2) Bandages
3) A pet that you can use as a tank, the script advices to use Rock Guar until 72.5, Scarab until 105 then a Sand Roach to finish, but you are welcome to use what ever you want.
4) You need to set a script variable in `scripts > options` called `tank` and select your tanking pet, this will need to be manually changed when you change tanks at the different levels.

Things this script performs actions that you might be confused by; some of which are explained below.

1) This will attempt to use a dagger on animals, this is by design so do not remove any parts of this.
2) This script will try to transfer pets, but this is purely to establish a successful tame, and at no point does this actually target any mobile to transfer to, this cancels the target cursor directly after.
3) This scipt does not release your tames to kill them, importantly it does this for the following reasons.
  - Killing your tamed pets is much faster due to their reduced hp.
  - Killing your tamed pets yields no experience towards codexes, mastery chains or aspect.
  - Killing your tamed pets yields no opportunity gain a passive gain, which would be VERY bad if we did.
4) This script has some baked in pets to tame at all the taming break points, you are free to add additional pets in at each section but i would recommend commenting out `\\` unused pets that you wont be taming, this will help to speed up the taming process.

#### Tailoring
General information: This script is designed to grab leather from a store, restock sewing kits from your shelf, and stock your shelf up with any items deemed worthy of being shelved, like armour suits, ship boarding ropes.  It will automatically recycle any normal quality items including the tailor repair kits

This you require for this to work

1) A shelf, create a script variable in `scripts > options` called `shelf` and target your shelf before pressing play.
2) You shelf loadout should be just a sewing kit, or 10, what ever floats your boat.
3) A container near your shelf with regular leather in, you need to create a script variable in `script > options` called `leather` and target this container.
4) You must create a counter in Razor called `leather`, this can be done by going to `Display/Counters` and adding a leather counter.
5) You must also create a restock agent, preferably `restock-1` that has your `backpack` set as its hotbag and `leather` added to the agent.

This creates the following, although you can change it if you wish.
  - 50-65   : Leather Gorget
  - 65-70   : Leather Gloves
  - 70-75   : Leather Cap
  - 75-80   : Leather Arms
  - 80-85   : Leather Legs
  - 85-90   : Leather Chest
  - 90-95   : Boarding Rope
  - 95-100  : Studded Arms
  - 100-120 : Tailor Repair Kit
