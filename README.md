> **Estado:** en planificación. Este README describe lo que voy a construir y se irá
> actualizando a medida que avance el proyecto.

## Objetivo
Repositorio público que documenta mi ruta hacia Cloud/DevOps y que funciona como centro 
de mi portafolio: roadmap,progreso,certificaciones y enlaces a cada proyecto.

Es también mi proyecto práctico de **GitHub Foundations**: cada pieza del repositorio usa una funcionalidad del temario (ramas, issues, pull requests, Projects, Pages, seguridad).

## Qué incluirá 
- Sitio con GitHub Pages: roadmap, progreso y enlaces a los proyectos.
- Tablero de GitHub Projects con cada proyecto como issue e hito.
- Plantillas de issue y de pull request, y etiquetas ordenadas.
- Flujo de trabajo con ramas y pull requests, incluso trabajando en solitario.
- Seguridad básica: proteción de rama, Dependabot y SECURITY.md


## Funcionalidades de Foundations que practico

| Funcionalidad            | Dónde la uso                                   |
|--------------------------|------------------------------------------------|
| Repositorios de README   | Este repo y el README de perfil                |
| Ramas y pull requests    | Todo cambio entra por PR, nunca directo a main |
| Issues y etiquetas       | Cada tarea del roadmap es un issue             |
| Github Projects          | Tablero con el avance de los proyectos         |
| Github Pages             | Sitio público de la bitácora                   |
| Markdown                 | Toda la documentación                          |
| Plantillas               | Issue forms y plantilla de PR                  |
| Seguridad                | Dependabot, SECURITY.md, protección de rama    |  

## Estructura planificada

```
.
├── docs/ 
(GitHub Pages)
|   ├── index.md
|   ├── roadmap.md 
|   ├── proyectos
├── .github/ 
    ├── ISSUE_TEMPLATE/ 
        ├── tarea.yml 
        ├── bug.yml
    ├── pull_request_template.md 
    ├── dependabot.yml 
    ├── CODEOWNERS
├── LICENSE
├── SECURITY.md
├── CONTRIBUTING.md
```

## Flujo de trabajo

1. Crear issue por cada tarea y asignarlo al tablero.
2. Crear una rama desde main (feature/nombre-corto).
3. Abrir pull request que referencie el issue (Closes #n).
4. Revisar el PR yo mismo con la plantilla y fusionarlo.
5. El issue se cierra solo y la tarjeta pasa a Hecho.

**Día 1: base**
- [ ] Crear el repositorio y este README
- [ ] Añadir la licencia MIT (archivo LICENSE)
- [ ] Crear la estructura de carpetas
- [ ] Activar la protección de rama en main

**Día 2: organización**
- [ ] Etiquetas y plantillas de issue
- [ ] Plantilla de pull request
- [ ] Tablero de Projects con los 3 proyectos como issues
      
**Día 3: publicación**
- [ ] Activar GitHub Pages desde /docs
- [ ] Páginas de inicio y roadmap
- [ ] README de perfil enlazando a este repo
      
**Día 4: seguridad y pulido**
- [ ] Dependabot y SECURITY.md
- [ ] Al menos 3 pull requests propios fusionados
- [ ] Enlace añadido a LinkedIn y al CV
## Licencia
 
MIT
