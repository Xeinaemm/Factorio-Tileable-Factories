# Tileable Factories

You can also find it on [Factorio.School](https://www.factorio.school/view/-OBdq3vJ2slIWEDAXEeM), [Factorioprints](https://factorioprints.com/view/-OBdq3vJ2slIWEDAXEeM) and 
[Factorio Codex](https://www.factoriocodex.com/blueprints/44).

<details>
<summary>Changelog</summary>

## v0.54.0
- Added new biolab(3560 SPM) in Lab book allowing daisy chain and one-way belt system.
- Added interstellar ship in the Starter book, for all planets up to the Aquilo.
- Simplified Progress Bar to require only display panel.
- Removed unnecessary combinators and updated requester chests for the most heavily used recipes for continuous production in "large" starter.
- Updated first interstellar ship, so it can survive parking around Fulgora.

## v0.53.1
- Fixed missing inserters in "small" starter.

## v0.53.0
- Redesigned Nauvis "small" starter, and some minor changes and additions to the "large" starter. There is no Spoon: 4:19:49h.
- Added interstellar ship in Starter book, for first voyages.

## v0.52.0
- Added Starter book with early and midgame phase carrying into Space Age under 8h(There is no spoon).
- Cleaned up Smart Mall wire spaghetti and removed bottleneck of input inserter with fixed stack size.
- Reduced size of Asteroid Crusher by 30% and simplified parameters to require only recipe.
- Added UPS-friendly drilling that directly produces molten metal.
- Updated nuclear reactor to be vertically, horizontally, and symmetrically tileable and halved number of roboports.

## v0.51.0
- Added landfill factory in Universal.
- Added parameterized blueprint for Yumako and Jellynut overgrowth soil in Gleba.
- Updated nuclear reactor (2.8 GW) for symmetry and added additional roboports to ensure accessibility in every direction.
- Added beacons for silo and wagon drilling.
- Updated belt throughput tolerance algorithm to treat exceeding upper bound as failure by default.
- Removed unnecessary controlled behavior of Requester chests in Gleba blueprints that provide nutrients for startup.

## v0.50.0
- Added Nuclear Reactor(2.8 GW) in Power.
- Added parameterized blueprint for Yumako and Jellynut artificial soil in Gleba.
- Rebuilt Fusion Reactor(22.5GW) to fix Requester chests that were out of reach of Roboports([Issue 23](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/23))
- Fixed issue with Carbon Fiber factory becoming clogged during significant power fluctuations.

## v0.49.0
- Added universal Silo in Space.
- Updated Quality Switches with missing items.
- Improved universal factory sulfur output in mixed-mode from 390/s to 455/s.
- Unified and parameterized Yumako and Jellynut(960/s) factories into one blueprint. Fixed bug where temporary clog could last few minutes.
- Added missing roboport section in Cargo Landing Pad.
- Added missing pipe in Fusion Reactor(22.5GW).

## v0.48.0
- Added Light/Medium/Heavy Hulls, Thruster and Storage for Spaceships in Space.
- Removed asymmetry of Cargo Bays in Cargo Landing Pad(2400/s).
- Reduced Electromagnetic Science size by additional 5%.
- Rocket fuel(Universal) and Lubricant(Universal) are tileable and can share beacons.
- Requester chests across Gleba blueprints will always trash unrequested items, even if blueprint has self-cleanup option.

## v0.47.0
- Added Cargo Landing Pad(2400/s) in Space.
- Improved ice platform output from 12/s to 18/s.
- Size of Ammonia/Ice subfactories were reduced across Aquilo blueprints.
- Reduced sizes of Fusion Reactor(22.5GW), Electromagnetic Science and Fluoroketone(Cold) by 5-9%.
- Fixed lack of tileability of Fusion power cell factory.
- Parameterized backup generator.
- Fixed wrong underground belt line in Scrap Recycler(120/s)([Issue 22](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/22))

## v0.46.0
- Added LDS Shuffle.
- Adjusted Cryogenic Science to 240/s to align with other science blueprints.
- Reduced sizes of Fusion Reactor(22.5GW), Scrap Recycler(120/s), Lithium Plate, Rocket Fuel(Aquilo) and Production Science by 5-10%.
- Refined Concrete factories is tileable.
- Removed Acid neutralisation from all universal blueprints to make blueprints less confusing.
- All blueprints that use coal liquefaction are tileable with each other and cross-share pipes to initiate auto-start.

## v0.45.1
- Fixed Quality Recycler (asteroid) getting clogged due to incorrect wire color.

## v0.45.0
- Added Module Switches.
- Improved efficiency of Scrap Recycler, Quality Recyclers, and Shredder. They should be able to process at least half of input belt of any configuration.
- Military Science is tileable.
- Fixed clog possibility of Carbon Fiber factory.

## v0.44.0
- Added Chaos Monkey(resiliency tool) in Tools.
- Removed flamethrower and pump factories as Smart Mall serves its purpose.
- Reduced size of Railgun and Fusion Reactor(3.5GW) factories.
- Beacon factory is tileable.
- Removed situation where backup generator could trigger critical and warning alerts at once.
- Fixed clog possibilities of Metallurgic, Lubricant(Universal), Bacteria Cultivation, Sulfur(Gleba), Jelly, Yumako, Agricultural Science factories thanks to Chaos Monkey.

## v0.43.0
- Added Bitter Egg(silo) factory.
- Plastic, Rocket Fuel, Sulfur, Sulfuric Acid, Lubricant, Plates, Steel, Inserter factories across Nauvis, Vulcanus, Fulgora, Gleba, and Space were unified, parameterized, and most became Universal. In total, 18 blueprints were removed.
- Explosive Rocket factory was reduced in half to fit on smaller ships.
- Removed remaining electric poles. Only exceptions are big drill and agricultural tower.
- Reduced book size by 7%.

## v0.42.0
- Unsafe downgrades for belts and inserters became safe switches and were moved to Upgrade & Switch tab.
- Unified inserters and removed belt braiding/weaving techniques.
- Replaced Recyclers with Heating Towers where possible for Gleba blueprints.
- Included only one quarter of solar power plant. 42.5 MW out of 170 MW.
- Removed space science(5/s) space platform.
- Reduced book size by 9%.
- Railgun ammo factory was reduced in half to fit on smaller ships.
- Lots of minor changes.

## v0.41.0
- Added Quality Upcycler for casino ships.
- Removed chunk filters for unwanted products as they now have separate Quality Upcycler and Quality Recycler.

## v0.40.0
- Added Progress bar in tools.
- Added 45 MW backup power plant and 170 MW solar power plant with ratio adjustments for quality.
- Connected internal water intake of Heating tower power plant.

## v0.39.0
- Removed clog from newly introduced Quality Recycler.
- Renamed Quality Enhancer to Quality Upcycler to align it with current terminology.
- Added Storage to Farm Control Panel. By default, request all produced items by Smart Mall, plus allows defining additional ones.
- Removed unnecessary logistic groups created for powering fusion reactor blueprints.
- Updated FAQ and descriptions.

## v0.38.0
- Added Farm Control Panel that allows control of Smart Mall, Quality Upcycler, and Quality Recycler farms at scale.
- Quality Upcycler and Smart Mall farms, connected by green wire, become multi-functional grinder that can be scaled infinitely.
- Added Quality Recycler for casino ships and updated unwanted products to include chunks.
- Scrap Recycler(bot network), Quality Recyclers, and Shredder are same size to fit almost all types of Fulgora islands or ships.
- Ice platform factory is tileable with each other.
- Updated FAQ and descriptions.

## v0.37.0
- Removed substitutes for sulfur, pipes, lubricant, and green circuit.
- Reduced number of belts from 7 to 4 of iron plates for artillery shells
- Unified Metallurgic science with other sciences to 240/s.
- Updated FAQ
  
## v0.36.0
- Removed laser turret and mines factory.
- UPS-optimized.

## v0.35.0
- Added sulfur factory(120/s and 240/s) for Vulcanus.
- Added timer and counter measurement tools.
- Redesigned, compacted, and pushed overlooked factories to their limits.
- Removed poles and gate factories because they can be crafted in smart mall.
- Reorganized books.
- Updated FAQ.

## v0.34.0
- Added artillery shell(60/s), pipes(240/s, 120/s), ice platform(12/s), foundation(36/s), scrap recycler(120/s) factories.
- Removed spear (spaceship) as it no longer serves its purpose and requires redesign.
- Pushed most of designs, including game engine, to their limits.

## v0.33.0
- Added input requirements to every factory and fixed many minor issues.
- Added universal Refined Concrete(240/s) factory.
- Added tools to measure throughput.

## v0.32.0
- Added Smart Malls. Mostly from early to late game and transition to Quality Upcyclers.
- Added new Quality Upcyclers and reduced space of rest by 20-40% thanks to new circuit network changes.
- Reduced space by 15-20% of Iron/Copper/Steel factories for Vulcanus and Space.
- Updated FAQ
- [Tests] Removed redundant combinators

## v0.31.0
- Added silo and wagon drilling, 2640/s and 3840/s, respectively.
- Rebuilt water supply for Plastic and Refined Concrete factories in Vulcanus to accommodate (another) game fluid changes.
- [Tests] Reworked test lab, including testing framework for better maintenance.
- Fixed Fusion Reactor(3.5GW) low power under load ([Issue 16](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/16))
- Added Holmium Ore to unwanted products in Quality Recycler ([Issue 17](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/17))
- Added missing pipe in quantum processor factory ([Issue 18](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/18))
- Many minor changes, such as adding missing power poles, circuit network constraints, or additional inputs/outputs for better blueprint tiling.
  
## v0.30.1
- Added missing pipe connection of fluoroketone (hot) in fluoroketone factory ([Issue 12](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/12))
- Removed clog related to overflow of petroleum gas in Vulcanus fuel factory ([Issue 13](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/13))
- Reduced space of fusion power cell factory by another 10%.

## v0.30.0
- Added multipurpose space platform - Spear.
- Added space deconstructor to remove items from blueprints that can be safely removed in space.
- Increased steel plate factory throughput from 160/s to 240/s. Added Gleba steel plate factory.
- Quality Upcycler stock quantity is limited to legendary items. When buffer is full, all remaining resources will be trashed to maximize resource sharing. ([Issue 4](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/4))
- Fixed fluoroketone (hot) overflow bug in fluoroketone factory. Now factory prioritizes external input of fluoroketone (hot). ([Issue 5](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/5))
- Reduced space of most Aquilo factories by 20-50%. ([Issue 8](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/8))
- Added unsafe downgrade planners for belts, splitters, and inserters. They are unsafe because reverting requires super force build of initial blueprint on placed factory. Never use this against book. For now, not every blueprint can be downgraded because of turbo underground belt length requirements. ([Issue 10](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/10))
- Fixed input belts in space iron, steel, and copper factories that prevented them from being tiled.
- Removed external Substations in Explosive rocket factory.

## v0.29.1
- Fixed misplaced inserters and Requester chest in Foundry Quality Upcycler ([Issue 3](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/3))
- Rebuilt refined concrete (Vulcanus) factory to hit 240/s when problem with steam condensation is fixed ([Issue 118644](https://forums.factorio.com/118644))
- One iron plate input was removed in Space Science.
- Added tileable input belts for Biolab.

## v0.29.0
- Added splitter, bulk inserter, stack inserter, refined concrete (Vulcanus), space platform foundation, and beacon factories.
- Redesigned belt and underground belts to use Vulcanus-specific recipes and also moved them alongside modules to planet-specific books
- Removed "To remove" book.

## v0.28.0
- Added belt and underground belt factories.
- Redesigned and increased robot factory's throughput from 40/s to 80/s. This is 20% better space efficient than using two 40/s.
- Revisited all blueprints and space of most factories was reduced by 5-20%. In many cases, recyclers are more efficient than heating towers. plans also use my belt balancers, which reduce space by 2x-10x compared to Raynquist's Belt Balancers.
- Fusion reactor (22.5GW) operates on normal-quality substations without power losses.
- [Tests] Added description to constant values used in fluid tests. 
  
## v0.27.0
- Added Modules factories (6/s).
- Redesigned Military and Production Science, increased throughput from 80/s to 240/s, and sorted inputs by type. Moved old designs to 'To remove' book. Military Science now requires walls rather than raw materials because otherwise, you would need extra 8 belts of stone.
- Redesigned Agricultural Science, increased throughput from 60/s to 120/s. Moved old design to 'To remove' book.
- Halved number of belt inputs in Utility Science.
- Updated book image.

## v0.26.0
- Added fuel factories to space platforms and final part of factories needed for [10 Books Full of Rails](https://github.com/Opinionated-Blueprints/10-Books-Full-of-Rails), including robots and solar elements.
- Updated blueprint descriptions.

## v0.25.0
- Added all military and pipe-related factories, needed in bulk to perform wall maintenance work when using [10 Books Full of Rails](https://github.com/Opinionated-Blueprints/10-Books-Full-of-Rails).
- Replaced heating towers with Recyclers at Lubricant factory for Nauvis. This adds no value and allows for 20% reduction in space.
- Changed direction of end of belt in Promethium Science to prevent Biter eggs from spoiling.
- Tweaked asteroid crusher. Now it produces stable 960/s when one product clogs entire system.
- Removed items related to god controller from main book.
- [Tests] floating-point arithmetic of fluid pumping speed is more accurate, has error of less than 0.01% compared to game mechanics, and doesn't cause integer overflow.

## v0.24.0
- Added Space Science (240/s) and moved old one to Substitutes book.
- Improved asteroid crusher load balancer. Now it can reach 950/s when one product clogs entire system.
- Added stock quantity parameter to Quality Upcyclers.

## v0.23.0
- Added fusion reactor, asteroid crusher, and shredder for space platform.
- Changed calcite belt direction to be similar to space version for iron, copper plates, and steel for Vulcanus. Easier to build many of these in row.
- Increased throughput of railgun ammo factory from 20/s to 40/s.
- Added boiler to quality switch upgrade planners.
  
## v0.22.0
- Added Military book with piercing ammo, explosive rockets, and railgun ammo.
- Added iron, copper plates, and steel for Vulcanus and Space platform.
- Added explosives for Nauvis and Space platform.
- Removed Rails book as it's broken experimental branch compared to current version of factories and needs redesign. You can find it on GitHub in development folder.

## v0.21.0
- Added Lubricant for each planet.
- Grouped Nauvis-specific plans into book.
- Reduced Agricultural tower farm throughput from 39/s to 30/s. Did I miss something, did growth time change from 4m to 5m?
- Updated FAQ.
- [Tests] Added tolerance parameter to grid plans.
- [Tests] Added throughput information and blueprint icons on map display.

## v0.20.0
- Added spoilage management to Biolab. When using Agricultural science, do not choose belts that use splitter, otherwise, biolab will be clogged forever and require rebuilding.
- Unified throughputs per second (TPS) according to legendary quality and maximum productivity bonus. Some factories may produce more than TPS, but this will not change number of factories needed unless you want to build 10+ in one place and find most optimal number of belts. most prominent example is rocket fuel factories or Production Science for which bandwidth is 20% higher than TPS. It's compromise between pushing it to its limits and presenting values that are easy to understand, calculate, and use.
- [Tests] Added tolerance parameter to tests.
  
## v0.19.0
- Blueprints can now target any quality except Rails book.
- Reduced quality of all electrical poles and substations to normal, except Rails book.
- Replaced steel chests with iron chests at Kovarex enrichment factory to exclude them from quality switches.
- Removed clogging at Military Science.
- Halved required productivity percentage for all rocket fuel factories and rounded throughput to 20, 60, or 120 per second. It is easier to calculate things and more achievable for most. In future, I will prepare cheat sheet with throughputs for different qualities and productivity levels.

## v0.18.0
- Added upgrade planners to quality switching. current version isn't ready to support lower-quality electric poles and substations.
- Added FAQ.
- Reduced quality of some pipes, all Agricultural towers, and Roboports to normal quality.

## v0.17.0
- Added special book called "To remove" for blueprints that will be removed in future. If you need any of these, move them out.
- Redesigned Promethium Science and increased throughput from 150/s to 240/s. Old blueprint is in 'To remove' book.
- Grouped planet-specific blueprints into internal books.
- Removed clogging from Rocket Fuel factory(oil) during light oil shortages.
- Added input information to all blueprints.
- Added missing lamps except for Aquilo blueprints. Lamps ruin visual phenomenon of hot heat pipe.
- Fixed declared blue circuit throughput from 30/s to 60/s.
- Factory producing sulfur and sulfuric acid excluding lubricant can work in sulfur acid mode (9000/s), sulfur(480/s), or mixed. Moved iron plate belt closer to sulfuric acid input and fixed unattainable throughput of 9000/s.
- Rounded Kovarex enrichment declared factory throughput from 17/s to 16/s. Doubled uranium-235 buffer from 40 to 80. It will take longer to warm up but later produce stable 16/s without need for extra 40% more machines. Inserters aren't fast enough to provide instant 40 uranium-235 without interruption.
- Redesigned steel factory to match with iron and copper plates input/output. Removed clogging, because like in Factorio, direction, and position of inserters matter when loading onto belt.
- Added extra inserter at end of Battery factory to fix periodic gaps.
- Fixed belt direction and quality of inserters in thermal power plant to make it tileable.
- Fusion Reactor requests Fluoroketone(Cold) until storage tank starts to buffer it to prevent over-delivery.
- Extra line balancer at end of Automation Science to prevent line gaps.
- Reversed lines of steel and iron plate at Chemical Science because it clogged system.
- Changed Green Circuit line direction at Utility Science because it clogged system.
- Moved line balancer to prevent line gaps at Superconductor factory.
- Added extra input inserters in Tungsten plate factory preventing line gaps.
- Replaced scrap filter with output priority to reduce Scrap Recycler clogging.

## v0.16.0
- Added Promethium Science and Quantum Processor factories.
- Added Cryogenic Science(120/s) and Fusion Power Cell(144/s).
- Added additional heating towers and made minor changes to spoilage management for most Gleba blueprints. I did this because, after several hundred hours of stress testing in lab, some designs failed for unknown reasons. game showed nutrients but somehow under hood, there was only spoilage.
- Updated blueprints image.
- Tuned Ammonia Factory and increased its efficiency from 4500/s to 6000/s.
- Power poles change in Lithium plate factory.
- Fluoroketone(Cold) factory also accept Fluoroketone(hot), especially useful with combination of Cryogenic Science farms. pipes of both factories match now.

## v0.14.0
- Added Lithium plate, Fluoroketone(Cold), ice and ammonia factories.
- Moved few heat pipes and added electric poles to power plant for Gleba, Aquilo.
- Reduced space by 10% and overall power consumption by replacing Cryogenic plant with Chemical plant producing solid fuel for Rocket fuel.

## v0.13.0
- Added Rocket fuel and electricity(408 MW) for Gleba and Aquilo.

## v0.12.0
- Added Carbon Fiber, Sulfur, and Plastic at Gleba.
- Redesigned bacteria management for copper and iron plates using better-quality chests. Now blueprints produce stable 240/s after warm-up.
- Added missing lamps across various blueprints.
- Updated blueprint image.

## v0.11.0
- Added Copper and Iron plate factories at Gleba.
- Added extra anti-spoilage changes to Yumako Mash, Jelly, and Bioflux.
- Added inserter at end of electric furnaces producing copper and iron plates. Blueprint didn't always produce perfect 240/s.

## v0.10.0
- Added Agricultural Science(60/s).
- Added Yumako Mash, Jelly, Bioflux, and Agricultural Tower farm.

## v0.9.0
- Added Metallurgic and Electromagnetic Science - both 120/s.
- Redesigned Low Density Structure factory for Vulcanus. 20% less space and more visually pleasing arrangement.

## v0.8.0
- Added Scrap Recycler for normal quality products needed in manufacturing. Should be placed before Quality Recycler or as separate line. Allows to set 9 exclusive filters or 45 mixed but number of chests can be extended.
- Added Quality Upcycler(Electric furnace).
- Quality Recycler allows to set of unlimited amounts of unwanted products. You can add them in Constant Combinator and this setting is shared across all Quality Recyclers.
- Reduced number of requested items from 200 to 20 for Quality Upcyclers. It allows for better resource management where more machines can work in parallel. Chests will trash any exceeding number of resources.
- Changed requester chests to buffer chests for rare and epic quality results. It allows sharing resources to speed up legendary crafting. Solves problem of resource hoarding by one type of product. When there were not enough rare and epic ingredients, many machines simply stopped and only legendary quality ones worked. Just make sure you have separate logistics network for such farms, as it will use all rare and above ingredients until chest is full of legendaries.
- Fixed not linked ingredient parameters in Quality Upcycler(Foundry).

## v0.7.0
- Added Rocket Fuel for Fulgora.
- Added factories for Tungsten plate, Tungsten carbide, Plastic, Rocket Fuel, and Low Density Structure at Vulcanus.
- Quality Upcyclers have additional 2-3 beacons for legendary crafting to speed up things.
- Supercapacitor directly produces Holmium Solution because there are not so many places to use it so it doesn't make sense to deliver it.

## v0.6.0
- Added Holmium plate(960/s)
- Added Superconductor(480/s)
- Added Supercapacitor(120/s)
- Added to Quality Upcyclers missing pipes and extra inserters that transfer byproducts directly to machines to reduce number of items on belt. Lamps and poles were slightly moved.
- [BUG] Changed in Quality Upcyclers quality modules to productivity modules in legendary machines.
- Quality Recycler allows to setting of up to 4 filters for unwanted products above rare quality to recycle. Done for scrap by default. chests were slightly moved.

## v0.5.0
- Added universal Quality Recycler (below rare) and Quality Upcycler (rare and above).
- Renamed book from 'stackable' to 'tileable' factories.

## v0.4.0
- [Rails] Added Military Science (480/s).
- [Rails] Added Production Science (480/s).
- [Rails] Added Biolab (57000 SPM). typical rail setup of 960/s can feed up to 8 of these and generate 456000 SPM.

## v0.3.1
- [Rails] Unified power poles connections.
- [Rails] Replaced bulk inserters with stack inserters for unloading onto belts.
- [Rails] Added missing train station requester setups.

## v0.3.0
- Added Nuclear Fuel factory.
- Added Battery factory.
- Rebuilt sulfur and sulfuric acid setup, same space, twice more sulfur(480/s), and 3 times more sulfuric acid(9000/s). Force build will work on previous versions.
- Moved some electric poles in rocket fuel factory to fix unplanned asymmetrical imperfections.
- Added experimental rail version of factories integrated with [10 Books Full of Rails](https://github.com/Opinionated-Blueprints/10-Books-Full-of-Rails)

## v0.2.0
- Added belt input information for factories with more than two inputs.
- Added Military Science
- Rebuilt uranium processing to use belts and uranium ore directly.

## v0.1.0
- Initial version

</details>