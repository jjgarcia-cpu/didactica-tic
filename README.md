# Didáctica y TIC en la Educación Inicial · Materiales interactivos

Materiales interactivos de la materia **Didáctica y Tecnologías de la Información y la Comunicación en la Educación Inicial** — Profesorado de Educación Inicial 3° · Inst. Superior Terciario Ntra. Sra. de Fátima · Ciclo lectivo 2026.

## 🌐 Acceso público

Los materiales se sirven vía **GitHub Pages**:

> **https://jjgarcia-cpu.github.io/didactica-tic/**

La página principal (`index.html`) lista los materiales por clase. Cada material es un solo `.html` autocontenido (CSS y JS embebidos): se abre al instante en el navegador, sin descargar nada, con quizzes autocorregidos, autoevaluación y glosario con buscador.

## 📁 Estructura

```
didactica-tic/
├── index.html                          # Landing con links a todo
├── clase-1/                            # TIC en el Nivel Inicial (12/08 · presencial)
│   └── Material_Estudio_Clase1.html
├── clase-2/                            # Educación Digital y DC (20/08 · virtual asincrónica)
│   └── Material_Estudio_Clase2.html
├── clase-3/                            # Competencias (02/09 · presencial)
│   └── Material_Estudios_Clase3.html
├── clase-4/                            # Recursos e IA (09–15/09 · virtual)
│   └── Material_Estudio_Clase4.html
├── clase-5/                            # Secuencias TIC (16/09 · presencial)
│   └── Material_Estudios_Clase5.html
└── clase-6/                            # Pensamiento computacional (23–29/09 · virtual)
    └── Material_Estudio_Clase6.html
```

Cada material incluye un botón **← Volver al menú** en el header (apunta a `../index.html`), igual en todas las clases.

## 📝 Contenido por clase

| Clase | Tema | Modalidad | Fecha | Secciones |
|-------|------|-----------|-------|-----------|
| 1 | Las TIC y la enseñanza en el Nivel Inicial | Presencial | miércoles 12/08 | Definición, mitos, dimensiones, argumentos, rol docente, perfil, autoevaluación, glosario |
| 2 | La Educación Digital y el Diseño Curricular | Virtual asincrónica | miércoles 20/08 | Marco GCBA, ejes del DC, usos con sentido, escenarios y foro, autoevaluación, glosario |
| 3 | Competencias docentes y criterios de buena práctica | Presencial | miércoles 02/09 | La jornada, competencias, criterios, 8 preguntas, A vs B, rúbrica |
| 4 | Recursos digitales e Inteligencia Artificial | Virtual asincrónica | 09/09 → 15/09 | Recursos del nivel, IA, mitos, los 8 criterios |
| 5 | Secuencias didácticas mediadas por TIC | Presencial | miércoles 16/09 | Tres momentos, coherencia, caso insectos |
| 6 | Pensamiento computacional con y sin pantallas | Virtual asincrónica | 23/09 → 29/09 | Qué es PC, pilares, herramientas del nivel, misión semanal |

## 🔧 Cómo agregar material de una clase nueva

1. Crear carpeta `clase-N/` y copiar dentro el `.html` del material.
2. Sumar la tarjeta correspondiente en `index.html` (copiar una sección `<section class="clase">` existente).
3. Commit + push:

```bash
git add . && git commit -m "Clase N: agrega material interactivo" && git push
```

GitHub Pages publica automáticamente en ~1 minuto. No hace falta tocar nada más.

---
Prof. Lic. Juan José García · jjgarcia@terciariofatimasoldati.edu.ar