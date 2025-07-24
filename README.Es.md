
# Cómo crear un proyecto Astro con Tailwind utilizando esta plantilla

## Paso 1: Clonar la plantilla

Ejecute el siguiente comando en su terminal para crear un nuevo proyecto basado en la plantilla:

> ⚠️  (Recuerda reemplazar "nuevo-proyecto" por el nombre que tendrá tu proyecto)

```bash
npx degit BracoZS/astro_tailwind_4-template nuevo-proyecto
```
Esto descargará el proyecto base en la carpeta "nuevo-proyecto"

## Paso 2: Entra en la carpeta del proyecto

```bash
cd nuevo-proyecto
```

## Paso 3: Instala las dependencias

```bash
npm install
```

¡Listo!


---

# Kit de inicio de Astro: Minimal


> 🧑‍🚀 **¿Eres un astronauta experimentado?** Elimina este archivo. ¡Que te diviertas!

## 🚀 Estructura del proyecto

Dentro de tu proyecto Astro, verás las siguientes carpetas y archivos:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro busca archivos `.astro` o `.md` en el directorio `src/pages/`. Cada página se expone como una ruta basada en su nombre de archivo.

No hay nada especial en `src/components/`, pero es ahí donde nos gusta colocar cualquier componente Astro/React/Vue/Svelte/Preact.

Cualquier recurso estático, como imágenes, se puede colocar en el directorio `public/`.

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, desde un terminal:

| Comando                   | Acción                                           |
| :------------------------ | :------------------------------------------------ |
| `npm install`             | Instala dependencias                            |
| `npm run dev`             | Inicia el servidor de desarrollo local en `localhost:4321`      |
| `npm run build`           | Compila tu sitio de producción en `./dist/`          |
| `npm run preview`         | Previsualiza tu compilación localmente, antes de implementarla     |
| `npm run astro ...`       | Ejecuta comandos CLI como `astro add`, `astro check` |
| `npm run astro -- --help` | Obtén ayuda sobre el uso de la CLI de Astro                     |

## 👀 ¿Quieres saber más?

No dudes en consultar [nuestra documentación](https://docs.astro.build) o unirte a nuestro [servidor Discord](https://astro.build/chat).
