# **Lesson Plan: How the Web Works (Intro Concepts)**

**Grade / Level:** Beginner / Intro to Web
**Duration:** 50–55 minutes
**Objective:** Students will understand how the web works, including client-server interactions, the request/response cycle, HTML structure, CSS presentation, and the process of page loading. By the end of the lesson, students will be able to explain these concepts and identify key elements in a webpage.

---

## **Materials Needed**

* Projector or screen for slides
* Web browser (for live demo)
* Code editor (VS Code, Sublime Text, Atom, etc.)
* Sample HTML/CSS files for demonstrations
* Optional: internet connection for live examples

---

## **Lesson Outline**

### **1. Introduction: The Web & the Browser (5–7 min)**

**Objective:** Students understand what the web is and how browsers interact with servers.

**Content / Activities:**

* Ask: *“What do you think happens when you type a URL in a browser?”*
* Explain **client vs. server**:

  * Browser = client (requests resources)
  * Server = delivers responses
* Define **URL**: Uniform Resource Locator
* Visual: Slide showing client-server interaction
* Quick demo: Open a website and show network requests in browser DevTools

---

### **2. Request/Response Cycle & HTTP Basics (7–10 min)**

**Objective:** Students understand how data travels between browser and server.

**Content / Activities:**

* Explain **HTTP / HTTPS**: Hypertext Transfer Protocol; HTTPS = secure
* Discuss **status codes**: 200 (OK), 404 (Not Found), 500 (Server Error)
* Demo: Inspect network requests and responses in DevTools
* Optional: Compare HTTP vs HTTPS requests

---

### **3. HTML — Structure (10–12 min)**

**Objective:** Students learn the basic structure and elements of an HTML page.

**Content / Activities:**

* Define HTML: HyperText Markup Language
* Introduce **elements, tags, and attributes**:

  * Paired tags: `<p>Text</p>`
  * Single tags: `<br>`, `<hr>`, `<img>`
  * Attributes: `src`, `alt`, `href`, `id`, `class`
* Walk through a **basic HTML page structure**:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My First Web Page</title>
</head>
<body>
  <h1>Welcome to My Web Page</h1>
  <p>This is a paragraph of text.</p>
</body>
</html>
```

* Explain headings `<h1>`–`<h6>` and paragraphs `<p>`
* Activity: Students edit a paragraph or heading and refresh the browser

---

### **4. CSS — Presentation (7–8 min)**

**Objective:** Students understand how CSS controls style and layout.

**Content / Activities:**

* Explain CSS purpose: colors, fonts, spacing, layout
* Introduce **ways to add CSS**: inline, internal (`<style>`), external (`<link rel="stylesheet">`)
* Quick demo: change background color, font, or text color in DevTools
* Discuss how CSS works together with HTML to style pages

---

### **5. How a Page Loads (5–7 min)**

**Objective:** Students understand the steps a browser takes to load a webpage.

**Content / Activities:**

* Explain process:

  1. Browser requests HTML → parses it
  2. Requests additional resources (CSS, images, scripts)
  3. Combines all resources → renders page
* Visual: Diagram of page loading process
* Demo: Open a page and observe network requests in DevTools

---

### **6. Summary & Q&A (5 min)**

* Recap key points:

  * What the web is, client vs. server
  * HTTP request/response and status codes
  * HTML structure, tags, and elements
  * CSS styling and presentation
  * How a page loads step by step
* Ask students to identify HTML elements and CSS styles on a live website

---

### **Optional Extension / Homework**

* Inspect a webpage in DevTools to see requests/responses
* Create a simple HTML page with headings, paragraphs, links, images, and CSS styling
* Explain in writing how the page loads and which resources are requested

---

✅ **Highlights in This Lesson Plan:**

* Clear objectives for each section
* Combination of theory, visuals, and live demos
* Beginner-friendly explanations
* Step-by-step flow from web concepts → HTML → CSS → page loading

---
