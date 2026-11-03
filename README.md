# Aula: Historia, Valenciano y Física

Tres webs de estudio y una portada común. No requiere instalación, servidor propio ni compilación.

## Probar antes de subir

Abre index.html con Chrome, Edge o Firefox. Cada tarjeta abre una asignatura en otra pestaña.
Conserva juntos los cuatro archivos HTML. Las actividades no necesitan conexión; los enlaces de consulta sí.

## Subir a GitHub y publicar la web

1. Extrae este ZIP en tu ordenador. Sube su contenido, no el ZIP.
2. En https://github.com inicia sesión y pulsa + > New repository.
3. Pon un nombre, por ejemplo aula-estudio. Para usar GitHub Pages con GitHub Free, elige Public.
4. Activa Add README y pulsa Create repository.
5. En el repositorio, pulsa Add file > Upload files. Arrastra index.html, historia.html,
   valenciano.html, fisica.html, README.md y .nojekyll. Si no ves .nojekyll en Windows,
   puedes omitirlo: estas páginas HTML también funcionan sin él.
6. Escribe un mensaje como «Añadir webs de estudio» y confirma con Commit changes
   (o Propose changes si la interfaz lo indica; en ese caso completa la propuesta).
7. Comprueba que index.html está directamente en la raíz del repositorio, junto a los otros HTML.
   No debe quedar dentro de una carpeta adicional llamada aula-estudio.
8. Abre Settings > Pages. En Build and deployment, elige Source: Deploy from a branch.
9. Selecciona la rama main y la carpeta /(root). Pulsa Save.
10. Espera a que termine la publicación. En Settings > Pages aparecerá Visit site.
    Puede tardar hasta 10 minutos. La dirección normalmente tendrá esta forma:
    https://TU-USUARIO.github.io/aula-estudio/
    Cambia TU-USUARIO y aula-estudio por los tuyos; el enlace real lo muestra GitHub.

## Archivos

- index.html: portada con acceso a las tres asignaturas.
- historia.html: Historia de España (tarjetas, respuesta larga, crucigramas y cronología).
- valenciano.html: fonética, pronoms febles y Mercè Rodoreda.
- fisica.html: IonLab actualizado, con selector de velocidades y regla del tornillo.
- .nojekyll: indica que la web ya está preparada como HTML estático.
- README.md: estas instrucciones.

## Actualizar una asignatura

En GitHub, usa Add file > Upload files para sustituir el HTML correspondiente con el mismo
nombre. Confirma el cambio. Pages publicará la actualización automáticamente.
Si conservas los nombres de archivo, la portada seguirá funcionando. Para ver una actualización
que no aparece, prueba Ctrl+F5 o una ventana privada.

## Si aparece un error 404

Comprueba que index.html está en la raíz y se escribe exactamente así, en minúsculas.
Revisa que Pages use main y /(root). Consulta Actions para ver si el despliegue ha terminado.
Mantén los nombres historia.html, valenciano.html y fisica.html en minúsculas.

## Fuentes de las instrucciones

- Crear un sitio: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- Configurar publicación: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- Subir archivos: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
