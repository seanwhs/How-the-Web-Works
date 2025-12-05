# **Learner Guide: How the Web Works (Intro Concepts)**

## **1. The Web & the Browser**

* **The Web:** A global network of connected computers sharing information.
* **Browser (Client):** The program you use to visit websites (e.g., Chrome, Firefox).
* **Server:** The computer that stores and delivers webpages.
* **URL:** Typing a URL starts the connection between your browser and the server.

**Key Point:** The browser requests pages, the server sends them back.

---

## **2. Request / Response Cycle**

* When you visit a website, your browser sends an **HTTP request** to the server.
* The server responds with an **HTTP response**, which contains the page content.
* **Status Codes:**

  * `200` → OK (page loaded successfully)
  * `404` → Not Found (page doesn’t exist)
* **HTTPS:** A secure version of HTTP that encrypts communication.

**Tip:** Every webpage you load involves multiple request-response cycles for HTML, CSS, images, and scripts.

---

## **3. HTML — Structure of a Webpage**

* **HTML (HyperText Markup Language):** The language that defines the content and structure of a webpage.
* **Elements & Tags:** Building blocks of HTML. Examples:

  * `<h1>` → Headings
  * `<p>` → Paragraphs
  * `<a>` → Links
  * `<img>` → Images

**Key Point:** HTML provides the blueprint for the webpage.

---

## **4. CSS — Style & Presentation**

* **CSS (Cascading Style Sheets):** Adds style and visual design to HTML content.
* Controls:

  * Colors and fonts
  * Spacing and alignment
  * Layout and positioning
* CSS works with HTML to make pages visually appealing.

**Tip:** Changing CSS changes how a page looks, not its content.

---

## **5. How a Page Loads**

1. Browser requests the HTML file from the server.
2. Browser parses the HTML and finds additional resources (CSS, images, scripts).
3. Browser requests those resources from the server.
4. Browser combines all files and renders the final page on screen.

**Key Point:** Loading a webpage is a multi-step process that happens very quickly.

---

## **6. Summary**

* Browser connects to a server using a URL.
* Browser sends an **HTTP request**; server sends an **HTTP response**.
* **HTML** provides page content and structure.
* **CSS** adds style and layout.
* Browser assembles all resources and renders the page.

---

## **Optional Activities**

* Inspect a webpage using browser DevTools (look at HTML, CSS, and network requests).
* Create a simple HTML page with headings, paragraphs, and links.
* Apply CSS to style text, colors, and spacing.

---
