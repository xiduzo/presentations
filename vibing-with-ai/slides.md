---
theme: academic
layout: intro
---

# Vibe coding

Demonstration of various work-flows

<div class="absolute bottom-10">
  <span class="font-700">
      23 Sep 2025 - MDD
  </span>
</div>

<!--
Who of you have ever written some code?

Who of you would call yourself a coder?

After this morning, I hope all of you will call yourselves coders!
-->

---
layout: full
---

<Tweet id="1617979122625712128" />

<Footnotes>
    <Footnote><a href="https://x.com/karpathy/status/1617979122625712128" rel="noreferrer" target="_blank">Source</a></Footnote>
    <Footnote></Footnote>
  <Footnote>🐇</Footnote>
  <Footnote><a href="https://www.youtube.com/watch?v=LCEmiRjPEtQ" rel="noreferrer" target="_blank">Andrej Karpathy: Software Is Changing (Again)</a></Footnote>
</Footnotes>

<!--
A while ago, while being the Director of AI at Tesla, Andrej wrote this bold claim
-->

---
layout: center
---

````md magic-move
```sql
-- SQL (1973)
SELECT *
FROM Students
WHERE EnrolledIn = "MDD";
```

```sql
-- SQL (1973)
SELECT *
FROM Students
WHERE EnrolledIn = "MDD"
AND Track = "IxD";
```

```python
# Python (1991)
Students.objects
    .filter(EnrolledIn="MDD")
    .filter(Track="IxD")
```

```typescript
// JavaScript (1995)
query(Students, {
    where: {
        EnrolledIn: 'MDD',
        Track: 'IxD'
    }
});
```

```csharp
// C# (2000)
Students
    .Where(s => s.EnrolledIn == "MDD")
    .Where(s => s.Track == "IxD");
```

```md
// Midjourney (2022)
A cyber‑punk samurai in a rain‑slick alley,
neon signs reflecting on wet pavement,
photorealistic,
4K,
--ar 21:9,
--v 5,
--q 2,
--style cyberpunk
```
````

<style>
.shiki span {
  font-size: 2.25rem;
  line-height: 1.5;
}
</style>

<!--
But I think this has been true since a longer time,

Who can read this?

>> And track <<

And this?

>> Python <<

And this...
-->

---
layout: full
---

<Tweet id="1886192184808149383" />

<div class="absolute bottom-101 left-93" v-mark="{ type: 'circle', color: 'blue', strokeWidth: 5 }"><span class="opacity-0 text-xl">vibe coding</span></div>

<Footnotes>
    <Footnote><a href="https://x.com/karpathy/status/1886192184808149383" rel="noreferrer" target="_blank">Source</a></Footnote>
</Footnotes>

<!--
A while later, he introduced the term “Vibe coding”.

While most people took this at face-value and did not read further than the first line.
-->

---
layout: quote
class: text-xl
---

There's a new kind of coding I call <span v-mark="{ type: 'circle', color: 'blue', strokeWidth: 5 }">"vibe coding"</span>, where you fully give in to the vibes, embrace exponentials, and <span v-mark="{ type: 'underline', color: 'green', strokeWidth: 5 }">forget that the code even exists</span>.

It's possible because the LLMs (e.g. Cursor Composer w Sonnet) are getting too good. Also I just talk to Composer with SuperWhisper so I barely even touch the keyboard.

<span v-mark="{ type: 'underline', color: 'red', strokeWidth: 5 }">I ask for the dumbest things</span> like _"decrease the padding on the sidebar by half"_ because I'm too lazy to find it. I _"Accept All"_ always, <span v-mark="{ type: 'underline', color: 'red', strokeWidth: 5 }">I don't read the diffs anymore.</span>

When I get error messages <span v-mark="{ type: 'underline', color: 'orange', strokeWidth: 5 }">I just copy paste</span> them in with no comment, <span v-mark="{ type: 'underline', color: 'orange', strokeWidth: 5 }">usually</span> that fixes it.

The code <span v-mark="{ type: 'underline', color: 'red', strokeWidth: 5 }">grows beyond my usual comprehension</span>, I'd have to really read through it for a while.

Sometimes <span v-mark="{ type: 'underline', color: 'orange', strokeWidth: 5 }">the LLMs can't fix a bug so I just work around it</span> or ask for random changes until it goes away.

<span v-mark="{ type: 'underline', color: 'green', strokeWidth: 5 }">It's not too bad for throwaway weekend projects</span>, but still quite amusing. I'm building a project or webapp, but it's not really coding - I just see stuff, say stuff, run stuff, and copy paste stuff, and <span v-mark="{ type: 'underline', color: 'green', strokeWidth: 5 }">it mostly works</span>.

<Footnotes>
    <Footnote><a href="https://x.com/karpathy/status/1886192184808149383" rel="noreferrer" target="_blank">Source</a></Footnote>
    <Footnote></Footnote>
  <Footnote>🐇</Footnote>
  <Footnote><a href="https://nmn.gl/blog/ai-and-learning" rel="noreferrer" target="_blank">New Junior Developers Can’t Actually Code</a></Footnote>
  <Footnote><a href="https://nmn.gl/blog/ai-illiterate-programmers" rel="noreferrer" target="_blank">AI is Creating a Generation of Illiterate Programmers</a></Footnote>
</Footnotes>

<!--
I think it is good to internalise the full tweet. Taking the good, the bad and the ugly from it.

This is my take on it:

>> Forget that code even exists
When we can guarantee transparency, this is a good thing.

>> I ask for the bumbest things, I don't read the diffs anymore.
This to me is a bit scary, we become too reliant on AI

>> I just copy paste, usualy
Today we will go over some work-flows that make you more than a copy-paste machine

>> Grows beyond my usual comprehension
This to me is a bit scary, we become too reliant on AI

>> Sometimes the LLMs can't fix a bug so I just work around it
You are limiting yourself by not having the knowledge to do things yourself anymore

>> It's not bad for throwaway weekend projects
Agree

>> It mostly works
But not always
-->

---
layout: full
---

<Tweet id="1952084574366032354" />

<Footnotes>
    <Footnote><a href="https://x.com/sama/status/1952084574366032354" rel="noreferrer" target="_blank">Source</a></Footnote>
    <Footnote></Footnote>
    <Footnote>🐇</Footnote>
  <Footnote><a href="https://medium.com/ai-mind-labs/replit-vibe-coding-tool-wipes-out-entire-company-database-8f77c66f9151" rel="noreferrer" target="_blank">Replit Vibe Coding Tool Wipes Out Entire Company Database</a></Footnote>
</Footnotes>

<!--
Not so long ago, this statement was made.

But it can also ruin your business in a second.
-->

---
layout: full
---

<Tweet id="1953529799219319205" scale="0.63" />

<Footnotes>
    <Footnote><a href="https://x.com/sama/status/1953529799219319205" rel="noreferrer" target="_blank">Source</a></Footnote>
</Footnotes>

<!--
An example of a fast-fashion SaaS
-->

---
layout: section
---

# Before we start exploring

A few disclaimers

---
layout: image-right
image: https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExbnczZngzZDJpMWs4azBlaHl4djJkenc0Z2Nsb25mNW1xMWdzeHBmcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/CDxjkzT5wp8VW/giphy.gif
backgroundSize: 25em
---

# Developer magic

I might sometimes _vibe_ with the LLMs by using some technical jargon to give very specific **context** to steer the LLM.

_For example:_

```
Create a basic application repository that
is to be build using the following technologies:

1. Vite (builder and bundler)
2. Nextjs (app router)
3. shadcn + takwindcss & tailwind-animate (UI)
4. usehooks-ts (common hooks -- `useLocalStorage`)


There is **no** need for a real database,
everything can be stored in local-storage.

There is **no** need for writing any sorts of
automated tests (unit, integration, e2e, etc...).
```

<Footnotes>
  <Footnote><a href="https://www.imdb.com/title/tt5027048/" rel="noreferrer" target="_blank">Source</a></Footnote>
  <Footnote></Footnote>
<Footnote>🐇</Footnote>
  <Footnote><a href="https://vercel.com/blog/maximizing-outputs-with-v0-from-ui-generation-to-code-creation" rel="noreferrer" target="_blank">Maximizing outputs with v0: From UI generation to code creation</a></Footnote>
</Footnotes>

<!--
.
-->

---
layout: image-right
image: '/context-matters.webp'
backgroundSize: 25em
---

# Context matters

The more the _context_ you provide,<br/> the better the LLMs can assist you.

<Footnotes>
    <Footnote><a href="https://www.instagram.com/littleporpoise/" rel="noreferrer" target="_blank">Source</a></Footnote>
    <Footnote></Footnote>
  <Footnote>🐇</Footnote>
  <Footnote><a href="https://arxiv.org/abs/1706.03762" rel="noreferrer" target="_blank">Attention Is All You Need</a></Footnote>
</Footnotes>

---
layout: image-right
image: https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExdXllaWkzdWxtb21zaW95ZmRpbmc5ZXc3dWpjMjRybjc2eXdmMzlocCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/P8ef3Dkynk0xLx1h1T/giphy.gif
backgroundSize: 25em
---

# This will go fast

This is **not** a step-by-step tutorial.

Let's _vibe_ together, ask questions!

---
layout: full
---

| Workflow | Who is in control | Who is the expert | Tools
|----------|---------|-----------|------|
| `Prompt engineer` | Mostly you    | Mostly you       | https://chat.openai.com/ 💰 <br/> https://msty.app/ |
| `AI Agents` | Collaborative    | Collaborative       | https://github.com/features/copilot 💰 <br/> https://www.continue.dev/ |
| `Spec Driven` | Collaborative    | Collaborative       | https://kiro.dev/ 💰 <br/> https://github.com/github/spec-kit |
| `Agentic AI` | Mostly AI    | Mostly AI       | https://v0.dev/ 💰 <br/> https://code.visualstudio.com/mcp |

<Footnotes>
  <Footnote>🐇</Footnote>
  <Footnote><a href="https://medium.com/@elisowski/ai-agents-vs-agentic-ai-whats-the-difference-and-why-does-it-matter-03159ee8c2b4" rel="noreferrer" target="_blank">AI Agents vs Agentic AI: What’s the Difference and Why Does It Matter?</a></Footnote>
  <Footnote><a href="https://opal.withgoogle.com/landing/?source=labs" rel="noreferrer" target="_blank">Google Opal: Build, edit and share mini-AI apps using natural language</a></Footnote>
</Footnotes>

---
layout: full
---

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://embed.figma.com/design/MtJcWLrYCIeEEIkf9h5dU4/Vibe-with-Figma?node-id=7661-21120&embed-host=share" allowfullscreen></iframe>

<Footnotes>
  <Footnote><a href="https://www.figma.com/design/MtJcWLrYCIeEEIkf9h5dU4/Vibe-with-Figma?node-id=7661-21189&t=ogJQ6Gzo4dOopeGn-4" rel="noreferrer" target="_blank">Source</a></Footnote>
</Footnotes>
