# 🧙 SÜRI KŌRE — Matemáticas Mágicas

> **Desde contar objetos hasta derivadas — una sola app para todo el camino | Gamificación educativa que funciona**

[![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)](https://expo.dev/)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![Google Play](https://img.shields.io/badge/Google_Play-Coming_Soon-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store)

[![Live Demo](https://img.shields.io/badge/🌐_Ver_Landing-8338ec?style=for-the-badge)](https://surikoreapp.vercel.app/)
[![Status](https://img.shields.io/badge/Estado-Desarrollo-orange?style=for-the-badge)](https://surikoreapp.vercel.app/)

---

## 📖 Descripción

**SÜRI KŌRE** es una aplicación educativa móvil desarrollada con **React Native** y **Expo** que transforma el aprendizaje de matemáticas en una experiencia de juego adictiva y efectiva. Cubre **4 niveles educativos completos** (Inicial, Primaria, Secundaria y Pre-universitario) con más de **35 operaciones matemáticas** diferentes, adaptándose automáticamente al sistema educativo de **26 países**.

La app utiliza mecánicas de gamificación avanzadas (sistema de vidas, combos, cronómetro, estrellas y récords) para mantener la motivación alta, mientras que su arquitectura SQLite permite funcionar completamente offline y almacenar progreso histórico detallado.

---

## ✨ Características Principales

### 🎮 Sistema de Gamificación

#### ❤️ Sistema de Vidas
* **3 vidas por partida:** Cada error te cuesta una vida
* **Game Over Dinámico:** Si pierdes las 3 vidas antes de terminar
* **Visualización Clara:** Indicador de vidas restantes en pantalla

#### 🔥 Combos y Rachas
* **Multiplicador x2:** Acierta 3 respuestas seguidas para activarlo
* **Puntos Dobles:** Cada pregunta vale el doble durante el combo
* **Pérdida de Combo:** Un error rompe la racha
* **Feedback Visual:** Animaciones cuando activas/pierdes el combo

#### ⭐ Sistema de Estrellas
* **3 Estrellas Máximas:** Rendimiento basado en % de aciertos
* **Criterios de Evaluación:**
  * ⭐⭐⭐ **90-100%** de aciertos
  * ⭐⭐ **70-89%** de aciertos
  * ⭐ **50-69%** de aciertos
  * Sin estrellas: **<50%** de aciertos

#### ⏱️ Sistema de Tiempo
* **Primaria:** Countdown timer (tiempo límite por pregunta)
* **Secundaria y Pre-uni:** Cronómetro ascendente (mide tu velocidad)
* **Récords de Velocidad:** Compite contra tus mejores tiempos

#### 🏆 Récords Personales
* **Guardado Local:** SQLite almacena tu mejor puntaje por cada tema
* **Desglose Detallado:** Récord separado por grado y dificultad
* **Historial Completo:** Revisa tu evolución a través del tiempo

---

## 📚 Niveles Educativos

### 🎈 Inicial (3-6 años)
**5 temas básicos para preescolares**

* 🔢 **Contar:** Del 1 al 20 con objetos visuales
* 🔷 **Formas:** Identificación de círculos, cuadrados, triángulos
* ⚖️ **Comparar:** Más que, menos que, igual que
* 🔗 **Secuencias:** Patrones simples y completar series
* 🥇 **Ordinales:** Primero, segundo, tercero

### 📚 Primaria (6-12 años)
**12 temas con dificultad progresiva**

* ➕ **Suma y Resta:** Operaciones básicas
* ✖️ **Multiplicación:** Tablas del 1 al 12
* ➗ **División:** Divisiones exactas e inexactas
* 🍕 **Fracciones:** Suma, resta, multiplicación y simplificación
* 📐 **Geometría:** Perímetros, áreas de figuras básicas
* 💯 **Decimales:** Operaciones con números decimales
* 🔢 **Potencias:** Cuadrados y cubos
* 📊 **Unidades:** Conversión de medidas (longitud, masa, tiempo)
* ⏰ **Tiempo:** Lectura de reloj, sumas de horas
* 💰 **Dinero:** Problemas de compra/venta
* 🏛️ **Números Romanos:** Conversión I-X-L-C-D-M
* 🔄 **MCM y MCD:** Múltiplos y divisores

### 🎓 Secundaria (12-17 años)
**9 temas con cronómetro de velocidad**

* 📐 **Álgebra:** Ecuaciones de primer y segundo grado
* 📊 **Trigonometría:** Razones, identidades, ángulos notables
* 📈 **Funciones:** Lineales, cuadráticas, evaluación
* 🎲 **Probabilidad:** Cálculo de probabilidades simples y compuestas
* 📉 **Estadística:** Media, mediana, moda, desviación
* 📏 **Geometría Analítica:** Distancia, punto medio, pendiente
* 📊 **Logaritmos:** Propiedades y ecuaciones logarítmicas
* 🔢 **Sistemas de Ecuaciones:** 2x2 y 3x3
* 🔺 **Áreas y Volúmenes:** Figuras 2D y sólidos 3D

### 🏛️ Pre-universitario (17+ años)
**9 temas de nivel avanzado**

* 📈 **Derivadas:** Reglas de derivación, aplicaciones
* ∫ **Integrales:** Inmediatas, por partes, sustitución
* 🎲 **Combinatoria:** Permutaciones, combinaciones, variaciones
* 📊 **Matrices:** Operaciones, determinantes, inversas
* 🔢 **Números Complejos:** Operaciones en forma binómica y polar
* 📐 **Límites:** Cálculo de límites algebraicos y trigonométricos
* 🌊 **Series:** Convergencia, suma de series
* 📉 **Cónicas:** Ecuaciones de circunferencia, elipse, parábola, hipérbola
* 🧮 **Sistemas de Ecuaciones Avanzados:** Métodos de resolución

---

## 🎯 Dificultades y Cantidad de Preguntas

### Fácil
* **10 preguntas** por partida
* Números pequeños y operaciones simples
* Ideal para comenzar a practicar

### Medio
* **15 preguntas** por partida
* Números moderados y complejidad intermedia
* Recomendado para consolidar conocimientos

### Difícil
* **20 preguntas** por partida
* Números grandes y problemas complejos
* Para dominar completamente el tema

**Los rangos numéricos se ajustan automáticamente según el nivel educativo seleccionado.**

---

## 🌍 Soporte Internacional (26 Países)

SÜRI KŌRE detecta automáticamente tu ubicación y adapta los **grados escolares** al sistema educativo de tu país:

**🌎 América:**
* 🇵🇪 Perú
* 🇲🇽 México
* 🇦🇷 Argentina
* 🇨🇱 Chile
* 🇨🇴 Colombia
* 🇪🇨 Ecuador
* 🇧🇷 Brasil
* 🇺🇸 Estados Unidos
* 🇨🇦 Canadá

**🌍 Europa:**
* 🇪🇸 España
* 🇫🇷 Francia
* 🇩🇪 Alemania
* 🇮🇹 Italia
* 🇬🇧 Reino Unido
* 🇵🇹 Portugal

**🌏 Otros:**
* 🇦🇺 Australia
* 🇳🇿 Nueva Zelanda
* 🇯🇵 Japón
* 🇰🇷 Corea del Sur
* 🇨🇳 China
* 🇮🇳 India
* Y más...

**Cada país tiene su configuración de grados adaptada al sistema educativo local.**

---

## 🛠️ Stack Tecnológico

| Categoría | Tecnología |
| :--- | :--- |
| **Framework** | React Native 0.74 |
| **Runtime** | Expo SDK 51 |
| **Base de Datos** | SQLite (expo-sqlite) para récords y progreso |
| **Navegación** | React Navigation 6 (Stack + Bottom Tabs) |
| **Estado** | React Hooks (useState, useEffect, useContext) |
| **Animaciones** | React Native Reanimated 3 |
| **Geolocalización** | expo-location (detección de país) |
| **Storage** | AsyncStorage para preferencias |
| **UI/UX** | Custom Components, React Native Paper |
| **Matemáticas** | MathJax para renderizado de fórmulas |

---

## 💎 Planes y Precios

### 🆓 Gratis (Para Siempre)
Todo lo que necesitas para practicar

* ✅ Todos los niveles (Inicial → Pre-universitario)
* ✅ 35+ operaciones matemáticas
* ✅ Sistema de vidas, combos y estrellas
* ✅ Timer y cronómetro
* ✅ Récords locales por tema
* ✅ Estadísticas básicas de rendimiento
* ✅ Detección automática de país
* ❌ Modo práctica (sin timer)
* ❌ Historial detallado de errores
* ❌ Modo repaso (solo preguntas falladas)
* ✅ Con anuncios (no invasivos)

### ⭐ Premium - S/ 9.90/mes
Para estudiar de verdad, no solo jugar

* ✅ **Todo lo del plan Gratis**
* ✦ **Sin anuncios**
* ✦ **Modo Práctica Libre:** Practica sin timer ni cronómetro, a tu ritmo
* ✦ **Historial Detallado:** Ve exactamente qué fallaste y por qué
* ✦ **Modo Repaso:** Partida especial solo con las preguntas que fallaste
* ✦ **Estadísticas Avanzadas:** Gráficos de evolución, temas más débiles
* ✦ **Exportar Progreso:** Descarga tus estadísticas en PDF

---

## 📸 Capturas de Pantalla

> **Nota:** Este repositorio contiene únicamente la landing page web. La aplicación móvil está en desarrollo privado.

**Ver landing page en vivo:** [surikoreapp.vercel.app](https://surikoreapp.vercel.app/)

---

## 🌐 Landing Page (Este Repositorio)

La landing page de SÜRI KŌRE está desarrollada con:
* **HTML5 semántico**
* **CSS3 moderno** (Variables CSS, Flexbox, Grid)
* **JavaScript Vanilla** (sin frameworks)
* **Diseño Responsive** (Mobile-first)
* **Animaciones CSS** (smooth scroll, hover effects)

### Características de la Landing
* ✅ Hero section con tagline impactante
* ✅ Sección de niveles con tarjetas interactivas
* ✅ Listado de funciones con iconos temáticos
* ✅ Comparativa de planes (Gratis vs Premium)
* ✅ Sección "Cómo funciona" con pasos
* ✅ Footer con políticas y términos
* ✅ Call-to-action a Google Play Store

---

## 🔧 Instalación del Proyecto (Landing Page)

```bash
# Clonar el repositorio
git clone https://github.com/JoelAG-gif/pagina-de-suri-kore.git

# Entrar al directorio
cd pagina-de-suri-kore

# Abrir con Live Server (VS Code) o cualquier servidor local
# No requiere build ni dependencias
```

---

## 📂 Estructura del Proyecto

```
pagina-de-suri-kore/
├── index.html          # Página principal
├── terminos.html       # Términos y Condiciones
├── privacidad.html     # Política de Privacidad
├── css/
│   └── styles.css      # Estilos globales
├── js/
│   └── main.js         # Scripts de interacción
└── assets/
    ├── images/         # Capturas de la app
    └── icons/          # Iconos de niveles
```

---

## 🎨 Paleta de Colores

```css
--primary: #8338EC;      /* Púrpura (tema mágico) */
--secondary: #FF006E;    /* Rosa vibrante */
--accent: #FFBE0B;       /* Amarillo */
--dark: #1A1423;         /* Fondo oscuro */
--light: #F7F4F3;        /* Texto claro */
--success: #06FFA5;      /* Verde neón */
```

---

## 🚀 Roadmap de Lanzamiento

### ✅ Completado
- [x] Diseño y maquetación de UI/UX
- [x] Sistema de niveles y temas implementado
- [x] Generador de preguntas aleatorias
- [x] Sistema de gamificación (vidas, combos, estrellas)
- [x] Base de datos SQLite para récords
- [x] Landing page web
- [x] Detección automática de país

### 🚧 En Desarrollo
- [ ] Modo Premium con backend de suscripciones
- [ ] Integración con Google Play Billing
- [ ] Sistema de notificaciones push (recordatorios diarios)
- [ ] Modo multijugador (desafíos entre amigos)

### 🔮 Futuras Versiones
- [ ] Versión iOS (App Store)
- [ ] Modo offline completo con sincronización en la nube
- [ ] Avatar personalizable y sistema de logros
- [ ] Tabla de clasificación global
- [ ] Soporte para tablets con UI optimizada
- [ ] Integración con plataformas educativas (Google Classroom)

---

## 📱 Instalación de la App (Próximamente)

### Desde Google Play Store
```
1. Busca "Süri Kōre" en Google Play
2. Descarga e instala
3. ¡Empieza a practicar!
```

### APK Directo (Beta Testers)
```
1. Descarga el APK desde el link proporcionado
2. Habilita "Fuentes desconocidas" en Configuración → Seguridad
3. Instala el archivo APK
4. Acepta los permisos necesarios
```

---

## 🎓 Filosofía Educativa

SÜRI KŌRE se basa en 3 principios pedagógicos fundamentales:

### 1️⃣ **Aprendizaje por Repetición Espaciada**
El sistema de récords y modo repaso implementa técnicas de memoria espaciada: practicas más los temas donde tienes errores.

### 2️⃣ **Gamificación Motivacional**
El sistema de vidas, combos y estrellas no es solo decorativo: genera dopamina natural que mantiene el cerebro comprometido con el aprendizaje.

### 3️⃣ **Progresión Adaptativa**
Los 3 niveles de dificultad se ajustan automáticamente al nivel educativo, asegurando que siempre haya desafío pero nunca frustración extrema.

---

## 📊 Estadísticas de Uso (Proyectadas)

* **35+ operaciones matemáticas** cubriendo Inicial → Pre-universitario
* **26 países** con sistemas educativos adaptados
* **4 niveles educativos** (Inicial, Primaria, Secundaria, Pre-uni)
* **3 dificultades** por tema (Fácil, Medio, Difícil)
* **Miles de preguntas** generadas aleatoriamente
* **Offline-first:** Funciona 100% sin internet

---

## 👥 Público Objetivo

* 🧒 **Niños de 3-6 años:** Aprendiendo a contar y reconocer formas
* 📚 **Estudiantes de Primaria:** Dominando operaciones básicas
* 🎓 **Estudiantes de Secundaria:** Preparándose para exámenes
* 🏛️ **Pre-universitarios:** Practicando para exámenes de admisión
* 👨‍🏫 **Profesores:** Herramienta complementaria en clase
* 👨‍👩‍👧 **Padres:** Apoyo en educación en casa

---

## 📞 Contacto y Soporte

**Email:** jireharoni03@gmail.com

**WhatsApp (próximamente):** +51 960 756 758

**Reportar Bugs:** [GitHub Issues](https://github.com/JoelAG-gif/pagina-de-suri-kore/issues)

---

## 📄 Licencia

© 2026 Novark Systems. Todos los derechos reservados.

**SÜRI KŌRE** es un producto en desarrollo. La aplicación móvil no es de código abierto. Este repositorio contiene únicamente el código de la landing page web.

---

## 👨‍💻 Desarrollado por

**Jireh Aroni**

*Desarrollador Full Stack especializado en aplicaciones educativas y gamificación*

* 💼 [LinkedIn](https://linkedin.com/in/jireharoni)
* 💻 [GitHub](https://github.com/JoelAG-gif)
* 🌐 [Portafolio](https://mi-portafolio-jireharoni.vercel.app/)

---

## 🙏 Agradecimientos

* **MathJax** por el renderizado de fórmulas matemáticas
* **Expo Team** por su increíble framework
* **React Native Community** por los recursos y componentes
* **Beta Testers** que están probando la primera versión

---

## 🌟 Contribuir

Este proyecto **no acepta contribuciones externas** por el momento, ya que es un producto comercial en desarrollo privado.

Si encuentras bugs o tienes sugerencias, por favor repórtalos en la sección de [Issues](https://github.com/JoelAG-gif/pagina-de-suri-kore/issues).

---

**🧙 SÜRI KŌRE — Matemáticas Mágicas**

[🌐 Ver Landing Page](https://surikoreapp.vercel.app/) • [📱 Descargar App (Próximamente)](https://play.google.com/store)

---

> *"La mejor manera de aprender matemáticas es jugando. SÜRI KŌRE convierte cada ejercicio en una aventura."*
