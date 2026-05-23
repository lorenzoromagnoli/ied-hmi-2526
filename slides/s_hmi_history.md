---
theme: default
title: HMI History & Case Studies
colorSchema: dark
fonts:
  sans: DM Sans
  mono: DM Mono
  weights: '300,400,500,700'
cssEngine: unocss
routerMode: hash
---

---
title: Cover
---

<div class="cover-layout">
  <div class="tag">IED Master Transportation Design · 2025/26</div>
  <h1>HMI History<br><span class="accent">& Case Studies</span></h1>
  <div class="subtitle">Automotive HMI — Context & Foundations</div>
  <div class="instructor">Lorenzo Romagnoli</div>
</div>

---
layout: section
title: What is HMI
---

# What is HMI

---
title: HMI Definition
---

<div class="slide-split">
  <div class="split-text">
    <h3>Definition</h3>
    <h1>Human–Machine<br><span class="accent">Interface</span></h1>
    <p>A collection of functional elements — head unit, instrument cluster, HUD — as well as interaction mediums — touch, voice, haptic, physical controls — that allow turning the vehicle into a living space.</p>
    <ul>
      <li>It connects driver intent to vehicle response</li>
      <li>It shapes the entire experience of being in a car</li>
      <li>Users evaluate the car through their experience with its HMI</li>
    </ul>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/hmi-definition.png" />
  </div>
</div>

---
title: HMI Scope — Beyond the Cabin
---

<div class="slide-split">
  <div class="split-text">
    <h3>Scope</h3>
    <h1>More than<br><span class="accent">screens</span></h1>
    <p>HMI extends beyond the car interior. It includes any surface or medium that communicates between the vehicle and the people around it.</p>
    <ul>
      <li><strong>Inside:</strong> Instrument cluster, centre stack, HUD, ambient lighting, haptics, voice</li>
      <li><strong>Outside:</strong> Exterior lighting, audio signals, pedestrian displays</li>
      <li><strong>Remote:</strong> Smartphone apps, key fobs, V2X communication</li>
    </ul>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/hmi-scope.png" />
  </div>
</div>

---
layout: section
title: A Brief History
---

# A brief<br>history

---
title: HMI Timeline — 1980s to Today
---

<div class="slide-timeline">
  <h3>Evolution</h3>
  <h1>40 years of <span class="accent">digital cockpits</span></h1>
  <div class="timeline-track">
    <div class="timeline-item">
      <div class="timeline-year">1986</div>
      <div class="timeline-label">First digital instrument cluster — Buick Riviera touch-screen radio</div>
    </div>
    <div class="timeline-item">
      <div class="timeline-year">1994</div>
      <div class="timeline-label">First factory-installed GPS navigation — Oldsmobile Guidestar, BMW 7 Series</div>
    </div>
    <div class="timeline-item">
      <div class="timeline-year">2001</div>
      <div class="timeline-label">BMW iDrive — first rotary-controller central infotainment system</div>
    </div>
    <div class="timeline-item">
      <div class="timeline-year">2010</div>
      <div class="timeline-label">Touch screens go mainstream — MyFord Touch, Audi MMI, Mercedes COMAND</div>
    </div>
    <div class="timeline-item">
      <div class="timeline-year">2014</div>
      <div class="timeline-label">Apple CarPlay and Android Auto — smartphone mirroring as standard</div>
    </div>
    <div class="timeline-item">
      <div class="timeline-year">2020</div>
      <div class="timeline-label">Full-screen takeover — Tesla Model S Plaid, Mercedes MBUX Hyperscreen</div>
    </div>
    <div class="timeline-item">
      <div class="timeline-year">Now</div>
      <div class="timeline-label">AI copilots, AR HUDs, multimodal interaction, Software-Defined Vehicle</div>
    </div>
  </div>
</div>

---
layout: section
title: Why HMI Matters
---

# Why HMI<br>matters

---
title: Three Human Needs
---

<div class="slide-needs">
  <h3>Human needs</h3>
  <h1>What HMI must <span class="accent">deliver</span></h1>
  <div class="needs-grid">
    <div class="needs-item">
      <div class="needs-number">01</div>
      <div class="needs-label">Informed decisions</div>
      <div class="needs-body">Surface the right information at the right moment — without overwhelming the driver.</div>
    </div>
    <div class="needs-item">
      <div class="needs-number">02</div>
      <div class="needs-label">Safer driving</div>
      <div class="needs-body">Minimise distraction, support situational awareness, keep eyes on the road as the primary task.</div>
    </div>
    <div class="needs-item">
      <div class="needs-number">03</div>
      <div class="needs-label">Natural interaction</div>
      <div class="needs-body">Reduce the gap between intent and action — voice, gesture, and touch that feel effortless.</div>
    </div>
  </div>
</div>

---
layout: center
title: HMI as Experience
class: text-center
---

# Users evaluate the car experience<br>through their experience<br>with its <span class="accent">HMI</span>.

---
layout: section
title: The C.A.S.E. Landscape
---

# The C.A.S.E.<br>landscape

---
title: C.A.S.E. — Four Forces Reshaping Mobility
---

<div class="slide-case">
  <h3>Industry context</h3>
  <h1>C.A.S.E. — four forces <span class="accent">reshaping mobility</span></h1>
  <div class="case-grid">
    <div class="case-item">
      <div class="case-letter">C</div>
      <div class="case-word">Connectivity</div>
      <div class="case-body">Always-on vehicles, V2X communication, over-the-air updates, integrated services</div>
    </div>
    <div class="case-item">
      <div class="case-letter">A</div>
      <div class="case-word">Autonomous</div>
      <div class="case-body">SAE levels 1–5, driver attention monitoring, new cabin experience during hands-off moments</div>
    </div>
    <div class="case-item">
      <div class="case-letter">S</div>
      <div class="case-word">Shared</div>
      <div class="case-body">MaaS, ride-hailing, fleet ownership — HMI must adapt to anonymous users and multiple profiles</div>
    </div>
    <div class="case-item">
      <div class="case-letter">E</div>
      <div class="case-word">Electric</div>
      <div class="case-body">Range anxiety, charging UX, energy management — entirely new mental models to design for</div>
    </div>
  </div>
</div>

---
layout: default
title: Current HMI Challenges
---

# Current HMI challenges

- **Information overload** — communicating large amounts of data without cognitive overload
- **Context switching** — the interface must shift between driving, parked, and stationary-moment experiences
- **Input diversity** — gesture, haptic, voice — each with different reliability and distraction profiles
- **Multi-surface continuity** — content that moves seamlessly from cluster to centre stack to HUD to phone
- **Zero-learning-curve expectation** — users expect car interfaces to feel as intuitive as their smartphone

---
layout: section
title: 5 Key Technology Trends
---

# 5 key<br>technology trends

---
title: Trend 1 — Multimodal Next-Gen Cockpit
---

<div class="slide-split">
  <div class="split-text">
    <h3>Trend 01</h3>
    <h1>Multimodal<br><span class="accent">next-gen cockpit</span></h1>
    <p>AR overlays, 3D navigation, gesture control, haptic feedback — the cockpit is becoming a spatial computing environment.</p>
    <ul>
      <li>Augmented Reality HUDs projecting navigation onto the road</li>
      <li>3D cluster displays replacing flat gauges</li>
      <li>Haptic surfaces giving tactile confirmation without looking</li>
      <li>Seamless mode switching between driver and passenger contexts</li>
    </ul>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/trend-multimodal.png" />
  </div>
</div>

---
title: Trend 2 — Connectivity & Smart Drive
---

<div class="slide-split">
  <div class="split-text">
    <h3>Trend 02</h3>
    <h1>Connectivity &<br><span class="accent">smart drive</span></h1>
    <p>The car as a platform: always-connected, always-learning, seamlessly integrated with the digital life outside the vehicle.</p>
    <ul>
      <li>AR HUD with real-time POI overlays and lane guidance</li>
      <li>All-in-one super-apps replacing fragmented services</li>
      <li>Car-to-infrastructure (V2I) — traffic signals, road hazard sharing</li>
      <li>Over-the-air updates that change HMI behaviour post-sale</li>
    </ul>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/trend-connectivity.png" />
  </div>
</div>

---
title: Trend 3 — Intelligent Assistants
---

<div class="slide-split">
  <div class="split-text">
    <h3>Trend 03</h3>
    <h1>AI<br><span class="accent">copilots</span></h1>
    <p>From command execution to proactive partnership — AI agents that understand context, anticipate needs, and act as a trusted companion on every journey.</p>
    <ul>
      <li><strong>NVIDIA DRIVE Concierge</strong> — multimodal AI managing cabin and road simultaneously</li>
      <li><strong>Cerence Co-Pilot</strong> — predictive suggestions, repair alerts, energy management</li>
      <li><strong>NIO NOMI</strong> — transforms the car "from a cold machine to a delightful companion"</li>
    </ul>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/trend-ai.png" />
  </div>
</div>

---
title: Trend 4 — Entertainment & Gamification
---

<div class="slide-split">
  <div class="split-text">
    <h3>Trend 04</h3>
    <h1>Entertainment &<br><span class="accent">gamification</span></h1>
    <p>Gamified HMI encourages users to explore car features and take full advantage of embedded technology — turning waiting time into engagement.</p>
    <ul>
      <li><strong>Audi Holoride</strong> — in-cabin VR content synced to the vehicle's live motion</li>
      <li><strong>WayRay Holograktor</strong> — AR windshield for navigation and infotainment</li>
      <li><strong>Ford</strong> — Escape Room concept for parked-vehicle entertainment</li>
    </ul>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/trend-entertainment.png" />
  </div>
</div>

---
title: Trend 5 — EV & Charging UX
---

<div class="slide-split">
  <div class="split-text">
    <h3>Trend 05</h3>
    <h1>EV &<br><span class="accent">charging UX</span></h1>
    <p>Electrification introduces entirely new HMI design territory — range anxiety, charging logistics, and energy management are emotional as much as functional problems.</p>
    <ul>
      <li><strong>Plug & Charge</strong> (ISO 15118) — automatic authentication, no card or app required</li>
      <li><strong>Google Maps EV routing</strong> — charging stops integrated into navigation</li>
      <li>Energy flow visualisations replacing traditional fuel gauges</li>
      <li>Preconditioning HMI — remote climate prep before departure</li>
    </ul>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/trend-ev.png" />
  </div>
</div>

---
layout: section
title: 8 Design Principles
---

# 8 design<br>principles

---
title: The 8 Principles — Overview
---

<div class="slide-principles">
  <h3>Design principles</h3>
  <h1>Eight principles for <span class="accent">great HMI</span></h1>
  <div class="principles-grid">
    <div class="principle-item"><span class="pn">01</span><span class="pt">Give users a sense of control</span></div>
    <div class="principle-item"><span class="pn">02</span><span class="pt">Safety first</span></div>
    <div class="principle-item"><span class="pn">03</span><span class="pt">Minimise cognitive load</span></div>
    <div class="principle-item"><span class="pn">04</span><span class="pt">Reduce unnecessary distraction</span></div>
    <div class="principle-item"><span class="pn">05</span><span class="pt">Support the daily routine</span></div>
    <div class="principle-item"><span class="pn">06</span><span class="pt">Self-evident navigation</span></div>
    <div class="principle-item"><span class="pn">07</span><span class="pt">The system constantly learns</span></div>
    <div class="principle-item"><span class="pn">08</span><span class="pt">Inviting visual language</span></div>
  </div>
</div>

---
title: Principle 1 — Sense of Control
---

<div class="slide-split">
  <div class="split-text">
    <h3>Principle 01</h3>
    <h1>Give users a<br><span class="accent">sense of control</span></h1>
    <p>Every action must produce a visible, audible, or haptic response. Users should always know the system received their input and what it will do next.</p>
    <ul>
      <li>No actions with consequences should be taken without informing the user</li>
      <li>Confirm inputs immediately — do not make users wonder if it worked</li>
      <li>Provide progress indicators for operations that take time</li>
      <li>Always offer a clear way to cancel or undo</li>
    </ul>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/case-mbux.png" />
  </div>
</div>

---
title: Example · Principle 01
---

<!-- Alternatives scouted: Audi Virtual Cockpit — live state changes glow on every input; Mercedes-Benz MBUX voice acknowledgement chime — every voice command confirmed with a distinct tone; Rivian Adventure Network charge confirmation — animated progress ring on both in-car display and phone simultaneously; BMW cancel/undo always accessible from any screen depth -->
<div class="slide-split">
  <div class="split-text">
    <h3>Example · Principle 01</h3>
    <h1>BMW iDrive<br><span class="accent">haptic touchpad</span></h1>
    <p>Every touch on the iDrive touchpad returns a simultaneous triple response: a physical click, a visual highlight on the central display, and a brief audio tone. The user never wonders if the system received their input.</p>
    <ul>
      <li><strong>Multi-modal confirmation</strong> — haptic + visual + audio fire together, each reinforcing the others</li>
      <li><strong>No silent actions</strong> — every input acknowledged; long-press actions show a fill-progress indicator before executing</li>
      <li><strong>Always a way out</strong> — the physical back button is reachable from every screen state without navigating menus</li>
    </ul>
    <div class="example-alts">
      <div class="alt-label">Also consider</div>
      <div class="alt-items">— Audi Virtual Cockpit — input highlight glows on every button press<br>— MBUX voice acknowledgement chime — distinct tone confirms every command<br>— Rivian charge progress ring — animated confirmation on display and phone simultaneously</div>
    </div>
    <div class="example-source">Image: BMW Vision iNEXT haptic controls · BMW Group PressClub</div>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/example-p1-control.png" />
  </div>
</div>

---
title: Principle 2 — Safety First
---

<div class="slide-split">
  <div class="split-text">
    <h3>Principle 02</h3>
    <h1>Safety<br><span class="accent">first</span></h1>
    <p>Safety is not a constraint on design — it is a design material. Every interaction decision must account for the driving context.</p>
    <ul>
      <li><strong>Reactive</strong> — responds only when the user acts</li>
      <li><strong>Proactive</strong> — anticipates needs and surfaces information before being asked</li>
    </ul>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.6);">A good notification must be <strong style="color: #fff;">Valuable</strong>, <strong style="color: #fff;">Timely</strong>, and <strong style="color: #fff;">Clear</strong>. If it doesn't meet all three, don't show it.</p>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/principle-safety.png" />
  </div>
</div>

---
title: Example · Principle 02
---

<!-- Alternatives scouted: Euro NCAP Distraction Testing Protocol 2024 — scores manufacturers on UI complexity at speed; NHTSA 2-second glance guideline; Apple CarPlay Driving Focus Mode — limits notification types while connected; Volvo Care Key — speed-limited profile for secondary drivers -->
<div class="slide-split">
  <div class="split-text">
    <h3>Example · Principle 02</h3>
    <h1>Volvo EX90<br><span class="accent">contextual UI</span></h1>
    <p>Volvo locks down the media and settings interface when the vehicle exceeds 7 km/h — only safety-critical and navigation functions remain fully accessible. The design treats speed as a permission layer.</p>
    <ul>
      <li><strong>Speed-sensitive UI</strong> — information complexity automatically scales with driving speed</li>
      <li><strong>Safety-critical always-on</strong> — emergency call, navigation, and hands-free phone are never restricted</li>
      <li><strong>Regulatory grounding</strong> — NHTSA and Euro NCAP recommendations built into the interaction architecture, not retrofitted</li>
    </ul>
    <div class="example-alts">
      <div class="alt-label">Also consider</div>
      <div class="alt-items">— Euro NCAP Distraction Protocol 2024 — scores UI complexity at speed<br>— NHTSA 2-second visual demand guideline — legal benchmark<br>— Apple CarPlay Driving Focus — limits notification types while moving</div>
    </div>
    <div class="example-source">Image: Volvo EX90 contextual UI at speed · Motor Authority / Volvo press</div>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/example-p2-safety.jpg" />
  </div>
</div>

---
title: Principles 3 & 4 — Cognitive Load & Distraction
---

<div class="slide-two-principles">
  <div class="two-p-item">
    <h3>Principle 03</h3>
    <h2>Minimise cognitive<br><span class="accent">load</span></h2>
    <ul>
      <li>Don't force users to memorise — display information where it's needed</li>
      <li>Leverage existing mental models from smartphones and everyday objects</li>
      <li>Chunk complex information into digestible units</li>
      <li>Consistent patterns reduce the cost of learning</li>
    </ul>
  </div>
  <div class="two-p-divider"></div>
  <div class="two-p-item">
    <h3>Principle 04</h3>
    <h2>Reduce unnecessary<br><span class="accent">distraction</span></h2>
    <ul>
      <li>1.6 million crashes per year are caused by phone distraction (US NHTSA)</li>
      <li>Voice should be the primary interaction medium while driving</li>
      <li>Show only what the driver needs now — progressive disclosure for everything else</li>
      <li>Limit notifications during active driving</li>
    </ul>
  </div>
</div>

---
title: Example · Principle 03
---

<!-- Alternatives scouted: Mercedes MBUX Zero-Layer adaptive home screen — context-aware surface of top 3 functions; Audi e-tron cluster simplification — removed 40% of data points vs previous gen; Apple visionOS layered information model as reference for spatial hierarchy -->
<div class="slide-split">
  <div class="split-text">
    <h3>Example · Principle 03</h3>
    <h1>BMW Panoramic<br><span class="accent">iDrive 2025</span></h1>
    <p>BMW's 2025 cockpit rearchitects the instrument cluster and head unit as a single continuous information canvas — but enforces strict visual zones that prevent data from one domain bleeding into another.</p>
    <ul>
      <li><strong>Zone separation</strong> — driving data, navigation, and entertainment each in dedicated, non-overlapping regions</li>
      <li><strong>Familiar mental models</strong> — tile-based layout maps directly to smartphone home screen patterns users already know</li>
      <li><strong>Progressive disclosure</strong> — detail expands on demand; summary always visible in peripheral view</li>
    </ul>
    <div class="example-alts">
      <div class="alt-label">Also consider</div>
      <div class="alt-items">— Mercedes MBUX Zero-Layer — context-aware surface of top 3 actions<br>— Audi e-tron cluster — 40% fewer data points vs previous generation<br>— Apple visionOS layered hierarchy — spatial model for progressive detail</div>
    </div>
    <div class="example-source">Image: BMW Panoramic Vision iDrive 2025 · BMW Group PressClub</div>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/example-p3-cogload.jpg" />
  </div>
</div>

---
title: Example · Principle 04
---

<!-- Alternatives scouted: UNECE WP.29 Regulation 79 — regulatory limit on secondary task interaction time while moving; Google/AAA glance duration research (2013–2020); Volvo voice-only driving mode on EX90; NHTSA 2-second visual demand guideline -->
<div class="slide-split">
  <div class="split-text">
    <h3>Example · Principle 04</h3>
    <h1>DS Aero Sport<br><span class="accent">voice-first cabin</span></h1>
    <p>DS designs the Aero Sport Lounge cabin around voice-first interaction — 80% of in-motion controls are accessed without touching a screen, with ambient lighting cues replacing visual confirmations that demand a direct look.</p>
    <ul>
      <li><strong>No screen-touch while moving</strong> — all non-critical controls route through voice or steering wheel</li>
      <li><strong>Ambient surface feedback</strong> — subtle lighting pulses replace on-screen notifications</li>
      <li><strong>Regulatory grounding</strong> — aligns with UNECE WP.29 and NHTSA 2-second visual demand guidelines</li>
    </ul>
    <div class="example-alts">
      <div class="alt-label">Also consider</div>
      <div class="alt-items">— NHTSA 2-second rule — legal benchmark for acceptable glance duration<br>— UNECE WP.29 Reg. 79 — EU distraction limits for in-motion UI<br>— Volvo EX90 voice-only mode — locks screen; voice handles everything</div>
    </div>
    <div class="example-source">Image: DS Aero Sport Lounge gesture control · DS Automobiles press materials</div>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/example-p4-distraction.png" />
  </div>
</div>

---
title: Principle 5 — Support Daily Routine
---

<div class="slide-split">
  <div class="split-text">
    <h3>Principle 05</h3>
    <h1>Support the<br><span class="accent">daily routine</span></h1>
    <p>Most driving is habitual. HMI should smooth the routine rather than interrupt it — while staying discoverable when users need something new.</p>
    <ul>
      <li>Use the "How Might We…" technique to identify friction points in daily use</li>
      <li><strong>Skills</strong> — discrete HMI functions that can be triggered manually by the driver or automatically by the system (e.g. auto-playing a driving playlist)</li>
      <li>Design for the habitual case first; the edge case second</li>
    </ul>
  </div>
  <div class="split-image">
    <img src="/images/shared/placeholder-wide.svg" />
  </div>
</div>

---
title: Example · Principle 05
---

<!-- Alternatives scouted: Google Assistant Driving Mode — predictive route suggestions based on calendar events; Apple Siri Suggestions on CarPlay — shortcuts surfaced at the right time; BMW Intelligent Personal Assistant habit-learning over 30-day windows; Spotify Car View auto-launch on Bluetooth connect -->
<div class="slide-split">
  <div class="split-text">
    <h3>Example · Principle 05</h3>
    <h1>Cerence<br><span class="accent">Co-Pilot</span></h1>
    <p>Cerence Co-Pilot monitors driving behaviour, upcoming conditions, and calendar data to surface proactive suggestions — without the driver asking. It is the distinction between a system that reacts and one that participates.</p>
    <ul>
      <li><strong>Context-aware Skills</strong> — charging reminders triggered by range + destination, not just low battery</li>
      <li><strong>Routine learning</strong> — after 3 repetitions, morning commute route and playlist are auto-loaded</li>
      <li><strong>Non-intrusive delivery</strong> — suggestions appear as glanceable cards, never as blocking dialogs</li>
    </ul>
    <div class="example-alts">
      <div class="alt-label">Also consider</div>
      <div class="alt-items">— Google Assistant Driving Mode — calendar-aware route prediction<br>— BMW IPA — habit learning over 30-day rolling window<br>— Spotify Car View — auto-launches on Bluetooth connect, zero steps</div>
    </div>
    <div class="example-source">Image: Cerence Co-Pilot proactive UI · Cerence Inc. press materials</div>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/example-p5-routine.png" />
  </div>
</div>

---
title: Principle 6 — Self-Evident Navigation
---

<div class="slide-split">
  <div class="split-text">
    <h3>Principle 06</h3>
    <h1>Self-evident<br><span class="accent">navigation</span></h1>
    <p>The structure of the system should be immediately obvious. Users should never have to search for a feature.</p>
    <ul>
      <li><strong>The Three-Tap Rule</strong> — any feature reachable in ≤ 3 interactions from the home state</li>
      <li>Identify navigation hubs and distribute skills across them logically</li>
      <li>Discoverability must be designed in — not left to user exploration</li>
      <li>Consistent placement: if it was there yesterday, it must be there today</li>
    </ul>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/principle-navigation.jpg" />
  </div>
</div>

---
title: Example · Principle 06
---

<!-- Alternatives scouted: BMW iDrive 8 menu depth audit — 7-series vs 5-series simplification study; Mercedes MBUX 2.0 Swipe-Up Quick Nav; Volvo bottom-bar navigation pattern on Google AAOS; Ford Sync 4 App Link with one-tap recents -->
<div class="slide-split">
  <div class="split-text">
    <h3>Example · Principle 06</h3>
    <h1>Tesla Model 3<br><span class="accent">navigation UX</span></h1>
    <p>Tesla consolidates the entire vehicle into a single 15.4″ touchscreen with a persistent home state. Every function is reachable in ≤ 3 taps from any screen — not as a design target, but as an enforced constraint of the information architecture.</p>
    <ul>
      <li><strong>Single navigation hub</strong> — no multi-level menus; every function branches from one starting point</li>
      <li><strong>Three-tap rule enforced by IA</strong> — not a guideline but a structural guarantee</li>
      <li><strong>Persistent edge controls</strong> — volume, climate, and drive mode are always visible at screen bottom</li>
    </ul>
    <div class="example-alts">
      <div class="alt-label">Also consider</div>
      <div class="alt-items">— BMW iDrive 8 — menu depth reduced from 6 to 3 levels between 2018–2022<br>— Volvo AAOS bottom-bar — consistent tab navigation matching smartphone convention<br>— Mercedes MBUX Swipe-Up — contextual quick-nav from anywhere in the UI</div>
    </div>
    <div class="example-source">Image: Tesla Model 3 interior · Wikimedia Commons CC BY-SA 4.0</div>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/example-p6-navigation.jpg" />
  </div>
</div>

---
title: Principle 7 — Learn & Personalise
---

<div class="slide-split">
  <div class="split-text">
    <h3>Principle 07</h3>
    <h1>Learn &<br><span class="accent">personalise</span></h1>
    <p>A system that learns from its user delivers better value over time. But there is an important distinction:</p>
    <ul>
      <li><strong>Customisation</strong> — the user manually adjusts settings. Most users never do this.</li>
      <li><strong>Personalisation</strong> — the system learns preferences automatically and adapts without asking.</li>
    </ul>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.6);">The sad fact is that many modern HMI offer customisation and call it personalisation.</p>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/example-p7-personalise.png" />
  </div>
</div>

---
title: Example · Principle 07
---

<!-- Alternatives scouted: NIO NOMI face-recognition on entry — cabin fully configured before the door closes; Mercedes Me profile sync across vehicles; Google Automotive Profiles (Android 12) — multi-user account switching on shared fleet vehicles; Volvo profile sync across app, web, and in-car -->
<div class="slide-split">
  <div class="split-text">
    <h3>Example · Principle 07</h3>
    <h1>BMW Digital Key<br><span class="accent">& BMW ID</span></h1>
    <p>When a driver approaches with their BMW Digital Key, the car silently loads their full profile — seat position, mirror angles, HUD height, favourite radio station, ambient lighting — before they touch anything.</p>
    <ul>
      <li><strong>Identity triggers context</strong> — no "select profile" step; recognition is the interaction</li>
      <li><strong>Silent adaptation</strong> — the car configures itself without announcing it</li>
      <li><strong>True personalisation</strong> — system observes preferred temperature, frequent destinations, and wake-word over time</li>
    </ul>
    <div class="example-alts">
      <div class="alt-label">Also consider</div>
      <div class="alt-items">— NIO NOMI face recognition — cabin configured before the door closes<br>— Google Automotive Profiles — multi-user account switching in fleet cars<br>— Mercedes Me profile sync — consistent identity across all touchpoints</div>
    </div>
    <div class="example-source">Image: BMW Digital Key on iPhone · BMW Group PressClub</div>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/example-p7-personalise.png" />
  </div>
</div>

---
title: Principle 8 — Inviting Visual Language
---

<div class="slide-split">
  <div class="split-text">
    <h3>Principle 08</h3>
    <h1>Inviting<br><span class="accent">visual language</span></h1>
    <p>Aesthetics and functionality are not in tension — they are partners. Users perceive attractive interfaces as more usable.</p>
    <ul>
      <li><strong>Aesthetic-Usability Effect</strong> — beautiful design builds trust and lowers perceived complexity</li>
      <li>Visual language must carry identity and character, not just information</li>
      <li>Designers must build emotion into the interface — the car experience is felt, not just used</li>
    </ul>
  </div>
  <div class="split-image">
    <img src="/images/shared/placeholder-wide.svg" />
  </div>
</div>

---
title: Example · Principle 08
---

<!-- Alternatives scouted: Genesis GV80 cluster — cinematic 12.3" ratio with custom iconography; BMW OS9 curved display light architecture (ambient glow as spatial guide); NIO ambient blue-tinted UI identity; Audi e-tron GT instrument cluster — Solarflare Orange accent system -->
<div class="slide-split">
  <div class="split-text">
    <h3>Example · Principle 08</h3>
    <h1>Polestar 2<br><span class="accent">Android Automotive</span></h1>
    <p>Polestar ships with Android Automotive OS — a consistent design language, familiar Google-native typography, and an app ecosystem that feels at home to any user who has ever held a smartphone.</p>
    <ul>
      <li><strong>Aesthetic-Usability Effect</strong> — clean, familiar UI reduces perceived complexity and lowers onboarding friction to near zero</li>
      <li>Visual restraint as brand identity — monochrome icon set and tight grid reflect Polestar's precision character</li>
      <li>Typography as hierarchy — weight and scale alone establish reading order at a glance, no colour needed</li>
    </ul>
    <div class="example-alts">
      <div class="alt-label">Also consider</div>
      <div class="alt-items">— Genesis GV80 cluster — cinematic 12.3" ratio, custom icon family<br>— BMW OS9 curved display — ambient glow as a spatial navigation guide<br>— NIO ambient UI — blue-tinted identity fused with functional states</div>
    </div>
    <div class="example-source">Image: Polestar 2 Android Automotive interior · Wikimedia Commons CC BY-SA 3.0</div>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/example-p8-visual.jpg" />
  </div>
</div>

---
title: Pyramid of User Needs
---

<div class="slide-pyramid-layout">
  <div class="pyramid-text">
    <h3>Framework</h3>
    <h1>Pyramid of<br><span class="accent">user needs</span></h1>
    <p>Every design decision should climb this pyramid. Functional must come before pleasurable — but pleasurable is what users remember.</p>
    <p style="font-size: 0.82rem; color: rgba(232,234,240,0.6); margin-top: 0.5rem;">Artistry and functionality should be equals, working together in perfect harmony to immerse users in the experience.</p>
  </div>
  <div class="pyramid-visual">
    <div class="pyramid-tier" style="width: 38%;"><span>Pleasurable</span></div>
    <div class="pyramid-tier" style="width: 58%;"><span>Usable</span></div>
    <div class="pyramid-tier" style="width: 78%;"><span>Reliable</span></div>
    <div class="pyramid-tier" style="width: 100%;"><span>Functional</span></div>
  </div>
</div>

---
layout: section
title: Case Studies
---

# Case studies

---
title: NIO NOMI — The AI Companion
---

<div class="slide-split">
  <div class="split-text">
    <h3>Case study</h3>
    <h1>NIO <span class="accent">NOMI</span></h1>
    <p>A physical AI presence inside the cabin — a rotating face that looks at you when you speak, expresses emotion, and builds a genuine relationship with the driver over time.</p>
    <ul>
      <li>Transforms the car "from a cold machine to a delightful companion"</li>
      <li>Face tracking — attention and gaze detection built into the companion's form</li>
      <li>Voice-first: designed as the primary interaction medium</li>
      <li>Personality and memory: NOMI remembers preferences, jokes, and routines</li>
    </ul>
    <p style="font-size: 0.75rem; color: rgba(232,234,240,0.5); margin-top: 0.5rem;">Key lesson: <strong style="color: rgba(232,234,240,0.9);">emotion and function are not separate design tracks</strong> — they compound.</p>
  </div>
  <div class="split-image">
    <img src="/images/s_hmi/case-nio-nomi.png" />
  </div>
</div>

---
title: Audi Holoride — In-Cabin VR
---

<!-- ── VIDEO — replace VIDEO_ID with actual YouTube ID for Audi Holoride ── -->
<div class="slide-video">
  <iframe
    src="https://www.youtube.com/embed/VIDEO_ID"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
  />
  <div class="video-caption">
    <span class="video-label">Case study</span>
    <span class="video-title">Audi Holoride — In-Cabin VR Experience</span>
    <span class="video-url">youtube.com/watch?v=VIDEO_ID</span>
  </div>
</div>

---
title: Mercedes-Benz MBUX Hyperscreen
---

<div class="slide-split">
  <div class="split-text">
    <h3>Case study</h3>
    <h1>MBUX<br><span class="accent">Hyperscreen</span></h1>
    <p>A single 141 cm screen stretching the full width of the dashboard — three separate displays unified under one curved glass surface.</p>
    <ul>
      <li>AI-driven adaptive UI — surfaces features based on time, location, and habit</li>
      <li><strong>Zero-layer concept</strong> — most common actions never require a menu</li>
      <li>Passenger screen fully independent from driver screen</li>
      <li>OLED haptic feedback — physical sensation without physical buttons</li>
    </ul>
    <p style="font-size: 0.75rem; color: rgba(232,234,240,0.5); margin-top: 0.5rem;">Key lesson: <strong style="color: rgba(232,234,240,0.9);">the biggest interface is not always the best one</strong> — usability must scale with screen size.</p>
  </div>
  <div class="split-image">
    <img src="/images/shared/placeholder-wide.svg" />
  </div>
</div>

---
layout: quote
title: The Design Challenge
---

"Artistry and functionality should be equals, working together in perfect harmony to immerse users in the experience."

<div class="quote-author">— HMI Design Principle 08</div>

---
layout: end
title: End
---

# See you next session

<div class="end-links">Questions?</div>
