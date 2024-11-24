# Tileable Factories

Book of factories that are as simple and compact as possible to build advanced factories.

<details>
<summary>Changelog</summary>

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
- Added experimental rail version of factories integrated with [10 Books Full of Rails](https://github.com/Opinionated-Blueprints/10-Books-Full-of-Rails")

## v0.2.0

- Added belt input information for factories with more than two inputs.
- Added Military Science
- Rebuilt uranium processing to use belts and uranium ore directly.

## v0.1.0

- Initial version

</details>