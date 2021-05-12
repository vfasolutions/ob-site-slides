---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background-color: hsl(207, 55%,94%);
# apply any windi css classes to the current slide
class: "text-center"
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
---

# Wordpress Site for Obnatus

Obnatus is a one person startup accelerator and angel investing

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 p-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
  class="abs-br m-6 text-xl icon-btn opacity-50 !border-none !hover:text-white">
<carbon-logo-github />
</a>

<style>
h1 {
  color: hsl(207,55%,14%)
}
p {
  color: hsl(207,55%,34%)
}

</style>

---

# Purpose of site

- Present basic info about company
- Present the people – founder and other people involved
- Present featured companies Obnatus has been involved with
- Allow contact through email and form
- Publish news article with blogging

---

# Site specs

<p></p>

The site will have 5 pages that need to be custom designed. Two will be in a "dark theme" while the rest will be in a light theme. The news/blog pages should be in a slightly different light theme as well.

The company wants to appear: **modern**, **technology-oriented**, **trustworthy**, **clean**

## Pages

- **Front page:** Scrollable with several modules, including about us, contact, "what we do"
- **Team:** Separate page to present people involved
- **Companies:** Separate page to present companies involved
- **Blog archive:** Archive page for blog posts aka news articles
- **Blog page:** Template for any blog post

---

# Front page

Use light theme

## Sections

- **Hero Image**: Large image with a text over it. Could be a carousel such as on [heydays.com](https://heydays.com) if there is a ready component for it.
- **About us**: Paragraph, icons with text, new paragraph
- **Product/What we do**: Paragraph, icons with text
- **News**: Block with latest news articles from blog
- **Contact**: Show address and email as well as normal contact form

---

# Portfolio page

Use dark theme

Should present a bunch of logos of companies. There are 3 types of companies listed.

- **Invested**: Should have a logo and a short description
- **Worked with**: Should have a logo and a short description
- **Involved with**: Should have just a small logo

Since the page is in "dark mode", the logos probably need to be adjusted so they have a light color.

---

# Team page

Use dark theme

There should be a main photo and description of the founder. See the .pptx slides for good example. Below it should be possible to add other people with a portrait and description. Just use any existing block for team/people here.

---

# News page

Use light theme but not exact same as front page

This page should just list all the blog articles.

---

# Blog post template

Use light theme but not exact same as front page, same as "News page"

Should have a featured image and title visible. Tags and date should be displayed as well. No special requirements as long as the design is consistent with the rest of the site.

---

# Other info page

Use light theme

We will need some simple pages that are just a bunch of text, such as privacy notice etc. These should just be a default page in Wordpress, but the font and colors should be the same as on the front page.

---

# Header

Header should have logo to the left, two menu items on the left, and 3 menu items on the right.

Ideally, the mobile menu should be full screen with two items first, then 3 items separated by some space.

The menu items on the right, should be anchor links to sections on the front page, e.g. to "About us" (/#about-us)

---

# Footer

Should use the main dark theme color as background. Will have some links to privacy page as well as company info and copyright. Will probably find something more to add after first draft.

---

# Colors

## Main color

<div style="display:flex;align-items:center">
<div style="background-color: hsl(207,55%,34%);height:2rem;width:2rem;border-radius:50%;display:block;margin:0.25rem"></div>
<div style="background-color: hsl(207,55%,54%);height:1.4rem;width:1.4rem;border-radius:50%;display:block;margin:0.25rem"></div>
<div style="background-color: hsl(207,55%,44%);height:1.4rem;width:1.4rem;border-radius:50%;display:block;margin:0.25rem"></div>
<div style="background-color: hsl(207,55%,34%);height:1.4rem;width:1.4rem;border-radius:50%;display:block;margin:0.25rem"></div>
<div style="background-color: hsl(207,55%,24%);height:1.4rem;width:1.4rem;border-radius:50%;display:block;margin:0.25rem"></div>
<div style="background-color: hsl(207,55%,14%);height:1.4rem;width:1.4rem;border-radius:50%;display:block;margin:0.25rem"></div>
</div>
<div class="flex">
<div>hsl(207,55%,34%)</div>,
<div>hsl(207,55%,54%)</div>,
<div>hsl(207,55%,44%)</div>,
<div>hsl(207,55%,34%)</div>,
<div>hsl(207,55%,24%)</div>,
<div>hsl(207,55%,14%)</div>,
</div>
 
## Main text color
 
<div class="flex items-center">
<div style="background-color: hsl(207,55%,10%);height:2rem;width:2rem;border-radius:50%;display:block;margin:0.25rem"></div>
<div>hsl(207,55%,14%)</div>
</div>

## Light background color

<div class="flex items-center">
<div style="background-color: hsl(207,55%,98%);height:2rem;width:2rem;border-radius:50%;display:block;margin:0.25rem"></div>
<div>hsl(207,55%,94%)</div>
</div>

## Accents

<div class="flex items-center">
<div style="background-color: #DD403A;height:2rem;width:2rem;border-radius:50%;display:block;margin:0.25rem"></div>
<div>#DD403A</div>
</div>
<div class="flex items-center">
<div style="background-color: #FDE12D;height:2rem;width:2rem;border-radius:50%;display:block;margin:0.25rem"></div>
<div>#FDE12D</div>
</div>

Feel free to adjust the accents if they don't fit well

---

# Fonts

- **Headers**: [Cantarell](https://fonts.google.com/specimen/Cantarell) regular
- **Body**: [Noto Sans SC](https://fonts.google.com/specimen/Noto+Sans+SC) regular
