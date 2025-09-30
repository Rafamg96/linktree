# 🔗 Linktree - Página de Enlaces Profesional

Una aplicación web estática moderna y profesional tipo Linktree, optimizada para GitHub Pages.

## ✨ Características

- 🎨 **Diseño Moderno**: Interfaz limpia y profesional con gradientes y animaciones suaves
- 📱 **Totalmente Responsive**: Adaptado para móviles, tablets y escritorio
- ⚡ **Rendimiento Óptimo**: Página estática sin dependencias externas
- 🎭 **Animaciones Fluidas**: Efectos visuales atractivos con CSS puro
- ♿ **Accesible**: Cumple con estándares de accesibilidad web
- 🎯 **Fácil Personalización**: Código limpio y bien organizado

## 🚀 Inicio Rápido

### Despliegue en GitHub Pages

Este repositorio incluye un workflow de GitHub Actions que despliega automáticamente tu sitio a GitHub Pages cuando haces push a la rama `main`.

1. **Fork este repositorio** o clónalo a tu cuenta de GitHub

2. **Activa GitHub Pages**:
   - Ve a Settings → Pages
   - En "Source" selecciona "GitHub Actions"
   - El despliegue se realizará automáticamente con cada push a `main`

3. **Personaliza tu contenido** editando `index.html`:
   - Cambia el título, nombre y biografía
   - Actualiza la imagen de perfil (línea 17)
   - Modifica los enlaces a tus redes sociales
   - Añade o elimina tarjetas de enlaces según necesites

4. **Personaliza los colores** (opcional) en `styles.css`:
   ```css
   :root {
       --primary-color: #6366f1;    /* Color primario */
       --secondary-color: #8b5cf6;  /* Color secundario */
   }
   ```

5. **Haz commit y push** de tus cambios:
   ```bash
   git add .
   git commit -m "Personalizar sitio"
   git push
   ```

6. Tu sitio estará disponible en: `https://tu-usuario.github.io/linktree/`

## 📝 Personalización

### Cambiar la Imagen de Perfil

Opción 1 - Usar una URL externa:
```html
<img src="https://tu-imagen.com/foto.jpg" alt="Profile Picture" id="profile-img">
```

Opción 2 - Usar una imagen local:
1. Añade tu imagen al repositorio (por ejemplo, `avatar.jpg`)
2. Actualiza la ruta:
```html
<img src="avatar.jpg" alt="Profile Picture" id="profile-img">
```

### Añadir Nuevos Enlaces

Copia este código dentro de la sección `.links`:

```html
<a href="https://tu-enlace.com" class="link-card" target="_blank" rel="noopener noreferrer">
    <span class="link-icon">🎯</span>
    <span class="link-text">Texto del Enlace</span>
</a>
```

### Personalizar Redes Sociales

Actualiza los atributos `href` de los iconos sociales con tus perfiles:

```html
<a href="https://github.com/tu-usuario" class="social-icon" aria-label="GitHub" target="_blank" rel="noopener noreferrer">
```

## 🎨 Estructura del Proyecto

```
linktree/
│
├── index.html          # Página principal
├── styles.css          # Estilos y diseño
└── README.md          # Documentación
```

## 🛠️ Tecnologías

- HTML5
- CSS3 (Grid, Flexbox, Animaciones)
- No requiere JavaScript ni frameworks

## 🌈 Paleta de Colores

El diseño utiliza un esquema de colores moderno basado en púrpura/índigo:

- **Gradiente de fondo**: `#667eea` → `#764ba2`
- **Color primario**: `#6366f1` (Índigo)
- **Color secundario**: `#8b5cf6` (Púrpura)

Puedes personalizar estos colores en las variables CSS del archivo `styles.css`.

## 📱 Responsive Design

El sitio es totalmente responsive con breakpoints en:
- 📱 Móvil: < 480px
- 📱 Tablet: < 640px
- 💻 Desktop: > 640px

## ♿ Accesibilidad

- Etiquetas ARIA para lectores de pantalla
- Alto contraste de colores
- Navegación por teclado
- Soporte para `prefers-reduced-motion`

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si encuentras un bug o tienes una sugerencia:

1. Haz fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Haz commit de tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📞 Soporte

Si tienes preguntas o necesitas ayuda, abre un issue en el repositorio.

---

⭐ Si te gusta este proyecto, ¡dale una estrella en GitHub!

Hecho con ❤️ por [Tu Nombre]