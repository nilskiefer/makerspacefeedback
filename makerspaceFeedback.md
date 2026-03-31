# Makerspace Feedback Notes

**Nils Kiefer**  
March 2026

These are personal notes based on my own experience visiting and using a number of makerspaces. They are not meant as a formal recommendation, just a compilation of the things I personally think matter most.

## What Seems Most Important

My overall impression is that the most important decision is usually not which flagship machines to buy. The bigger long-term risks tend to be poor maintenance, missing consumables, weak storage routines, and tools that do not match the actual users of the space.

If I had to summarize my view in one sentence, it would be this: design the makerspace around the realities of shared use. Beginners will make mistakes, tools will wear out quickly, and missing small parts will block more projects than missing advanced machines.

### 1. Consumables matter more than people expect

The biggest pain point in most workshops is not the lack of tools, but the lack of maintenance and missing consumables. A space can look excellent in year one and then become frustrating very quickly once supplies disappear and worn parts are not replaced.

Because of that, I think the makerspace would benefit a lot from keeping a strong stock of basic materials and frequently used parts.

### 2. Some "tools" should be treated almost like consumables

In a shared environment, some items wear out fast enough that it is better to plan for replacement instead of treating them as permanent purchases. Can have some general use but also offer people to buy replacements (per user it becomes cheap in bulk)

This applies especially to:

- Soldering iron tips
- Drill bits
- Needle-nose pliers
- Cutters
- Screwdriver bits
- Oscilloscope probes

In the same spirit, I usually think it makes more sense to buy reliable, low-cost shared tools in bulk and replace them when needed than to buy a few expensive tools and hope they survive heavy use. Wire strippers are one area where paying more can make sense.

### 3. Infrastructure and workflow matter more than niche machines

My impression is that strong infrastructure matters more than unusual equipment.

The basics I would care most about are:

- Sturdy workbenches
- Good lighting
- Easy local Wi-Fi access for IoT devices and lab equipment
- Power outlets with ground-fault protection, if that is not already standard in the facility

Eduroam is often inconvenient for IoT projects and some modern machines, so a local Wi-Fi network for makerspace users would be very helpful.

### 4. Storage, access, and cleanup need to be solved early

A makerspace degrades quickly if storage and cleanup are inconvenient. I think cleaning needs to be easy, project storage needs to exist, and higher-value tools probably need some kind of controlled access.

Useful ideas:

- A dedicated tool locker for higher-value equipment somehow limited to people, probably a million ways to do it.
- Project storage for longer-term members who want to keep their own tools and ongoing builds on site
- A small storage fee so abandoned boxes can be cleared without drama when it stops being payed (forgotten)
- A workshop vacuum

### 5. The tool selection should match the actual users

Many workshop problems come from inexperience rather than negligence. It is unrealistic to train every user to a high level, and people often do not know what they do not know. Because of that, I think tool choices should reflect the actual user base.

If the space is mainly for students and beginners, there is usually little reason to fill it with premium tools that cost many times more but do not create equally large benefits in beginner workflows.

### 6. Looking at an established makerspace would probably help

I think a visit to Stockholm Makerspace would likely be very useful. They support a broad range of users, have operated for a long time, and seem to have already solved many practical problems that show up in shared workshop environments.

## Core Stock to Keep on Hand

In many projects, the real bottleneck is not a missing machine but one missing small part. This is one of the main reasons I often go to ELAB: not for their older or more niche tools, but because they have stocked useful components and recent chips that make it easy to keep moving on a project.

If I were setting up a baseline stock, I would want things like:

- Solder
- Soldering iron tips
- Hot glue sticks
- Drill bits
- Screws and fastener assortments
- Common cables and connectors
- Heat-shrink tubing
- Wire in multiple gauges and types
- Heat-set inserts
- USB-C cables
- Micro-USB cables
- DC connectors
- Buck converters
- Battery management systems
- Chargers
- Sensors
- Microcontrollers

## Mechanical Equipment

### High Priority

#### Several small 3D printers

I tend to think of 3D printers almost like large consumables. They have many moving parts and will inevitably require maintenance, often to the point where repairs are more time-consuming than replacement. In shared use, the main bottleneck is usually not maximum print volume, but having enough printers that are both working and available.

Because of that, I would rather buy several small, relatively affordable printers than a few expensive ones. A strong candidate is the [Bambu Lab A1 Mini](https://bambulab.com/en-eu/a1-mini).

If one breaks, replacement is realistic. Around 95 percent of printed parts will probably fit on a machine of that size. From what I have seen, shared-use printers degrade regardless of price category, so redundancy matters more than buying a few premium machines.

For general use, I would probably limit printing to PLA.

#### 3D scanner

I think a 3D scanner could be a relatively high-priority purchase because it fills a niche that does not seem to be covered elsewhere at KTH. It is often hard for an individual, or even a typical student makerspace, to justify buying one, even though it becomes useful surprisingly often.

Anything that involves designing around an object that already exists becomes much easier with a 3D scanner. That includes enclosures, adapters, mounts, replacement parts, reverse engineering, and modifications to existing products.

One concrete option is the [EINSTAR 2](https://3dverkstan.se/produkt/einstar-2/), listed at 13,188 SEK excluding VAT.

#### Basic mechanical bench tools

For light mechanical work, I think a few flexible bench tools would go a long way:

- A Dremel-style rotary tool, because it is easy to use and useful for many small tasks
- A drill stand for the rotary tool, such as the [Dremel Workstation](https://www.dremel.com/se/sv/p/dremel-workstation-26150220jb)
- A small vise for holding parts during lighter work, for example this [tool holder and vise from Jula](https://www.jula.se/catalog/verktyg-och-maskiner/tillbehor-till-elverktyg/slip-och-gravyrtillbehor/slipgravyrsatser-och-tillbehor/verktygshallare-024117/)

If the space is expected to support more woodworking, or other work that needs sturdier fixtures, that becomes a separate discussion. At that point, stronger vises and more serious workholding would probably make sense, but so would better dust handling and filtration.

Obviously a handheld drill, any should do.

### Medium Priority

#### One larger or more capable printer

It could make sense to also have one larger or more advanced printer for bigger parts and more demanding materials, but I would treat this as secondary. PLA is probably sufficient for most makerspace projects.

ELAB has had some success with the Bambu Lab A1, although I do not think the increased cost is justified unless you already know that a larger print area than the A1 Mini is needed often.

#### Rapid prototyping tools

If the goal is to support many MVPs and fast prototyping cycles, a hot-wire cutter and a supply of styrofoam could be very useful.

### Lower Priority

#### Multifunction fabrication machine

A machine like the [Bambu H2D](https://bambulab.com/en-eu/h2d) is interesting.

It may cover several fabrication tasks, but it does not replace a proper laser cutter and concentrates maintenance risk into one machine. I would not treat this as an early purchase.

## Electrical Equipment

### High Priority

#### Baseline electrical bench

The baseline electrical setup I would want to see includes:

- Cheap power banks for breadboard circuits and prototypes
- Wire strippers
- Several crimp tools
- Multimeters
- Heat guns
- Bench power supplies
- Soldering irons
- A microscope
- An oscilloscope

#### Power banks

Cheap power banks are useful because they provide a simple, protected, and convenient 5 V source for small prototypes. This assumes that USB-to-breadboard adapters, breadboards, and Dupont wires are also available.

#### Wire strippers and crimp tools

I think wire strippers are essential. Crimp tools should also be available in multiple types, because crimping comes up often and different connectors require different tools.

#### Multimeters

Cheap multimeters have become very good. There is usually no need to overspend here. One example is the [UNI-T 131D from Electrokit](https://www.electrokit.com/multimeter-uni-t131d).

#### Soldering irons

T12-based soldering irons seem like a good fit for a shared lab. They are cheap, common, and easy to source. Lab soldering irons will inevitably be abused, and I do not think the price jump to marginally better stations is justified in a shared student environment.

Spare tips should be stocked in bulk. A good model is to treat tips as consumables that users buy when needed. That shifts some responsibility from maintainers to users and makes wear more manageable.

One possible option is this [KSGER T12 station](https://ksger.net/products/1859372).

#### Microscope

I think a microscope is a very overlooked tool and often becomes almost essential for anything beyond the simplest electronics work. SMD parts are cheap in bulk, and assembly and debugging get much easier when magnification is available.

I would want to research this more before making a concrete recommendation.

#### Oscilloscope

I would definitely want an oscilloscope. I am very happy with the Digilent Analog Discovery 3. It is relatively cheap, requires a laptop, and offers more features than many oscilloscopes that cost several times more, although at lower frequencies. Its main drawbacks are that it has no built-in screen and may be somewhat more fragile than a desktop oscilloscope.

If this type of device is used in a shared space, I think there should be very clear instructions to connect ground before anything else.

I have also heard good things about the Rigol DHO800 series.

#### Bench power supplies

The right choice depends on how advanced the expected projects are, but almost any reasonable unit will do. I have heard good things about the KA3005D. Isolated outputs are a useful feature to prioritize.

I do not see much benefit in paying extra for very low-noise power supplies when the cost-to-benefit ratio, compared with what is already available in other KTH labs, seems poor.

### Medium Priority

#### Thermal camera

A thermal camera is more advanced, but still very useful for debugging PCBs, and it does not seem especially common from what I have seen. It should probably be fastened to a desk or otherwise secured.

One example is the [UNI-T UTI712S from Clas Ohlson](https://www.clasohlson.com/se/UNI-T-Uti712S-v%C3%A4rmekamera-termisk/p/36-9240).

### Lower Priority

#### PCB fabrication machine

Some form of PCB fabrication machine would be relatively unique within KTH and could be valuable. One example is [Voltera PCB fabrication systems](https://www.voltera.io/products).

That said, I have not seen the corresponding machine at Stockholm Makerspace get much use, so I would want to do more research before recommending it.

## If I Had to Prioritize Spending

If the makerspace has limited budget and time, these are the things I would personally prioritize before buying niche machines:

1. Reliable benches, power, lighting, Wi-Fi, and cleaning tools
2. A strong system for consumables, stock replacement, and storage
3. Several affordable 3D printers instead of a few premium ones
4. A 3D scanner, since it fills a real niche and makes designing around existing objects much easier
5. A solid baseline electrical bench for soldering, debugging, and prototyping
6. Clear access control for expensive tools and accessories

My sense is that if those basics are done well, the space will stay useful over time. If they are not, even very impressive equipment will quickly become frustrating to use.
