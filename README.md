# CODER CLON

Sitio de práctica para el curso de Desarrollo Web en Corderhouse.

Tecnologías utilizadas:

- HTML (semántico)
- CSS
  - Flex
  - Grid
  - Transition
  - Media queries
  - Pseudoclases y pseudoelementos
- Metodología BEM
- Git
- Github / Github pages
- SEO onpage básico
- SASS
  - Variables y mapas
  - Anidamientos (nesting y &)
  - extend
  - mixin e include
  - each

## Configuración de SASS (NodeJS)

Instalación del módulo node-sass:

`npm install -D node-sass`

Script en archivo package.json:

`"build-sass": "node-sass --include-path scss ./scss/style.scss ./css/style.css -w"`

Correr el script para procesar el archivo de entrada y generar el archivo de salida:

`npm run build-sass`

Por buena práctica la carpeta **node_modules** se agrega a la lista del archivo **.gitignore** para evitar que sea subida al repositorio remoto, ya que esta puede ser reconstruida facilmente con el comando:

`npm install`
