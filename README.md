# 🧮 MateKids

Sitio web educativo e interactivo para que niños y niñas practiquen operaciones matemáticas básicas (suma, resta, multiplicación y división) de forma divertida, con retroalimentación visual y sonora inmediata.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## 📖 Descripción

**MateKids** es una página web pensada para apoyar el aprendizaje temprano de las matemáticas. A través de un sistema de preguntas con opciones múltiples, los niños resuelven ejercicios de suma, resta, multiplicación y división, mientras reciben confeti y sonidos de refuerzo positivo al acertar, y pueden ir subiendo de nivel de dificultad.

Yo desarrollé los módulos de **Suma** y **Multiplicación**.

## ✨ Funcionalidades

- **4 operaciones matemáticas**: suma, resta, multiplicación y división, cada una en su propia sección.
- **3 niveles de dificultad** por operación (rangos numéricos crecientes).
- **Opciones múltiples** generadas aleatoriamente, con una respuesta correcta y distractores cercanos al resultado.
- **Retroalimentación inmediata**: mensajes de acierto/error, efecto de confeti animado y sonidos (`bien.mp3` / `mal.mp3`).
- **Marcador de puntaje** que lleva la cuenta de respuestas correctas.
- **Menú de navegación tipo hamburguesa** presente en todas las páginas.
- **Diseño temático infantil**, ambientado con ilustraciones de animales.

## 🚀 Cómo ejecutarlo

Este es un proyecto **100% front-end** (HTML, CSS y JavaScript puro), no requiere instalación de dependencias ni backend.

### Opción 1: Abrir directamente en el navegador
1. Clona o descarga este repositorio.
2. Abre el archivo `index.html` con tu navegador de preferencia.

### Opción 2: Usar Live Server (recomendado)
1. Clona el repositorio y ábrelo en Visual Studio Code.
2. Instala la extensión [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).
3. Haz clic derecho sobre `index.html` → **"Open with Live Server"**.
4. El proyecto ya incluye la configuración del puerto en `.vscode/settings.json`.

```bash
git clone https://github.com/tu-usuario/PROYECTO-MATEKIDS.git
cd PROYECTO-MATEKIDS
```

## 🛠️ Tecnologías utilizadas

- **HTML5** – estructura de las páginas
- **CSS3** – estilos y animaciones (confeti, menú, botones)
- **JavaScript (Vanilla)** – lógica del juego, generación de ejercicios y validación de respuestas

## 🎮 Cómo se juega

1. Desde la página principal, elige una operación: suma, resta, multiplicación o división.
2. Selecciona el nivel de dificultad (1, 2 o 3).
3. Resuelve el ejercicio mostrado eligiendo una de las 4 opciones.
4. Si aciertas, sumas un punto y aparece un efecto de confeti; si fallas, se genera un nuevo ejercicio para seguir practicando.

## 📌 Próximas mejoras (sugeridas)

- [ ] Unificar la lógica de las 4 operaciones en un solo script reutilizable (actualmente cada página repite su propia copia del código).
- [ ] Guardar el puntaje del usuario (localStorage o backend).
- [ ] Hacer el diseño responsivo para dispositivos móviles.
- [ ] Agregar más niveles y tipos de ejercicios.
