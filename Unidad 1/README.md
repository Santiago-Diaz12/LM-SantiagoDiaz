# Documentación UD1 Lenguajes de Marcas
## Introduccion a Lenguajes de marcas
### Definición 

Un lenguaje de marcas organiza informacion mediante una sintaxis basada en marcas o etiquetas

### Clasificacion de Lenguajes de marcas

|Tipo|Uso|Ejemplos|
|----|---|--------|
|Presentación|Dar formato a los documentos de texto|HTML, CSS|
|Intercambio de información|Almacenar información de forma ordenada|XML, RSS|
|Documentación|Documentar proyectos|Markdown, WikiTex |

## Instalacion y configuración del entorno

1. Instalamos [VS Code](https://code.visualstudio.com)
2. Instalamos Plugins 
    - [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
    - [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)
     - [Markdown All in one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
     - [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)
  

### Plugins


|Nombre|Foto|Uso|
|------|----|----|
|HTML CSS Support|![html css](https://w7.pngwing.com/pngs/423/47/png-transparent-css-cascading-style-sheets-frontend-web-design-html-styling-3d-icon.png)|sirve para ofrecer autocompletado inteligente de clases, IDs y etiquetas de HTML en hojas de estilo CSS, y viceversa.|
|Live Preview|![LivePreview](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRXAebGWeujxJPlWMKsviLLlD9uT1x93A32JmAX_dzxIQ&s=10)|sirve para ver los cambios de tus páginas web en tiempo real sin salir del editor o usando un navegador integrado|
|Markdown All in One|![Markdown All in One](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRIM6bLfgcIwE0u2AOByahzTW6LL6kH0X8Lz3ecSx3FKg&s=10)|se usa para mejorar y acelerar la escritura de archivos en formato Markdown|
|XML|![XML](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQb4UxIlLe5jls6nXUhn2LVphePLlz3N-kuCpez6CaLTg&s=10)| se usa para mejorar la escritura de documentos en este formato, ayudándote a evitar errores de sintaxis.|
1. Instalamos git hub
```bash
sudo apt install git
```
2. Configurar repositorio git (en la carpeta principal del proyecto)
```bash
git init
git add .
git commit -m "comentario descriptivo"
```
3. conectar con Github
```bash
git remote add origin https://github.com/Santiago-Diaz12/LM-SantiagoDiaz.git
git branch -M main
git push -u origin main
```