# ⟨HTML⟩ Cheat Sheet & DevFolio Project

> A self-contained, interactive HTML learning toolkit — cheat sheet, hands-on project, and quick reference all in one file.

---

## What Is This?

This is a **single-file HTML learning kit** built for anyone who wants to go from knowing basic HTML tags to confidently using every major one in a real project. It has three parts, accessible from a top navigation bar:

| Tab | What's Inside |
|-----|---------------|
| **Cheat Sheet** | Every HTML tag grouped by category with hover descriptions |
| **Project** | 10 guided tasks to build a full developer portfolio using HTML only |
| **Quick Ref** | A searchable table of 80+ tags with categories, descriptions, and key attributes |

---

## The Project — DevFolio

You will build **DevFolio**, a complete personal portfolio website for a fictional developer named *Alex Rivera*. The project is split into **10 progressive tasks**, each targeting a specific group of HTML tags.

**Rules:**
- Write everything in a single `index.html` file
- Pure HTML only — no CSS, no JavaScript required
- Complete tasks in order (each one builds on the previous)

---

## 📋 Task Breakdown

### Task 01 — Document Skeleton
**Tags:** `<!DOCTYPE>` `<html>` `<head>` `<meta>` `<title>` `<body>`

Set up the full document boilerplate. Add charset, viewport, description, and author meta tags. Every HTML file starts here.

---

### Task 02 — Navigation Bar
**Tags:** `<nav>` `<ul>` `<li>` `<a>`

Build a semantic navigation bar with 5 anchor links (`#hero`, `#about`, `#skills`, `#projects`, `#contact`) that jump to sections within the page.

---

### Task 03 — Hero Section
**Tags:** `<header>` `<h1>` `<h2>` `<h3>` `<p>` `<strong>` `<em>` `<br>` `<hr>`

Create the intro/hero area. Use `<strong>` to bold the name, `<em>` for italic emphasis, `<br>` for a line break inside a paragraph, and `<hr>` as a visual divider below.

---

### Task 04 — About Section
**Tags:** `<section>` `<article>` `<aside>` `<figure>` `<figcaption>` `<img>` `<dl>` `<dt>` `<dd>`

Add a profile image inside a `<figure>` with a `<figcaption>`. Write a bio inside `<article>`. Use `<aside>` with a `<dl>` description list for quick facts (location, experience, languages, etc.).

---

### Task 05 — Skills Table
**Tags:** `<table>` `<caption>` `<thead>` `<tbody>` `<tfoot>` `<tr>` `<th>` `<td>`

Build a skills table with proper semantic structure — a caption, a header row, at least 5 body rows (skill, level, years of experience), and a footer row summarizing totals.

---

### Task 06 — Projects Section
**Tags:** `<main>` `<details>` `<summary>` `<blockquote>` `<cite>` `<code>` `<pre>` `<abbr>`

Wrap content in `<main>`. Create 3 expandable project cards using `<details>` + `<summary>`. Each card includes a description, a `<pre><code>` snippet, a `<blockquote>` testimonial with `<cite>`, and `<abbr>` for a technical term.

---

### Task 07 — Contact Form
**Tags:** `<form>` `<fieldset>` `<legend>` `<label>` `<input>` `<select>` `<option>` `<optgroup>` `<textarea>` `<button>` `<datalist>`

Build a fully structured contact form grouped into two `<fieldset>` blocks. Include input types: `text`, `email`, `tel`, `number`, `date`, `checkbox`, `radio`. Add a `<select>` dropdown, a `<textarea>`, and both a `submit` and `reset` `<button>`. Every input must have a matching `<label for="id">`.

---

### Task 08 — Media Section
**Tags:** `<video>` `<audio>` `<source>` `<picture>` `<iframe>` `<track>`

Embed an HTML5 `<video>` player, an `<audio>` player, a responsive `<picture>` element with multiple `<source>` breakpoints, and a YouTube video via `<iframe>`.

---

### Task 09 — Footer
**Tags:** `<footer>` `<address>` `<time>` `<small>` `<sup>` `<sub>`

Create a semantic footer with `<address>` for contact info (name, city, mailto link), a `<time datetime="YYYY">` for the copyright year, `<small>` for fine print, and use `<sup>` / `<sub>` somewhere in the content (e.g., E=mc², H₂O).

---

### Task 10 — Bonus: Advanced Tags
**Tags:** `<mark>` `<del>` `<ins>` `<progress>` `<meter>` `<kbd>` `<datalist>` `<output>`

Scatter advanced semantic tags throughout the page:
- `<mark>` to highlight availability status
- `<del>` + `<ins>` to show a price update
- `<progress>` for a profile completion bar
- `<meter>` for a skill rating gauge
- `<kbd>` to show a keyboard shortcut
- `<datalist>` + `<input list="id">` for a tech search

---

## Tag Coverage by Category

| Category | Tags Covered |
|----------|-------------|
| Document Structure | `<!DOCTYPE>` `<html>` `<head>` `<body>` `<meta>` `<title>` `<link>` `<style>` `<script>` `<noscript>` |
| Semantic Layout | `<header>` `<nav>` `<main>` `<section>` `<article>` `<aside>` `<footer>` `<div>` `<span>` |
| Headings & Text | `<h1>`–`<h6>` `<p>` `<br>` `<hr>` `<pre>` `<blockquote>` `<q>` `<address>` |
| Inline Formatting | `<strong>` `<em>` `<b>` `<i>` `<u>` `<s>` `<mark>` `<small>` `<sup>` `<sub>` `<del>` `<ins>` `<abbr>` `<cite>` `<time>` |
| Code & Technical | `<code>` `<kbd>` `<samp>` `<var>` `<pre>` |
| Lists | `<ul>` `<ol>` `<li>` `<dl>` `<dt>` `<dd>` |
| Links & Media | `<a>` `<img>` `<picture>` `<source>` `<video>` `<audio>` `<track>` `<iframe>` `<canvas>` `<svg>` |
| Tables | `<table>` `<caption>` `<thead>` `<tbody>` `<tfoot>` `<tr>` `<th>` `<td>` `<colgroup>` `<col>` |
| Forms | `<form>` `<input>` `<label>` `<button>` `<select>` `<option>` `<optgroup>` `<textarea>` `<fieldset>` `<legend>` `<datalist>` `<output>` `<progress>` `<meter>` |
| Interactive | `<details>` `<summary>` `<dialog>` `<template>` |
| Figure | `<figure>` `<figcaption>` |
| Deprecated  | `<font>` `<center>` `<marquee>` `<blink>` `<strike>` `<tt>` `<acronym>` |

---

## Tips for Beginners

- Always validate your HTML at [validator.w3.org](https://validator.w3.org) after each task.
- Use VS Code with the **Prettier** extension to auto-format your HTML.
- Open your `index.html` directly in Chrome/Firefox — just drag the file into the browser.
- Use `Ctrl + U` (or `Cmd + U` on Mac) in the browser to view the page source.
- Don't worry about styling — focus on structure. CSS comes after HTML.

---

## Semantic HTML — Why It Matters

Using the right tag for the right purpose isn't just about correctness — it has real-world impact:

| Benefit | Why It Matters |
|---------|---------------|
| **Accessibility** | Screen readers use semantic tags to navigate content for visually impaired users |
| **SEO** | Search engines give more weight to content in `<article>`, `<h1>`, `<nav>` etc. |
| **Maintainability** | Semantic code is easier to read and collaborate on |
| **Performance** | Proper structure reduces the need for extra CSS classes and JavaScript hooks |

---

## Further Learning

| Resource | Link |
|----------|------|
| MDN Web Docs (HTML) | https://developer.mozilla.org/en-US/docs/Web/HTML |
| HTML Living Standard | https://html.spec.whatwg.org |
| W3Schools HTML Ref | https://www.w3schools.com/tags |
| HTML Validator | https://validator.w3.org |
| Can I Use (browser support) | https://caniuse.com |

---

## License

This project is for **educational use only**. Feel free to use, share, and modify it for learning purposes.

---

*Built as a hands-on HTML learning resource. No frameworks. No build tools. Just HTML.*
