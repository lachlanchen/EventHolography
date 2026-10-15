[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner — apps and four buddies](https://lazying.art/media/brand/lazyingart-intro.gif)](https://lazying.art)

# EventHolography

[![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-3776ab?style=for-the-badge&logo=apache&logoColor=white)](./LICENSE)
![Focus: Documentation-First](https://img.shields.io/badge/Focus-Documentation--First-FCA121?style=for-the-badge)
![Repository Stage](https://img.shields.io/badge/Stage-Early--Stage-lightgrey?style=for-the-badge)
![i18n](https://img.shields.io/badge/i18n-Directory%20Present-2ea44f?style=for-the-badge)
![Status](https://img.shields.io/badge/Repository-Documentation%20First-0f766e?style=for-the-badge&logo=markdown&logoColor=white)
![Audience](https://img.shields.io/badge/Audience-Researchers%20%26%20Contributors-22c55e?style=for-the-badge&logo=google-translate&logoColor=white)

---

Repositorio de materiales del proyecto **Event-assisted Holographic Imaging**.

> Se preserva la descripción original del proyecto (base canónica):
> `The repo for the paper Event-assited Holographic Imaging`

## 🧭 Navegación rápida

| Área | Enlace |
|---|---|
| 🎯 Visión general | [Visión general](#overview-) |
| 🗂️ Alcance | [Estructura del proyecto](#project-structure-) |
| ✅ Requisitos previos | [Requisitos previos](#prerequisites-) |
| ▶️ Uso | [Uso](#usage-) |
| 🧪 Contribución | [Contribución](#contributing-) |
| ❤️ Soporte | [❤️ Support](#-support) |
| 📜 Licencia | [Licencia](#license-) |

<a id="overview-"></a>
## Visión general 🔍

`EventHolography` es un repositorio de **documentación primero** dedicado al tema del proyecto **Event-assisted Holographic Imaging**.

En este punto de la instantánea del repositorio, su propósito es servir como centro de onboarding y comunicación en lugar de un paquete ejecutable.

- Estado canónico: andamiaje de documentación de investigación en una fase inicial
- Enfoque público: contexto del artículo, supuestos de configuración y guía multilingüe
- Alcance: estructura del repositorio, proceso de contribución y preparación para futuras contribuciones de código/datos

## Snapshot del repositorio 📈

| Elemento | Detalles | Estado |
|---|---|---|
| `README.md` | Documentación principal del proyecto | Presente y mantenido activamente |
| `LICENSE` | Términos legales y política de reutilización | Apache License 2.0 |
| `.gitignore` | Reglas para ignorar artefactos locales/build | Presente |
| `i18n/` | Archivos README por idioma | Presente |
| `.auto-readme-work/` | Metadatos de pipeline para generación de README | Generado solo durante la redacción |

## Características ✨

- Identidad clara para los materiales del proyecto **Event-assisted Holographic Imaging**
- Licencia Apache 2.0 para reutilización abierta y flexible
- Diseño preparado para internacionalización de README (`i18n/`)
- Estado de documentación-first comunicado explícitamente a usuarios y colaboradores
- Estructura preparada para incorporar datasets, scripts, checkpoints y guías de reproducibilidad más adelante

<a id="project-structure-"></a>
## Estructura del proyecto 🗂️

```text
EventHolography/
├── README.md
├── LICENSE
├── .gitignore
├── i18n/
└── .auto-readme-work/
```

Notas:

- `i18n/` contiene las versiones traducidas del README, incluido árabe, ruso y otros.
- `.auto-readme-work/` se genera durante este flujo de documentación y no es la interfaz pública canónica.

<a id="prerequisites-"></a>
## Requisitos previos ✅

El estado actual del repositorio solo requiere:

- `git` para clonar y trabajar con historial/ramas de forma local
- Un editor que soporte Markdown o el visor de GitHub

Suposición:

- Hoy no se requiere ninguna dependencia de Python/Node/Rust ni runtime de modelo porque aún no hay pipeline ejecutable comprometido.

<a id="usage-"></a>
## Uso ▶️

Aún no existe un punto de entrada ejecutable, por lo que el uso actual está centrado en documentación:

```bash
# Explorar el contenido del repositorio
ls -la

# Leer la visión general del proyecto
cat README.md
```

Cuando lleguen activos de implementación, esta sección debería pasar a instrucciones de ejecución (datasets, modelos, comandos de entrenamiento/inferencia).

## Configuración ⚙️

Actualmente no hay una superficie de configuración en tiempo de ejecución.

Áreas de configuración previstas (cuando llegue el código):

- Rutas raíz de dataset
- Directorios de checkpoints y salidas
- Parámetros de reconstrucción holográfica
- Metadatos del sensor de eventos y opciones de calibración
- Presets de reproducibilidad (seed, particiones, aumentos)

## Ejemplos 📌

Los ejemplos prácticos en esta instantánea son comandos para explorar el repositorio:

```bash
# Confirmar encabezado de licencia
head -n 5 LICENSE

# Verificar cobertura de documentación de idiomas
ls -la i18n

# Leer contexto auto-generado (opcional)
ls -la .auto-readme-work
```

Si esperabas ejemplos de entrenamiento/inferencia, este repositorio aún no los incluye.

<a id="contributing-"></a>
## Contribuciones 🤝

Las contribuciones son bienvenidas.

Hasta que se añadan plantillas dedicadas, usa este flujo estándar:

1. Haz un fork del repositorio
2. Crea una rama enfocada (`docs/<tema>`)
3. Haz commits pequeños, revisables, con mensajes claros
4. Abre un PR con motivación, cambios exactos de archivos y cualquier comando de verificación

Si agregas instrucciones técnicas, incluye ejemplos de comandos y salidas esperadas.

## Notas de desarrollo 🧪

- Este es un esqueleto de repositorio en etapa temprana con prioridades documentation-first.
- Mantén las afirmaciones técnicas ligadas únicamente a los activos comprometidos (archivos del árbol del repositorio).
- Mantén las actualizaciones de README incrementales, preservando el contexto histórico y la paridad de traducciones.
- Si agregas código, coloca detalles de implementación, resultados esperados y pasos de reproducibilidad junto con esta documentación.

## Solución de problemas 🩺

### “Aún no hay nada para ejecutar”

Esto es normal en el estado actual. No hay scripts ejecutables, configuraciones, notebooks ni datasets comprometidos.

### “¿Dónde están los README traducidos?”

Consulta el directorio `i18n/`. Si falta un idioma objetivo, añade `i18n/README.<lang>.md` y sincroniza los enlaces de navegación por idiomas.

### “¿Por qué la ortografía del título es distinta?”

La frase original en las notas superiores es `Event-assited` (con una "s"), que se conserva en la línea histórica entre comillas. Este README usa la ortografía corregida `Event-assisted` en el texto nuevo.

### “¿Debo usar la carpeta `.auto-readme-work/`?”

Úsala como metadatos generados para redactar el README. No suele ser necesaria para colaboradores estándar salvo si trabajas en automatización de documentación.

## Hoja de ruta 🗺️

- Añadir metadatos del artículo (enlace de publicación, DOI y bloque de cita BibTeX)
- Añadir entrypoints de implementación e instrucciones reproducibles de uso cuando estén disponibles
- Añadir documentación de datasets, preprocesamiento y configuración de experimentos
- Añadir plantillas de issues/PR y documentos de automatización para contribuidores
- Mantener los README multilingües sincronizados con la fuente en inglés

## Citación 📚

Los detalles de cita aún no están disponibles en el repositorio.

Cuando la publicación correspondiente esté disponible, incluye un bloque `BibTeX` y el enlace de publicación en esta sección.

## Agradecimientos 🙏

Actualmente no hay agradecimientos definidos en los archivos del repositorio.

Si se debe reconocer apoyo, instituciones o colaboradores, añádelos en una actualización posterior.

## Licencia 📄

Este proyecto está licenciado bajo Apache License 2.0. Consulta [LICENSE](./LICENSE).


## ❤️ Support

<!-- support:start -->
[![GitHub Sponsors](https://img.shields.io/badge/GitHub-Sponsors-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/lachlanchen)
[![LazyingArt Support](https://img.shields.io/badge/LazyingArt-Support-0EA5E9?style=for-the-badge)](https://chat.lazying.art/donate)
[![PayPal Support](https://img.shields.io/badge/PayPal-Support-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/RongzhouChen)
[![Stripe Support](https://img.shields.io/badge/Stripe-Support-635BFF?style=for-the-badge&logo=stripe&logoColor=white)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400)
<!-- support:end -->
