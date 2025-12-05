# **Cheat Sheet: How the Web Works (Intro Concepts)**

### **1. The Web & Browser**

* **Web:** Network of connected computers sharing information
* **Browser (Client):** Requests and displays webpages (Chrome, Firefox)
* **Server:** Stores and sends webpage content
* **URL:** Web address typed in the browser to start a connection

---

### **2. Request / Response Cycle**

* **HTTP Request:** Browser asks server for a resource
* **HTTP Response:** Server sends resource back
* **Status Codes:**

  * `200` → OK
  * `404` → Not Found
  * `500` → Server Error
* **HTTPS:** Secure, encrypted version of HTTP

---

### **3. HTML — Structure**

* **HTML (HyperText Markup Language):** Defines page content and structure
* **Common Elements:**

  * `<h1>` → Heading
  * `<p>` → Paragraph
  * `<a>` → Link
  * `<img>` → Image

---

### **4. CSS — Presentation**

* **CSS (Cascading Style Sheets):** Styles the HTML content
* **Controls:**

  * Colors, fonts, spacing
  * Layout and positioning
* **How it works:** Browser combines HTML + CSS to display styled content

---

### **5. How a Page Loads**

1. Browser requests HTML
2. Parses HTML and discovers additional resources (CSS, images, JS)
3. Requests those resources
4. Combines all and renders the page

---

### **Quick Tips**

* Every page involves multiple **request-response cycles**
* **HTML = structure**, **CSS = style**, **JavaScript = behavior**
* HTTPS is essential for **secure communication**
* Use **DevTools** to inspect HTML, CSS, and network requests

---
