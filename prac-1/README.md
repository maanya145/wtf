# Practical 1 - GreenLeaf Organics Website

## Objective

The main objective of this practical is to learn the basics of HTML and CSS by building a simple static webpage for a fictional company called **GreenLeaf Organics** (an organic food company).

In this practical I learned how to:

- Create a proper HTML5 document structure
- Use semantic tags like `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>` and `<footer>`
- Make a navigation menu using internal links
- Display data in a table
- Build a simple contact form with labels and inputs
- Style the whole page using an external CSS file

## Folder Structure

```
prac-1/
│
├── index.html                      -> Main homepage of GreenLeaf Organics
├── style.css                       -> CSS file for styling the main page
├── README.md                       -> This file
│
└── supplementary/
    │
    ├── supp-1-college-department/  -> Supplementary problem 1 (College Department page)
    │   ├── index.html
    │   └── style.css
    │
    └── supp-2-ngo/                 -> Supplementary problem 2 (NGO page)
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
2. Go to the `prac-1` folder.
3. Double click on `index.html` and it will open in your default browser.

Same thing can be done for the supplementary pages, just open their `index.html` files also.


### Method 2: Using Python's built-in server

If you have Python installed, run this command from inside the `prac-1` folder:

```bash
python3 -m http.server 8000
```

Then open your browser and go to:

```
http://localhost:8000
```
