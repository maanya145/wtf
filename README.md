# WTF - ITUS102: Web Technology Framework

Lab work for **ITUS102: Web Technology Framework**, Semester 1, Faculty of Technology, CHARUSAT.

Each practical folder holds the main implementation, and a `supplementary/` folder holding the solutions to the supplementary problems for that practical. The write-ups for each practical are in `docs/`.

## Objective

Build web pages that apply the concepts covered in the course, starting with semantic HTML5 structure and version control, then responsive styling with CSS3, and maintain the whole thing in a single Git repository with a readable commit history.

## Folder Structure

```
wtf/
├── README.md
├── docs/
│   ├── ITUS102_Practical_1.docx        # Practical 1 write-up
│   └── ITUS102_Practical_2.docx        # Practical 2 write-up
├── prac-1/                             # Semantic HTML5 + Git and GitHub
│   ├── index.html
│   ├── style.css
│   └── supplementary/
│       ├── supp-1-college-department/  # Department homepage
│       │   ├── index.html
│       │   └── style.css
│       └── supp-2-ngo/                 # NGO homepage
│           ├── index.html
│           └── style.css
└── prac-2/                             # Responsive CSS3 with Flexbox and Grid
    ├── index.html
    ├── style.css
    └── supplementary/
        ├── supp-1-hospital/            # Hospital homepage
        │   ├── index.html
        │   └── style.css
        ├── supp-2-ecommerce/           # E-commerce landing page
        │   ├── index.html
        │   └── style.css
        └── supp-3-portfolio/           # Developer portfolio
            ├── index.html
            └── style.css
```

Supplementary problem 3 of Practical 1 asks for a project README file. This file is that deliverable.

## Practicals

### Practical 1 - Semantic HTML5 and version control (CO1)

A homepage for GreenLeaf Organics Pvt. Ltd. built entirely from semantic structural elements.

| Section | Element used | Content |
|---|---|---|
| Company banner | `header` + `.banner` | Company name and tagline |
| Navigation | `nav` | Links to every section |
| About | `section` + `article` | Company background |
| Products | `section` + `table` | Product, weight, price |
| Services | `section` + `ul` | Services offered |
| Featured | `section` | Offer of the week |
| Store timings | `aside` | Supporting information |
| Contact | `section` + `form` + `address` | Enquiry form and address |
| Footer | `footer` | Copyright and back to top |

### Practical 2 - Responsive design with CSS3 (CO2)

A responsive homepage for the Department of Computer Engineering.

- Navigation built with **Flexbox** (`flex-wrap` and `gap`)
- Program and facility cards built with **CSS Grid** (`repeat(2, 1fr)`)
- News and sidebar built with a **2fr / 1fr grid**
- **Media queries** at `768px` (stack navigation, collapse grids to one column) and `480px` (reduce font size and padding)
- Cascading and inheritance used deliberately: base font and colour set once on `body`, overrides handled by specificity rather than `!important`

## Technologies Used

- HTML5 (semantic elements, forms, tables, metadata)
- CSS3 (selectors, box model, Flexbox, CSS Grid, media queries)
- Git for local version control
- GitHub for the remote repository and commit history
- Visual Studio Code
- Google Chrome and Mozilla Firefox with browser developer tools
- W3C HTML Validator

## Steps to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/maanya145/wtf.git
   ```
2. Move into the practical you want to view:
   ```bash
   cd wtf/prac-1
   ```
3. Open `index.html` in Google Chrome or Mozilla Firefox, or use the Live Server extension in Visual Studio Code.

The supplementary pages run the same way, from inside their own folders.

No build step, server, or dependency installation is required, since the project uses only HTML5 and CSS3.

## Testing and Validation

- Markup checked with the [W3C HTML Validator](https://validator.w3.org/) and reported errors resolved.
- Responsiveness checked using the device toolbar in browser developer tools at desktop, tablet, and mobile widths.
- Pages verified in at least two modern browsers.

## Author

Maanya | Semester 1 | Faculty of Technology, CHARUSAT
