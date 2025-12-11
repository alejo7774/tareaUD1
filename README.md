# Proyecto Web – tareaUD1  
Desarrollo Colaborativo con Git y GitHub

Este proyecto corresponde a la Unidad Didáctica 1 del módulo **Desarrollo colaborativo en entornos de programación**.  
El objetivo es construir una página web básica y aplicar el flujo de trabajo profesional con Git, GitHub, ramas, commits y Pull Requests.


## 📑 Tabla de Contenido

1. [Descripción del proyecto](#descripcion-del-proyecto)  
2. [Instalación del repositorio](#instalacoón-del-repositorio)  
3. [Estructura del proyecto](#estructura-del-proyecto)  
4. [Mejoras implementadas](#mejoras-implementadas)  
5. [Flujo de trabajo con Git](#flujo-de-trabajo-con-git)  


---

## id="descripcion-del-proyecto">🧾 Descripción del proyecto

Esta página web incluye varias secciones: Inicio, Sobre mí, Contacto, Galería de imágenes y un Footer con enlaces.  
Cada funcionalidad fue desarrollada en una rama diferente y posteriormente integrada en `main` mediante Pull Requests.

El repositorio oficial del proyecto es:  
👉 **https://github.com/alejo7774/tareaUD1**

---

## id="instalacoón-del-repositorio"🛠 Instalación del repositorio

Para clonar el proyecto en local:


git clone https://github.com/alejo7774/tareaUD1.git
cd tareaUD1


## id"estructura-del-proyecto"🗂 Estructura del proyecto

tareaUD1/
│
├── index.html
├── style.css
├── img/
│ ├── Copilot.webp
│ ├── copilot_chat.webp
│ └── GitHub_Copilot.webp
│
└── README.md


---

## id="mejoras-implementadas"🚀 Mejoras implementadas

Cada mejora se realizó en una **rama independiente**, siguiendo el flujo:

`crear rama → realizar cambios → commit → push al remoto → Pull Request → merge en main`

---

### ✔ Menú de navegación  
**Rama:** `feature/menu`  
Se añadió un menú superior con enlaces internos.

---

### ✔ Tabla en “Sobre mí”  
**Rama:** `feature/tabla`  
Se añadió una tabla con horario de clases.

---

### ✔ Galería de imágenes  
**Rama:** `feature/galeria`  
Se creó una sección con tres imágenes almacenadas en `/img`.

---

### ✔ Footer con enlaces a redes sociales  
**Rama:** `feature/footer`  
Se añadió un pie de página con enlaces y estilos CSS personalizados.

---

### ✔ Estilos CSS y diseño responsive  
**Rama:** `feature/style`  
Se creó `style.css` con un diseño moderno, sombras y adaptación a móvil.

---

### ✔ Botón “Volver arriba”  
**Rama:** `feature/backtotop`  
Se añadió un botón flotante circular para volver al inicio de la página.

---

### ✔ Documentación del proyecto (este README)  
**Rama:** `feature/readme`  
Se creó este README en formato Markdown con descripción, estructura, mejoras y flujo de trabajo.


## id="flujo-de-trabajo-con-git"🔄 Flujo de trabajo con Git

En este proyecto se ha utilizado un flujo de trabajo basado en **ramas independientes**, siguiendo buenas prácticas de desarrollo colaborativo.

El proceso seguido para cada mejora fue el siguiente:

1. **Crear una rama nueva** desde la rama principal:
   	git checkout -b feature/nueva-mejora
2. Realizar los cambios necesarios en los archivos del proyecto.
3. Añadir los cambios al área de preparación (staging) 
	git add .
4. Crear un commit descriptivo:
	git commit -m "Descripción de la mejora implementada"
5. Subir la rama al repositorio remoto en GitHub:
	git push origin feature/nueva-mejora
6. Crear un Pull Request (PR) en GitHub comparando la nueva rama con main.

7. Revisar y fusionar el PR para integrar los cambios en la rama principal:
	Create Pull Request
	Merge Pull Request
	Confirm merge

## Autor
Proyecto realizado por Javier Alejandro Mosquera Astudillo
DAM – FP Virtual Aragón
