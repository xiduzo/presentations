---
theme: apple-basic
title: Figma day 1
# https://sli.dev/features/drawing
drawings:
  persist: true
mdc: true
overviewSnapshots: true
layout: fact
transition: slide-up
fonts:
    mono: Fira Code
---

# Figma day 1
### 13th of November 2025

---
layout: image
image: /images/scissors.jpeg
backgroundSize: contain
---

---
layout: statement
transition: slide-left
---

### Manage expectations

<div class="mt-12"></div>

<h1 v-click>MDD <span class="font-mono">!=</span> Course UX design</h1>

<style>
* {
    font-feature-settings: 'liga' 1, 'dlig' 1;
}
</style>

---
layout: fact
transition: fade
---

# Who ❤️ Figma?{style="marginLeft: 1.25em"}

### And why

---
layout: fact
transition: fade
---

# Who 💔 Figma?{style="marginLeft: 1.25em"}

### And why

---
layout: fact
---

# People ❤️ Figma{style="marginLeft: -0.325em"}

### But why


---
layout: image
image: /images/ux-tools.png
backgroundSize: cover
class: text-black!
---

<div class="mt-120"></div>

<Footnotes>
    <Footnote><a href="https://www.uxness.in/2024/06/2024-annual-ux-tools-survey-by-uxness.html" rel="noreferrer" target="_blank">Source</a></Footnote>
</Footnotes>

---
layout: image-right
image: /images/adobe.png
---

# It is free*

### Compared to the Adobe Creative Cloud

[* for students](https://www.figma.com/education){style="opacity:0.5;"}

<Footnotes class="absolute bottom-8 italic opacity-50">
    <Footnote>🐇 But so is <a href="https://penpot.app/" rel="noreferrer" target="_blank">penpot</a></Footnote>
</Footnotes>

---
layout: image-right
image: /images/sketch.png
---

# It is collaborative

### Compared to Sketch

Works on MacOS, Windows, iOS, iPad, Android and in the Browser

<Footnotes class="absolute bottom-8 italic opacity-50">
    <Footnote>🐇 But so is <a href="https://penpot.app/" rel="noreferrer" target="_blank">penpot</a></Footnote>
</Footnotes>

---
layout: image-right
image: /images/plugin.png
backgroundSize: contain
---

# The community

### Extend Figma how you need it

<Footnotes class="absolute bottom-8 italic opacity-50">
    <Footnote>🐇 <a href="https://www.figma.com/community/plugin/1373258770799080545" rel="noreferrer" target="_blank">Microflow hardware bridge</a></Footnote>
</Footnotes>

---
layout: image-right
image: /images/ui3.png
---

# UI3

### And the promise of AI tools

<Footnotes class="absolute bottom-8 italic opacity-50">
    <Footnote><a href="https://help.figma.com/hc/en-us/articles/23570416033943" rel="noreferrer" target="_blank">AI in Figma</a></Footnote>
</Footnotes>

---
layout: fact
---

# Why I ❤️ Figma

### It makes (web)designers think like a developer <u>again</u>

---
layout: image
transition: slide-left
image: /images/designers-developers-kiss.jpeg
backgroundSize: 60%
---

---
layout: fact
---

# Components

### Variants, auto layout, ~~variables~~

---
layout: fact
---

# What is a component?

### And when did this concept arise?

---
layout: image
image: /images/components-timeline.png
backgroundSize: contain
---

---
layout: iframe
url: https://madebymike.github.io/html5-periodic-table
---

---
layout: image
image: /images/figma-html.png
backgroundSize: contain
---

---
layout: quote
---

### What is a component?
# Components are the main building blocks for user interfaces.

<Footnotes class="absolute bottom-8 italic opacity-50">
    <Footnote>🐇 <a href="https://www.designsystemchecklist.com/category/components" rel="noreferrer" target="_blank">Design system checklist</a></Footnote>
</Footnotes>

---
layout: image-right
image: https://bradfrost.com/wp-content/uploads/2021/11/1_XxiyR4IgdUyfd4edKpqTyQ.jpeg
---

# ⚠️{style="color: #f00;text-align: center;"}
## A (Figma) component library is not a design system!

### It is a small _sub-set_ of a design system

<Footnotes class="absolute bottom-8 italic opacity-50">
    <Footnote>🐇 <a href="https://bradfrost.com/blog/post/design-systems-are-for-user-interfaces/" rel="noreferrer" target="_blank">Design systems by Brad Frost</a></Footnote>
</Footnotes>

---
layout: fact
---

### Exercise


# ✂️✂️✂️{style="margin: 0.2em 0 0.5em;"}

## Cut out and organize the components of the _NS_ (Dutch Railways)

<div class="mt-12 italic">
    Look at
  <a href="https://docs.huihoo.com/yui/2.5.0/" target="_blank">Yahoo UI</a>,
  <a href="https://getbootstrap.com/docs/5.3/examples/" target="_blank">Bootstrap</a>,
  <a href="https://m3.material.io/components" target="_blank">Material UI</a> or
  <a href="https://atlassian.design/components" target="_blank">Atlassian</a>
</div>

---
layout: image
image: /images/discovery-example.webp
backgroundSize: contain
---

---
layout: fact
---

### ⚠️ _next slide contains a spoiler_ ⚠️

---
layout: image
image: /images/nessie.png
class: text-black!
transition: slide-left
---

<div class="mt-112"></div>

[NS design system](https://design.ns.nl/4a05a30ad/p/04b3ac-nessie--ns-design-system){style="opacity:0.5;"}<br/>
[Nessie use case](https://milanvdmaaten.netlify.app/ns/){style="opacity:0.5;"}

---
layout: fact
transition: slide-left
---

# Break

---
layout: fact
---

# What does a<br/> button look like?

[Button stealer](https://anatolyzenkov.com/stolen-buttons/button-stealer){style="opacity:0.5;"}

---
layout: image
image: /images/no-layer-names.png
backgroundSize: 100%
---

---
layout: image
image: /images/layer-names.png
backgroundSize: 100%
---

---
layout: fact
---

### Exercise

# Make a component{style="margin: 0.2em 0 0.5em;"}

## At least <u>3 variants</u>, each variant should have at least <u>2 states</u> and use <u>auto layout</u>

### [Figma file](https://www.figma.com/design/lWzYDfRjjvERZZyPa8tQP8/Figma)

<div class="mt-12 italic">
    Look at
  <a href="https://component.gallery/components/button/" target="_blank">Component gallery</a>,
  <a href="https://www.designsystemchecklist.com/category/components/" target="_blank">Design system checklist</a>,
  <a href="https://m3.material.io/components/all-buttons" target="_blank">Material design 3</a> or
  <a href="https://ui.shadcn.com/docs/components/button" target="_blank">Shadcnui (<code>V0</code> uses this!)</a>
</div>

<!--
mddfigmaday1
-->

---
transition: slide-left
---

## 🐇 Down the rabbit hole

- [Figma fundamentals](https://www.youtube.com/watch?v=Cx2dkpBxst8&list=PLXDU_eVOJTx7QHLShNqIXL1Cgbxj7HlN4), [Components](https://www.youtube.com/watch?v=k74IrUNaJVk&list=PLXDU_eVOJTx5LSjOmeBYMuvaa4UayfMe4) & [Auto layout](https://www.youtube.com/watch?v=PNJxeD29ZTg&list=PLXDU_eVOJTx55HFubfbTL3ellJjBM2QE2)

### Design systems
- [The design system guide](https://thedesignsystem.guide/)
- [Component gallery](https://component.gallery/)
- [Design system repo](https://designsystemsrepo.com/)
- [Design System ROI Calculator](https://www.knapsack.cloud/calculator)
- [Design system checklist](https://www.designsystemchecklist.com/)
- [Open source Dutch government design system](https://www.nldesignsystem.nl/)
- [Screens from tons of apps](https://mobbin.com/browse/ios/apps)

### People to follow
- [Brad Frost](https://bradfrost.com/), writes about design (systems)
- [Joey Banks](https://baselinedesign.io/), Talks a lot about Design systems and Figma
- [Rogie](https://bento.me/rogie), Designer Advocate at Figma
- [Nathan A Curtis](https://www.directededges.com/nathan-curtis), Most famous design system designer worldwide

---
---

## 🐇🐇 Deep down the rabbit hole

### Flexbox (autolayout for the web)
- [Flexbox in 100 seconds](https://www.youtube.com/watch?v=K74l26pE4YA)
- [A guide to flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Flex box froggy](https://flexboxfroggy.com/)

### Grid
- [Grid in 100 seconds](https://www.youtube.com/watch?v=uuOXPWCh-6o)
- [A guide to grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Grid garden](https://cssgridgarden.com/)

### Open source Figma
- [Penpot](https://penpot.app/)
