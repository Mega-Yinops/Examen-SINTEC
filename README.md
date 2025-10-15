# Examen Técnico Sintec - Jaciel Aaron

Este repositorio contiene tres ejercicios técnicos desarrollados como parte de una prueba técnica para Sintec, demostrando diferentes aspectos del desarrollo frontend con tecnologías web modernas.

## 📋 Índice

- [Ejercicio 1: Sistema de Autenticación](#ejercicio-1-sistema-de-autenticación)
- [Ejercicio 2: Buscador de Pokémon con Flip Cards](#ejercicio-2-buscador-de-pokémon-con-flip-cards)
- [Ejercicio 3: Pokédex con Scroll Infinito](#ejercicio-3-pokédex-con-scroll-infinito)
- [Flujo de Desarrollo](#flujo-de-desarrollo)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación y Uso](#instalación-y-uso)

## 🔐 Ejercicio 1: Sistema de Autenticación

**Archivo:** `Ejercicio 1 - Jaciel Aaron.html`

### Descripción
Sistema completo de autenticación simulada con JWT, roles de usuario y rutas protegidas.

### Características Implementadas
- ✅ **Autenticación JWT simulada** con tokens de expiración
- ✅ **Token con expiración** (2 minutos)
- ✅ **Rutas protegidas** con middleware de validación
- ✅ **Middleware de protección** para contenido sensible
- ✅ **Hook useAuth()** personalizado
- ✅ **Sistema de roles** (Admin/Usuario)
- ✅ **Extensión automática de sesión**
- ✅ **Dashboard interactivo** post-login
- ✅ **Panel administrativo** para usuarios admin

### Funcionalidades
- Login con validación de credenciales
- Gestión de estado de autenticación
- Protección de rutas por roles
- Logout con limpieza de sesión
- UI responsiva con Tailwind CSS

### Usuarios de Prueba
```
admin / admin123 (Administrador)
user / user123 (Usuario)
```

---

## 🔍 Ejercicio 2: Buscador de Pokémon con Flip Cards

**Archivo:** `Ejercicio 2 - Jaciel Aaron.html`

### Descripción
Buscador interactivo de Pokémon que consume la PokéAPI con efectos visuales de flip cards y animaciones avanzadas.

### Características Implementadas
- ✅ **Búsqueda por nombre o ID** de Pokémon
- ✅ **Consumo de PokéAPI** con fetch y async/await
- ✅ **Flip Cards 3D** con animaciones CSS
- ✅ **Gestión de estados** (loading, error, éxito)
- ✅ **Validación de entrada** y manejo de errores
- ✅ **Información detallada** del Pokémon
- ✅ **Responsive design** con gradientes
- ✅ **Efectos visuales** y transiciones suaves

### Datos Mostrados
- Imagen frontal y trasera del Pokémon
- Nombre y número de Pokédex
- Tipos con colores temáticos
- Estadísticas base (HP, Attack, Defense, etc.)
- Altura y peso
- Experiencia base

### API Utilizada
- **PokéAPI v2** (https://pokeapi.co/api/v2/)

---

## 📱 Ejercicio 3: Pokédex con Scroll Infinito

**Archivo:** `Ejercicio 3 - Jaciel Aaron.html`

### Descripción
Pokédex completa con scroll infinito, filtros por tipo, modal de detalles y diseño responsive.

### Características Implementadas
- ✅ **Cuadrícula responsive** de Pokémon
- ✅ **Scroll infinito** (lazy loading)
- ✅ **Carga inicial de 20 Pokémon** con paginación automática
- ✅ **Filtros por tipo** (Fuego, Agua, Hierba, etc.)
- ✅ **Modal de detalles** con información completa
- ✅ **Estadísticas en tiempo real** (total cargados, filtrados)
- ✅ **Intersection Observer API** para detección de scroll
- ✅ **Caché de datos** para optimización de rendimiento
- ✅ **Estados de carga** y feedback visual
- ✅ **Diseño responsive** mobile-first

### Funcionalidades Avanzadas
- Detección automática de final de página
- Sistema de caché para evitar peticiones duplicadas
- Filtrado dinámico sin recargar datos
- Modal con navegación entre Pokémon
- Contador en tiempo real de elementos

---

## 🔄 Flujo de Desarrollo

### 1. Análisis y Planificación
- **Análisis de requerimientos** técnicos de cada ejercicio
- **Definición de arquitectura** y estructura de archivos
- **Selección de tecnologías** apropiadas para cada caso de uso
- **Diseño de interfaz** y experiencia de usuario

### 2. Desarrollo por Ejercicios

#### Ejercicio 1 - Sistema de Autenticación
1. **Estructura HTML** con formularios y secciones protegidas
2. **Estilos con Tailwind CSS** para diseño responsive
3. **Lógica de autenticación** con simulación de JWT
4. **Gestión de estado** para login/logout
5. **Implementación de roles** y permisos
6. **Validación de formularios** y manejo de errores

#### Ejercicio 2 - Buscador Pokémon
1. **Diseño de flip cards** con CSS 3D transforms
2. **Integración con PokéAPI** usando fetch API
3. **Estados de la aplicación** (loading, success, error)
4. **Animaciones CSS** para transiciones suaves
5. **Validación de entrada** del usuario
6. **Responsive design** para múltiples dispositivos

#### Ejercicio 3 - Pokédex Infinita
1. **Grid responsive** con CSS Grid y Flexbox
2. **Implementación de Intersection Observer** para scroll infinito
3. **Sistema de filtros** dinámicos por tipo
4. **Modal interactivo** para detalles del Pokémon
5. **Caché de datos** para optimización
6. **Estadísticas en tiempo real** con contadores

### 3. Testing y Optimización
- **Pruebas funcionales** de cada característica
- **Validación de responsive design** en diferentes dispositivos
- **Optimización de rendimiento** (caché, lazy loading)
- **Pruebas de accesibilidad** y usabilidad
- **Validación de manejo de errores** y casos edge

### 4. Documentación
- **Comentarios en código** para explicar lógica compleja
- **README detallado** con instrucciones de uso
- **Documentación de APIs** utilizadas
- **Guía de características** implementadas

---

## 🛠 Tecnologías Utilizadas

### Frontend
- **HTML5** - Estructura semántica
- **CSS3** - Estilos avanzados, animaciones y responsive design
- **JavaScript (ES6+)** - Lógica de aplicación y manipulación DOM
- **Tailwind CSS** - Framework de utilidades CSS (Ejercicio 1)

### APIs y Servicios
- **PokéAPI v2** - Datos de Pokémon
- **Fetch API** - Peticiones HTTP asíncronas
- **Intersection Observer API** - Detección de scroll infinito

### Funcionalidades Avanzadas
- **Local Storage** - Persistencia de datos de autenticación
- **JWT Simulation** - Sistema de tokens simulado
- **CSS Animations** - Transiciones y efectos visuales
- **Responsive Design** - Diseño adaptativo
- **Progressive Enhancement** - Mejora progresiva de funcionalidades

---

## 🚀 Instalación y Uso

### Requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet (para APIs y CDNs)

### Instrucciones
1. **Clona o descarga** este repositorio
```bash
git clone [url-del-repositorio]
cd Examen-Sintec
```

2. **Abre los archivos HTML** directamente en tu navegador:
   - `Ejercicio 1 - Jaciel Aaron.html` - Sistema de Autenticación
   - `Ejercicio 2 - Jaciel Aaron.html` - Buscador de Pokémon
   - `Ejercicio 3 - Jaciel Aaron.html` - Pokédex con Scroll Infinito

### Uso Local
Los archivos son completamente autocontenidos y no requieren servidor web. Simplemente ábrelos con:
- **Doble clic** en el archivo
- **Arrastrar y soltar** en el navegador
- **File > Open** en tu navegador

---

## 📝 Notas del Desarrollador

### Decisiones Técnicas
- **Vanilla JavaScript** para demostrar conocimientos fundamentales
- **CSS puro** con algunas utilidades de Tailwind para mostrar versatilidad
- **APIs públicas** para datos reales sin necesidad de backend
- **Diseño mobile-first** para mejor experiencia en dispositivos

### Patrones Implementados
- **Module Pattern** para organización de código
- **Observer Pattern** para manejo de eventos
- **Singleton Pattern** para gestión de estado
- **Factory Pattern** para creación de elementos DOM

### Optimizaciones
- **Debouncing** en búsquedas
- **Lazy loading** de imágenes
- **Caché de datos** para evitar peticiones duplicadas
- **Intersection Observer** para mejor rendimiento en scroll

---

## 👨‍💻 Autor

**Jaciel Aaron**
- Desarrollador Frontend
- Examen Técnico para Sintec
- Fecha: Octubre 2025

---

## 📄 Licencia

Este proyecto fue desarrollado como parte de una prueba técnica y es propiedad intelectual del desarrollador y de Sintec según los términos del proceso de selección.