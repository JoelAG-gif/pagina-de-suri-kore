# 🧙 SÜRI KŌRE — Matemáticas Mágicas

> **Desde contar objetos hasta derivadas — una sola app para todo el camino | Gamificación educativa que funciona**

[![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Expo_SDK_54-000020?style=for-the-badge&logo=expo&logoColor=white)](https://expo.dev/)
[![Google Play](https://img.shields.io/badge/Google_Play-Coming_Soon-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store)

[![Live Demo](https://img.shields.io/badge/%F0%9F%8C%90_Ver_Landing-8338ec?style=for-the-badge)](https://surikoreapp.vercel.app/)
[![Status](https://img.shields.io/badge/Estado-Desarrollo-orange?style=for-the-badge)](https://surikoreapp.vercel.app/)

---

## 📖 Descripción

**SÜRI KŌRE** es una aplicación educativa móvil desarrollada con **React Native** y **Expo SDK 54** que transforma el aprendizaje de matemáticas en una experiencia de juego adictiva y efectiva. Cubre **4 niveles educativos completos** (Inicial, Primaria, Secundaria y Pre-universitario) con **33 operaciones matemáticas** diferentes, adaptándose automáticamente al sistema educativo de **19 países hispanohablantes**.

La app utiliza mecánicas de gamificación avanzadas (sistema de vidas, combos, cronómetro, estrellas y récords) para mantener la motivación alta. Funciona completamente offline y almacena todo el progreso localmente en el dispositivo.

---

## ✨ Características Principales

### 🎮 Sistema de Gamificación

#### ❤️ Sistema de Vidas
- **3 vidas por partida:** Cada error te cuesta una vida
- **Game Over Dinámico:** Si pierdes las 3 vidas antes de terminar
- **Visualización Clara:** Indicador de vidas restantes en pantalla

#### 🔥 Combos y Rachas
- **Multiplicador x2:** Acierta 3 respuestas seguidas para activarlo
- **Puntos Dobles:** Cada pregunta vale el doble durante el combo
- **Pérdida de Combo:** Un error rompe la racha

#### ⭐ Sistema de Estrellas
- ⭐⭐⭐ **80%+** de aciertos
- ⭐⭐ **50-79%** de aciertos
- ⭐ **30-49%** de aciertos
- Sin estrellas: **<30%** de aciertos

#### ⏱️ Sistema de Tiempo
- **Primaria:** Countdown timer (tiempo límite por pregunta)
- **Secundaria y Pre-uni:** Cronómetro ascendente (mide tu velocidad)

#### 🏆 Récords Personales
- Guardado local por tema, grado y dificultad
- Historial completo de partidas

---

## 📚 Niveles Educativos

### 🎈 Inicial (3-6 años) — 6 temas
🔢 Contar · 🔷 Formas · ⚖️ Comparar · 🔗 Secuencias · 🥇 Ordinales · 👥 Agrupación

### 📚 Primaria (6-12 años) — 18 temas
➕ Suma · ➖ Resta · ✖️ Multiplicación · ➗ División · 🔣 Decimales · ½ Fracciones · % Porcentajes · ⏰ Tiempo · 💰 Dinero · 📏 Medidas · 🏛️ Romanos · ⚡ Potencias · 🔢 MCM/MCD · ⚖️ Proporciones · 📐 Geometría · 📊 Estadística · 🔤 Álgebra · ⚖️ Comparar

### 🎓 Secundaria (12-17 años) — 13 temas · ⏱️ Cronómetro
🔤 Álgebra · 📐 Geometría · 📊 Estadística · ½ Fracciones · √ Potencias y Raíces · 🎲 Probabilidad · 📈 Progresiones · ㏒ Logaritmos · 🔢 Sistemas Ecua. · 🧩 Factorización · 📐 Trigonometría · % Porcentajes · ⚖️ Proporciones

### 🏛️ Pre-universitario (17+ años) — 13 temas · ⏱️ Velocidad
🔤 Álgebra avanzada · 📐 Trigonometría · 📍 Geom. Analítica · 📊 Estadística · 🎲 Probabilidad · 🎯 Combinatoria · ㏒ Logaritmos · 📈 Progresiones · ∫ Derivadas · √ Potencias y Raíces · 🔢 Sistemas Ecua. · 🧩 Factorización · 📐 Geometría

---

## 🎯 Dificultades

| Nivel | Preguntas | Descripción |
|-------|-----------|-------------|
| **Fácil** | 10 | Números pequeños, ideal para comenzar |
| **Medio** | 15 | Complejidad intermedia |
| **Difícil** | 20 | Números grandes, problemas complejos |

---

## 🌍 19 Países Hispanohablantes

🇵🇪 Perú · 🇲🇽 México · 🇦🇷 Argentina · 🇨🇴 Colombia · 🇪🇸 España · 🇨🇱 Chile · 🇪🇨 Ecuador · 🇧🇴 Bolivia · 🇻🇪 Venezuela · 🇵🇾 Paraguay · 🇺🇾 Uruguay · 🇨🇷 Costa Rica · 🇬🇹 Guatemala · 🇵🇦 Panamá · 🇭🇳 Honduras · 🇩🇴 Rep. Dominicana · 🇸🇻 El Salvador · 🇳🇮 Nicaragua · 🇨🇺 Cuba

Cada país tiene grados escolares adaptados al sistema educativo local. La app detecta el país automáticamente.

---

## 🛠️ Stack Tecnológico

| Categoría | Tecnología |
|-----------|------------|
| **Framework** | React Native (Expo SDK 54) |
| **Navegación** | React Navigation (Stack Navigator) |
| **Estado** | React Hooks + Context API |
| **Almacenamiento** | AsyncStorage (récords, historial, sesiones) |
| **Animaciones** | Animated (React Native built-in) |
| **Localización** | expo-localization (detección de país) |
| **Compras** | RevenueCat (react-native-purchases) |
| **Anuncios** | Google AdMob (react-native-google-mobile-ads) |
| **Build** | EAS Build |

---

## 💎 Planes y Precios

### 🆓 Gratis (Para Siempre)
- ✅ Todos los niveles (Inicial → Pre-universitario)
- ✅ 33 operaciones matemáticas
- ✅ Sistema de vidas, combos y estrellas
- ✅ Timer y cronómetro
- ✅ Récords locales por tema
- ✅ Estadísticas y análisis
- ✅ 19 países con grados adaptados
- ✅ Con anuncios (solo entre partidas)

### 👑 Premium
- ✅ **Todo lo del plan Gratis**
- ✦ **Sin anuncios**
- ✦ **Modo Práctica Libre:** Sin timer ni cronómetro, a tu ritmo
- ✦ **Historial Detallado:** Proceso paso a paso de cada pregunta
- ✦ **Modo Repaso:** Practica solo las preguntas que fallaste

| Plan | Precio | Ahorro |
|------|--------|--------|
| Mensual | S/ 21.90/mes | — |
| Anual | S/ 149.90/año | 43% vs mensual |

*Precios en Soles peruanos. Los precios finales pueden variar por país según Google Play.*

---


---

## 🌐 Landing Page (Este Repositorio)

La landing page de SÜRI KŌRE está desarrollada con **Astro** y desplegada en Vercel:

- ✅ Hero section con mago animado
- ✅ Sección de niveles con tarjetas interactivas
- ✅ Listado de funciones con iconos
- ✅ Comparativa de planes (Gratis vs Premium) con precios
- ✅ Sección "Cómo funciona" con pasos
- ✅ Página de Términos y Condiciones completa
- ✅ Página de Política de Privacidad completa
- ✅ Footer con enlaces legales
- ✅ Diseño responsive (mobile-first)
- ✅ Animación de estrellas en canvas

**Ver en vivo:** [surikoreapp.vercel.app](https://surikoreapp.vercel.app/)

---

## 📞 Contacto y Soporte

**Empresa:** Novark Systems

**País:** Perú

**Email general:** contacto@novarksystems.com

**Email legal:** legal@novarksystems.com

**Email privacidad:** privacidad@novarksystems.com

---

## 📄 Licencia

© 2026 Novark Systems. Todos los derechos reservados.

**SÜRI KŌRE** es un producto comercial. La aplicación móvil no es de código abierto. Este repositorio contiene únicamente el código de la landing page web.

---

**🧙 SÜRI KŌRE — Matemáticas Mágicas**

[🌐 Ver Landing Page](https://surikoreapp.vercel.app/) · [📱 Descargar App (Próximamente)](https://play.google.com/store)
