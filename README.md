# Mooneria Website 💇‍♀️

_A responsive website for Mooneria, a hair salon offering braids, event hairstyles, straightening, coloring, cuts, treatments and bridal styling._

## Getting Started 🚀

_These instructions will give you a copy of the project up and running on your local machine for development and testing purposes._

### Prerequisites 📋

_What you need to run the project:_

* A modern web browser (Chrome, Firefox, Edge or Safari)
* A code editor, such as Visual Studio Code

No server or extra installation is needed, since it is a static website.

### Installation 🔧

_Step by step to get a development environment running:_

Download or clone the project:

```
git clone [your-repository-url]
```

Open the project folder:

```
cd peluqueria-monica
```

Open `index.html` in your browser (double-click the file, or use the *Live Server* extension in Visual Studio Code).

## Project Structure 📁

```
peluqueria-monica/
├── index.html
├── ccs/
│   └── style.css
└── img/
    ├── peluqueriaMonica.png
    ├── trenzas.jpg
    ├── eventos.jpg
    ├── alisado.webp
    └── color.png
```

## Adding New Photos 🖼️

_To add a new photo to a gallery, copy this block inside the `gallery-card-container` of the section you want:_

```html
<div class="gallery-card">
    <div class="gallery-card-image-container">
        <img src="img/YOUR-PHOTO.jpg" alt="Photo description">
    </div>
    <p>Text under the photo</p>
</div>
```

_All photos are displayed at the same size automatically._

## Responsive Design 📱

The layout adapts to the screen size:

* **Desktop (over 1024px):** 4 photos per row
* **Tablet (601px to 1024px):** 3 photos per row
* **Mobile (600px or less):** 2 photos per row

## Built With 🛠️

* HTML5 - Page structure
* CSS3 (Flexbox and media queries) - Styling and responsive layout
* [Google Material Symbols](https://fonts.google.com/icons) - Menu icon

## Authors ✒️

* **[Mónica]** - *Design and development* - [your-profile-link]


  
# Acknowledgements 🎁

Thanks to Tiburcio, our favourite teacher, for teaching us how to become a website content creator.

---
✂️ made with ❤️ for Peluquería Mónica 😊
