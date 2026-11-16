# Core Skills

Repositorio centralizado de conocimientos, metodologías, instrucciones, herramientas y recursos reutilizables para distintas áreas de trabajo.

Su objetivo es mantener una estructura modular y escalable que facilite la creación, organización, mantenimiento y reutilización de recursos especializados.

## 📁 Estructura del repositorio

La organización se realiza por dominios temáticos. Cada dominio agrupa recursos relacionados y permite incorporar nuevas categorías sin modificar la estructura general.

```text
core-skills/
│
├── README.md                      # Índice maestro, documentación y guía de navegación
│
├── .templates/                    # Plantillas reutilizables para crear nuevos recursos
│   └── skill-template.md           # Plantilla estándar para nuevas skills
│
├── engineering/                    # Ingeniería de software, arquitectura y DevOps
│   ├── git-workflows/               # Flujos de trabajo y buenas prácticas con Git
│   ├── python-automation/           # Automatización y desarrollo con Python
│   └── system-design/               # Diseño de sistemas y arquitectura de software
│
├── finance/                        # Finanzas personales, inversiones e impuestos
│   ├── budgeting-models/            # Modelos de presupuestos y control financiero
│   ├── investment-analysis/         # Análisis y evaluación de inversiones
│   └── tax-planning/                # Planificación y conceptos tributarios
│
├── productivity-ops/                # Productividad, gestión personal y operaciones
│   ├── time-blocking/               # Organización y planificación del tiempo
│   ├── gtd-system/                  # Gestión de tareas y metodología GTD
│   └── decision-frameworks/         # Modelos y marcos para la toma de decisiones
│
├── ai-and-prompts/                  # Inteligencia artificial, prompts y agentes
│   ├── coding-assistants/           # Instrucciones y asistentes para programación
│   └── financial-review-prompts/    # Prompts para análisis y revisión financiera
│
└── scripts-and-tools/               # Herramientas y utilidades transversales
    ├── cli/                         # Scripts y utilidades de línea de comandos
    ├── macros/                      # Macros y automatizaciones
    └── utilities/                   # Herramientas auxiliares reutilizables
```

## 🧩 Organización de los recursos

Cada directorio de primer nivel representa un dominio temático. Dentro de este se crean carpetas independientes para cada recurso especializado.

Se recomienda mantener una estructura homogénea para facilitar su identificación y mantenimiento.

### Estructura recomendada para una skill

```text
nombre-de-la-skill/
│
├── SKILL.md              # Instrucciones principales y definición de la skill
│
├── references/           # Documentación y material de consulta complementario
│   ├── reference-01.md
│   └── reference-02.md
│
├── examples/             # Ejemplos prácticos y casos de uso
│   └── example-01.md
│
└── scripts/              # Scripts auxiliares, cuando sean necesarios
    └── utility.py
```

No todos los recursos necesitan incluir todas las carpetas. Se deben incorporar únicamente los componentes que aporten valor a su funcionamiento.

## 📐 Convenciones y criterios de organización

Para mantener la consistencia del repositorio, se establecen las siguientes recomendaciones:

| Elemento                       | Convención                                                            |
| ------------------------------ | --------------------------------------------------------------------- |
| Directorios                    | `kebab-case`                                                          |
| Archivos Markdown              | `kebab-case.md`                                                       |
| Archivos principales de skills | `SKILL.md`                                                            |
| Scripts                        | Extensión según lenguaje (`.py`, `.js`, `.sh`, etc.)                  |
| Documentación                  | Markdown (`.md`)                                                      |
| Idioma                         | Preferentemente español, conservando términos técnicos estandarizados |

### Principios de diseño

- **Modularidad:** cada recurso debe tener una responsabilidad específica y funcionar de manera independiente cuando sea posible.
- **Reutilización:** priorizar soluciones y componentes que puedan aprovecharse en diferentes proyectos.
- **Consistencia:** mantener convenciones de nombres y estructuras homogéneas.
- **Escalabilidad:** permitir agregar nuevos dominios y recursos sin reorganizar el repositorio.
- **Mantenibilidad:** documentar requisitos, dependencias, ejemplos y cambios relevantes.

## 🚀 Incorporación de nuevos recursos

Para agregar un recurso al repositorio:

1. Identificar el dominio temático al que pertenece.
2. Crear un directorio con un nombre descriptivo en `kebab-case`.
3. Utilizar la plantilla correspondiente ubicada en `.templates/`.
4. Incorporar las instrucciones, referencias, ejemplos y scripts necesarios.
5. Documentar el propósito, alcance y requisitos del recurso.
6. Actualizar este README cuando se agreguen nuevos dominios o recursos relevantes.

## 📌 Consideraciones generales

- `README.md` funciona como punto de entrada y directorio general del repositorio.
- `.templates/` centraliza las estructuras base para mantener consistencia.
- Cada skill debe contar con su propio `SKILL.md` como archivo principal de instrucciones.
- Las referencias y ejemplos deben mantenerse separados de las instrucciones principales cuando su extensión lo justifique.
- Los scripts deben incluir documentación de uso y dependencias cuando corresponda.
- Evitar duplicar recursos: antes de crear uno nuevo, verificar si existe una solución reutilizable.

---

**Core Skills** — Conocimiento organizado, modular y reutilizable.
