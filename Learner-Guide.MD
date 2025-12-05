# **Learner Guide: How the Web Works (Intro Concepts)**

## **Module Overview**

Welcome! In this module, you will learn how the web works, how browsers communicate with servers, and the basics of creating and styling webpages using HTML and CSS. By the end of this guide, you’ll understand:

* How the web and browsers work
* The HTTP request/response cycle
* How HTML structures content
* How CSS styles content
* How a browser loads a page

---

## **1. The Web & the Browser**

### **What the Web Is**

The web is a system of interconnected documents and resources accessed over the internet using browsers.

* **Browser (Client):** Software used to access web pages (e.g., Chrome, Firefox).
* **Server:** A computer that stores web pages and sends them to browsers upon request.

### **Typing a URL → Starting a Connection**

When you type a URL like `https://example.com`:

1. The browser checks if it knows the server’s address (DNS lookup).
2. It sends a request to the server.
3. The server responds with the web page content.

**Activity:** Open a browser, type a URL, and notice how fast the page loads. That’s your browser and the server working together!

---

## **2. Request / Response Cycle**

When a browser loads a page, it communicates with a server using **HTTP** (HyperText Transfer Protocol).

### **How it Works:**

1. **HTTP Request:** Browser asks the server for a resource (like an HTML page).
2. **HTTP Response:** Server sends the requested page or an error message.

### **Status Codes**

| Code | Meaning                  |
| ---- | ------------------------ |
| 200  | OK (success)             |
| 404  | Not Found (page missing) |
| 500  | Internal Server Error    |

### **HTTPS**

* HTTPS is HTTP with encryption (secure).
* Protects data from being intercepted.

**Activity:** Open DevTools in your browser (F12), go to the Network tab, refresh a page, and check the request/response details.

---

## **3. HTML — Structure**

HTML (HyperText Markup Language) is used to define the **content and structure** of a web page.

### **Basic HTML Concepts**

* **Tags:** Define elements. Example: `<p>Text here</p>`
* **Elements:** Everything inside a tag. Example: `<h1>Heading</h1>`
* **Attributes:** Provide extra info about elements. Example: `<img src="photo.jpg" alt="My Photo">`

### **HTML Page Structure**

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Web Page</title>
</head>
<body>
  <h1>Welcome!</h1>
  <p>This is a paragraph of text.</p>
</body>
</html>
```

### **Common Tags**

* Headings: `<h1>`–`<h6>`
* Paragraphs: `<p>`
* Links: `<a href="https://example.com">Click here</a>`

**Activity:** Create a simple HTML page with a heading and a paragraph in your code editor, then open it in a browser.

---

## **4. CSS — Presentation**

CSS (Cascading Style Sheets) is used to style web pages.

### **CSS Basics**

* **Colors, fonts, spacing, and layout**
* Can be added in three ways:

  1. **Inline CSS:** `<p style="color: blue;">Text</p>`
  2. **Internal CSS:** Using `<style>` in `<head>`
  3. **External CSS:** Linking a separate `.css` file

### **Example**

```html
<style>
  body {
    background-color: lightyellow;
    font-family: Arial, sans-serif;
  }
  h1 {
    color: darkblue;
  }
</style>
```

**Activity:** Change the color or font of your heading and paragraph using CSS. Refresh the page to see the effect.

---

## **5. How a Page Loads**

When a browser loads a web page:

1. **Requests HTML** → parses it
2. **Requests additional resources** (CSS, images, scripts)
3. **Combines everything** → renders the page

**Example Diagram:**

```
Browser       Server
   |            |
   |--HTTP Req->|
   |            |
   |<--HTML----|
   |--CSS, Img->|
   |<--CSS, Img-|
   |            |
Render Page
```

**Activity:** Open a webpage, inspect it using DevTools, and notice how many files are loaded (HTML, CSS, images, scripts).

---

## **Summary**

You’ve learned:

* The web is a system of clients (browsers) and servers
* Browsers communicate via HTTP/HTTPS
* HTML gives structure to a webpage
* CSS controls styling and layout
* Browsers combine HTML, CSS, and other resources to display a page

---

### **Optional Exercise**

* Create a simple webpage with:

  * A heading and paragraph
  * A link to another website
  * An image
  * CSS styling (background color, font, text color)

---
