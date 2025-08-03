# 🏎️ Campeonato de Karts de Constantinopla 2025

Sitio web oficial del Campeonato de Karts de Constantinopla 2025. Una plataforma moderna y responsive para seguir las clasificaciones, resultados y estadísticas del campeonato.

## 📋 Características

- ✅ **Clasificación en tiempo real** del campeonato
- ✅ **Resultados detallados** de carreras y clasificaciones
- ✅ **Información de circuitos** con estadísticas
- ✅ **Diseño responsive** para móviles y tablets
- ✅ **Interfaz moderna** con animaciones suaves
- ✅ **Datos embebidos** sin dependencias externas

## 🌐 Ver el Sitio Web

**URL del sitio:** [https://tu-usuario.github.io/constantinopla-karts-2025/](https://tu-usuario.github.io/constantinopla-karts-2025/)

## 📊 Sistema de Puntuación

| Posición | Puntos |
|----------|--------|
| 1º       | 10     |
| 2º       | 8      |
| 3º       | 6      |
| 4º       | 5      |
| 5º       | 4      |
| 6º       | 3      |
| 7º       | 2      |
| 8º       | 1      |
| 9º+      | 0      |

## 🏁 Temporada 2025 - Estado Actual

### Clasificación de Pilotos (Después de 1 carrera)
1. **Oscaristo** - 10 puntos
2. **Crosshairs4G63** - 8 puntos
3. **o11ve** - 6 puntos
4. **Ceri** - 5 puntos
5. **JeZzZuZ** - 4 puntos

### Circuitos
- **BeniKarts** ✅ (Completado - Enero 2025)
- Más circuitos por anunciar...

## 🚀 Despliegue en GitHub Pages

### Configuración Inicial

1. **Fork o crea un nuevo repositorio**
   ```bash
   git clone https://github.com/tu-usuario/constantinopla-karts-2025.git
   cd constantinopla-karts-2025
   ```

2. **Estructura de archivos necesaria:**
   ```
   constantinopla-karts-2025/
   │
   ├── index.html          # Página de redirección
   ├── homepage.html       # Página principal
   ├── championship.html   # Clasificación del campeonato
   ├── circuits.html       # Circuitos y resultados
   └── README.md          # Este archivo
   ```

3. **Activar GitHub Pages:**
   - Ve a `Settings` → `Pages`
   - Selecciona `Deploy from a branch`
   - Elige `main` branch y `/ (root)`
   - Guarda los cambios

4. **¡Listo!** Tu sitio estará disponible en unos minutos

## 🔧 Características Técnicas

### Tecnologías Utilizadas
- **HTML5** - Estructura semántica
- **CSS3** - Diseño moderno con gradientes y animaciones
- **JavaScript (Vanilla)** - Funcionalidad sin frameworks
- **PapaParse** - Procesamiento de datos CSV
- **GitHub Pages** - Hosting gratuito

### Compatibilidad
- ✅ Chrome/Edge (últimas versiones)
- ✅ Firefox (últimas versiones)
- ✅ Safari (últimas versiones)
- ✅ Dispositivos móviles iOS/Android

### Rendimiento
- ⚡ Carga rápida (sin dependencias pesadas)
- 📱 Responsive en todos los dispositivos
- 🎨 Animaciones suaves de 60fps
- 🔒 Funciona completamente offline

## 📈 Cómo Actualizar Resultados

### Para añadir una nueva carrera:

1. **Actualizar championship.html:**
   ```javascript
   // Modificar el CSV embebido añadiendo nueva columna
   const championshipCSV = `Driver; Total; Race 01; Race 02
   Oscaristo; 20; 10; 10
   Crosshairs4G63; 16; 8; 8
   ...`;
   ```

2. **Actualizar la tabla HTML:**
   ```html
   <th>Carrera 02</th>
   ```

### Para añadir un nuevo circuito:

1. **En circuits.html, añadir botón:**
   ```html
   <button class="circuit-btn" onclick="showCircuit('nuevo-circuito')">
     Nuevo Circuito
   </button>
   ```

2. **Añadir datos CSV del circuito:**
   ```javascript
   const nuevoCircuitoQualyCSV = `Position; Driver; Best Lap; Gap
   1; Piloto1; 00:45.123; 0.000
   ...`;
   ```

3. **Crear sección HTML correspondiente**

## 🎯 Roadmap

### Próximas Actualizaciones
- [ ] Segunda carrera de la temporada
- [ ] Nuevos circuitos
- [ ] Estadísticas avanzadas de pilotos
- [ ] Gráficos de progresión
- [ ] Historial de temporadas anteriores

### Posibles Mejoras
- [ ] Modo oscuro/claro
- [ ] Notificaciones de nuevos resultados
- [ ] API para datos externos
- [ ] Página de estadísticas individuales
- [ ] Comparativa entre pilotos

## 🤝 Contribuir

¿Quieres contribuir al proyecto? ¡Perfecto!

1. Fork el repositorio
2. Crea una branch para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit tus cambios (`git commit -am 'Añadir nueva funcionalidad'`)
4. Push a la branch (`git push origin feature/nueva-funcionalidad`)
5. Crear un Pull Request

## 📞 Contacto

Para preguntas sobre el campeonato o el sitio web:
- **GitHub Issues:** [Crear una issue](https://github.com/tu-usuario/constantinopla-karts-2025/issues)
- **Sugerencias:** Usa las GitHub Discussions

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

---

**¡Hecho con ❤️ para la comunidad karting de Constantinopla!** 🏁

*Última actualización: Enero 2025*