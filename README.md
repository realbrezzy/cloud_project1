# 🛍️ Static E-Commerce Product Cards Project

This is a **static HTML & CSS** project that displays product cards in an e-commerce style layout, complete with a **search bar** at the top.  
The cards are **responsive** for different screen sizes and include product images, titles, and prices.  
It’s designed for beginners and learners who want to understand HTML & CSS layout styling, along with simple JavaScript search filtering.

---

## Group Members

| Name                     | Registration Number |
| ------------------------ | ------------------- |
| \[Manzi Ivan]            | \[2309000412]       |
| \[Ntakirutimana Patrick] | \[2405000436]       |
| \[Bahati Yves]           | \[2305000895]       |
| \[Mucyo pacifique]       | \[230900050]        |

## 📂 Project Structure

ecommerce-cards/<br>
│<br>
├── index.html # Main HTML file<br>
├── style.css # Styles for the project<br>
└── images/ # Product images (loaded from Unsplash in this example)<br>

---

## ✨ Features

- **Responsive Layout**: Works on desktops, tablets, and mobile devices.
- **Search Bar**: Filters product cards in real-time based on the text typed.
- **Card Design**: Each card has an image, a title, and a price.
- **Static Content**: No backend needed — works purely with HTML, CSS, and a small JavaScript snippet.
- **Image Sourcing**: Images are fetched from [Unsplash](https://unsplash.com/) for demonstration purposes.

---

## 🛠️ Technologies Used

- **HTML5**: Markup structure.
- **CSS3**: Styling, layout, responsiveness.
- **JavaScript**: Implements the search filter functionality.

---

## 📜 How It Works

1. **HTML Layout**

   - A `<header>` contains the search bar.
   - The `<main>` section contains a grid of product cards.
   - Each card includes:
     - An image (same size for all)
     - A title (product name)
     - A price tag

2. **CSS Styling**

   - Uses **CSS Grid** for responsive card layout.
   - Adds hover effects to the cards.
   - Makes images fixed in size for uniformity.
   - Adjusts layout for smaller screens with media queries.

3. **JavaScript Function**
   - Listens for `input` changes in the search bar.
   - Filters product cards in real time based on matching product names.
   - Hides cards that don’t match the search query.

---

## 📷 Example Screenshot

**Desktop View:**

[ Search bar at top ]<br>
[ Card 1 ]<br>
[ Card 2 ]<br>
[ Card 3 ]<br>
[ Card 4 ]<br>
[ Card 5 ]<br>
[ Card 6 ]<br>

**Mobile View:**

[ Search bar ]<br>
[ Card 1 ]<br>
[ Card 2 ]<br>
[ Card 3 ]<br>
