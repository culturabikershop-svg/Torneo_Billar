# 🎱 Gestor de Torneo de Billar a 3 Bandas

Sistema integral, interactivo y autónomo (Single-File App) para la organización, administración, seguimiento en vivo y premiación oficial de campeonatos de billar a tres bandas.

Diseñado para funcionar sin depender de servidores externos, guardando los datos en tiempo real mediante almacenamiento local (`localStorage`) y optimizado para usarse en computadoras de sala, televisores de proyección o dispositivos móviles (Android / iOS).

---

## 🚀 Características Principales

### 1. Inscripción y Reglas de Juego
- Registro individual o masivo de participantes (un clic para cargar listas completas).
- Soporte para **Metas de Distancia / Hándicap** personalizadas por jugador.
- Sorteo automático y balanceado de grupos según la cantidad de integrantes elegida.

### 2. Control de Mesas y Partidas
- Marcador en vivo de carambolas, entradas y mayor serie (HS) por partido.
- Fijación de entradas límite de forma global para agilizar la fase clasificatoria.
- **Botón de Forfeit (W.O.):** Opción inmediata para declarar incomparecencia por jugador tanto en grupos como en eliminación directa.

### 3. Pizarra Digital de Sala
- Vista condensada de grupos y participantes diseñada para proyectar en pantallas o Smart TVs.
- Modo de **Pantalla Completa** integrado.

### 4. Cuadro de Eliminación Directa (Playoffs KO)
- Clasificación automática basada en victorias, promedio general puro y mayor serie.
- Generación de llaves desde 32avos hasta la Gran Final.
- Programación de fecha, horario y mesa por encuentro.
- Reconocimiento automático de **ambos semifinalistas como 3.er Lugar Compartido**.

### 5. Premiación Oficial y Diplomas
- Generación automática de certificados oficiales de honor para:
  - 🥇 **1.° Lugar:** Campeón
  - 🥈 **2.° Lugar:** Subcampeón
  - 🥉 **3.° Lugar (A):** Semifinalista 1
  - 🥉 **3.° Lugar (B):** Semifinalista 2
- Acabados ceremoniales diferenciados (Oro, Plata y Bronce) con logotipo oficial del club.
- Salida directa para impresión o guardado en formato PDF (hoja horizontal/landscape).

### 6. ⭐ Ranking Histórico Acumulado
- Permite cerrar cada torneo y acumular puntos y estadísticas a lo largo de toda la temporada.
- Sistema de puntuación por circuito:
  - Campeón: +100 pts
  - Subcampeón: +70 pts
  - Semifinalistas (3.os lugares): +50 pts c/u
  - Puntos por participación y partidos ganados.
- Tabla histórica ordenada de mejor a peor según puntos, promedio puro y títulos obtenidos.

### 7. Integración con WhatsApp y Respaldo de Datos
- **Copia directa al portapapeles:** Botones de captura optimizados para Pizarra, Tabla de Grupos (en bloques de 4), Cuadro KO por rondas legibles en celular y Ranking. Con un clic queda copiado para pegar (`Ctrl + V`) en cualquier chat o grupo de WhatsApp.
- **Exportación / Importación completa en JSON:** Respaldo y restauración total de la base de datos del torneo.
- **Exportación a Excel (.CSV):** Descarga estructurada de las clasificaciones del torneo y del ranking histórico.

---

## 📲 Cómo Usar e Instalar en el Celular (PWA)

Esta aplicación puede agregarse directamente a la pantalla de inicio de cualquier teléfono inteligente sin pasar por tiendas de aplicaciones:

### En iPhone (iOS - Safari):
1. Abre el enlace de GitHub Pages en **Safari**.
2. Toca el botón **Compartir** (icono de cuadrado con una flecha hacia arriba).
3. Selecciona la opción **"Agregar a pantalla de inicio"**.

### En Android (Google Chrome):
1. Abre el enlace de GitHub Pages en **Google Chrome**.
2. Toca los tres puntos en la esquina superior derecha.
3. Elige **"Instalar aplicación"** o **"Agregar a la pantalla principal"**.

---

## 🛠️ Tecnologías Utilizadas
- **HTML5 Semántico**
- **CSS3 Moderno** (Diseño responsivo, Grid, Flexbox y temas oscuros de alto contraste)
- **JavaScript Vanilla (ES6+)**
- **html2canvas** (Renderizado y captura de pantalla en alta resolución)
- **Web Storage API** (`localStorage` para persistencia de datos local)
- **Async Clipboard API** (Copia binaria de imágenes PNG al portapapeles)

---

## 📄 Licencia
Este proyecto es de uso libre para la administración de eventos y torneos de clubes de billar.
