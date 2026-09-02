# Didáctica y TIC en la Educación Inicial · Materiales interactivos

Materiales interactivos de la materia **Didáctica y Tecnologías de la Información y la Comunicación en la Educación Inicial** — Profesorado de Educación Inicial 3° · Inst. Superior Terciario Ntra. Sra. de Fátima · Ciclo lectivo 2026.

## 🌐 Acceso público

Los materiales se sirven vía **GitHub Pages**:

> **https://jjgarcia-cpu.github.io/didactica-tic/**

La página principal (`index.html`) lista los materiales por clase.

## 📁 Estructura

```
didactica-tic/
├── index.html                          # Landing con links a todo
├── clase-3/                            # Competencias (02/09 · presencial)
│   └── Material_Estudios_Clase3.html
├── clase-4/                            # Recursos e IA (09–15/09 · virtual)
│   └── Material_Estudio_Clase4.html
├── clase-5/                            # Secuencias TIC (16/09 · presencial)
│   └── Material_Estudios_Clase5.html
└── clase-6/                            # Pensamiento computacional (23–29/09 · virtual)
    └── Material_Estudio_Clase6.html
```

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
