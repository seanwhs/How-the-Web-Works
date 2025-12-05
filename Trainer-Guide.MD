# **Trainer Guide: How the Web Works (Intro Concepts)**

## **Module Overview**

**Goal:** Introduce learners to how the web functions, from typing a URL to viewing a fully rendered page.
**Duration:** ~60–75 minutes
**Audience:** Beginners or non-technical learners interested in web basics.

**Learning Outcomes:**
By the end of the module, learners should be able to:

1. Explain the roles of browsers and servers.
2. Describe the request/response cycle.
3. Identify basic HTML and CSS components.
4. Understand how a web page is loaded and displayed.

---

## **1. The Web & the Browser**

**Duration:** 10–15 minutes

**Key Points to Cover:**

* **The Web:** A system of connected documents and resources accessible via the internet.
* **Browser vs. Server:**

  * Browser = *client*: Requests and displays content.
  * Server: Stores content and responds to requests.
* **URL (Uniform Resource Locator):** The “address” of a web resource.
* When you type a URL: browser finds the server → asks for the page → displays it.

**Trainer Notes:**

* Use real-world analogy: Browser = customer, Server = restaurant, URL = menu item.
* Show popular browsers (Chrome, Firefox, Safari).

**Activity / Demonstration:**

* Ask learners to open a browser and type a simple URL (e.g., `example.com`).
* Explain what’s happening “behind the scenes” as the page loads.

---

## **2. Request / Response Cycle**

**Duration:** 10–15 minutes

**Key Points to Cover:**

* **HTTP (Hypertext Transfer Protocol):** The “language” browsers and servers use.
* Browser sends an **HTTP request** → server responds with **HTTP response**.
* **Status Codes:**

  * 200 = OK (successful)
  * 404 = Not Found
  * 500 = Server Error
* **HTTPS:** Adds encryption for secure communication (important for privacy).

**Trainer Notes:**

* Visualize with a simple diagram showing browser → request → server → response → browser.
* Emphasize why HTTPS is important (security, trust).

**Activity / Demonstration:**

* Show DevTools in browser → Network tab → reload page to see requests/responses.
* Show a 404 page and explain what went wrong.

---

## **3. HTML — Structure**

**Duration:** 10–15 minutes

**Key Points to Cover:**

* **HTML (Hypertext Markup Language):** Defines content and structure.
* **Elements & Tags:** `<h1>` to `<h6>` for headings, `<p>` for paragraphs, `<a>` for links.
* **Basic page structure:**

  ```html
  <html>
    <head><title>My Page</title></head>
    <body>
      <h1>Welcome!</h1>
      <p>This is a paragraph.</p>
      <a href="https://example.com">Link</a>
    </body>
  </html>
  ```

**Trainer Notes:**

* Compare HTML to the skeleton of a building: structure only, no style.
* Emphasize that HTML is semantic (headings, paragraphs, links).

**Activity / Demonstration:**

* Open a simple HTML file in a browser.
* Inspect page source to identify headings, paragraphs, and links.

---

## **4. CSS — Presentation**

**Duration:** 10–15 minutes

**Key Points to Cover:**

* **CSS (Cascading Style Sheets):** Controls presentation (colors, fonts, layout).
* CSS works **with** HTML, not instead of it.
* Example:

  ```css
  body { font-family: Arial; color: #333; }
  h1 { color: blue; }
  p { margin: 10px 0; }
  ```
* Styles can be inline, internal, or external.

**Trainer Notes:**

* Analogy: HTML = structure, CSS = paint and interior design.
* Highlight how CSS makes pages visually appealing and readable.

**Activity / Demonstration:**

* Apply a CSS rule in DevTools to change a heading color.
* Compare before/after to show impact of CSS.

---

## **5. How a Page Loads**

**Duration:** 10 minutes

**Key Points to Cover:**

* Browser requests HTML → parses it → finds additional resources (CSS, images, JS).
* Browser sends additional requests for each resource → combines everything.
* Rendering: Browser paints the page for the user to see.

**Trainer Notes:**

* Emphasize sequence: HTML → CSS → images → scripts → rendering.
* Explain why pages may appear progressively as resources load.

**Activity / Demonstration:**

* Use Chrome DevTools → Network tab → reload page and observe the sequence of requests.
* Point out how different file types load separately.

---

## **Trainer Tips**

* Keep technical terms simple; use analogies wherever possible.
* Encourage questions at each stage—this topic is very visual.
* Use live demos—they help learners “see” the web in action.
* Keep exercises small and interactive.

---
