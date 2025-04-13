# GitHub Portfolio - Proyecto de Construcción de Software

Este repositorio contiene un portafolio web colaborativo desarrollado por el equipo como parte del curso **Construcción de Software**. El objetivo del proyecto es mostrar el perfil profesional de cada uno de los integrantes mediante una plataforma unificada, aplicando buenas prácticas de desarrollo colaborativo, automatización y control de versiones.

## 🌐 Proyecto en Producción

🔗 [Ver Sitio en GitHub Pages](https://reedmamani.github.io/Portada-Grupal/)

---

## 🧑‍💻 Integrantes del Equipo

	Luis Enrique Carbonel Guerrero (Analista de software)
	Edgar Alfredo Gonzales Huisa (Programador fronted)
	Jesus Enrique Guerrero Peralta (Programador backend)
	Yonathan Ayma Jimenez (Programador tester)
	Reed Bronson Mamani Taco (Programador fullstack)


---

## 📌 Objetivo del Proyecto

Desarrollar una plataforma web que permita a cada miembro del equipo presentar su perfil profesional en una sección personalizada, utilizando un diseño y estructura comunes.

### Objetivos específicos

- Mostrar información como formación, experiencia y habilidades técnicas.
- Personalizar cada sección individual del portafolio.
- Aplicar buenas prácticas de desarrollo colaborativo usando Git, GitHub, GitFlow y CI/CD.

---

## 🧰 Tecnologías Utilizadas

- **Frontend:** HTML5, CSS
- **Control de versiones:** Git, GitHub
- **Despliegue:** GitHub Pages
- **Automatización:** GitHub Actions (CI/CD)

---

## 🔄 Flujo de Trabajo GitFlow

Este proyecto sigue el modelo **GitFlow**, utilizando las siguientes ramas:

- `main` – Rama de producción
- `develop` – Rama de desarrollo general
- `feature/*` – Nuevas funcionalidades
- `release/*` – Preparación de versiones
- `hotfix/*` – Corrección urgente en producción

Las fusiones se realizan mediante **Pull Requests**, con revisión previa por el equipo.

---

## 📦 Commits y Convención

Se usó una convención uniforme para los mensajes de commit, basada en prefijos:

- `feat:` Nueva funcionalidad
- `fix:` Corrección de errores
- `docs:` Documentación
- `test:` Pruebas


---

## ⚙️ Integración y Entrega Continua (CI/CD)

El repositorio incluye configuración de **GitHub Actions** para:

- Ejecutar pruebas automáticamente al hacer push a `main`
- Generar el build del proyecto
- Desplegar automáticamente a GitHub Pages

### Archivo de workflow
`.github/workflows/static.yml`

Este archivo gestiona el despliegue automático asegurando Entrega Continua (CD).

---

## 🧪 Pruebas y Revisión

- Cada nueva funcionalidad se desarrolló en una rama `feature/` individual.
- Se ejecutaron pruebas locales antes de cada fusión.
- Se aplicó **code review** para asegurar calidad.
- Los conflictos fueron gestionados colaborativamente por el equipo.

---

## 🤝 Colaboración

Se trabajó con un enfoque ágil, manteniendo comunicación efectiva entre los miembros del equipo. Las tareas fueron distribuidas y gestionadas por el líder del equipo.

---

## 📄 Licencia

Este proyecto es de uso académico y no tiene una licencia de uso comercial.

