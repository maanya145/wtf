# Practical 2 - College Department Website

## Objective

The main objective of this practical is to practice HTML and CSS by building a simple static webpage for the **Department of Computer Engineering, CHARUSAT University**.

In this practical I learned how to:

- Create a proper HTML5 document structure
- Use semantic tags like `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` and `<footer>`
- Make a navigation menu using internal links
- Display content in card layout using `div` and CSS grid
- Use an `<aside>` section for quick links
- Style the whole page using an external CSS file

## Folder Structure

```
prac-2/
│
├── index.html                  -> Main homepage of Computer Engineering Department
├── style.css                   -> CSS file for styling the main page
├── README.md                   -> This file
│
└── supplementary/
    │
    ├── supp-1-hospital/        -> Supplementary problem 1 (Hospital page)
    │   ├── index.html
    │   └── style.css
    │
    ├── supp-2-ecommerce/       -> Supplementary problem 2 (E-commerce page)
    │   ├── index.html
    │   └── style.css
    │
    └── supp-3-portfolio/       -> Supplementary problem 3 (Portfolio page)
        ├── index.html
        └── style.css
```

## Technologies Used

- **HTML5** - for the structure and content of the webpages
- **CSS3** - for styling (external stylesheet)
- No frameworks, no JavaScript, no build tools are used. Everything is plain HTML and CSS.

## How to Run Locally

This is a simple static website, so there is nothing to install.

### Method 1: Open the file

1. Download or clone this folder on your computer.
2. Go to the `prac-2` folder.
3. Double click on `index.html` and it will open in your default browser.

Same thing can be done for the supplementary pages, just open their `index.html` files also.


### Method 2: Using Python's built-in server

If you have Python installed, run this command from inside the `prac-2` folder:

```bash
python3 -m http.server 8000
```

Then open your browser and go to:

```
http://localhost:8000
```
