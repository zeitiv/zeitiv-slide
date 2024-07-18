---
theme: dracula
title: zeitiv.dev Portfolio

fonts:
  sans: Fira Code
  serif: Ubuntu
  mono: Fira Code

twoslash: true
lineNumbers: true
monaco: true
highlighter: shiki
drawings:
  persist: false
transition: slide-left
mdc: true
hideInToc: true

---
# Alex Grädel
## Frontend Developer


---
layout: two-cols
hideInToc: true
---
# Agenda

<Toc />


---
layout: iframe-right

url: https://zeitiv.dev
---
# Project Overview

## zeitiv.dev



---
layout: two-cols-header
---
<h1 class="font-serif mb-8">Tech Stack</h1>


<div class="container flex flex-row gap-32 align-middle h-full !mt-4">
<section class="px-8 py-4 rounded-xl bg-dark/10 backdrop-blur-sm border-3 border-dark shadow-xl text-xl">
  <h2 class="font-serif mb-2">cv frontend</h2>
  <ul class="">
    <div class="list-none" v-click>
      <div class="i-logos:angular-icon"></div>
      <span>angular 18 -></span>
      <span v-click class="!py-1.5 !px-2  !bg-light/10 !rounded !shadow-inner border-[#72CCFC] border-0 shadow-dark/80 text-sm hover:scale-105 text-white">
        <span class="text-[#72CCFC]">signal</span>
        <span class="text-pink">{{"<"}}</span>
        <span class="text-emerald">ContactForm</span>
        <span class="text-pink">{{">"}}</span>(<span class="text-purple">{}</span>);
      </span>
    </div>
    <div class="list-none" v-click>astro</div>
    <div class="list-none" v-click>bunJS</div>
    <div class="list-none" v-click>
      <span>unoCSS -> </span>
      <span v-click  class="!px-2 !py-1 !bg-light/10 !rounded !shadow-inner shadow-dark/80">
        <span class="text-white/80  border-dark-300 text-sm">'@unocss/reset/tailwind.css'</span>
      </span>
    </div class="list-none" v-click>
    <div class="list-none" v-click>TypeScript</div>
  </ul>
</section>


<section v-click class="px-8 py-4 rounded-xl bg-dark/10 backdrop-blur-sm border-3 border-dark shadow-x text-xl" >
  <h2 class="font-serif mb-2">contact backend</h2>
  <ul>
    <div>BunJS</div>
    <div>Elysia</div>
    <div>TypeScript</div>
    <div>ViteJS</div>
  </ul>
</section>
</div>



---

# Project Architecture

<section class="px-8 py-4 rounded-xl bg-dark/10 backdrop-blur-sm border-3 border-dark shadow-xl" >


The portfolio website is structured with modular components:

- About
- Experience
- Skills
- Education
- Contact (Angular Component)

</section>

---

# NAV


```html

<nav
  class="flex sm:flex-col flex-wrap justify-between gap-2 sm:gap-4 text-grey text-xl uppercase"
  id="sidenav"
>
  <a href="/#about" class="flex items-center transition-all hover:text-white" aria-label="About">
    <span class="i-ic:round-info size-10 sm:hidden"></span>
    <span class="hidden sm:inline">About</span>
  </a>
  <a id="exp-link" href="/#experience" class="flex items-center transition-all hover:text-white" aria-label="Experience">
    <span class="i-ic:round-work size-10 sm:hidden"></span>
    <span class="hidden sm:inline">Experience</span>
  </a>
  <a id="edu-link" href="/#education" class="flex items-center transition-all hover:text-white" aria-label="Education">
    <span class="i-ic:round-school size-10 sm:hidden"></span>
    <span class="hidden sm:inline">Education</span>
  </a>
  <a id="skills-link" href="/#skills" class="flex items-center transition-all hover:text-white" aria-label="Skills">
    <span class="i-ic:round-build size-10 sm:hidden"></span>
    <span class="hidden sm:inline">Skills</span>
  </a>
</nav>

```



---
# CI/CD Pipeline

<section class="px-8 py-4 rounded-xl bg-dark/10 backdrop-blur-sm border-3 border-dark shadow-xl" >


## Trigger
-> Activated on commits to the main branch or pull requests.

## Steps
-> Builds a Docker image of the website. `bun run build`

-> Publishes the Docker image to GitHub Packages. `

-> Sends a webhook to Portainer for deployment.

-> Generates a report in pull request comments upon successful deployment.


</section>

---

# Highlighting Key Features

<section class="px-8 py-4 rounded-xl bg-dark/10 backdrop-blur-sm border-3 border-dark shadow-xl" >



```ts twoslash

function parseBold(text: string) {
  const boldPattern = /\*\*(.*?)\*\*/g;
  const parsedText = text.replace(boldPattern, "<strong class='extra-bold'>$1</strong>");
  return parsedText;
}

const testString = "Hello **World**";
console.log(parseBold(testString));

```

</section>


---
scale: 0.5
---
# Test


---
# Magic

````md magic-move
```js
console.log(`Step ${1}`)
```
```js
console.log(`Step ${1 + 1}`)
```
```ts
console.log(`Step ${3}` as string)
```
````


---


---
layout: end
---
# Thank You!
