# Tileable Factories

Book of factories that are as simple and compact as possible to build advanced factories.

You can also find it on [Factorio.School](https://www.factorio.school/view/-OBdq3vJ2slIWEDAXEeM) or [Factorioprints](https://factorioprints.com/view/-OBdq3vJ2slIWEDAXEeM).

<details>
<summary>Changelog</summary>

## v0.34.0
- Added artillery shell(60/s), pipes(240/s, 120/s), ice platform(12/s), foundation(36/s), scrap recycler(120/s) factories.
- Removed the spear (spaceship) as it no longer serves its purpose and requires a redesign.
- Pushed most of the designs, including the game engine, to their limits.

## v0.33.0
- Added input requirements to every factory and fixed many minor issues.
- Added universal Refined Concrete(240/s) factory.
- Added tools to measure throughput.

## v0.32.0
- Added Smart Malls. Mostly from early to late game and transition to Quality Enhancers.
- Added new Quality Enhancers and reduced space of rest by 20-40% thanks to new circuit network changes.
- Reduced space by 15-20% of Iron/Copper/Steel factories for Vulcanus and Space.
- Updated FAQ
- [Tests] Removed redundant combinators

## v0.31.0
- Added silo and wagon drilling, 2640/s and 3840/s, respectively.
- Rebuilt the water supply for the Plastic and Refined Concrete factories in Vulcanus to accommodate (another) game fluid changes.
- [Tests] Reworked the test lab, including a testing framework for better maintenance.
- Fixed fusion reactor low power under load ([Issue 16](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/16))
- Added Holmium Ore to unwanted products in Quality Recycler ([Issue 17](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/17))
- Added missing pipe in quantum processor factory ([Issue 18](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/18))
- Many minor changes, such as adding missing power poles, circuit network constraints, or additional inputs/outputs for better blueprint tiling.
  
## v0.30.1
- Added missing pipe connection of fluoroketone (hot) in fluoroketone factory([Issue 12](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/12))
- Removed clog related to overflow of petroleum gas in Vulcanus fuel factory([Issue 13](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/13))
- Reduced space of fusion power cell factory by another 10%.

## v0.30.0
- Added multipurpose space platform - Spear.
- Added space deconstructor to remove items from blueprints that can be safely removed in space.
- Increased steel plate factory throughput from 160/s to 240/s. Added Gleba steel plate factory.
- Quality Enhancer stock quantity is limited to legendary items. When the buffer is full, all remaining resources will be trashed to maximize resource sharing. ([Issue 4](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/4))
- Fixed fluoroketone (hot) overflow bug in a fluoroketone factory. Now factory prioritizes external input of fluoroketone (hot). ([Issue 5](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/5))
- Reduced space of most Aquilo factories by 20-50%. ([Issue 8](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/8))
- Added unsafe downgrade planners for belts, splitters, and inserters. They are unsafe because reverting requires a super force build of an initial blueprint on a placed factory. Never use this against a book. For now, not every blueprint can be downgraded because of the turbo underground belt length requirements. ([Issue 10](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/10))
- Fixed input belts in space iron, steel, and copper factories that prevented them from being tiled.
- Removed external Substations in the Explosive rocket factory.

## v0.29.1
- Fixed misplaced inserters and Requester chest in Foundry Quality Enhancer ([Issue 3](https://github.com/Xeinaemm/Factorio-Tileable-Factories/issues/3))
- Rebuilt refined concrete (Vulcanus) factory to hit 240/s when a problem with steam condensation is fixed ([Issue 118644](https://forums.factorio.com/118644))
- One iron plate input was removed in Space Science.
- Added tileable input belts for Biolab.

## v0.29.0
- Added splitter, bulk inserter, stack inserter, refined concrete (Vulcanus), space platform foundation, and beacon factories.
- Redesigned belt and underground belts to use Vulcanus-specific recipes and also moved them alongside modules to planet-specific books
- Removed "To remove" book.

## v0.28.0
- Added belt and underground belt factories.
- Redesigned and increased the robot factory's throughput from 40/s to 80/s. This is 20% more space efficient than using two 40/s.
- Revisited all blueprints and the space of most factories was reduced by 5-20%. In many cases, recyclers are more efficient than heating towers. The plans also use my belt balancers, which reduce space by 2x-10x compared to Raynquist's Belt Balancers.
- Fusion reactor (22.5GW) operates on normal-quality substations without power losses.
- [Tests] Added description to constant values used in fluid tests. 
  
## v0.27.0
- Added Modules factories (6/s).
- Redesigned Military and Production Science, increased throughput from 80/s to 240/s, and sorted inputs by type. Moved old designs to the 'To remove' book. Military Science now requires walls rather than raw materials because otherwise, you would need an extra 8 belts of stone.
- Redesigned Agricultural Science, increased throughput from 60/s to 120/s. Moved the old design to the 'To remove' book.
- Halved the number of belt inputs in Utility Science.
- Updated book image.

## v0.26.0
- Added fuel factories to space platforms and the final part of the factories needed for [10 Books Full of Rails](https://github.com/Opinionated-Blueprints/10-Books-Full-of-Rails), including robots and solar elements.
- Updated blueprint descriptions.

## v0.25.0
- Added all military and pipe-related factories, needed in bulk to perform wall maintenance work when using [10 Books Full of Rails](https://github.com/Opinionated-Blueprints/10-Books-Full-of-Rails).
- Replaced heating towers with Recyclers at Lubricant factory for Nauvis. This adds no value and allows for a 20% reduction in space.
- Changed the direction of the end of the belt in Promethium Science to prevent Biter eggs from spoiling.
- Tweaked asteroid crusher. Now it produces stable 960/s when one product clogs the entire system.
- Removed items related to god controller from the main book.
- [Tests] The floating-point arithmetic of fluid pumping speed is more accurate, has an error of less than 0.01% compared to game mechanics, and doesn't cause integer overflow.

## v0.24.0
- Added Space Science (240/s) and moved the old one to the Substitutes book.
- Improved asteroid crusher load balancer. Now it can reach 950/s when one product clogs the entire system.
- Added stock quantity parameter to Quality Enhancers.

## v0.23.0
- Added fusion reactor, asteroid crusher, and shredder for space platform.
- Changed calcite belt direction to be similar to the space version for iron, copper plates, and steel for the Vulcanus. Easier to build many of these in a row.
- Increased throughput of railgun ammo factory from 20/s to 40/s.
- Added boiler to quality switch upgrade planners.
  
## v0.22.0
- Added Military book with piercing ammo, explosive rockets, and railgun ammo.
- Added iron, copper plates, and steel for the Vulcanus and Space platform.
- Added explosives for Nauvis and Space platform.
- Removed Rails book as it's a broken experimental branch compared to the current version of factories and needs a redesign. You can find it on GitHub in the development folder.

## v0.21.0
- Added Lubricant for each planet.
- Grouped Nauvis-specific plans into a book.
- Reduced Agricultural tower farm throughput from 39/s to 30/s. Did I miss something, did the growth time change from 4m to 5m?
- Updated FAQ.
- [Tests] Added tolerance parameter to grid plans.
- [Tests] Added throughput information and blueprint icons on a map display.

## v0.20.0
- Added spoilage management to Biolab. When using Agricultural science, do not choose belts that use a splitter, otherwise, the biolab will be clogged forever and require rebuilding.
- Unified throughputs per second (TPS) according to legendary quality and maximum productivity bonus. Some factories may produce more than TPS, but this will not change the number of factories needed unless you want to build 10+ in one place and find the most optimal number of belts. The most prominent example is rocket fuel factories or Production Science for which bandwidth is 20% higher than TPS. It's a compromise between pushing it to its limits and presenting values that are easy to understand, calculate, and use.
- [Tests] Added tolerance parameter to tests.
  
## v0.19.0

- Blueprints can now target any quality except the Rails book.
- Reduced the quality of all electrical poles and substations to normal, except the Rails book.
- Replaced steel chests with iron chests at the Kovarex enrichment factory to exclude them from quality switches.
- Removed clogging at Military Science.
- Halved the required productivity percentage for all rocket fuel factories and rounded the throughput to 20, 60, or 120 per second. It is easier to calculate things and more achievable for most. In the future, I will prepare a cheat sheet with throughputs for different qualities and productivity levels.

## v0.18.0

- Added upgrade planners to quality switching. The current version isn't ready to support lower-quality electric poles and substations.
- Added FAQ.
- Reduced quality of some pipes, all Agricultural towers, and Roboports to normal quality.

## v0.17.0

- Added a special book called "To remove" for blueprints that will be removed in the future. If you need any of these, move them out.
- Redesigned Promethium Science and increased throughput from 150/s to 240/s. Old blueprint is in 'To remove' book.
- Grouped planet-specific blueprints into internal books.
- Removed clogging from Rocket Fuel factory(oil) during light oil shortages.
- Added input information to all blueprints.
- Added missing lamps except for Aquilo blueprints. Lamps ruin the visual phenomenon of a hot heat pipe.
- Fixed declared blue circuit throughput from 30/s to 60/s.
- Factory producing sulfur and sulfuric acid excluding lubricant can work in sulfur acid mode (9000/s), sulfur(480/s), or mixed. Moved the iron plate belt closer to the sulfuric acid input and fixed the unattainable throughput of 9000/s.
- Rounded Kovarex enrichment declared factory throughput from 17/s to 16/s. Doubled uranium-235 buffer from 40 to 80. It will take longer to warm up but later produce a stable 16/s without the need for an extra 40% more machines. Inserters aren't fast enough to provide instant 40 uranium-235 without interruption.
- Redesigned steel factory to match with iron and copper plates input/output. Removed clogging, because like in Factorio, the direction, and position of the inserters matter when loading onto the belt.
- Added extra inserter at the end of the Battery factory to fix periodic gaps.
- Fixed the belt direction and quality of the inserters in the thermal power plant to make it tileable.
- Fusion Reactor requests Fluoroketone(Cold) until the storage tank starts to buffer it to prevent over-delivery.
- Extra line balancer at the end of Automation Science to prevent line gaps.
- Reversed lines of steel and iron plate at Chemical Science because it clogged the system.
- Changed Green Circuit line direction at Utility Science because it clogged the system.
- Moved line balancer to prevent line gaps at Superconductor factory.
- Added extra input inserters in Tungsten plate factory preventing line gaps.
- Replaced scrap filter with output priority to reduce Scrap Recycler clogging.

## v0.16.0

- Added Promethium Science and Quantum Processor factories.
- Added Cryogenic Science(120/s) and Fusion Power Cell(144/s).
- Added additional heating towers and made minor changes to spoilage management for most Gleba blueprints. I did this because, after several hundred hours of stress testing in the lab, some designs failed for unknown reasons. The game showed nutrients but somehow under the hood, there was only spoilage.
- Updated blueprints image.
- Tuned the Ammonia Factory and increased its efficiency from 4500/s to 6000/s.
- Power poles change in Lithium plate factory.
- Fluoroketone(Cold) factory also accept Fluoroketone(hot), especially useful with combination of Cryogenic Science farms. The pipes of both factories match now.

## v0.14.0

- Added Lithium plate, Fluoroketone(Cold), ice and ammonia factories.
- Moved a few heat pipes and added electric poles to the power plant for Gleba, Aquilo.
- Reduced space by 10% and overall power consumption by replacing the Cryogenic plant with a Chemical plant producing solid fuel for Rocket fuel.

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
- Added inserter at the end of the electric furnaces producing copper and iron plates. Blueprint didn't always produce a perfect 240/s.

## v0.10.0

- Added Agricultural Science(60/s).
- Added Yumako Mash, Jelly, Bioflux, and Agricultural Tower farm.

## v0.9.0

- Added Metallurgic and Electromagnetic Science - both 120/s.
- Redesigned Low Density Structure factory for Vulcanus. 20% less space and a more visually pleasing arrangement.

## v0.8.0

- Added Scrap Recycler for normal quality products needed in manufacturing. Should be placed before Quality Recycler or as a separate line. Allows to set 9 exclusive filters or 45 mixed but the number of chests can be extended.
- Added Quality Enhancer(Electric furnace).
- Quality Recycler allows to set of unlimited amounts of unwanted products. You can add them in Constant Combinator and this setting is shared across all Quality Recyclers.
- Reduced number of requested items from 200 to 20 for Quality Enhancers. It allows for better resource management where more machines can work in parallel. Chests will trash any exceeding number of resources.
- Changed requester chests to buffer chests for rare and epic quality results. It allows sharing resources to speed up legendary crafting. Solves the problem of resource hoarding by one type of product. When there were not enough rare and epic ingredients, many machines simply stopped and only legendary quality ones worked. Just make sure you have a separate logistics network for such farms, as it will use all the rare and above ingredients until the chest is full of legendaries.
- Fixed not linked ingredient parameters in Quality Enhancer(Foundry).

## v0.7.0

- Added Rocket Fuel for Fulgora.
- Added factories for Tungsten plate, Tungsten carbide, Plastic, Rocket Fuel, and Low Density Structure at Vulcanus.
- Quality Enhancers have an additional 2-3 beacons for legendary crafting to speed up things.
- Supercapacitor directly produces Holmium Solution because there are not so many places to use it so it doesn't make sense to deliver it.

## v0.6.0

- Added Holmium plate(960/s)
- Added Superconductor(480/s)
- Added Supercapacitor(120/s)
- Added to Quality Enhancers missing pipes and extra inserters that transfer byproducts directly to machines to reduce the number of items on the belt. Lamps and poles were slightly moved.
- [BUG] Changed in Quality Enhancers quality modules to productivity modules in legendary machines.
- Quality Recycler allows to setting of up to 4 filters for unwanted products above rare quality to recycle. Done for scrap by default. The chests were slightly moved.

## v0.5.0

- Added universal Quality Recycler (below rare) and Quality Enhancer (rare and above).
- Renamed book from 'stackable' to 'tileable' factories.

## v0.4.0

- [Rails] Added Military Science (480/s).
- [Rails] Added Production Science (480/s).
- [Rails] Added Biolab (57000 SPM). A typical rail setup of 960/s can feed up to 8 of these and generate 456000 SPM.

## v0.3.1

- [Rails] Unified power poles connections.
- [Rails] Replaced bulk inserters with stack inserters for unloading onto belts.
- [Rails] Added missing train station requester setups.

## v0.3.0

- Added Nuclear Fuel factory.
- Added Battery factory.
- Rebuilt sulfur and sulfuric acid setup, same space, twice more sulfur(480/s), and 3 times more sulfuric acid(9000/s). Force build will work on previous versions.
- Moved some electric poles in the rocket fuel factory to fix unplanned asymmetrical imperfections.
- Added experimental rail version of factories integrated with [10 Books Full of Rails](https://github.com/Opinionated-Blueprints/10-Books-Full-of-Rails)

## v0.2.0

- Added belt input information for factories with more than two inputs.
- Added Military Science
- Rebuilt uranium processing to use belts and uranium ore directly.

## v0.1.0

- Initial version

</details>
