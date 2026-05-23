---
theme: default
title: Template Reference — IED HMI Course
colorSchema: dark
fonts:
  sans: DM Sans
  mono: DM Mono
  weights: '300,400,500,700'
cssEngine: unocss
---

<!-- ═══════════════════════════════════════════════════════════════
     LAYOUT REFERENCE — empty states for all available templates
     Use this file as a copy-paste source when building sessions

     RULE: every slide must have title: in its frontmatter block
     so it appears labelled in the sidebar navigation.
     ═══════════════════════════════════════════════════════════════ -->

---
title: Cover
---

<!-- ── COVER ───────────────────────────────────────────────────── -->
<div class="cover-layout">
  <div class="tag">IED Master Transportation Design · 2025/26</div>
  <h1>Session Title<br><span class="accent">Subtitle</span></h1>
  <div class="subtitle">Session N — Topic Name</div>
  <div class="instructor">Lorenzo Romagnoli</div>
</div>

---
layout: section
title: Section Title
---

# Section Title

---
layout: default
title: Slide Title
---

# Slide Title

- Point one
- Point two
- Point three

---
layout: two-cols
title: Slide Title
---

# Left column

Content on the left.

::right::

# Right column

Content on the right.

---
layout: center
title: Key Concept
class: text-center
---

# Key concept

A single focused statement.

---
layout: quote
title: Quote
---

"Quote text goes here."

<div class="quote-author">— Author Name</div>

---
title: Video Title
---

<!-- ── VIDEO EMBED ───────────────────────────────────────────────
     Use for: YouTube or Vimeo videos
     The caption bar is the PDF/PPTX fallback — always fill it in
     YouTube embed URL: replace VIDEO_ID below                    -->
<div class="slide-video">
  <iframe
    src="https://www.youtube.com/embed/VIDEO_ID"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
  />
  <div class="video-caption">
    <span class="video-label">Video</span>
    <span class="video-title">Video title here</span>
    <span class="video-url">youtube.com/watch?v=VIDEO_ID</span>
  </div>
</div>

---
title: Slide Title
---

<!-- ── FULLBLEED IMAGE ───────────────────────────────────────────
     Use for: chapter openers, mood/reference photos
     Replace src with: /images/sNN/filename.jpg              -->
<div class="slide-fullbleed">
  <img src="/images/shared/placeholder-wide.svg" class="fullbleed-img" />
  <div class="fullbleed-overlay">
    <div class="fullbleed-tag">Category · Subcategory</div>
    <div class="fullbleed-title">Title line one<br>Title line two</div>
    <div class="fullbleed-caption">Supporting caption or short description.</div>
  </div>
</div>

---
title: Slide Title
---

<!-- ── TEXT + IMAGE SPLIT ────────────────────────────────────────
     Use for: concept explanation with a visual reference      -->
<div class="slide-split">
  <div class="split-text">
    <h3>Label</h3>
    <h1>Title <span class="accent">here</span></h1>
    <p>Body text explaining the concept alongside the image.</p>
    <ul>
      <li>Point one</li>
      <li>Point two</li>
    </ul>
  </div>
  <div class="split-image">
    <img src="/images/shared/placeholder-square.svg" />
  </div>
</div>

---
title: Slide Title
---

<!-- ── FIGURE WITH CAPTION ───────────────────────────────────────
     Use for: UI screenshots, wireframes, annotated references  -->
<div class="slide-figure">
  <div class="figure-image">
    <img src="/images/shared/placeholder-wide.svg" />
  </div>
  <div class="figure-caption">
    <span class="figure-label">Fig. N</span>
    Caption describing the image — source, context, or annotation.
  </div>
</div>

---
title: Slide Title
---

<!-- ── 2-UP COMPARISON ───────────────────────────────────────────
     Use for: side-by-side comparison of two approaches        -->
<div class="slide-compare">
  <h2 class="compare-title">Comparing <span class="accent">two approaches</span></h2>
  <div class="compare-grid">
    <div class="compare-item">
      <img src="/images/shared/placeholder-wide.svg" />
      <div class="compare-label">Option A — description</div>
    </div>
    <div class="compare-item">
      <img src="/images/shared/placeholder-wide.svg" />
      <div class="compare-label">Option B — description</div>
    </div>
  </div>
</div>

---
layout: end
title: End
---

# Thank you

<div class="end-links">
  Questions?
</div>
