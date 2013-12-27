flit - not the real name
====
goal: build a game, keep it simple, anywhere this document strays into fancy, consider cutting it down to bare hints of the fancy idea

unnamed defender style tower defense game

side scrolling mobile game, with two opposing play options - attack and defend. AI for both sides for single player? Forced multiplayer? Some mix? 

long narrow corridors for levels, all in 3d but played as a 2d side on shooter, move forward and up/down, not back?. 3d gives depth and allows for fun 3d SFX, easier lighting(I think), opens possibility to give overhead opening shot, and other such niceties.  


defending team controls deployment of defense measures, ground-to-air missiles/lasers/walls/ship eating plants, what have you. everything is on the table, the wackier the better, but lets keep it simple to start. 
depending on how things evolve, can imagine selling ability to buy upgraded defense measures and so on. so keep that in mind when thinking about tech trees(?) etc. Primary mechanic is setting up traps and clever area designs to defeat attackers, then running those without running out of resources, money, or unobatainium, or fuel, something to be limited and recoverable in some way. 

attacking team runs squad of ships to attack environment - planet denizens I suppose. upgradable attacks, bombs, lasers, support ships for regenerating lost ships faster, etc. primary mechanic is to destroy everything in sight while capturing some number of aliens(bumping into wander tiny people ala defender or hover over and suck up UFO style, or other?) - meet your quota - for probing, spying, etc. not sure that will ever be expanded on, but might make for good flavor text. 

fixed set of environments, but many options for deploying defenses into those environments. 

environment considerations, potential specs:
size: 10000 units long, some reasonable but fairly shallow depth, few hundred high? (unity units) this will require experimentation of course
scale: fixed between 'stages'? that is, buildings/features appear aproximately the same distance from the camera in stage 1 as in stage 2 - i think this makes sense but need to see how it looks. 
number: 10 environments to start?
set pieces: underground city/base, above ground moon, above ground earthlike, above ground foresty etc
backdrops: should we have static 2d backdrops or generated/rendered backdrops? how alive are they?
item placement: user must be able to place models in the scene - so some kind of grid system might make sense for placing items and having a 'snap-to' type feature. 

attacker:(needs better name)
resources: shields, ammo, ship mix(gunner, bomber, supplier), money, fuel
upgradables: sheilds, ammo, ships, travel distance
limitations: farther from home, less resources for making ammo, shields, fuel, assuming home worlds are unique
can only carry so much. again, this may not make it in game, but gives flavor for reasons resources scarce at higher levels(higher stages?). 

defender:
resources: world shield?, money, fuel, population(aka army size)
upgradables: sheilds, buildings, cannons, other defenses
limitations: money drained by building new buildings/cannons, money trickles in from 'taxes' or some such, no explanation necessary, resources gathered from assaulting forces upon destruction
motivation: keep city alive to get more upgrades, to handle bigger assaults, to get more resources from killing them

multiplayer: gameplay for the attacker is fairly obvious, fly about and shoot stuff, maybe deploy a decoy or something or change formations, but for defender, seems much more complex. need to simplify. more importantly, how does it work? defender and attacker can't both play realtime and expect defender to do anything reasonable can they? start with default layout then I guess. user then spends time editing world in realtime. some way to make mass edits - 'upgrade all these'. simples possible version might just have the defender acting like the old atari game - pointing the turrets and firing at the attacker. then it's just a trajectory/speed/ammo type choice rather than a whole level building exercise. (idea that maybe doesn't fit here, or mabye is the real idea here afterall - offline play for defender, maybe even every player, is to customize home world, which eventually gets attacked, at which time, user can't be attacker b/c has to focus on defending home world. sounds fun. winnings from attacking(piracy?) is used to upgrade home world. each user can customize home world in various ways to make it their own, sounds good). creates a nice offline/online mechanic, reasons to do both, penalty for getting attacked at home might be weaker resources for piracy - can't travel as far, as long, with as good ammo/shields etc.  





