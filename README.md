# paxdriver

I'm Kris Driver — co-host and producer of the *Frivolous Gravitas* podcast; author of *Emergence: Luctor et Emergo* and *The Melting Pot: A Canadian Guide to Cooking & Nutrition for Managing Chronic Health Conditions*; singer / songwriter / producer of the feature-length LP hip-hop album *Emergence: Luctor et Emergo*; and a developer / designer with a bad habit of taking interest in too many things at once.

Formerly a FOREX investment banker and Flash developer; currently freelancing in web development (HTML / CSS / React), working in Blender and graphics, and maintaining open source projects that veer between humanitarian systems design, industrial process modeling, browser-side experiments, and machine learning research.

## Current focus

Lately the biggest work on this GitHub has been [KriSYS](https://github.com/paxdriver/KriSYS/tree/phase-six-react) and [AmmoNite](https://github.com/paxdriver/AmmoNite), with [blender-to-canvas](https://github.com/paxdriver/blender-to-canvas) continuing on the side as a smaller technical sandbox.

### KriSYS
KriSYS is probably the most important project on my GitHub right now, and the one I'd most like help with.

It is a humanitarian crisis communication ledger meant for disasters, rolling blackouts, warzones, and other hostile communications environments. The idea is to make alerts, station check-ins, and encrypted family / group / individual messages verifiable even when internet access is unreliable or absent altogether.

The goal is not cryptocurrency. There are no tokens, no mining incentives, no financial layer, and no speculative gimmicks. The "blockchain" portion is simply a cryptographically signed, append-only message history with one canonical chain per crisis so that confirmed events can be verified offline.

Victims can supply family members and friends abroad with their wallet addresses so loved ones have a consistent way to check in on their status as a crisis unfolds. On the aid side, the same system can help with accountable record keeping, alerts, aid distribution tracking, station activity, and family reunification.

Core use cases:
- encrypted family, group, and individual messages
- authorized check-ins at camps, hospitals, depots, and aid vehicles
- emergency alerts issued by the crisis service provider
- QR-based identity and check-ins
- offline verification of confirmed history via signed blocks

Active branch:
- [KriSYS / phase-six-react](https://github.com/paxdriver/KriSYS/tree/phase-six-react)

If done properly, this could be a tremendous help in disasters and conflict zones alike, so if you work in React, offline-first architecture, relay networking, applied cryptography, or humanitarian logistics, feel free to get in touch.

### AmmoNite
AmmoNite is a systems-engineering concept for a modular coastal facility built around ammonium nitrate fertilizer production, with potable water, brine-derived magnesium binders, and occasional oxygen surplus integrated into the same design.

In plainer English, it is an attempt to think through how seawater, sunlight, atmospheric nitrogen, and local sand / rock / salt could be turned into a practical industrial base for sunny, arid coastal regions where fresh water and fertilizer are scarce, supply chains are fragile, and overly complex maintenance requirements are more liability than luxury.

The repo is currently focused on first-pass sizing and mass-energy balances rather than detailed engineering drawings. I would rather keep the assumptions conservative and the trade-offs visible than pretend the hard parts do not exist.

Major themes:
- AN output as the anchor for the rest of the system
- solar-derived heat and electricity wherever possible
- simple thermal storage using local sand, rock, and salt
- potable water from desalination
- brine recovery for salts and magnesium-based construction binders
- optional wastewater integration and low-emission backup power

### blender-to-canvas
blender-to-canvas is a much smaller and more playful project. I'm using Blender model data to render 3D in canvas mainly as an excuse to practise with `ArrayBuffer`s in JavaScript and get better at moving data between languages and platforms.

There is no reason this couldn't be simplified, and it is certainly not the best approach to building a browser 3D engine. That is part of the point. I may branch it later to compare contiguous memory allocation versus regular JavaScript allocation, then compare both against THREE.js and a math library just to see whether any differences are actually measurable.

Educational, experimental, and definitely not something I'd tell anybody to put into production lol.

Older demo:
- [blender-to-canvas video](https://www.youtube.com/watch?v=4K0B8xxW46g)

## YouTube
My YouTube channel is currently on hiatus.

I started it as a development / research channel and as a place to document the long chase after machine learning / AGI ideas, but I'm boycotting YouTube for new uploads because of the gratuitous abuse of its copyright claim system against my content despite my holding valid licenses for the music being flagged.

I'm not willing to keep laboriously disputing bogus claims every single time I publish something new when the platform could simply allow me to attach the PDF license and move on. Until YouTube stops enabling that kind of nonsense, the channel stays paused.

Regardless, the channel is still up and older material remains available here:
- [@Machine_LearningAI](https://www.youtube.com/@Machine_LearningAI)

## A note on open source
A particular shout-out of thanks goes to the open source community. From writing and publishing tools to audio engineering, graphics, web development, and research tooling, I truly have stood on the backs of giants. A lot of what I make only exists because other people decided to share their work.

## Reach me
- Website: [KrisDriver.com](https://www.krisdriver.com)
- BlueSky: [@paxdriver.bsky.social](https://bsky.app/profile/paxdriver.bsky.social)
