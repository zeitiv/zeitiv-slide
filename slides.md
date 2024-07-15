---
theme: dracula
title: zeitiv.dev Portfolio

fonts:
  sans: Fira Code
  serif: Robot Slab
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
# Technologies


<div class="container flex flex-row gap-8 justify-between">
<section class="px-8 py-4 rounded-xl bg-dark/10 backdrop-blur-sm border-3 border-dark shadow-xl">
  <h2>Frontend</h2>

  <ul>
    <li>Astro</li>
    <li>UnoCSS</li>
    <li>TypeScript</li>
  </ul>

</section>


<section class="p-8 rounded-xl bg-dark/10 backdrop-blur-sm border-3 border-dark shadow-xl">
  <h2>Backend</h2>
  <ul>
    <li>BunJS</li>
    <li>Elysia</li>
    <li>TypeScript</li>
    <li>ViteJS</li>
  </ul>
</section>
</div>



---

# Project Architecture

The portfolio website is structured with modular components:

- About
- Experience
- Skills
- Education
- Contact (Angular Component)



---

# CI/CD Pipeline

## Trigger
-> Activated on commits to the main branch or pull requests.

## Steps
-> Builds a Docker image of the website. `bun run build`

-> Publishes the Docker image to GitHub Packages. `

-> Sends a webhook to Portainer for deployment.

-> Generates a report in pull request comments upon successful deployment.

---

# Highlighting Key Features



```ts twoslash

function parseBold(text: string) {
  const boldPattern = /\*\*(.*?)\*\*/g;
  const parsedText = text.replace(boldPattern, "<strong class='extra-bold'>$1</strong>");
  return parsedText;
}

const testString = "Hello **World**";
console.log(parseBold(testString));

```

---
layout: end
---
# Thank You!
