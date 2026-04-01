# Makerspace Feedback Notes

**Nils Kiefer**, March 2026

Personal notes based on visiting and using several makerspaces. Not a formal recommendation, just what I think matters most.

## What Matters Most

The most important decision is usually not which flagship machines to buy. The bigger long-term risks are poor maintenance, missing consumables, weak storage, and tools that don't match the actual users.

Beginners make mistakes, tools wear out fast, and missing small parts will block more projects than missing advanced machines.

### 1. Consumables

The biggest pain point in most workshops isn't a lack of tools, it's missing consumables and worn parts that never get replaced. A space can look great in year one and become frustrating quickly without a resupply plan.

### 2. Tools as consumables

In shared use, some items wear out fast enough that replacement should be planned from the start. Consider offering replacements for purchase; per user it becomes cheap in bulk.

This applies to:
- Soldering iron tips
- Drill bits
- Needle-nose pliers
- Cutters
- Screwdriver bits
- Oscilloscope probes
- Power supply cables

For tools in this category, it makes more sense to buy reliable low-cost items in bulk than a few expensive ones. Wire strippers are an exception where paying more is worth it.

### 3. Infrastructure 

- Sturdy workbenches (Heard good things about ELFA arbetsbänk, relatively cheap)
- Good lighting
- Local Wi-Fi for IoT devices and lab equipment (Eduroam is often impractical for this)
- Ground-fault protected outlets, if not already standard

### 4. Storage, access, and cleanup

A makerspace degrades quickly if these aren't easy.

- Controlled access for higher-value tools
- Project storage for members with ongoing builds
- A small storage fee so abandoned boxes can be cleared cleanly
- A workshop vacuum

### 5. Match tools to actual users

Many problems come from inexperience, not negligence. If the space is primarily for students and beginners, there's little reason to fill it with premium tools that cost much more without meaningfully improving beginner workflows.

### 6. Visit an established makerspace

A visit to Stockholm Makerspace would likely be valuable. They support a broad range of users, have operated for a long time, and have already solved many practical problems that come up in shared workshop environments.

Its in THINGS building and there are often enthusiastic "guides" that can walk through what they offer and answer any questions.

## Core Stock to Keep on Hand

The real bottleneck in many projects isn't a missing machine but one missing small part. This is one of the main reasons people rely on spaces like ELAB, not for niche tools, but for stocked components that keep projects moving.

Baseline stock:
- Solder
- Soldering iron tips
- Hot glue sticks
- Drill bits
- Screws and fastener assortments
- Common cables and connectors (USB-C, Micro-USB, DC)
- Heat-shrink tubing
- Wire (multiple gauges)
- Heat-set inserts
- Buck converters
- Battery management systems
- Sensors
- Microcontrollers
- Breadboards
- Dupont wires
- Resistor and capacitor assortment kits
- Kapton tape and electrical tape
- Zip ties and velcro straps
- Duct tape
- Fiberglass and carbon fiber rods

## Mechanical Equipment

### High Priority

#### Several small 3D printers

Treat 3D printers like large consumables. They have many moving parts and in shared use the bottleneck is almost never print volume, it's having enough printers that are working and available. Redundancy matters more than buying a few premium machines.

A strong candidate is the [Bambu Lab A1 Mini](https://bambulab.com/en-eu/a1-mini). If one breaks, replacement is realistic. From experience, most printed parts will fit on a machine that size.

For general use, limit printing to PLA.

#### 3D scanner

A 3D scanner fills a niche that isn't well covered elsewhere at KTH and is hard for individuals or small groups to justify buying. It becomes useful surprisingly often; anything involving designing around an existing object (enclosures, adapters, mounts, replacement parts, reverse engineering) is much easier with one.

One concrete option: [EINSTAR 2 from 3DVerkstan](https://3dverkstan.se/produkt/einstar-2/), 13,188 SEK ex. VAT.

#### Basic bench tools

- A Dremel-style rotary tool
- A drill stand for it, such as the [Dremel Workstation 220](https://www.dremel.com/se/sv/p/dremel-workstation-26150220jb)
- A small vise, for example this [tool holder from Jula](https://www.jula.se/catalog/verktyg-och-maskiner/tillbehor-till-elverktyg/slip-och-gravyrtillbehor/slipgravyrsatser-och-tillbehor/verktygshallare-024117/)
- A handheld drill

If the space is expected to support serious woodworking, stronger workholding and better dust handling become a separate discussion.

### Medium Priority

#### One larger printer

A larger or more advanced printer could make sense for bigger parts and demanding materials, but treat it as secondary. The [Bambu Lab A1](https://bambulab.com/en-eu/a1) is an option, though the larger print area is only worth the cost if you already know it'll be needed regularly.

#### Rapid prototyping tools

A hot-wire cutter and styrofoam supply can be very useful for ultra fast prototyping.

### Lower Priority

#### Multifunction fabrication machine

The [Bambu H2D](https://bambulab.com/en-eu/h2d) covers several fabrication tasks but doesn't replace a proper laser cutter and concentrates maintenance risk into one machine. May be a good option if access is limited somehow. Not an early purchase.

## Electrical Equipment

### High Priority

#### Baseline electrical bench

- Power banks (cheap, good 5 V source for breadboard prototypes)
- Wire strippers
- Crimp tools (multiple types, different connectors require different tools)
- Multimeters
- Heat guns
- Bench power supplies
- Soldering irons
- Microscope
- Oscilloscope

#### Multimeters

Cheap multimeters have become very good. One example: [UNI-T UT131D from Electrokit](https://www.electrokit.com/multimeter-uni-t131d), 199 SEK.

#### Soldering irons

T12-based stations are a good fit for shared labs, cheap, common, easy to source. Lab irons will be abused, and the price jump to marginally better stations isn't justified in a student environment. Stock tips in bulk and let users buy replacements when needed.

One option: [KSGER T12 station](https://ksger.net/products/1859372).

#### Microscope

An often overlooked tool that becomes almost essential for anything beyond basic electronics work. SMD parts are cheap in bulk, and assembly and debugging get much easier with magnification. Worth more research before a specific recommendation.

#### Oscilloscope

The Digilent [Analog Discovery 3](https://digilent.com/shop/analog-discovery-3/) is relatively cheap, requires a laptop, and offers more features than many oscilloscopes that cost several times more, though at lower frequencies and without a built-in screen. If used in a shared space, ground connection order needs to be clearly documented.

The [Rigol DHO800 series](https://rigolshop.eu/products/oscilloscope/dho800.html) is a good alternative if a standalone unit is preferred.

#### Bench power supplies

Almost any reasonable unit will do. The [Korad KA3005D](https://www.digikey.se/en/products/detail/sra-soldering-products/KA3005D/10708362?srsltid=AfmBOoq80bOPX4wRTvH1oZx8g5GnpVaJ0sw8GKZtJqQ5YC0YinVTV5Gn) is well regarded. Prioritize isolated outputs.

### Medium Priority

#### Thermal camera

Useful for PCB debugging and not especially common in student spaces. Should be secured to a desk.

One option: [UNI-T UTI712S from Clas Ohlson](https://www.clasohlson.com/se/UNI-T-Uti712S-v%C3%A4rmekamera-termisk/p/36-9240).

### Lower Priority

#### PCB fabrication machine

Would be relatively unique within KTH. [Voltera](https://www.voltera.io/products) makes one option. That said, the equivalent machine at Stockholm Makerspace doesn't seem to get much use, worth more research before committing.