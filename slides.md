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

## Fullstack Developer <mdi-laptop-mac class="text-3xl ml-2" />

---
layout: two-cols
hideInToc: true
title: serif

---

# Agenda

<Toc />

---
hideInToc: true

---

# Introduction <mdi-account-circle class="text-3xl ml-2" />

- Frontend Developer with a passion for creating efficient, scalable web applications
- Specializing in Angular, Astro, and modern web technologies
- Today's presentation: Deep dive into my portfolio project -> <strong class="text-xl">zeitiv.dev</strong>

---
layout: iframe-right
url: https://zeitiv.dev

---

# Project Overview <logos-astro class="text-3xl ml-2" />

## zeitiv.dev

---
layout: iframe
url: https://zeitiv.dev
---

---

# Project Goals <mdi-target class="text-3xl ml-2" />

- Showcase my skills and experience as a frontend developer
- Demonstrate proficiency in modern web technologies
- Create a performant, responsive, and accessible personal website
- Implement best practices in web development and DevOps

---

# Tech Stack <mdi-stack-overflow class="text-3xl ml-2" />

<div class="flex flex-row justify-around align-middle content-center mt-20 gap-8" >
  <section class="px-8 py-4 rounded-xl bg-dark/10 backdrop-blur-sm border-3 border-dark shadow-xl text-xl ">
    <h2 class="font-serif mb-2">Frontend <logos-angular-icon class="ml-2" /></h2>
    <ul class="text-light">
      <li>Angular 18</li>
      <li>Astro</li>
      <li>UnoCSS</li>
      <li>TypeScript</li>
    </ul>
  </section>

  <section class="px-8 py-4 rounded-xl bg-dark/10 backdrop-blur-sm border-3 border-dark shadow-xl text-xl">
    <h2 class="mb-2">Backend <logos-nodejs-icon class="ml-2" /></h2>
    <ul class="text-light">
      <li>BunJS</li>
      <li>Elysia</li>
      <li>TypeScript</li>
      <li>ViteJS</li>
    </ul>
  </section>
    <section class="px-8 py-4 rounded-xl bg-dark/10 backdrop-blur-sm border-3 border-dark shadow-xl text-xl">
    <h2 class="mb-2">Server <logos-ubuntu class="ml-2" /></h2>
    <ul class="text-light">
      <li>Ubuntu</li>
      <li>Docker</li>
      <li>Portainer</li>
      <li>NGINX</li>
    </ul>
  </section>
</div>

---

# Tech Stack Deep Dive <mdi-code-tags class="text-3xl ml-2" />

<div class="grid grid-cols-3 gap-4">
  <section class="px-4 py-2 rounded-xl bg-dark/10 backdrop-blur-sm border-2 border-dark shadow-xl text-sm">
    <h3 class="font-serif mb-2">Angular 18 <logos-angular-icon class="ml-2" /></h3>
    <ul class="text-light">
      <li>Powerful framework for building dynamic SPAs</li>
      <li>Excellent TypeScript support</li>
      <li>Reactive programming with RxJS</li>
    </ul>
  </section>

  <section class="px-4 py-2 rounded-xl bg-dark/10 backdrop-blur-sm border-2 border-dark shadow-xl text-sm">
    <h3 class="font-serif mb-2">Astro <logos-astro class="ml-2" /></h3>
    <ul class="text-light">
      <li>Static site generation for improved performance</li>
      <li>Partial hydration for interactive components</li>
      <li>Easy integration with various frameworks</li>
    </ul>
  </section>

  <section class="px-4 py-2 rounded-xl bg-dark/10 backdrop-blur-sm border-2 border-dark shadow-xl text-sm">
    <h3 class="font-serif mb-2">UnoCSS <logos-unocss class="ml-2" /></h3>
    <ul class="text-light">
      <li>Atomic CSS engine for rapid UI development</li>
      <li>Highly customizable and extensible</li>
      <li>Excellent performance with small bundle size</li>
    </ul>
  </section>
</div>

---

# Components <mdi-puzzle class="text-3xl ml-2" />

<div class="grid grid-cols-2 gap-4">

<section class="px-8 py-4 rounded-xl bg-dark/10 backdrop-blur-sm border-3 border-dark shadow-xl text-xl h-full">
<img src="/image.png" />
</section>

<section class="px-8 py-4 rounded-xl bg-dark/10 backdrop-blur-sm border-3 border-dark shadow-xl text-xl h-full">
</section>

</div>

---

# Navigation <mdi-navigation class="text-3xl ml-2" />

<div class="shadow-xl">

```html
<nav
  class="flex sm:flex-col flex-wrap justify-between gap-2 sm:gap-4 text-grey text-xl uppercase"
  id="sidenav"
>
  <!-- About link with an icon for small screens and text for larger screens -->
  
    href="/#about"
    class="flex items-center transition-all hover:text-white"
    aria-label="About"
  >
    <span class="i-ic:round-info size-10 sm:hidden"></span>
    <!-- Icon displayed on small screens -->
    <span class="hidden sm:inline">About</span>
    <!-- Text displayed on larger screens -->
  </a>
  ...
</nav>
```
</div>

---

# Future Improvements <mdi-rocket-launch class="text-3xl ml-2" />

- <mdi-server class="text-green-500" /> Implement server-side rendering for improved SEO
- <mdi-post class="text-blue-500" /> Add a blog section to share technical articles and insights
- <mdi-ab-testing class="text-purple-500" /> Implement A/B testing for optimizing user engagement
- <mdi-cellphone-link class="text-red-500" /> Explore PWA capabilities for offline access and improved mobile experience


---
# Future Improvements <mdi-rocket-launch class="text-3xl ml-2" />

<div class="grid grid-cols-3 gap-4">
  <section class="px-4 py-2 rounded-xl bg-dark/10 backdrop-blur-sm border-2 border-dark shadow-xl">
    <h3 class="font-serif mb-2">Server-Side Rendering <mdi-server class="text-green-500 ml-2" /></h3>
    <p class="text-sm">Implement SSR for improved SEO and initial load performance</p>
  </section>

  <section class="px-4 py-2 rounded-xl bg-dark/10 backdrop-blur-sm border-2 border-dark shadow-xl">
    <h3 class="font-serif mb-2">Blog Section <mdi-post class="text-blue-500 ml-2" /></h3>
    <p class="text-sm">Add a blog to share technical articles and insights</p>
  </section>


  <section class="px-4 py-2 rounded-xl bg-dark/10 backdrop-blur-sm border-2 border-dark shadow-xl">
    <h3 class="font-serif mb-2">A/B Testing <mdi-ab-testing class="text-purple-500 ml-2" /></h3>
    <p class="text-sm">Implement A/B testing for optimizing user engagement</p>
  </section>

  <section class="px-4 py-2 rounded-xl bg-dark/10 backdrop-blur-sm border-2 border-dark shadow-xl">
    <h3 class="font-serif mb-2">PWA Capabilities <mdi-cellphone-link class="text-red-500 ml-2" /></h3>
    <p class="text-sm">Explore PWA for offline access and improved mobile experience</p>
  </section>
</div>

---
hideInToc: true

---
# Questions? <mdi-help-circle class="text-3xl ml-2" />

<div class="flex justify-center items-center h-full">
  <h2 class="text-4xl font-bold">Thank you for your attention!</h2>
</div>



---
hideInToc: true
---
hideInToc: true
---
# Thank You! 

<div class="flex flex-col items-center justify-center h-full">
  <h2 class="text-5xl font-bold mb-4">Alex Grädel</h2>
  <p class="text-2xl">Frontend Developer</p>
  <mdi-hand-wave class="text-3xl ml-2 text-yellow-400" />
  <div class="flex mt-8 space-x-4">
    <a href="https://github.com/yourusername" target="_blank" rel="noopener noreferrer">
      <mdi-github class="text-4xl hover:text-gray-300 text-white transition-colors" />
    </a>
    <a href="https://linkedin.com/in/yourusername" target="_blank" rel="noopener noreferrer">
      <mdi-linkedin class="text-4xl hover:text-blue-400 text-white transition-colors" />
    </a>
    <a href="mailto:your.email@example.com">
      <mdi-email class="text-4xl hover:text-red-400 text-white transition-colors" />
    </a>
  </div>
</div>

