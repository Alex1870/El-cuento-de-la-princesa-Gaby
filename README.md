# El libro de la princesa Gaby

Un libro web estático hecho con HTML, CSS y JavaScript, preparado para GitHub Pages.

## Qué incluye

- Portada de cuento de hadas con puertas de castillo que se abren.
- Libro con páginas separadas: portada, dedicatoria, capítulos, recuerdos fotográficos individuales y epílogo.
- Cada fotografía tiene su propia página con palabras cariñosas.
- Navegación con botones, teclado (flechas izquierda/derecha) y gesto de deslizamiento en móvil.
- Índice del cuento para saltar a los capítulos.
- Estrellas, pétalos y pequeños destellos.
- Dedicatoria personalizada para Gaby antes de entrar al libro.
- Flores interactivas que florecen al tocarlas y muestran deseos.
- Tres sobres de cartas sorpresa que se abren al tocarlos y muestran una carta en una ventana emergente.
- Sorpresa final interactiva al llegar al epílogo.
- Diseño adaptable a móvil y escritorio, con respeto por la preferencia de movimiento reducido.

## Probar

Abra `index.html` en un navegador moderno. Mantenga la carpeta `assets` junto a este archivo.

## Publicar en GitHub Pages

1. Cree un repositorio en GitHub.
2. Suba `index.html`, `README.md` y la carpeta `assets` a la raíz.
3. Abra **Settings → Pages**.
4. En **Build and deployment**, seleccione **Deploy from a branch**.
5. Elija la rama `main` y la carpeta `/ (root)`, y guarde.

## Privacidad

El proyecto contiene fotografías personales. Si el repositorio es público, cualquiera podrá ver y descargar las imágenes. Publique las fotografías solo con el consentimiento de Gaby; si no, mantenga el repositorio privado.

## Personalización

Los textos están dentro de `index.html`. Cada fotografía tiene una página individual. Las imágenes están en `assets/`.

- Misterio progresivo de la llave dorada: cuatro pistas interactivas repartidas por el cuento y un tesoro final que se desbloquea al reunirlas.

## Final del cuento (versión 7)

- El epílogo y el tesoro desbloqueado ofrecen **Volver a leer** y **Cerrar el cuento**.
- **Volver a leer** reinicia la experiencia desde las puertas del castillo y la dedicatoria.
- **Cerrar el cuento** abre una despedida final con una opción de volver al epílogo.
- **Cierre del cuento** muestra una despedida final con un mensaje cálido y la opción de volver a leer. El navegador no permite que una página cierre de forma fiable una pestaña abierta manualmente; por eso la despedida indica que la lectora puede cerrar la pestaña cuando quiera.
