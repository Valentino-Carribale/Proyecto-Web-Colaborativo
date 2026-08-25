# 🌐 La Forja Colaborativa

Proyecto web colaborativo desarrollado para el **Trabajo Práctico 8 – La Forja Colaborativa** de la materia **Funcionamiento de los Sistemas Digitales (FSD 2026)**.

El objetivo del proyecto es poner en práctica el flujo de trabajo colaborativo con **Git y GitHub**, permitiendo que diferentes estudiantes trabajen sobre un mismo proyecto mediante **Forks y Pull Requests**.

## 📌 Objetivo

Crear una página web sencilla que pueda ser modificada y ampliada por distintos estudiantes de la clase. Cada participante debe agregar su nombre a una lista y crear una nueva tarjeta para la galería, respetando la estructura y los criterios visuales definidos por el autor del repositorio.

El proyecto busca practicar el flujo:

**Repositorio local → Git → GitHub → Fork → Modificación → Pull Request → Integración**

## 🖥️ Contenido de la página

La página incluye como mínimo:

- Un título o encabezado.
- Una lista con los nombres de los participantes.
- Una galería de tarjetas.
- Una tarjeta por cada participante.
- *Extra: README.md*

Cada tarjeta contiene:

- 🖼️ Una imagen.
- 🏷️ Un título o nombre.
- 📝 Una breve descripción.

### 🎨 Temática

La temática de las tarjetas es sobre personajes variados, se complementaron DnD, Red Dead Redemption 2 e incluso streamers.

## 📁 Estructura del proyecto

```TP8: La Forja Colaborativa
/
├── index.html
├── css/
│   └── style.css
├── img/
│   └── ...
└── README.md (este archivo)
```

### `index.html`

Contiene la estructura principal de la página web, incluyendo:

- El encabezado.
- La lista de participantes.
- La galería.
- Las tarjetas de los participantes.

### `css/style.css`

Contiene los estilos visuales de la página.

### `img/`

Contiene las imágenes utilizadas por las tarjetas.

### `README.md`

Este archivo documenta el proyecto, su estructura y las reglas para colaborar.

## 👥 Criterios de colaboración

Cada estudiante que participe en este repositorio deberá:

1. Realizar un **Fork** del repositorio.
2. Obtener una copia del proyecto.
3. Trabajar sobre su propia copia.
4. Agregar su nombre a la lista de participantes.
5. Agregar una nueva tarjeta (e imagen) a la galería.
6. Respetar la estructura del proyecto.
7. Mantener los criterios visuales establecidos.
8. Registrar los cambios mediante Git.
9. Subir los cambios a su repositorio.
10. Crear un **Pull Request** hacia el repositorio original.

La modificación debe integrarse al proyecto existente sin romper su funcionamiento ni alterar innecesariamente su organización.

## 🎨 Criterios visuales

Para mantener una galería coherente, todas las tarjetas deben respetar las siguientes reglas:

- Mantener la misma estructura HTML de las tarjetas existentes.
- Mantener el mismo estilo de títulos y descripciones.
- Conservar el diseño, espaciado y distribución establecidos en el CSS.
- Evitar cambios que afecten negativamente al resto de las tarjetas.

### Plantilla de tarjeta

Cada nueva tarjeta debe seguir una estructura equivalente a la utilizada en las tarjetas existentes.

```html
<div class="card">
    <img src="./img/imagen.jpg" alt="Descripción de la imagen">
    <h3>Nombre</h3>
    <p>Breve descripción.</p>
</div>
```

> La clase y estructura exactas deben poder adaptarse al código existente del proyecto.

## 🌱 Primera contribución

El autor del repositorio incorpora inicialmente:

- Su propio nombre a la lista.
- Su primera tarjeta a la galería.
- La estructura base del proyecto.
- Los estilos iniciales.

Luego, otros estudiantes podrán realizar sus propias contribuciones mediante Forks y Pull Requests.

## 🔀 Pull Requests

Cada Pull Request debe incluir una descripción breve que indique:

- Qué modificaciones se realizaron.
- Qué tarjeta se agregó.
- Qué archivos fueron modificados.
- Si fue necesario realizar algún ajuste para respetar la estructura original.

## 🛠️ Tecnologías utilizadas

- **HTML** — estructura de la página.
- **CSS** — diseño y estilos.
- **Git** — control de versiones.
- **GitHub** — alojamiento del repositorio y colaboración.
- **Fork** — creación de una copia del repositorio.
- **Pull Request** — propuesta de integración de cambios.

## 👤 Autor

**Nombre:** Valentino Carribale

**Curso:** 4to Informático

**Repositorio de GitHub:** https://github.com/Valentino-Carribale/Proyecto-Web-Colaborativo

## 🤝 Colaboraciones

### Colaboraciones realizadas

1. Ramiro Herrera: https://github.com/Valentino-Carribale/Proyecto-18-8-FSD-Herrera
2. Tomás Barcudi: https://github.com/Valentino-Carribale/SuperSaiyajin3
3. Ciro Griffa: https://github.com/Valentino-Carribale/TP-GIT-CiroG

### Colaboraciones recibidas

1. Ramiro Herrera: https://github.com/Valentino-Carribale/Proyecto-Web-Colaborativo/pull/1
2. Ciro Griffa: https://github.com/Valentino-Carribale/Proyecto-Web-Colaborativo/pull/2
3. Tomás Cardozo: https://github.com/Valentino-Carribale/Proyecto-Web-Colaborativo/pull/3

---
**FSD 2026 — Trabajo Práctico 8 - La Forja Colaborativa**
