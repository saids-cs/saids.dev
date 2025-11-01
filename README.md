# saids.dev

> "Keep It Simple, Stupid"

This repository contains the source code for my online **Personal portfolio and Resume**. It's purpose is to serve as a centralized resourse to showcase my professional expirience, skllls and the projects i've worked on.

You can see the site here: [https://saids-cs.github.io/saids.dev/index.html](https://saids-cs.github.io/saids.dev/index.html)

## 🛠️ Used Tecnologies

This project is an **static** website that use fundamental technologies to ensure the speed and accessibility.

* **HTML5:** Semantic strucuture of the content.
* **SCSS (Sass):** CSS preprocessor used for more organized, maintainable, and modular style writing.

## 🚀 How to view the website (No installation required)

Since this project is a static website, it does not require installation.

Just open the **index.html** into you browser.

## 📁 Project Structure

The code is clearly organized and includes comments to facilitate navigation and maintenance.

saids.dev/\
├── assets/ # Recursos estáticos (imágenes, fuentes, iconos, etc.)\
├── css/ # Archivos CSS compilados y su "source map"\
│ ├── style.css # Hoja de estilos principal (generada desde SCSS)\
│ └── style.css.map\
├── pages/ # Secciones principales del sitio web (About, Contacto, Proyectos, etc.)\
│ ├── about.html\
│ ├── contact.html\
│ ├── posts.html\
│ └── projects.html\
├── scss/ # Todo el código fuente del preprocesador SCSS\
│ ├── style.scss # Archivo SCSS principal\
│ ├── _variables.scss # Definición de colores, fuentes y otros valores reusables\
│ └── _generalStyle.scss # Estilos generales, resets y utilidades\
└── index.html # Página de inicio / Landing Page

## ⚙️ Development Process (If you wish to modify the styles)

If you plan to modify the `.SCSS` files, you will need to compile the code to CSS.

1.	**REQUIREMENT:** [Sass](https://sass-lang.com/install/) must be installed.
	```bash
	npm install -g sass
	```		

2.	**Compile and watch the changes:** Run the following command. This will make the Sass watch your `scss/` folder and compile automaticly the `style.css` file inside `css` every time you save a change:
	```bash
	sass --watch scss/style.scss:css/style.css
	```

 ## 📜 License

This work is dedicated to the Public Domain under the **CC0 1.0 Universal Public Domain Dedication** license.

This means you are free to copy, modify, and distribute the code without asking for permission.


`Created by Saids Ruby`
