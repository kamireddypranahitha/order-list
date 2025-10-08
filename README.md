# 🍲 Andhra Foods Digital Menu (T4-orderlist.html)

This is a simple, single-page HTML file designed to display a restaurant menu, "ANDHRA FOODS." It serves as a fundamental example of using **ordered lists (`<ol>`)** and basic styling to present structured data.

---

## ✨ Key Features

* **Menu Categories:** The content is neatly organized into three main categories: **Main Course**, **Desserts**, and **Today Special Menu**.
* **Ordered Lists:** Each menu category uses an ordered list (`<ol>`) to number the items.
* **Internal CSS:** Styling is defined within the `<style>` block in the `<head>`:
    * The main **`<h1>`** title has a black background, is centered, and uses white text.
    * The category headings **`<h2>`** use the Verdana font family and are colored light yellow.
* **Background Color:** The entire page body has a **dark red** background (`bgcolor="darkred"`).
* **Text Styling:** The main course list uses the deprecated **`<font>`** tag to color the text light yellow.

---

## 🍽️ Menu Highlights

The menu is extensive, featuring various dishes, including:

| Category | Example Item | Price |
| :--- | :--- | :--- |
| **Main Course** | Andhra Chicken Biryani | 150 Rs |
| | Gongura Mutton Biryani | 200 Rs |
| | Palakura Pappu with Ghee Rice | 90 Rs |
| **Desserts** | Butterscotch | 70 Rs |
| **Today Special**| Bamboo Chicken | 200 Rs |

---

## 💻 Code Structure

The file demonstrates the mixing of HTML structural tags and styling methods:

```html
<body bgcolor="darkred">
  <h1>ANDHRA FOODS</h1>
  <h2>Main Course</h2>
  <h3><ol>
    </ol></h3>
  </body>
