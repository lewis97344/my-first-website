# 👨‍💻 Build Your First Web Page

Welcome! This guide helps you create a simple web page using basic **HTML** and **CSS** styles. No coding experience needed.

---

## 🧱 Basic HTML Structure

Every web page has this skeleton:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Page</title>
  </head>
  <body>
    <!-- Your content goes here -->
  </body>
</html>
```

- `<!DOCTYPE html>`: tells the browser this is an HTML5 page.  
- `<html>`: wraps the whole page.  
- `<head>`: metadata (not visible on page).  
- `<title>`: page title shown on browser tab.  
- `<body>`: visible content goes here.

---

## ✍️ Add a Heading

```html
<h1 style="color: blue;">Hello, I’m Lewis</h1>
```

- `<h1>` is the biggest heading tag — good for main titles.  
- `style="color: blue;"` changes the text colour (this is called CSS - it's what adds styles to your website!).

---

## 📝 Add a Paragraph

```html
<p style="font-size: 16px; color: black;">
  This is a paragraph. Use it for regular text.
</p>
```

- `<p>` defines a paragraph (block of text).  
- CSS here sets font size and colour.

---

## 📋 Add a List of Your Hobbies

```html
<h2 style="color: darkgreen;">My Hobbies</h2>
<ul>
  <li>Reading</li>
  <li>Gaming</li>
  <li>Music</li>
</ul>
```

- `<h2>` is a smaller heading than `<h1>`.  
- `<ul>` means unordered list (bullets).  
- `<li>` is a list item — each hobby goes here.

---

## 🔗 Add a Link

```html
<a href="https://example.com" target="_blank" style="color: purple;">
  Visit Example
</a>
```

- `<a>` creates a clickable link.  
- `href="..."` is the link’s URL.  
- `target="_blank"` opens link in a new tab.  
- CSS changes link colour.

---

## 🖼️ Add an Image

```html
<img src="https://via.placeholder.com/150" alt="Placeholder Image" style="border: 2px solid black;" />
```

- `<img>` inserts an image.  
- `src="..."` is the image address.  
- `alt="..."` is text shown if image fails or for screen readers.  
- CSS adds a black border here.

---

## 🌍 View Your Page

1. Save your file as `index.html`.  
2. Right-click on the file in VS Code and select "Open Preview"  
3. Your web page will open in a new tab showing your first web page!

---

Feel free to change text, colours, or add more tags as you explore!  
