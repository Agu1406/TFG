Primer commit del proyecto, creación de los directorios:

- backend
- frontend
- database
- reverse-proxy

# Guía de Conventional Commits
.
## Estructura Básica
tipo(alcance): descripción corta

[descripción larga opcional]

[pie opcional con referencias]

## Tipos Principales

- feat: Nuevas características o funcionalidades
- fix: Corrección de errores
- docs: Cambios en documentación
- style: Cambios de formato (espacios, indentación, etc.)
- refactor: Refactorización de código
- test: Añadir o modificar tests
- chore: Tareas de mantenimiento
- perf: Mejoras de rendimiento
- ci: Cambios en integración continua
- build: Cambios en sistema de build

## Ejemplos Prácticos

### 1. Feature Nueva

feat(auth): implementar login con Google

- Añadir botón de login con Google
- Configurar OAuth2
- Añadir manejo de tokens
- Crear página de perfil de usuario

Closes #45

### 2. Corrección de Bug

fix(formulario): corregir validación de email

El formulario aceptaba emails sin '@'.
Añadida expresión regular para validación correcta.

Fixes #123

### 3. Documentación

docs(readme): actualizar instrucciones de instalación

- Añadir requisitos previos
- Actualizar comandos de instalación
- Incluir troubleshooting común

## Buenas Prácticas

1. Primera Línea
   - Usar verbos en imperativo
   - Máximo 50 caracteres
   - No terminar con punto

2. Descripción Detallada
   - Separar del título con línea en blanco
   - Explicar el "qué" y el "por qué"
   - Usar viñetas para mejor legibilidad

3. Referencias
   - Usar "Closes", "Fixes" o "Resolves" para cerrar issues
   - Referenciar otros issues con #número
   - Mencionar breaking changes

## Recordatorio Final

- Ser específico y claro
- Pensar en quien leerá el commit
- Mantener consistencia en el estilo
- Separar cambios grandes en commits más pequeños