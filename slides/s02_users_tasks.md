---
theme: default
title: S02 — Users, Tasks & HMI Architecture
colorSchema: dark
fonts:
  sans: DM Sans
  mono: DM Mono
  weights: '300,400,500,700'
cssEngine: unocss
routerMode: hash
---

<div class="cover-layout">
  <div class="tag">IED Master Transportation Design · 2025/26</div>
  <h1>Users, Tasks<br><span class="accent">& HMI Architecture</span></h1>
  <div class="subtitle">Session 02 — Interaction Design / Automotive HMI</div>
  <div class="instructor">Lorenzo Romagnoli</div>
</div>

---
layout: section
title: HMI Case Studies
---

# HMI case<br>studies

---
title: Today's Presenters
---

<div class="slide-needs">
  <h3>Case study presentations · 5 min each</h3>
  <h1>Rudi &amp; Leonardo<br><span class="accent">you're up first</span></h1>
  <div class="needs-grid">
    <div class="needs-item">
      <div class="needs-number">01</div>
      <div class="needs-label">Show it</div>
      <div class="needs-body">Videos and images. No slides required. Let the interface speak.</div>
    </div>
    <div class="needs-item">
      <div class="needs-number">02</div>
      <div class="needs-label">Tell us what surprised you</div>
      <div class="needs-body">What made you choose this one? What did you discover that you didn't expect?</div>
    </div>
    <div class="needs-item">
      <div class="needs-number">03</div>
      <div class="needs-label">What would you steal — and what would you fix?</div>
      <div class="needs-body">One clear point of view. A full product review is less valuable than a sharp opinion.</div>
    </div>
  </div>
</div>

---
layout: section
title: Part 1 — Personas
---

# Part 1<br><span class="accent">Personas</span>

---
layout: center
title: The Problem with "The User"
class: text-center
---

# Designing for everyone<br>means designing for <span class="accent">no one</span>.

---
title: Exercise — Draw a Bike
---

<div class="slide-activity">
  <div class="activity-header">
    <h3>Exercise · 2 min</h3>
    <h1>Draw a bike.<br><span class="accent">Any bike.</span></h1>
  </div>
  <div class="activity-steps">
    <div class="activity-step">
      <div class="step-number">01</div>
      <div class="step-body">
        <div class="step-label">Sketch it or find a photo</div>
        <div class="step-hint">Don't overthink it. A quick sketch on paper, a photo on your phone, a doodle on the board. Any bike that comes to mind.</div>
      </div>
    </div>
    <div class="activity-step">
      <div class="step-number">02</div>
      <div class="step-body">
        <div class="step-label">Drop it on the board</div>
        <div class="step-hint">Add it to your section on the FigJam board. One bike per person.</div>
      </div>
    </div>
  </div>
  <div class="board-link">
    <a href="https://www.figma.com/board/mwVmxZB3ZZ4gbWlrSJAChe/Untitled?node-id=0-1&t=kTiXSe7PqwyEuBaz-1" target="_blank">figma.com/board — Session 02</a>
    <span class="board-password">Password: shared by email</span>
  </div>
</div>

---
title: Exercise — Meet the Rider
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Now meet the person</h3>
    <h1>Design a bike<br><span class="accent">for him</span></h1>
    <p><strong>Tom · 31 · Software developer · London</strong></p>
    <ul>
      <li>Lives in a 45m² flat in Hackney. No hallway, no shed, no outdoor storage.</li>
      <li>Works in Canary Wharf. Takes the tube every day — 40 minutes each way.</li>
      <li>The tube station is a 15-minute walk from his flat. He hates that walk. Especially in winter.</li>
      <li>Has tried owning a normal bike twice. Both were stolen within a month.</li>
      <li>Would cycle every day if only he could bring the bike inside — at home, on the tube, under his desk at work.</li>
    </ul>
    <p style="margin-top: 1rem; font-size: 0.95rem; font-weight: 500;">Does your bike still work for Tom?<br>Take 2 minutes — would you change it?</p>
  </div>
</div>

---
title: Exercise — The Answer
---

<div class="slide-split">
  <div class="split-text">
    <h3>The answer · 1975</h3>
    <h1>Brompton <span class="accent">bicycle</span></h1>
    <p>Andrew Ritchie designed it from his flat overlooking the Brompton Oratory in London. He was not designing for the cycling market. He was designing for Tom — the commuter with no storage, a stolen bike in his past, and a 15-minute walk he wanted to eliminate.</p>
    <ul>
      <li><strong>Folds in under 20 seconds</strong> — fits under a desk, in an overhead rack, in a hallway corner</li>
      <li><strong>Stands upright when folded</strong> — doesn't touch your clothes or the floor</li>
      <li><strong>Not fast, not light, not cheap</strong> — optimised for exactly one thing, with no apology for the rest</li>
    </ul>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.6);">Today: a waiting list, sold in 45 countries, beloved by people who have never seen a London tube. <strong>Designed for one person. Relevant to many.</strong></p>
  </div>
  <div class="split-image">
    <img src="/images/s02/brompton-t-line.png" style="width: 100%; height: 100%; object-fit: cover;" />
  </div>
</div>

---
title: Two Different Worlds
---

<div class="slide-case">
  <h3>Context</h3>
  <h1>How personas work<br><span class="accent">depends on the field</span></h1>
  <div class="case-grid" style="grid-template-columns: repeat(3, 1fr)">
    <div class="case-item">
      <div class="case-word">Product innovation</div>
      <div class="case-body">Personas come from deep research — interviews, ethnography, jobs-to-be-done. The problem comes first; the persona describes exactly who has it. Specific, behavioural, built to be argued with.</div>
    </div>
    <div class="case-item">
      <div class="case-word">Automotive market</div>
      <div class="case-body">Cars are designed for millions. Automotive personas are broader — "the confident achiever", "the young family" — defined by marketing as much as research. They guide brand positioning, not individual interaction decisions.</div>
    </div>
    <div class="case-item">
      <div class="case-word">The tension</div>
      <div class="case-body">A persona broad enough to represent a million buyers is too vague to make a single design decision from. It tells you who buys the car — almost nothing about what the HMI should do.</div>
    </div>
  </div>
</div>

---
layout: center
title: Our Approach
class: text-center
---

# In this course we work like<br>product designers, not automotive marketers.<br>One <span class="accent">specific</span> persona.<br>One <span class="accent">sharp</span> point of view.

---
title: Why Specificity Unlocks Creativity
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Our method</h3>
    <h1>Specific personas<br><span class="accent">unlock bolder design</span></h1>
    <p>Designing for a precise, opinionated persona is a constraint — and constraints are where creative thinking happens. When you know exactly who you're designing for, every decision has a clear test.</p>
    <ul>
      <li>A vague persona produces a safe, compromise-heavy HMI. It tries to offend no one and ends up inspiring no one.</li>
      <li>A specific persona forces you to take positions. It lets you say <em>"this feature exists because Fatima needs it"</em> — and therefore justify every choice you make.</li>
      <li>The best automotive HMI of the last decade — iDrive, Tesla, Polestar — were all built on a clear, specific point of view about who the car was for.</li>
    </ul>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.6);">Your persona won't represent everyone who could buy your car. That's exactly the point. Design for one person brilliantly — and you'll likely design something remarkable for many.</p>
  </div>
</div>

---
title: What Is a Persona
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Definition</h3>
    <h1>A persona is<br><span class="accent">a design tool</span></h1>
    <p>A persona is a fictional but research-grounded portrait of a user type. It gives the design team a shared, concrete reference to test decisions against.</p>
    <ul>
      <li>Not a real person — a <strong>composite</strong> of real behaviours and needs</li>
      <li>Not a demographic profile — a <strong>behavioural</strong> portrait</li>
      <li>Not a marketing segment — a <strong>design target</strong></li>
    </ul>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.6);">When you're about to make a design decision, the persona is the voice in the room that asks: <em>"but would I actually use that?"</em></p>
  </div>
</div>

---
title: Why Personas Work
---

<div class="slide-case">
  <h3>Why they work</h3>
  <h1>Four reasons to <span class="accent">use personas</span></h1>
  <div class="case-grid">
    <div class="case-item">
      <div class="case-letter">F</div>
      <div class="case-word">Focus</div>
      <div class="case-body">Every proposal can be tested against one question: would this person actually use it?</div>
    </div>
    <div class="case-item">
      <div class="case-letter">E</div>
      <div class="case-word">Empathy</div>
      <div class="case-body">Shifts the conversation from what we can build to what they actually need.</div>
    </div>
    <div class="case-item">
      <div class="case-letter">A</div>
      <div class="case-word">Alignment</div>
      <div class="case-body">Everyone on the team argues from the same portrait — designer, engineer, strategist.</div>
    </div>
    <div class="case-item">
      <div class="case-letter">P</div>
      <div class="case-word">Priority</div>
      <div class="case-body">Not all tasks are equal. The persona reveals which ones actually matter.</div>
    </div>
  </div>
</div>

---
title: Persona Anti-Patterns
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Caution</h3>
    <h1>How personas<br><span class="accent">go wrong</span></h1>
    <p>Personas are powerful when grounded in observation. They become obstacles when they're invented from assumptions.</p>
    <ul>
      <li><strong>The demographic trap</strong> — "35–45, suburban, two kids" is a marketing slide, not a persona. Behaviour matters, not birthday.</li>
      <li><strong>The wish-list persona</strong> — built to justify decisions already made, not to challenge them.</li>
      <li><strong>The forgotten persona</strong> — printed, laminated, and ignored. A persona only works if you use it.</li>
      <li><strong>One persona to rule them all</strong> — complex products often need two or three distinct types. One composite user erases real differences.</li>
    </ul>
  </div>
</div>

---
title: Automotive Persona Template
---

<div class="slide-principles">
  <h3>Template</h3>
  <h1>The automotive persona <span class="accent">portrait</span></h1>
  <div class="principles-grid">
    <div class="principle-item"><span class="pn">01</span><span class="pt">Name + photo — make them real, not generic</span></div>
    <div class="principle-item"><span class="pn">02</span><span class="pt">Role & life context — job, commute, lifestyle snapshot</span></div>
    <div class="principle-item"><span class="pn">03</span><span class="pt">Driving context — when, where, how far, how often</span></div>
    <div class="principle-item"><span class="pn">04</span><span class="pt">Goals — what does a perfect drive look like for them?</span></div>
    <div class="principle-item"><span class="pn">05</span><span class="pt">Frustrations — what makes driving and the current HMI annoying?</span></div>
    <div class="principle-item"><span class="pn">06</span><span class="pt">Tech comfort — their relationship with screens, apps, voice assistants</span></div>
    <div class="principle-item"><span class="pn">07</span><span class="pt">Car relationship — is the car a tool or a pleasure? Status or utility?</span></div>
    <div class="principle-item"><span class="pn">08</span><span class="pt">Key quote — one sentence they might actually say</span></div>
  </div>
</div>

---
layout: center
title: Four Examples
class: text-center
---

# Four personas.<br>Each one exposes a <span class="accent">blind spot</span><br>in standard HMI design.

---
title: Persona Example — Sandro
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Persona example 01</h3>
    <h1>Meet <span class="accent">Sandro</span></h1>
    <p><strong>52 · Mechanical engineer · Turin</strong><br>Owns three cars — two of which have no screens at all. Drives his daily Alfa Romeo Giulia like it owes him something. Has physically taped over the lane departure warning light because the blinking "ruins the vibe".</p>
    <ul>
      <li><strong>Goals</strong> — maximum driver feedback, zero digital interference. The car should amplify him, not second-guess him.</li>
      <li><strong>Frustrations</strong> — the driving mode resets to Comfort every time he starts the car. The automatic parking assist activates when he doesn't ask for it. The voice assistant re-routed him once; it has not been forgiven.</li>
      <li><strong>Tech comfort</strong> — understands every system better than the dealership does. Deliberately ignores most of them.</li>
      <li><strong>Key quote</strong> — "I don't need the car to think for me. I need it to get out of my way."</li>
    </ul>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.6);"><strong>The blind spot:</strong> HMI is designed assuming drivers need help. Sandro is better than the system — and the system won't accept that.</p>
  </div>
</div>

---
title: Persona Example — Jake
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Persona example 02</h3>
    <h1>Meet <span class="accent">Jake</span></h1>
    <p><strong>24 · Game developer · Eindhoven</strong><br>Has 2,400 hours in Gran Turismo and a full sim rig in his bedroom. Just got his first real car — a used Golf GTI — and immediately started looking for a way to unlock the hidden telemetry menu.</p>
    <ul>
      <li><strong>Goals</strong> — treat the car as a data-rich platform he can configure like a gaming peripheral. Custom HUD, remapped steering wheel buttons, live tire and brake temps.</li>
      <li><strong>Frustrations</strong> — the car has sensors for everything but shows him almost nothing. The cluster is locked to factory layouts. He knows what brake bias means and the car won't tell him his own.</li>
      <li><strong>Tech comfort</strong> — off the charts. He has already modded the infotainment firmware. Twice.</li>
      <li><strong>Key quote</strong> — "It's my car. Why can't I see my own data?"</li>
    </ul>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.6);"><strong>The blind spot:</strong> OEMs lock down the interface to protect the brand. Jake treats that as a challenge.</p>
  </div>
</div>

---
title: Persona Example — Nadia
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Persona example 03</h3>
    <h1>Meet <span class="accent">Nadia</span></h1>
    <p><strong>31 · Marketing manager · Madrid</strong><br>Chronically twelve minutes late to everything. Enters the car already stressed, sets navigation before the seatbelt is on, and is on a voice call before she's left the garage. Has 23 unread messages she will "check at the next red light".</p>
    <ul>
      <li><strong>Goals</strong> — squeeze six things into the drive. Confirm the 10am, reply to the client, find a parking spot, not die.</li>
      <li><strong>Frustrations</strong> — navigation interrupts her calls. The message preview disappears before she can read it. CarPlay takes 40 seconds to connect and she does not have 40 seconds.</li>
      <li><strong>Tech comfort</strong> — very high. That's part of the problem.</li>
      <li><strong>Key quote</strong> — "I can multitask. I've been doing it for years."</li>
    </ul>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.6);"><strong>The blind spot:</strong> the HMI is supposed to reduce distraction. For Nadia it actively enables it — and she'll tell you that's a feature.</p>
  </div>
</div>

---
title: Persona Example — Fatima
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Persona example 04</h3>
    <h1>Meet <span class="accent">Fatima</span></h1>
    <p><strong>58 · Home carer · London</strong><br>Shares a family car with her husband and two adult children. She drives it the most — school pickups for grandchildren, weekly groceries, hospital appointments — but has never once set up her own profile.</p>
    <ul>
      <li><strong>Goals</strong> — reliable transport without having to fight the interface. She just needs it to work.</li>
      <li><strong>Frustrations</strong> — the seat and mirrors are always in her husband's position. The navigation history is full of destinations she doesn't recognise. The language is set to a dialect she finds unnatural. Personalisation requires seven steps she has never bothered with.</li>
      <li><strong>Tech comfort</strong> — confident with her phone. Disengaged from the car's system because it has never once felt like hers.</li>
      <li><strong>Key quote</strong> — "I just move the seat and get on with it."</li>
    </ul>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.6);"><strong>The blind spot:</strong> the most frequent driver in the household is completely invisible to the system.</p>
  </div>
</div>

---
title: Homework Review
---

<div class="slide-activity">
  <div class="activity-header">
    <h3>Round the room · 2 min each</h3>
    <h1>Your car.<br><span class="accent">Your driver.</span></h1>
  </div>
  <div class="activity-steps">
    <div class="activity-step">
      <div class="step-number">01</div>
      <div class="step-body">
        <div class="step-label">Share your pitch</div>
        <div class="step-hint">The car, the driver, the one thing wrong with the current HMI. Two sentences — same as last week.</div>
      </div>
    </div>
    <div class="activity-step">
      <div class="step-number">02</div>
      <div class="step-body">
        <div class="step-label">Now test it as a persona</div>
        <div class="step-hint">Is your customer a behaviour or just a demographic? Do you know their frustration? Can you write their key quote? You just learned what a proper persona looks like — does your pitch pass?</div>
      </div>
    </div>
    <div class="activity-step">
      <div class="step-number">03</div>
      <div class="step-body">
        <div class="step-label">Listen to everyone else</div>
        <div class="step-hint">You're about to form pairs. Pay attention — whose direction resonates with yours?</div>
      </div>
    </div>
  </div>
</div>

---
title: Form Your Groups
---

<div class="slide-activity">
  <div class="activity-header">
    <h1>Form your<br><span class="accent">pairs</span></h1>
  </div>
  <div class="activity-steps">
    <div class="activity-step">
      <div class="step-number">01</div>
      <div class="step-body">
        <div class="step-label">Find someone whose project interests you</div>
        <div class="step-hint">A direction that resonates with yours — or creates an interesting contrast — is a good start.</div>
      </div>
    </div>
    <div class="activity-step">
      <div class="step-number">02</div>
      <div class="step-body">
        <div class="step-label">Agree on a shared direction</div>
        <div class="step-hint">Decide whose vehicle concept to develop, or find a new one. One persona, one journey, built together.</div>
      </div>
    </div>
    <div class="activity-step">
      <div class="step-number">03</div>
      <div class="step-body">
        <div class="step-label">Tell us your pair and your direction</div>
        <div class="step-hint">Drop your names and one sentence on the board — that's your project commitment for the rest of the course.</div>
      </div>
    </div>
  </div>
  <div class="board-link">
    <a href="https://www.figma.com/board/mwVmxZB3ZZ4gbWlrSJAChe/Untitled?node-id=0-1&t=kTiXSe7PqwyEuBaz-1" target="_blank">figma.com/board — Session 02</a>
    <span class="board-password">Password: shared by email</span>
  </div>
</div>

---
layout: center
title: Persona to Journey
class: text-center
---

# A persona tells you <span class="accent">who</span>.<br>A journey map tells you <span class="accent">when</span> —<br>and what the HMI needs to do at every step.

---
title: What Is a Journey Map
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Method</h3>
    <h1>The user<br><span class="accent">journey map</span></h1>
    <p>A journey map traces the persona through a real experience over time — capturing every moment of action, decision, emotion, and HMI interaction from start to finish.</p>
    <ul>
      <li>Not a feature list — a <strong>narrative with a timeline</strong></li>
      <li>Not an ideal flow — a realistic description of <strong>what actually happens</strong>, friction included</li>
      <li>Each HMI touchpoint in the journey is a task waiting to be designed</li>
    </ul>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.6);">The journey is where the persona becomes useful. Without it, the persona is a portrait. With it, it's a design tool.</p>
  </div>
</div>

---
title: The Five Driving Phases
---

<div class="slide-principles">
  <h3>Journey phases</h3>
  <h1>Five phases of <span class="accent">every drive</span></h1>
  <div class="principles-grid">
    <div class="principle-item"><span class="pn">01</span><span class="pt">Pre-drive — destination planning, charging check, route comparison. Often done from the phone before entering the car.</span></div>
    <div class="principle-item"><span class="pn">02</span><span class="pt">Start-up — entering the car, profile loading, navigation confirmation, connecting the phone, adjusting seat and mirrors.</span></div>
    <div class="principle-item"><span class="pn">03</span><span class="pt">In-drive — the highest-stakes phase. Only glanceable, voice-triggered, or steering-wheel interactions are safe.</span></div>
    <div class="principle-item"><span class="pn">04</span><span class="pt">Stop / Pause — traffic, charging, parking. The screen unlocks; more complex interactions become available.</span></div>
    <div class="principle-item"><span class="pn">05</span><span class="pt">Arrival — parking assist, locking, trip summary, companion app handoff. The drive ends but the HMI conversation continues.</span></div>
  </div>
</div>

---
title: Journey Map Template
---

<div class="slide-jmap">
  <h3>Method · User Journey Map</h3>
  <h1>Journey map <span class="accent">template</span></h1>
  <div class="jmap-table">
    <div class="jmap-corner"></div>
    <div class="jmap-phase-header">01 · Pre-drive</div>
    <div class="jmap-phase-header">02 · Start-up</div>
    <div class="jmap-phase-header">03 · In-drive</div>
    <div class="jmap-phase-header">04 · Stop / Pause</div>
    <div class="jmap-phase-header">05 · Arrival</div>
    <div class="jmap-row-label">Actions</div>
    <div class="jmap-cell empty">What does the user do?</div>
    <div class="jmap-cell empty">What does the user do?</div>
    <div class="jmap-cell empty">What does the user do?</div>
    <div class="jmap-cell empty">What does the user do?</div>
    <div class="jmap-cell empty">What does the user do?</div>
    <div class="jmap-row-label">Emotions &amp; Thoughts</div>
    <div class="jmap-cell emotion empty">How do they feel? What are they thinking?</div>
    <div class="jmap-cell emotion empty">How do they feel? What are they thinking?</div>
    <div class="jmap-cell emotion empty">How do they feel? What are they thinking?</div>
    <div class="jmap-cell emotion empty">How do they feel? What are they thinking?</div>
    <div class="jmap-cell emotion empty">How do they feel? What are they thinking?</div>
    <div class="jmap-row-label">Opportunities</div>
    <div class="jmap-cell opportunity empty">What could the HMI do better?</div>
    <div class="jmap-cell opportunity empty">What could the HMI do better?</div>
    <div class="jmap-cell opportunity empty">What could the HMI do better?</div>
    <div class="jmap-cell opportunity empty">What could the HMI do better?</div>
    <div class="jmap-cell opportunity empty">What could the HMI do better?</div>
    <div class="jmap-row-label">Critical Points</div>
    <div class="jmap-cell critical empty">Where does it break down?</div>
    <div class="jmap-cell critical empty">Where does it break down?</div>
    <div class="jmap-cell critical empty">Where does it break down?</div>
    <div class="jmap-cell critical empty">Where does it break down?</div>
    <div class="jmap-cell critical empty">Where does it break down?</div>
    <div class="jmap-row-label">Touchpoints</div>
    <div class="jmap-cell touchpoint empty">Which HMI surface?</div>
    <div class="jmap-cell touchpoint empty">Which HMI surface?</div>
    <div class="jmap-cell touchpoint empty">Which HMI surface?</div>
    <div class="jmap-cell touchpoint empty">Which HMI surface?</div>
    <div class="jmap-cell touchpoint empty">Which HMI surface?</div>
  </div>
</div>

---
title: Journey Map — Fatima
---

<div class="slide-jmap">
  <h3>Worked example · Fatima</h3>
  <h1>The school run <span class="accent">journey map</span></h1>
  <div class="jmap-table">
    <div class="jmap-corner"></div>
    <div class="jmap-phase-header">01 · Pre-drive</div>
    <div class="jmap-phase-header">02 · Start-up</div>
    <div class="jmap-phase-header">03 · In-drive</div>
    <div class="jmap-phase-header">04 · Stop / Pause</div>
    <div class="jmap-phase-header">05 · Arrival</div>
    <div class="jmap-row-label">Actions</div>
    <div class="jmap-cell">Gets in car. Adjusts seat and mirrors from husband's position. 90 seconds lost.</div>
    <div class="jmap-cell">Scans nav history. Types school address from scratch — again.</div>
    <div class="jmap-cell">Tries voice for music. It fails. Drives in silence.</div>
    <div class="jmap-cell">Parks in tight street. Disables unexpected parking assist.</div>
    <div class="jmap-cell">Exits car. No profile saved. Locks vehicle.</div>
    <div class="jmap-row-label">Emotions &amp; Thoughts</div>
    <div class="jmap-cell emotion">😤 "Again?!" — Frustrated, rushed before she's even left the driveway.</div>
    <div class="jmap-cell emotion">😶 "I do this every single day." — Invisible, ignored by her own car.</div>
    <div class="jmap-cell emotion">😑 "Fine. Silence then." — Resigned. Trust in voice already gone.</div>
    <div class="jmap-cell emotion">😧 "What is it doing?!" — Startled. The car acted without her consent.</div>
    <div class="jmap-cell emotion">😐 "Nothing ever changes." — Indifferent. Disengaged from the system.</div>
    <div class="jmap-row-label">Opportunities</div>
    <div class="jmap-cell opportunity">Auto-recognise the driver. Load her profile silently on entry.</div>
    <div class="jmap-cell opportunity">Surface her frequent destinations. One tap to her most common route.</div>
    <div class="jmap-cell opportunity">Remember her station. Adapt voice recognition to her accent over time.</div>
    <div class="jmap-cell opportunity">Offer assistance only when requested. Default to off in familiar areas.</div>
    <div class="jmap-cell opportunity">Learn from each drive. Build her profile incrementally without requiring setup.</div>
    <div class="jmap-row-label">Critical Points</div>
    <div class="jmap-cell critical">90 seconds wasted before she can move. Daily friction, high cost.</div>
    <div class="jmap-cell critical">Manually types the same address every day. System remembers nothing for her.</div>
    <div class="jmap-cell critical">One voice failure = permanent distrust. She will not try again.</div>
    <div class="jmap-cell critical">Unsolicited automation causes fear. Breaks sense of control.</div>
    <div class="jmap-cell critical">Zero learning loop. Every drive resets. Problem is structural, not incidental.</div>
    <div class="jmap-row-label">Touchpoints</div>
    <div class="jmap-cell touchpoint">Seat &amp; mirror controls · Driver profile UI</div>
    <div class="jmap-cell touchpoint">Navigation home screen · Destination search</div>
    <div class="jmap-cell touchpoint">Voice assistant · Media controls · Steering wheel</div>
    <div class="jmap-cell touchpoint">Parking assist UI · ADAS settings</div>
    <div class="jmap-cell touchpoint">Lock screen · Companion app · Profile memory</div>
  </div>
</div>

---
layout: center
title: The Missing Question
class: text-center
---

# The journey tells you what happens.<br>The vision tells you how it <span class="accent">should feel</span>.

---
title: The Experience Vision
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Design north star</h3>
    <h1>The experience<br><span class="accent">vision</span></h1>
    <p>An experience vision is a one-sentence brief for the emotional quality of the product. It answers: how should the persona feel from the moment they enter the car to the moment they lock it?</p>
    <p>Without a vision, design decisions are made feature by feature, with no common thread. With one, every decision can be tested against the same question: <em>does this make them feel that way?</em></p>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.5);">Four brands. Four visions. What do you think they are?</p>
  </div>
</div>

---
title: BMW — Question
---

<div class="slide-fullbleed">
  <img class="fullbleed-img" src="/images/s02/vision-bmw.jpg" />
  <div class="fullbleed-overlay">
    <div class="brand-sub">Experience vision · 01</div>
    <div class="brand-name">BMW</div>
  </div>
</div>

---
title: BMW — Reveal
---

<div class="slide-fullbleed">
  <img class="fullbleed-img" src="/images/s02/vision-bmw.jpg" />
  <div class="fullbleed-overlay">
    <div class="brand-sub">Experience vision · 01</div>
    <div class="brand-name">BMW</div>
    <div class="brand-claim">
      <div class="brand-claim-tag">"Sheer driving pleasure"</div>
      <div class="brand-claim-impl">The HMI should amplify the driver, never distract them. Every interaction is in service of the drive — not the other way around.</div>
    </div>
  </div>
</div>

---
title: Volvo — Question
---

<div class="slide-fullbleed">
  <img class="fullbleed-img" src="/images/s02/vision-volvo.jpg" />
  <div class="fullbleed-overlay">
    <div class="brand-sub">Experience vision · 02</div>
    <div class="brand-name">Volvo</div>
  </div>
</div>

---
title: Volvo — Reveal
---

<div class="slide-fullbleed">
  <img class="fullbleed-img" src="/images/s02/vision-volvo.jpg" />
  <div class="fullbleed-overlay">
    <div class="brand-sub">Experience vision · 02</div>
    <div class="brand-name">Volvo</div>
    <div class="brand-claim">
      <div class="brand-claim-tag">"Safe and calm"</div>
      <div class="brand-claim-impl">The HMI should reduce anxiety, not add to it. Alerts are quiet by default. Complexity is hidden. The car feels like it has everything under control.</div>
    </div>
  </div>
</div>

---
title: Tesla — Question
---

<div class="slide-fullbleed">
  <img class="fullbleed-img" src="/images/s02/vision-tesla.jpg" />
  <div class="fullbleed-overlay">
    <div class="brand-sub">Experience vision · 03</div>
    <div class="brand-name">Tesla</div>
  </div>
</div>

---
title: Tesla — Reveal
---

<div class="slide-fullbleed">
  <img class="fullbleed-img" src="/images/s02/vision-tesla.jpg" />
  <div class="fullbleed-overlay">
    <div class="brand-sub">Experience vision · 03</div>
    <div class="brand-name">Tesla</div>
    <div class="brand-claim">
      <div class="brand-claim-tag">"Effortless and smart"</div>
      <div class="brand-claim-impl">The car should feel like it already knows what you need. Software updates make it better over time. The interface anticipates, rather than reacts.</div>
    </div>
  </div>
</div>

---
title: Range Rover — Question
---

<div class="slide-fullbleed">
  <img class="fullbleed-img" src="/images/s02/vision-rover.jpg" />
  <div class="fullbleed-overlay">
    <div class="brand-sub">Experience vision · 04</div>
    <div class="brand-name">Range Rover</div>
  </div>
</div>

---
title: Range Rover — Reveal
---

<div class="slide-fullbleed">
  <img class="fullbleed-img" src="/images/s02/vision-rover.jpg" />
  <div class="fullbleed-overlay">
    <div class="brand-sub">Experience vision · 04</div>
    <div class="brand-name">Range Rover</div>
    <div class="brand-claim">
      <div class="brand-claim-tag">"Composed luxury"</div>
      <div class="brand-claim-impl">Everything should feel unhurried, precise, and assured. Nothing beeps unnecessarily. Nothing looks cheap. The interface matches the leather.</div>
    </div>
  </div>
</div>

---
title: Fatima's Emotional Arc
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Worked example · Fatima</h3>
    <h1>Current state<br><span class="accent">vs. target</span></h1>
    <p>The gap between how the experience feels today and how it should feel is exactly where the design work lives.</p>
    <div style="font-size: 0.82rem; margin-top: 0.5rem;">
      <div style="display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 0.4rem 0.75rem; margin-bottom: 0.25rem;">
        <span style="color: rgba(232,234,240,0.4); font-size: 0.72rem; text-transform: uppercase; letter-spacing: 0.05em;">Phase</span>
        <span style="color: rgba(232,234,240,0.4); font-size: 0.72rem; text-transform: uppercase; letter-spacing: 0.05em;">Today</span>
        <span style="color: var(--slidev-theme-primary, #a78bfa); font-size: 0.72rem; text-transform: uppercase; letter-spacing: 0.05em;">Vision</span>
      </div>
      <div style="display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 0.4rem 0.75rem; border-top: 1px solid rgba(255,255,255,0.08); padding-top: 0.4rem;">
        <span>Pre-drive</span><span style="color: rgba(232,234,240,0.55);">Irritated — adjusting everything again</span><span>Welcomed — the car already knows her</span>
        <span>Start-up</span><span style="color: rgba(232,234,240,0.55);">Invisible — typing her own address again</span><span>Recognised — her destinations are there</span>
        <span>In-drive</span><span style="color: rgba(232,234,240,0.55);">Resigned — drives in silence</span><span>At home — her preferences, her music</span>
        <span>Stop</span><span style="color: rgba(232,234,240,0.55);">Startled — unwanted assist kicks in</span><span>Supported — only when she wants it</span>
        <span>Arrival</span><span style="color: rgba(232,234,240,0.55);">Indifferent — nothing was learned</span><span>Valued — the car got a little better</span>
      </div>
    </div>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.6);">Fatima's vision in one sentence: <em>"A car that finally knows who I am."</em></p>
  </div>
</div>

---
layout: section
title: Part 2 — User Tasks
---

# Part 2<br><span class="accent">User Tasks</span>

---
layout: center
title: What Is A Task
class: text-center
---

# A task is something<br>the user is trying to <span class="accent">accomplish</span>,<br>not a feature you're trying to build.

---
title: The Driving Task Hierarchy
---

<div class="slide-split">
  <div class="split-text">
    <h3>Framework</h3>
    <h1>Three levels of<br><span class="accent">driving tasks</span></h1>
    <p>All tasks a driver performs can be sorted into three layers. Higher layers demand more attention and cannot be interrupted safely.</p>
    <ul>
      <li><strong>Primary — Driving</strong><br>Steering, braking, acceleration, hazard perception. Always running. Cannot be interrupted. Any HMI that competes with this layer is a safety risk.</li>
      <li><strong>Secondary — Vehicle operation</strong><br>Navigation, ADAS settings, climate, vehicle status. Needed regularly. Should be accessible in one or two glances.</li>
      <li><strong>Tertiary — Comfort & entertainment</strong><br>Music, phone calls, seat massage, POIs. Nice to have. Should be defeatable or voice-triggered.</li>
    </ul>
  </div>
</div>

---
title: Cognitive Load at the Wheel
---

<div class="slide-split">
  <div class="split-text">
    <h3>Why it matters</h3>
    <h1>At 100 km/h<br><span class="accent">you travel 28 m/s</span></h1>
    <p>A two-second glance at a screen covers 56 metres of road without visual input. NHTSA's guideline: no single interaction should require more than two seconds of eyes-off-road time.</p>
    <ul>
      <li><strong>Visual distraction</strong> — eyes off the road</li>
      <li><strong>Manual distraction</strong> — hands off the wheel</li>
      <li><strong>Cognitive distraction</strong> — mind off the drive</li>
    </ul>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.6);">The most dangerous interactions combine all three. Complex touchscreen menus are the textbook example.</p>
  </div>
  <div class="split-image">
    <img src="/images/s02/nhtsa-glance.jpg" />
    <div class="split-caption">NHTSA glance duration study · eyes-off-road risk curve</div>
  </div>
</div>

---
title: Frequency × Criticality Matrix
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Prioritisation tool</h3>
    <h1>Frequency ×<br><span class="accent">Criticality</span></h1>
    <p>Not all tasks deserve the same access. Map every task on two axes to decide where and how it should surface.</p>
    <ul>
      <li><strong>High frequency + High criticality</strong><br>→ Always visible. Cluster and/or HUD. Maximum one tap or one voice command.</li>
      <li><strong>High frequency + Low criticality</strong><br>→ Easy to reach but not intrusive. Persistent media controls, quick-access strip.</li>
      <li><strong>Low frequency + High criticality</strong><br>→ Prominent but not constant. Emergency contacts, hazard lights, eCall.</li>
      <li><strong>Low frequency + Low criticality</strong><br>→ Buried in settings. Fine to require navigation.</li>
    </ul>
  </div>
</div>

---
title: The 6 Task Domains
---

<div class="slide-case">
  <h3>Task domains</h3>
  <h1>Six domains of <span class="accent">driver tasks</span></h1>
  <div class="case-grid">
    <div class="case-item">
      <div class="case-word">Driving</div>
      <div class="case-body">Speed, heading, gear, driving modes, ADAS engagement, lane position</div>
    </div>
    <div class="case-item">
      <div class="case-word">Navigation</div>
      <div class="case-body">Route planning, turn guidance, traffic, POIs, charging stops</div>
    </div>
    <div class="case-item">
      <div class="case-word">Comfort</div>
      <div class="case-body">Climate, seat, ambient lighting, privacy glass, air quality</div>
    </div>
    <div class="case-item">
      <div class="case-word">Media</div>
      <div class="case-body">Music, podcasts, radio, streaming, volume, EQ</div>
    </div>
    <div class="case-item">
      <div class="case-word">Phone</div>
      <div class="case-body">Calls, messages, notifications, contacts, CarPlay / Android Auto</div>
    </div>
    <div class="case-item">
      <div class="case-word">Vehicle</div>
      <div class="case-body">Tyre pressure, range, charging status, maintenance alerts, door locks</div>
    </div>
  </div>
</div>

---
title: Building a Task Inventory
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Method</h3>
    <h1>Task<br><span class="accent">inventory</span></h1>
    <p>A task inventory is a structured list of every task your persona might perform in a drive. It is the foundation of your HMI architecture.</p>
    <p><strong>How to build one:</strong></p>
    <ul>
      <li>Start from a journey: morning commute, long trip, parking in an unfamiliar city</li>
      <li>List every interaction moment, however small</li>
      <li>Tag each task with its domain, frequency, and criticality level</li>
      <li>Expect 20–40 tasks for a realistic single persona</li>
    </ul>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.6);">A task inventory is not a feature list. "Set climate to 21°C" is a task. "Climate control system" is a feature.</p>
  </div>
</div>

---
layout: center
title: Journey to Tasks
class: text-center
---

# Every friction point in the journey<br>is a design <span class="accent">opportunity</span>.<br>Every touchpoint is a task to prioritise.

---
title: From Journey Moment to Task
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>The extraction</h3>
    <h1>Journey moments<br><span class="accent">become tasks</span></h1>
    <p>Each HMI moment in the journey is a task in disguise. Reading the journey carefully surfaces not just what happens — but how often, how critical, and how badly the current system handles it.</p>
    <div style="font-size: 0.78rem; margin-top: 0.75rem;">
      <div style="display: grid; grid-template-columns: 1.6fr 1fr 1fr 1fr; gap: 0.35rem 0.6rem; margin-bottom: 0.3rem;">
        <span style="color: rgba(232,234,240,0.4); font-size: 0.7rem; text-transform: uppercase; letter-spacing: 0.05em;">Journey moment</span>
        <span style="color: rgba(232,234,240,0.4); font-size: 0.7rem; text-transform: uppercase; letter-spacing: 0.05em;">Task</span>
        <span style="color: rgba(232,234,240,0.4); font-size: 0.7rem; text-transform: uppercase; letter-spacing: 0.05em;">Domain</span>
        <span style="color: rgba(232,234,240,0.4); font-size: 0.7rem; text-transform: uppercase; letter-spacing: 0.05em;">Priority</span>
      </div>
      <div style="display: grid; grid-template-columns: 1.6fr 1fr 1fr 1fr; gap: 0.35rem 0.6rem; border-top: 1px solid rgba(255,255,255,0.08); padding-top: 0.4rem;">
        <span style="color: rgba(232,234,240,0.65);">"Seat is in her husband's position — again"</span>
        <span>Load driver profile</span>
        <span>Vehicle</span>
        <span style="color: var(--slidev-theme-primary, #a78bfa);">Daily · High</span>
        <span style="color: rgba(232,234,240,0.65);">"Types the school address from scratch"</span>
        <span>Set favourite destination</span>
        <span>Navigation</span>
        <span style="color: var(--slidev-theme-primary, #a78bfa);">Daily · Medium</span>
        <span style="color: rgba(232,234,240,0.65);">"Voice doesn't understand her accent"</span>
        <span>Change media by voice</span>
        <span>Media</span>
        <span style="color: var(--slidev-theme-primary, #a78bfa);">Daily · Low</span>
        <span style="color: rgba(232,234,240,0.65);">"Parking assist activates unexpectedly"</span>
        <span>Control driving assistance</span>
        <span>Driving</span>
        <span style="color: var(--slidev-theme-primary, #a78bfa);">Rare · Critical</span>
      </div>
    </div>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.6);">The journey gives you the <em>why</em> behind each task — the frustration, the frequency, the stakes. That context is what turns a list of features into a set of real design problems.</p>
  </div>
</div>

---
layout: section
title: Part 3 — HMI Architecture
---

# Part 3<br><span class="accent">HMI Architecture</span>

---
layout: center
title: Architecture Definition
class: text-center
---

# Architecture is the answer to one question:<br>which task lives on <span class="accent">which surface</span>?

---
title: The HMI Surfaces
---

<div class="slide-principles">
  <h3>The surfaces</h3>
  <h1>Where does the <span class="accent">interface live</span>?</h1>
  <div class="principles-grid">
    <div class="principle-item"><span class="pn">CL</span><span class="pt">Instrument Cluster — driving-critical data, always in view</span></div>
    <div class="principle-item"><span class="pn">HU</span><span class="pt">Head Unit (IVI) — rich content, parked and in-drive configuration</span></div>
    <div class="principle-item"><span class="pn">HUD</span><span class="pt">Head-Up Display — high-priority guidance overlaid on the road</span></div>
    <div class="principle-item"><span class="pn">SW</span><span class="pt">Steering Wheel — fast access without hands leaving the wheel</span></div>
    <div class="principle-item"><span class="pn">HK</span><span class="pt">Hard Keys — dedicated physical controls for critical or habitual tasks</span></div>
    <div class="principle-item"><span class="pn">AL</span><span class="pt">Ambient — light, haptics, sound cues as non-visual communication</span></div>
    <div class="principle-item"><span class="pn">VC</span><span class="pt">Voice — hands-free, eyes-free, always available</span></div>
    <div class="principle-item"><span class="pn">APP</span><span class="pt">Companion App — remote access before and after the drive</span></div>
  </div>
</div>

---
title: Surface Characteristics
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Design constraints</h3>
    <h1>Each surface has<br><span class="accent">its own rules</span></h1>
    <p>Surface selection is not aesthetic — it follows directly from distraction constraints and task characteristics.</p>
    <ul>
      <li><strong>Cluster</strong> — glanceable only. No deep navigation. Maximum 2 seconds to parse.</li>
      <li><strong>Head unit</strong> — the richest surface. Reserved for in-depth tasks best done at rest or by passengers.</li>
      <li><strong>HUD</strong> — highest-priority layer. Real road as context. Only the most critical data.</li>
      <li><strong>Steering wheel</strong> — eyes-on-road mandatory. Buttons only. Haptic confirmation.</li>
      <li><strong>Voice</strong> — lowest distraction input. Best for complex or multi-step commands.</li>
    </ul>
  </div>
</div>

---
title: Lucid Air — HMI Architecture
---

<div class="slide-figure">
  <div class="figure-image">
    <img src="/images/s02/lucid-air-architecture.png" />
  </div>
  <div class="figure-caption">
    <span class="figure-label">Reference</span>
    <span>Lucid Air — HMI surface architecture</span>
  </div>
</div>

---
title: Domain-to-Surface Mapping
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Mapping framework</h3>
    <h1>Domains<br><span class="accent">to surfaces</span></h1>
    <p>The mapping matrix assigns each task domain to one or more surfaces, with a primary home and secondary access points.</p>
    <ul>
      <li><strong>Driving domain</strong> → Cluster (primary) · HUD (speed, guidance) · Steering wheel (mode switches)</li>
      <li><strong>Navigation</strong> → HUD (turn-by-turn) · Cluster (distance/ETA) · Head unit (route planning)</li>
      <li><strong>Comfort</strong> → Hard keys (temp +/−) · Head unit (full settings) · Voice (set 21°C)</li>
      <li><strong>Media</strong> → Steering wheel (skip/volume) · Head unit (browse) · Voice (play artist)</li>
      <li><strong>Phone</strong> → Steering wheel (answer/reject) · Head unit (contacts) · Voice</li>
      <li><strong>Vehicle</strong> → Cluster (alerts) · Head unit (settings) · Companion app (remote)</li>
    </ul>
  </div>
</div>

---
title: The Glance Test
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>Validation method</h3>
    <h1>The<br><span class="accent">glance test</span></h1>
    <p>Any information placed on a driver-facing surface must pass the glance test: can the driver understand it in under two seconds, without context?</p>
    <ul>
      <li><strong>Cover it</strong> — show the screen for 1 second, then hide it. What did they see?</li>
      <li><strong>The five-word rule</strong> — if it takes more than five words to describe what you saw, there's too much on screen.</li>
      <li><strong>Glance ≠ read</strong> — cluster content must communicate through shape, position, and colour — not text.</li>
    </ul>
    <p style="margin-top: 0.75rem; font-size: 0.82rem; color: rgba(232,234,240,0.6);">The glance test is the earliest, cheapest design critique you can run. Use it before you open Figma.</p>
  </div>
</div>

---
title: Architecture Anti-Patterns
---

<div class="slide-split" style="grid-template-columns: 1fr">
  <div class="split-text">
    <h3>What to avoid</h3>
    <h1>Three architecture<br><span class="accent">mistakes</span></h1>
    <p>Most bad HMI architecture fails for one of three reasons — and all three are visible before a line of UI is drawn.</p>
    <ul>
      <li><strong>Overcrowded surfaces</strong> — putting critical and non-critical information side by side, so the driver can't tell at a glance what matters right now.</li>
      <li><strong>Buried critical tasks</strong> — important functions (hazard lights, emergency call) requiring multiple taps to access.</li>
      <li><strong>Inconsistent placement</strong> — the same function appearing in different locations depending on context. Mental model destroyed.</li>
    </ul>
  </div>
</div>

---
layout: center
title: Discussion
class: text-center
---

# What do these interiors<br>tell you about the <span class="accent">design vision</span>?

---
title: Discussion — Volvo EX30
---

<div class="slide-figure">
  <div class="figure-image">
    <img src="/images/s02/discuss-volvo-ex30.jpg" />
  </div>
  <div class="figure-caption">
    <span class="figure-label">Discussion</span>
    <span>Volvo EX30 interior</span>
  </div>
</div>

---
title: Discussion — Lotus Eletre
---

<div class="slide-figure">
  <div class="figure-image">
    <img src="/images/s02/discuss-interior-2.jpg" />
  </div>
  <div class="figure-caption">
    <span class="figure-label">Discussion</span>
    <span>Lotus Eletre interior</span>
  </div>
</div>

---
title: Discussion — Citroën Ami
---

<div class="slide-figure">
  <div class="figure-image">
    <img src="/images/s02/discuss-interior-3.jpg" />
  </div>
  <div class="figure-caption">
    <span class="figure-label">Discussion</span>
    <span>Citroën Ami interior</span>
  </div>
</div>

---
title: Discussion — Byton
---

<div class="slide-figure">
  <div class="figure-image">
    <img src="/images/s02/discuss-interior-4.jpg" />
  </div>
  <div class="figure-caption">
    <span class="figure-label">Discussion</span>
    <span>Byton interior</span>
  </div>
</div>

---
title: Discussion — BMW Panoramic iDrive
---

<div class="slide-figure">
  <div class="figure-image">
    <img src="/images/s02/discuss-interior-5.jpg" />
  </div>
  <div class="figure-caption">
    <span class="figure-label">Discussion</span>
    <span>BMW Panoramic iDrive interior</span>
  </div>
</div>

---
layout: section
title: Next Steps
---

# Next steps

---
title: Assignment — Before S03
---

<div class="slide-activity">
  <div style="position: absolute; bottom: 1rem; left: 2rem; right: 2rem; border-top: 1px solid rgba(255,255,255,0.07); padding-top: 0.5rem; display: flex; justify-content: space-between; font-size: 0.65rem; color: rgba(232,234,240,0.35);">
    <a href="https://www.figma.com/board/mwVmxZB3ZZ4gbWlrSJAChe/Untitled?node-id=0-1&t=kTiXSe7PqwyEuBaz-1" target="_blank" style="color: rgba(232,234,240,0.35); text-decoration: none;">figma.com/board — Session 02</a>
    <span>Password: shared by email</span>
  </div>
  <div class="activity-header">
    <h3>Assignment · for Session 03</h3>
    <h1>Consolidate your <span class="accent">project foundation</span></h1>
  </div>
  <div class="activity-steps">
    <div class="activity-step">
      <div class="step-number">01</div>
      <div class="step-body">
        <div class="step-label">Complete your persona</div>
        <div class="step-hint">Base it on someone real — a friend, a parent, yourself in a specific context, someone you've shared a car with. All 8 fields, plus a photo. Whether you're designing a utility car or a hypercar, the rigour is identical — a specific, honest persona is what makes the difference.</div>
      </div>
    </div>
    <div class="activity-step">
      <div class="step-number">02</div>
      <div class="step-body">
        <div class="step-label">Map the journey</div>
        <div class="step-hint">Walk your persona through the 5 driving phases. For each phase: what happens, what HMI moments appear, how do they feel today — and how should they feel? Use the template from today's session.</div>
      </div>
    </div>
    <div class="activity-step">
      <div class="step-number">03</div>
      <div class="step-body">
        <div class="step-label">Write your experience vision</div>
        <div class="step-hint">One sentence. How should your persona feel from the moment they enter the car to the moment they lock it? This is your design north star — everything in the HMI should be testable against it.</div>
      </div>
    </div>
    <div class="activity-step">
      <div class="step-number">04</div>
      <div class="step-body">
        <div class="step-label">Sketch a first architecture</div>
        <div class="step-hint">From the HMI moments in your journey, identify your key tasks and map them to surfaces. A rough sketch or diagram is enough — we'll refine it together at the start of S03. Be ready to explain one decision your vision directly influenced.</div>
      </div>
    </div>
  </div>
</div>

---
layout: center
title: The Question to Keep
class: text-center
---

# Every design decision<br>should survive one question:<br><em>"Would <span class="accent">my persona</span> actually use this?"</em>

---
layout: end
title: Questions
---

# Questions?

---
layout: end
title: End
---

# See you next session
