# 🍔 Responsive Food Website UI

This project is a **responsive landing page** for a food-related website, built using **HTML and CSS**. It includes a **navigation bar**, **hero section**, and an **image-text block** layout, designed to work seamlessly across different screen sizes.

---

## 📁 Folder Structure

```
project-root/
├── index.html         # Main HTML file
├── index.css          # Linked CSS file for styling
├── images/
│   ├── Burger.jpg     # Hero image
│   ├── image1.jpg     # Image column 1
│   ├── image2.jpg     # Image column 2
│   ├── image3.jpg     # Main vertical image
│   └── arrow.png      # CTA arrow icon
│   └── menu-bar.png   # Mobile menu icon
```

---

## 🌟 Features

### ✅ Layout Components

* **Navigation Bar**

  * Logo / Menu Icon (for mobile)
  * Navigation links (`Home`, `Order`, `Food`, etc.)

* **Hero Section**

  * Left: Text with heading, description, and button
  * Right: Full-height image

* **Image & Text Flex Section**

  * Left: A 2-column image gallery
  * Right: Text block with heading, subheading, and CTA (Click + arrow)

---

## 🎨 Fonts Used

* [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) (for body)
* [Roboto](https://fonts.google.com/specimen/Roboto) (for hero, buttons, and content)

---

## 📱 Responsiveness

The layout is **fully responsive** using media queries. Breakpoints are used to adjust the design for smaller screens:

### 🖥 Desktop (Above 768px)

* Full nav menu is visible
* Flex layout for hero and image-text sections
* Larger image sizes and padding

### 📱 Tablet (Max-width: 768px)

* Navbar links hidden; menu icon displayed
* Hero switches to vertical layout
* Image-text section stacks vertically
* Image sizes and text font sizes reduced

### 📲 Mobile (Max-width: 480px)

* Further reduction in font and image sizes
* Images rearranged horizontally inside columns
* Padding reduced for better fit
* Text blocks and buttons expand to full width

---

## 🛠 Technologies Used

* **HTML5** – Markup structure
* **CSS3** – Styling and responsiveness
* **Flexbox** – Layout arrangement
* **Media Queries** – Responsive breakpoints
* **Google Fonts** – Custom typography

---

## 🔄 How It Works

1. **Base Styles** – All elements reset using `* { margin: 0; padding: 0; box-sizing: border-box; }` for consistency.
2. **Flexbox Layout** – Used across the layout (`display: flex`) to handle positioning.
3. **Gradient Backgrounds** – Applied to sections for a modern aesthetic.
4. **Responsive Design** – Uses media queries at 768px and 480px to adapt layout and style.
5. **Hover Effects** – On buttons for interactivity.
6. **Custom Fonts** – Loaded via Google Fonts for a modern, elegant look.

---

## ✅ To Run

Simply open the `index.html` file in any modern browser.

---

## 📝 Author Notes

* Images (`Burger.jpg`, `image1.jpg`, etc.) are placeholders. You can replace them with real assets.
* JavaScript is not included, but you can easily add interactivity (like toggling the nav on mobile).

---

Let me know if you'd like this in downloadable `.md` format or need help deploying it to GitHub Pages or another platform.
