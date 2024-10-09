# Manage Pro

Este repositorio contiene el código fuente para Manage Pro que se despliega en GitHub Pages.


## Descripción de Archivos y Directorios

- **.github/workflows/static.yml**: Configuración del flujo de trabajo para desplegar el contenido estático en GitHub Pages.
- **about/**: Contiene páginas relacionadas con la sección "Acerca de".
- **assets/**: Directorio para recursos estáticos como imágenes y otros archivos multimedia.
- **auth/**: Contiene páginas de autenticación como login y signup.
- **css/**: Archivos de estilos CSS para diferentes partes del sitio web.
- **index.html**: Página principal del sitio web.
- **pages/**: Contiene varias páginas del sitio web relacionadas con servicios y capacitación.
- **testimonials.html**: Página de testimonios.
- **us.html**: Página "Nosotros".
- **user.html**: Página de perfil de usuario.

## Despliegue

Este proyecto utiliza GitHub Actions para desplegar automáticamente el contenido estático en GitHub Pages. El flujo de trabajo está definido en [`.github/workflows/static.yml`](.github/workflows/static.yml).

### Pasos del Flujo de Trabajo

1. **Checkout**: Se clona el repositorio.
2. **Setup Pages**: Configura GitHub Pages.
3. **Upload artifact**: Sube todo el contenido del repositorio como un artefacto.
4. **Deploy to GitHub Pages**: Despliega el contenido en GitHub Pages.

## Cómo Contribuir

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva funcionalidad'`).
4. Sube tus cambios a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT.