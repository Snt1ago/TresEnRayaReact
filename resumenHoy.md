Descripción --> ¿Qué estoy construyendo?: Estoy creando un juego de tres en raya interactivo con el tutorial de React.

Instrucciones de instalación y uso:
Desafíos que enfrente:

11/8 - comienzo tic tac toe

1. Comence desacrgando, descomprimiendo e importando desde sandbox el ejemplo de react a VSCode, ademas instale sus dependencias con npm install e iniciando el servidor local con npm start.
   problemas: tuve vulnerabilidades al instalar las dependencias.
   solucion: las resolvi forzando el comando que me dio node en la terminal.

2. npm start no me funciona, ademas he analizado el package.json y el script esta definido, tampoco funciono borrando la carpeta node_modules, package-lock.json y reinstalando las dependencias con npm install.
   problema: El problema era que tenía una versión desactualizada o corrupta de react-scripts.
   solucion: Al instalar la versión más reciente con npm install react-scripts@latest se solucionó el conflicto.

descripcion general:
12/8 - leyendo

1. palabras clave export, default, return. ya sabemos como crear un componente y la funcion princiapal.
2. entendiendo el index.js.

construyendo el tablero:
27/8 - elementos JSX

problema: no usar elementos jsx adyacentes, porque da error.
solucion: Para solucionar esto, puedes usar Fragmentos ( <>y </>) para encapsular varios elementos JSX adyacentes.

28/8 - Pasando datos a través de accesorios
solucion:
problema: