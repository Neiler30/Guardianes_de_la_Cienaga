# Guardianes de la Ciénaga
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/3f936949-2cfa-4080-8e83-dc899eab336f" />

## Registro de Avance del Proyecto

Fecha: Junio 2026

---

# Estado General

Actualmente el proyecto se encuentra en fase de preproducción avanzada.

Se han completado los sistemas fundamentales para comenzar la construcción del mundo del juego y la integración de mecánicas principales.

---

# Editor de Mapas Personalizado

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/788ef3dd-248b-4bfa-9245-161ff716c086" />


Se desarrolló un editor de mapas propio utilizando:

- TypeScript
- Three.js
- Vite

Sin utilizar motores como:

- Unity
- Unreal Engine
- Godot

El objetivo del editor es permitir construir visualmente la Ciénaga Grande de Santa Marta y sus distintas zonas jugables.

---

## Funciones Implementadas

### Biblioteca de Assets

|<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/bd40fde1-18fd-4b1a-a0f4-7934b06b98e7" />


Sistema para visualizar y organizar modelos GLB.

Categorías actuales:

- Basura
- Construcciones
- Vegetación
- Fauna
- Vehículos

---

### Importación de Referencias
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/30fada4d-3b38-4b5a-b161-a23bf120477b" />


Permite cargar imágenes de referencia para recrear la forma real de la Ciénaga Grande.

Utilizado para:

- Delimitar zonas de agua
- Delimitar zonas de tierra
- Construir la geografía principal

---

### Sistema de Malla Editable

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/d71aedeb-ce4f-4e38-b70c-349038b7ee9a" />


Se desarrolló una cuadrícula editable basada en vértices.

Características:

- Selección individual de vértices
- Modificación manual del terreno
- Deformación de la forma general del mapa
- Adaptación a la geografía real de la Ciénaga

---

### Sistema de Capas

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/3e2b2b86-f6d2-4df0-b914-cd10bb0bf64f" />


Capas actualmente disponibles:

- Agua
- Terreno

Esto permitirá posteriormente definir:

- Zonas navegables
- Zonas caminables
- Áreas protegidas
- Manglares
- Puntos de interés

---

### Escala del Mundo

Se inició la implementación de un sistema de escala real.

Características:

- Tamaño configurable por celda
- Medición en metros
- Cálculo automático de área
- Cálculo automático de dimensiones del mapa

Actualmente:

- Rejilla: 24 x 18
- Vértices: 475
- Tamaño de celda configurable

---

### Herramientas de Edición

Implementadas:

- Seleccionar
- Mover
- Rotar
- Escalar
- Brush
- Borrar celdas
- Crear zonas
- Punto de aparición del jugador

---

## Vista Actual del Editor

Características visibles:

- Biblioteca lateral de assets
- Vista superior del mapa
- Sistema de cuadrícula editable
- Herramientas de edición
- Inspector de propiedades
- Configuración de capas
- Gestión de escala

Objetivo:

Convertirse en una herramienta equivalente a una versión simplificada de Unity Editor enfocada exclusivamente en Guardianes de la Ciénaga.

---

# Construcción del Mundo

Se comenzó la recreación de la forma general de la Ciénaga Grande de Santa Marta utilizando referencias cartográficas reales.

El mapa servirá como base para:

- Navegación en canoa
- Exploración
- Recolección de residuos
- Restauración ambiental

---

# Assets Integrados

Actualmente se encuentran integrados modelos GLB para pruebas y prototipos.

---

## Vehículos

### Canoa


Uso:

- Transporte principal del jugador
- Navegación por la ciénaga
- Recolección de residuos

---

### Camión de Basura


Uso:

- Punto de descarga de residuos
- Mecánica de reciclaje

---

### Embarcación de Recolección


Uso:

- Apoyo logístico en zonas alejadas
- Recolección automática de residuos

---

## Entorno

### Manglares


Uso:

- Vegetación principal del ecosistema

---

### Terreno


Uso:

- Base de pruebas para construcción de escenarios

---

### Muelles


Uso:

- Puntos de acceso
- Zonas de interacción

---

### Señales Informativas


Uso:

- Educación ambiental
- Información de zonas

---

## Fauna

### Peces


Uso:

- Decoración ambiental
- Eventos ecológicos

---

# Sistema de Juego
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/a2143d43-b038-4ffe-9980-24928a6994de" />


Se encuentra en desarrollo.

Características previstas:

- Primera persona
- Navegación en canoa
- Recolección de residuos
- Restauración ambiental
- Mejoras de equipamiento
- Progresión por zonas

---

# Próximos Objetivos

## Prioridad Alta

- Finalizar sistema de escala real
- Mejorar deformación de la malla
- Sistema de navegación
- Física de la canoa
- Sistema de agua

---

## Prioridad Media

- Colocación masiva de vegetación
- Sistema de fauna
- Eventos ambientales
- Puntos de reciclaje

---

## Prioridad Baja

- Sistema de logros
- Enciclopedia ambiental
- Misiones secundarias
- Fotomodo

---

# Objetivo Final

Construir una representación interactiva de la Ciénaga Grande de Santa Marta donde los jugadores puedan aprender sobre el ecosistema, restaurar el ambiente y generar conciencia ambiental mientras disfrutan una experiencia de exploración y simulación.
